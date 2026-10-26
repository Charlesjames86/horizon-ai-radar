---
layout: default
title: "Horizon Summary: 2026-10-26 (EN)"
date: 2026-10-26
lang: en
---

> From 21 items, 13 important content pieces were selected

---

1. [Anthropic Files S-1 for IPO, Sparking Debate on Valuation and Commitments](#item-1) ⭐️ 9.0/10
2. [Context Engineering: Organization and Strategic Forgetting Matter as Much as Length](#item-2) ⭐️ 8.0/10
3. [Dan Luu Urges Engineers to Build More Ambitious Software](#item-3) ⭐️ 7.0/10
4. [PBT doesn't speed up grokking but escapes hyperparameter dead zones](#item-4) ⭐️ 7.0/10
5. [Nanbeige releases Nanbeige4.3-33B, an Apache 2.0 teacher model for smaller agents](#item-5) ⭐️ 7.0/10
6. [memt-1.0 uses gated DeltaNet-2 and mixture-of-storage for agent memory](#item-6) ⭐️ 7.0/10
7. [TitleArt Revives 1997 Microsoft WordArt in the Browser](#item-7) ⭐️ 6.0/10
8. [Stanford Archive Reveals NeXT Office Photos](#item-8) ⭐️ 6.0/10
9. [Hacker News Discusses Dolly Parton's Imagination Library](#item-9) ⭐️ 6.0/10
10. [Blog Post Argues Websites Should Be Printable, Sparking HN Debate](#item-10) ⭐️ 6.0/10
11. [Show HN: Keybytes modular keyboard lets keys form any shape](#item-11) ⭐️ 6.0/10
12. [arXiv Paper Argues Attention Is Not Necessary, Sparks Debate](#item-12) ⭐️ 6.0/10
13. [Steal My Bitcoin CTF PoC Released with Community Context](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Anthropic Files S-1 for IPO, Sparking Debate on Valuation and Commitments](https://www.sec.gov/Archives/edgar/data/2130357/000162828026067168/anthropicpbc-sx1.htm) ⭐️ 9.0/10

Anthropic PBC has filed its S-1 registration statement with the SEC, moving a step closer to becoming the first major AI model developer to go public. The filing reveals massive forward cash commitments, including $114 billion to Google, $110 billion to AWS, $161 billion to Broadcom, and $120 billion to SpaceX, alongside an $80.7 billion loss in the first half of 2026. This IPO would be a landmark event for the AI industry, subjecting Anthropic's finances and business model to public market scrutiny for the first time. The outcome could set a precedent for how AI labs are valued and whether their massive infrastructure bets are justified by demand. The S-1 discloses enormous forward commitments to major cloud and chip suppliers, and the company reported an $80.7 billion loss in the first half of 2026. The filing also includes a warning that Anthropic's technology carries existential risks, and it follows a $65 billion Series H round at a $965 billion post-money valuation.

hackernews · SiNTEx · Oct 26, 13:04 · [Discussion](https://news.ycombinator.com/item?id=50242939)

**Background**: An S-1 is a registration statement filed with the SEC by companies intending to go public, providing detailed financial and business information. A forward commitment is a binding agreement to carry out a transaction at a future date, often used to secure supply or prices. Anthropic is an AI safety and research company behind the Claude models, and its IPO would test public market appetite for a pure-play AI lab.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/10/26/anthropic-ipo-live-updates-ai-s-1-filing.html">Anthropic IPO live updates: AI lab's S - 1 filing</a></li>
<li><a href="https://www.bloomberg.com/news/articles/2026-10-26/anthropic-ipo-s-1-filing-offers-first-look-at-claude-maker-s-finances">Anthropic IPO : S - 1 Filing Offers First Look at Claude... - Bloomberg</a></li>
<li><a href="https://www.investopedia.com/terms/f/forward-commitment.asp">Forward Commitment: What it Means, How it Works - Investopedia</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters drew parallels to the WeWork S-1, questioning whether demand can justify the massive forward commitments amid commoditization risks. Others debated the sustainability of Anthropic's revenue growth and raised concerns about the broader implications of AI maximalism.

**Tags**: `#Anthropic`, `#IPO`, `#AI industry`, `#business strategy`, `#Hacker News`

---

<a id="item-2"></a>
## [Context Engineering: Organization and Strategic Forgetting Matter as Much as Length](https://www.dbreunig.com/2026/10/24/the-state-of-context-engineering.html) ⭐️ 8.0/10

An article surveying the state of context engineering for LLMs argues that how information is organized and strategically forgotten matters as much as raw context length, sparking a rich Hacker News discussion with 227 points and 57 comments. This moves the conversation beyond the simplistic 'context too long' framing, highlighting that dependency length, hierarchical context trees, and strategic forgetting are key design principles for building more capable and efficient LLM agents. Commenters introduced concepts like dependency length (relevant relationships should be close together in text), VictorTaelin's UniiChat idea of summarizing messages into a binary tree with a zoom tool, and the notion that perfect memory may impede creativity, making strategic forgetting a design principle.

hackernews · pchristensen · Oct 25, 20:32 · [Discussion](https://news.ycombinator.com/item?id=50235780)

**Background**: Context engineering is the practice of designing the entire information ecosystem fed to an LLM, including what to include, how to structure it, and what to omit. As LLM agents tackle long-horizon tasks, managing finite context windows through memory addition and deletion strategies has become critical for maintaining performance. Strategic forgetting frameworks like SF-AMS aim to balance memory retention and removal based on utility signals.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Meirtz/Awesome-Context-Engineering">GitHub - Meirtz/Awesome- Context - Engineering : Comprehensive...</a></li>
<li><a href="https://arxiv.org/abs/2607.22562">[2607.22562] SF-AMS: Strategic Forgetting for Structured ...</a></li>
<li><a href="https://aclanthology.org/2026.acl-long.27/">How Memory Management Impacts LLM Agents: An Empirical Study ...</a></li>

</ul>
</details>

**Discussion**: Commenters largely agreed that organization matters as much as length, with one noting that LLM attention works best when related concepts are close together (dependency length). Others praised hierarchical context tree ideas like UniiChat and pi-optchat, and discussed how strategic forgetting mirrors human imperfect memory and may aid creativity. One commenter disagreed with the article's claim that performance degrades around 200k-300k tokens, finding newer models handle large contexts well and that models quickly fill context by scanning codebases.

**Tags**: `#llm`, `#context-engineering`, `#ai-agents`, `#memory-management`, `#prompt-engineering`

---

<a id="item-3"></a>
## [Dan Luu Urges Engineers to Build More Ambitious Software](https://danluu.com/ambitious/) ⭐️ 7.0/10

Dan Luu published an essay arguing that engineers should aim for more ambitious software, citing AI as a tool that enables building more complex systems. The post sparked a Hacker News discussion with 849 points and 728 comments. The discussion highlights a growing debate about AI's role in software quality and the importance of finding unique competitive advantages in a world where AI can generate code easily. It also draws attention to the poor state of software outside the tech bubble, affecting everyday products. Commenters noted that AI can speed up development but may introduce overfit, unmaintainable code, and that ambitious projects should leverage unique specifications where individuals have a competitive edge. Examples include building an SDK for Kobo e-readers and attempting a Python interpreter in Rust.

hackernews · ltratt · Oct 24, 21:47 · [Discussion](https://news.ycombinator.com/item?id=50225695)

**Background**: Dan Luu is a well-known software engineer and blogger who writes about performance, systems, and industry myths. His essays often challenge conventional wisdom and spark discussions in the tech community. The Hacker News platform is a popular forum for sharing and discussing technology news and projects.

<details><summary>References</summary>
<ul>
<li><a href="https://danluu.com/">danluu.com</a></li>
<li><a href="https://danluu.com/perf-opt/">There's no reason for software to be slow anymore - danluu.com</a></li>
<li><a href="https://www.hungyichen.com/en/insights/vibe-coding-software-engineering-crisis">The Dark Side of Vibe Coding : The AI Code Quality ... | Hung-Yi Chen</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed views: some shared success stories of building ambitious projects with AI, while others warned about AI-generated code quality and technical debt. A key theme was finding unique competitive advantages rather than just making faster versions of existing tools, and several noted the poor software quality outside tech.

**Tags**: `#software-engineering`, `#ambition`, `#AI-generated-code`, `#industry-commentary`, `#hacker-news-discussion`

---

<a id="item-4"></a>
## [PBT doesn't speed up grokking but escapes hyperparameter dead zones](https://www.reddit.com/r/MachineLearning/comments/1xfqhfc/pbt_doesnt_make_grokking_faster_but_it_can_escape/) ⭐️ 7.0/10

An empirical study compared Population Based Training (PBT) against grid search on the modular addition mod 97 grokking task, finding that PBT was slower than the best fixed grid cell (2667 ± 2244 steps vs 317 ± 29 steps to reach 95% validation accuracy). However, from a hyperparameter dead zone where no fixed setting groks, fast PBT achieved 3/3 success at about 6850 steps, while fixed settings and slow PBT achieved 0/3. This finding clarifies that PBT's value lies in rescuing training from poorly chosen hyperparameter ranges rather than accelerating grokking, which could guide practitioners to use PBT as a safety net when hyperparameters are uncertain. It also highlights that the learned schedule, not weight copying, drives the escape, offering a non-obvious insight for hyperparameter optimization research. Ablations show that a random donor still escapes but later, and without selection members grok then lose it; replaying the winning learning rate/weight decay schedule on fresh initializations yields 55/60 reaching 95% accuracy, while constant knobs at the schedule's geometric mean yield 0/60. Caveats include a single task, model, and split, with 3 to 10 seeds per test and p-values mostly above 0.05, and the replayed schedules are post-hoc winners.

reddit · r/MachineLearning · /u/Virtual-Message-9739 · Oct 26, 07:48

**Background**: Grokking refers to a phenomenon where neural networks first overfit training data and then much later suddenly generalize, often observed on algorithmic tasks like modular addition. Population Based Training (PBT) is a hyperparameter optimization method that trains a population of models in parallel, periodically copying weights from better-performing members and perturbing their hyperparameters. This study tests whether PBT can accelerate grokking or help when initial hyperparameters are in a region where no fixed configuration groks.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2301.05217">P rogress measures for grokking via</a></li>
<li><a href="https://docs.ray.io/en/latest/tune/examples/pbt_guide.html">A Guide to Population Based Training with Tune — Ray 2.59.0</a></li>
<li><a href="https://www.lesswrong.com/posts/XpCnhaAQrssq8tJBG/an-interactive-introduction-to-grokking-and-mechanistic">An interactive introduction to grokking and mechanistic... — LessWrong</a></li>

</ul>
</details>

**Tags**: `#grokking`, `#population-based-training`, `#hyperparameter-optimization`, `#deep-learning`, `#empirical-study`

---

<a id="item-5"></a>
## [Nanbeige releases Nanbeige4.3-33B, an Apache 2.0 teacher model for smaller agents](https://www.reddit.com/r/MachineLearning/comments/1xf6x35/nanbeige_releases_nanbeige4333b_an_apache_20/) ⭐️ 7.0/10

Nanbeige released Nanbeige4.3-33B, an open-weight model under the Apache 2.0 license with a 512K context window, positioned as the teacher for its planned smaller agents including an upcoming 3B model. The team reports 80.9 on Terminal-Bench 2.1 versus 73.0 for Qwen3.8-27B, but trails on SWE-Bench Pro with 60.3 versus 61.7. This adds a permissively licensed, long-context 33B teacher model to the open-weights ecosystem, giving teams a distillation source for building smaller, cheaper agentic models. Its mixed benchmark results also highlight that no single model dominates all agentic tasks, which matters for teams choosing a base model for tool-use deployments. The reported scores come from the releasing team's own evaluations rather than independent replication, and the agent results rely on preserve_thinking=true to retain earlier reasoning across turns. The model card recommends that setting for multi-turn tool use but not general chat, and the authors suggest comparing task success against total generated tokens rather than treating headline scores as a deployment ranking.

reddit · r/MachineLearning · /u/jatingargiitk · Oct 25, 16:32

**Background**: Teacher models are larger, stronger models used to train or distill smaller student models, so a 33B teacher can transfer agentic skills to a much smaller 3B agent. Terminal-Bench measures an agent's ability to complete tasks in a terminal environment, while SWE-Bench Pro evaluates resolving real repository issues end-to-end, and both are commonly cited for coding and tool-use agents. The preserve_thinking setting keeps a model's prior reasoning in context during multi-turn agent loops, avoiding redundant re-reasoning and saving time and KV-cache memory.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tbench.ai/">TERMINAL - BENCH</a></li>
<li><a href="https://www.swebench.com/">SWE - bench Leaderboards</a></li>
<li><a href="https://www.linkedin.com/pulse/qwen3827b-setup-guide-vllm-ollama-api-integration-parvez-mohammed-f2apf">Qwen3.8–27B Setup Guide: vLLM, Ollama, and API Integration...</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#open-weights`, `#agentic-ai`, `#benchmarks`, `#model-release`

---

<a id="item-6"></a>
## [memt-1.0 uses gated DeltaNet-2 and mixture-of-storage for agent memory](https://www.reddit.com/r/MachineLearning/comments/1xeu0ht/memt10_architecture_breakdown_gated_deltanet2/) ⭐️ 7.0/10

A Reddit post breaks down memt-1.0's memory-native architecture, which uses gated DeltaNet-2 and a mixture-of-storage layer to internalize agent memory instead of relying on append-only prompt stacking or external RAG. At a 128k-token history length, memt-1.0-nano reportedly delivers a 1.86x end-to-end inference speedup and a 66x reduction in persistent storage compared to a full-context KV cache setup. This matters because long-horizon agents typically suffer from KV cache memory bottlenecks as context grows, and internalizing state into architecture-level update layers could offer a more scalable alternative to external memory pipelines. If the claims hold, it could influence how developers design memory for agents that run over many turns. The architecture uses a stable token-level memory update mechanism within each turn and a two-stage training pipeline (continued pre-training plus post-training across 34B tokens) to preserve general reasoning while outperforming existing parametric memory baselines. The post is a Reddit discussion rather than a peer-reviewed paper, so the efficiency claims have not been independently verified.

reddit · r/MachineLearning · /u/Mrs-Grumpy23 · Oct 25, 05:31

**Background**: KV cache stores key-value pairs for every token in the context, so memory grows linearly with context length and becomes a major bottleneck for long-context LLM inference. Gated DeltaNet-2 is a second-generation linear memory architecture that extends Gated DeltaNet and Kimi Delta Attention by decoupling erase and write gates for finer control over the recurrent state. Mixture-of-storage is a layer that scales memory capacity by combining multiple storage mechanisms, and parametric memory refers to baking information into model weights or states rather than retrieving it as text.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2605.22791">Gated DeltaNet - 2 : Decoupling Erase and Write in Linear Attention</a></li>
<li><a href="https://www.emergentmind.com/topics/gated-deltanet-2-architecture">Gated DeltaNet - 2 : Advanced Memory Architecture</a></li>
<li><a href="https://arxiv.org/pdf/2603.20397">KV Cache Optimization Strategies for Scalable and Efficient ...</a></li>

</ul>
</details>

**Tags**: `#agent-memory`, `#architecture`, `#efficiency`, `#kv-cache`, `#machine-learning`

---

<a id="item-7"></a>
## [TitleArt Revives 1997 Microsoft WordArt in the Browser](https://titleart.dvy.io/) ⭐️ 6.0/10

A developer recreated the classic 1997 Microsoft WordArt as a web app called TitleArt, using screenshots to faithfully reproduce the original styles. The project unexpectedly offers proper vector hard shadows, which some users find genuinely useful. While primarily a nostalgia project, TitleArt demonstrates that retro tools can have modern utility, as its vector shadow feature addresses a long-standing limitation in professional design software like Adobe Illustrator. The creator tweaked built-in styles by eye based on various screenshots to achieve authenticity. The vector hard shadow capability is notable because Adobe Illustrator has struggled to provide this feature easily for decades.

hackernews · davidbarker · Oct 26, 03:23 · [Discussion](https://news.ycombinator.com/item?id=50238708)

**Background**: Microsoft WordArt was a popular feature in Office 97 that allowed users to create stylized text with 3D effects, shadows, and textures, widely used in school projects and flyers. Scott Forstall, who later led iOS development at Apple, contributed to WordArt as an intern at Microsoft. Modern design tools often lack simple vector hard shadow options, making this recreation unexpectedly relevant.

<details><summary>References</summary>
<ul>
<li><a href="https://wordart97.net/">WordArt 97 - Create WordArt Online</a></li>
<li><a href="https://www.popsci.com/diy/how-to-get-the-retro-wordart-back-in-microsoft-word/">How to get the retro WordArt back in Microsoft Word The History of Microsoft WordArt: From Windows 95 to Today Travel back in time to 1997 with this WordArt generator How to Get Old-School WordArt Back in Modern Microsoft Word TitleArt Revives 1997 Microsoft WordArt in Pure Web Code</a></li>

</ul>
</details>

**Discussion**: Commenters shared nostalgic memories of using WordArt and similar tools like BannerMania in school computer labs. One user highlighted the vector hard shadow feature as genuinely useful, while another noted the irony of WordArt being an early form of ubiquitous decorative graphics, comparable to today's AI-generated images.

**Tags**: `#nostalgia`, `#web-app`, `#vector-graphics`, `#wordart`, `#show-hn`

---

<a id="item-8"></a>
## [Stanford Archive Reveals NeXT Office Photos](https://exhibits.stanford.edu/menuez/browse/next-computer-inc?per_page=96&sort=pub_year_isi+asc%2C+title_sort+asc&view=masonry) ⭐️ 6.0/10

Stanford's Menuez archive has made available a collection of behind-the-scenes photographs from NeXT Computer's office, capturing the company's early culture and design work. The archive was shared on Hacker News, where it sparked a reflective discussion with over 100 comments. These photos offer a rare visual record of the company Steve Jobs founded after leaving Apple, whose NeXTSTEP operating system became the foundation for macOS and iOS. The discussion also highlights NeXT's outsized influence on the early web and the broader tech industry. The archive contains high-resolution images that commenters noted remain sharp when zoomed in, and the discussion references a project called NextSpace that aims to bring NeXTSTEP's interface to modern hardware. NeXT sold only about 50,000 NeXTcubes by 1991, yet one was used by Tim Berners-Lee to create the first web browser and server.

hackernews · Austin_Conlon · Oct 26, 03:31 · [Discussion](https://news.ycombinator.com/item?id=50238763)

**Background**: NeXT was founded by Steve Jobs in 1985 after his departure from Apple, and it produced high-end workstations like the NeXT Computer, introduced in 1988 at $6,500. Its NeXTSTEP operating system, based on the Mach kernel and BSD Unix, was technically influential despite low sales, and after Apple acquired NeXT in 1996, it became the basis for Mac OS X. Tim Berners-Lee developed the first web browser and server on a NeXT workstation, linking the company directly to the birth of the World Wide Web.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/NeXT_Computer">NeXT Computer - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/NeXTSTEP_(operating_system)">NeXTSTEP (operating system)</a></li>
<li><a href="https://en.wikipedia.org/wiki/NeXT">NeXT - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed a mix of nostalgia and melancholy, with one 27-year-old lamenting missing the era of in-person collaboration on truly new technology. Others praised NeXTSTEP's distinctive interface and recommended the book 'Steve Jobs in Exile,' while several reflected on NeXT's role in the early web and the outsized impact of Steve Jobs.

**Tags**: `#NeXT`, `#Steve Jobs`, `#tech history`, `#Hacker News`, `#retro computing`

---

<a id="item-9"></a>
## [Hacker News Discusses Dolly Parton's Imagination Library](https://imaginationlibrary.com/) ⭐️ 6.0/10

A Hacker News post about Dolly Parton's Imagination Library, a free book-by-mail program for children, sparked a discussion with 605 points and 101 comments. The thread featured personal stories from parents and insights into the program's locally funded distribution model. The discussion highlights the impact of a major early literacy initiative that has distributed millions of books worldwide, and it reveals how its decentralized funding model relies on local charities and partners. This matters for understanding community-driven nonprofit models and the role of public figures in promoting education. The program mails free, high-quality books to children from birth to age five, regardless of family income, with wholesale pricing negotiated centrally but per-book funding provided entirely by local affiliates. This means availability varies by community, as children in areas without local partners may not receive books.

hackernews · jumploops · Oct 25, 18:23 · [Discussion](https://news.ycombinator.com/item?id=50234474)

**Background**: Dolly Parton's Imagination Library was launched in 1995 by the country music star for children in her home county in East Tennessee, inspired by her father's inability to read and write. The program has since expanded to the USA, UK, Ireland, Canada, and Australia, and has distributed over 100 million books. It operates through a network of local affiliates who fund and promote the program, while the central organization selects books and negotiates wholesale prices.

<details><summary>References</summary>
<ul>
<li><a href="https://imaginationlibrary.com/">Dolly Parton ' s Imagination Library | USA, UK, IE, CA, AU</a></li>
<li><a href="https://imaginationlibrary.com/about-us/">About Dolly Parton ' s Imagination Library</a></li>
<li><a href="https://bookriot.com/dollys-imagination-library-state-funding/">The Battle Over Funding Imagination Library Grows: Book ...</a></li>

</ul>
</details>

**Discussion**: Commenters shared heartwarming personal stories, such as a parent whose child eagerly awaits books in the mail and another whose son received his final book with a letter from Dolly ending 'I will always love you.' Some discussed the locally funded model, noting that it allows the program to operate with low overhead but creates gaps where local charities are unable to participate. Overall sentiment was highly positive, with praise for the program's impact on children's literacy.

**Tags**: `#nonprofit`, `#literacy`, `#education`, `#community`, `#hacker-news`

---

<a id="item-10"></a>
## [Blog Post Argues Websites Should Be Printable, Sparking HN Debate](https://brennenputh.me/blog/printable-websites/) ⭐️ 6.0/10

A blog post by Brennen Puth argues that websites should be designed to print well, and the piece sparked a lively Hacker News discussion with 106 comments covering print styles, font sizing, and the purpose of the web. The debate highlights a growing tension between screen-first web design and the enduring need for printable content, affecting accessibility, archiving, and users who rely on paper or e-ink displays. Commenters noted that the article's own print CSS produced four pages with mostly blank space and a broken code sample, while others debated whether changing default font sizes for print is appropriate and pointed to tools like PrintFriendly and The Printliminator.

hackernews · bagatelle · Oct 26, 10:32 · [Discussion](https://news.ycombinator.com/item?id=50241664)

**Background**: CSS provides a print media type via the @media print at-rule, allowing developers to apply styles that only take effect when a page is printed or saved as PDF. Common techniques include hiding navigation and sidebars with display: none, removing background colors, and using @page rules to control margins and page breaks. These practices are part of broader web accessibility and print design guidelines.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Media_queries/Printing">Printing - CSS | MDN</a></li>
<li><a href="https://www.sitepoint.com/css-printer-friendly-pages/">How to Create Printer-friendly Pages with CSS - SitePoint</a></li>
<li><a href="https://www.w3.org/WAI/tips/designing/">Designing for Web Accessibility – Tips for Getting Started Accessibility in Print Guide — Alta Planning + Design Accessibility for visual designers | Digital.gov Designing for Accessibility: Best Practices for ADA-Compliant ... Resources for Designers | Web Accessibility Initiative (WAI ... How To Design For Accessibility</a></li>

</ul>
</details>

**Discussion**: Commenters were divided: some agreed that good HTML structure and hidden navigation are worthwhile, but others argued that the web's original purpose is navigation, not printing, and that print-specific typography changes are misguided. Several pointed out the irony of the article's own print layout failing, while others shared practical tools for making unprintable sites printable.

**Tags**: `#web-design`, `#css`, `#print-styles`, `#accessibility`, `#hacker-news`

---

<a id="item-11"></a>
## [Show HN: Keybytes modular keyboard lets keys form any shape](https://github.com/notaroomba/keybytes) ⭐️ 6.0/10

A developer presented Keybytes, a modular keyboard project on GitHub where individual keys can be arranged into arbitrary shapes, currently demonstrated as a two-key proof-of-concept. The creator is still working on the firmware and plans to add more keys. This project challenges the fixed-layout paradigm of traditional keyboards, potentially enabling highly customized ergonomic or unconventional shapes for users with specific needs. If successful, it could inspire new DIY hardware designs and influence the modular peripherals market. The current proof-of-concept only shows two keys, and the firmware is incomplete. Key challenges include ensuring reliable communication and snappy feel with a full set of keys, maintaining structural integrity, and portability at scale.

hackernews · NotARoomba · Oct 25, 03:47 · [Discussion](https://news.ycombinator.com/item?id=50228115)

**Background**: Modular keyboards allow users to rearrange or swap components like key switches or numpads, but most designs keep a standard grid layout. Keybytes aims to go further by letting each key be placed independently, enabling shapes like triangles or circles. This is part of a broader DIY keyboard movement where enthusiasts build custom layouts using open-source hardware and firmware.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Keyboard_layout">Keyboard layout - Wikipedia</a></li>
<li><a href="https://www.geeky-gadgets.com/diy-modular-split-keyboard/">DIY Modular Keyboard Design Features Repairable Parts ...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed interest but raised concerns about scalability: with only two keys, it's hard to judge communication reliability, structural integrity, and portability of a full layout. Some questioned whether the added complexity per key offers advantages beyond firmware customization, and one noted that ergonomic keyboards are usually not perfectly columnar.

**Tags**: `#keyboard`, `#hardware`, `#modular-design`, `#DIY`, `#HCI`

---

<a id="item-12"></a>
## [arXiv Paper Argues Attention Is Not Necessary, Sparks Debate](https://arxiv.org/abs/2512.19428) ⭐️ 6.0/10

A new arXiv paper titled 'Attention Is Not What You Need' proposes an alternative to the attention mechanism in neural networks, claiming that attention may be unnecessary for certain tasks. The paper has sparked a discussion on Hacker News, where commenters raised concerns about a potential off-by-one bug in the model's token pairing operation. If valid, the work could challenge the dominance of the transformer architecture, which relies on attention, and open the door to more efficient models. However, the community notes that many attention alternatives only work at small scale, so the impact on large language models remains uncertain. The paper describes a pairing operation (zt, zt+Δ) with a positive offset Δ, which critics argue uses the next token to predict the next token, potentially causing data leakage. The author's code may also contain the same bug, though this is unconfirmed.

hackernews · westurner · Oct 25, 23:52 · [Discussion](https://news.ycombinator.com/item?id=50237224)

**Background**: The attention mechanism is a key component of transformer models, allowing them to weigh the importance of different tokens in a sequence. Transformers have become the dominant architecture in natural language processing, powering models like GPT and BERT. Scaling laws describe how model performance improves predictably with increases in model size, data, and compute, which has driven the trend toward larger models.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Transformer_(deep_learning)">Transformer (deep learning) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Neural_scaling_law">Neural scaling law - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism, with one pointing out a potential off-by-one bug in the pairing operation that could invalidate results. Others noted that many attention alternatives work only for small sequence sizes, and some criticized the derivative 'X is all you need' title.

**Tags**: `#machine-learning`, `#transformers`, `#attention-mechanism`, `#arxiv`, `#nlp`

---

<a id="item-13"></a>
## [Steal My Bitcoin CTF PoC Released with Community Context](https://github.com/KillaBoi/StealMyBitcoin-PoC) ⭐️ 6.0/10

A proof-of-concept repository for the 'Steal My Bitcoin' CTF challenge has been released on GitHub, providing a single-file Python exploit that demonstrates a live PHP callback against the challenge. The release is accompanied by community discussion clarifying that the challenge used PHP's built-in development server behind an nginx proxy, rather than a standard fpm or mod_php setup. This PoC makes the exploit reproducible and highlights a common pitfall in CTF design: challenges that claim to replicate real-world setups but actually rely on unusual configurations like PHP's dev server, which can mislead participants about realistic security practices. The discussion also underscores the importance of transparency in challenge infrastructure, especially when real cryptocurrency is involved. The PoC is a single standard-library Python file that performs one live PHP callback against the challenge from start to finish. Community members noted that the challenge was updated to actually run PHP within 2-3 hours, and that the wallet key was not on the server, contrary to some initial suspicions.

hackernews · davikr · Oct 26, 00:15 · [Discussion](https://news.ycombinator.com/item?id=50237379)

**Background**: CTF (Capture The Flag) competitions are security challenges where participants hack systems to retrieve hidden flags. The 'Steal My Bitcoin' challenge involved a PHP-based web application and a Bitcoin wallet, drawing significant attention (585 points, 458 comments on Hacker News). PHP's built-in development server is intended for testing, not production, and lacks security features of standard setups like php-fpm or mod_php, making it a notable choice for a challenge that claimed to mimic real-world conditions.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/KillaBoi/StealMyBitcoin-PoC">KillaBoi/StealMyBitcoin-PoC: A public release of the Steal My Bitcoin ...</a></li>
<li><a href="https://news.ycombinator.com/item?id=50237379">Steal My Bitcoin CTF PoC | Hacker News</a></li>
<li><a href="https://capturetheflag.withgoogle.com/">Google CTF</a></li>

</ul>
</details>

**Discussion**: Commenters criticized the challenge's setup as misleading, with one noting that it used PHP's dev server and proxied requests from nginx, which is far from typical PHP usage. Others provided updates that the wallet key was not on the server and that the challenge was quickly updated to run PHP, while some pointed out that the PoC was already linked in the original thread.

**Tags**: `#CTF`, `#security`, `#PHP`, `#proof-of-concept`, `#hackernews`

---