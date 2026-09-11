---
layout: default
title: "Horizon Summary: 2026-09-11 (EN)"
date: 2026-09-11
lang: en
---

> From 34 items, 23 important content pieces were selected

---

1. [Calif Research Unveils WeWorm, First Zero-Click WeChat Worm Built with AI](#item-1) ⭐️ 9.0/10
2. [Shopify migrates mobile app from React Native back to native Swift and Kotlin](#item-2) ⭐️ 8.0/10
3. [OpenAI Launches Agents API with Self-Hosted Sandbox Option](#item-3) ⭐️ 8.0/10
4. [Researchers question whether OpenAI can be trusted with unpublished math](#item-4) ⭐️ 8.0/10
5. [Forgejo 16.0.4 Fixes Critical RCE in Template Expansion](#item-5) ⭐️ 8.0/10
6. [Microsoft Elevates Rust to Tier-1 Internal Language](#item-6) ⭐️ 8.0/10
7. [Anthropic report accuses Moonshot and DeepSeek of secretly proxying to Claude](#item-7) ⭐️ 8.0/10
8. [trynix.dev runs any Nix package from 13 years in the browser](#item-8) ⭐️ 8.0/10
9. [ACL Announces Sustainable Reviewing Policy Capping Submissions](#item-9) ⭐️ 8.0/10
10. [Fly connectome fails to learn Pong, audit reveals bugs and circuit limits](#item-10) ⭐️ 8.0/10
11. [Anthropic Restricts Claude to Users 18 and Older](#item-11) ⭐️ 7.0/10
12. [WebGL 'Deathray' Lets Untrusted Sites Freeze Macs](#item-12) ⭐️ 7.0/10
13. [NASA's Decorrelation Stretch Reveals Ancient Rock Art](#item-13) ⭐️ 7.0/10
14. [Cognition launches SWE-2 coding model, claims parity with Fable 5.1 and GPT-Astra](#item-14) ⭐️ 7.0/10
15. [PlanetScale Launches Neki, a Sharded Postgres Offering](#item-15) ⭐️ 7.0/10
16. [Open-Source 'Proof of Capture' Uses Steganography to Verify Image Authenticity](#item-16) ⭐️ 7.0/10
17. [Datasette 1.0a39 and 0.65.4 security patches after AI-assisted audit](#item-17) ⭐️ 7.0/10
18. [348M model trained from scratch hits 99.4% on GPT-3 arithmetic benchmarks](#item-18) ⭐️ 7.0/10
19. [IAEA Explainer on Cherenkov Radiation Sparks Expert Discussion](#item-19) ⭐️ 6.0/10
20. [Nine coding agent harnesses benchmarked on a laptop](#item-20) ⭐️ 6.0/10
21. [Free Online Music Theory Textbook Sparks Hacker News Debate](#item-21) ⭐️ 6.0/10
22. [NTSB Update on B-767 Miami Runway Excursion Cites Pilot Errors](#item-22) ⭐️ 6.0/10
23. [Sante's 83.83 on DiagnosisArena-MCQ Only Measures Multiple-Choice Diagnosis Selection](#item-23) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Calif Research Unveils WeWorm, First Zero-Click WeChat Worm Built with AI](https://simonwillison.net/2026/Sep/10/calif-research/) ⭐️ 9.0/10

Calif Research released a demo of WeWorm, described as the first zero-click worm that spreads through WeChat calls on both iOS and Android, compromising accounts without the victim answering or interacting with their phone. The team says it found the bug and wrote the first remote code execution (RCE) exploit in about two days with AI assistance, then built the full worm in roughly one more week. This is a major escalation in mobile security: a self-spreading, zero-click exploit against a widely used messaging app like WeChat could enable account hijacking at worm scale, and the researchers' claim that AI compressed months of work into about a week signals a significant shift in offensive security capabilities. It also raises urgent questions about how AI-assisted exploit development could lower the barrier for attackers targeting billions of users. The vulnerability is described as a memory corruption issue in WeChat's VoIP stack, and Calif tested the demo across three smartphones, including two Android Pixel 10a devices and an iPhone 17e. According to reports, Tencent has since blocked the exploit, and the demo was conducted as a proof-of-concept rather than a live attack.

rss · Simon Willison · Sep 10, 00:56

**Background**: A zero-click exploit compromises a device without any action from the victim, making it far more dangerous than attacks that require a link click or file download. Remote code execution (RCE) means an attacker can run arbitrary code on a target system from a remote location, and a worm is malware that automatically copies itself to new victims, enabling rapid, self-sustaining spread. WeChat is a hugely popular messaging and calling app in China, so a worm that spreads through its voice-call feature could potentially reach an enormous user base.

<details><summary>References</summary>
<ul>
<li><a href="https://thehackernews.com/2026/09/wechat-zero-click-worm-took-over.html">WeChat Zero-Click Worm Took Over Accounts on iPhone and ...</a></li>
<li><a href="https://cybersecuritynews.com/weworm-first-0-click-worm/">WeWorm - First 0-Click Worm Spreading Through WeChat Calls ...</a></li>
<li><a href="https://www.1950.ai/post/wechat-zero-click-worm-how-ai-turned-a-voip-vulnerability-into-a-self-spreading-account-hijacking-t">WeChat Zero-Click Worm: How AI Turned a VoIP Vulnerability Into...</a></li>

</ul>
</details>

**Tags**: `#security`, `#AI`, `#mobile-exploit`, `#zero-click`, `#WeChat`

---

<a id="item-2"></a>
## [Shopify migrates mobile app from React Native back to native Swift and Kotlin](https://shopify.engineering/back-to-native) ⭐️ 8.0/10

Shopify announced it is migrating its mobile app away from React Native back to fully native development using Swift for iOS and Kotlin for Android. The company cited staying closer to platform capabilities and first-party tooling, with fewer framework and dependency layers between its code and the platform. This is a high-profile reversal by a major e-commerce company and has reignited the long-running cross-platform versus native development debate, especially as AI-assisted code migration tools make such rewrites cheaper. It could influence how other large engineering organizations weigh React Native against native stacks. Shopify says React Native apps can be fast and that its own app was fast, so the move is not primarily about performance but about platform alignment and reduced abstraction layers. The migration also comes amid debate over whether LLM-assisted tooling made the rewrite economically feasible, with community members noting similar migrations were done before AI assistance.

hackernews · fnthawar2 · Sep 10, 14:09 · [Discussion](https://news.ycombinator.com/item?id=49643982)

**Background**: React Native is an open-source framework from Meta that lets developers build iOS and Android apps using JavaScript and React with a single shared codebase. Swift is Apple's modern language for iOS, macOS and related platforms, while Kotlin is a statically typed JVM language that Google promotes as the preferred language for Android development. The trade-off between cross-platform frameworks and fully native code has been a recurring theme in mobile engineering for years.

<details><summary>References</summary>
<ul>
<li><a href="https://reactnative.dev/">React Native · Learn once, write anywhere</a></li>
<li><a href="https://developer.apple.com/swift/">Swift - Apple Developer</a></li>
<li><a href="https://developer.android.com/kotlin/">Kotlin and Android | Android Developers</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were sharply divided: some questioned whether Shopify's large engineering headcount undermines its authority on engineering decisions, while others shared firsthand accounts of migrating React Native apps to native code, some arguing LLMs made it far cheaper and others insisting such migrations were already feasible before AI. A common critique was that the article never clearly articulates the user-facing benefit of going native.

**Tags**: `#React Native`, `#Mobile Development`, `#Swift`, `#Kotlin`, `#Engineering Culture`

---

<a id="item-3"></a>
## [OpenAI Launches Agents API with Self-Hosted Sandbox Option](https://developers.openai.com/api/docs/guides/agents-api/overview) ⭐️ 8.0/10

OpenAI released the Agents API, which lets developers create production-ready agents in a single API call by specifying the task, model, tools, and environment, with OpenAI hosting and maintaining the underlying Codex harness. The API includes automatic context compaction, multi-agent orchestration, programmatic tool calling, and MCP support, and notably allows developers to self-host their sandbox environment. This is a significant platform-level move that positions OpenAI as a full-stack agent provider, potentially simplifying agent development for teams that lack the resources to build their own harness. It also intensifies the debate over vendor lock-in versus open, self-hosted alternatives in the fast-growing agentic AI ecosystem. The Agents API runs the Codex harness and manages agent infrastructure, including automatic context compaction, multi-agent orchestration, programmatic tool calling, and MCP support. A key detail buried in the documentation is that developers can opt to self-host their sandbox, which may ease transitions between providers and reduce lock-in concerns.

hackernews · aquir · Sep 10, 19:43 · [Discussion](https://news.ycombinator.com/item?id=49649213)

**Background**: AI agents are systems that use large language models to autonomously perform tasks by calling tools and maintaining state across steps. Building a reliable agent harness — the orchestration layer that manages context, tool calls, and execution environments — is a complex undertaking, which is why many developers rely on frameworks or managed services. OpenAI's Agents API packages this harness as a hosted service, while still offering a self-hosted sandbox option for those who want more control over execution and data.

<details><summary>References</summary>
<ul>
<li><a href="https://developers.openai.com/api/docs/guides/agents">Agents SDK | OpenAI API</a></li>
<li><a href="https://openai.com/index/introducing-the-agents-api/">Introducing the Agents API | OpenAI</a></li>
<li><a href="https://northflank.com/blog/self-hosted-ai-sandboxes">Self-hosted AI sandboxes: Guide to secure code execution in 2026 | Blog — Northflank</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed: some see the API as a useful abstraction that solves the hard problem of building and hosting an agent harness, especially for environments without a file system, while others criticize it as unnecessary vendor lock-in and point out that self-hosting the sandbox or running Codex in a VM can avoid lock-in. A recurring complaint is that OpenAI should provide the reasoning tokens users pay for instead of pushing more proprietary services.

**Tags**: `#openai`, `#agents`, `#api`, `#llm`, `#vendor-lock-in`

---

<a id="item-4"></a>
## [Researchers question whether OpenAI can be trusted with unpublished math](https://mathstodon.xyz/@andreasthom/117240535270608201) ⭐️ 8.0/10

A Mathstodon post by Andreas Thom sparked a large discussion (826 points, 762 comments) about whether researchers can trust OpenAI with unpublished mathematics, after concerns arose that OpenAI may have used collaborative chats with researchers to train its models and then published results along those lines without attribution. The thread cites a related X/Twitter post by Valerio Capraro and a Bluesky discussion, and commenters debate whether OpenAI's internal models genuinely solved open problems or benefited from fresh training data supplied through researcher interactions. This matters because it touches on research integrity, data privacy, and the ethics of AI companies using user conversations for training, potentially deterring mathematicians from collaborating with AI labs or sharing unpublished work. If researchers cannot trust that their ideas will be attributed, the open collaboration model that has driven much AI-for-science progress could erode, affecting both academia and industry labs. Commenters note that OpenAI reportedly gave at least 100,000 researchers free access to its models, and that internal models are said to solve open problems at a surprisingly fast rate, raising the possibility that fresh training data from researcher chats improves model intuition. Others argue both things can be true: chats may enhance latent representations, while reinforcement learning on verifiable math with massive compute could independently discover superhuman techniques, and some find it suspicious that OpenAI generated 300 billion output tokens from a model still in training right after learning a major proof might be in its training data.

hackernews · pred_ · Sep 10, 06:49 · [Discussion](https://news.ycombinator.com/item?id=49639408)

**Background**: OpenAI's data usage policies state that conversations may be used to improve and train models unless users opt out, and the company retains certain interaction data while reducing personal information in training sets. In AI research, attribution standards for machine contributions are still emerging, with tools like IBM's AI attribution toolkit and the AIACTA open specification attempting to define transparency and provenance norms. The debate reflects broader tensions as AI systems become active participants in mathematical discovery rather than passive tools.

<details><summary>References</summary>
<ul>
<li><a href="https://help.openai.com/en/articles/5722486-api-data-usage-policies">How your data is used to improve model performance | OpenAI ...</a></li>
<li><a href="https://openai.com/policies/how-your-data-is-used-to-improve-model-performance/">How your data is used to improve model performance - OpenAI</a></li>
<li><a href="https://research.ibm.com/blog/AI-attribution-toolkit">A new tool for crediting AI’s contributions - IBM Research</a></li>

</ul>
</details>

**Discussion**: Commenters largely see a strong ethical problem, with one comparing OpenAI to a human collaborator who publishes a joint result without crediting the other party, and another suspecting 'parallel construction' in OpenAI's decision to generate 300 billion output tokens from a training model after learning a major proof might be in its data. Others caution that both explanations can coexist—chats may improve model intuition while RL on verifiable math independently discovers superhuman techniques—and some question whether rapid AI progress on open problems is real or an artifact of fresh training data.

**Tags**: `#AI ethics`, `#OpenAI`, `#research integrity`, `#data privacy`, `#machine learning`

---

<a id="item-5"></a>
## [Forgejo 16.0.4 Fixes Critical RCE in Template Expansion](https://codeberg.org/forgejo/forgejo/src/branch/forgejo/release-notes-published/16.0.4.md) ⭐️ 8.0/10

Forgejo released versions 16.0.4 and 15.0.8 to fix a critical remote code execution vulnerability (CVE-2026-89094) affecting all versions before 16.0.4. The flaw occurs when generating a new repository from a template repository, where mishandled template expansion on files in the .forgejo/template directory can be exploited with a crafted template. Because Forgejo is a widely used self-hosted Git service, this critical RCE could allow attackers to execute arbitrary code on vulnerable instances, potentially compromising source code and CI/CD pipelines. Administrators running affected versions should upgrade immediately to 16.0.4 or 15.0.8. The vulnerability is tracked as CVE-2026-89094 and involves template expansion on files in .forgejo/template being mishandled during repository initialization; the fix prevents template expansion from interfering with git repo initialization. The release notes also mention a second security fix, and the advisory notes that Gitea is protected against both issues.

hackernews · weierstass · Sep 10, 15:57 · [Discussion](https://news.ycombinator.com/item?id=49645907)

**Background**: Forgejo is a community-driven fork of Gitea, a self-hosted Git service similar to GitHub. Template repositories let users create new repositories pre-populated with files and configuration, and Forgejo performs variable substitution on files listed in .forgejo/template during that process. A remote code execution (RCE) vulnerability means an attacker can run arbitrary commands on the server, making it one of the most severe classes of security bugs.

<details><summary>References</summary>
<ul>
<li><a href="https://cve.halosecurity.com/cve-advisory/cve-2026-89094-forgejo-remote-code-execution-via-template-expansion">Forgejo Remote Code Execution via Template Expansion ...</a></li>
<li><a href="https://lwn.net/Articles/1093671/">Forgejo 16.0.4 and 15.0.8 address critical security vulnerability</a></li>
<li><a href="https://www.rapid7.com/db/vulnerabilities/cve-2026-89094/">CVE-2026-89094: Forgejo: Forgejo before 16.0.4 ... - Rapid7</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted the specific pull requests and noted that Gitea is protected against both issues, while others discussed the role of AI in vulnerability discovery and the potential disadvantage of disallowing LLM contributions. Some users also pointed out that the release notes were temporarily unreadable due to Codeberg rate limits.

**Tags**: `#security`, `#vulnerability`, `#forgejo`, `#git`, `#rce`

---

<a id="item-6"></a>
## [Microsoft Elevates Rust to Tier-1 Internal Language](https://rustfoundation.org/media/guest-post-rust-is-tier-1-language-at-microsoft/) ⭐️ 8.0/10

At RustConf, Microsoft principal engineer Victor Ciura announced that Rust is now a Tier-1 language at Microsoft, placing it alongside C++, C#, and TypeScript as one of the best-supported languages for internal development. The company also replaced LLVM with a custom MSVC backend for its Rust toolchain. This makes Microsoft the latest major OS vendor to diversify its systems programming options, signaling that Rust is now a mature, serious competitor to C++ and C# rather than a niche experiment. It could accelerate large-scale migration of legacy C and C++ codebases across the industry. Tier-1 status means Rust gets the full 'paved path' from developer laptop to production, including secure supply-chain builds, SDL compliance, and deep platform integration. Microsoft has also set a goal to convert 1 billion lines of code to Rust by 2030 via automated tooling, and DARPA is funding work to automate C-to-Rust conversion across six teams.

hackernews · mmastrac · Sep 10, 13:39 · [Discussion](https://news.ycombinator.com/item?id=49643546)

**Background**: Rust is a systems programming language focused on memory safety and performance, originally developed at Mozilla. Microsoft has been investing in Rust for years, particularly for security-sensitive components, and the Rust Foundation promotes its adoption across the industry. Tier-1 designation is significant because it means a language receives first-class tooling, documentation, and support within a company's engineering workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://rustfoundation.org/media/guest-post-rust-is-tier-1-language-at-microsoft/">Guest Post: Rust Is Tier-1 Language at Microsoft</a></li>
<li><a href="https://www.theregister.com/devops/2026/09/11/microsoft-annoints-rust-as-a-tier-1-internal-language/5295732">Microsoft annoints Rust as a 'Tier 1' internal language</a></li>
<li><a href="https://mangodeveloper.com/articles/microsoft-makes-rust-a-tier-1-language-ships-custom-msvc-backend">Microsoft Makes Rust a Tier-1 Language, Ships Custom MSVC ...</a></li>

</ul>
</details>

**Discussion**: Commenters largely see this as a milestone proving Rust's maturity, with some noting it is no longer a 'moves fast and breaks things' language compared to newer alternatives like Zig and Odin. Others highlighted the MSVC backend replacement as the biggest technical news and pointed to Microsoft's 1B LOC conversion goal and DARPA-funded C-to-Rust automation as evidence of serious commitment.

**Tags**: `#Rust`, `#Microsoft`, `#systems-programming`, `#language-adoption`, `#C++`

---

<a id="item-7"></a>
## [Anthropic report accuses Moonshot and DeepSeek of secretly proxying to Claude](https://www.anthropic.com/threat-intelligence-report-september-2026) ⭐️ 8.0/10

Anthropic's September 2026 threat intelligence report, covering cases disrupted between December 2025 and August 2026, states that Moonshot AI silently forwarded customer requests to Claude instead of processing them with its own Kimi models, and that DeepSeek similarly relayed exchanges to Claude without informing its customers. The report also says MiniMax built its own proxy network service through a shell company, and it details misuse cases across seven harm areas including cyber operations and biological misuse. The report escalates the public dispute between Anthropic and Chinese AI labs over model distillation and API proxying, and it raises unresolved questions about whether routing requests through a competitor's model violates terms of service or constitutes deceptive marketing to end users. It also intensifies scrutiny of Chinese open-weight models that are already being used to post-train US models such as Cursor's Composer 2 and Cognition's Devin. The report covers threat actors disrupted between December 2025 and August 2026, including a Yemen-based cell, China-based actors, and Russia-based freelancers, while Anthropic says it is withholding the names of research institutions in the biological misuse section. Moonshot's Kimi K3, released in July 2026, is the largest open-weights model ever at 2.8 trillion parameters, and its custom license requires revenue sharing of up to 30% for inference providers earning over $20 million annually.

hackernews · garo-pro · Sep 10, 17:23 · [Discussion](https://news.ycombinator.com/item?id=49647300)

**Background**: Anthropic publishes periodic threat intelligence reports describing how its Claude models are misused and how it disrupts such activity, with earlier editions released in August 2025. Moonshot AI is a Beijing-based company behind the Kimi family of open-weights models and one of China's 'AI Tigers', while DeepSeek is a Hangzhou-based developer of open-weights LLMs owned by the hedge fund High-Flyer. 'Distillation' refers to training a model on another model's outputs, a practice Anthropic has accused Chinese competitors of using against Claude throughout 2026.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/threat-intelligence-report-september-2026">Countering misuse of AI: September 2026 / Anthropic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Moonshot_AI">Moonshot AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were sharply critical, with several accusing Anthropic of a double standard for treating competitors' proxying and distillation as misuse while training on others' data itself. Others argued the report conflates genuinely harmful activity with conduct that merely threatens Anthropic's business model, and one commenter noted that the report labels using AI for AI research as misuse.

**Tags**: `#AI misuse`, `#Anthropic`, `#threat intelligence`, `#AI ethics`, `#industry news`

---

<a id="item-8"></a>
## [trynix.dev runs any Nix package from 13 years in the browser](https://simonwillison.net/2026/Sep/10/trynix/) ⭐️ 8.0/10

Farid Zakaria launched trynix.dev, which uses qemu-wasm to run an x86_64 Linux virtual machine entirely in the browser via WebAssembly, bootable with any Nix package from the past 13 years. Packages are URL-addressable, so a link like https://trynix.dev/?pkg=python3%403.6.2 loads an interactive shell running Python 3.6.2 from 2017, and a companion GitHub Action, trynix-preview, comments a link on pull requests so reviewers can boot the PR's build in the browser. This makes historical and reproducible software environments instantly accessible through a URL, with no server, container, or local install required, which lowers the barrier for testing, teaching, and debugging. The trynix-preview action turns code review into an executable experience, letting reviewers boot a pull request's build directly in the browser, a meaningful step for reproducibility and supply-chain verification in the Nix ecosystem. The system relies on qemu-wasm, an experimental port of QEMU to WebAssembly that supports TCG JIT compilation, networking, and mounting, and it runs unmodified Linux guests in the browser. Because everything executes client-side, performance depends on the browser's WebAssembly capabilities, and the approach is best suited to interactive exploration rather than heavy workloads.

rss · Simon Willison · Sep 10, 23:44

**Background**: Nix is a purely functional package manager, created by Eelco Dolstra in 2003, that treats software packages as immutable values and is known for reproducible, declarative builds. QEMU is a general-purpose machine emulator and virtualizer, and qemu-wasm is a project that compiles QEMU to WebAssembly so full operating systems can run inside a browser tab. WebAssembly is a safe, sandboxed binary instruction format that lets near-native code execute in the browser under the same security policies as JavaScript.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/ktock/qemu-wasm">GitHub - ktock/qemu-wasm: QEMU on browser · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Nix_(package_manager)">Nix (package manager)</a></li>
<li><a href="https://webassembly.org/">WebAssembly</a></li>

</ul>
</details>

**Discussion**: The item was surfaced via Lobste.rs, where the linked write-up "Review a pull request by booting it" drew attention, and Simon Willison amplified it as a technically impressive project. Overall sentiment is positive, with the main framing being that this is a high-value engineering feat for reproducibility and PR review rather than a paradigm shift.

**Tags**: `#Nix`, `#WebAssembly`, `#qemu`, `#reproducibility`, `#browser`

---

<a id="item-9"></a>
## [ACL Announces Sustainable Reviewing Policy Capping Submissions](https://www.reddit.com/r/MachineLearning/comments/1wd7b83/acl_sustainable_reviewing_policy_d/) ⭐️ 8.0/10

ACL announced a new "Sustainable Reviewing Policy" for its ACL Rolling Review (ARR) system, capping total submissions at 20 per author and first-author submissions at 5 per cycle. Each submission must now "pay" for itself by providing a qualified reviewer or chair, otherwise it enters a lottery for remaining capacity. This policy directly addresses the unsustainable growth in NLP paper submissions, which has strained the volunteer reviewer pool and threatened review quality. It could reshape submission incentives across the ML/NLP community, encouraging authors to contribute to reviewing and potentially reducing low-quality or mass submissions. The policy includes a mentorship system for authors not yet qualified to review, allows non-author designated contributors who must vouch for the work in an arXiv-endorsement style, and introduces penalties or bans for accounts that systematically submit or endorse low-quality work. The caps of 20 total and 5 first-author submissions per cycle are considered generous by the original poster.

reddit · r/MachineLearning · /u/S4M22 · Sep 11, 05:38

**Background**: ACL Rolling Review (ARR) is a centralized reviewing service for top-tier ACL conferences, where authors submit papers in two-month cycles and receive reviews and metareviews. Reviews are decoupled from acceptance decisions, allowing authors to revise and resubmit to different venues. In recent years, submission numbers have grown dramatically, putting immense pressure on the volunteer reviewer community.

<details><summary>References</summary>
<ul>
<li><a href="https://aclrollingreview.org/">ACL Rolling Review – A peer review platform for the ...</a></li>
<li><a href="https://aclrollingreview.org/dates">Dates and Venues – ACL Rolling Review – A peer review ... ACL Rolling Review ACL Rolling Review | ACL Member Portal ACL ARR - OpenReview ACL Rolling Review - Facebook GitHub - acl-org/aclrollingreview: ACL Rolling Review website</a></li>
<li><a href="https://www.aclweb.org/portal/content/acl-rolling-review">ACL Rolling Review | ACL Member Portal</a></li>

</ul>
</details>

**Discussion**: The Reddit poster expressed strong support for the policy, calling it "highly required" despite being a form of gatekeeping, and noted that the caps are still generous. The discussion likely includes diverse viewpoints on the pros and cons of tying review capacity to submission slots.

**Tags**: `#ACL`, `#peer-review`, `#conference-policy`, `#NLP`, `#research-community`

---

<a id="item-10"></a>
## [Fly connectome fails to learn Pong, audit reveals bugs and circuit limits](https://www.reddit.com/r/MachineLearning/comments/1wc67ci/i_tried_to_make_a_real_fly_connectome_learn_to/) ⭐️ 8.0/10

A developer attempted to train a small real subgraph of the MaleCNS v1.0 fly connectome to play Pong using dopamine-style plasticity, but it failed to learn. A detailed audit uncovered a neuPrint regex bug that zeroed out two neuron populations, a missing photoreceptor-to-motion-detector pathway, and motor neurons with zero sensory synapses, while also showing that viral projects like Doom, Minecraft, and Beat Saber demos had similar validation failures. This negative result provides a rigorous case study showing that many viral 'fly brain plays game' demos may not actually validate learning or emergent behavior, which could mislead the computational neuroscience and ML communities. It highlights the importance of auditing connectome simulations and understanding circuit-level constraints before claiming brain-like performance. The audit found that half of the four available motor neurons had zero synapses from any sensory pathway, and learning-on vs learning-off produced bit-for-bit identical results across multiple seeds despite weights changing. The effect of the learning rule appeared to quiet the system rather than improve skill, with punishment dominating due to more misses than hits.

reddit · r/MachineLearning · /u/oPeraza2007 · Sep 10, 02:28

**Background**: A connectome is a comprehensive map of neural connections in a brain, and the MaleCNS v1.0 is a full adult male Drosophila central nervous system reconstruction with 166,000 neurons from electron microscopy. Dopamine-style plasticity is a learning mechanism where dopamine modulates synaptic strengths based on reward or punishment signals. Pong is a simple video game often used as a benchmark for learning agents because it provides a clear binary hit-or-miss signal.

<details><summary>References</summary>
<ul>
<li><a href="https://male-cns.janelia.org/">Male CNS Connectome - MaleCNS connectome</a></li>
<li><a href="https://github.com/nftechie/doomfly">GitHub - nftechie/doomfly: Fly- connectome simulation controlling a live...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Connectome">Connectome - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The Reddit post asks if others have encountered similar walls with MaleCNS v1.0, especially around the central complex and steering circuits, suggesting that simulating these properly is the obvious next step. No further comments were provided in the content.

**Tags**: `#computational-neuroscience`, `#connectome`, `#machine-learning`, `#plasticity`, `#negative-results`

---

<a id="item-11"></a>
## [Anthropic Restricts Claude to Users 18 and Older](https://support.claude.com/en/articles/15171100-age-assurance-on-claude) ⭐️ 7.0/10

Anthropic has updated its age assurance policy so that Claude is no longer available to minors, requiring users to be 18 or older and introducing age verification for consumer accounts. The change applies to Claude Free, Pro, and Max plans, while Team, Enterprise, and Developer Platform users are unaffected. This is a significant accessibility and privacy shift from a major AI provider, potentially pushing minors toward alternative models and raising questions about how AI companies should handle underage users. It also sets a precedent that could influence how other AI platforms approach age gating and parental controls. Anthropic's updated privacy policy, effective July 8, 2026, allows age and identity verification that may include government-issued ID images, facial geometry templates, and verification results. The policy applies only to consumer accounts and not to commercial or enterprise offerings.

hackernews · Muhammad523 · Sep 11, 10:48 · [Discussion](https://news.ycombinator.com/item?id=49656225)

**Background**: Age verification for online services typically works through document scanning, biometric age estimation, or database lookups, and is increasingly required by regulations for age-restricted content. AI chatbots have historically lacked standardized parental controls, unlike platforms such as Netflix or YouTube Kids, leaving parents with fragmented options. Anthropic's move follows broader industry debates about protecting minors online while preserving privacy.

<details><summary>References</summary>
<ul>
<li><a href="https://privacy.claude.com/en/articles/10301952-updates-to-our-privacy-policy">Updates to our Privacy Policy | Anthropic Privacy Center</a></li>
<li><a href="https://cybersecuritynews.com/anthropic-updated-privacy-policy/">Anthropic Updated Privacy policy to Include Identity ...</a></li>
<li><a href="https://getsensible.app/blog/parental-controls-for-chatgpt">Parental Controls for ChatGPT: What Actually Works in 2026 - Sensible</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were largely critical, arguing that age verification is invasive and that OS-level parental controls would be a better solution. Some pointed to Chinese models as an alternative without age checks, while others questioned whether banning minors is justified and noted that enforcement may already be happening in some regions.

**Tags**: `#AI policy`, `#age verification`, `#privacy`, `#Anthropic`, `#Hacker News`

---

<a id="item-12"></a>
## [WebGL 'Deathray' Lets Untrusted Sites Freeze Macs](https://auberon.xyz/blog/posts/deathray/) ⭐️ 7.0/10

A blog post titled 'The Deathray' describes a simple technique that allows an untrusted website to freeze a Mac, most likely by abusing WebGL to exhaust GPU resources. The post sparked a Hacker News discussion with 147 comments, where users reported real crashes and debated mitigations. This highlights a long-standing denial-of-service risk in WebGL that can render a machine unusable without stealing data, affecting anyone who visits a malicious or careless site. It also forces a trade-off between disabling WebGL for safety and losing popular web apps like Figma, Canva, and Google Maps. The technique appears to rely on WebGL's direct GPU interaction to exhaust resources, causing the browser or whole system to freeze; one commenter reported it completely crashed Firefox on Linux. Because the attack is a denial-of-service rather than a data breach, the main damage is lost time and productivity, and browsers may even reopen the offending tab on restart.

hackernews · auberonedu · Sep 10, 19:34 · [Discussion](https://news.ycombinator.com/item?id=49649124)

**Background**: WebGL is a JavaScript API that lets websites render 3D graphics directly on the GPU, powering interactive tools like Figma, Canva, and Google Maps. Because it runs untrusted code close to the graphics hardware, security researchers have long warned that WebGL can be abused for denial-of-service attacks that crash or freeze a browser. This class of issue has been known since WebGL shipped around 2011 and is documented in the specification.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Denial-of-service_attack">Denial-of-service attack - Wikipedia</a></li>
<li><a href="https://blog.pixelfreestudio.com/webgl-security-best-practices-ensuring-safe-3d-web-experiences/">WebGL Security Best Practices: Ensuring Safe 3D Web Experiences</a></li>
<li><a href="https://security.stackexchange.com/questions/13799/is-webgl-a-security-concern">web browser - Is WebGL a security concern? - Information ...</a></li>

</ul>
</details>

**Discussion**: Commenters noted the issue has existed since WebGL shipped in 2011 and is a self-correcting problem because users simply avoid sites that freeze their machines, though disabling WebGL would break Figma, Canva, and Google Maps. Others pointed out WebGL is slower than native 3D APIs due to sandboxing, shared historical browser-crash pranks from the 90s, and reported that the demo crashed Firefox on Linux while leaving other programs unaffected.

**Tags**: `#WebGL`, `#security`, `#denial-of-service`, `#browser`, `#macOS`

---

<a id="item-13"></a>
## [NASA's Decorrelation Stretch Reveals Ancient Rock Art](https://spinoff.nasa.gov/Manipulating_Satellite_Photos_Now_Reveals_Ancient_Images) ⭐️ 7.0/10

NASA's decorrelation stretch, a technique originally developed to enhance satellite and Mars rover imagery, is now being used to uncover faded ancient rock art. Around 2005, rock art enthusiast and medical imaging professional Jon Harman adapted the method into the DStretch plugin, which has since become a widely used tool in archaeology. This is a notable example of a NASA spinoff, showing how remote-sensing technology can be repurposed for cultural heritage preservation. It highlights the cross-disciplinary value of signal processing, with the same core idea appearing in medical imaging and remote sensing. Decorrelation stretch works by removing inter-channel correlation in a color image and then stretching the color differences, making subtle variations visible. The DStretch plugin has been available since around 2005, and similar contrast-enhancement effects can be approximated in tools like GIMP using LAB color decomposition and auto-levels.

hackernews · gumby · Sep 10, 15:29 · [Discussion](https://news.ycombinator.com/item?id=49645437)

**Background**: Decorrelation stretch is an image processing technique that enhances color differences in multispectral or RGB imagery by removing correlation between color channels. It was developed for remote sensing and planetary imaging, where it helps scientists spot subtle surface features. The technique is now applied to archaeology, where faded pigments on rock surfaces can be made visible again.

<details><summary>References</summary>
<ul>
<li><a href="https://spinoff.nasa.gov/Manipulating_Satellite_Photos_Now_Reveals_Ancient_Images">Technique for Manipulating Satellite Photos Now... | NASA Spinoff</a></li>
<li><a href="https://www.nasa.gov/technology/tech-transfer-spinoffs/nasa-technique-for-manipulating-satellite-photos-now-reveals-ancient-images/">NASA Technique for Manipulating Satellite Photos Now Reveals ...</a></li>
<li><a href="https://asterweb.jpl.nasa.gov/content/03_data/01_Data_Products/d-stretch.pdf">Decorrelation Stretch</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the technique is not new, with DStretch dating back to around 2005 and similar contrast enhancement long used in medical imaging and remote sensing. Some shared practical GIMP steps for achieving similar results, while others discussed the broader insight that human vision is not canonical and that false-color composites can reveal hidden information.

**Tags**: `#image-processing`, `#remote-sensing`, `#archaeology`, `#NASA-spinoff`, `#signal-processing`

---

<a id="item-14"></a>
## [Cognition launches SWE-2 coding model, claims parity with Fable 5.1 and GPT-Astra](https://cognition.com/blog/swe-2) ⭐️ 7.0/10

Cognition released SWE-2, a new coding model it calls its most advanced yet and its closest to the frontier, post-trained from the 2.8T-parameter Kimi K3 model. The company claims SWE-2 rivals Anthropic's Claude Fable 5.1 and OpenAI's GPT-6 Astra, and it is the first SWE model with adjustable reasoning effort levels. The release intensifies competition in the AI coding assistant market, where Cognition's Devin competes with frontier models from Anthropic and OpenAI. It also highlights a growing trend of post-training open base models like Kimi K3 into specialized commercial products, raising questions about benchmark credibility and closed-weight lock-in. SWE-2 adds 5-6 points on many benchmarks over its Kimi K3 base, but Cognition published no SWE-bench Verified score, token pricing, or context window, and vals.ai archived its SWE-bench Verified leaderboard on September 5, 2026 citing score saturation. Community members also flagged the huge gap between Terminal Bench 2.1 (92.8%) and the newer Terminal Bench 4 (27.3%) as evidence of possible benchmark overfitting.

hackernews · seelos · Sep 10, 15:29 · [Discussion](https://news.ycombinator.com/item?id=49645443)

**Background**: Cognition is the company behind Devin, an autonomous AI software engineer, and has previously faced skepticism over demo credibility. SWE-2 is post-trained from Kimi K3, a large open model already heavily RL-trained for agentic coding, meaning Cognition fine-tuned an existing model rather than training one from scratch. Claude Fable 5.1 is Anthropic's frontier coding model released September 1, 2026, and GPT-6 Astra is OpenAI's flagship model released September 3, 2026.

<details><summary>References</summary>
<ul>
<li><a href="https://cognition.com/blog/swe-2">Introducing SWE - 2 : Pushing the Pareto Frontier | Cognition</a></li>
<li><a href="https://cellcog.ai/blog/cognition-swe-2/">Cognition SWE - 2 : Benchmarks, the 64% Cost Claim, and... | CellCog</a></li>
<li><a href="https://genztech.blog/models/cognition-swe-2/">Cognition SWE - 2 for Coding — Benchmarks, Pricing & Specs (2026)</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were largely skeptical: one highlighted the Terminal Bench 2.1 vs 4.0 delta as a sign of benchmark overfitting, another recalled Cognition's past demo credibility issues, and others questioned why anyone would choose another closed-weight model over open alternatives like DeepSeek Flash 4.1. Some acknowledged that post-training Kimi K3 to Fable 5-level capability is a positive signal, while one dismissed Devin as the most consistently poor product they had used.

**Tags**: `#AI`, `#coding-assistants`, `#model-release`, `#benchmarking`, `#open-weights`

---

<a id="item-15"></a>
## [PlanetScale Launches Neki, a Sharded Postgres Offering](https://planetscale.com/blog/introducing-neki) ⭐️ 7.0/10

PlanetScale introduced Neki, a sharded Postgres solution that adds a router, sidecars, and a control plane on top of standard Postgres shards to scale to hundreds of millions of QPS and petabytes of data without downtime. The launch generated 252 points and 132 comments on Hacker News, with discussion focused on architecture, consistency guarantees, and marketing claims. Neki represents a significant new sharded Postgres offering from a major database vendor, signaling growing competition in the distributed Postgres space, particularly against Supabase's Multigres. It matters because Postgres lacks native sharding, and a managed sharding layer from PlanetScale could make horizontal scaling more accessible to teams running large workloads. Neki claims to provide 'unlimited IOPS' on 'PlanetScale Metal', a claim that drew skepticism from commenters who questioned whether it is a technical miracle or false marketing. PlanetScale has stated that Neki will be released as open source once it is ready and tested in real production workloads, but it is currently a closed launch.

hackernews · simon_weber · Sep 10, 15:43 · [Discussion](https://news.ycombinator.com/item?id=49645686)

**Background**: PostgreSQL does not ship with a native, built-in sharding engine, so scaling it horizontally typically requires external tools or middleware. Sharding splits data across multiple Postgres clusters, each holding a partition, with a coordinator routing queries to the appropriate shard. PlanetScale previously built its business on Vitess, an open-source sharding system for MySQL originally developed at Google, and Neki is its equivalent effort for Postgres.

<details><summary>References</summary>
<ul>
<li><a href="https://neki.dev/?ref=upstract.com">Neki | Sharded Postgres by PlanetScale</a></li>
<li><a href="https://planetscale.com/neki">Neki — PlanetScale</a></li>
<li><a href="https://www.percona.com/blog/an-overview-of-sharding-in-postgresql-and-how-it-relates-to-mongodbs/">PostgreSQL Sharding : An Overview and MongoDB... - Percona</a></li>

</ul>
</details>

**Discussion**: Commenters criticized the launch post for failing to clearly describe what Neki is and what it is for in the opening paragraph. Others raised concerns about eventual consistency and CAP theorem trade-offs, questioned the 'unlimited IOPS' marketing claim, and pointed out the irony that Neki is closed source while PlanetScale's CEO has criticized Supabase's open-source Multigres.

**Tags**: `#Postgres`, `#Database Sharding`, `#PlanetScale`, `#Distributed Systems`, `#CAP Theorem`

---

<a id="item-16"></a>
## [Open-Source 'Proof of Capture' Uses Steganography to Verify Image Authenticity](https://merybenavente.me/blog/proof-of-capture) ⭐️ 7.0/10

A new blog post titled 'Proof of Capture' presents an open-source, steganography-based method for proving that an image was captured by a real camera rather than generated or edited, positioning itself as an alternative to Apple's Reference Image feature. The approach embeds a signed perceptual hash (pHash) of the image into the image data itself, rather than relying on a separate signed original stored by the manufacturer. As AI-generated and manipulated images become more convincing, reliable proof of capture is increasingly important for journalism, legal evidence, and social media authenticity. An open-source alternative to Apple's proprietary Reference Image could democratize this capability, but the community discussion reveals serious security concerns that may limit its practical trustworthiness. The scheme signs a perceptual hash (pHash) of the image rather than an exact pixel checksum, which means it tolerates minor modifications but also inherits the non-cryptographic weaknesses of perceptual hashing. Community members noted that preimage attacks against pHash-based schemes like PhotoDNA and PDQ have been demonstrated, and that a 15%x20% similarity threshold could allow swapping a face while still passing as authentic.

hackernews · merybenavente · Sep 10, 19:44 · [Discussion](https://news.ycombinator.com/item?id=49649222)

**Background**: Apple's Reference Image, announced for the iPhone 18 Pro, is an opt-in feature that stores an untouched original with verification metadata so a photo can be shown to come from a real capture rather than AI. Steganography is the practice of hiding data within other data, such as embedding a signature inside image pixels. Perceptual hashing generates a compact fingerprint based on how an image looks rather than its exact binary content, making it useful for detecting similar images but not for cryptographic security.

<details><summary>References</summary>
<ul>
<li><a href="https://appleinsider.com/articles/26/09/09/apple-reference-image-is-a-new-way-to-authenticate-iphone-photography">Apple Reference Image is a new way to authenticate iPhone ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Perceptual_hashing">Perceptual hashing</a></li>

</ul>
</details>

**Discussion**: Commenters raised significant security concerns: nmadden warned that signing by default can have unintended consequences, such as undeniably linking leaked photos to their owner; Retr0id pointed out that perceptual hashes are non-cryptographic and cited demonstrated preimage attacks against PhotoDNA and PDQ; treyd noted that an attacker with an FPGA could spoof the photosensor controller; and Wendell58 argued that the 15%x20% threshold is too loose and could allow swapping a face.

**Tags**: `#steganography`, `#image authentication`, `#perceptual hashing`, `#security`, `#open source`

---

<a id="item-17"></a>
## [Datasette 1.0a39 and 0.65.4 security patches after AI-assisted audit](https://simonwillison.net/2026/Sep/11/datasette-security/) ⭐️ 7.0/10

Datasette released two security patch versions on the same day: 1.0a39 for the current alpha series and 0.65.4 for the stable 0.65.x family. The fixes came out of an extensive audit run by Simon Willison and Alex Garcia using Claude Fable 5.1, GPT-5.6, and GPT-6 Astra, followed by nearly a week of human review, and were prompted by issues reported by Sevban Dönmez. Anyone running a Datasette instance on the public web should upgrade, especially if that instance mixes public and private tables behind an authentication layer, since the bugs were subtle enough to evade normal review. The release also signals that frontier-model security audits are becoming a standard part of open-source maintenance workflows. The maintainers split the work in a shared private repository: one person wrote automated tests reproducing each issue while the other implemented the fix, ensuring two humans plus coding agents on different models reviewed every problem. Willison said security audits by frontier models will be incorporated into all future Datasette development work.

rss · Simon Willison · Sep 11, 03:27

**Background**: Datasette is an open-source multi-tool for exploring and publishing data, turning SQLite databases into interactive, searchable websites with a built-in JSON API. It is widely used by data journalists, researchers, and archivists, and it supports permission systems that can expose some tables publicly while keeping others private. A prior 0.65.3 release already fixed a SQL injection issue affecting deployments that mix public and private tables in a single database.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Sep/11/datasette-security/">Datasette 1.0a39 and 0.65.4 security releases</a></li>
<li><a href="https://datasette.io/">Datasette: An open source multi-tool for exploring and ...</a></li>
<li><a href="https://jasonvsthenoise.com/repowatch/2026-08-07-datasette-private-table-sql-injection/">Datasette closes a SQL injection path into private tables</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#security`, `#open-source`, `#ai-assisted-development`, `#release`

---

<a id="item-18"></a>
## [348M model trained from scratch hits 99.4% on GPT-3 arithmetic benchmarks](https://www.reddit.com/r/MachineLearning/comments/1wc7hmu/i_trained_a_348m_model_trained_from_scratch_on/) ⭐️ 7.0/10

A developer trained a 348M-parameter language model from scratch on 22.7B tokens and fine-tuned it into a math model that solves arithmetic by explicitly showing worked steps such as column addition with carries and borrow chains. The model achieves 99.4% average accuracy across nine GPT-3 arithmetic sub-tasks, far surpassing GPT-3 175B's few-shot direct-answer results on multi-digit addition, subtraction, and multiplication. This demonstrates that a small model with roughly 1/500th the parameters of GPT-3 175B can dramatically outperform it on structured arithmetic when trained to show its work, suggesting that explicit reasoning traces and data quality matter more than raw scale for certain tasks. It also shows the model can generalize beyond its training data, inventing new place-value names like 'millions' and 'ten-millions' that never appeared in training. The model's clean addition ceiling jumped from 8 to 14 digits simply by extending the place-name vocabulary from 6 to 19 entries, and its reasoning traces are load-bearing: 95.3% of the time the working is valid and the answer is right. However, it struggles badly on word problems (GSM8K 4%, ASDiv 16.5%), has no division capability, requires greedy decoding, and its failure mode is operation selection rather than arithmetic itself.

reddit · r/MachineLearning · /u/nkthebass · Sep 10, 03:28

**Background**: GPT-3 arithmetic benchmarks are a set of nine sub-tasks (2- to 5-digit addition and subtraction, plus 2-digit multiplication) introduced with the GPT-3 paper to test whether language models can do basic math without a calculator. Small language models (SLMs) use the same architecture as large language models but with far fewer parameters, and prior work such as ArithmeticGPT has explored ways to boost their arithmetic skills. Training a model 'from scratch' means building and training it on raw text without starting from an existing pretrained checkpoint.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Small_language_model">Small language model - Wikipedia</a></li>
<li><a href="https://link.springer.com/article/10.1007/s10994-024-06681-1">ArithmeticGPT: empowering small-size large language models ... ArithmeticGPT: Empowering Small-Size Large Language Models ... Small language model - Wikipedia ArithmeticGPT: empowering small-size large language models ... Arithmetic with Language Models: from Memorization to ... Arithmetic with Language Models: from Memorization to Computation Reflect, Rewrite, Repeat: How Simple Arithmetic Enables ...</a></li>
<li><a href="https://github.com/rasbt/LLMs-from-scratch">GitHub - rasbt/LLMs-from-scratch: Implement a ChatGPT-like ...</a></li>

</ul>
</details>

**Tags**: `#language-models`, `#arithmetic`, `#small-models`, `#training-from-scratch`, `#benchmarks`

---

<a id="item-19"></a>
## [IAEA Explainer on Cherenkov Radiation Sparks Expert Discussion](http://www.iaea.org/newscenter/news/what-is-cherenkov-radiation) ⭐️ 6.0/10

The IAEA published an explainer article on Cherenkov radiation, the blue glow produced when charged particles travel faster than light in a medium such as water. The piece was surfaced on Hacker News, where physicists and engineers added substantial technical context about the phenomenon's applications. Cherenkov radiation underpins major scientific instruments, from neutrino detectors to gamma-ray telescopes, so accurate public communication of the concept matters for both science literacy and fields like nuclear engineering and astrophysics. The discussion also highlights how a seemingly simple explainer can become a venue for correcting common misconceptions about the speed of light. Commenters noted that the phrase 'faster than light' is misleading and should specify 'faster than light in a medium,' since nothing exceeds the speed of light in vacuum. They also pointed out that the IAEA article focuses on IAEA-related uses and omits the most widespread application: detecting high-energy particles via Imaging Atmospheric Cherenkov Telescopes and water Cherenkov detectors.

hackernews · andsoitis · Sep 11, 08:42 · [Discussion](https://news.ycombinator.com/item?id=49655286)

**Background**: Cherenkov radiation occurs when a charged particle, such as an electron, moves through a dielectric medium faster than the phase velocity of light in that medium, producing a characteristic blue glow—similar to a sonic boom for light. It is named after Soviet physicist Pavel Cherenkov, who shared the 1958 Nobel Prize in Physics with Ilya Frank and Igor Tamm for experimentally demonstrating and explaining the effect. The phenomenon is perhaps most familiar as the blue glow seen in the water surrounding nuclear reactor cores.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cherenkov_radiation">Cherenkov radiation - Wikipedia</a></li>
<li><a href="https://www.iaea.org/newscenter/news/what-is-cherenkov-radiation">What is Cherenkov Radiation? | IAEA</a></li>
<li><a href="https://www.energy.gov/ne/articles/cherenkov-radiation-explained">Cherenkov Radiation, Explained | Department of Energy</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion was broadly appreciative but corrective: commenters stressed that the 'faster than light' framing is misleading, highlighted the importance of Imaging Atmospheric Cherenkov Telescopes and water Cherenkov detectors in astrophysics, and shared a historical note that 1960s Cherenkov detector research led to nonimaging optics principles now used in solar concentrators and illumination design.

**Tags**: `#physics`, `#Cherenkov radiation`, `#astrophysics`, `#optics`, `#science communication`

---

<a id="item-20"></a>
## [Nine coding agent harnesses benchmarked on a laptop](https://nasutton.notion.site/Nine-coding-harnesses-vs-your-laptop-3d139990182b80d59fa3cf500f0450ba?pvs=74) ⭐️ 6.0/10

A new article benchmarks nine coding agent harnesses running on a laptop, comparing their real-world performance in resource-constrained environments. The write-up sparked a Hacker News discussion (123 points, 39 comments) where developers shared alternative lightweight tools and their own benchmark experiences. As coding agents proliferate, developers increasingly need to know which harnesses actually work on modest hardware rather than relying on vendor claims. This comparison helps developers choosing local coding agents make more informed decisions, especially those running local LLMs on laptops or small servers. The benchmark focuses on resource-constrained environments such as laptops, tiny VPS servers, and single-board computers, and emphasizes compatibility with local models. Community members noted that the field is churning rapidly, making it hard to know which harnesses are worth testing or adopting.

hackernews · nasutton12 · Sep 10, 22:54 · [Discussion](https://news.ycombinator.com/item?id=49651221)

**Background**: A coding agent harness is the scaffolding around a language model that provides tools, prompts, and workflow control, turning a raw model into an autonomous coding assistant. Examples include OpenAI's Codex CLI and Pi, a minimal agent harness. Running these agents locally on a laptop requires balancing model size, memory usage, and inference speed, which is why lightweight harnesses and local LLM serving tools like Ollama, vLLM, and llama.cpp are relevant.

<details><summary>References</summary>
<ul>
<li><a href="https://pi.dev/">A terminal-based coding agent</a></li>
<li><a href="https://github.com/openai/codex">GitHub - openai/codex: Lightweight coding agent that runs in your...</a></li>
<li><a href="https://pub.towardsai.net/agent-model-harness-what-a-coding-agent-harness-actually-is-3149945c26b5">Agent = Model + Harness : What a Coding Agent ... | Towards AI</a></li>

</ul>
</details>

**Discussion**: Commenters shared alternative lightweight tools: OleksandrC recommended hax, a 0.7 MB native C binary that auto-discovers local llama-server configs, while tontinton mentioned maki.sh. julesrms questioned how benchmarkers select harnesses, noting their own tool Juggler was never tested, and toasty228 reported that codex was faster and more token-efficient than pi and omp in their workload.

**Tags**: `#coding-agents`, `#benchmarking`, `#local-llm`, `#developer-tools`, `#resource-constrained`

---

<a id="item-21"></a>
## [Free Online Music Theory Textbook Sparks Hacker News Debate](https://musictheory.pugetsound.edu/mt21c/MusicTheory.html) ⭐️ 6.0/10

A free, comprehensive online music theory textbook hosted at musictheory.pugetsound.edu was shared on Hacker News, where it received 247 points and 105 comments. The discussion highlighted the textbook's self-study resources, including homework assignments, and included both praise for its SVG illustrations and a substantive critique of its pedagogical approach. This resource provides free, accessible music theory education for self-learners and classrooms, potentially lowering barriers for students who cannot afford traditional textbooks. The community discussion also reveals broader tensions in music pedagogy between rote memorization and contextual understanding, which could influence how such materials are designed in the future. The textbook includes SVG illustrations and a full set of homework assignments, making it suitable for self-study. A notable critique from the discussion is that it, like many music theory texts, presents facts to memorize without sufficient context or motivation, such as the pattern of whole and half steps in a major scale.

hackernews · aanet · Sep 10, 17:14 · [Discussion](https://news.ycombinator.com/item?id=49647134)

**Background**: Music theory is the study of the practices and possibilities of music, covering elements like scales, chords, harmony, and rhythm. Online textbooks have become increasingly popular as free or low-cost alternatives to traditional printed materials, especially for self-directed learners. Hacker News is a popular technology and startup news aggregator where users often share and discuss educational resources.

**Discussion**: The community response was largely positive, with users praising the textbook's self-study resources and SVG illustrations, and one user recommending the free 'Absolutely Understand Guitar' video series as a complementary resource. However, a substantive critique argued that the textbook suffers from the common problem of requiring rote memorization without context, and another user questioned the meaning of '21st-Century Classroom' in the title.

**Tags**: `#music theory`, `#education`, `#online textbook`, `#self-study`, `#Hacker News`

---

<a id="item-22"></a>
## [NTSB Update on B-767 Miami Runway Excursion Cites Pilot Errors](https://www.ntsb.gov/news/press-releases/Pages/NR20260909.aspx) ⭐️ 6.0/10

The NTSB released an investigative update on a Boeing 767 runway excursion accident in Miami, highlighting an unstable approach, excessive speed, and pilot errors by a relatively inexperienced crew on the aircraft type. The update describes a Captain (Pilot Flying) certified on the B767 only since May and a First Officer (Pilot Monitoring) who repeatedly raised concerns about speed without consistent verbal responses. The case is a stark illustration of why stabilized approach criteria and go-around discipline matter: an approach that never stabilized ended in a runway overrun that killed five people. It also renews attention on cockpit communication and crew resource management, particularly when both pilots are new to the aircraft type. According to the update, the aircraft was high and fast, the crew descended too rapidly, and the glideslope was not captured in time; the Pilot Monitoring's concerns about excessive speed throughout the recording did not receive consistent verbal responses. The accident was an overrun of an Amazon cargo aircraft, and the NTSB update is investigative rather than a final probable-cause determination.

hackernews · mckn1ght · Sep 10, 21:30 · [Discussion](https://news.ycombinator.com/item?id=49650418)

**Background**: A runway excursion is a runway safety event in which an aircraft inappropriately leaves the runway surface, either by veering off the side or overrunning the end; unstable approaches are a leading contributing factor. A stabilized approach means the aircraft is on the correct speed, glidepath, and configuration with minimal flight-control inputs by a defined gate, typically 1,000 feet above ground level, and if those criteria are not met, standard practice is to execute a go-around, an aborted landing in which the aircraft climbs away and repositions for another approach.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Runway_excursion">Runway excursion - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Go-around">Go - around - Wikipedia</a></li>
<li><a href="https://skybrary.aero/articles/runway-excursion">Runway Excursion - SKYbrary Aviation Safety Runway excursion - Wikipedia Runway Excursion | SKYbrary Aviation Safety What is a Runway Excursion? | Aviation Glossary | Aviatize Runway Safety Areas (RSAs) - Federal Aviation Administration Runway Excursion: Causes, Effects, Prevention, and Safety ...</a></li>

</ul>
</details>

**Discussion**: Commenters, including a pilot, stressed that the overarching lesson is procedural discipline: if stabilized approach criteria are not met at the 1,000-foot gate, go around, and this approach was a missed opportunity to do so. Others highlighted the breakdown in cockpit communication, noting that the Pilot Monitoring's repeated speed cautions drew no consistent verbal response, and one commenter noted the accident killed five people.

**Tags**: `#aviation safety`, `#NTSB`, `#runway excursion`, `#cockpit communication`, `#stabilized approach`

---

<a id="item-23"></a>
## [Sante's 83.83 on DiagnosisArena-MCQ Only Measures Multiple-Choice Diagnosis Selection](https://www.reddit.com/r/MachineLearning/comments/1wbkxsa/what_santes_8383_on_diagnosisarenamcq_actually/) ⭐️ 6.0/10

A Reddit analysis argues that Ant Ling's reported 83.83 score for Ling-3.0-flash-Sante on DiagnosisArena-MCQ only reflects the model's ability to pick one of four supplied diagnoses, not its broader clinical reasoning. The post also notes two other reported medical results — MedXpertQA-Text at 53.88 and HealthBench Professional at 45.73 — and warns that the HealthBench Professional score is not percentage accuracy and may be length-adjusted or unadjusted. As medical AI models increasingly advertise benchmark scores, this critique highlights how easily multiple-choice results can be misread as evidence of full clinical reasoning. It matters for developers, clinicians, and regulators who must decide whether a model can actually generate differentials, identify missing history, and choose next investigations in real care settings. DiagnosisArena-MCQ supplies case information, examinations, and tests, then asks the model to choose from four diagnoses, so the 83.83 figure applies only to the supplied-options version. The post also notes that the Sante chart lacks enough scoring detail to determine whether the HealthBench Professional value is length-adjusted or unadjusted, which complicates comparison with other published results.

reddit · r/MachineLearning · /u/Expert_Coffee_203 · Sep 9, 13:01

**Background**: DiagnosisArena is a benchmark built from 1,113 structured patient cases across 28 medical specialties, designed to assess diagnostic reasoning in clinical settings. MedXpertQA-Text is a text-only multiple-choice benchmark of 2,450 expert-level medical questions, while HealthBench Professional evaluates LLMs on clinician-relevant tasks using physician-written rubrics rather than simple accuracy. These benchmarks differ in what they measure, so a high score on one does not automatically transfer to another.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2505.14107v1">DiagnosisArena: Benchmarking Diagnostic Reasoning for Large ...</a></li>
<li><a href="https://medxpertqa.github.io/">MedXpertQA</a></li>
<li><a href="https://cdn.openai.com/dd128428-0184-4e25-b155-3a7686c7d744/HealthBench-Professional.pdf">HealthBench Professional: Evaluating Large Language Models on ...</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion shows moderate engagement, with commenters generally agreeing that benchmark scores need careful interpretation and that multiple-choice results should not be conflated with open-ended clinical reasoning. Some note that the lack of scoring detail for HealthBench Professional makes cross-model comparisons premature.

**Tags**: `#medical-ai`, `#benchmarking`, `#evaluation`, `#clinical-reasoning`, `#machine-learning`

---