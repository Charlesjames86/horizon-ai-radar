---
layout: default
title: "Horizon Summary: 2026-09-04 (EN)"
date: 2026-09-04
lang: en
---

> From 31 items, 24 important content pieces were selected

---

1. [OpenAI Unveils GPT-6 Astra with Major Benchmark Gains](#item-1) ⭐️ 10.0/10
2. [Solving Jane Street's Reverse Engineering Challenge: A Detailed Write-up](#item-2) ⭐️ 8.0/10
3. [Hackers Had Live Feed of ID Verification Scans for Over a Year](#item-3) ⭐️ 8.0/10
4. [Go Grandmaster Shin Jinseo Defeats AI KataGo with Two-Stone Handicap](#item-4) ⭐️ 8.0/10
5. [Porting a 1993 Amiga Game to Godot Using an LLM to Read 68000 Assembly](#item-5) ⭐️ 8.0/10
6. [Deepity C++ Library Shows Predictive Coding Networks Match Backprop on MNIST](#item-6) ⭐️ 8.0/10
7. [Jasper Research Releases Cookbook for Training Text-to-Image Models from Scratch](#item-7) ⭐️ 8.0/10
8. [Claude Code v2.1.260 Adds Diff Panel and Cache Diagnostics](#item-8) ⭐️ 7.0/10
9. [Verisign Proposes Terminating .name Third-Level Domains](#item-9) ⭐️ 7.0/10
10. [Qwen 3.8 27B on Cerebras Hits 1500 tok/s but Rate Limits and Costs Raise Concerns](#item-10) ⭐️ 7.0/10
11. [Artificial Beaver Dams Boost Coho Salmon Survival from 8% to 60%](#item-11) ⭐️ 7.0/10
12. [Gwern's Retrospective on Project Xanadu: Lessons and Legacy](#item-12) ⭐️ 7.0/10
13. [K2 Horizon: Six Fully Open AI Models Released](#item-13) ⭐️ 7.0/10
14. [Which Tools Do AI Coding Agents Prefer? A 17k Run Analysis](#item-14) ⭐️ 7.0/10
15. [GPS Glitch Across US Causes Errors Up to 33 Feet](#item-15) ⭐️ 7.0/10
16. [MCP in Production: Real-World Use Cases and Debates](#item-16) ⭐️ 7.0/10
17. [Anthropic Updates Claude System Prompts with Song Lyric Restrictions](#item-17) ⭐️ 7.0/10
18. [Grounding LLMs with JEPA World Models Trained in Simulation](#item-18) ⭐️ 7.0/10
19. [Pilot-Based Protocol Determines LLM Query Repetition for Reliability](#item-19) ⭐️ 7.0/10
20. [llm-gemini 0.34 Adds Gemini 3.8 Flash Support and Async Bug Fix](#item-20) ⭐️ 6.0/10
21. [AAAI-27 Desk Rejection for Minor Abstract Edits Sparks Concern](#item-21) ⭐️ 6.0/10
22. [Mol-JEPA: Multimodal JEPA-Based Molecular Foundation Model](#item-22) ⭐️ 6.0/10
23. [Massive TikTok Dataset Released on Hugging Face](#item-23) ⭐️ 6.0/10
24. [CABiNet vs YOLO26-sem on UAVid: Accuracy, Compute, and GPU Latency Benchmark](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI Unveils GPT-6 Astra with Major Benchmark Gains](https://openai.com/index/gpt-6-astra/) ⭐️ 10.0/10

OpenAI has announced GPT-6 Astra, a major new AI model, along with its system card. The model shows significant improvements on benchmarks like ARC-AGI-3 and the Artificial Analysis Coding Agent Index. This release represents a major step in frontier AI development, potentially impacting industries that rely on advanced reasoning and coding capabilities. The high community engagement underscores its significance in shaping the future of AI models. The system card is available at deploymentsafety.openai.com/gpt-6-astra. However, the ARC-AGI-3 scorecard has been criticized for being misleading, as it shows a score of 7.8% while the model is estimated to score around 30% with the Responses API harness.

hackernews · kibae · Sep 3, 18:41 · [Discussion](https://news.ycombinator.com/item?id=49554643)

**Background**: ARC-AGI-3 is an interactive reasoning benchmark that challenges AI agents to explore novel environments and build adaptable world models. The Artificial Analysis Coding Agent Index evaluates coding agent performance across various tasks. These benchmarks are used to measure progress toward artificial general intelligence (AGI).

<details><summary>References</summary>
<ul>
<li><a href="https://arcprize.org/arc-agi/3">ARC - AGI - 3</a></li>
<li><a href="https://artificialanalysis.ai/">AI Model & API Providers Analysis | Artificial Analysis</a></li>
<li><a href="https://www.linkedin.com/pulse/ais-dirty-little-secret-why-most-benchmarks-joke-how-changes-danu-s-jmiqc">AI's Dirty Little Secret: Why Most Benchmarks Are a Joke...</a></li>

</ul>
</details>

**Discussion**: Community comments highlight concerns about the ARC-AGI-3 scorecard's transparency, with one user noting the discrepancy between the reported score and the estimated score with a different harness. Others express excitement about improved user prompting and collaboration, while some point out that speed remains a bottleneck. There is also discussion about whether progress is merely skill acquisition rather than true intelligence.

**Tags**: `#AI`, `#OpenAI`, `#GPT-6`, `#machine learning`, `#frontier models`

---

<a id="item-2"></a>
## [Solving Jane Street's Reverse Engineering Challenge: A Detailed Write-up](https://jestoph.com/2026/09/04/jane-street-challenge.html) ⭐️ 8.0/10

A developer published a comprehensive write-up of solving the Jane Street reverse engineering challenge, detailing the handling of GDSII format and netlist extraction. The post includes insights into the technical process and community feedback on alternative tools. This write-up showcases advanced reverse engineering skills applied to hardware puzzles, highlighting the growing interest in chip-level security and open-source EDA tools. It provides a valuable learning resource for the community and underscores the importance of understanding industry-standard formats like GDSII. The challenge involved parsing GDSII files and extracting netlists, which are critical for reconstructing circuit layouts. The author likely used custom scripts or tools, while commenters suggested alternatives like Degate and KLayout's Python API, as well as yosys for assertion checking.

hackernews · anitil · Sep 4, 10:17 · [Discussion](https://news.ycombinator.com/item?id=49562657)

**Background**: GDSII is a binary file format that serves as the de facto industry standard for IC layout data exchange in electronic design automation (EDA). Netlist extraction is the process of translating an IC layout back into an electrical circuit representation, which is essential for simulation, verification, and analysis. These concepts are fundamental to understanding the challenge and the solutions discussed.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GDSII">GDSII - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Netlist_extraction">Netlist extraction</a></li>

</ul>
</details>

**Discussion**: The community discussion was positive and constructive, with members congratulating the author and sharing alternative approaches. Some comments highlighted the use of open-source tools like Degate and KLayout, while others joked about the author's future career prospects at Jane Street. A few noted the perceived NIH (Not Invented Here) syndrome in the author's custom solution.

**Tags**: `#reverse engineering`, `#GDSII`, `#hardware`, `#puzzle`, `#open source`

---

<a id="item-3"></a>
## [Hackers Had Live Feed of ID Verification Scans for Over a Year](http://www.techdirt.com/2026/09/03/hackers-had-a-live-feed-of-every-id-this-verification-company-scanned-for-over-a-year/) ⭐️ 8.0/10

Hackers had a live feed of every ID verification company scanned for over a year, as reported by Techdirt. This breach exposed sensitive identity documents and verification data, highlighting systemic flaws in the identity verification industry. This breach is significant because it compromises the trust in identity verification systems used by governments and businesses, potentially enabling identity theft and fraud. It underscores the urgent need for more secure and privacy-preserving identity verification methods, especially as age-verification laws expand. The breach reportedly involved a major identity verification company, with Krebs on Security linking it to an active breach affecting Fortune 500 customers. The live feed lasted over a year, indicating a prolonged and undetected compromise.

hackernews · beardyw · Sep 4, 06:47 · [Discussion](https://news.ycombinator.com/item?id=49561320)

**Background**: Identity verification companies collect and process sensitive personal documents, such as driver's licenses and passports, to confirm individuals' identities for various services. These systems often rely on centralized databases, making them attractive targets for hackers. The breach highlights the risks of storing such data centrally and the need for more robust security measures.

<details><summary>References</summary>
<ul>
<li><a href="https://krebsonsecurity.com/">Krebs on Security – In-depth security news and investigation</a></li>
<li><a href="https://techcrunch.com/2026/09/02/it-sure-looks-like-hackers-breached-a-major-id-card-verification-service/">It sure looks like hackers breached a major ID card ...</a></li>

</ul>
</details>

**Discussion**: Community comments criticized the design of ID verification systems, with one user advocating for PKI-based trust chains and zero-knowledge proofs to minimize data exposure. Another user praised Brian Krebs' article as a better read, while others expressed frustration with non-technical decision-makers and suggested government-mediated digital wallets as a preferable alternative.

**Tags**: `#security`, `#privacy`, `#identity verification`, `#data breach`, `#hacking`

---

<a id="item-4"></a>
## [Go Grandmaster Shin Jinseo Defeats AI KataGo with Two-Stone Handicap](https://www.kedglobal.com/artificial-intelligence/newsView/ked202607210007) ⭐️ 8.0/10

Shin Jinseo, the world's No. 1 Go player, defeated the top AI engine KataGo by 4.5 points in Game 2 of the Ssen Math·Hankyung Gishinjeon, becoming the first human to win an official match under a two-stone handicap. This milestone highlights human strategic creativity against current AI systems, showing that even top Go AIs have exploitable weaknesses. It has technical implications for AI robustness and rekindles debate about the limits of human-AI competition in board games. The two-stone handicap is considered the absolute boundary for human competition against modern AI, as no human can win an even game. Shin's victory came through a complex variation of the 'flying knife' joseki, which led to an equal position and exploited KataGo's blind spots.

hackernews · gmays · Sep 3, 01:11 · [Discussion](https://news.ycombinator.com/item?id=49544762)

**Background**: Go is an ancient board game with a 19x19 grid, where players place stones to surround territory. KataGo is an open-source AI that trains by self-play, becoming stronger over time. Handicaps are traditionally used to balance games between players of different strengths, with stones placed on the board before play.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Handicapping_in_Go">Handicapping in Go - Wikipedia</a></li>
<li><a href="https://senseis.xmp.net/?Handicap">Handicap at Sensei's Library Go grandmaster Shin defeats AI KataGo in historic human ... Go handicaps - Rules and strategy of Go games Go Handicap Stones Calculator for Fair Pairings Top Human Go Player Shin Jin-seo Beats AI with Two-Stone Handicap Handicap Placement at Sensei's Library</a></li>
<li><a href="https://medium.com/the-polymaths-journey/katagos-gotta-go-a6914fdb7b0f">KataGo ’s Gotta Go . The past few months have been a… | by... | Medium</a></li>

</ul>
</details>

**Discussion**: Commenters noted Shin's extraordinary strength, being significantly ahead of other humans in rating, and that his victory exploited a known weakness in KataGo. Some clarified that the handicap means Shin is weaker, but even games are unwinnable for humans, while others drew parallels to historic AI victories like Deep Blue and AlphaGo.

**Tags**: `#Go`, `#AI`, `#KataGo`, `#human vs AI`, `#game playing`

---

<a id="item-5"></a>
## [Porting a 1993 Amiga Game to Godot Using an LLM to Read 68000 Assembly](https://babyloniantwins.com/blog/porting-a-1993-amiga-game-to-godot/) ⭐️ 8.0/10

A developer successfully ported his 1993 Amiga game, originally written in MC68000 assembly, to the Godot engine using an LLM (Claude) to translate the assembly code. The initial port was completed in a single evening, with additional weekends spent polishing the feel and shipping. This demonstrates a novel, practical use of LLMs for retro game porting, potentially lowering the barrier for preserving and modernizing classic games. It highlights how AI can assist in understanding and translating legacy code, which could impact the retro gaming community and software preservation efforts. The developer used vasm on a Mac to assemble the code, aiming for a byte-identical binary to the original. A 108-byte mismatch was discovered, attributed to the original game being saved from memory after running, rather than being a clean assembler output. The developer also released the original game for free.

hackernews · rabahs · Sep 3, 14:28 · [Discussion](https://news.ycombinator.com/item?id=49550375)

**Background**: The Amiga is a classic home computer popular in the late 1980s and early 1990s, often programmed in MC68000 assembly for performance. Godot is a modern open-source game engine that supports 2D and 3D game development. LLMs like Claude can analyze and translate code, making it possible to port legacy assembly code to higher-level languages or modern engines.

<details><summary>References</summary>
<ul>
<li><a href="https://godotengine.org/">Godot Engine - Free and open source 2D and 3D game engine</a></li>
<li><a href="http://sun.hasenbraten.de/vasm/">vasm portable and retargetable assembler</a></li>
<li><a href="https://en.wikipedia.org/wiki/Godot_(game_engine)">Godot (game engine)</a></li>

</ul>
</details>

**Discussion**: Community comments expressed amazement at the developer's original assembly programming and shared similar experiences with LLM-based porting. Some discussed technical nuances like the 50Hz vs 60Hz refresh rate differences between PAL and NTSC Amiga systems, and others noted the nostalgic value and potential inspiration from other games.

**Tags**: `#LLM`, `#retro-gaming`, `#Godot`, `#assembly`, `#porting`

---

<a id="item-6"></a>
## [Deepity C++ Library Shows Predictive Coding Networks Match Backprop on MNIST](https://www.reddit.com/r/MachineLearning/comments/1w5fuhm/deepity_a_c_library_showing_predictive_coding/) ⭐️ 8.0/10

A new C++ library called Deepity demonstrates that predictive coding networks (PCNs) can achieve 97.73% test accuracy on MNIST in about 60 seconds, closely matching the 98.27% accuracy of backpropagation in PyTorch (~70s). The implementation uses recent research on direct Kolen-Pollack feedback alignment and algorithmic caching to close the performance gap. This is significant because predictive coding networks offer a biologically plausible alternative to backpropagation, with potential advantages in continual learning and energy efficiency. Demonstrating competitive performance on a standard benchmark could encourage further research and adoption of PCNs in practical machine learning applications. The library is implemented in C++ and runs on CPU, with benchmarks showing 97.73% accuracy in 59.5 seconds versus PyTorch's 98.27% in ~70 seconds over 50 epochs. The author plans to port the kernels to CUDA for scaling and to test continual learning scenarios where backpropagation struggles.

reddit · r/MachineLearning · /u/Important-Home4431 · Sep 2, 16:49

**Background**: Predictive coding networks (PCNs) are a biologically inspired framework for hierarchical computation, offering an alternative to traditional feedforward neural networks. They have been studied for their potential in continual learning and biological plausibility, but naive implementations are often slow. Direct Kolen-Pollack feedback alignment is a technique that improves error transmission in PCNs, and algorithmic caching helps reduce redundant computations during inference.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2602.15571">[2602.15571] Accelerated Predictive Coding Networks via Direct Kolen-Pollack Feedback Alignment</a></li>
<li><a href="https://arxiv.org/html/2602.15571">Accelerated Predictive Coding Networks via Direct Kolen–Pollack Feedback Alignment</a></li>
<li><a href="https://arxiv.org/pdf/2506.06332">Introduction to Predictive Coding Networks for Machine Learning</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#Predictive Coding`, `#C++`, `#MNIST`, `#Backpropagation`

---

<a id="item-7"></a>
## [Jasper Research Releases Cookbook for Training Text-to-Image Models from Scratch](https://www.reddit.com/r/MachineLearning/comments/1w5c9rd/detailed_explanation_of_how_to_create_a/) ⭐️ 8.0/10

Jasper Research released a comprehensive cookbook that details how to build a text-to-image model from scratch, including a 100M-image dataset named MONET and a codebase called nano-t2i. The cookbook shares full reasoning and intermediate results, allowing users to train their own models. This resource lowers the barrier for researchers and practitioners to understand and replicate the techniques used by frontier labs in text-to-image generation. It provides a practical, hands-on path for deep learning enthusiasts to gain expertise in a rapidly evolving field. The cookbook is available as an interactive report on Hugging Face Spaces, and the dataset MONET is the largest open image-text dataset, built from 2.9 billion images and refined to 104.9 million high-quality samples. The nano-t2i codebase includes a tiny model that can be trained from scratch, making it accessible even with limited computational resources.

reddit · r/MachineLearning · /u/dh7net · Sep 2, 14:40

**Background**: Text-to-image models generate images from textual descriptions, typically using diffusion models or vision transformers. Training such models usually requires massive datasets and significant computational power, which has limited experimentation to large labs. This cookbook aims to democratize access by providing a complete, open-source pipeline with a smaller-scale dataset and model.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/jasperai/monet">MONET: Lowering the bar for World-Class Image Generation research.</a></li>
<li><a href="https://huggingface.co/docs/diffusers/en/training/text2image">Text-to-image - Hugging Face</a></li>
<li><a href="https://github.com/markhliu/txt2img">GitHub - markhliu/txt2img: Build text-to-image generative AI ...</a></li>

</ul>
</details>

**Discussion**: The Reddit community expressed strong interest and appreciation for the resource, with many praising the inclusion of a dataset and codebase. Some users asked clarifying questions about the dataset's composition and the model's training requirements, while others noted the value of having a practical guide from a research group.

**Tags**: `#text-to-image`, `#machine learning`, `#tutorial`, `#deep learning`, `#generative models`

---

<a id="item-8"></a>
## [Claude Code v2.1.260 Adds Diff Panel and Cache Diagnostics](https://github.com/anthropics/claude-code/releases/tag/v2.1.260) ⭐️ 7.0/10

Anthropic released Claude Code v2.1.260, introducing a diff panel that opens in fullscreen mode to show uncommitted changes, accessible via the /diff command. The update also adds likely causes for prompt-cache misses to /cost and the status line, plus /reload-plugins and a text form of /advisor for headless sessions. This release enhances developer productivity by making code review of AI-generated edits more visual and accessible, while improving transparency around prompt caching costs. It also expands functionality for headless and desktop environments, benefiting a wide range of Claude Code users. The diff panel is available in fullscreen mode and can be toggled with /diff, showing uncommitted changes as Claude edits. Cache miss diagnostics now indicate likely causes such as tool definition changes or idle past the TTL, and the update includes numerous bug fixes, including permission rule handling and model switching issues.

github · ashwin-ant · Sep 3, 23:48

**Background**: Claude Code is Anthropic's AI-powered coding assistant available as a CLI and VS Code extension. Prompt caching reduces token usage and costs by reusing cached prefixes, but misses can occur when the system prompt changes or after idle periods. The /diff command helps developers review AI-generated changes before committing, and headless sessions are used in desktop apps and SDK integrations.

<details><summary>References</summary>
<ul>
<li><a href="https://code.claude.com/docs/en/vs-code">Use Claude Code in VS Code - Claude Code Docs</a></li>
<li><a href="https://code.claude.com/docs/en/prompt-caching">How Claude Code uses prompt caching - Claude Code Docs</a></li>
<li><a href="https://code.claude.com/docs/en/claude-apps-gateway-config">Claude apps gateway configuration - Claude Code Docs</a></li>

</ul>
</details>

**Tags**: `#Claude Code`, `#release`, `#AI coding assistant`, `#developer tools`

---

<a id="item-9"></a>
## [Verisign Proposes Terminating .name Third-Level Domains](https://neil.fraser.name/news/2026/09/03/) ⭐️ 7.0/10

Verisign has proposed terminating all third-level .name domains (x.y.name) and releasing the corresponding second-level domains (y.name), affecting existing registrations. The proposal is currently under discussion and has not yet been finalized. This policy change could disrupt existing websites and email services that rely on third-level .name domains, raising concerns about ICANN's stability mission and potential domain squatting. It highlights the fragility of domain name ownership and the power dynamics between registries, registrars, and registrants. The proposal does not mention reserving released second-level domains to prevent squatting, which has drawn criticism. Existing second-level .name domains (e.g., dvt.name) are not affected, only third-level ones under them.

hackernews · pavel_lishin · Sep 3, 14:54 · [Discussion](https://news.ycombinator.com/item?id=49550772)

**Background**: A domain name consists of top-level, second-level, and third-level parts. .name is a generic top-level domain (gTLD) operated by Verisign, originally designed for personal names, allowing registrations at both second and third levels. ICANN's mission is to ensure the stable and secure operation of the Internet's unique identifier systems, which some argue conflicts with arbitrary termination of existing registrations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ICANN">ICANN - Wikipedia</a></li>
<li><a href="https://www.icann.org/">Internet Corporation for Assigned Names and Numbers (ICANN)</a></li>
<li><a href="https://www.icann.org/en/governance/bylaws">Bylaws FOR INTERNET CORPORATION FOR ASSIGNED NAMES ... - ICANN</a></li>

</ul>
</details>

**Discussion**: Commenters expressed shock and concern, noting the contradiction with ICANN's stability mission and the risk of domain squatting. Some clarified that only third-level domains are affected, not second-level ones, and others drew parallels to the leased nature of domain names, suggesting that relying on them for identity is risky.

**Tags**: `#DNS`, `#ICANN`, `#domain policy`, `#internet governance`, `#Verisign`

---

<a id="item-10"></a>
## [Qwen 3.8 27B on Cerebras Hits 1500 tok/s but Rate Limits and Costs Raise Concerns](https://inference-docs.cerebras.ai/models/overview) ⭐️ 7.0/10

Qwen 3.8 27B is now available on Cerebras Inference, claiming speeds up to 1500 tokens per second. However, users report significant rate limits and billing issues that may hinder practical use. This announcement highlights the growing competition in high-speed LLM inference, but the practical limitations underscore the gap between peak performance and real-world usability. It affects developers and enterprises seeking cost-effective, high-throughput AI solutions. The public endpoint has a token-per-minute limit of 450,000, which one user hit in about 90 seconds, burning $1.10. Cached tokens count toward the limit, and some enterprise accounts face billing access restrictions, preventing self-serve billing.

hackernews · altertable · Sep 3, 18:32 · [Discussion](https://news.ycombinator.com/item?id=49554520)

**Background**: Cerebras Inference uses wafer-scale engines to deliver extremely high token throughput, often exceeding GPU-based solutions. Qwen 3.8 27B is a 27-billion-parameter vision-language model from Alibaba's Qwen family, designed for general text generation and agentic tasks. The model is also available on other platforms like OpenRouter, but at much lower speeds.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cerebras.ai/inference">Inference - Cerebras</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-27B">Qwen/Qwen3.8-27B · Hugging Face</a></li>
<li><a href="https://simonwillison.net/2026/Aug/16/qwen-38-27b/">Qwen 3.8 27B is excellent, but it defaults to wildly overthinking things</a></li>

</ul>
</details>

**Discussion**: Community comments express mixed sentiment: some praise the speed but criticize the rate limits and cost, noting that cached tokens count toward limits and billing issues exist. Others suggest alternatives like local inference on RTX 5090 or using OpenRouter, while some report positive experiences with the speed and quality for code review tasks.

**Tags**: `#AI`, `#LLM`, `#Inference`, `#Cerebras`, `#Qwen`

---

<a id="item-11"></a>
## [Artificial Beaver Dams Boost Coho Salmon Survival from 8% to 60%](https://www.discoverwildlife.com/animal-facts/artificial-beaver-dams-california) ⭐️ 7.0/10

A recent study in California found that installing artificial beaver dams increased juvenile coho salmon survival rates from 8% to 60%. This dramatic improvement highlights the effectiveness of nature-based solutions for habitat restoration. This finding is significant because it offers a cost-effective and ecologically sound method to restore salmon populations, which are crucial for both ecosystem health and commercial fisheries. It also supports the broader trend of using nature-based solutions to address environmental challenges. The artificial beaver dams were constructed in a California stream and resulted in a survival rate increase from 8% to 60% for juvenile coho salmon. Interestingly, water temperatures decreased after damming, likely due to increased groundwater exchange, which may benefit salmon.

hackernews · speckx · Sep 3, 16:21 · [Discussion](https://news.ycombinator.com/item?id=49552572)

**Background**: Coho salmon are anadromous fish that migrate from freshwater to the ocean and back to spawn. Beaver dams create deep pools and slow-water habitats that are essential for juvenile salmon survival, but beaver populations have declined due to habitat loss and hunting. Artificial beaver dams mimic these structures to restore critical habitat without relying on live beavers.

**Discussion**: Commenters expressed enthusiasm for the positive results, with some noting related engineering comparisons and historical restoration efforts. Others shared personal observations of coho fry declines in areas lacking beaver dams, reinforcing the importance of such interventions. A few voiced cautious optimism about the long-term sustainability of these projects.

**Tags**: `#ecology`, `#conservation`, `#salmon`, `#beaver dams`, `#restoration`

---

<a id="item-12"></a>
## [Gwern's Retrospective on Project Xanadu: Lessons and Legacy](https://gwern.net/xanadu) ⭐️ 7.0/10

Gwern published a detailed retrospective on Project Xanadu in 2025, analyzing its failures and enduring ideas in hypertext and computing. The article examines why the project failed despite its visionary concepts. This retrospective offers valuable insights for modern developers working on hypertext, collaborative editing, and distributed systems. It connects historical ideas like transclusion and permalinks to contemporary technologies such as CRDTs, sparking relevant discussions. The article is hosted on Gwern's website and has a score of 7.0/10, indicating high engagement. Community comments discuss the relevance of Xanadu's principles to current problems like storage management and the potential of CRDTs in git.

hackernews · andsoitis · Sep 4, 01:45 · [Discussion](https://news.ycombinator.com/item?id=49559522)

**Background**: Project Xanadu, founded by Ted Nelson in 1960, was the first hypertext project, aiming to create a deep, interconnected system with features like transclusion and two-way links. However, it was overshadowed by the World Wide Web, which adopted a simpler model. CRDTs (Conflict-free Replicated Data Types) are data structures that allow concurrent updates without coordination, relevant to modern collaborative editing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Project_Xanadu">Project Xanadu - Wikipedia</a></li>
<li><a href="https://www.xanadu.com/xuTheModel/">The xanadu model</a></li>
<li><a href="https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type">Conflict-free replicated data type - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community comments express mixed views: some argue Xanadu's ideas still solve real problems, while others note limitations of transclusion. There is discussion on how CRDTs and permalinks could be integrated into modern tools like git, showing ongoing relevance.

**Tags**: `#hypertext`, `#history of computing`, `#Project Xanadu`, `#technical analysis`, `#CRDT`

---

<a id="item-13"></a>
## [K2 Horizon: Six Fully Open AI Models Released](https://ifm.ai/blog/k2/) ⭐️ 7.0/10

IFM released K2 Horizon, a fleet of six fully open-source AI models ranging from 0.9B to 375B parameters, under the Apache 2.0 license. The release includes training code, checkpoints, logs, data or reconstruction recipes, quantization support, and deployment tooling. This release is significant because it offers a fully transparent alternative to closed models, addressing concerns about societal manipulation and trust. It provides developers with a range of options from edge to enterprise, potentially accelerating adoption of open-weight models in self-hosted environments. The fleet includes a dense 32B model and a 36B-A4B model with approximately 4B active parameters, both positioned for local deployment. The flagship 375B-A23B model scores 47 on the Artificial Analysis Intelligence Index, but community benchmarks suggest the 32B model lags behind Qwen3.8 27B in some tests.

hackernews · karimf · Sep 3, 15:36 · [Discussion](https://news.ycombinator.com/item?id=49551760)

**Background**: Open-source AI models provide transparency by releasing weights, training data, and code, allowing scrutiny and customization. This contrasts with closed models where underlying details are hidden. K2 Horizon aims to offer frontier performance with radical openness, joining other efforts like Nvidia's Nemotron.

<details><summary>References</summary>
<ul>
<li><a href="https://ifm.ai/blog/k2">Introducing K2 Horizon: Frontier Performance, Radically Open</a></li>
<li><a href="https://ifm.ai/k2/">K2 Horizon: Open-Source AI Models for Every Scale | IFM</a></li>
<li><a href="https://aicybr.com/blog/k2-horizon-open-models-training-data-code">K2 Horizon: Six Fully Open AI Models from 0.9B to 375B, with ...</a></li>
<li><a href="https://artificialanalysis.ai/models/k2-horizon-375b-a23b">K2 Horizon 375B A23B - Intelligence, Performance & Price ...</a></li>
<li><a href="https://aireiter.com/blog/k2-horizon-models">K2 Horizon Models: Which Size Should You Run? (2026)</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed sentiment: some praise the fully open approach, while others question performance claims and note quality issues. For instance, one user found the 3.7B model unreliable for coding tasks, and another pointed out that the 32B model underperforms compared to Qwen3.8 27B. There is also a general sense of 'model fatigue' due to the rapid pace of releases.

**Tags**: `#open-source`, `#AI`, `#models`, `#LLM`, `#transparency`

---

<a id="item-14"></a>
## [Which Tools Do AI Coding Agents Prefer? A 17k Run Analysis](https://armature.tech/blog/which-tools-coding-agents-install) ⭐️ 7.0/10

Armature published an empirical analysis of 17,000 runs to reveal which third-party tools Claude, Codex, and Cursor prefer to install during software development tasks. The study analyzed public GitHub repositories across 10 programming languages to establish a balanced panel of 75 repositories. This provides developers and companies with data-driven insights into AI agent tool preferences, which is crucial for optimizing developer tools and marketing strategies. Understanding these patterns helps businesses tailor their products to be more discoverable and appealing to AI agents, a growing market segment. The analysis covers 17,000 runs and 75 repositories across 10 programming languages, using real-world statistics to ensure representativeness. The findings highlight significant differences in tool selection among Claude, Codex, and Cursor, which can inform tool integration and agent-oriented design.

hackernews · screm · Sep 3, 21:20 · [Discussion](https://news.ycombinator.com/item?id=49557206)

**Background**: AI coding agents like Claude Code, Cursor, and OpenAI Codex are autonomous systems that assist developers by planning and executing coding tasks. They often rely on external tools and services, and understanding their preferences is important for developers and companies aiming to integrate with or sell to these agents. This study is part of a growing body of empirical research on AI coding agents' behavior.

<details><summary>References</summary>
<ul>
<li><a href="https://aitoolly.com/ai-news/article/2026-09-04-benchmarking-ai-coding-agents-a-deep-dive-into-tool-selection-across-17000-experimental-runs">How AI Coding Agents Choose Tools: A 17,000 Run Analysis</a></li>
<li><a href="https://arxiv.org/pdf/2511.04824">Agentic Refactoring: An Empirical Study of AI Coding Agents</a></li>

</ul>
</details>

**Discussion**: Commenters shared practical insights: one noted the golden age of AI and concerns about future lock-in, while another described building a similar analysis for their company and emphasized marketing to agents. Some discussed specific behaviors, such as Claude Code's use of awk/sed/Python for file editing, and the reliability of Claude's web search, with references to open-source tracking tools.

**Tags**: `#AI coding agents`, `#tool usage`, `#empirical analysis`, `#developer tools`

---

<a id="item-15"></a>
## [GPS Glitch Across US Causes Errors Up to 33 Feet](https://www.sciencealert.com/gps-glitched-across-the-us-by-as-much-as-33-feet-scientists-have-never-seen-this-before) ⭐️ 7.0/10

A GPS glitch across the US caused positioning errors of up to 33 feet (about 10 meters), disrupting delivery geofencing and raising concerns about broader impacts. Scientists have reportedly never seen this before, indicating an unusual event. This glitch affects critical GPS-dependent services like delivery routing and electronic monitoring, potentially causing significant economic losses and safety issues. It highlights the vulnerability of modern infrastructure to GPS errors, which are often taken for granted. The error magnitude of 33 feet is comparable to typical multipath errors in urban environments, but the widespread nature across the US is unusual. The glitch may be linked to solar activity, as the May 2024 solar storm was estimated to cost the US agricultural industry $500 million due to precision navigation disruptions.

hackernews · thread_id · Sep 3, 00:49 · [Discussion](https://news.ycombinator.com/item?id=49544618)

**Background**: GPS (Global Positioning System) relies on signals from satellites to determine location, but errors can arise from atmospheric conditions, multipath interference, and receiver clock inaccuracies. Geofencing uses GPS to create virtual boundaries, and when errors exceed the boundary size, services like delivery confirmations or electronic monitoring can fail. Solar storms can disrupt GPS signals by affecting the ionosphere, leading to increased errors.

<details><summary>References</summary>
<ul>
<li><a href="https://www.geoplugin.com/resources/geofencing-accuracy-best-practices-for-improvements/">Geofencing Accuracy | GeoPlugin</a></li>
<li><a href="https://webheadsunited.com/gps-vs-beacon-for-geofence-accuracy-a-breakdown/">GPS vs. Beacon for Geofence Accuracy: A Comprehensive ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Error_analysis_for_the_Global_Positioning_System">Error analysis for the Global Positioning System - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community comments highlight real-world impacts: an Amazon driver notes that GPS errors waste time and could be costly region-wide, while another commenter warns of false alerts for electronic monitoring devices leading to wrongful reincarceration. Some skeptics question the severity, noting 33 feet is within typical multipath error, and others doubt the $500 million agricultural cost estimate, calling it a rough guess.

**Tags**: `#GPS`, `#technology failure`, `#infrastructure`, `#navigation`, `#real-world impact`

---

<a id="item-16"></a>
## [MCP in Production: Real-World Use Cases and Debates](https://news.ycombinator.com/item?id=49548600) ⭐️ 7.0/10

A Hacker News discussion asked who uses MCP in production, attracting 91 points and 117 comments. Practitioners shared diverse use cases, from user-facing sports analytics to customer-facing voice agents, and debated MCP's advantages over traditional APIs and CLIs. This discussion provides valuable insights into the real-world adoption of MCP, a protocol introduced by Anthropic in November 2024 to standardize AI-tool integration. It highlights where MCP adds value—such as for non-technical users and cross-system correlation—and where it may be redundant for technical users already using CLIs, informing developers' decisions on whether to adopt MCP. Commenters noted that MCP is particularly useful when end users are non-technical and need OAuth-based authentication, as seen with MCP OAuth and CIMD. Some mentioned diminishing value as AI agents become better at using APIs/CLIs directly, but an in-house MCP for log/metrics search across five legacy systems proved valuable for correlating events across systems.

hackernews · sukit · Sep 3, 11:21

**Background**: MCP (Model Context Protocol) is an open standard introduced by Anthropic in November 2024 to standardize how AI systems like LLMs integrate with external tools and data sources. It provides a common interface for AI agents to retrieve and interact with data, often compared to a 'USB-C for AI.' The protocol has gained support from major companies like OpenAI, Google, Microsoft, and AWS, and was donated to the Linux Foundation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://dev.to/aristoaistack/mcp-explained-how-ai-agents-actually-work-2026-5p8">MCP Explained: How AI Agents Actually Work (2026)</a></li>
<li><a href="https://www.runlayer.com/blog/mcp-vs-cli-for-ai-agents-choosing-the-right-interface">MCP vs CLI Tools: Which is best for production applications?</a></li>

</ul>
</details>

**Discussion**: The community sentiment is mixed but constructive. Some users strongly advocate for MCP, citing its ease for non-technical users and auth handling, while others note that for technical users with existing CLIs, MCP offers little advantage. A key insight is that MCP shines when it aggregates multiple sources or systems, as one commenter described using an in-house MCP to correlate logs across five legacy systems.

**Tags**: `#MCP`, `#AI agents`, `#production`, `#API`, `#LLM`

---

<a id="item-17"></a>
## [Anthropic Updates Claude System Prompts with Song Lyric Restrictions](https://simonwillison.net/2026/Sep/2/claudes-new-system-prompt/) ⭐️ 7.0/10

Anthropic has reorganized and published updated system prompts for Claude models, including a new section in Fable 5.1 that prohibits reproducing song lyrics, poems, or book passages. The prompts are now available on an index page with per-model pages, and can be accessed as Markdown for easy diffing. This update reflects Anthropic's ongoing efforts to address copyright concerns in AI outputs, which is a critical issue for the industry. By publicly sharing these prompts, Anthropic provides valuable transparency that helps developers and researchers understand and improve AI safety measures. The new lyric restriction applies to works published after 1929, and Claude will decline requests even if the user claims ownership or pastes lines incrementally. The prompts are available for Claude.ai and mobile apps, but not for Claude Cowork or Claude Code, and the platform docs support adding '.md' to URLs for Markdown versions.

rss · Simon Willison · Sep 2, 14:16

**Background**: System prompts are the hidden instructions that guide AI model behavior. Anthropic has been publishing these prompts since 2024 to increase transparency, and the latest reorganization makes it easier to track changes over time. The new copyright-related restrictions are part of broader efforts to prevent AI from reproducing copyrighted material without permission.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2024/Aug/26/anthropic-system-prompts/">Anthropic Release Notes : System Prompts | Simon Willison’s Weblog</a></li>
<li><a href="https://github.com/asgeirtj/system_prompts_leaks">GitHub - asgeirtj/ system _ prompts _leaks: Extracted system prompts ...</a></li>
<li><a href="https://theaterfi.re/post/1360757">Anthropic now publishes their system prompts ... | TheaterFire</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights appreciation for Anthropic's transparency in publishing system prompts, with some noting the usefulness of the Markdown feature for diffing. There is also interest in the distinction between Claude Cowork and Claude Code, as the prompts are not provided for these tools.

**Tags**: `#AI`, `#Anthropic`, `#system prompts`, `#copyright`, `#safety`

---

<a id="item-18"></a>
## [Grounding LLMs with JEPA World Models Trained in Simulation](https://www.reddit.com/r/MachineLearning/comments/1w69gvd/grounding_llms_with_jepabased_world_models/) ⭐️ 7.0/10

A Reddit user proposes training JEPA-style world models in physics simulations (e.g., MuJoCo) to ground LLMs with physical intuition, addressing the 'Mary's Room' problem. The idea combines JEPA prediction with LLM conditioning, which the author claims has not been done cleanly. This research direction could address a fundamental limitation of LLMs—their lack of grounded understanding—potentially leading to models that reason with physical intuition. If successful, it could improve downstream learning efficiency and enable more robust AI in embodied or physics-related tasks. The proposal suggests freezing JEPA representations and attaching them to an LLM as a conditioning signal, with open questions about the interface (e.g., concatenation vs. cross-attention) and the sim-to-real gap. The author references V-JEPA and DreamerV3 as adjacent work but notes the specific combination is novel.

reddit · r/MachineLearning · /u/Full_Promotion4522 · Sep 3, 14:45

**Background**: JEPA (Joint Embedding Predictive Architecture) is a self-supervised learning approach that predicts representations of future states in an abstract embedding space, rather than predicting pixels or tokens. The 'Mary's Room' thought experiment, from philosophy of mind, illustrates the difference between propositional knowledge and experiential knowledge. Recent research, such as JEPA-x and PSG-JEPA, has explored grounding JEPA world models in physical states, but the integration with LLMs remains an open area.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2608.24044">[2608.24044] JEPA-x: Cross-Predictive Physics Grounding for ...</a></li>
<li><a href="https://arxiv.org/html/2608.06799v1">Is Forward Prediction Enough? Physical State Grounding for ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_argument">Knowledge argument - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#JEPA`, `#world models`, `#grounding`, `#AI research`

---

<a id="item-19"></a>
## [Pilot-Based Protocol Determines LLM Query Repetition for Reliability](https://www.reddit.com/r/MachineLearning/comments/1w6wtw7/how_many_repeated_llm_queries_are_enough_testing/) ⭐️ 7.0/10

A new preprint proposes a generalizability-theory-based method to estimate the number of repeated LLM queries needed for reliable results, validated on three external corpora with 37 of 39 prediction cells meeting the replication criterion. This work addresses a practical question for LLM practitioners: how many times to repeat a prompt before comparing results. It offers a principled alternative to fixed iteration thresholds, which the study found do not transfer across contexts. The method uses pilot-based variance estimates to calculate the repeat count for a chosen reliability target. The external corpora did not include brand recommendations, so independent replication on repeated brand-recommendation data remains outstanding; some preregistered tests, including parts of drift diagnostics, failed.

reddit · r/MachineLearning · /u/dizhat · Sep 4, 06:53

**Background**: Generalizability theory extends classical reliability by using analysis of variance to separate multiple sources of measurement error. Repeated LLM queries often yield inconsistent answers, raising concerns about reliability in applications like factual QA and classification. This preprint applies G-theory to determine how many repetitions are needed for stable outputs.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cogn-iq.org/learn/theory/generalizability-theory/">Generalizability Theory — Facets, Variance... — Cogn-IQ Encyclopedia</a></li>
<li><a href="https://arxiv.org/html/2607.22554">Same Question, Different Answers: Evaluating LLM Reliability ...</a></li>
<li><a href="https://arxiv.org/pdf/2412.07923v3">Asking Again and Again: Exploring LLM Robustness to Repeated ...</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#reliability`, `#methodology`, `#generalizability theory`, `#preprint`

---

<a id="item-20"></a>
## [llm-gemini 0.34 Adds Gemini 3.8 Flash Support and Async Bug Fix](https://simonwillison.net/2026/Sep/2/llm-gemini/) ⭐️ 6.0/10

llm-gemini 0.34 has been released, adding support for the new Gemini 3.8 Flash model with low, medium, and high thinking levels. It also fixes a bug where async responses failed to record the resolved model version. This update enables users of the llm tool to access Google's latest Gemini 3.8 Flash model, which offers improved performance in software engineering and agentic workflows. The bug fix ensures more reliable async operations, benefiting developers who rely on asynchronous LLM calls. Gemini 3.8 Flash is the successor to Gemini 3.7 Flash, offering customizable effort levels to balance quality, cost, and latency. The 3.8 Flash Cyber variant is available only to 'trusted defenders'. The release also includes a contribution from Charlie Tonneslan for the async fix.

rss · Simon Willison · Sep 2, 16:39

**Background**: llm is a command-line tool by Simon Willison that provides a unified interface to various LLMs. llm-gemini is a plugin that allows llm to access Google's Gemini models. Gemini Flash models are known for being fast, cheap, and competent at tasks like HTML and JavaScript generation.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/simonw/llm-gemini">GitHub - simonw/ llm - gemini : LLM plugin to access Google's Gemini...</a></li>
<li><a href="https://simonwillison.net/2026/Sep/2/llm-gemini/">Release: llm - gemini 0.34 | Simon Willison’s Weblog</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/generate-content/thinking">Gemini thinking - generateContent API | Google AI for Developers</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#Gemini`, `#release`, `#tooling`

---

<a id="item-21"></a>
## [AAAI-27 Desk Rejection for Minor Abstract Edits Sparks Concern](https://www.reddit.com/r/MachineLearning/comments/1w6kcp6/aaai27_desk_rejection_over_incredibly_minor/) ⭐️ 6.0/10

A researcher reported receiving a desk rejection from AAAI-27 due to minor changes made to the title or abstract between the abstract-registration and full-paper deadlines, despite the guidelines allowing such edits. The rejection notice stated the decision was final and appeals would not be considered. This incident highlights potential inconsistencies in how AAAI-27 enforces its modification rules, which could unfairly penalize researchers and create confusion in the academic community. It may prompt the conference to clarify its policies or reconsider its enforcement procedures to ensure fairness. The AAAI-27 guidelines state that title and abstract can be edited after registration but warn against substantive changes that describe qualitatively different research. The rejection notice explicitly said the decision is final and appeals will not be considered, leaving the researcher with no recourse.

reddit · r/MachineLearning · /u/Dansilly · Sep 3, 21:12

**Background**: AAAI (Association for the Advancement of Artificial Intelligence) is a major AI conference with a rigorous review process. Desk rejection occurs when a paper is rejected without full peer review, often due to policy violations. The conference has specific submission instructions and review processes that authors must follow to avoid immediate rejection.

<details><summary>References</summary>
<ul>
<li><a href="https://aaai.org/conference/aaai/aaai-27/submission-instructions/">AAAI-27 Submission Instructions - AAAI</a></li>
<li><a href="https://aaai.org/conference/aaai/aaai-27/review-process/">Review Process - AAAI</a></li>
<li><a href="https://www.besthub.dev/articles/aaai-27-submission-guide-new-rules-and-details-that-could-lead-to-immediate-desk-rejection-6f9ab39403f3">AAAI‑27 Submission Guide: New Rules and Details That C… | BestHub</a></li>

</ul>
</details>

**Tags**: `#AAAI`, `#conference`, `#desk rejection`, `#academic publishing`, `#policy`

---

<a id="item-22"></a>
## [Mol-JEPA: Multimodal JEPA-Based Molecular Foundation Model](https://www.reddit.com/r/MachineLearning/comments/1w6i8pr/moljepa_multimodal_molecular_foundation_model_r/) ⭐️ 6.0/10

A researcher shared their paper on Mol-JEPA, a multimodal molecular foundation model built on the JEPA (Joint-Embedding Predictive Architecture) framework, along with a summary website. The model aims to learn unified representations from multiple molecular modalities. This work contributes to the growing field of multimodal molecular foundation models, which could improve drug discovery and materials design by integrating diverse data sources. It also applies Yann LeCun's JEPA paradigm to the molecular domain, potentially offering a more efficient alternative to token-based models. The model is multimodal, meaning it processes multiple types of molecular data, such as structures, text, or knowledge graphs. The author notes that further work is needed to improve performance and welcomes feedback, indicating the model is still in an early research stage.

reddit · r/MachineLearning · /u/TerribleAntelope9348 · Sep 3, 19:56

**Background**: JEPA (Joint-Embedding Predictive Architecture) is a self-supervised learning framework proposed by Yann LeCun that predicts representations in an abstract embedding space rather than in input space, aiming to learn useful world models. Multimodal molecular foundation models, such as MolFM, aim to integrate information from molecular structures, biomedical literature, and knowledge bases to support biomedical research. This work applies JEPA to molecular data, potentially enabling more efficient learning from diverse molecular modalities.

<details><summary>References</summary>
<ul>
<li><a href="https://rohitbandaru.github.io/blog/JEPA-Deep-Dive/">Deep Dive into Yann LeCun’s JEPA | Rohit Bandaru</a></li>
<li><a href="https://arxiv.org/abs/2307.09484">[2307.09484] MolFM: A Multimodal Molecular Foundation Model</a></li>

</ul>
</details>

**Tags**: `#molecular modeling`, `#JEPA`, `#foundation model`, `#multimodal`, `#machine learning`

---

<a id="item-23"></a>
## [Massive TikTok Dataset Released on Hugging Face](https://www.reddit.com/r/MachineLearning/comments/1w5h9se/i_scraped_594_billion_tiktok_videos_and_323/) ⭐️ 6.0/10

A user scraped 5.94 billion TikTok videos and 3.23 billion profiles in three weeks and uploaded the full dataset to Hugging Face for free. The dataset is available at https://huggingface.co/datasets/kuben-developer/tiktok-videos-4b, with a tutorial and paid code provided. This dataset is one of the largest public social media datasets ever released, potentially enabling large-scale research in recommendation systems, content analysis, and social behavior. However, it raises significant ethical and legal concerns regarding TikTok's Terms of Service and user privacy, which could impact the research community and platform policies. The data was collected via reverse-engineering TikTok's mobile app, which exposes 24 endpoints accessible without an account, though this likely violates TikTok's ToS. The full code is not free; the author charges a small fee, and the dataset includes videos, profiles, comments, hashtags, and sounds.

reddit · r/MachineLearning · /u/DataShack · Sep 2, 17:38

**Background**: TikTok is a popular short-video platform with a private mobile API that has been reverse-engineered by developers to access public data. Hugging Face is a leading platform for hosting machine learning datasets, offering tools for easy loading and sharing. Scraping social media data often conflicts with platform terms of service, raising legal and ethical questions.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/SyntaxSparkk/TikTok">GitHub - SyntaxSparkk/TikTok: TikTok Reverse Engineering ...</a></li>
<li><a href="https://github.com/johnwhoyou/TikTok-Mobile-API-Reverse-Engineering">GitHub - johnwhoyou/TikTok-Mobile-API-Reverse-Engineering ...</a></li>
<li><a href="https://arxiv.org/html/2504.13279v2">Just Another Hour on TikTok: Reverse-engineering unique ...</a></li>
<li><a href="https://huggingface.co/datasets">Datasets – Hugging Face</a></li>
<li><a href="https://github.com/huggingface/datasets">GitHub - huggingface/datasets: The largest hub of ready-to ... Releases · huggingface/datasets - GitHub Top 20 hugging Face datasets : Unlocking the Power of Ready ... Hugging Face Dataset Hub - GeeksforGeeks Hugging Face Guide — Models, Datasets & Inference API (2026)</a></li>
<li><a href="https://ensembledata.com/blog/why-so-many-companies-use-tiktok-data-scrapers">Why so many companies use TikTok data scrapers</a></li>
<li><a href="https://www.tiktok.com/legal/page/us/terms-of-service/en">Terms of Service | TikTok</a></li>

</ul>
</details>

**Tags**: `#dataset`, `#TikTok`, `#scraping`, `#Hugging Face`, `#social media`

---

<a id="item-24"></a>
## [CABiNet vs YOLO26-sem on UAVid: Accuracy, Compute, and GPU Latency Benchmark](https://www.reddit.com/r/MachineLearning/comments/1w5cfv1/cabinet_icra_2021_vs_yolo26sem_on_uavid_accuracy/) ⭐️ 6.0/10

The author, original first author of CABiNet (ICRA 2021), rebuilt the repo and benchmarked CABiNet against YOLO26-sem variants on the UAVid dataset, reporting mIoU, params, FLOPs, and FP16 latency. Results show CABiNet-L achieves 67.14 mIoU at 4.44 ms, outperforming YOLO26x-sem (64.41 mIoU, 13.09 ms) with ~3x lower latency. This comparison provides a reproducible, controlled benchmark between a purpose-built 2021 efficient architecture and a 2026 general multi-task model, offering valuable insights for practitioners selecting models for real-time aerial semantic segmentation. It highlights that specialized architectures can still be competitive or superior in accuracy-efficiency trade-offs, despite the rise of large multi-task models. The benchmark controls data representation, class weighting (ENet inverse-log with cls_pw=0.5), EMA weights, and evaluation protocol (single-scale, no TTA), while model-specific training recipes differ (e.g., epochs, optimizer, loss, augmentation). CABiNet-S (65.25 mIoU) and YOLO26s (61.69 mIoU) are near iso-compute (~44 GFLOPs), with CABiNet-S +3.6 mIoU but slightly slower; YOLO26n/s sit on the Pareto frontier for lower latency.

reddit · r/MachineLearning · /u/Naive-Explanation940 · Sep 2, 14:46

**Background**: CABiNet is a dual-branch CNN for real-time semantic segmentation, combining a high-resolution spatial branch with a lightweight context branch over a MobileNetV3 backbone, published at ICRA 2021. UAVid is a high-resolution UAV video dataset for semantic segmentation of urban scenes, with 8 object categories and slanted views. YOLO26 is a 2026 general multi-task model with a semantic-segmentation variant (YOLO26-sem). The benchmark uses matched evaluation on UAVid test split at 1024x1024 resolution.

<details><summary>References</summary>
<ul>
<li><a href="https://uavid.nl/">UAVid Semantic Segmentation Dataset</a></li>
<li><a href="https://arxiv.org/abs/1810.10438">UAVid: A Semantic Segmentation Dataset for UAV Imagery UAVid: A Semantic Segmentation Dataset for UAV Imagery GitHub - dataset-ninja/uavid: UAVid Semantic Segmentation ... UAVid - Dataset Ninja UAVid Dataset - University of Twente Research Information UAVid++ - vivichiciudean.github.io</a></li>
<li><a href="https://arxiv.org/html/1606.02147">ENet : A Deep Neural Network Architecture for Real-Time Semantic...</a></li>

</ul>
</details>

**Tags**: `#semantic segmentation`, `#model comparison`, `#UAVid`, `#real-time inference`, `#efficient architectures`

---