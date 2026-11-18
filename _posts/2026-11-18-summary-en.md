---
layout: default
title: "Horizon Summary: 2026-11-18 (EN)"
date: 2026-11-18
lang: en
---

> From 24 items, 17 important content pieces were selected

---

1. [Wiz Discloses Pre-Auth RCE in Nginx HTTP/2 Handling](#item-1) ⭐️ 9.0/10
2. [Java4Shell: Critical RCE in OpenJDK via Base64 Decoding](#item-2) ⭐️ 9.0/10
3. [Google's AI answers reportedly cut search traffic by 40%](#item-3) ⭐️ 8.0/10
4. [Microsoft's ONNX Runtime repository vanishes from GitHub amid supply-chain fears](#item-4) ⭐️ 8.0/10
5. [Harvard researchers find AI coding agents shifted the bottleneck to code review](#item-5) ⭐️ 8.0/10
6. [Simon Willison and Prime Radiant introduce external sandbox pattern for coding agents](#item-6) ⭐️ 8.0/10
7. [OpenAI Releases GPT-6.2 Astra and Sol with Major Price Cuts](#item-7) ⭐️ 8.0/10
8. [Datasette Lite rewritten to run full server-side app in browser](#item-8) ⭐️ 8.0/10
9. [Quad9 Exits France Over DNS Blocking Order](#item-9) ⭐️ 7.0/10
10. [Energy-Based Reasoners claim 385x more efficient inference than LLMs](#item-10) ⭐️ 7.0/10
11. [IRS sign-in via ID.me sparks privacy and accessibility backlash](#item-11) ⭐️ 7.0/10
12. [Phrack Issue 73 Released with Docker Escape Exploit](#item-12) ⭐️ 7.0/10
13. [curl Maintainer Questions AI Rust Rewrites Amid 200+ Real Bugfixes](#item-13) ⭐️ 7.0/10
14. [Inside-DB Website Compiles Deutsche Bank Scandals, Sparks Hacker News Discussion](#item-14) ⭐️ 6.0/10
15. [Energy drinks linked to 11 times more cardiac arrest reports in FDA database](#item-15) ⭐️ 6.0/10
16. [Blog questions why Gemini 4 Carbon is slow; HN debates efficiency](#item-16) ⭐️ 6.0/10
17. [Archive Team Preserves Apple Support Community Before 2026 Closure](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Wiz Discloses Pre-Auth RCE in Nginx HTTP/2 Handling](https://www.wiz.io/blog/nginx-http2-rce-vulnerabilities) ⭐️ 9.0/10

Wiz researchers disclosed pre-authentication remote code execution vulnerabilities in nginx's HTTP/2 implementation, with the fix having landed in the open-source repository a week before the public notice. Given nginx's massive deployment as a web server and reverse proxy, a pre-auth RCE poses severe real-world risk, and the disclosure timeline gap may have allowed attackers to exploit the flaw before defenders could patch. The vulnerability is an integer underflow in HTTP/2 frame processing, and a simple workaround is to disable HTTP/2; the commit message reportedly included 'Reported by Xint.io', hinting at the reporting party.

hackernews · speedping · Nov 18, 15:19 · [Discussion](https://news.ycombinator.com/item?id=50547374)

**Background**: HTTP/2 is a major revision of the HTTP protocol that improves performance via multiplexing and header compression, and nginx is one of the most widely used web servers and reverse proxies. Pre-authentication RCE means an attacker can execute arbitrary code without needing valid credentials, making it especially dangerous. Integer underflow occurs when a calculation produces a value smaller than the minimum representable, often leading to memory corruption.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/vlet/p5-Protocol-HTTP2">GitHub - vlet/p5-Protocol- HTTP 2 : HTTP / 2 protocol implementation ...</a></li>
<li><a href="https://javaee.github.io/grizzly/http2.html">Project Grizzly - HTTP / 2 Overview</a></li>

</ul>
</details>

**Discussion**: Commenters criticized the disclosure practice, noting the fix was public for a week before the advisory, and debated migrating to HTTP/3 instead of reverting to HTTP/1.1; some expressed alarm over the scale of potential compromise, while others pointed to integer underflow as a recurring class of bug that languages should trap.

**Tags**: `#security`, `#nginx`, `#http2`, `#vulnerability`, `#rce`

---

<a id="item-2"></a>
## [Java4Shell: Critical RCE in OpenJDK via Base64 Decoding](https://calif.io/java4shell/) ⭐️ 9.0/10

Security researchers at Calif disclosed Java4Shell (CVE-2026-114938), a critical remote code execution vulnerability in OpenJDK's optimized AVX-512 Base64 decoder that allows malformed Base64 input to corrupt memory and execute arbitrary code. The exploit uses a novel heap grooming technique over the network, achieving reliable remote exploitation under stable network conditions. This vulnerability affects a vast number of Java-based servers and applications, potentially allowing attackers to take full control of vulnerable systems. Its high severity (CVSS 9.2) and the ease of triggering via Base64 input make it a significant threat to the Java ecosystem, prompting urgent patching and detection efforts. The vulnerability specifically affects OpenJDK builds using the HotSpot VM with AVX-512 support, while OpenJ9 and GCJ are not affected. Exploitation requires precise heap grooming and is sensitive to network latency and jitter, but the researchers demonstrated successful attacks over the public internet.

hackernews · werrett · Nov 17, 21:11 · [Discussion](https://news.ycombinator.com/item?id=50538240)

**Background**: OpenJDK is the open-source implementation of the Java platform, widely used in enterprise servers and cloud environments. Base64 is a common encoding scheme for binary data, often used in web applications for transmitting images, files, and authentication tokens. Heap grooming (or heap feng shui) is an exploitation technique that manipulates memory allocation patterns to place controlled data at predictable locations, facilitating code execution.

<details><summary>References</summary>
<ul>
<li><a href="https://calif.io/java4shell/">Java 4 Shell : Write once, RCE everywhere</a></li>
<li><a href="https://www.wiz.io/blog/cve-2026-114938-rce-java4shell-openjdk">CVE-2026-114938 OpenJDK RCE ( Java 4 Shell ): Everything... | Wiz Blog</a></li>
<li><a href="https://www.sentinelone.com/blog/java4shell-vulnerability-in-openjdk-enables-rce-on-avx-512-cpus/">Defending Against Java 4 Shell : Vulnerability in OpenJDK Enables...</a></li>

</ul>
</details>

**Discussion**: Commenters praised the sophistication of the exploit and noted that despite specific conditions, many hosts will be impacted. Semgrep published free detection scripts, and discussion highlighted the Eclipse Foundation's lack of advance notice for CVEs, raising concerns about coordinated disclosure and the need for modernization.

**Tags**: `#security`, `#Java`, `#vulnerability`, `#RCE`, `#OpenJDK`

---

<a id="item-3"></a>
## [Google's AI answers reportedly cut search traffic by 40%](https://revscope.co/blog/search-seo-geo-2026/) ⭐️ 8.0/10

A blog post from RevScope reports that Google's AI-generated answers are reducing search traffic by 40%, citing industry observations and sparking a debate on Hacker News with 642 points and 490 comments. This matters because a 40% drop in search traffic could fundamentally disrupt the open web's content ecosystem, affecting publishers, SEO professionals, and anyone who relies on search-driven discovery. The 40% figure is reportedly an estimate from industry analysis, not an official Google statistic, and the actual impact may vary by query type and industry; Google's AI Overviews, launched in May 2024, have already been linked to traffic declines by 39% of marketers in surveys.

hackernews · slashdev · Nov 18, 00:17 · [Discussion](https://news.ycombinator.com/item?id=50540178)

**Background**: Google's AI Overviews are AI-generated summaries that appear at the top of search results, answering queries directly without requiring users to click through to websites. SEO (Search Engine Optimization) is the practice of optimizing content to rank higher in search results, and the rise of AI answers threatens the traditional click-based model that many websites depend on for traffic and revenue.

<details><summary>References</summary>
<ul>
<li><a href="https://www.contentgrip.com/google-search-market-share-decline/">Google vs AI search : is Google ’s dominance fading?</a></li>
<li><a href="https://searchengineland.com/guide/what-is-seo">What Is SEO - Search Engine Optimization ?</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree that AI answers provide a better user experience by eliminating clickbait and SEO-optimized fluff, but some mourn the loss of serendipitous discovery on the open web. A few note that the shift away from traditional search was already underway before AI, and that Google's move is a defensive response to other LLMs.

**Tags**: `#AI`, `#search`, `#SEO`, `#web`, `#Google`

---

<a id="item-4"></a>
## [Microsoft's ONNX Runtime repository vanishes from GitHub amid supply-chain fears](https://github.com/microsoft/onnxruntime) ⭐️ 8.0/10

Microsoft's ONNX Runtime repository, a widely used machine learning runtime, has disappeared from GitHub, with the URL now returning an error. The disappearance coincides with reports that Microsoft's Agent Framework PyPI package was compromised, leading the community to speculate about a possible supply-chain attack. ONNX Runtime is a critical dependency for many AI applications, and its sudden removal could disrupt countless projects and raise serious concerns about the security of Microsoft's open-source supply chain. If linked to a compromise, this event could erode trust in widely used packages and prompt a broader review of security practices. The repository's disappearance follows the compromise of the Microsoft Agent Framework PyPI package, as reported by security firm Socket, though Microsoft has not confirmed a connection. Community members also note that ONNX Runtime includes telemetry that is enabled by default and can only be disabled by building from source.

hackernews · nvader · Nov 17, 23:18 · [Discussion](https://news.ycombinator.com/item?id=50539610)

**Background**: ONNX Runtime is an open-source runtime accelerator for machine learning models, developed by Microsoft and widely used to deploy models across different hardware and platforms. Supply-chain attacks, where malicious code is injected into trusted software packages, have become increasingly common in open-source ecosystems, as seen in recent npm and PyPI incidents.

<details><summary>References</summary>
<ul>
<li><a href="https://socket.dev/pypi/package/agent-framework">agent - framework - PyPI Package Security Analysis - Socket</a></li>
<li><a href="https://grokipedia.com/page/ONNX_Runtime">ONNX Runtime</a></li>

</ul>
</details>

**Discussion**: Commenters speculate that the disappearance is linked to the compromise of Microsoft's Agent Framework PyPI package, with some suggesting Microsoft may be cleaning up affected repositories. Others raise concerns about ONNX Runtime's default telemetry and discuss broader supply-chain risks, including backdoored models and similar issues in other projects like Immich.

**Tags**: `#supply-chain-security`, `#onnx-runtime`, `#microsoft`, `#github`, `#open-source-security`

---

<a id="item-5"></a>
## [Harvard researchers find AI coding agents shifted the bottleneck to code review](https://complexdiscovery.com/harvard-researchers-find-ai-coding-agents-shifted-the-bottleneck-to-code-review/) ⭐️ 8.0/10

Harvard researchers report that AI coding agents have moved the engineering bottleneck from writing code to reviewing it, sparking practitioner discussion about review fatigue, overdesigned solutions, and lost code ownership. This finding highlights a major shift in software development workflows, where AI-generated code increases review load and may require new processes and tools to maintain code quality and developer well-being. The research is based on practitioner observations and aligns with industry telemetry showing a 441.5% increase in median pull request review time, though the study's conclusions may lag behind the fast-paced evolution of AI models.

hackernews · judahmeek · Nov 17, 21:16 · [Discussion](https://news.ycombinator.com/item?id=50538303)

**Background**: AI coding agents are tools that use large language models to autonomously generate and modify code. As these agents become more capable, developers increasingly delegate coding tasks to them, producing large volumes of code that must be reviewed by humans. Code review is a standard practice in software engineering to catch bugs and ensure quality, but the surge in AI-generated code has overwhelmed traditional review processes.

<details><summary>References</summary>
<ul>
<li><a href="https://zandigital.in/code-review-bottleneck-ai">Code Review Is the Bottleneck : Time in Review Up 441%</a></li>
<li><a href="https://news.ycombinator.com/item?id=50538303">Harvard researchers find AI coding agents shifted the bottleneck to...</a></li>
<li><a href="https://www.zdnet.com/article/will-ai-replace-software-engineers-it-depends-on-who-you-ask/">Will AI replace software engineers ? It depends on who you... - ZDNET</a></li>

</ul>
</details>

**Discussion**: Practitioners on Hacker News shared mixed feelings: some noted AI now reviews code better than humans, while others complained of review fatigue and overdesigned solutions. A key concern was that as developers lose code ownership, fewer will be qualified or willing to review, with some suggesting dropping code reviews altogether.

**Tags**: `#AI coding agents`, `#code review`, `#software engineering`, `#developer productivity`, `#AI research`

---

<a id="item-6"></a>
## [Simon Willison and Prime Radiant introduce external sandbox pattern for coding agents](https://simonwillison.net/2026/Nov/17/external-sandboxes-for-coding-agents/) ⭐️ 8.0/10

Simon Willison and Prime Radiant released three sandbox server implementations (external-sandbox-v86, external-sandbox-container, and external-sandbox-quicksand) that follow an 'external sandbox' pattern, where agent-executed code runs in a dedicated sandbox separate from the agent itself. Each implementation exposes the same localhost API, allowing tools like Pi, Claude Code, and Codex to send code execution requests to the sandbox. This pattern addresses a critical security gap in AI coding agents: by isolating code execution from the agent, it reduces the risk of prompt injection attacks or agent mistakes causing damage to the host machine. It enables safer experimentation with local models and provides a reusable architecture for agent safety. The three implementations use different isolation technologies: v86 runs Alpine Linux in WebAssembly via a Node.js server, the container version uses Apple Containers, and the Quicksand version bundles QEMU and Alpine Linux in a Python package. All include an optional HTTP/HTTPS allow-list proxy and a credential replacement mechanism to make authenticated API calls without exposing secrets to the agent.

rss · Simon Willison · Nov 17, 22:52

**Background**: Prompt injection is an attack where malicious input manipulates an LLM into performing unintended actions, and in agentic settings, the attacker can inherit the agent's permissions. Sandboxing is a security technique that runs untrusted code in an isolated environment to prevent it from affecting the host system. The external sandbox pattern separates the agent (which may be compromised) from the code execution environment, adding a layer of defense.

**Tags**: `#ai-agents`, `#sandboxing`, `#security`, `#prompt-injection`, `#llm-safety`

---

<a id="item-7"></a>
## [OpenAI Releases GPT-6.2 Astra and Sol with Major Price Cuts](https://simonwillison.net/2026/Nov/17/gpt62-astra-and-sol/) ⭐️ 8.0/10

OpenAI released GPT-6.2 Astra, a new frontier model for complex tasks, and GPT-6.2 Sol, an efficient everyday model, available via API as gpt-6.2-astra and gpt-6.2-sol. Astra is priced at 80% of its predecessor at $8/MTok input and $40/MTok output, with cached tokens at $0.40/MTok, while Sol remains at $2/$10 per MTok. The significant price reduction, especially the steep discount on cached tokens, makes long-running agentic sessions much more affordable and could accelerate adoption of AI agents. The move also reflects intensifying price competition among frontier model providers like OpenAI and Anthropic. Astra's cached input price of $0.40/MTok is a 60% reduction from the previous model's $1/MTok, which is particularly beneficial for agentic workloads that repeatedly process the same context. Simon Willison shipped LLM 0.38 with support for the new models, and his pelican benchmark shows Astra producing more detailed images at higher effort levels.

rss · Simon Willison · Nov 17, 22:38

**Background**: OpenAI's GPT-6.2 series are large language models accessed via API, with pricing measured per million tokens (MTok). Cached tokens refer to previously processed input that can be reused at a discount, which is important for agentic applications that maintain long contexts. Simon Willison's LLM is a command-line tool and Python library for interacting with various LLMs, and its 0.38 release adds support for these new models.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Nov/2/llm/">Release: llm 0 .37 | Simon Willison ’s Weblog</a></li>
<li><a href="https://fiscallm.com/llm-pricing">LLM API pricing compared: cost per message and per user...</a></li>
<li><a href="https://www.cloudzero.com/blog/claude-pricing/">Claude pricing in 2026: every plan, API rate, and what it costs</a></li>

</ul>
</details>

**Tags**: `#openai`, `#llm`, `#model-release`, `#pricing`, `#api`

---

<a id="item-8"></a>
## [Datasette Lite rewritten to run full server-side app in browser](https://simonwillison.net/2026/Nov/17/datasette-lite/) ⭐️ 8.0/10

Simon Willison has released a complete rewrite of Datasette Lite that uses service workers and Pyodide to run the full server-side Datasette Python application directly in the browser, making it nearly indistinguishable from the real application. This demonstrates a novel approach to running Python applications client-side with full plugin support, version selection, and SQLite flexibility, which is valuable for developers interested in WebAssembly, Pyodide, and browser-based tooling. Users can load any SQLite database, JSON, CSV, or SQL script; select from over 100 SQLite versions; load specific Datasette versions, commits, tags, or branches from PyPI or GitHub; and install additional plugins from PyPI or wheel URLs, all via crafted URLs to lite.datasette.io.

rss · Simon Willison · Nov 17, 16:48

**Background**: Datasette is an open-source Python tool for exploring and publishing data, typically run as a server-side application. Pyodide is a port of CPython to WebAssembly that allows Python packages to run in the browser, and service workers act as proxy servers between the web app and the network, enabling offline capabilities and request interception. Datasette Lite combines these technologies to provide a serverless, client-side version of Datasette.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/pyodide/pyodide">GitHub - pyodide / pyodide : Pyodide is a Python distribution for the...</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API">Service Worker API - Web APIs | MDN</a></li>
<li><a href="https://github.com/simonw/datasette">GitHub - simonw/ datasette : An open source multi-tool for exploring and...</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#pyodide`, `#webassembly`, `#service-workers`, `#python-in-browser`

---

<a id="item-9"></a>
## [Quad9 Exits France Over DNS Blocking Order](https://techstackups.com/articles/quad9-leaves-france-dns-blocking/) ⭐️ 7.0/10

Quad9, a privacy-focused public DNS resolver, announced it is withdrawing its services from France after a French court order required it to block piracy-related domains. The decision follows a ruling that for the first time upheld the obligation of DNS resolvers to block pirated sites under French law. This case sets a precedent for holding neutral DNS infrastructure liable for content enforcement, which could pressure other resolvers like Cloudflare and Google to either comply or exit markets. It highlights the growing tension between copyright enforcement and the open, privacy-preserving architecture of the internet. The blocking order stems from a French court's interpretation of Article L.333-10, which allows rights holders to request site blocking; the list of blocked domains has grown from six to over 118. Quad9 argues it cannot reliably identify French users, raising questions about how it will enforce the withdrawal.

hackernews · ritzaco · Nov 18, 13:18 · [Discussion](https://news.ycombinator.com/item?id=50545958)

**Background**: DNS resolvers like Quad9 (9.9.9.9) translate human-readable domain names into IP addresses and are typically designed to be neutral and privacy-preserving. France has increasingly used DNS blocking as a tool to combat online piracy, requiring ISPs and sometimes third-party resolvers to block access to infringing sites. Quad9, operated by the Quad9 Foundation in Switzerland, has a founding charter that prioritizes user privacy and security.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Quad9">Quad9 - Wikipedia</a></li>
<li><a href="https://gigazine.net/gsc_news/en/20260403-pirate-france/">Google, Cloudflare, and Cisco's claims in a French piracy ... - GIGAZINE</a></li>
<li><a href="https://torrentfreak.com/inside-a-french-piracy-blocklist-expired-domains-a-seized-site-and-hong-kong-servers/">Inside a French Piracy Blocklist: Expired Domains ... * TorrentFreak</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism about anti-piracy measures that bypass prosecution, with one arguing that such efforts are a backdoor to suppressing speech. Others questioned the practicality of Quad9's withdrawal given its inability to identify French users, and some distinguished between commercial pirates and individual sharers.

**Tags**: `#DNS`, `#privacy`, `#internet governance`, `#censorship`, `#piracy`

---

<a id="item-10"></a>
## [Energy-Based Reasoners claim 385x more efficient inference than LLMs](https://energy-based-reasoners.github.io/) ⭐️ 7.0/10

A new project page introduces Energy-Based Reasoners (EBRs), which learn an energy function over latent reasoning states and formulate looped updates as gradient descent on this energy, claiming 385x more efficient inference than large language models. If validated, this approach could offer a dramatically more efficient alternative to LLM inference, especially for tasks requiring iterative reasoning like logic puzzles, and has attracted attention from figures like Yann LeCun through Logical Intelligence. The energy function scores latent states, and its gradient guides refinement and provides a stopping signal; however, the claim is based on a project page rather than peer-reviewed results, and community members note that EBMs are notoriously hard to train and may not scale beyond niche problems.

hackernews · frenchmajesty · Nov 18, 09:29 · [Discussion](https://news.ycombinator.com/item?id=50543989)

**Background**: Energy-based models (EBMs) learn a scalar energy function that assigns lower energy to more plausible configurations, drawing from statistical physics. They have long been proposed as an alternative to probabilistic models but are challenging to train due to the need to approximate intractable partition functions. Recent work like Energy-Based Reasoners applies EBMs to iterative reasoning by treating updates as gradient descent on the energy landscape.

<details><summary>References</summary>
<ul>
<li><a href="https://energy-based-reasoners.github.io/">Energy - Based Reasoners : Your Recurrent Reasoner Should Be an...</a></li>
<li><a href="https://news.ycombinator.com/item?id=50543989">Energy - Based Reasoners : 385x more efficient inference</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters expressed both enthusiasm and skepticism: some pointed to Yann LeCun-backed Logical Intelligence as promising for tasks LLMs struggle with, while others with hands-on experience warned that EBMs are impressive validators but extremely hard to train, niche-specific, and may not scale to large problems.

**Tags**: `#energy-based-models`, `#inference-efficiency`, `#AI-research`, `#LLM-alternatives`, `#machine-learning`

---

<a id="item-11"></a>
## [IRS sign-in via ID.me sparks privacy and accessibility backlash](https://consumerrights.wiki/w/ID.me_terms_required_for_IRS_sign-in) ⭐️ 7.0/10

A Hacker News discussion with 456 points and 242 comments highlights controversy over the IRS requiring ID.me for online sign-in, with users reporting accessibility barriers and privacy concerns. Commenters note that login.gov is now accepted for some IRS services, but many still face problems with ID.me's smartphone requirement. This matters because millions of Americans rely on IRS online services, and requiring a third-party identity verification service like ID.me can exclude those without smartphones or reliable internet, while raising privacy concerns about facial recognition and data handling. The discussion reflects broader tensions around government digital identity and the role of private companies in public services. ID.me verification typically requires a photo of an ID, a video selfie, and personal information, with a fallback to a 'Trusted Referee' video call for failed attempts. The IRS has a contract with ID.me worth $86 million, and login.gov is being positioned as an alternative, though availability varies by service.

hackernews · DeepLogin · Nov 18, 00:51 · [Discussion](https://news.ycombinator.com/item?id=50540437)

**Background**: ID.me is a private identity verification company that uses biometric data such as selfies to confirm users' identities. The IRS began requiring ID.me for online account access to combat identity theft and fraud, but the move has drawn criticism from privacy advocates and lawmakers. Login.gov is a government-run single sign-on service that aims to provide a simpler, more secure alternative for accessing federal services.

<details><summary>References</summary>
<ul>
<li><a href="https://www.itechpost.com/articles/109255/20220222/more-irs-facial-recognition-id-privacy-concerns-backlash-heres-sign.htm">No More IRS Facial Recognition After ID . me Privacy Concerns ...</a></li>
<li><a href="https://taxrefunddesk.com/identity-verification/id-me-irs-verification">ID . me IRS Sign - In : Verifying Identity for Your Refund</a></li>
<li><a href="https://help.id.me/hc/en-us/articles/9198013708439-Verify-your-identity-with-IDMe-Self-Service">Verify your identity with IDMe Self-Service – IDMe Help Center</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration that ID.me is impossible to use without a smartphone, with one person noting a friend unable to cash out Treasury bonds. Others criticized the TreasuryDirect switch to ID.me, calling it a joke, and some shared workarounds like using login.gov for IRS sign-in. The overall sentiment is negative, citing privacy and accessibility issues.

**Tags**: `#digital identity`, `#privacy`, `#government services`, `#accessibility`, `#ID.me`

---

<a id="item-12"></a>
## [Phrack Issue 73 Released with Docker Escape Exploit](https://phrack.org/issues/73/introduction_md) ⭐️ 7.0/10

Phrack, the legendary hacker zine, has released issue 73, featuring technical security research including a Docker escape exploit. The issue continues the publication's tradition of publishing in-depth hacking articles and has sparked discussion on Hacker News about disclosure norms and hacker culture nostalgia. Phrack remains a highly influential publication in the security community, and its releases often showcase cutting-edge research and set trends. The inclusion of a Docker escape exploit highlights ongoing container security challenges and raises questions about responsible disclosure practices. The Docker escape exploit is one of several articles in the issue, which also covers topics like phreaking and hacker culture. The community discussion questions whether such exploits are responsibly disclosed with CVEs or dropped without warning, reflecting evolving norms in vulnerability disclosure.

hackernews · notmine1337 · Nov 17, 18:31 · [Discussion](https://news.ycombinator.com/item?id=50535992)

**Background**: Phrack is an e-zine written by and for hackers, first published in 1985, and has been described as having 'its finger on the pulse of hacker culture.' Originally covering phreaking and anarchy, it now covers a wide range of security topics and is run by international volunteers. Docker escape refers to techniques that allow breaking out of a Docker container to access the host system, a critical security concern in containerized environments.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Phrack_Magazine">Phrack Magazine</a></li>
<li><a href="https://phrack.org/">Phrack Magazine</a></li>
<li><a href="https://exploitnotes.org/exploit/container/docker/docker-escape">Docker Escape - Exploit Notes</a></li>

</ul>
</details>

**Discussion**: Commenters expressed nostalgia for the early days of Phrack and phreaking culture, sharing memories of blue boxes and dialers. Some questioned whether the Docker escape exploit was responsibly disclosed, while others praised the unpolished, open spirit of the zine compared to more formal HN comments.

**Tags**: `#security`, `#phrack`, `#exploitation`, `#hacker-culture`, `#responsible-disclosure`

---

<a id="item-13"></a>
## [curl Maintainer Questions AI Rust Rewrites Amid 200+ Real Bugfixes](https://simonwillison.net/2026/Nov/18/daniel-stenberg/) ⭐️ 7.0/10

Daniel Stenberg, lead maintainer of curl, reported that while AI agents converted 185,000 lines of C code into 340,000 lines of Rust over about three weeks, the actual curl project merged over 300 commits, including more than 200 bugfixes and several security vulnerability fixes. He questioned whether these AI-generated Rust rewrites can keep up with the ongoing maintenance and security patching of the original project. This highlights a critical gap in AI-driven code rewrites: generating a large codebase is not the same as maintaining it with real-world bugfixes and security patches. The commentary is relevant to open-source maintainers, security engineers, and organizations considering AI-assisted ports of critical infrastructure, as it underscores the value of active maintenance over one-time translation. Stenberg counted 185,000 lines of C converted to 340,000 lines of Rust by the agents, while the real project merged over 300 commits and 200+ bugfixes in the same period, plus additional fixes in the following month. The core question is whether AI-generated clones can sustain the same pace of bugfixes and vulnerability patches as the actively maintained original.

rss · Simon Willison · Nov 18, 15:58

**Background**: curl is a widely used command-line tool and library for transferring data with URLs, written primarily in C and maintained by Daniel Stenberg. Rust is a systems programming language known for memory safety, making it a popular target for rewriting C code to eliminate vulnerabilities. AI coding agents have recently been used to automatically translate large C codebases into Rust, but such rewrites are typically one-time efforts that do not automatically incorporate subsequent upstream fixes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Rust_(programming_language)">Rust ( programming language ) - Wikipedia</a></li>
<li><a href="https://www.linkedin.com/pulse/why-rust-programming-language-dominates-systems-code-2026-rohit-singh-mwbkc">Why Rust Programming Language Dominates Systems Code in 2026</a></li>

</ul>
</details>

**Tags**: `#curl`, `#rust`, `#ai-code-generation`, `#open-source-maintenance`, `#security`

---

<a id="item-14"></a>
## [Inside-DB Website Compiles Deutsche Bank Scandals, Sparks Hacker News Discussion](https://www.inside-db.com/) ⭐️ 6.0/10

A website called Inside-DB has been created to compile critical articles about Deutsche Bank's various scandals. The site was shared on Hacker News, where it received 141 points and 43 comments, with users discussing its presentation and the need for a summary. This matters because it aggregates investigative journalism on Deutsche Bank's scandals in one place, making it easier for the public to access and understand the bank's controversial history. The Hacker News discussion highlights the importance of clear presentation and summarization in making complex financial scandals accessible to a broader audience. The site requires readers to click through to linked articles, which some commenters noted may deter casual visitors who lack time to read in-depth pieces. The discussion also touched on the perception of strict German regulation and the site's title missing the word 'Inside'.

hackernews · gyre007 · Nov 18, 15:38 · [Discussion](https://news.ycombinator.com/item?id=50547620)

**Background**: Deutsche Bank is a major German multinational investment bank that has been involved in numerous scandals, including the Global Laundromat money-laundering operation from 2010 to 2014 and bribery fines. Investigative journalists and authors like David Enrich have chronicled the bank's dysfunction and overreach. Hacker News is a popular social news website focused on computer science and entrepreneurship, where users often share and discuss articles of intellectual interest.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Deutsche_Bank">Deutsche Bank - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hacker_News">Hacker News</a></li>

</ul>
</details>

**Discussion**: Commenters generally appreciated the compilation but criticized the lack of a high-level summary, with one noting that many visitors will move on without understanding the key points. Some expressed skepticism about the effectiveness of German banking regulation, while others mentioned having seen documentaries on the topic and found the site's proofs useful. One user joked that the site was 'hugged to death' due to heavy traffic.

**Tags**: `#Deutsche Bank`, `#finance`, `#investigative journalism`, `#scandal`, `#Hacker News`

---

<a id="item-15"></a>
## [Energy drinks linked to 11 times more cardiac arrest reports in FDA database](https://www.sciencedaily.com/releases/2026/11/261110042543.htm) ⭐️ 6.0/10

An analysis of FDA adverse-event reports submitted from 2017 through 2025 found that energy drinks and caffeinated supplements were associated with 11 times more reports of cardiac arrest than other products. Of the reports, 854 involved energy drinks or dietary supplements containing caffeine or other stimulants. The finding could influence how regulators and consumers view the safety of energy drinks, which are consumed by tens of millions of people, and it highlights the need for better post-market surveillance of stimulant-containing products. It also raises questions about whether the signal reflects a true risk or is an artifact of reporting biases. The analysis is based on spontaneous reports to the FDA Adverse Event Reporting System (FAERS), which cannot establish causation and is subject to reporting bias and confounding. The absolute number of reports is small—about 100 per year for caffeine or other stimulants—relative to the tens of millions of consumers.

hackernews · wjSgoWPm5bWAhXB · Nov 18, 14:03 · [Discussion](https://news.ycombinator.com/item?id=50546465)

**Background**: The FDA Adverse Event Reporting System (FAERS) is a database of voluntary reports of adverse events submitted by healthcare professionals, consumers, and manufacturers; it is used for signal detection but cannot prove that a product caused an event. Energy drinks typically contain caffeine, often combined with other stimulants such as taurine and guarana, and have been linked in some studies to cardiovascular effects. Observational analyses of such reports are prone to the base rate fallacy, where a higher proportion of reports for a product does not necessarily mean a higher risk per user.

<details><summary>References</summary>
<ul>
<li><a href="https://www.npr.org/2021/08/20/1029582399/planet-money-investigates-the-base-rate-fallacy-as-it-pertains-to-the-pandemic">Planet Money Investigates The Base Rate Fallacy As It Pertains... : NPR</a></li>
<li><a href="https://www.sciencedaily.com/releases/2026/07/260721000820.htm">Coffee may protect your heart but energy drinks could... | ScienceDaily</a></li>
<li><a href="https://www.news-medical.net/health/Do-Energy-Drinks-Affect-Blood-Vessels.aspx">Do Energy Drinks Affect Blood Vessels?</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were skeptical of the causal link, pointing out that energy drink consumers may have other risk factors such as sleep deprivation, overtraining, or hangovers, and that the absolute number of reports is tiny given the huge consumer base. Some argued that sugar and artificial sweeteners, not caffeine, are the real danger, while others noted that 'energy drinks' is a vague category covering a wide spectrum of products.

**Tags**: `#health`, `#caffeine`, `#energy-drinks`, `#FDA`, `#risk-analysis`

---

<a id="item-16"></a>
## [Blog questions why Gemini 4 Carbon is slow; HN debates efficiency](https://kernel.dev/blog/why-is-gemini-4-carbon-taking-so-long/) ⭐️ 6.0/10

A blog post titled 'Why is Gemini 4 Carbon taking so long?' sparked a Hacker News discussion with 229 points and 121 comments, where users shared anecdotal evidence that Google's Gemini 4 Carbon model is notably slow and token-inefficient compared to competitors. The discussion highlights a trade-off in frontier model design: Google appears to prioritize quality and reasoning depth over inference speed and token efficiency, which could affect developer adoption and cost for latency-sensitive applications. One commenter analyzed 146 'battles' and found Carbon took 6m08s versus 2m04s for opponents, generated 16.4k output tokens versus 6.8k, and made 21 tool calls versus 11—all statistically significant differences.

hackernews · deenadz · Nov 18, 04:14 · [Discussion](https://news.ycombinator.com/item?id=50541790)

**Background**: Gemini 4 Carbon is a reasoning model from Google, based on Gemini 4 Argon, designed for complex software engineering, multimodal knowledge work, and scientific reasoning. It became generally available via the Gemini API and Google AI Studio on November 10, 2026, priced at $8.00 per million tokens. Token efficiency and inference speed are key metrics for LLMs, as generating more tokens and making more tool calls directly increases latency and cost.

<details><summary>References</summary>
<ul>
<li><a href="https://benchlm.ai/models/gemini-4-carbon">Gemini 4 Carbon Benchmarks, Pricing & Speed (November 2026)</a></li>
<li><a href="https://kie.ai/gemini-4-carbon">Gemini 4 Carbon API: 1M Context, Deep Reasoning | Kie. ai</a></li>
<li><a href="https://onlysota.ai/models/google/gemini-4-carbon">Gemini 4 Carbon benchmarks — Google — OnlySOTA</a></li>

</ul>
</details>

**Discussion**: Commenters generally agree that Carbon is slow and token-inefficient, with some attributing this to Google's focus on frontier quality over serving efficiency. Others praise Carbon's problem-solving style as a refreshing 'light touch' compared to Claude's 'bulldozer attitude,' and one user notes falling back on Gemini 4 Argon for security reasons due to fewer triggers.

**Tags**: `#AI/ML`, `#LLM`, `#Google Gemini`, `#model efficiency`, `#Hacker News discussion`

---

<a id="item-17"></a>
## [Archive Team Preserves Apple Support Community Before 2026 Closure](https://wiki.archiveteam.org/index.php/Apple_Discussions) ⭐️ 6.0/10

Archive Team, a volunteer digital preservation group, is archiving the Apple Support Community ahead of its permanent closure on November 20, 2026. The site is now read-only and no longer accepts new posts. This effort ensures that years of user-generated troubleshooting content remain accessible to researchers and the public, even after Apple removes the official platform. It also highlights the growing role of volunteer archivists in preserving at-risk online communities. Archive Team is using its custom archiving tools to crawl the community, with live progress available on its tracker. The archived content will likely be made available through the Internet Archive's Wayback Machine, consistent with Archive Team's usual practice.

hackernews · digitaldragon · Nov 17, 23:32 · [Discussion](https://news.ycombinator.com/item?id=50539747)

**Background**: Archive Team is a volunteer collective founded in 2009 by Jason Scott that focuses on preserving at-risk online services, having previously archived GeoCities, Yahoo! Video, and Friendster. Web archiving involves using automated crawlers to capture and preserve web content for future access, often through services like the Wayback Machine. The Apple Support Community, launched in 2004, has been a major user-to-user support forum but will close permanently in 2026.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Archive_Team">Archive Team</a></li>
<li><a href="https://en.wikipedia.org/wiki/Web_archiving">Web archiving</a></li>
<li><a href="https://discussions.apple.com/learn">How to use the Apple Support Community</a></li>

</ul>
</details>

**Discussion**: Commenters largely criticized the Apple Support Community as unhelpful and full of misinformation, questioning whether archiving it is worthwhile. Some argued that preservation is still valuable, while others suggested focusing only on confirmed answers and unanswered questions.

**Tags**: `#digital preservation`, `#archiving`, `#Apple Support Community`, `#community discussion`, `#web archiving`

---