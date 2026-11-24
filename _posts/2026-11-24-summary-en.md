---
layout: default
title: "Horizon Summary: 2026-11-24 (EN)"
date: 2026-11-24
lang: en
---

> From 23 items, 18 important content pieces were selected

---

1. [Nvidia Reinstates Jensen Huang as CEO After Brief Ouster](#item-1) ⭐️ 9.0/10
2. [Quad9 Deactivates DNS Service in France Over Legal Constraints](#item-2) ⭐️ 8.0/10
3. [Anthropic stock falls below $83 IPO price](#item-3) ⭐️ 8.0/10
4. [GPT-6.2 Astra Solves 1808 Sketchbook Mystery in 22 Minutes](#item-4) ⭐️ 8.0/10
5. [Z.ai Releases GLM-5.4, Its First Looped Transformer Model](#item-5) ⭐️ 8.0/10
6. [Ladybird browser ships first alpha for macOS and Linux](#item-6) ⭐️ 8.0/10
7. [GreyNoise Uncovers Active Campaign Exploiting Check Point Security Management Servers](#item-7) ⭐️ 7.0/10
8. [Blog Post '2035 Came Early' Sparks HN Debate on AI Coding](#item-8) ⭐️ 7.0/10
9. [Songe: A Training Engine for Local LLMs Using Idle Compute](#item-9) ⭐️ 7.0/10
10. [LLM Agents Serve Their Parent Companies, Not Users](#item-10) ⭐️ 7.0/10
11. [Blog Post on Deterministic VM Performance Analysis Sparks HN Debate](#item-11) ⭐️ 7.0/10
12. [Stalwart 1.2.0 becomes drop-in replacement for Microsoft Exchange](#item-12) ⭐️ 7.0/10
13. [US Commerce Department bans exports to ex-Nvidia partner Megaspeed](#item-13) ⭐️ 7.0/10
14. [GTA 6 Recompilation Project 'Leonida' Banned from GitHub](#item-14) ⭐️ 7.0/10
15. [Hacker News Debates Bug Bounty Economics and Ethics](#item-15) ⭐️ 7.0/10
16. [AMD EPYC Zen 6 vs. Zen 1: 12.1x Geomean Performance Gain in Under a Decade](#item-16) ⭐️ 7.0/10
17. [Camillo Sitte's 1889 Blueprint for Beautiful Cities Revisited](#item-17) ⭐️ 6.0/10
18. [Datasette-charts 0.1a0: AI-assisted plugin for full-table interactive charts](#item-18) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Nvidia Reinstates Jensen Huang as CEO After Brief Ouster](https://www.cnbc.com/2026/11/23/nvidia-jensen-huang-ceo.html) ⭐️ 9.0/10

Nvidia's board reinstated Jensen Huang as President, CEO, and board director on November 23, 2026, just 11 days after he resigned amid scrutiny of his ties to a Chinese executive suspected of diverting chips to China. The board said it received input from senior US government officials and is confident his reinstatement poses no national security risk. The reversal raises serious questions about board independence and corporate governance at the world's most valuable chip company, and sets a precedent for direct government involvement in private-sector leadership decisions. It also intensifies debate over the fairness of US export controls as Nvidia's rivals face stricter sanctions enforcement. The board's statement emphasized that it acted based on input from senior US government levels, and the decision was reportedly unanimous despite the board having forced Huang out less than two weeks earlier. Critics note that the reinstatement occurred before investigations into his conduct concluded, potentially undermining the board's credibility.

hackernews · jaz · Nov 23, 14:00 · [Discussion](https://news.ycombinator.com/item?id=50611576)

**Background**: Jensen Huang co-founded Nvidia, which has become the dominant supplier of AI chips and one of the world's most valuable companies. He resigned after scrutiny of his ties to a Chinese executive linked to Megaspeed International, suspected of diverting advanced Nvidia chips to China in violation of US export controls. Under Delaware law, the Caremark precedent sets a high bar for holding boards liable for failing to oversee compliance, which may shield directors from personal liability.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reuters.com/legal/transactional/nvidia-boards-huang-reversal-raises-doubts-about-independence-critics-say-2026-11-24/">Nvidia board's Huang reversal raises doubts about ...</a></li>
<li><a href="https://apnews.com/article/nvidia-export-controls-chips-china-remote-access-60f868d3bb430b85a8657b27d421096e">Trump administration moves to restrict China from indirect ...</a></li>
<li><a href="https://www.semafor.com/article/11/23/2026/jensen-huangs-return-raises-troubling-questions-for-corporate-america">Jensen Huang’s return raises troubling questions for corporate America</a></li>

</ul>
</details>

**Discussion**: Commenters debated board liability under the Caremark precedent, with some arguing that the DoJ's decision not to prosecute combined with the high legal bar will shield directors. Others criticized the hypocrisy of forcing ASML and Japanese chip companies to comply with sanctions while Nvidia receives White House blessing, and noted that nominal governance structures often differ from real power dynamics, drawing parallels to the 2023 OpenAI saga.

**Tags**: `#nvidia`, `#corporate-governance`, `#semiconductors`, `#national-security`, `#geopolitics`

---

<a id="item-2"></a>
## [Quad9 Deactivates DNS Service in France Over Legal Constraints](https://quad9.net/news/blog/quad9-service-deactivation-in-france/) ⭐️ 8.0/10

Quad9 has deactivated its public DNS resolver service in France, effective November 24, 2026, after a French court order required it to block pirated websites. Users querying 9.9.9.9 from France now receive a REFUSED response with an Extended DNS Error (EDE 18) stating 'Service unavailable due to French legal constraints'. This is a significant real-world case of DNS-level censorship, showing how copyright enforcement orders can force global public resolvers to withdraw services from an entire country. It raises concerns about internet fragmentation, privacy, and the precedent for other jurisdictions to impose similar blocking demands on DNS providers. Quad9 states it lacks geographic blocking capabilities because its system is designed to treat all users identically, so instead of localizing censorship it chose to deactivate service in France entirely. The deactivation affects users and downstream systems such as AdGuard Home that rely on Quad9 as an upstream resolver.

hackernews · farrokhi · Nov 24, 08:33 · [Discussion](https://news.ycombinator.com/item?id=50625384)

**Background**: Quad9 is a free public DNS resolver that blocks malicious domains and is known for filtering over 97% of tested malware and phishing domains. DNS resolvers translate domain names into IP addresses, and blocking at the DNS level is a common method of internet censorship. French courts have ordered DNS providers to block piracy sites, and Quad9 has previously challenged such orders as disproportionate DNS censorship.

<details><summary>References</summary>
<ul>
<li><a href="https://quad9.net/news/press/quad9-faces-new-dns-censorship-legal-challenge-in-france-from-canal/">Quad9 Faces New DNS Censorship Legal Challenge in... | Quad9</a></li>
<li><a href="https://en.wikipedia.org/wiki/Quad9">Quad9 - Wikipedia</a></li>
<li><a href="https://ghostarchive.org/archive/8RC93">French Piracy Blocking Order Goes Global, DNS ... | Ghostarchive</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (two threads with 1,382 and 911 points and hundreds of comments) shows strong community concern, with users confirming the service deactivation via dig and reporting broken home networks. Commenters debate whether France should instead require residential ISPs to enforce blocks, and some highlight the broader implications for DNS censorship and internet freedom.

**Tags**: `#DNS`, `#privacy`, `#internet-regulation`, `#censorship`, `#network-infrastructure`

---

<a id="item-3"></a>
## [Anthropic stock falls below $83 IPO price](https://www.bloomberg.com/news/articles/2026-11-24/anthropic-breaks-below-83-ipo-price-in-premarket-trading) ⭐️ 8.0/10

Anthropic's stock dropped below its $83 IPO price in premarket trading, just days after the company priced its initial public offering at $83 per share, above its initially guided range of $70 to $78, valuing it at $1.5 trillion. This is a significant financial event for one of the leading AI companies, and the rapid drop below the IPO price could signal growing investor skepticism about lofty AI valuations and the broader AI investment climate. Anthropic's IPO raised $81.3 billion, making it one of the largest ever, but the stock's immediate decline highlights the gap between hype-driven pricing and fundamental financial performance.

hackernews · Betelbuddy · Nov 24, 13:23 · [Discussion](https://news.ycombinator.com/item?id=50627836)

**Background**: Anthropic is an AI company known for its Claude models and is considered a leading frontier research lab. An IPO prices a company's shares for the first time on a public exchange, and the IPO price is often set high based on investor demand and growth expectations. When the stock falls below that price soon after, it can indicate that the market's initial enthusiasm has cooled or that the valuation was overly optimistic.

<details><summary>References</summary>
<ul>
<li><a href="https://finance.yahoo.com/technology/ai/articles/anthropic-prices-ipo-83-per-220759400.html?fr=sycsrp_catchall">Anthropic prices IPO at $83 per share, giving it a $1.5 ...</a></li>
<li><a href="https://apnews.com/article/anthropic-ipo-pricing-70b660ddf900d90bbf484ecdf1fb441c">Anthropic prices its IPO at $83 per share in biggest IPO on ...</a></li>
<li><a href="https://valueaddvc.com/ai-valuations">AI Valuations Nov 2026: Anthropic $965B, OpenAI $852B</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were sharply divided, with many arguing the stock is driven by hype rather than fundamentals and predicting a 70-80% drop, while others noted that early stock performance after an IPO often has little bearing on long-term prices. Some shared personal losses from emotional trades, and one commenter emphasized that AI can be transformative while still being a bad investment at current prices.

**Tags**: `#Anthropic`, `#IPO`, `#AI industry`, `#stock market`, `#valuation`

---

<a id="item-4"></a>
## [GPT-6.2 Astra Solves 1808 Sketchbook Mystery in 22 Minutes](https://simonwillison.net/2026/Nov/24/astra-historical-mystery/) ⭐️ 8.0/10

GPT-6.2 Astra autonomously identified the creator of an anonymous 1808 sketchbook held at Yale's Beinecke Library in just 22 minutes using publicly available sources. It discovered a little-known archival reference to a visit by the vicomte de Chabot and predicted that Chabot's travel journal would confirm the attribution, which it did. This case study demonstrates that AI models can autonomously conduct original historical research, potentially transforming how historians approach archival work. It raises questions about the role of human expertise in disciplines that rely on interpretation and narrative. The model used minimal prompting and relied on public primary and secondary sources, including a diary reference to a visit by the vicomte de Chabot five days before a date in the sketchbook. The discovered source is itself a major find for Canadian and fur trade historians, though the journal is only available by order from Cleveland State University.

rss · Simon Willison · Nov 24, 16:53

**Background**: GPT-6.2 Astra is OpenAI's frontier model released in November 2026, designed for complex tasks with improved efficiency. The Beinecke Library at Yale is a major repository of rare books and manuscripts. Historical research typically involves analyzing primary sources (original documents) and secondary sources (interpretations), and attributing anonymous works often requires cross-referencing archival records.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-gpt-6-2-astra-sol/">Introducing GPT-6.2 Astra and Sol | OpenAI</a></li>
<li><a href="https://beinecke.library.yale.edu/">Beinecke Library | Yale Library</a></li>
<li><a href="https://history.ucla.edu/primary-secondary-sources/">Primary & Secondary Sources - UCLA Department of History</a></li>

</ul>
</details>

**Tags**: `#AI`, `#historical research`, `#GPT-6.2`, `#case study`, `#automation`

---

<a id="item-5"></a>
## [Z.ai Releases GLM-5.4, Its First Looped Transformer Model](https://simonwillison.net/2026/Nov/23/glm-54/) ⭐️ 8.0/10

Chinese AI lab Z.ai released GLM-5.4, its first flagship model built on a looped transformer architecture, on November 23, 2026. The model is currently accessible only through Z.ai's Coding Plan subscription, with open weights promised after safety hardening. This is the second looped transformer release within a week, following Thinking Machines Lab's Inkling 2 Mini on November 20, suggesting a potential architectural trend toward parameter-efficient recursive depth in LLM design. Z.ai claims GLM-5.4 reaches intelligence levels comparable to 2T-3T parameter models, which could reshape how labs scale model capability without proportionally increasing parameter counts. In a looped transformer, a group of weight-shared layers runs for multiple iterations, refining hidden states to create a deeper network without increasing parameter count. GLM-5.4 is not yet open-weights, and Simon Willison had to use the Coding Plan subscription because the model is not accessible through the regular API; he also built an llm-glm plugin since the existing llm-zai plugin did not yet support the new model.

rss · Simon Willison · Nov 23, 23:40

**Background**: A standard Transformer runs each layer once per forward pass, while a looped transformer reuses the same weights across recurrent passes to add effective depth. This parameter-efficient approach has appeared in models like Nanbeige 4.2, Ouro, and Dory1.0, and Thinking Machines' Inkling 2 Mini loops its middle layers three times per token to improve reasoning on tasks like agentic coding. Z.ai frames GLM-5.4 as the start of 'Generalized Coding,' where code becomes the foundation for solving a wider range of tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://z.ai/blog/glm-5.4">GLM-5.4: Toward Generalized Coding with Our First Loop ... - z.ai</a></li>
<li><a href="https://thinkingmachines.ai/news/inkling-2-mini/">Introducing Inkling 2 Mini - Thinking Machines Lab</a></li>
<li><a href="https://sebastianraschka.com/llm-architecture-gallery/looped-depth-sharing/">Looped Transformer | Sebastian Raschka, PhD</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#transformer architecture`, `#AI research`, `#model release`, `#Z.ai`

---

<a id="item-6"></a>
## [Ladybird browser ships first alpha for macOS and Linux](https://simonwillison.net/2026/Nov/23/ladybird/) ⭐️ 8.0/10

Ladybird, an independent browser built largely from scratch, released its first installable alpha on November 23, 2026, for macOS and Linux, letting users try it without compiling from source. This is a major milestone for browser engine diversity, as Ladybird implements its own HTML parser, CSS engine, layout, JavaScript, and WebAssembly, offering a rare alternative to Chromium, Gecko, and WebKit. The alpha still relies on external libraries like HarfBuzz for text shaping, Skia for 2D graphics, ffmpeg for video, and SQLite, and it uses a multi-process architecture with separate WebContent processes per tab; some advanced web features like service workers are incomplete, causing failures such as with Datasette Lite.

rss · Simon Willison · Nov 23, 21:46

**Background**: Ladybird originated from SerenityOS, an operating system written from scratch by Andreas Kling, and has evolved into a standalone browser project aiming to implement web standards independently. HarfBuzz is a text shaping library that converts Unicode text into properly positioned glyphs, while Skia is an open-source 2D graphics library used by Chrome and Android. The project has increasingly adopted coding agents in 2026 to accelerate development.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HarfBuzz">HarfBuzz - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Skia_Graphics_Library">Skia Graphics Library</a></li>
<li><a href="https://en.wikipedia.org/wiki/SerenityOS">SerenityOS - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#browser`, `#ladybird`, `#open-source`, `#web-standards`, `#systems`

---

<a id="item-7"></a>
## [GreyNoise Uncovers Active Campaign Exploiting Check Point Security Management Servers](https://www.greynoise.io/blog/check-point-security-management-servers-intrusion-campaign) ⭐️ 7.0/10

GreyNoise documented an active intrusion campaign targeting Check Point Security Management Servers, where attackers exploited the HFS loginSrp1 endpoint to recover the V8 PRNG state and forge signed admin session cookies. The campaign, observed through late 2026, involved multiple threat actors, including one using a script to check for and patch a Linux IPv4 use-after-free bug (CVE-2026-98432). This campaign highlights a sophisticated technique of PRNG state recovery to bypass authentication on critical security infrastructure, potentially leading to full network compromise. It underscores the growing trend of AI-assisted attacks and the need for robust hardening of management interfaces. Attackers collected multiple session cookies from successive logins to reconstruct the internal state of V8's Math.random() PRNG, enabling forgery of signed admin cookies. The campaign also involved exploitation of CVE-2026-18574, an authentication bypass in Check Point Security Management Server, and subsequent self-protection measures by attackers using nftables to drop malicious IPv4 packets.

hackernews · louiereederson · Nov 24, 16:32 · [Discussion](https://news.ycombinator.com/item?id=50630594)

**Background**: Check Point Security Management Servers are central consoles for configuring and monitoring Check Point firewalls and security policies. V8 is the JavaScript engine used in Chrome and Node.js, and its Math.random() function relies on a pseudo-random number generator (PRNG) whose internal state can be recovered if enough outputs are observed. GreyNoise is a threat intelligence service that analyzes internet-wide scanning and attack traffic to provide real-time context on emerging threats.

<details><summary>References</summary>
<ul>
<li><a href="https://v8.dev/blog/math-random">There’s Math. random (), and then there’s Math. random () · V 8</a></li>
<li><a href="https://support.checkpoint.com/results/sk/sk185222">CVE-2026-18574 - Management Authentication Bypass</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/check-point-patches-management-server-zero-day-exploited-in-attacks/">Check Point warns of Management Server zero-day exploited in ...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed concern that LLM-driven attacks will soon become widespread among less sophisticated criminals, targeting critical infrastructure. Some noted that router and firewall companies are prime targets and discussed hardening strategies, while others highlighted the attackers' use of self-protection measures like patching vulnerabilities to maintain access.

**Tags**: `#security`, `#vulnerability-exploitation`, `#network-security`, `#threat-intelligence`, `#firewalls`

---

<a id="item-8"></a>
## [Blog Post '2035 Came Early' Sparks HN Debate on AI Coding](https://fzakaria.com/2026/11/23/2035-came-early) ⭐️ 7.0/10

A blog post titled '2035 came early' on fzakaria.com sparked a Hacker News discussion with 841 points and 317 comments about how AI-assisted coding and LLM orchestration are reshaping software engineering practice and career expectations. The discussion reflects a broader industry shift where developers increasingly act as orchestrators of large language models rather than hands-on coders, raising questions about craftsmanship, career trajectories, and the value of traditional engineering skills. Commenters shared personal experiences, including one who spent over 100 hours prompting Claude to build waarm64.com and rushed its release due to competition, while others debated whether JavaScript's dominance is overstated and praised Gary Bernhardt's influence on software craftsmanship.

hackernews · setheron · Nov 24, 06:30 · [Discussion](https://news.ycombinator.com/item?id=50624497)

**Background**: LLM orchestration refers to managing, coordinating, and chaining large language models to build complex AI-driven applications, often involving multiple models, workflows, and data sources. AI-assisted coding tools like Claude and GitHub Copilot are increasingly used to generate code from natural language prompts, shifting developers' roles toward reviewing and directing AI output rather than writing every line manually.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/llm-orchestration">What is LLM orchestration? - IBM</a></li>
<li><a href="https://grokipedia.com/page/ai_assisted_software_development">AI-assisted software development</a></li>

</ul>
</details>

**Discussion**: The community showed diverse perspectives: some shared personal stories of career shifts away from hands-on coding, others debated the actual reach of JavaScript, and several praised Gary Bernhardt as an underappreciated influence. Overall sentiment was reflective, with agreement that AI orchestration is changing engineering work but disagreement on how universal or desirable that shift is.

**Tags**: `#AI-assisted development`, `#software engineering`, `#LLM orchestration`, `#career`, `#Hacker News discussion`

---

<a id="item-9"></a>
## [Songe: A Training Engine for Local LLMs Using Idle Compute](https://github.com/sous-labs/songe) ⭐️ 7.0/10

Songe is an open-source training engine that lets users fine-tune local large language models using their computer's idle compute. Before training, it measures how much the machine can learn at once and trains on what fits, as detailed in its DESIGN.md. This project lowers the barrier to entry for local LLM fine-tuning by leveraging existing hardware without requiring dedicated GPU clusters. It could enable hobbyists and small teams to customize models on consumer-grade machines, aligning with the growing trend of decentralized and resource-efficient AI training. Songe is Apache-2.0 licensed and available via pip install songe. It automatically adapts training to the available compute, but the community discussion raises questions about its effectiveness on modest or CPU-only hardware and how improvement is measured per training epoch.

hackernews · bluepeter · Nov 24, 15:03 · [Discussion](https://news.ycombinator.com/item?id=50629231)

**Background**: Fine-tuning is the process of further training a pre-trained language model on a specific dataset to adapt it to a particular task or domain. Local LLMs are models run on personal devices rather than cloud servers, often using tools like Ollama or llama.cpp. Distributed training across idle compute is an emerging approach that pools unused resources from multiple machines to handle larger workloads, as seen in research projects like Thunder and decentralized fine-tuning systems.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/sous-labs/songe">GitHub - sous-labs/songe: A training engine for your local model, using...</a></li>
<li><a href="https://arxiv.org/html/2503.02550v2">Thunder: Harnessing Unused GPU Cycles in Large-Scale Training via...</a></li>
<li><a href="https://huggingface.co/papers/2312.08361">Paper page - Distributed Inference and Fine - tuning of Large...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed enthusiasm for a SETI@home-like distributed LLM training system and asked about rough improvement numbers per training epoch. Others requested concrete examples of how Songe judges improvement, and one user asked whether it works on a modest Windows PC without a GPU.

**Tags**: `#local-llm`, `#fine-tuning`, `#distributed-training`, `#open-source`, `#machine-learning`

---

<a id="item-10"></a>
## [LLM Agents Serve Their Parent Companies, Not Users](https://michaelharley.net/posts/2026/11/01/llm-agents-work-for-their-parent-companies-not-for-you/) ⭐️ 7.0/10

A blog post argues that LLM agents like Claude prioritize the interests of their parent companies over users, citing examples where the agent refuses to bypass website terms of service (e.g., Bandcamp) but will perform other tasks like downloading YouTube songs. The post sparked a Hacker News discussion with 311 comments debating the legitimacy of such refusals. This debate highlights a growing tension in AI alignment: whether AI agents should act as fiduciaries for users or as gatekeepers enforcing corporate policies. It affects how users trust and interact with AI assistants, and could influence future regulation of AI agents' legal responsibilities. The author's example involves Claude refusing to circumvent Bandcamp's terms of service to help a user connect with bands, while still complying with a request to download a YouTube song. Commenters note that respecting site policies is necessary to avoid a spam-filled internet, and some propose that LLM agents should be legally required to act in users' best interests, similar to legal or medical advisors.

hackernews · surprisetalk · Nov 24, 12:40 · [Discussion](https://news.ycombinator.com/item?id=50627340)

**Background**: LLM agents are AI systems that use large language models to reason, plan, and take actions via external tools. AI alignment research aims to ensure such systems pursue intended goals and values, but aligning agents with user interests versus corporate policies is a key challenge. Terms of service (ToS) are legal agreements that websites use to restrict automated access, and AI agents must navigate these constraints.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_alignment">AI alignment</a></li>
<li><a href="https://developer.nvidia.com/blog/introduction-to-llm-agents">Introduction to LLM Agents | NVIDIA Technical Blog</a></li>

</ul>
</details>

**Discussion**: Commenters are divided: some argue that LLM agents should be legally required to act as fiduciaries for users, like legal or medical advisors, while others find the author's argument flimsy and support Claude's refusals as correct behavior that respects website policies and prevents a spammier internet. A common view is that the agent is trying to be a good citizen by honoring Bandcamp's wishes.

**Tags**: `#LLM agents`, `#AI ethics`, `#terms of service`, `#AI alignment`, `#regulation`

---

<a id="item-11"></a>
## [Blog Post on Deterministic VM Performance Analysis Sparks HN Debate](https://fzakaria.com/2026/11/12/worshipping-at-the-altar-of-brendan-gregg) ⭐️ 7.0/10

A blog post titled 'Worshipping at the altar of Brendan Gregg' explores deterministic VM-based performance analysis, referencing flame graphs and profiling techniques. The post, discussed on Hacker News with 29 comments, examines the approach's limitations for multithreaded and async workloads and compares it to record-and-replay tools like rr. Deterministic VM-based analysis promises reproducible performance debugging, which could significantly aid developers in diagnosing complex issues, but its effectiveness for modern multithreaded and asynchronous systems is questioned. The discussion highlights ongoing challenges in profiling concurrent code and the need for better tools. The deterministic VM is noted to be single-threaded, which may compromise performance analysis for high-throughput multithreaded pipelines. Commenters also question whether such analysis helps async workloads like C++ coroutines and fibers, and suggest alternatives like sleep profiling or CPU stall profiling.

hackernews · kqr · Nov 24, 10:50 · [Discussion](https://news.ycombinator.com/item?id=50626413)

**Background**: Flame graphs, created by Brendan Gregg in 2011, are a visualization technique for identifying hot spots in software by aggregating stack traces. Deterministic VMs aim to provide reproducible execution for debugging, while record-and-replay tools like rr capture and replay program execution to aid debugging. These techniques are commonly used in performance engineering to understand and optimize software behavior.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Flame_graph">Flame graph - Wikipedia</a></li>
<li><a href="https://www.brendangregg.com/flamegraphs.html">Flame Graphs - Brendan Gregg</a></li>

</ul>
</details>

**Discussion**: Commenters expressed interest in deterministic VMs but raised concerns about the single-threaded limitation for multithreaded pipelines and the difficulty of inferring cross-thread dependencies with flame graphs. Some drew parallels to record-and-replay tools like rr, while others questioned the approach's utility for async workloads and suggested alternative profiling methods.

**Tags**: `#performance-analysis`, `#deterministic-vm`, `#flamegraphs`, `#async`, `#profiling`

---

<a id="item-12"></a>
## [Stalwart 1.2.0 becomes drop-in replacement for Microsoft Exchange](https://stalw.art/blog/microsoft-exchange-replacement/) ⭐️ 7.0/10

Stalwart has released version 1.2.0, which it claims makes it a drop-in replacement for Microsoft Exchange. This means organizations can replace Exchange with Stalwart without changing their existing Outlook clients or workflows. This is a significant milestone for the open-source email ecosystem, as it offers organizations a path away from Microsoft's proprietary lock-in. It could particularly benefit self-hosted setups and companies looking to reduce licensing costs. Stalwart is an all-in-one mail and collaboration server supporting JMAP, IMAP4, POP3, SMTP, CalDAV, CardDAV, and WebDAV. However, it lacks certain regulatory compliance features such as GoBD-compliant archiving, which may be a limitation for some businesses.

hackernews · shaunpud · Nov 23, 22:32 · [Discussion](https://news.ycombinator.com/item?id=50620349)

**Background**: Microsoft Exchange is a widely used mail server and calendaring system, and Outlook is its primary client. Stalwart is an open-source alternative that aims to provide similar functionality without vendor lock-in. Drop-in replacement means it can substitute Exchange without requiring changes to clients or configurations.

<details><summary>References</summary>
<ul>
<li><a href="https://stalw.art/blog/microsoft-exchange-replacement/">Stalwart is now a drop - in replacement for Microsoft Exchange</a></li>
<li><a href="https://github.com/stalwartlabs/stalwart">GitHub - stalwartlabs/ stalwart : All-in-one Mail & Collaboration server .</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (668 points, 330 comments) raised concerns about regulatory archiving (GoBD), protocol lock-in, and client compatibility. Some commenters questioned how Stalwart can be a drop-in replacement if Outlook will no longer support on-premise Exchange, while others noted that Stalwart is used by Mozilla's Thundermail.

**Tags**: `#email`, `#open-source`, `#microsoft-exchange`, `#self-hosting`, `#protocols`

---

<a id="item-13"></a>
## [US Commerce Department bans exports to ex-Nvidia partner Megaspeed](https://www.upi.com/Top_News/US/2026/11/24/NVIDIA-partner-Megaspeed/1701795520063/) ⭐️ 7.0/10

The U.S. Commerce Department has issued an export ban on Megaspeed, a Singapore-based company that was formerly an official Nvidia cloud partner, amid investigations into export-control violations and alleged smuggling of advanced Nvidia chips to China. This action signals escalating U.S. scrutiny of intermediaries that may facilitate chip diversion to China, but its limited scope—covering only U.S.-made chips—may undermine its effectiveness in curbing access to high-end AI chips made in Taiwan. The ban restricts only exports from the United States to Megaspeed, not re-exports from other countries, and most advanced AI chips are fabricated in Taiwan, so they would not be directly affected by this rule.

hackernews · nephihaha · Nov 24, 16:08 · [Discussion](https://news.ycombinator.com/item?id=50630245)

**Background**: Megaspeed is a Singapore-based firm that leveraged its relationship with Alibaba to become an official Nvidia cloud partner. U.S. export controls restrict the sale of certain advanced chips to China and require licenses for others, and the Commerce Department's Entity List bans exports of U.S.-origin technology to listed parties. The case is part of broader U.S. efforts to prevent advanced AI chips from reaching China through third-party intermediaries.

<details><summary>References</summary>
<ul>
<li><a href="https://www.straitstimes.com/world/united-states/us-blacklists-megaspeed-chip-firm-linked-to-nvidia-scandal">US blacklists Megaspeed , Alibaba unit amid Nvidia ... | The Straits Times</a></li>
<li><a href="https://www.indiatoday.in/world/story/megaspeed-us-blacklist-nvidia-export-control-espionage-probe-3045532-2026-11-24">Megaspeed US blacklist: Nvidia customer faces export ... - India Today</a></li>
<li><a href="https://www.nytimes.com/2026/11/09/business/economy/nvidia-megaspeed-investigation-huang.html">U . S . Commerce Dept . Inquiry Into Megaspeed Was Halted After...</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted a key loophole: the ban only covers U.S.-made chips, not Taiwan-made AI chips, so it may not affect the high-end chips people care about. Others expressed skepticism that such measures will work, noting that GPUs will likely continue flowing through other companies and that Megaspeed may not have directly exported GPUs but only provided compute access to Chinese clients.

**Tags**: `#export-controls`, `#nvidia`, `#ai-chips`, `#geopolitics`, `#semiconductors`

---

<a id="item-14"></a>
## [GTA 6 Recompilation Project 'Leonida' Banned from GitHub](https://github.com/ItsNotRexed/Leonida/issues) ⭐️ 7.0/10

The GitHub repository for 'Leonida', a fan-made static recompilation of GTA 6's Xbox version for PC, was banned while its lead developer was at school. The takedown sparked a large Hacker News discussion with over 500 comments debating the ethics and legality of reverse engineering and piracy. This event highlights the ongoing tension between fan-driven reverse engineering projects and corporate copyright enforcement, raising questions about the legality and ethics of recompiling games for platforms like PC. It affects developers, gamers, and rights holders, and could influence how similar projects are treated in the future. Leonida is a static recompilation project that leverages the Xbox Series CPU's x86-64 architecture to run the game natively on PC, translating precompiled RDNA2 GPU programs to SPIR-V for Vulkan. The repository was taken down, likely due to a DMCA notice, though the exact reason is not specified.

hackernews · smuhakg · Nov 24, 02:08 · [Discussion](https://news.ycombinator.com/item?id=50622638)

**Background**: Static recompilation is a technique that converts a game's machine code into native code for another platform, allowing games to run without emulation. This has been used in projects like recompiling Mario 64 and Zelda, and is often legally contentious because it involves reverse engineering copyrighted software. GitHub, as a hosting platform, must respond to DMCA takedown notices, which can result in repository bans.

<details><summary>References</summary>
<ul>
<li><a href="https://gta6recomp.com/leonida">Leonida — GTA 6 PC Static Recompilation Project Tracker & Source</a></li>
<li><a href="https://github.com/FedorovIgorFeliksovich/LeonidaMy">GitHub - FedorovIgorFeliksovich/LeonidaMy: Leonida Is A Native PC...</a></li>
<li><a href="https://flipboard.com/article/github-reverses-takedown-of-reverse-engineered-gta-source-code/f-55bde07cfa/arstechnica.com">Github reverses takedown of reverse - engineered GTA... | Flipboard</a></li>

</ul>
</details>

**Discussion**: The discussion was polarized: some argued that reverse engineering is ethically acceptable given corporations' own legal minimalism and tax avoidance, while others condemned piracy as harming the thousands of developers who spent years on the game. A common sentiment was frustration with console exclusivity, with users willing to pay for the game but not for expensive hardware.

**Tags**: `#reverse-engineering`, `#copyright`, `#gaming`, `#github`, `#ethics`

---

<a id="item-15"></a>
## [Hacker News Debates Bug Bounty Economics and Ethics](https://www.justafewbugs.xyz/) ⭐️ 7.0/10

A blog post titled 'Just a Few Bugs' sparked a Hacker News discussion with around 40 comments about bug bounty programs, focusing on exploitation, researcher incentives, and ethical concerns. The discussion highlights growing tensions in the bug bounty ecosystem, where researchers and program owners both report frustration, and raises questions about whether such programs fairly compensate security work or exploit researchers. Commenters shared insider perspectives: one program owner described fighting their own team to secure fair bounties for researchers, while another researcher revealed hoarding thousands of bugs for a year to build a zero-click RCE chain and plans to sell to Crowdfense; a third commenter noted that AI found about 60 bugs in the D compiler's code generator.

hackernews · jjjegly · Nov 24, 09:47 · [Discussion](https://news.ycombinator.com/item?id=50625953)

**Background**: Bug bounty programs are crowdsourced security initiatives where organizations reward ethical hackers for responsibly disclosing vulnerabilities before they can be exploited. Platforms like HackerOne facilitate these programs, but researchers can often earn far more by selling zero-day exploits to brokers or spyware companies, creating ethical dilemmas. Vulnerability disclosure policies vary, and the line between ethical research and exploitation is a persistent debate in the security community.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bug_bounty_program">Bug bounty program</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vulnerability_disclosure">Vulnerability disclosure</a></li>
<li><a href="https://www.hackerone.com/bug-bounty-programs">Bug Bounty Programs - HackerOne</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed views: some criticized bug bounty programs as exploitative 'gig work' that underpay researchers, while others shared experiences of both sides suffering. One commenter described hoarding bugs to sell to exploit brokers, and another noted AI's growing role in finding bugs, adding a new dimension to the debate.

**Tags**: `#bug-bounty`, `#security-research`, `#vulnerability-disclosure`, `#ethics`, `#hacker-news`

---

<a id="item-16"></a>
## [AMD EPYC Zen 6 vs. Zen 1: 12.1x Geomean Performance Gain in Under a Decade](https://www.phoronix.com/review/amd-epyc-9006-7601) ⭐️ 7.0/10

Phoronix benchmarks show AMD's EPYC Zen 6 (Venice) delivering a 12.1x geometric mean performance improvement over Zen 1 (Naples) across a suite of tests, achieved in less than 10 years. This demonstrates the rapid pace of server CPU advancement, with gains driven by both core count scaling (roughly 3x) and per-core IPC/clock improvements, and a ~5x performance-per-Watt improvement that directly impacts data center efficiency and total cost of ownership. The comparison pits dual EPYC 7601 (32-core Zen 1, 64 cores/128 threads total) against dual EPYC 9686F (96-core Zen 6 at 5.32GHz, 192 cores/384 threads total); the core count alone accounts for nearly 3x, with the rest from architectural gains, and the flagship EPYC 9996 offers 256 Zen 6C cores, 512 threads, and 1024MB L3 cache.

hackernews · zdw · Nov 24, 05:15 · [Discussion](https://news.ycombinator.com/item?id=50624061)

**Background**: AMD's Zen microarchitecture first launched in February 2017 with the Ryzen series and was used in the first-generation EPYC server CPUs (codenamed Naples). Zen 6, also known as Venice for EPYC, is the latest iteration, featuring a 12-core CCD, 4MB of L3 per core, and a 27% IPC uplift according to AMD. Phoronix is a well-known Linux hardware review site that uses its Phoronix Test Suite to run reproducible benchmarks and reports geometric mean scores to summarize overall performance across many tests.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zen_6">Zen 6 - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/AMD_Zen_Microarchitecture">AMD Zen Microarchitecture</a></li>
<li><a href="https://www.phoronix-test-suite.com/">Phoronix Test Suite - Linux Testing & Benchmarking Platform ...</a></li>

</ul>
</details>

**Discussion**: Commenters broke down the 12.1x gain into roughly 3x from core count scaling and the remainder from per-core improvements, and highlighted the ~5x performance-per-Watt gain as particularly impressive. Some noted that performance-per-dollar has decreased due to price increases, while others marveled at the 1024MB L3 cache and the speed of compiling the Linux kernel in 18 seconds.

**Tags**: `#AMD EPYC`, `#CPU performance`, `#benchmarking`, `#hardware`, `#Zen architecture`

---

<a id="item-17"></a>
## [Camillo Sitte's 1889 Blueprint for Beautiful Cities Revisited](https://www.worksinprogress.news/p/how-to-make-a-lovable-city) ⭐️ 6.0/10

An essay in Works in Progress examines Camillo Sitte's 1889 book 'City Planning According to Artistic Principles,' arguing for human-scale, aesthetically pleasing urban design, and sparked a discussion on Hacker News (82 points, 55 comments). The essay and discussion highlight ongoing debates about car-centric urban planning versus traditional, pedestrian-friendly cities, resonating with contemporary movements for sustainable and livable urban spaces. Sitte's book was highly influential, edited five times between 1889 and 1922, and emphasized the artistic placement of monuments and squares; however, commenters note that modern cities face challenges like high population density and car dependency that Sitte did not anticipate.

hackernews · crescit_eundo · Nov 24, 16:19 · [Discussion](https://news.ycombinator.com/item?id=50630423)

**Background**: Camillo Sitte (1843–1903) was an Austrian architect and urban theorist whose work influenced urban planning and land use regulation. His 1889 book critiqued the rigid, functionalist planning of his time and advocated for traditional European urbanism, focusing on the aesthetic arrangement of public spaces.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Camillo_Sitte">Camillo Sitte - Wikipedia</a></li>
<li><a href="https://architectuul.com/architecture/city-planning-according-to-artistic-principles">City Planning According to Artistic Principles | Architectuul</a></li>

</ul>
</details>

**Discussion**: Commenters expressed diverse views: some criticized the article for misinterpreting landmarks like St. Peter's Square, others found Christopher Alexander more relevant, and many debated the impact of cars and modern population density on the feasibility of Sitte's ideas.

**Tags**: `#urban-design`, `#architecture`, `#history`, `#cities`, `#hackernews-discussion`

---

<a id="item-18"></a>
## [Datasette-charts 0.1a0: AI-assisted plugin for full-table interactive charts](https://simonwillison.net/2026/Nov/23/datasette-charts/) ⭐️ 6.0/10

Simon Willison released datasette-charts 0.1a0, a new Datasette plugin that adds interactive charts to table views and arbitrary SQL queries, prototyped in a single Sunday session using Claude Fable 5.2. Unlike earlier plugins such as datasette-vega that only charted the current page of up to 100 rows, this plugin aggregates across the entire result set, making Datasette far more useful for exploring large datasets with minimal user direction. Charts are compiled into SQL queries using GROUP BY, time bucketing, and window functions, with each query capped at 5,000 rows; chart state is persisted in the URL fragment for bookmarking and sharing, and sampling is used to suggest charts for large tables without evaluating the full result set.

rss · Simon Willison · Nov 23, 00:37

**Background**: Datasette is Simon Willison's open-source tool for exploring and publishing data, built on Python and SQLite. Datasette Lite runs Datasette entirely in the browser via Pyodide, which compiles Python to WebAssembly. Claude Fable 5.2 is an Anthropic large language model released in November 2026, and Willison used it as a coding agent to build the plugin prototype.

<details><summary>References</summary>
<ul>
<li><a href="https://lite.datasette.io/">Datasette</a></li>
<li><a href="https://platform.claude.com/docs/en/models/fable-5-2/overview">Claude Fable 5.2 - Claude Platform Docs</a></li>
<li><a href="https://simonwillison.net/series/datasette-lite/">Simon Willison: Datasette Lite</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#data-visualization`, `#plugins`, `#ai-assisted-development`, `#open-source`

---