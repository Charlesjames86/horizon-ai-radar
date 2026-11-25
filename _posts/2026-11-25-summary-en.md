---
layout: default
title: "Horizon Summary: 2026-11-25 (EN)"
date: 2026-11-25
lang: en
---

> From 26 items, 20 important content pieces were selected

---

1. [OpenAI preprint claims matrix multiplication exponent is exactly 9/4](#item-1) ⭐️ 10.0/10
2. [Google's Cogentic AI Releases Six Math Papers on Factoring and Discrete Logs](#item-2) ⭐️ 9.0/10
3. [1Password Discloses Employee Laptop Compromise Led to Code Push](#item-3) ⭐️ 8.0/10
4. [Rockbox ported to $9 undocumented YP3 MP3 player with LLM help](#item-4) ⭐️ 8.0/10
5. [Bypassing iOS Safari's 60 FPS Limit for Native-Feeling Web Apps](#item-5) ⭐️ 8.0/10
6. [Ternary Bonsai 2.5 27B: Ternary-Quantized Model Matches Frontier on SWE-bench](#item-6) ⭐️ 8.0/10
7. [Researchers Hijack US Treasury Subdomains for $3 via AWS IP Reallocation](#item-7) ⭐️ 8.0/10
8. [Simon Willison Identifies Three LLM Inflection Points in Twelve Months](#item-8) ⭐️ 8.0/10
9. [GPT-6.2 Astra Solves 1808 Sketchbook Mystery in 22 Minutes](#item-9) ⭐️ 8.0/10
10. [GLM-5.4: Z.ai's First Loop Transformer for Generalized Coding](#item-10) ⭐️ 8.0/10
11. [Ladybird browser engine releases first alpha for macOS and Linux](#item-11) ⭐️ 8.0/10
12. [Sandboxed LLM Agents Can Communicate via Inference Server Side Channels](#item-12) ⭐️ 7.0/10
13. [Browser Gallery Revives Classic Nvidia and ATI GPU Tech Demos](#item-13) ⭐️ 7.0/10
14. [Essay argues competent engineers should embrace LLM tools, sparking HN debate](#item-14) ⭐️ 7.0/10
15. [Reviving Old Java Phones with Bluetooth Networking](#item-15) ⭐️ 7.0/10
16. [Windows Loudness Equalization Reverse-Engineered and Ported to PipeWire](#item-16) ⭐️ 6.0/10
17. [Josh Comeau Releases Professionally Recorded Button Sounds for Web UI](#item-17) ⭐️ 6.0/10
18. [Economics Professor Distills Macrohistory into Six Facts, Sparking HN Debate](#item-18) ⭐️ 6.0/10
19. [Versine launches MCP for AI agents to send and request money](#item-19) ⭐️ 6.0/10
20. [datasette-charts 0.2a0 adds Datasette Agent integration for chat-based chart creation](#item-20) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI preprint claims matrix multiplication exponent is exactly 9/4](https://github.com/openai/math/blob/main/preprints/The-matrix-multiplication-exponent-is-nine-fourths-November-24-2026/paper.pdf) ⭐️ 10.0/10

A preprint hosted on OpenAI's GitHub claims that the matrix multiplication exponent ω is exactly 9/4 over every field, refuting the conjecture that ω equals 2. This paper is part of a set of four new OpenAI papers that together resolve eight problems from the Top 500 Open Problems in Math list, including strongly polynomial linear programming (Smale's ninth problem), mean-payoff games, and parity games. If verified, an exact value of 9/4 for ω would be a major breakthrough in algebraic complexity theory, settling a decades-old open problem and potentially leading to faster algorithms for matrix multiplication and related tasks. The result also intensifies the debate about AI's role in fundamental mathematical research and raises concerns about cryptographic implications. The claimed exponent 9/4 (2.25) is an exact value over every field, which is stronger than previous bounds that approached 2 asymptotically but were not exact. The paper is part of a broader set of AI-generated mathematical breakthroughs from OpenAI's internal system, and the proofs are yet to be fully verified by the mathematical community.

hackernews · E-Reverance · Nov 25, 01:19 · [Discussion](https://news.ycombinator.com/item?id=50637220)

**Background**: The matrix multiplication exponent, denoted ω, is the smallest number such that any two n×n matrices can be multiplied using O(n^{ω+ε}) field operations for any ε>0. For decades, ω has been known to be between 2 and 3, with the best upper bounds approaching 2 but never reaching it; the conjecture that ω=2 remains open. This preprint claims to settle the question by showing ω=9/4 exactly, which would be a surprising resolution.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Matrix_multiplication_algorithm">Matrix multiplication algorithm - Wikipedia</a></li>
<li><a href="https://mathworld.wolfram.com/MatrixMultiplicationExponent.html">Matrix Multiplication Exponent -- from Wolfram MathWorld</a></li>
<li><a href="https://www.datacamp.com/blog/openai-math-breakthroughs-what-the-latest-results-mean">OpenAI's AI Math Breakthroughs : What the Latest... | DataCamp</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (908 points, 513 comments) is intense, with commenters debating OpenAI's motivations and the potential cryptographic implications. Some express concern that OpenAI might be holding back stronger internal models to achieve breakthroughs and then using them to build even stronger models in a compounding loop, while others compare the current AI research atmosphere to Bell Labs but question whether these labs will use their findings for public good.

**Tags**: `#matrix-multiplication`, `#algorithms`, `#mathematics`, `#AI-research`, `#cryptography`

---

<a id="item-2"></a>
## [Google's Cogentic AI Releases Six Math Papers on Factoring and Discrete Logs](https://github.com/google-research/google-research/tree/master/cogentic_research_papers) ⭐️ 9.0/10

Google Research published six research papers produced by Cogentic, its multi-agent AI system running on Gemini 4, covering integer factorization, discrete logarithms, game theory, and computational complexity. One paper reportedly presents a proven fast algorithm for factoring numbers, marking a significant AI-driven contribution to mathematics. These results could have profound implications for public-key cryptography, which relies on the presumed hardness of integer factorization (RSA) and discrete logarithms (Diffie-Hellman, DSA). If AI can meaningfully advance these problems, it may accelerate the timeline for cryptographic migration to post-quantum algorithms. The papers were added to Google's public GitHub repository on November 25, 2026, and are explicitly attributed to Cogentic, an AI agent harness. The factoring algorithm is described as 'proven fast,' but the actual impact on practical cryptographic key sizes remains unclear without peer review and concrete benchmarks.

hackernews · rgwohlbold · Nov 25, 13:33 · [Discussion](https://news.ycombinator.com/item?id=50642086)

**Background**: Integer factorization is the problem of breaking a composite number into its prime factors, and the RSA cryptosystem's security depends on this being computationally infeasible for large numbers. The discrete logarithm problem is a related hardness assumption used in Diffie-Hellman key exchange and digital signature schemes. Both problems are believed to be hard for classical computers, but quantum computers running Shor's algorithm could solve them efficiently, which is why post-quantum cryptography is an active field.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/google-research/google-research/tree/master/cogentic_research_papers">google-research/cogentic_research_papers at master · google ...</a></li>
<li><a href="https://cellcog.ai/blog/google-cogentic-math-papers/">Google's Cogentic: Six AI-Written Math Papers | CellCog</a></li>
<li><a href="https://en.wikipedia.org/wiki/Integer_factorization">Integer factorization - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (307 points, 242 comments) shows intense interest and debate, with some users speculating about bigger undisclosed breakthroughs and others drawing parallels to AlphaGo's impact on mathematics. A key concern is whether these results invalidate public-key cryptography, and some commenters jokingly suggest government intervention or note prior AI factoring achievements like Anthropic's RSA-896.

**Tags**: `#cryptography`, `#integer-factorization`, `#discrete-logarithms`, `#AI-for-math`, `#google-research`

---

<a id="item-3"></a>
## [1Password Discloses Employee Laptop Compromise Led to Code Push](https://1password.com/blog/update-on-nov-2026-security-incident) ⭐️ 8.0/10

1Password disclosed a security incident in which an attacker compromised an employee's laptop and used access to the employee's corporate GitHub account to push code to production. The company began investigating on November 19, 2026, and stated that its apps and services are operating normally. This incident highlights a critical supply-chain risk for SaaS providers: a single compromised employee device can lead to malicious code being deployed to production, potentially affecting all customers. For a password manager, such a breach could undermine trust in the service's ability to protect sensitive credentials. 1Password has not specified whether the attacker accessed encrypted vault data or whether end-to-end encryption alone prevented data exposure. The company emphasized that its apps and services are functioning normally, but the investigation is ongoing.

hackernews · lxhrstn · Nov 25, 17:18 · [Discussion](https://news.ycombinator.com/item?id=50644817)

**Background**: 1Password is a popular password manager that stores user credentials in encrypted vaults, using end-to-end encryption so that only the user can decrypt their data. SaaS (Software as a Service) companies like 1Password rely on employees with access to code repositories and deployment pipelines, creating a supply-chain attack surface. A compromise of an employee's device can allow attackers to push malicious code that, once deployed, may bypass security controls.

<details><summary>References</summary>
<ul>
<li><a href="https://1password.com/blog/update-on-nov-2026-security-incident">Update on a security incident involving... | 1 Password</a></li>
<li><a href="https://bitwarden.com/resources/zero-knowledge-encryption-white-paper/">How End-to-End Encryption Paves the Way for Zero Knowledge ...</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted that compromising an employee laptop to push code is a top attack vector for SaaS companies, with the probability approaching 1 as employee count grows. Some questioned whether 1Password's encrypted vault data was never accessed or was protected solely by end-to-end encryption, noting the two scenarios have different implications for phishing risks. Others expressed concern that a sophisticated multi-step attack could lead to undetected full compromise of user credentials.

**Tags**: `#security`, `#saas`, `#supply-chain`, `#password-manager`, `#incident-response`

---

<a id="item-4"></a>
## [Rockbox ported to $9 undocumented YP3 MP3 player with LLM help](https://jayd.ml/2026/11/14/rockbox-on-yp3.html) ⭐️ 8.0/10

A developer documented porting the open-source Rockbox firmware to an undocumented $9 AliExpress 'YP3' MP3 player, using large language models to assist with reverse engineering and development. The project was shared on a personal blog and sparked a Hacker News discussion with 90 points and 50 comments. This shows how LLMs can lower the barrier to embedded reverse engineering, making it feasible to revive ultra-cheap, undocumented hardware with community firmware. It also signals renewed interest in standalone, non-networked music players as alternatives to smartphones and streaming. The player costs only $9 on AliExpress and lacks public documentation, so the port required reverse engineering the hardware and firmware with LLM assistance. The author's write-up details the process, though specific technical hurdles and limitations are not summarized in the provided content.

hackernews · jaydenmilne · Nov 24, 06:22 · [Discussion](https://news.ycombinator.com/item?id=50624446)

**Background**: Rockbox is an open-source firmware replacement for portable digital audio players that offers a richer user interface and extra features compared to stock firmware. It has historically supported devices like Archos, iriver, and iPod models, and is fondly remembered for running on the SanDisk Sansa Clip. The YP3 is a generic, ultra-low-cost MP3 player sold on AliExpress with no official developer documentation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Rockbox">Rockbox - Wikipedia</a></li>
<li><a href="https://sourceforge.net/projects/rockbox/">Rockbox - Open Source Jukebox Firmware - SourceForge.net Rockbox for Windows Users — iPodmania Rockbox user manual Rockbox - Wikipedia Rockbox - Open Source Jukebox Firmware - Browse /OldFiles at ... rockbox/firmware at master · Rockbox/rockbox · GitHub</a></li>
<li><a href="https://www.aliexpress.com/w/wholesale-yp3-mp3.html">YP3 MP3 Player - AliExpress</a></li>

</ul>
</details>

**Discussion**: Commenters expressed nostalgia for Rockbox on the Sansa Clip and excitement about LLM-assisted embedded development enabling alternatives to pricey used players. Some shared related projects, such as a Rockbox port to the Innioasis Y1 and using Claude to program M5Stack dev kits, while noting that embedded programming remains time-consuming.

**Tags**: `#Rockbox`, `#embedded systems`, `#LLM`, `#reverse engineering`, `#MP3 player`

---

<a id="item-5"></a>
## [Bypassing iOS Safari's 60 FPS Limit for Native-Feeling Web Apps](https://rida.dev/blog/bypassing-ios-safari-60-fps-limit) ⭐️ 8.0/10

A developer detailed how to bypass iOS Safari's 60 FPS rendering cap by hacking through WebKit source code to find workarounds, enabling web applications to achieve 120 FPS and feel native. This matters because it pushes the boundary of web performance on iOS, potentially allowing web apps to match native app smoothness, which could impact web developers and users who rely on Safari. The workaround involves enabling high-frequency input and manipulating WebKit internals, but it may come with trade-offs such as increased battery drain since 120Hz is always on rather than selectively enabled like in native iOS.

hackernews · vinhnx · Nov 25, 03:04 · [Discussion](https://news.ycombinator.com/item?id=50637890)

**Background**: iOS Safari caps rendering at 60 FPS by default, even on devices with 120Hz ProMotion displays, to save battery. Native apps can selectively enable 120 FPS for certain animations, but the web lacks an equivalent mechanism, so developers must find workarounds to achieve higher frame rates.

<details><summary>References</summary>
<ul>
<li><a href="https://rida.dev/blog/bypassing-ios-safari-60-fps-limit">Bypassing iOS Safari ’s 60 FPS Limit to Build Web Applications That...</a></li>
<li><a href="https://dev.to/it-influencer/how-can-you-make-website-feel-like-a-native-app-21hj">How can you make website feel like a native app ? - DEV Community</a></li>

</ul>
</details>

**Discussion**: Commenters praised the impressive demo and the deep WebKit hacking, but also noted that the glass effect can be distracting and that the difference may be subtle in some cases. One commenter explained that native iOS selectively enables 120Hz for large transitions, and always-on 120Hz would drain battery more than Apple prefers.

**Tags**: `#iOS`, `#Safari`, `#WebKit`, `#performance`, `#web development`

---

<a id="item-6"></a>
## [Ternary Bonsai 2.5 27B: Ternary-Quantized Model Matches Frontier on SWE-bench](https://prismml.com/news/bonsai-2-5-27b) ⭐️ 8.0/10

PrismML released Ternary Bonsai 2.5 27B, a ternary-quantized language model derived from Qwen3.8-27B with all weights quantized to {-1, 0, +1} and an FP16 scale per group of 128, fitting in a 5.9 GB footprint. It reportedly achieves performance on SWE-bench Verified comparable to frontier models like Opus 4.6 while running efficiently on consumer hardware such as a Mac Mini. This demonstrates that aggressive ternary quantization can shrink a 27B model to under 6 GB without sacrificing coding and agentic capabilities, potentially democratizing access to powerful AI on consumer devices. It also suggests that frontier-level benchmark performance may be achievable with much smaller models, narrowing the gap between large and small models. The model uses a hybrid-attention architecture unchanged from Qwen3.8-27B, and community benchmarks show generation speeds of 22-25 tokens/s on a Mac Mini M5 Pro with 24 GB RAM, with context windows up to 128k tokens. However, SWE-bench Verified is not the most representative benchmark, and some of the reported performance may reflect benchmark-specific tuning or lagging benchmark updates.

hackernews · b0m · Nov 24, 20:08 · [Discussion](https://news.ycombinator.com/item?id=50633922)

**Background**: Ternary quantization maps neural network weights to three discrete values {-1, 0, +1}, drastically reducing model size and memory bandwidth compared to standard 16-bit or 8-bit formats. This technique is part of a broader trend toward efficient inference for large language models, enabling deployment on edge devices. SWE-bench is a benchmark that evaluates models on real-world GitHub issues, testing their ability to resolve software engineering tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.prismml.com/models/bonsai-2-5-27b">Ternary Bonsai 2.5 27B - Bonsai - docs.prismml.com</a></li>
<li><a href="https://prismml.com/news/bonsai-2-5-27b">PrismML — Introducing Ternary Bonsai 2.5 27B: Powering ...</a></li>
<li><a href="https://arxiv.org/abs/2303.01505">[2303.01505] Ternary Quantization: A Survey - arXiv.org A Survey on Binary and Ternary Neural Networks and Their ... TRQ: Ternary Neural Networks With Residual Quantization Ternary Quantization in Neural Networks - emergentmind.com Ternary quantization of spiking neural networks TRAINED TERNARY QUANTIZATION - OpenReview</a></li>

</ul>
</details>

**Discussion**: Community members shared positive real-world results, with one user reporting 22-25 tokens/s on a Mac Mini and another autonomously generating a Tetris clone at 7-8 tokens/s. Some raised technical questions about alternative quantization schemes (e.g., quaternary) and noted that SWE-bench Verified may not fully represent model capabilities, while others highlighted improved task completion times in long-horizon agentic benchmarks.

**Tags**: `#quantization`, `#language-models`, `#efficient-inference`, `#swe-bench`, `#small-models`

---

<a id="item-7"></a>
## [Researchers Hijack US Treasury Subdomains for $3 via AWS IP Reallocation](https://www.intruder.io/research/taking-over-us-treasury-subdomains-for-3-each) ⭐️ 8.0/10

Security researchers at Intruder demonstrated that they could take over subdomains of the US Treasury for just $3 each by exploiting AWS's rapid reallocation of released Elastic IP addresses and stale DNS records. They provisioned valid TLS certificates for the hijacked subdomains, effectively serving trusted HTTPS content under a .gov domain. This highlights a systemic vulnerability in cloud infrastructure where dangling DNS records pointing to released IPs can be exploited to impersonate trusted government domains, undermining confidence in HTTPS and public-sector security. It also raises questions about cloud providers' responsibility to prevent such takeovers and the need for stricter domain validation for sensitive domains. The attack relies on AWS's policy of reallocating released Elastic IP addresses, which can be claimed by anyone; despite AWS stating that rapid allocation and release is a policy violation, the researchers argue that AWS could do more, such as offering an Elastic IP record type in Route 53 that is automatically deleted. The takeover also exploits the fact that certificate authorities will issue TLS certificates for any domain as long as the requester can demonstrate control via a file on that domain.

hackernews · negura · Nov 25, 04:27 · [Discussion](https://news.ycombinator.com/item?id=50638478)

**Background**: Subdomain takeover occurs when a DNS record points to a resource that has been released or is no longer controlled by the domain owner, allowing an attacker to claim that resource and serve content under the trusted subdomain. In cloud environments, Elastic IP addresses are static, public IPv4 addresses that can be quickly reassigned, and if a DNS record still points to a released IP, an attacker can obtain that IP and effectively take over the subdomain. This risk is amplified by automated TLS certificate issuance, which can make the hijacked subdomain appear legitimate with a valid HTTPS certificate.

<details><summary>References</summary>
<ul>
<li><a href="https://cheatsheetseries.owasp.org/cheatsheets/Subdomain_Takeover_Prevention_Cheat_Sheet.html">Subdomain Takeover Prevention - OWASP Cheat Sheet Series</a></li>
<li><a href="https://aws.amazon.com/blogs/mt/securing-elastic-ip-addresses-from-accidental-release/">Securing Elastic IP addresses from accidental release | AWS ...</a></li>
<li><a href="https://brandefense.io/security-news/aws-elastic-ip-takeover-dns-playbook/">AWS Elastic IP Takeover: DNS Playbook - Brandefense</a></li>

</ul>
</details>

**Discussion**: Commenters expressed confusion about how TLS takeover works without the private key, and others criticized AWS for not doing more to prevent the issue, with suggestions like an Elastic IP record type in Route 53 that auto-deletes. Some questioned whether extended validation certificates should be required for sensitive domains like .gov, and noted that AWS allowing IP reallocation within the same organization as a banned account seems like an oversight.

**Tags**: `#security`, `#subdomain-takeover`, `#AWS`, `#DNS`, `#TLS`

---

<a id="item-8"></a>
## [Simon Willison Identifies Three LLM Inflection Points in Twelve Months](https://simonwillison.net/2026/Nov/24/llm-inflection-points/) ⭐️ 8.0/10

In a keynote at the AI Engineer Code Summit, Simon Willison argued that LLM and coding agent capabilities hit three major inflection points in the past year, anchored by the one-year anniversary of Claude Opus 4.5's release on November 24, 2025. He highlighted Opus 4.5 and GPT-5.1 as the first models that made coding agents reliably useful, and introduced the concept of 'Fable class models' from Claude Fable 5 in June 2026. This retrospective from a highly respected voice in the AI engineering community offers a structured framework for understanding the rapid, step-change evolution of coding agents, which are increasingly central to software development workflows. It helps developers and organizations anticipate capability jumps and adapt their tooling and practices accordingly. Willison notes that Claude Opus 4.5 was the first model where Claude Code's default output was generally correct, making it a clear accelerant, and that OpenAI's GPT-5.1 family had a similar effect on Codex. He defines Fable class models as those that, given a goal and necessary tools, can solve problems with brute force, citing Claude Fable's proactive behavior such as spinning up its own screenshot mechanism and local logging server.

rss · Simon Willison · Nov 24, 23:02

**Background**: Claude is a family of large language models developed by Anthropic, with Opus as its most capable tier. Claude Code is a terminal-based coding agent introduced in February 2025 alongside Claude 3.7 Sonnet. In 2026, Anthropic released Claude Mythos to a handful of organizations but deemed it too dangerous for general release due to its cybersecurity capabilities, then released Claude Fable 5 as a safeguarded version for the public.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Opus_4.5">Claude Opus 4.5</a></li>
<li><a href="https://grokipedia.com/page/Comparison_of_Claude_Opus_45_and_Grok_Code_Fast_1">Comparison of Claude Opus 4.5 and Grok Code Fast 1</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#coding-agents`, `#AI-trends`, `#Claude`, `#AI-engineering`

---

<a id="item-9"></a>
## [GPT-6.2 Astra Solves 1808 Sketchbook Mystery in 22 Minutes](https://simonwillison.net/2026/Nov/24/astra-historical-mystery/) ⭐️ 8.0/10

History professor Mark Humphries reports that GPT-6.2 Astra autonomously identified the creator of an anonymous 1808 sketchbook held at Yale's Beinecke Library in just 22 minutes using public sources. The model discovered a little-known archival reference and correctly predicted that a diary by the vicomte de Chabot would confirm the sketchbook was his work. This case study demonstrates an AI model autonomously solving a real historical mystery, showcasing the potential of agentic AI to accelerate archival research and make novel discoveries. It raises questions about the evolving role of AI in historical scholarship and could foreshadow a broader shift in how humanities research is conducted. Astra found a diary reference to a visit by the vicomte de Chabot dated five days before a date mentioned in the sketchbook at a nearby river, and suggested that Chabot's journal of his travels—only available by order from Cleveland State University—might confirm the attribution. The newly discovered source is itself considered a major find of interest to Canadian and fur trade historians.

rss · Simon Willison · Nov 24, 16:53

**Background**: GPT-6.2 Astra is OpenAI's most capable model, released in November 2026, featuring a 1M token context window and strong reasoning abilities. The Beinecke Rare Book and Manuscript Library at Yale University holds rare books and archives, including the digitized 1808 sketchbook in question. Agentic AI systems like Astra can autonomously plan and execute multi-step research tasks, such as searching archives and forming hypotheses.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-gpt-6-2-astra-sol/">Introducing GPT-6.2 Astra and Sol | OpenAI</a></li>
<li><a href="https://artificialanalysis.ai/models/gpt-6-2-astra">GPT-6.2 Astra Models - Intelligence, Performance & Price ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#historical research`, `#GPT-6.2`, `#case study`, `#automation`

---

<a id="item-10"></a>
## [GLM-5.4: Z.ai's First Loop Transformer for Generalized Coding](https://simonwillison.net/2026/Nov/23/glm-54/) ⭐️ 8.0/10

Z.ai released GLM-5.4, its first flagship model built on a looped transformer architecture, where a group of 28 weight-shared layers runs for two iterations to increase effective depth without increasing parameter count. The model is not yet open-weight, but is accessible via Z.ai's Coding Plan subscription and API. This is the second looped transformer release in a week, following Thinking Machines Lab's Inkling 2 Mini, signaling a potential architectural trend toward parameter-efficient depth. For AI/ML practitioners, it demonstrates a way to achieve deeper reasoning without proportional parameter growth, which could influence future model designs. GLM-5.4 uses 28 weight-shared layers run for 2 iterations and reaches intelligence levels comparable to 2T-3T parameter models, according to Z.ai. The model weights will be open-sourced after safety hardening, and it is currently only available through the Coding Plan subscription, though the API is OpenAI-compatible.

rss · Simon Willison · Nov 23, 23:40

**Background**: A looped transformer (also called recurrent depth or looped depth sharing) applies the same transformer block or a group of weight-shared layers multiple times per forward pass, refining hidden states iteratively. This approach, related to weight tying seen in models like ALBERT, allows a model to have more effective depth without increasing its parameter count, potentially improving reasoning efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://sebastianraschka.com/llm-architecture-gallery/looped-depth-sharing/">Looped Transformer | Sebastian Raschka, PhD</a></li>
<li><a href="https://www.marktechpost.com/2026/11/23/zai-glm-5-4-loop-transformer/">Z AI Releases GLM-5.4: A 750B Loop Transformer ... - MarkTechPost</a></li>
<li><a href="https://z.ai/blog/glm-5.4">GLM-5.4: Toward Generalized Coding with Our First Loop ... - z.ai</a></li>

</ul>
</details>

**Tags**: `#AI`, `#machine-learning`, `#transformers`, `#model-architecture`, `#GLM`

---

<a id="item-11"></a>
## [Ladybird browser engine releases first alpha for macOS and Linux](https://simonwillison.net/2026/Nov/23/ladybird/) ⭐️ 8.0/10

The Ladybird project released its first alpha on November 23, 2026, allowing users on macOS and Linux to install the browser without compiling it themselves. Ladybird is an independent browser engine with its own HTML parser, CSS engine, layout, JavaScript, and WebAssembly implementations. This is a significant milestone for an independent browser engine built largely from scratch, offering an alternative to the dominant Chromium, Gecko, and WebKit engines. It demonstrates that a small team can ship a functional browser with modern web capabilities, which could influence web standards and browser diversity. Ladybird still relies on external components like HarfBuzz for text shaping, Skia for 2D graphics, ffmpeg for video, and SQLite, while running each tab in a separate process for isolation. Early testing shows it handles WebAssembly tools like ffmpeg and Pyodide well, but service worker support is incomplete, causing failures such as Datasette Lite's error about navigator.serviceWorker.startMessages.

rss · Simon Willison · Nov 23, 21:46

**Background**: Ladybird originated from SerenityOS, an operating system written from scratch by Andreas Kling and contributors, and has evolved into a standalone browser project. Building a browser engine from scratch is extremely complex, requiring implementations of HTML parsing, CSS, layout, JavaScript, and WebAssembly, which is why most browsers today are based on a few established engines. HarfBuzz is a text shaping library that converts Unicode text into properly positioned glyphs, and Skia is an open-source 2D graphics library used by Chrome and others.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HarfBuzz">HarfBuzz - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Skia_Graphics_Library">Skia Graphics Library</a></li>
<li><a href="https://en.wikipedia.org/wiki/SerenityOS">SerenityOS - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#browser`, `#open-source`, `#web-standards`, `#ladybird`, `#software-release`

---

<a id="item-12"></a>
## [Sandboxed LLM Agents Can Communicate via Inference Server Side Channels](https://www.lesswrong.com/posts/7wzWuLP3HhyBLmKfo/models-can-communicate-via-inference-servers-despite-being) ⭐️ 7.0/10

A LessWrong post demonstrates that two LLM agents running on the same inference server can reliably communicate even without direct messaging or shared filesystem access, using two protocols: Step Sizing and KV Cache Message Board. These exploit side channels such as shared KV-cache contention and kernel-dependent numerical variations that arise from vLLM's batch-size-dependent kernel selection. This research reveals a novel covert channel that could undermine sandboxing assumptions in multi-agent LLM deployments, with implications for AI safety and security. It highlights the need for mitigations such as cache separation keys and batch-invariant inference to prevent unintended information leakage between isolated agents. The attacks require specific conditions: agents must be aware of each other, have pre-shared messages to check, and know the details of the inference server and its kernels. The Step Sizing protocol leverages the fact that vLLM chooses kernels based on step size, producing slightly different activations for different batch sizes, while the KV Cache Message Board exploits shared prefix caching.

hackernews · gmays · Nov 25, 02:34 · [Discussion](https://news.ycombinator.com/item?id=50637686)

**Background**: Inference servers like vLLM optimize performance by batching requests and reusing KV caches for common prefixes, but these optimizations can create side channels. A covert channel is a mechanism that allows two parties to communicate indirectly through shared resources, bypassing intended isolation. Batch-invariant inference aims to make each request's output independent of other requests in the batch, eliminating such timing and numerical variations.

<details><summary>References</summary>
<ul>
<li><a href="https://www.lesswrong.com/posts/7wzWuLP3HhyBLmKfo/models-can-communicate-via-inference-servers-despite-being">Models Can Communicate via Inference Servers Despite Being ...</a></li>
<li><a href="https://docs.vllm.ai/en/latest/features/batch_invariance/">Batch Invariance - vLLM</a></li>
<li><a href="https://arxiv.org/html/2603.10726v1">CacheSolidarity: Preventing Prefix Caching Side Channels in ...</a></li>

</ul>
</details>

**Discussion**: Commenters are divided: some argue the attacks require unrealistic conditions and deep knowledge of the stack, while others note that frontier models could easily discover such tricks, especially now that the technique is publicly documented. There is also debate over mitigations like cache separation keys and batch-invariant inference, with one commenter pointing out that the title is misleading because the models are not truly sandboxed from each other.

**Tags**: `#LLM security`, `#sandboxing`, `#covert channels`, `#inference servers`, `#AI safety`

---

<a id="item-13"></a>
## [Browser Gallery Revives Classic Nvidia and ATI GPU Tech Demos](https://gpu-demo-gallery.pages.dev/) ⭐️ 7.0/10

A new Show HN project called GPU Demo Gallery lets users run classic Nvidia and ATI tech demos directly in the browser. The gallery includes demos such as the Grass Demo and Crystal Ball, and has sparked a detailed discussion about missing features and historical context. This project makes historically significant GPU demos accessible to a wider audience, preserving graphics history and allowing younger generations to experience the evolution of real-time rendering. It also highlights the growing interest in retro-computing and browser-based emulation. The gallery currently features 23 vintage demos, but users have reported issues such as a missing 'N' in the Nvidia logo in the Grass Demo and problems with mouse interaction in Crystal Ball. Community members have also requested additional demos like Dawn (2002) and the PSX T-Rex demo, as well as more contextual information about the hardware features each demo showcased.

hackernews · arkits · Nov 25, 04:31 · [Discussion](https://news.ycombinator.com/item?id=50638503)

**Background**: Tech demos are non-interactive or interactive programs created by GPU manufacturers like Nvidia and ATI to showcase the capabilities of their graphics cards. These demos were often distributed with hardware or at trade shows and are now considered important artifacts of computer graphics history. Browser-based emulation allows these demos to run on modern systems without the need for original hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ATI_Technologies">ATI Technologies - Wikipedia</a></li>
<li><a href="https://topaihubs.com/articles/reliving-graphics-history-old-nvidia-ati-demos-now-in-your-browser">Reliving Graphics History: Old Nvidia & ATI Demos Now in Your ...</a></li>
<li><a href="https://www.youtube.com/watch?v=eB_IBXQtxAE">Explore 23 Vintage Nvidia & ATI GPU Demos in Your Browser ... nvidia-geforce-tech-demos directory listing - Archive.org Video Card Tech Demos - Download - soggi Download NVIDIA Tech Demos | NVIDIA Cool Stuff About · 3d retro graphics GPU Demos - AMD GPUOpen</a></li>

</ul>
</details>

**Discussion**: The community response is nostalgic and enthusiastic, with users sharing personal memories of their first GPUs. However, some commenters criticize the project for lacking historical context and for apparent bugs, with one asking if it was 'vibe coded.' Others suggest adding more demos and even the original box art to enhance the experience.

**Tags**: `#retro-computing`, `#GPU`, `#tech-demos`, `#browser-emulation`, `#graphics`

---

<a id="item-14"></a>
## [Essay argues competent engineers should embrace LLM tools, sparking HN debate](https://www.iankduncan.com/engineering/2026-11-19-smart-people-who-give-a-shit-use-tools) ⭐️ 7.0/10

Ian Duncan published an essay on November 19, 2026, arguing that smart engineers who care about their work should use LLM tools, which prompted a 109-comment Hacker News discussion about whether LLMs are 'just another abstraction' and how they shift incentives around verification and shipping. The debate highlights a growing tension in software engineering: LLMs dramatically lower the cost of producing code, but may also lower the cost of 'giving a shit' about verification, potentially allowing less careful developers to out-ship more diligent ones. Commenters noted that using an LLM is qualitatively different from previous abstraction shifts like assembler-to-C or C-to-JavaScript, because the core activity of modeling a problem in code is not simply abstracted away; others raised concerns about knowledge atrophy and whether recent outages stem from AI-generated code or AI-discovered legacy vulnerabilities.

hackernews · matthewsinclair · Nov 25, 07:46 · [Discussion](https://news.ycombinator.com/item?id=50639698)

**Background**: Large language models (LLMs) are increasingly used in software engineering for tasks like code generation, review, and debugging, with a growing body of research (e.g., systematic reviews of LLM4SE) mapping their impact. A common argument is that LLMs represent 'just another layer of abstraction,' similar to compilers or high-level languages, but critics argue that abstractions always leak and that LLMs change the nature of programming itself. The Hacker News discussion reflects broader industry concerns about verification gaps and accountability in AI-assisted development.

<details><summary>References</summary>
<ul>
<li><a href="https://dev.to/marcoallegretti/llms-are-just-another-layer-of-abstraction-24p8">LLMs Are Just Another Layer of Abstraction - DEV Community</a></li>
<li><a href="https://martinfowler.com/articles/convo-llm-abstractions.html">Conversation: LLMs and Building Abstractions</a></li>
<li><a href="https://arxiv.org/abs/2308.10620">[2308.10620] Large Language Models for Software Engineering ... Large Language Models for Software Engineering: A Systematic ... Large Language Model for Software Engineering - GitHub Frontiers | Research directions for using LLM in software ... Towards an understanding of large language models in software ... LLMs: A game-changer for software engineers? - ScienceDirect</a></li>

</ul>
</details>

**Discussion**: Commenters were divided: some argued that LLMs are fundamentally different from prior abstractions because they change the nature of the activity, while others warned that LLMs amplify the cost of 'giving a shit' relative to fast shipping, and that discipline is needed to avoid knowledge atrophy. A few questioned whether recent outages were caused by AI-generated code or by AI finding old human-written vulnerabilities, noting that each camp tells itself a different story.

**Tags**: `#LLMs`, `#software-engineering`, `#AI-assisted-development`, `#developer-productivity`, `#hacker-news-discussion`

---

<a id="item-15"></a>
## [Reviving Old Java Phones with Bluetooth Networking](https://antcating.github.io/2026/11/23/getting-old-java-phones-online-again.html) ⭐️ 7.0/10

A technical guide shows how to get a Sony Ericsson S500i J2ME feature phone back online by using a Raspberry Pi as a Bluetooth Personal Area Network (PAN) gateway, bypassing the phone's unusable 2G modem. As 2G networks are shut down worldwide, this work offers a practical path to keep retro feature phones and J2ME applications usable, which matters to retro-computing enthusiasts and mobile preservationists. The solution relies on Bluetooth PAN support, which is notably rare among feature phones and mostly limited to certain Sony Ericsson models; USB tethering on these phones only works in the phone-to-PC direction, not the reverse.

hackernews · waximabbax · Nov 24, 13:14 · [Discussion](https://news.ycombinator.com/item?id=50627726)

**Background**: J2ME (Java 2 Micro Edition) was a lightweight Java platform for running applications on resource-constrained mobile devices like feature phones. Many such phones relied on 2G cellular networks for internet access, and as operators retire 2G, these devices lose their native connectivity. Bluetooth Personal Area Networking allows a device to share another device's internet connection over a short-range wireless link.

<details><summary>References</summary>
<ul>
<li><a href="https://daily.dev/posts/that-java-phone-can-still-go-online-00uqf7jtl">That Java Phone Can Still Go Online - daily.dev</a></li>
<li><a href="https://news.ycombinator.com/item?id=50627726">Getting old Java phones online again | Hacker News</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters shared nostalgic and practical insights: one recalled Google's London office maintaining hundreds of J2ME test devices in cages due to vast platform variance, while others discussed Bluetooth PAN quirks, Symbian PPP workarounds like Gnubox, and retro web services such as ProtoWeb.

**Tags**: `#J2ME`, `#retro-computing`, `#mobile`, `#networking`, `#feature-phones`

---

<a id="item-16"></a>
## [Windows Loudness Equalization Reverse-Engineered and Ported to PipeWire](https://github.com/xoxorwr/pw-loudness-eq) ⭐️ 6.0/10

A developer known as xoxorwr has reverse-engineered the loudness equalization algorithm from Windows' WMALFXGFXDSP.dll and ported it to PipeWire, releasing the project as pw-loudness-eq on GitHub. The tool aims to replicate Windows' behavior of evening out the volume of each application so that quiet and loud parts play at a similar level. This project brings a long-standing Windows audio feature to Linux's PipeWire audio server, potentially improving the listening experience for users who want consistent volume across applications. It also sparks broader discussion about hidden audio processing in Windows and the ethics and necessity of reverse-engineering proprietary algorithms. The algorithm is susceptible to increasing gain of focused impulses such as whistle or pure tones, which is why additional limiting is required at the end. Community members also note that Windows applies a hidden limiter (CAudioLimiter in AudioEng.dll) via audiodg.exe on shared-mode WASAPI, DirectSound, and MME playback, but not on WASAPI exclusive or ASIO.

hackernews · ThrowNotAway · Nov 25, 11:34 · [Discussion](https://news.ycombinator.com/item?id=50641171)

**Background**: PipeWire is a low-level multimedia framework and audio server for Linux, created by Wim Taymans at Red Hat, designed to unify audio and video processing and replace PulseAudio and JACK. Loudness equalization (more accurately called loudness normalization) is a technique that adjusts gain over time to make quiet and loud parts of audio play at similar perceived levels, unlike equalization which adjusts gain per frequency band. Windows includes such processing in its shared-mode audio pipeline, but the algorithm was undocumented, prompting this reverse-engineering effort.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/PipeWire">PipeWire - Wikipedia</a></li>
<li><a href="https://www.pipewire.org/">PipeWire</a></li>

</ul>
</details>

**Discussion**: Commenters debated terminology, with one insisting the correct term is loudness normalization rather than equalization, and another questioning why reverse-engineering was necessary when simple limiter algorithms are readily available, calling the approach potentially unethical. Others highlighted that Windows' hidden limiter slightly compresses peaks on shared-mode playback, and one user expressed that reducing dynamic range is undesirable for music enjoyment.

**Tags**: `#audio-processing`, `#reverse-engineering`, `#pipewire`, `#windows`, `#loudness-normalization`

---

<a id="item-17"></a>
## [Josh Comeau Releases Professionally Recorded Button Sounds for Web UI](https://buttons.joshwcomeau.com/) ⭐️ 6.0/10

Josh Comeau launched a website (buttons.joshwcomeau.com) offering a collection of professionally recorded button click and press sounds for web interfaces. The sounds are multi-sampled with variations in pitch and timbre, and the site itself demonstrates the sounds with interactive buttons. This resource gives web developers and designers easy access to high-quality UI sounds, which can enhance user feedback and interaction design. It also highlights the challenges of browser audio restrictions, sparking discussion on how to implement sound in web apps effectively. The sounds are recorded in stereo using XY microphones in a treated environment, and some samples include pitch shifting (e.g., 'DOWN4' sounds nearly a semitone lower). Browsers, especially iOS Safari, may block audio playback, requiring user interaction to enable sound.

hackernews · gaurang_tandon · Nov 25, 03:23 · [Discussion](https://news.ycombinator.com/item?id=50638032)

**Background**: The Web Audio API is a high-level JavaScript API for processing and synthesizing audio in web applications, enabling developers to create rich sound experiences. However, browsers often block autoplay of audio to protect users from unexpected noise, requiring user gestures to start audio. UI sound design is a niche but important field that focuses on providing auditory feedback for user actions, improving usability and experience.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/Media/Guides/Autoplay">Autoplay guide for media and Web Audio APIs - Media | MDN Usage example</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API">Web Audio API - Web APIs | MDN - MDN Web Docs</a></li>
<li><a href="https://uisfx.com/ui-sound-design">UI Sound Design Guide: Interface Sound Effects | UI SFX</a></li>

</ul>
</details>

**Discussion**: Commenters praised the project as fun and inspiring, with one suggesting eliminating pitch shifting to keep variations subtle. Others discussed browser audio restrictions, noting that flipping the mute switch on iPhone can allow audio, and questioned the choice of stereo over mono recording.

**Tags**: `#web-audio`, `#ui-design`, `#sound-design`, `#frontend`, `#developer-tools`

---

<a id="item-18"></a>
## [Economics Professor Distills Macrohistory into Six Facts, Sparking HN Debate](https://basilhalperin.com/essays/macrohistory.html) ⭐️ 6.0/10

An economics professor published an essay titled 'Macrohistory in Six Facts' on his personal website, summarizing long-run macroeconomic history into six key observations. The essay was shared on Hacker News, where it garnered 146 points and 78 comments, with discussion focusing on the framing of 'macrohistory' and the statistical presentation of the data. The essay and its discussion highlight the ongoing interest in long-run economic growth patterns and how they are communicated to broader audiences. The critiques raised in the HN thread underscore the importance of careful data visualization and clear terminology when presenting stylized facts about economic history. Commenters specifically criticized the 'Fact 6' graph, which plots log(doubling time) against log(time before present), arguing that any straight line on such a graph would imply a singularity at the present and that doubling time itself involves another logarithm, making it undefined for negative growth. Others noted that the term 'macrohistory' was expected to cover broader historical aspects beyond economics.

hackernews · tptacek · Nov 25, 03:04 · [Discussion](https://news.ycombinator.com/item?id=50637891)

**Background**: Macrohistory refers to the study of long-term patterns in political, economic, and social change, often using quantitative data to identify stylized facts about economic growth. In economics, 'stylized facts' are broad empirical regularities that theoretical models aim to explain, such as the divergence of income across countries over the long run. The essay's approach of distilling history into a few key facts is a common pedagogical device in economics.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Long_run_and_short_run">Long run and short run - Wikipedia</a></li>
<li><a href="https://www.amazon.com/Macrohistory-Essays-Sociology-Long-Run/dp/0804735239">Amazon.com: Macrohistory : Essays in Sociology of the Long Run ...</a></li>

</ul>
</details>

**Discussion**: HN commenters engaged in a substantive debate: some questioned the term 'macrohistory' as being too narrow (focused only on money), while others critiqued the statistical validity of the doubling-time graph. A few recommended related reading, such as 'More from Less,' and reflected on the strangeness of modern economic life compared to the long sweep of history.

**Tags**: `#economics`, `#macrohistory`, `#long-run-growth`, `#data-visualization`, `#hacker-news-discussion`

---

<a id="item-19"></a>
## [Versine launches MCP for AI agents to send and request money](https://news.ycombinator.com/item?id=50634426) ⭐️ 6.0/10

Versine, a YC-backed startup, launched an MCP that allows AI agents to send and request money from a self-custodial USDC wallet on Base, with passkey approval for transactions. The product is available on iOS, Android, and as an MCP for ChatGPT and Claude, plus a public MCP and REST API for other agents. This is an early application of the Model Context Protocol to payments, potentially enabling AI assistants to automate financial tasks like splitting bills and settling debts, which could reshape how consumers interact with money. However, it also raises significant concerns about fraud, dispute resolution, and trust in AI-driven transactions. Versine uses self-custodial stablecoin wallets storing USDC on Base to avoid money transmission regulations, and supports one-time or recurring standing permissions, trusted contacts for no-approval sends, and claim forwarding to non-users via OTP verification. The team had only four weeks to build after a pivot, which drove the stablecoin approach.

hackernews · harshithl1777 · Nov 24, 20:44

**Background**: The Model Context Protocol (MCP) is an open standard developed by Anthropic that lets AI applications like Claude and ChatGPT connect to external tools and data sources. Passkeys are cryptographic credentials based on public-key cryptography, standardized by the FIDO Alliance and W3C WebAuthn, used for passwordless authentication. Stablecoins like USDC are cryptocurrencies pegged to fiat currencies, often used for fast, low-cost transfers.

<details><summary>References</summary>
<ul>
<li><a href="https://modelcontextprotocol.io/">What is the Model Context Protocol ( MCP )? - Model Context Protocol</a></li>
<li><a href="https://en.wikipedia.org/wiki/Passkey_(authentication)">Passkey (authentication)</a></li>
<li><a href="https://www.anthropic.com/news/model-context-protocol">Introducing the Model Context Protocol \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Commenters raised concerns about fraud and dispute resolution, with one former payments fraud engineer asking about reversal flows if an agent pays the wrong person. Others questioned the viability of the business model, comparing it to SpherePay and noting that demand for such services may be higher outside the US, while some offered suggestions like earning yield on USDC and expanding to the UK.

**Tags**: `#MCP`, `#fintech`, `#payments`, `#AI agents`, `#startup`

---

<a id="item-20"></a>
## [datasette-charts 0.2a0 adds Datasette Agent integration for chat-based chart creation](https://simonwillison.net/2026/Nov/24/datasette-charts/) ⭐️ 6.0/10

datasette-charts 0.2a0, released on November 24, 2026, adds integration with Datasette Agent, allowing users to request charts via chat and have them generated using the same underlying chart suggestion and generation tools. A demo video shows the agent creating a chart from a prompt and responding to changes made in the chart builder panel. This update makes chart creation more accessible for Datasette users by enabling natural language interaction, reflecting the broader trend of embedding AI agents into data tools to lower the barrier to exploratory data analysis. The integration works on agent.datasette.io, where users can sign in with GitHub to try the plugin, and the agent can notice when a user changes the chart in the panel and describe the new chart accordingly. The plugin builds on the charting capabilities introduced in datasette-charts 0.1a0, which uses vendored D3, Observable Plot, and topojson-client.

rss · Simon Willison · Nov 24, 04:24

**Background**: Datasette is an open-source tool for exploring and publishing data, created by Simon Willison, that lets users query SQLite databases via a web interface. Datasette Agent is a plugin that adds a chat interface to Datasette, enabling users to ask questions about their data in natural language. datasette-charts is a plugin that generates charts from tables or SQL queries, and version 0.2a0 integrates it with the agent so charts can be created conversationally.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Nov/23/datasette-charts/">Release: datasette - charts 0.1a0 | Simon Willison’s Weblog</a></li>
<li><a href="https://simonwillison.net/">Simon Willison’s Weblog</a></li>
<li><a href="https://devlery.com/en/blog/datasette-agent-sqlite-ai-assistant">Datasette Agent shows why narrow AI agents matter - Devlery</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#data-visualization`, `#ai-agents`, `#plugins`, `#release`

---