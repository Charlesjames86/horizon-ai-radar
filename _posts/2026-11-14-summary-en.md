---
layout: default
title: "Horizon Summary: 2026-11-14 (EN)"
date: 2026-11-14
lang: en
---

> From 35 items, 20 important content pieces were selected

---

1. [ggml, the tensor library behind llama.cpp, reaches v1.0.0](#item-1) ⭐️ 8.0/10
2. [Granzyme K identified as tissue-specific driver of aging, decoupled from inflammation](#item-2) ⭐️ 8.0/10
3. [EFF Warns Tech Companies Are Redefining Privacy Again](#item-3) ⭐️ 7.0/10
4. [Nvidia allegedly engineered GPU scarcity by funding AI startups to buy its chips](#item-4) ⭐️ 7.0/10
5. [Drawing Terminal Borders Without Wasting a Character Cell](#item-5) ⭐️ 7.0/10
6. [Unsloth Releases Dynamic v3.1 Quantizations for Qwen3.8-27B](#item-6) ⭐️ 7.0/10
7. [Jonathan Blow questions AI's impact on software development](#item-7) ⭐️ 7.0/10
8. [GPU-Accelerated SDR Monitors All Airband Frequencies Live from Orcas Island](#item-8) ⭐️ 7.0/10
9. [Blogger runs 600 experiments on JEPA world model, sparking debate on methodology](#item-9) ⭐️ 7.0/10
10. [OpenAI disbands robotics team, betting LLMs will control robots](#item-10) ⭐️ 7.0/10
11. [Brain-IT AI reconstructs viewed images from fMRI brain scans](#item-11) ⭐️ 7.0/10
12. [Korea's top tax accountant exam scorer faces unproven AI glasses cheating suspicion](#item-12) ⭐️ 7.0/10
13. [Claude Code v2.1.323 Adds Experimental Code Mode and Plugin Engine Constraints](#item-13) ⭐️ 6.0/10
14. [Side-by-side comparison of all 13 Monkey Island versions](#item-14) ⭐️ 6.0/10
15. [Retrospective on 3Com's rise and fall sparks nostalgic discussion](#item-15) ⭐️ 6.0/10
16. [FM-1 Workbench: Open Firmware Music Hardware Sparks Community Enthusiasm](#item-16) ⭐️ 6.0/10
17. [Blog Post on Music Player Development Pitfalls Sparks Discussion](#item-17) ⭐️ 6.0/10
18. [Microsoft apologizes for 24-hour outage, denies AI cause](#item-18) ⭐️ 6.0/10
19. [Google used 29 AI agents to build a 50-task causal reasoning benchmark](#item-19) ⭐️ 6.0/10
20. [Users mourn removed ChatGPT model amid legal battle over harm](#item-20) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [ggml, the tensor library behind llama.cpp, reaches v1.0.0](https://github.com/ggml-org/ggml/releases/tag/v1.0.0) ⭐️ 8.0/10

The ggml tensor library, which powers llama.cpp and whisper.cpp, released version 1.0.0 on November 13, ending three and a half years of unversioned weekly syncs. The release prunes deprecated APIs, bumps the RPC protocol, and includes performance work across eight backends under a new semantic versioning contract. This milestone formalizes semantic versioning for ggml and llama.cpp, meaning major-version bumps will signal API and ABI incompatibilities, which helps downstream projects manage dependencies more reliably. It also underscores the maturation of the local AI inference ecosystem, where ggml-based tools enable running large models on commodity hardware. The release includes performance improvements across eight backends and a bumped RPC protocol, and it removes deprecated APIs. Community members report that MoE models slightly exceeding GPU memory can now cache less-frequently used experts in host memory rather than failing to load.

hackernews · cobychapple · Nov 14, 02:28 · [Discussion](https://news.ycombinator.com/item?id=50493062)

**Background**: ggml is a low-level C/C++ tensor library designed for machine learning on commodity hardware, with minimal dependencies. It serves as the foundation for llama.cpp, a popular open-source project for running large language models locally, and whisper.cpp for speech recognition. These tools enable efficient inference on CPUs and consumer GPUs, often using quantization to reduce model size.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/ggml-org/ggml">GitHub - ggml -org/ ggml : Tensor library for machine learning · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Llama.cpp">llama.cpp - Wikipedia</a></li>
<li><a href="https://www.navsplace.net/ggml-v1-0-0-tensor-library-release-20261114/">ggml Hits 1.0.0: The Tensor Library Behind llama.cpp Grows Up</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion is overwhelmingly positive, with users praising the continuous performance gains—one reported a 5-10% speed boost per monthly upgrade and a benchmark improvement from 4:22 to 3:59 on a 50K-token prompt. Commenters highlight practical benefits like MoE expert offloading and express appreciation for making local inference accessible on older or less powerful hardware, comparing ggml and llama.cpp to "the Linux of the AI world."

**Tags**: `#ggml`, `#llama.cpp`, `#local-inference`, `#machine-learning`, `#open-source`

---

<a id="item-2"></a>
## [Granzyme K identified as tissue-specific driver of aging, decoupled from inflammation](https://www.nature.com/articles/d41586-026-03638-3) ⭐️ 8.0/10

Researchers have identified the protein Granzyme K (GzmK) as a tissue-specific driver of organismal aging, according to a paper published in Cell Immunity. The study shows that GzmK deficiency markedly attenuates organ aging despite persistent immune aging phenotypes, effectively uncoupling immune and tissue aging. This finding challenges the prevailing view that aging is primarily driven by systemic inflammation (inflammaging) and suggests that tissue aging can be targeted independently of immune aging. It opens new avenues for developing anti-aging therapies that specifically target GzmK without broadly suppressing the immune system. The paper's abstract notes that GzmK deficiency attenuates organ aging while immune aging phenotypes persist, indicating that GzmK drives tissue aging but not immune aging or systemic inflammaging. Granzyme K is a serine protease traditionally known for its role in immune cell granules and pro-apoptotic functions.

hackernews · gumby · Nov 13, 19:25 · [Discussion](https://news.ycombinator.com/item?id=50488470)

**Background**: Granzyme K is a protein encoded by the GZMK gene on chromosome 5 in humans and is traditionally described as a granule-secreted, pro-apoptotic serine protease involved in immune responses. Aging is often accompanied by 'inflammaging,' a chronic low-grade systemic inflammatory state linked to immune dysfunction and tissue degeneration. The new study distinguishes between immune aging and tissue aging, showing that GzmK specifically drives the latter.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GZMK">GZMK - Wikipedia</a></li>
<li><a href="https://www.frontiersin.org/journals/immunology/articles/10.3389/fimmu.2021.677707/full">Intracellular and Extracellular Roles of Granzyme K</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted the paper's nuance, noting that GzmK deficiency uncouples immune and tissue aging, and linked to the original Cell Immunity paper. Some debated the definition of aging and the trade-offs involved, while others questioned the evolutionary purpose of such proteins.

**Tags**: `#aging`, `#biology`, `#research`, `#immunology`, `#longevity`

---

<a id="item-3"></a>
## [EFF Warns Tech Companies Are Redefining Privacy Again](https://www.eff.org/deeplinks/2026/11/tech-companies-are-trying-shift-entire-concept-privacy-again) ⭐️ 7.0/10

The Electronic Frontier Foundation (EFF) published a November 2026 analysis arguing that tech companies are once again attempting to shift the entire concept of privacy, likely to normalize surveillance-based business models. The post sparked a Hacker News discussion with 91 points and 16 comments covering ad-tech incentives, wearable recording devices, and the need for stronger privacy laws. This matters because how privacy is defined shapes what data collection is considered acceptable, affecting billions of users of ad-supported platforms and wearable devices. The debate also highlights the growing push for constitutional or legislative privacy protections amid a patchwork of state and federal tech laws taking effect in 2026. EFF's post does not introduce a new technical breakthrough but rather documents a recurring pattern of privacy erosion; the community discussion notes that ad companies like Facebook and Google, and increasingly AI model makers, lead the charge because their business models depend on data acquisition. Commenters also compare current recording products to the backlash against Google Glass a decade ago and question the plausibility of personal jammer hardware.

hackernews · gslin · Nov 14, 12:45 · [Discussion](https://news.ycombinator.com/item?id=50496602)

**Background**: The EFF is a nonprofit founded in 1990 that defends civil liberties in the digital world through litigation, policy analysis, and activism. Ad-tech companies rely on extensive data collection for targeted advertising, which often conflicts with privacy regulations that require opt-in consent or opt-out mechanisms. In 2026, a wave of state and federal tech laws addressing AI safety, data privacy, and children's online protections is taking effect, creating a complex compliance landscape.

<details><summary>References</summary>
<ul>
<li><a href="https://www.eff.org/about">About EFF | Electronic Frontier Foundation</a></li>
<li><a href="https://builtin.com/articles/tech-laws-2026">12 Tech Laws Taking Effect in 2026 You Need to Know | Built In</a></li>
<li><a href="https://www.venable.com/insights/publications/2025/04/key-privacy-issues-in-adtech">Key Privacy Issues in Adtech | Insights | Venable LLP</a></li>

</ul>
</details>

**Discussion**: Commenters generally agree that ad companies and AI model makers are driving privacy erosion, with some arguing that nothing will change until people hold representatives accountable and vote for privacy-focused lawmakers. Others question why current recording wearables should face less backlash than Google Glass did, and one user asks whether personal jammer hardware is plausible as a DIY countermeasure.

**Tags**: `#privacy`, `#surveillance`, `#ad-tech`, `#regulation`, `#EFF`

---

<a id="item-4"></a>
## [Nvidia allegedly engineered GPU scarcity by funding AI startups to buy its chips](https://www.techpowerup.com/354814/nvidia-allegedly-engineered-scarcity-by-funding-ai-startups-to-buy-its-gpus) ⭐️ 7.0/10

A TechPowerUp article, citing a Wall Street Journal report via Wccftech, alleges that Nvidia artificially inflated the ongoing GPU and memory shortage by investing in AI startups that then purchased Nvidia GPUs to build data centers. The report emerged following the departure of former Nvidia CEO Jensen Huang, with Colette Kress now serving as interim CEO. The allegation raises questions about whether the GPU shortage panic was partly financing theater, potentially affecting trust in Nvidia's business practices and the broader AI hardware market. It also highlights the growing scrutiny of circular financing arrangements among major AI players like Nvidia, Microsoft, and OpenAI. The story is a third-hand report (WSJ → Wccftech → TechPowerUp), which critics argue reduces its novelty and reliability. Nvidia has made over 100 AI startup investments in the last two years, including in OpenAI, xAI, and Mistral, and these funded companies allegedly receive preferential access to the newest A100/A800/H100 chips.

hackernews · speckx · Nov 14, 02:52 · [Discussion](https://news.ycombinator.com/item?id=50493251)

**Background**: Circular financing in the AI industry refers to a pattern where chipmakers like Nvidia invest in AI startups, which then use the funds to purchase hardware from the same chipmaker, creating a self-reinforcing cycle. Nvidia has been a prolific investor in AI startups, leveraging its financial strength to support companies that build data centers optimized for its GPUs. This strategy ensures demand for Nvidia's products while giving startups access to scarce chips and capital.

<details><summary>References</summary>
<ul>
<li><a href="https://www.techpowerup.com/354814/nvidia-allegedly-engineered-scarcity-by-funding-ai-startups-to-buy-its-gpus">NVIDIA Allegedly Engineered Scarcity By Funding AI Startups ...</a></li>
<li><a href="https://www.explainx.ai/blog/nvidia-engineered-gpu-scarcity-startup-funding-wsj-claimed-vs-verified-2026">WSJ: Nvidia Funded Startups to Buy GPUs — What's Verified ...</a></li>
<li><a href="https://techcrunch.com/2026/01/02/nvidias-ai-empire-a-look-at-its-top-startup-investments/">Nvidia’s AI empire: A look at its top startup investments</a></li>

</ul>
</details>

**Discussion**: Commenters debate the business logic, with some explaining that Nvidia's circular financing is a normal strategy to secure demand and prevent customers from switching to competitors like AMD or ASICs. Others criticize the derivative reporting chain and note that the circular financing story was already known a year ago, while some highlight the WSJ article's point that major cloud providers were moving away from Nvidia.

**Tags**: `#nvidia`, `#ai-hardware`, `#business-strategy`, `#circular-financing`, `#tech-industry`

---

<a id="item-5"></a>
## [Drawing Terminal Borders Without Wasting a Character Cell](https://www.joshka.net/cell-borders/) ⭐️ 7.0/10

A blog post by joshka explores techniques for rendering borders in terminal user interfaces without consuming a full character cell, using half-block characters and other tricks. The post sparked a Hacker News discussion with 336 points and 148 comments about terminal capabilities and TUI design. This matters because terminal screen real estate is precious, and saving cells on borders allows more content to be displayed, which is especially important for data-dense TUI applications. The discussion also highlights broader debates about TUI design philosophy and terminal emulator capabilities. The techniques include using half-block characters (like ▀ and ▄) to create borders that occupy only half a cell vertically, and potentially zero-width borders horizontally. However, the post notes that such borders may look visually crowded, and support depends on terminal font and rendering.

hackernews · vinhnx · Nov 13, 23:06 · [Discussion](https://news.ycombinator.com/item?id=50491423)

**Background**: Terminal user interfaces (TUIs) are text-based interfaces rendered in a terminal emulator, often built with libraries like Ratatui (a Rust crate). Traditionally, borders around UI elements consume a full character cell on each side, reducing the available space for content. This article explores ways to draw borders more efficiently by using special Unicode characters that only partially fill a cell.

<details><summary>References</summary>
<ul>
<li><a href="https://ratatui.rs/">Ratatui | Ratatui</a></li>
<li><a href="https://github.com/ratatui/ratatui">GitHub - ratatui / ratatui : A Rust crate for cooking up terminal user ...</a></li>

</ul>
</details>

**Discussion**: Commenters discussed alternatives like overstrike mode (DECSET 20) supported by mintty, which would allow drawing borders over existing text, and debated whether TUIs are reinventing GUIs. Some expressed concern about TUI frameworks being resource-heavy, redrawing at high refresh rates instead of only on changes, and questioned the need for fancy borders versus raw text interfaces.

**Tags**: `#terminals`, `#TUI`, `#ratatui`, `#rendering`, `#developer-tools`

---

<a id="item-6"></a>
## [Unsloth Releases Dynamic v3.1 Quantizations for Qwen3.8-27B](https://unsloth.ai/docs/models/qwen3.8) ⭐️ 7.0/10

Unsloth released new GGUF quantizations for Qwen3.8-27B using its Dynamic v3.1 (preview) algorithm on November 11, 2026, and also updated DeepSeek-V4.1-Flash-1017 and Qwen3.8-Flash-Next with UD3.1 quants. These quantizations improve accuracy by 5-10% at the same size on most benchmarks and reduce token usage by up to 50%, making local inference more efficient for users running models on consumer GPUs and Apple Silicon Macs. Unsloth claims 10-15% increased accuracy and 50% less token usage versus other quants of the same size, with 7% faster speed; the 1-bit quant of Qwen3.8-Flash-Next fits in 68GB and DeepSeek-V4.1-Flash-1017 in 128-145GB, enabling them to run on Macs with 96GB+ unified memory.

hackernews · Retro_Dev · Nov 14, 00:06 · [Discussion](https://news.ycombinator.com/item?id=50491980)

**Background**: Quantization reduces the precision of model weights to shrink file size and memory usage, enabling large language models to run on consumer hardware. GGUF is a binary format used by llama.cpp and Ollama that supports CPU, GPU, and Apple Silicon inference. Unsloth's Dynamic quantization method selectively quantizes different layers to preserve accuracy better than uniform quantization.

<details><summary>References</summary>
<ul>
<li><a href="https://unsloth.ai/docs/models/qwen3.8">Qwen3.8 - How to Run Locally | Unsloth Documentation</a></li>
<li><a href="https://unsloth.ai/docs/basics/dynamic-3.0-ggufs">Unsloth Dynamic 3.0 GGUFs | Unsloth Documentation</a></li>
<li><a href="https://www.besthub.dev/articles/unsloth-dynamic-v3-1-quantization-fits-552b-moe-on-mac-memory-requirements-by-bit-level-ae2e1e31d358">Unsloth Dynamic v3.1 Quantization Fits 552B MoE on Mac ...</a></li>

</ul>
</details>

**Discussion**: Community members welcomed the update, with one user reporting that the new quant was significantly less token-hungry (46.5k vs 61.7k tokens per task) but slightly worse in debugging tasks, while others asked about hardware optimization and benchmarks for local models.

**Tags**: `#LLM quantization`, `#Unsloth`, `#Qwen`, `#local inference`, `#GGUF`

---

<a id="item-7"></a>
## [Jonathan Blow questions AI's impact on software development](https://www.youtube.com/watch?v=IRK8h67ol7Q) ⭐️ 7.0/10

In a recent video, game developer Jonathan Blow argued that despite the hype around AI, software development hasn't fundamentally changed, prompting a Hacker News discussion with 531 comments. This debate highlights the gap between AI promises and the reality of building complex software, affecting how developers, tool makers, and companies invest in AI coding assistants. Blow's talk focuses on the lack of transformative change in software development since the early 2000s, and commenters debate whether LLMs can address the core challenges of problem modeling and architectural design.

hackernews · helloplanets · Nov 13, 15:08 · [Discussion](https://news.ycombinator.com/item?id=50484658)

**Background**: Jonathan Blow is a well-known independent game developer behind Braid and The Witness, and he is also the creator of the Jai programming language. Large Language Models (LLMs) like GitHub Copilot and ChatGPT have been increasingly used for coding tasks, but their ability to fundamentally alter software development remains debated.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jonathan_Blow">Jonathan Blow - Wikipedia</a></li>
<li><a href="https://www.node-magazine.com/thoughtleadership/automation-vs-innovation-the-truth-about-ai-powered-coding">NODE - Automation vs innovation: The truth about AI-powered coding</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree that coding is not the hardest part of software development; instead, problem definition and design are. Some offer counterexamples from indie game development, while others criticize Blow's views on developer salaries and privacy.

**Tags**: `#AI`, `#software-engineering`, `#LLMs`, `#game-development`, `#programming`

---

<a id="item-8"></a>
## [GPU-Accelerated SDR Monitors All Airband Frequencies Live from Orcas Island](https://orcasairband.com/) ⭐️ 7.0/10

A live airband monitoring service called Orcas Airband, built on an Ettus B210 SDR and dual RTX 4090 GPUs, uses a CUDA-based polyphase channelizer to demodulate all VHF airband frequencies in real time. The system unexpectedly captured live radio chatter during a ground stop at Vancouver International Airport, providing real-time insight into the disruption. This demonstrates how consumer-grade GPUs can enable wideband, real-time monitoring of entire radio bands, making advanced signal processing accessible to hobbyists and researchers. Such systems could improve situational awareness for aviation enthusiasts and provide alternative data sources during communication outages. The Ettus B210 provides up to 56 MHz of instantaneous bandwidth, covering the entire VHF airband (108-137 MHz) in one capture. The CUDA polyphase channelizer splits the wideband signal into individual channels, demodulates them, and detects transmissions, with raw transcripts showing communications from Victoria Ground and Vancouver Centre.

hackernews · mmaunder · Nov 13, 22:04 · [Discussion](https://news.ycombinator.com/item?id=50490593)

**Background**: The VHF airband (108-137 MHz) is used for aviation voice communications, with channels spaced at 25 kHz or 8.33 kHz. Software-defined radio (SDR) allows flexible processing of radio signals in software, and polyphase channelizers are efficient algorithms for separating a wideband signal into multiple narrowband channels. GPUs like the RTX 4090 excel at parallel processing, making them ideal for real-time channelization and demodulation of many channels simultaneously.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ettus.com/all-products/ub210-kit/">USRP B210 USB Software Defined Radio (SDR) - Ettus Research</a></li>
<li><a href="https://en.wikipedia.org/wiki/Airband">Airband - Wikipedia</a></li>
<li><a href="https://github.com/khan-hannan/CUDA-PolyphaseChannelizer">GitHub - khan-hannan/CUDA-PolyphaseChannelizer: a simple ...</a></li>

</ul>
</details>

**Discussion**: The author (mmaunder) explained the system's architecture and shared raw transcripts related to the ground stop, while another user (molsongolden) pointed to a specific interaction confirming the ground stop. Users also discussed usability improvements, such as a 'jump to time' button and squelch filtering, and compared the project to other SDR-based monitoring tools.

**Tags**: `#software-defined-radio`, `#GPU-accelerated`, `#signal-processing`, `#aviation`, `#real-time-monitoring`

---

<a id="item-9"></a>
## [Blogger runs 600 experiments on JEPA world model, sparking debate on methodology](https://haddyalchaer.com/jepa) ⭐️ 7.0/10

A practitioner published a blog post detailing 600 experiments conducted over several months on LeWorldModel (LeWM), a JEPA-based world model whose main benchmark is the Push-T robotic manipulation task. The post describes building harder test scenarios and an interactive demo, and it prompted extensive discussion on Hacker News about experimental methodology and the novelty of the findings. This hands-on exploration provides rare empirical insight into the stability and behavior of JEPA world models, a research direction championed by Yann LeCun as an alternative to generative and reconstruction-based approaches. The community debate also highlights the need to distinguish personal learning journeys from novel research contributions in the fast-growing field of AI world models. The experiments focus on the Push-T simulation, where a robot pushes a T-shaped block to a target pose, and the author built harder tests by taking start states from one demonstration and goals from another. Commenters noted that the goals still come from expert demonstrations rather than arbitrary configurations, and that concepts like hierarchical planning and action chunking are already well established.

hackernews · halcdev · Nov 13, 17:55 · [Discussion](https://news.ycombinator.com/item?id=50487185)

**Background**: JEPA (Joint Embedding Predictive Architecture) is a self-supervised learning approach that predicts abstract latent representations of inputs rather than reconstructing raw pixels or tokens, and it is central to Yann LeCun's vision of world models. LeWM is a recent JEPA world model that trains stably end-to-end and uses Push-T as its main benchmark. Model Predictive Control (MPC) is a classical control technique that optimizes actions over a planning horizon using a system model, and several commenters drew parallels between MPC and JEPA-style planning.

<details><summary>References</summary>
<ul>
<li><a href="https://www.turingpost.com/p/jepa">JEPA: Joint Embedding Predictive Architecture Explained</a></li>
<li><a href="https://arxiv.org/abs/2603.19312">[2603.19312] LeWorldModel: Stable End-to-End Joint-Embedding ... Flow-JEPA: Robust Latent Dynamics for JEPA World Models via ... After 600 experiments, here's what I discovered about JEPA ... GitHub - AbdelStark/awesome-jepa: Curated resources for JEPA ... JEPA-Style World Models Introducing the V-JEPA 2 world model and new benchmarks for ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Joint_Embedding_Predictive_Architecture">Joint Embedding Predictive Architecture</a></li>

</ul>
</details>

**Discussion**: Commenters questioned why the harder tests still rely on expert demonstrations rather than arbitrary start-goal pairs, and one noted strong similarities between JEPA and Model Predictive Control, where a black-box neural simulator replaces the system model. Others argued that hierarchical planning and sub-goals are well-understood concepts, suggesting the post is more a personal learning transcript than a source of novel results, while some appreciated the hands-on effort.

**Tags**: `#JEPA`, `#world-models`, `#reinforcement-learning`, `#model-predictive-control`, `#AI-research`

---

<a id="item-10"></a>
## [OpenAI disbands robotics team, betting LLMs will control robots](https://www.reddit.com/r/artificial/comments/1xvivdy/openai_is_so_convinced_that_llms_will_become/) ⭐️ 7.0/10

OpenAI has disbanded its stand-alone robotics team and reassigned its researchers to other parts of the company, according to a Fortune report from November 13, 2026. The company framed the move as an effort to accelerate robotics progress by relying on its general-purpose models, which are reportedly starting to run robots directly. This signals a strategic shift away from building dedicated robotics hardware and toward using general-purpose LLMs as the 'brains' for embodied AI, which could reshape how robotics labs and partners approach robot control. It also reflects OpenAI's confidence that scaling language models can generalize to physical tasks, potentially lowering the barrier for robot development across the industry. OpenAI insists the move is meant to accelerate rather than abandon robotics, with researchers reassigned internally rather than laid off. The approach hinges on the idea that general models can already run robots, though details on which models or hardware partners are involved remain unclear.

reddit · r/artificial · /u/Eliv_nurotic · Nov 13, 20:32

**Background**: Embodied AI refers to artificial intelligence systems embedded in physical bodies that perceive the environment through sensors and act via actuators. Historically, robotics teams built specialized control stacks, but recent advances in large language models have led researchers to explore using LLMs for high-level planning and robot control. OpenAI previously had a robotics division that developed projects like Dactyl and Rubik's Cube-solving robot hands before shifting focus to language models.

<details><summary>References</summary>
<ul>
<li><a href="https://fortune.com/2026/11/13/openai-disbands-robotics-team-as-its-general-models-start-running-robots/">Exclusive: OpenAI disbands stand-alone robotics team as ...</a></li>
<li><a href="https://tech.yahoo.com/ai/articles/exclusive-openai-disbands-stand-alone-170530559.html">Exclusive: OpenAI disbands its stand-alone robotics team as ...</a></li>
<li><a href="https://casrai.org/news/openai-disbands-robotics-team-2026">OpenAI Disbands Its Robotics Team: What It Means — CASRAI</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#robotics`, `#LLMs`, `#AI strategy`, `#embodied AI`

---

<a id="item-11"></a>
## [Brain-IT AI reconstructs viewed images from fMRI brain scans](https://www.reddit.com/r/artificial/comments/1xvissf/this_ai_finds_patterns_in_visual_brain_activity/) ⭐️ 7.0/10

A new AI system called Brain-IT reconstructs images that people viewed from fMRI brain scans with high accuracy by predicting both the layout and high-level content of the images and passing those predictions to an image generator. The research was presented at the ICLR 2026 conference and uploaded as a preprint to arXiv. This work advances non-invasive brain-computer interfaces by combining fMRI decoding with generative AI, potentially enabling new ways to study visual perception and communicate with patients who cannot speak or move. It also highlights the growing convergence of neuroscience and generative modeling. Brain-IT uses data from the visual cortex and a two-stage approach: first predicting the broad layout and high-level content of the viewed image, then feeding these predictions to an AI image generator. The study is a preprint and has not yet undergone peer review, so its accuracy claims should be interpreted with caution.

reddit · r/artificial · /u/Fcking_Chuck · Nov 13, 20:29

**Background**: Functional magnetic resonance imaging (fMRI) measures brain activity by detecting changes in blood flow, and researchers have long used it to study how the visual cortex responds to images. Recent advances in generative AI, especially diffusion models, have made it possible to reconstruct images from brain activity, but earlier methods often lacked faithfulness to the actual seen images. Brain-IT aims to improve reconstruction fidelity by explicitly predicting image layout and content before generation.

<details><summary>References</summary>
<ul>
<li><a href="https://www.semanticscholar.org/paper/Brain-IT:-Image-Reconstruction-from-fMRI-via-Beliy-Zalcher/aec94fe9b0fe716000db66d588c72588cb80e498">[PDF] Brain - IT : Image Reconstruction from fMRI... | Semantic Scholar</a></li>
<li><a href="https://arxiv.org/html/2411.07121v2">Decoding Visual Experience and Mapping Semantics</a></li>
<li><a href="https://en.wikipedia.org/wiki/International_Conference_on_Learning_Representations">International Conference on Learning Representations - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#brain-computer interface`, `#fMRI decoding`, `#generative AI`, `#neuroscience`, `#computer vision`

---

<a id="item-12"></a>
## [Korea's top tax accountant exam scorer faces unproven AI glasses cheating suspicion](https://www.reddit.com/r/artificial/comments/1xv6aut/koreas_tax_accountant_exam_top_scorer_is_facing/) ⭐️ 7.0/10

The top scorer on South Korea's tax accountant exam, who achieved 397.5 out of 400 in the first round, is facing online accusations of using AI smart glasses to cheat, despite no evidence and no reports from either of the two proctors. The exam agency is reviewing the matter, and the tax accountants' association has requested an investigation while warning that unproven accusations could damage his reputation. This case highlights the growing challenge of detecting AI-assisted cheating in high-stakes exams, where even perfect scores can be met with suspicion and where current proctoring methods may be unable to distinguish AI glasses from normal eyewear. It raises broader questions about exam integrity, the burden of proof, and whether exams should be redesigned to test skills that AI cannot easily replicate. The scorer answered 159 of 160 questions correctly, including a perfect score in introductory tax law where the average across 16,856 candidates was 30.18/100 and 74.21% failed; candidates had roughly one minute per question. Neither proctor reported any issue, and the exam agency has not found evidence, leaving the accusation unsubstantiated.

reddit · r/artificial · /u/meshive · Nov 13, 12:13

**Background**: AI smart glasses, such as Meta Ray-Ban Display, can capture text via built-in cameras, relay questions to large language models, and provide answers through in-lens displays or audio. South Korea has already seen cases of exam cheating using AI glasses, including its first criminal case, prompting schools and universities to tighten rules. Traditional proctoring relies on human observers or software that flags unusual eye movements, audio, or extra devices, but these methods struggle to detect subtle AI eyewear.

<details><summary>References</summary>
<ul>
<li><a href="https://www.the-independent.com/asia/east-asia/south-korea-ai-glasses-cheating-exams-criminal-case-b3014506.html">South Korea files first criminal case over AI smart glasses exam ...</a></li>
<li><a href="https://www.talview.com/blog/meta-ai-glasses-exam-cheating">Meta AI Glasses & the Future of AI Cheating in Exams</a></li>
<li><a href="https://www.ray-ban.com/usa/l/discover-meta-ray-ban-display">Discover Meta Ray - Ban Display Glasses with Neural... | Ray - Ban ® US</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration that there is no clean way to clear the accused: if innocent, 'we found nothing' does not fully exonerate him, and if someone cheats this way in the future, proctors likely cannot tell AI glasses from normal ones. The discussion debated whether exams should ban glasses, use detectors, or stop testing material that a camera plus a model can answer in a minute.

**Tags**: `#AI ethics`, `#exam integrity`, `#AI detection`, `#smart glasses`, `#society`

---

<a id="item-13"></a>
## [Claude Code v2.1.323 Adds Experimental Code Mode and Plugin Engine Constraints](https://github.com/anthropics/claude-code/releases/tag/v2.1.323) ⭐️ 6.0/10

Claude Code v2.1.323 introduces Code Mode, an experimental opt-in feature where Claude writes JavaScript to invoke its tools, and adds an engines["claude-code"] field to plugin.json to enforce version compatibility. The release also enhances `claude plugin validate` with TypeScript type checking for hooks and adds various UX improvements and bug fixes. Code Mode represents a novel approach to tool invocation that could enable more complex, programmatic interactions with Claude's capabilities, potentially improving efficiency for advanced users. The plugin engine constraints and validation improvements enhance the reliability and safety of the plugin ecosystem, which is critical as Claude Code becomes a more extensible platform. Code Mode is opt-in and can be disabled at the organization level via documentation; the engines field ensures plugins outside their stated version range are not installed or loaded, and install/update picks the newest compatible version. The `claude plugin validate` command now type-checks TypeScript hooks modules, reporting warnings that can fail with `--strict`.

github · claude-code-publisher[bot] · Nov 12, 22:12

**Background**: Claude Code is Anthropic's terminal-based AI coding agent that can understand codebases and handle complex Git workflows using natural language. Plugins extend Claude Code's functionality, and the engines field is similar to npm's engines field in package.json, which specifies version requirements for the runtime environment. Code Mode is an experimental feature that lets Claude generate JavaScript code to call tools, rather than invoking them directly.

<details><summary>References</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI coding agent and assistant</a></li>
<li><a href="https://docs.npmjs.com/cli/v6/configuring-npm/package-json/">Specifics of npm's package. json handling | npm Docs</a></li>
<li><a href="https://aistack.sh/changelog/claude-code-feature-2026-11-type-checking-added-to-plugin-typescript">Type checking added to plugin TypeScript hooks module validation</a></li>

</ul>
</details>

**Tags**: `#claude-code`, `#ai-tools`, `#release-notes`, `#developer-tools`, `#plugin-system`

---

<a id="item-14"></a>
## [Side-by-side comparison of all 13 Monkey Island versions](https://monkeyisland.pages.dev/) ⭐️ 6.0/10

A new website presents a side-by-side visual comparison of all 13 versions of the classic adventure game The Secret of Monkey Island, highlighting graphical differences across platforms such as CGA, EGA, VGA, and Amiga. The project offers a valuable resource for game preservation and retro-computing enthusiasts, illustrating how early graphics hardware limitations shaped game art and sparking nostalgia for the formative era of PC gaming. The comparison covers versions spanning CGA (4-color 320x200), EGA (16-color), VGA (256-color), and Amiga (custom chipset) graphics, revealing how artists adapted to each platform's constraints; the site has garnered 283 upvotes and 83 comments on a tech forum.

hackernews · maximilianburke · Nov 14, 04:23 · [Discussion](https://news.ycombinator.com/item?id=50493904)

**Background**: The Secret of Monkey Island is a 1990 point-and-click adventure game by Ron Gilbert and LucasArts, known for its humor and art. Early PC graphics were dominated by IBM's CGA and EGA standards, which offered limited color palettes, while the Commodore Amiga provided superior graphics and sound. Comparing these versions shows how technical constraints influenced game development and player experience.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Color_Graphics_Adapter">Color Graphics Adapter - Wikipedia</a></li>
<li><a href="https://ohiostate.pressbooks.pub/graphicshistory/chapter/16-4-amiga/">16.4 Amiga – Computer Graphics and Computer Animation...</a></li>

</ul>
</details>

**Discussion**: Commenters shared nostalgic memories of growing up with CGA graphics, with some recalling the 'cold' feel of cyan/magenta/black/white and appreciating the artists' skill in working with minimal colors. Others reminisced about Amiga copy protection and the magic of 1990s adventure games, expressing a desire to relive those experiences.

**Tags**: `#retro-gaming`, `#graphics`, `#game-preservation`, `#CGA`, `#Amiga`

---

<a id="item-15"></a>
## [Retrospective on 3Com's rise and fall sparks nostalgic discussion](https://dfarq.homeip.net/what-happened-to-3com/) ⭐️ 6.0/10

A blog post titled 'What happened to 3Com?' recounts the history of the networking pioneer, and it sparked a Hacker News thread with 176 points and 93 comments sharing personal anecdotes and technical trivia. The discussion highlights 3Com's lasting impact on networking, from Ethernet to early PC cards, and shows how technical communities value historical knowledge and personal connections to technology. Commenters shared specific details such as the 3c509 card's pencil-mark Easter egg (a test mode triggered by a graphite mark) and how failure-rate analysis led 3Com to offer a lifetime warranty on its 3c50x Ethernet cards.

hackernews · gvieri · Nov 13, 23:48 · [Discussion](https://news.ycombinator.com/item?id=50491830)

**Background**: 3Com Corporation was founded in 1979 by Robert Metcalfe, co-inventor of Ethernet, and others. It became a leading manufacturer of networking hardware, including early Ethernet cards and switches, before being acquired by Hewlett-Packard in 2010 and absorbed into HP.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/3Com">3Com - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/List_of_3Com_products">List of 3Com products - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The Hacker News comments are overwhelmingly positive and nostalgic, with former employees and users sharing stories about 3Com's engineering culture, product reliability, and key figures like Ron Crane and David Boggs. Many express admiration for the company's technical legacy and the serendipitous nature of early networking innovation.

**Tags**: `#3Com`, `#networking`, `#tech history`, `#hardware`, `#retrospective`

---

<a id="item-16"></a>
## [FM-1 Workbench: Open Firmware Music Hardware Sparks Community Enthusiasm](https://open.m-vave.com/fm1-workbench) ⭐️ 6.0/10

The FM-1 Workbench is a small, affordable music hardware device that has attracted attention on Hacker News for its open firmware ecosystem, with users installing new community-developed firmwares every few days, including generative music applications like NACHTFART and DUB-1. This device exemplifies a growing trend of open firmware in music hardware, where manufacturers embrace community creativity, potentially influencing larger companies like Akai and Behringer to adopt similar open approaches. Many generative firmwares for the FM-1 can be run in a browser emulator for previewing, and the device supports MIDI connectivity, but some community firmwares are not tested on physical hardware and require backing up projects before updating.

hackernews · simonebrunozzi · Nov 13, 19:14 · [Discussion](https://news.ycombinator.com/item?id=50488325)

**Background**: The FM-1 is a sub-$100 pocket synthesizer that has seen a surge in custom firmware development, with nearly a dozen replacement operating systems created by the community. Open firmware allows users to modify and extend the device's functionality, a practice that has roots in earlier music tech like JJOS for the MPC1000 and open-source Eurorack modules.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.dubspot.com/custom-firmware-vibe-coding-music-hardware-2026">The Custom Firmware Boom: Where Vibe-Coded Gear Goes Next</a></li>
<li><a href="https://sitem.co/public/summary/5830/the-rise-of-open-firmware-in-electronic-music-hardware-from-m-vave-fm-1-to-industry-giants">The Rise of Open Firmware in Electronic Music Hardware: From ...</a></li>
<li><a href="https://www.synthtopia.com/content/2026/10/28/will-open-firmware-become-the-next-big-trend-in-electronic-music-gear/">Will Open Firmware Become the Next Big Trend in Electronic ...</a></li>

</ul>
</details>

**Discussion**: Commenters are enthusiastic about the device's generative firmwares and open ecosystem, with some praising it as a bright spot in post-LLM music tech. Others ask about using it to learn music theory and seek recommendations for firmware and learning resources.

**Tags**: `#music-tech`, `#hardware`, `#open-firmware`, `#generative-music`, `#hacker-news`

---

<a id="item-17"></a>
## [Blog Post on Music Player Development Pitfalls Sparks Discussion](https://alichraghi.github.io/blog/how-not-to-build-a-music-player/) ⭐️ 6.0/10

A blog post titled 'How Not to Build a Music Player' recounts the author's pitfalls in building a music player, sparking a Hacker News discussion with 143 points and 62 comments. The discussion highlights that despite the abundance of music player options, especially on Linux, there are still unmet needs and gaps in the market, prompting many developers to build their own solutions. Commenters shared personal experiences, such as writing their own players to avoid testing many apps, and mentioned specific tools like LIBLRC for lyrics search and Amarok still being maintained.

hackernews · vinhnx · Nov 13, 23:04 · [Discussion](https://news.ycombinator.com/item?id=50491400)

**Background**: Music players are a common personal project for developers, and Linux offers a wide range of options from simple CLI players to feature-rich GUI applications. Building a music player involves challenges like handling audio formats, metadata, and user interface design, which the blog post likely explores.

<details><summary>References</summary>
<ul>
<li><a href="https://linuxconfig.org/best-music-player-for-linux">Best Music Player for Linux Explained - LinuxConfig.org Top 11 Best Music Players for Linux [2024] - It's FOSS Best Music Player for Linux: A Comprehensive Guide Best Music Players for Ubuntu: 14 Top Picks in 2026- Ubuntu Free Best Open Source Linux Music Players 2026 - SourceForge Best Linux Media Players: A Comprehensive Guide - linuxvox.com</a></li>
<li><a href="https://www.jploft.com/blog/music-app-development-challenges">Key Music App Development Challenges & Their Solutions</a></li>

</ul>
</details>

**Discussion**: Commenters noted the paradox of many music players yet unfilled niches, with some sharing their own player projects and others mentioning alternatives like Amarok and Clementine. The overall sentiment was that building a custom player can be quicker than finding one that meets specific needs.

**Tags**: `#music-player`, `#software-development`, `#hacker-news`, `#personal-project`, `#linux`

---

<a id="item-18"></a>
## [Microsoft apologizes for 24-hour outage, denies AI cause](https://www.reddit.com/r/artificial/comments/1xvinch/we_are_deeply_sorry_microsoft_apologizes_for/) ⭐️ 6.0/10

Microsoft issued a public apology after a global outage lasting nearly 24 hours disrupted Outlook, Teams, Microsoft 365, and Copilot for users in more than 70 countries, while explicitly stating that AI was not the cause of the incident. The outage highlights the world's heavy reliance on a handful of cloud providers for critical productivity and communication tools, and Microsoft's denial that AI was involved reflects growing scrutiny of AI's role in critical infrastructure reliability. Microsoft ruled out a cyberattack and attributed the outage to a technical issue, but did not immediately provide a detailed root cause; the incident affected services for over 22 hours before restoration was complete.

reddit · r/artificial · /u/esporx · Nov 13, 20:23

**Background**: Microsoft 365 is a suite of cloud-based productivity services including Outlook email, Teams collaboration, and Office apps, used by millions of organizations worldwide. Major outages at large cloud providers can disrupt businesses globally, prompting questions about redundancy and incident response. The mention of AI likely stems from speculation that AI-driven systems or automated tools may have contributed to the failure.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/2026_Microsoft_outage">2026 Microsoft outage - Wikipedia</a></li>
<li><a href="https://www.bbc.com/news/live/cq5y10ge3dp3t">Microsoft says it is 'deeply sorry' for global outage after almost 24 ....</a></li>
<li><a href="https://www.bbc.co.uk/news/articles/cwvg238zrnm5o">Why is Microsoft 's outage lasting so long and will emails be lost?</a></li>

</ul>
</details>

**Tags**: `#Microsoft`, `#outage`, `#cloud services`, `#AI reliability`, `#incident response`

---

<a id="item-19"></a>
## [Google used 29 AI agents to build a 50-task causal reasoning benchmark](https://www.reddit.com/r/artificial/comments/1xvwdwz/google_used_29_ai_agents_to_build_a_50task/) ⭐️ 6.0/10

Google Research used 29 AI agents over 11.5 hours to generate a 50-task causal reasoning benchmark from 13 public tables, where models must decide if a causal effect is identifiable and estimate it against a known answer. Separate reviewer and auditor agents were deployed to catch wording clues and template shortcuts that could let models answer without doing the intended work. This demonstrates a multi-agent pipeline for benchmark construction with built-in adversarial review, which could reduce contamination and shortcut exploitation in AI evaluations. If scalable, it offers a way to generate fresh, audited benchmarks faster than human-only authoring, affecting how researchers measure causal reasoning and agent reliability. The benchmark is modest at 50 tasks derived from 13 public tables, and the Reddit post is a brief summary, so details on task diversity and difficulty are limited. The reviewer/auditor agents flagged problems that were then turned into tests for future drafts, but the approach still relies on AI agents to catch AI-generated shortcuts.

reddit · r/artificial · /u/andrewaltair · Nov 14, 07:30

**Background**: Causal reasoning benchmarks test whether a model can determine if a causal effect is identifiable from observational data and, when it is, estimate the effect correctly. Benchmark contamination occurs when test cases leak into training data, inflating scores, and template shortcuts let models exploit superficial patterns instead of reasoning. Automated auditing using LLM agents is an emerging approach to detect such flaws at scale.

<details><summary>References</summary>
<ul>
<li><a href="https://www.icesi.edu.co/CRAN/web/packages/dosearch/vignettes/dosearch.html">Identifying Causal Effects using dosearch</a></li>
<li><a href="https://jcode.sh/bench">Contamination-resistant AI agent benchmarks | jcode</a></li>
<li><a href="https://arxiv.org/abs/2604.24955">[2604.24955] Who Guards the Benchmarks? Automated Auditing of ... Automated Benchmark Auditing for AI Agents and ... - OpenReview LLM Agent Benchmarks (November 2026): 133 Agentic Evals ... [2506.00641] AgentAuditor: Human-Level Safety and Security ... AgentAuditor-ASSEBench/README.md at main · Astarojth ... AgentSuite: Toward More Reliable Agent Evaluation with a...</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#benchmark`, `#causal reasoning`, `#Google Research`, `#evaluation`

---

<a id="item-20"></a>
## [Users mourn removed ChatGPT model amid legal battle over harm](https://www.reddit.com/r/artificial/comments/1xw2k13/requiem_for_a_robot_the_ai_users_mourning/) ⭐️ 6.0/10

A report by The Observer highlights that the removal of a specific ChatGPT model has led to an outpouring of grief among users, even as a legal battle continues over the psychological damage the chatbot may have caused. This case illustrates the growing emotional attachment users form with AI chatbots and raises critical questions about corporate responsibility and user welfare when models are deprecated or found to be harmful. The report juxtaposes user grief with ongoing litigation, though specific details about the model version, the nature of the psychological harm, and the legal claims are not provided in the summary.

reddit · r/artificial · /u/TheObserverUK · Nov 14, 13:35

**Background**: ChatGPT models are frequently updated, and older versions are sometimes retired, which can disrupt users who have developed routines or emotional bonds with a particular model. Meanwhile, a new wave of lawsuits alleges that AI chatbots can cause psychological injury, testing legal frameworks like Section 230 and product liability.

<details><summary>References</summary>
<ul>
<li><a href="https://mylawcle.com/products/ai-chatbot-litigation-the-next-frontier-in-product-liability-and-litigation/">AI Chatbot Litigation: The Next Frontier in Product... | myLawCLE</a></li>
<li><a href="https://en.wikipedia.org/wiki/Human–AI_interaction">Human–AI interaction - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#chatbots`, `#human-AI interaction`, `#AI regulation`, `#social impact`

---