---
layout: default
title: "Horizon Summary: 2026-11-19 (EN)"
date: 2026-11-19
lang: en
---

> From 24 items, 19 important content pieces were selected

---

1. [Google Releases Gemini 4 Neon Frontier Model](#item-1) ⭐️ 9.0/10
2. [Ruby2ßhell: Pre-auth RCE in stock Rails via single-byte overflow](#item-2) ⭐️ 8.0/10
3. [15 million web servers on one VM using smoltcp, DPDK, and AF_XDP](#item-3) ⭐️ 8.0/10
4. [OpenAI Releases GPT-6.2 Astra and Sol with Lower Pricing](#item-4) ⭐️ 8.0/10
5. [European Commission Deploys Matrix to 40,000+ Staff](#item-5) ⭐️ 7.0/10
6. [Nintendo DMCA Takedown Targets Picofly Switch Modchip Firmware on GitHub](#item-6) ⭐️ 7.0/10
7. [OpenJDK java4shell bug reported via PR, possibly LLM-assisted](#item-7) ⭐️ 7.0/10
8. [Germany and Austria Push for European Control of TikTok](#item-8) ⭐️ 7.0/10
9. [Zerodha builds distributed blob storage on SQLite](#item-9) ⭐️ 7.0/10
10. [Blog Post Explores Teaching Robots to Carve Marble Sculptures](#item-10) ⭐️ 7.0/10
11. [Foolscap: AI writing app that analyzes but never writes for you](#item-11) ⭐️ 7.0/10
12. [Stenberg: AI Rust rewrites can't keep pace with curl's ongoing fixes](#item-12) ⭐️ 7.0/10
13. [Simon Willison and Prime Radiant Introduce External Sandbox Pattern for Coding Agents](#item-13) ⭐️ 7.0/10
14. [Claude Code v2.1.328 adds auto permission mode and hook failure blocking](#item-14) ⭐️ 6.0/10
15. [LastBook.org: A Curated Knowledge Collection for Surviving and Rebuilding Society](#item-15) ⭐️ 6.0/10
16. [PHP 8.6 Released with Performance Gains and New Features](#item-16) ⭐️ 6.0/10
17. [Blog Post Advocates Memory Compression Over Buying More RAM](#item-17) ⭐️ 6.0/10
18. [Blog predicts SSD price drop in second half of next year, sparking debate](#item-18) ⭐️ 6.0/10
19. [datasette-arrows 0.1a0 adds Apache Arrow streaming export to Datasette](#item-19) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Google Releases Gemini 4 Neon Frontier Model](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-neon/) ⭐️ 9.0/10

Google announced Gemini 4 Neon, a new frontier model built for complex coding, analytical reasoning, and production-grade enterprise workflows, adapted from the Gemini Carbon model and offered at a lower cost. The release intensifies competition among frontier AI labs, particularly with Anthropic's Opus 5.5, and expands Google's Gemini 4 lineup with a cost-efficient option that could appeal to enterprises and developers. Gemini 4 Neon is positioned as more intelligent overall than Gemini Carbon on the AA Index but scores lower on research-scale reasoning evaluations like CritPt, and it is engineered for real-world AI coding and agent harnesses including repo-level edits, debugging, refactoring, and secure code.

hackernews · yigitdemirag · Nov 18, 21:34 · [Discussion](https://news.ycombinator.com/item?id=50552424)

**Background**: Gemini is Google's flagship family of large language models, and the Gemini 4 generation includes multiple variants such as Argon, Carbon, and Neon, each optimized for different tasks and cost profiles. Frontier models are the most advanced LLMs from major labs, and they are often compared using benchmarks like the AA Index and CritPt, though real-world performance can differ from benchmark scores.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/opus">Claude Opus \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Commenters debated how Gemini 4 Neon fits within the Gemini fleet, noting that Carbon remains positioned as the 'long horizon' model despite Neon's higher overall scores, and some users argued that Anthropic's Opus 5.5 feels more human-like and generally intelligent than Gemini despite benchmark comparisons. Others highlighted Gemini's strengths in research and analysis tasks due to Google's search index advantage.

**Tags**: `#LLM`, `#Google Gemini`, `#AI models`, `#model benchmarks`, `#AI industry`

---

<a id="item-2"></a>
## [Ruby2ßhell: Pre-auth RCE in stock Rails via single-byte overflow](https://verialabs.com/ruby2shell/) ⭐️ 8.0/10

A pre-authentication remote code execution vulnerability, dubbed Ruby2ßhell, has been reported in stock Ruby on Rails, likely involving a single-byte overflow in string case conversion. The flaw is part of a recent wave of memory-safety bugs in Ruby's interpreter, with patches released in Ruby 4.0.10, 3.4.13, and 3.3.14 on November 18. This is a high-severity vulnerability affecting the widely used Ruby on Rails framework, allowing unauthenticated attackers to execute arbitrary code. It highlights the growing risk of memory-safety flaws in Ruby and the need for rapid patching across the ecosystem. The vulnerability is believed to stem from a single-byte overflow in the ß-to-SS case conversion, which can corrupt memory and potentially lead to RCE. It is covered in a Ruby advisory that addresses six other vulnerabilities, and proof-of-concept code exists for some of the flaws.

hackernews · jdns · Nov 19, 05:09 · [Discussion](https://news.ycombinator.com/item?id=50556287)

**Background**: Ruby on Rails is a popular web application framework written in Ruby, and memory-safety bugs in the Ruby interpreter can have widespread impact. A single-byte overflow occurs when a program writes one byte beyond a buffer boundary, which can corrupt adjacent memory and, under the right conditions, be exploited for remote code execution. The ß character is a German letter that converts to 'SS' in uppercase, and handling such case conversions incorrectly can introduce such overflows.

<details><summary>References</summary>
<ul>
<li><a href="https://dailysecurityreview.com/resources/ruby-patches-seven-memory-safety-flaws-five-with-rce-proof-of-concept/">Ruby Patches Seven Memory-Safety Flaws, Five With RCE Proof ...</a></li>
<li><a href="https://one2bla.me/The-dark-arts/Common-vulnerabilities/single-byte-overflows">Single byte overflows</a></li>

</ul>
</details>

**Discussion**: Commenters note that the recent RCE wave involves single-byte overflows being reported as RCEs because AI can automate finding the rest of the exploit chain, arguing this proves the need for memory-safe software stacks. Some initially confused this with another vulnerability already covered in a Ruby advisory, while others express interest in how a single-byte overflow can trigger RCE and speculate that the ß-to-SS conversion was added without proper testing.

**Tags**: `#security`, `#ruby-on-rails`, `#rce`, `#vulnerability`, `#memory-safety`

---

<a id="item-3"></a>
## [15 million web servers on one VM using smoltcp, DPDK, and AF_XDP](https://kapteko.com/15-million-webservers/) ⭐️ 8.0/10

A technical article demonstrates running 15 million web servers on a single VM with only 10GB RAM and 1 CPU core by combining the smoltcp TCP/IP stack, DPDK, and AF_XDP. The author achieves this extreme density through kernel-bypass networking and a lightweight, event-driven TCP/IP implementation. This pushes the boundaries of server density and resource efficiency, showing how kernel-bypass and user-space networking can dramatically reduce overhead. It is relevant for anyone interested in high-performance networking, cloud infrastructure, or embedded systems where resources are constrained. The setup uses smoltcp, a standalone event-driven TCP/IP stack designed for bare-metal systems, along with DPDK for user-space packet processing and AF_XDP for high-performance packet access. AF_XDP also supports a busy-polling mode (SO_PREFER_BUSY_POLL) that eliminates interrupts at the cost of dedicating a CPU core.

hackernews · fessguid · Nov 19, 05:56 · [Discussion](https://news.ycombinator.com/item?id=50556533)

**Background**: smoltcp is a standalone, event-driven TCP/IP stack written in Rust, designed for bare-metal and real-time systems with no heap requirement. DPDK (Data Plane Development Kit) is an open-source set of libraries and drivers that offload packet processing from the kernel to user space for higher throughput. AF_XDP is a Linux kernel feature (since 4.8) that uses eBPF to bypass most of the networking stack, enabling high-performance packet processing in user space.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/smoltcp-rs/smoltcp">GitHub - smoltcp-rs/smoltcp: a smol tcp/ip stack · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/DPDK">DPDK</a></li>
<li><a href="https://en.wikipedia.org/wiki/AF_XDP">AF XDP</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion is overwhelmingly positive, with commenters praising the article's technical depth, readability, and humor. Many appreciate that it is not AI-generated and evokes the style of 2000s-era blogs, while one notes that the 10GB RAM constraint is even more impressive than the title suggests.

**Tags**: `#networking`, `#DPDK`, `#AF_XDP`, `#smoltcp`, `#performance`

---

<a id="item-4"></a>
## [OpenAI Releases GPT-6.2 Astra and Sol with Lower Pricing](https://simonwillison.net/2026/Nov/17/gpt62-astra-and-sol/) ⭐️ 8.0/10

OpenAI released GPT-6.2 Astra, a new frontier model, and GPT-6.2 Sol, an efficient model for everyday work, available via API as gpt-6.2-astra and gpt-6.2-sol. Simon Willison shipped LLM 0.38 with support for both models. Astra is priced at 80% of its predecessor ($8/$40 per million tokens), and cached input tokens cost just $0.40 per million versus $1 previously, which significantly lowers costs for long-running agentic sessions. This pricing pressure also matches Claude Fable 5.2, signaling intensifying competition among frontier model providers. GPT-6.2 Sol keeps the same $2/$10 pricing as 6.1 Sol and 6 Sol, which is half the price of GPT-5.6 Sol. In Simon Willison's pelican benchmark and a Three.js animation test, Astra produced more detailed outputs at higher effort levels but neither model convincingly morphed Yonkers into a mech compared to Claude Fable 5.2.

rss · Simon Willison · Nov 17, 22:38

**Background**: OpenAI periodically releases new model versions with tiered offerings: a frontier model for complex tasks and an efficient model for everyday use. API pricing is typically quoted per million tokens (MTok), with separate rates for input, output, and cached input tokens; cached tokens are reused context that providers discount heavily. Simon Willison's LLM is a command-line tool and Python library for interacting with various LLM APIs, and its updates often coincide with new model launches.

<details><summary>References</summary>
<ul>
<li><a href="https://developers.openai.com/api/docs/pricing">Pricing | OpenAI API</a></li>

</ul>
</details>

**Tags**: `#openai`, `#llm`, `#model-release`, `#pricing`, `#api`

---

<a id="item-5"></a>
## [European Commission Deploys Matrix to 40,000+ Staff](https://element.io/blog/how-the-european-commission-rolled-out-matrix-to-more-than-40-000-staff/) ⭐️ 7.0/10

The European Commission has rolled out the Matrix decentralized communication protocol to more than 40,000 staff members, as detailed in a blog post by Element, a company that provides Matrix-based collaboration tools. This deployment demonstrates that Matrix can scale to support large governmental organizations, potentially boosting confidence in open-source, decentralized communication solutions for enterprise and public-sector use. The rollout involved disabling live presence (online/away indicators) due to performance load as more users joined, and the deployment has sparked debate about Matrix's end-to-end encryption security and its suitability for national security use cases.

hackernews · liotier · Nov 19, 10:58 · [Discussion](https://news.ycombinator.com/item?id=50558533)

**Background**: Matrix is an open standard for decentralized, end-to-end encrypted communication that allows users to host their own servers (homeservers) while still interoperating with other Matrix servers. Element is a popular client for Matrix, and the protocol is often positioned as a privacy-focused alternative to centralized messaging platforms like WhatsApp and Telegram.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Matrix_(protocol)">Matrix (protocol) - Wikipedia</a></li>
<li><a href="https://matrix.org/docs/matrix-concepts/end-to-end-encryption/">Matrix.org - End-to-End Encryption implementation guide</a></li>
<li><a href="https://selfhostedguides.com/matrix-element-self-hosted-chat/">Self-Hosting Matrix with Element: Decentralized ... — Selfhosted Guides</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed feelings: some praised self-hosted Matrix for privacy and fun, while others criticized its encryption as insecure and complex, with one calling it "a disaster" and another predicting migration away from it. Concerns were raised about the abandonment of MLS work and the disabling of live presence, with some preferring simpler alternatives like IRC.

**Tags**: `#Matrix`, `#decentralized communication`, `#privacy`, `#encryption`, `#open-source`

---

<a id="item-6"></a>
## [Nintendo DMCA Takedown Targets Picofly Switch Modchip Firmware on GitHub](https://www.youtube.com/watch?v=-TLCGUpoD6c) ⭐️ 7.0/10

Nintendo issued a DMCA takedown notice against the Picofly firmware, an open-source modchip firmware for the Nintendo Switch, hosted on GitHub. The notice, which cites only DMCA §1201 (anti-circumvention) and claims no copyrighted code, resulted in the removal of a fork of the repository, while the main repository remains available. This action highlights the growing tension between hardware manufacturers and the modding/right-to-repair community over the scope of anti-circumvention laws. It raises important questions about whether security checks in consoles constitute technological protection measures under the DMCA and sets a precedent for how companies can use takedown notices against clean-room firmware. Picofly is a fully open-source modchip based on the RP2040 microcontroller, and its firmware is a clean-room implementation that contains no Nintendo copyrighted assets. The DMCA notice only targets a fork that included additional materials beyond the firmware, leaving the original repository untouched, which suggests a nuanced enforcement strategy.

hackernews · cowlevel · Nov 18, 14:56 · [Discussion](https://news.ycombinator.com/item?id=50547048)

**Background**: The Digital Millennium Copyright Act (DMCA) has two key provisions: §512, which provides a safe harbor for online platforms and outlines the takedown notice process, and §1201, which prohibits circumvention of technological protection measures (TPMs) like DRM. Modchips such as Picofly are hardware devices that allow running unsigned code on consoles, often used for homebrew applications but also for piracy. Nintendo has a long history of aggressively protecting its intellectual property, including against modding and piracy.

<details><summary>References</summary>
<ul>
<li><a href="https://switch.hacks.guide/user_guide/modchip/">Introduction to Modchips | NH Switch Guide</a></li>
<li><a href="https://news.ycombinator.com/item?id=50547048">Nintendo takes Picofly firmware down from GitHub... | Hacker News</a></li>

</ul>
</details>

**Discussion**: Commenters debated whether console security checks qualify as TPMs under the DMCA, with some arguing that Picofly is clean-room firmware and thus not infringing. Others pointed out a potential legal flaw: Nintendo cited §1201 in a takedown notice, but DMCA takedowns are a mechanism of §512, raising questions about the notice's validity. The discussion also touched on the resilience of open-source hosting, with mentions of alternatives like Radicle and observations that the main repository remains online.

**Tags**: `#DMCA`, `#Nintendo`, `#modding`, `#open-source`, `#right-to-repair`

---

<a id="item-7"></a>
## [OpenJDK java4shell bug reported via PR, possibly LLM-assisted](https://github.com/openjdk/jdk/pull/32781) ⭐️ 7.0/10

A critical java4shell vulnerability in OpenJDK was reported via a GitHub pull request, with discussion suggesting an LLM may have assisted in its discovery, and Oracle later took over the issue. This highlights the growing role of AI in vulnerability discovery and raises questions about the reliability and originality of LLM-assisted security research, while also underscoring the importance of proper vulnerability disclosure processes. The vulnerability, tracked as CVE-2026-114938, is a memory corruption issue in OpenJDK's Base64 decoder that can lead to remote code execution, with a CVSS 4.0 score of 9.2; the PR author noted Oracle asked them to halt the PR until approval, and later took over the issue.

hackernews · notmine1337 · Nov 19, 11:47 · [Discussion](https://news.ycombinator.com/item?id=50558906)

**Background**: OpenJDK is the open-source implementation of Java, and vulnerabilities in it can affect many Java applications. The java4shell vulnerability is a critical flaw that allows attackers to execute arbitrary code remotely. LLM-assisted vulnerability discovery is an emerging practice where large language models help identify security flaws in code.

<details><summary>References</summary>
<ul>
<li><a href="https://www.phoronix.com/news/Java4Shell-Vulnerability">Java 4 Shell Vulnerability For OpenJDK Java That Can... - Phoronix</a></li>
<li><a href="https://www.tenable.com/blog/java4shell-cve-2026-114938-frequently-asked-questions-about-openjdk-rce-vulnerability">Java 4 Shell (CVE-2026-114938): OpenJDK RCE Vulnerability FAQ</a></li>
<li><a href="https://www.sentinelone.com/blog/java4shell-vulnerability-in-openjdk-enables-rce-on-avx-512-cpus/">Defending Against Java 4 Shell : Vulnerability in OpenJDK Enables...</a></li>

</ul>
</details>

**Discussion**: Commenters debated whether the LLM independently discovered the bug or had seen prior reports, with some noting that understanding criticality and exploitation still requires human supervision. Others criticized auto-close bots for prematurely closing the PR, emphasizing the need for human review.

**Tags**: `#security`, `#OpenJDK`, `#LLM`, `#vulnerability`, `#AI-assisted-research`

---

<a id="item-8"></a>
## [Germany and Austria Push for European Control of TikTok](https://www.techcentral.ie/germany-and-austria-call-for-european-control-of-tiktok/) ⭐️ 7.0/10

Germany and Austria are calling for European-level control over TikTok, arguing that the platform's algorithm and content moderation should be governed by EU authorities rather than a foreign company. The proposal has sparked debate on media consolidation, algorithmic transparency, and geopolitical tech regulation. This push reflects growing European momentum to regulate foreign-owned platforms and could set a precedent for how the EU asserts digital sovereignty over social media algorithms. It affects not only TikTok but also other platforms like Instagram and Facebook, and may influence global tech policy. The proposal raises questions about whether control should be exercised through local democratic governments or EU-level bodies, and how to define 'local' algorithms based on geographic or social boundaries. Critics note that data brokers with Chinese ownership also pose risks, suggesting broader user tracking regulation is needed.

hackernews · thm · Nov 19, 14:44 · [Discussion](https://news.ycombinator.com/item?id=50560795)

**Background**: TikTok is owned by Chinese company ByteDance, which has raised national security concerns in the US and Europe over potential data access and algorithmic influence. The EU's Digital Services Act (DSA), in force since 2022, already imposes transparency and content moderation obligations on large platforms, but this proposal goes further by seeking direct European control. The US has similarly pressured TikTok to divest from ByteDance, setting a global precedent for regulating foreign-owned tech platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Digital_Services_Act">Digital Services Act - Wikipedia</a></li>
<li><a href="https://www.atlanticcouncil.org/dispatches/tiktoks-new-ownership-structure-doesnt-solve-security-concerns-for-americans/">TikTok’s new ownership structure doesn’t solve security ...</a></li>

</ul>
</details>

**Discussion**: Commenters largely support the idea of preventing any single entity from controlling large fractions of media feeds, with some arguing that local democratic control is preferable to corporate or foreign control. Others note that the US set a precedent with TikTok and that the EU should apply similar scrutiny to Instagram and Facebook, while some point out that data brokers and broader user tracking need to be addressed.

**Tags**: `#TikTok`, `#EU regulation`, `#social media`, `#algorithmic control`, `#tech policy`

---

<a id="item-9"></a>
## [Zerodha builds distributed blob storage on SQLite](https://zerodha.tech/blog/high-performance-distributed-blob-storage/) ⭐️ 7.0/10

Zerodha published a blog post detailing Blobasaur, a sharded, distributed blob storage server built on SQLite, which increased write throughput from 7,700 to 25,300 operations per second by replacing one database with 16 shards. The system now stores user preference blobs for Zerodha's Kite trading platform, replacing the previous SSDB storage. This case study demonstrates that SQLite, traditionally seen as a lightweight embedded database, can be tuned for high-throughput distributed blob storage when sharded and optimized, offering a simpler alternative to complex distributed databases for specific workloads. It provides a real-world example of architectural trade-offs and performance tuning that could influence how other teams design storage systems. The blog notes that SQLite is faster than direct filesystem I/O for blobs under ~100 KiB, which covers 99% of their compressed values, but raw files start to outperform SQLite above that threshold. The system uses sharding across 16 SQLite databases to achieve the throughput gains, and the post also mentions that deleting rows does not shrink SQLite files, a common RDBMS behavior.

hackernews · ghostfoxgod · Nov 19, 08:39 · [Discussion](https://news.ycombinator.com/item?id=50557537)

**Background**: SQLite is a widely deployed embedded relational database that stores data in a single file and is known for its simplicity and reliability. Blob storage refers to storing large binary objects such as images, JSON documents, or user preferences. Zerodha is an Indian online brokerage platform that operates Kite, a trading platform, and needed a high-throughput storage solution for user preference blobs. The blog post describes how they evaluated alternatives like YugabyteDB and RocksDB before choosing SQLite and building a distributed layer on top.

<details><summary>References</summary>
<ul>
<li><a href="https://zerodha.tech/blog/high-performance-distributed-blob-storage/">Distributed, high-performance blob storage on... - Zerodha Tech Blog</a></li>
<li><a href="https://sqlite.org/fasterthanfs.html">35% Faster Than The Filesystem - SQLite The SQLite Renaissance: Building High-Performance Blob Stores Optimizing SQLite BLOB Storage: Internal vs. External ... database performance - Storage-optimizing sqlite blob to act ... SQLite BLOB: Store Binary Data, Images and Files (Tested ... What are the performance characteristics of sqlite with very ...</a></li>
<li><a href="https://sqlite.org/intern-v-extern-blob.html">Internal Versus External BLOBs - SQLite</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism about using SQLite for this use case, with one noting that years of trying led to 'tears' and recommending an alternative like possum, while another pointed out that the blog's observation about deleting rows not shrinking files is true of every RDBMS and should be apparent from first principles. Others asked whether other databases were tried with application-side compression and suggested using a graph layer or noted that OpenStack Swift uses SQLite for metadata but scales poorly compared to Ceph.

**Tags**: `#SQLite`, `#blob storage`, `#distributed systems`, `#database`, `#performance`

---

<a id="item-10"></a>
## [Blog Post Explores Teaching Robots to Carve Marble Sculptures](https://eleanorwiesler.com/blog/robotic-stone-carving/) ⭐️ 7.0/10

A blog post by Eleanor Wiesler describes a project in which robots were taught to carve marble sculptures, detailing the technical process and sparking a Hacker News discussion with 73 comments. This work highlights the growing intersection of robotics and art, showing how automation can be applied to traditional crafts like stone carving, which could impact artists, conservators, and the manufacturing of ornamental architecture. The discussion notes that the carved model was based on a scan of a ceramic rabbit lacking the crisp detail of master marble sculptures, and that natural marble's veins and imperfections require experienced carvers to adapt designs during carving—a challenge for robotic automation.

hackernews · ewiesler · Nov 18, 17:03 · [Discussion](https://news.ycombinator.com/item?id=50548808)

**Background**: Robotic stone carving typically uses industrial robot arms equipped with milling tools, guided by CAD/CAM software to remove material from stone blocks. While CNC and robotic milling are common in manufacturing, applying them to fine art sculpture raises questions about artistic authorship, material responsiveness, and the value of human craft.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Marble_sculpture">Marble sculpture - Wikipedia</a></li>
<li><a href="https://www.academia.edu/67040723/Adaptive_robotic_stone_carving_Method_tools_and_experiments">Adaptive robotic stone carving : Method, tools, and experiments</a></li>

</ul>
</details>

**Discussion**: Commenters debated the artistic merit of robotic carving, with some arguing the output is 'cold and sterile' and lacks a human soul, while others saw potential for architectural ornamentation and noted that marble's natural imperfections require a master's judgment that robots cannot easily replicate.

**Tags**: `#robotics`, `#art`, `#automation`, `#manufacturing`, `#HN discussion`

---

<a id="item-11"></a>
## [Foolscap: AI writing app that analyzes but never writes for you](https://foolscap.works/) ⭐️ 7.0/10

David launched Foolscap, a writing app that uses AI to read and analyze a book's structure, characters, and threads, and provides a conversational agent for queries, but never writes content for the author. It is available with a free tier and a 50% discount code via email. This tool takes a contrarian approach to AI writing assistants by enhancing rather than replacing human creativity, addressing concerns about skill atrophy and privacy. It sparks discussion on the ethical role of AI in creative work and the need for privacy safeguards. Foolscap reads as you write and picks out structure, allowing a dialectic between system and writer; it also has an agent for conversational actions but never writes into the work. The system can follow theorems and proofs but lacks Lean support, and the creator invites interest in that area.

hackernews · atugard · Nov 19, 13:21 · [Discussion](https://news.ycombinator.com/item?id=50559749)

**Background**: AI writing tools like ChatGPT and Sudowrite often generate text for authors, raising concerns about originality and skill loss. Foolscap instead focuses on analysis and organization, similar to how a writing coach or editor might help. The Lean theorem prover is a proof assistant for formal verification, which Foolscap could potentially integrate for mathematical writing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lean_theorem_prover">Lean theorem prover</a></li>
<li><a href="https://foolscap.app/">Foolscap</a></li>

</ul>
</details>

**Discussion**: Commenters appreciate the tool's focus on organization without replacing creativity, but raise concerns about privacy and data retention, especially for authors writing sensitive content. Others request more detailed demonstration videos and suggest highlighting privacy features on the homepage.

**Tags**: `#AI`, `#writing`, `#creativity`, `#privacy`, `#Show HN`

---

<a id="item-12"></a>
## [Stenberg: AI Rust rewrites can't keep pace with curl's ongoing fixes](https://simonwillison.net/2026/Nov/18/daniel-stenberg/) ⭐️ 7.0/10

Daniel Stenberg reported that while AI agents converted 185,000 lines of C into 340,000 lines of Rust over about three weeks, the real curl project merged over 300 commits and fixed more than 200 bugs in the same period, plus a few vulnerabilities. This highlights a key limitation of AI-driven code translation: a static Rust clone immediately falls behind the continuously evolving upstream, missing bug fixes and security patches, which matters for maintainers and users evaluating such rewrites. The Rust rewrite grew to 340,000 lines from 185,000 lines of C, and Stenberg questions whether these clones will keep up as curl continues to merge hundreds of commits and fix vulnerabilities each month.

rss · Simon Willison · Nov 18, 15:58

**Background**: curl is a widely used command-line tool and library (libcurl) for transferring data, created by Daniel Stenberg, who remains lead developer. There is growing interest in rewriting C code in Rust to eliminate memory-safety vulnerabilities, and AI agents are increasingly used to automate such translations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CURL">cURL - Wikipedia</a></li>
<li><a href="https://github.com/curl/curl">GitHub - curl/curl: A command line tool and library for ... curl curl on Windows | Microsoft Learn curl - How To Use Command-line Tool | curl/curl | DeepWiki Code layout - everything curl</a></li>
<li><a href="https://bughunters.google.com/blog/scaling-memory-safety">Scaling Memory Safety: AI-Assisted Rewrites of C/C++ ...</a></li>

</ul>
</details>

**Tags**: `#curl`, `#rust`, `#ai-agents`, `#open-source`, `#security`

---

<a id="item-13"></a>
## [Simon Willison and Prime Radiant Introduce External Sandbox Pattern for Coding Agents](https://simonwillison.net/2026/Nov/17/external-sandboxes-for-coding-agents/) ⭐️ 7.0/10

Simon Willison and Prime Radiant released three open-source sandbox server implementations that demonstrate the 'external sandbox' pattern, where agent-executed code runs in a dedicated sandbox separate from the agent itself. The implementations include external-sandbox-v86 (Node.js with v86 running Alpine Linux in WebAssembly), external-sandbox-container (Python with Apple Containers), and external-sandbox-quicksand (Python with Microsoft's Quicksand bundling QEMU and Alpine Linux). This pattern addresses a critical safety gap in AI coding agents: by isolating code execution from the agent's environment, it reduces the risk of prompt injection attacks or agent mistakes causing damage to the host machine. The shared localhost API and compatibility with tools like Pi, Claude Code, and Codex make it a practical contribution that could influence how developers safely experiment with local models. Each sandbox server exposes the same localhost API, allowing coding agents to send execution requests, and includes an optional HTTP/HTTPS allow-list proxy with a credential replacement mechanism so agents can make authenticated API calls without accessing secrets. The proxy can be reconfigured at runtime through a web UI, giving fine-grained control over network access.

rss · Simon Willison · Nov 17, 22:52

**Background**: Coding agents like Claude Code and Codex can execute arbitrary code and shell commands, which creates security risks if the agent is compromised via prompt injection—a technique where malicious instructions are hidden in content the agent processes. Sandboxing isolates untrusted code in a restricted environment to prevent it from affecting the host system. The external sandbox pattern specifically separates the agent from the execution environment, unlike traditional sandboxes that run alongside the agent.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.primeradiant.com/external-sandboxes-for-coding-agents/">External sandboxes for coding agents</a></li>
<li><a href="https://simonwillison.net/2026/Nov/17/external-sandboxes-for-coding-agents/">External sandboxes for coding agents - simonwillison.net</a></li>
<li><a href="https://www.obsidiansecurity.com/blog/prompt-injection">Prompt Injection Attacks on AI Agents : How to Detect and Prevent...</a></li>

</ul>
</details>

**Tags**: `#ai-agents`, `#sandboxing`, `#security`, `#llm-safety`, `#developer-tools`

---

<a id="item-14"></a>
## [Claude Code v2.1.328 adds auto permission mode and hook failure blocking](https://github.com/anthropics/claude-code/releases/tag/v2.1.328) ⭐️ 6.0/10

Anthropic released Claude Code v2.1.328, which introduces an auto permission mode for Claude Opus 4.6 and Sonnet 4.6 across Amazon Bedrock, Google Cloud's Agent Platform, Microsoft Foundry, and the Claude apps gateway, with interactive sessions that have no permission mode starting in it. The release also adds an "onFailure": "block" option for mcp_tool hooks, warnings for missing OpenTelemetry endpoints and dropped cloud-session messages, and a CLAUDE_CODE_DISABLE_DEFERRED_TOOL_RESUME environment variable. The auto permission mode lowers friction for developers using Claude Code on major cloud platforms by removing the need to manually configure permission modes in interactive sessions. The hook failure blocking option strengthens security and reliability for teams that rely on hooks as guardrails, since a failing hook can now stop a tool call instead of silently allowing it. The "onFailure": "block" setting for mcp_tool hooks mirrors existing support for command and HTTP hooks, meaning a hook that crashes, times out, or returns invalid JSON will block the action. The release also includes numerous bug fixes, such as zsh commands failing at words starting with '=', markdown rendering freezes on malformed input, and token counts double-counting retried replies.

github · claude-code-publisher[bot] · Nov 19, 01:14

**Background**: Claude Code is Anthropic's agentic coding tool that runs in the terminal and can execute commands, edit files, and call tools on the user's behalf. Hooks are user-defined commands that run at specific points in the Claude Code lifecycle, such as before or after a tool call, and can be used to enforce policies or add guardrails. Permission modes control how much autonomy Claude Code has when performing actions, and auto mode is a newer option that balances automation with safety.

<details><summary>References</summary>
<ul>
<li><a href="https://startdebugging.net/2026/10/how-to-make-a-claude-code-hook-fail-closed-with-onfailure-block/">How to Make a Claude Code Hook Fail Closed with onFailure : " block "</a></li>
<li><a href="https://castel.studio/blog/claude-code-hooks/">Claude Code hooks : examples that block , with tests</a></li>
<li><a href="https://opentelemetry.io/docs/languages/js/exporters/">Exporters | OpenTelemetry</a></li>

</ul>
</details>

**Tags**: `#claude-code`, `#release`, `#ai-tools`, `#developer-tools`, `#anthropic`

---

<a id="item-15"></a>
## [LastBook.org: A Curated Knowledge Collection for Surviving and Rebuilding Society](https://lastbook.org/) ⭐️ 6.0/10

A website called LastBook.org has been launched, offering a curated collection of knowledge intended to help people survive and rebuild society after a collapse. The project was discussed on Hacker News, where commenters raised practical concerns about its accessibility and power requirements. This project reflects a growing interest in knowledge preservation and community resilience, especially among technologists who worry about societal collapse. It also highlights the tension between idealistic survivalist goals and practical constraints like power availability and device compatibility. Commenters noted that the site does not offer PDF downloads, lacks a mobile version, and seems designed for desktop use, which is problematic because phones are easier to power in emergencies than laptops. The site's content is not listed anywhere, making it hard to assess what knowledge is included.

hackernews · tejohnso · Nov 19, 14:47 · [Discussion](https://news.ycombinator.com/item?id=50560822)

**Background**: Knowledge preservation for survival involves documenting critical skills and information that could be lost in a societal collapse, similar to how technologies like Roman concrete were lost after the fall of Rome. Projects like Open Source Ecology and Project NOMAD aim to make tools and knowledge accessible for rebuilding civilization, often leveraging open-source principles. LastBook.org appears to be a curated digital library for such scenarios, but its design choices have sparked debate about practicality.

<details><summary>References</summary>
<ul>
<li><a href="https://civilizationrebuild.com/phase-2-first-year/education/knowledge-preservation">Knowledge Preservation | Survival Wiki</a></li>
<li><a href="https://github.com/rebuildcivilization/rebuild-civilization">GitHub - rebuildcivilization/rebuild-civilization: Rebuild ...</a></li>

</ul>
</details>

**Discussion**: Commenters criticized the lack of PDF downloads and mobile support, arguing that eInk devices and phones are more practical in emergencies due to lower power needs. Others mentioned related projects like Open Source Ecology and Project NOMAD, and some suggested using a Kiwix server for offline access. Overall, the sentiment was that the concept is interesting but the implementation has significant accessibility flaws.

**Tags**: `#survival`, `#knowledge-preservation`, `#open-source`, `#community`, `#resilience`

---

<a id="item-16"></a>
## [PHP 8.6 Released with Performance Gains and New Features](https://www.php.net/releases/8.6/en.php) ⭐️ 6.0/10

PHP 8.6 has been released, introducing new features such as partial function application, a Duration class, a Polling API, and a clamp() function, along with performance improvements including reduced overhead in ZTS (Zend Thread Safety) mode. This release matters because the reduced ZTS overhead could pave the way for native async support in PHP, and the new features like partial function application improve developer productivity. Additionally, a security advisory affecting PHP 8.5+ makes upgrading urgent for users on newer versions. The ZTS overhead reduction is a key performance improvement that may lead to PHP only needing ZTS mode in the future, and there is a security vulnerability (GHSA-8mjj and GHSA-2fjv) affecting PHP 8.5 and above, so users on those versions should upgrade immediately.

hackernews · netol · Nov 19, 09:27 · [Discussion](https://news.ycombinator.com/item?id=50557870)

**Background**: PHP is a widely-used server-side scripting language. ZTS (Zend Thread Safety) is a mode that allows PHP to run in multithreaded environments, but it historically incurs performance overhead. PHP releases are typically made annually with new features and improvements, and security advisories are issued for vulnerabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://www.php.net/releases/8.6/en.php">PHP : PHP 8 . 6 Release Announcement</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement about the ZTS overhead reduction and its potential to enable native async support, while also noting the security vulnerability affecting PHP 8.5+ and the need to upgrade. Some users lamented the lack of a way to limit function arguments in the type system, and others shared their upgrade experiences.

**Tags**: `#PHP`, `#release`, `#security`, `#performance`, `#async`

---

<a id="item-17"></a>
## [Blog Post Advocates Memory Compression Over Buying More RAM](https://curiousbits.nl/blog/do-not-buy-ram-compress/) ⭐️ 6.0/10

A blog post on curiousbits.nl argues that users should compress RAM rather than buy more, sparking a Hacker News discussion with 99 comments about zswap vs zram and the limits of compression for machine learning workloads. Memory compression is a built-in feature of macOS and Windows that can significantly reduce memory pressure without hardware upgrades, yet many Linux distributions still require manual configuration, so raising awareness can help users save money and improve performance. Community members note that zswap is generally preferred over zram when a disk swap device exists, and that the compression algorithm (e.g., zstd vs lz4) varies by distribution and should be chosen carefully; compression offers little benefit for already-compressed data like ML models.

hackernews · Ecno92 · Nov 19, 08:56 · [Discussion](https://news.ycombinator.com/item?id=50557661)

**Background**: zram is a Linux kernel module that creates a compressed block device in RAM, often used as a swap space. zswap is a compressed cache in front of a real swap device, storing compressed pages in RAM and evicting less-used pages to disk. macOS has enabled memory compression by default since OS X Mavericks 10.9 in 2013, and Windows also uses similar techniques.

<details><summary>References</summary>
<ul>
<li><a href="https://linuxblog.io/zswap-better-than-zram/">I was wrong! zswap IS better than zram - LinuxBlog.io</a></li>
<li><a href="https://www.baeldung.com/linux/zram-zswap-zcache-comparison">Comparing Zram, Zswap , and Zcache: Choosing... | Baeldung on Linux</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zram">zram - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree that memory compression is effective, with one sharing a real-world example of a leaking daemon compressed from 2.5GB to 450MB. Many recommend zswap over zram for systems with disk swap, and some question the benefit for local ML inference since models are already compressed.

**Tags**: `#memory-compression`, `#linux`, `#zram`, `#zswap`, `#systems`

---

<a id="item-18"></a>
## [Blog predicts SSD price drop in second half of next year, sparking debate](https://www.drivevault.io/blog/when-will-hard-drive-prices-come-down.html) ⭐️ 6.0/10

A blog post on DriveVault.io predicts that SSD prices will begin to decline in the second half of next year, citing expected improvements in NAND supply. The post sparked a lively Hacker News discussion with 189 comments debating whether AI datacenter demand will keep memory prices elevated. SSD pricing affects everything from consumer electronics to enterprise storage costs, and the current AI-driven memory boom has pushed prices up sharply, so any forecast of a downturn is significant for buyers and manufacturers. The debate highlights uncertainty over whether AI infrastructure spending can sustain current demand levels. The prediction is largely speculative, with no hard data on when or by how much prices might fall. Community members point to conflicting signals: memory makers like Micron and SK Hynix trade at low P/E ratios despite explosive growth, suggesting the market expects a profit collapse, while new technologies like High Bandwidth Flash could add NAND demand in the late 2020s.

hackernews · illidan1000 · Nov 19, 09:05 · [Discussion](https://news.ycombinator.com/item?id=50557716)

**Background**: SSD prices are driven by NAND flash memory supply and demand, which has historically been cyclical with boom-and-bust periods. The recent surge in memory prices is attributed to AI datacenter buildouts consuming large amounts of DRAM and NAND, tightening supply for consumer markets. High Bandwidth Flash (HBF) is an emerging technology that stacks NAND flash like HBM to provide cheaper, high-capacity memory for AI inference workloads.

<details><summary>References</summary>
<ul>
<li><a href="https://storagediskprices.com/ssd-price-history/">SSD Price Tracker : 2020-2026 Price History Chart & Forecast</a></li>
<li><a href="https://datacenterdisk.com/trends/ssd">SSD Prices : Live Price History Tracker & Forecast</a></li>
<li><a href="https://cloudzat.com/ssd-prices-2020-2026-price-history-and-2026-forecast/">SSD Prices : SSD Tracker, Trends, History and 2026 Forecast</a></li>

</ul>
</details>

**Discussion**: Commenters are divided: some note that low valuations for memory makers like Micron and SK Hynix suggest the market expects a profit collapse, while others argue that AI demand could keep prices high or that a demand drop is possible if datacenter buildouts stall. Several mention High Bandwidth Flash as a potential new NAND demand driver by 2027-2028, and some hope for broader price declines in RAM and GPUs.

**Tags**: `#hardware`, `#storage`, `#memory-pricing`, `#ai-infrastructure`, `#market-analysis`

---

<a id="item-19"></a>
## [datasette-arrows 0.1a0 adds Apache Arrow streaming export to Datasette](https://simonwillison.net/2026/Nov/18/datasette-arrows/) ⭐️ 6.0/10

Simon Willison released datasette-arrows 0.1a0, an alpha plugin that implements Apache Arrow streaming export using Datasette's new register_output_renderer streaming hook introduced in Datasette 1.0a43. The plugin was built almost in a single shot by Claude Fable 5.2 and adds an Arrow option to the export dialog, allowing users to download all rows as an Apache Arrow IPC stream. This plugin demonstrates how Datasette's new streaming export hook can be used to support additional formats beyond CSV and TSV, enabling memory-efficient export of large datasets. It matters for data analysts and developers who want to move data from Datasette into tools like DuckDB, pandas, or Polars without loading entire tables into memory. The plugin is an alpha release (0.1a0) and the screenshot showing Arrow grouped with CSV and TSV in the export dialog is from Datasette's main branch; the most recent release does not yet group streaming formats together, but that is planned for the next alpha. The Arrow IPC stream format is designed for zero-copy, memory-mapped data and is compatible with DuckDB, pandas, Polars, and other tools.

rss · Simon Willison · Nov 18, 17:09

**Background**: Datasette is an open-source tool for exploring and publishing data, built by Simon Willison. Apache Arrow is a cross-language development platform for in-memory columnar data, and its IPC streaming format allows serializing data in chunks without loading everything into memory. Datasette 1.0a43 introduced the ability for plugins to implement streaming export formats via the register_output_renderer hook, which previously only supported non-streaming output.

<details><summary>References</summary>
<ul>
<li><a href="https://arrow.apache.org/docs/python/ipc.html">Streaming, Serialization, and IPC — Apache Arrow v26.0.1</a></li>
<li><a href="https://docs.datasette.io/en/stable/plugin_hooks.html">Plugin hooks - Datasette documentation</a></li>
<li><a href="https://simonwillison.net/">Simon Willison’s Weblog</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#apache-arrow`, `#streaming`, `#plugin`, `#data-export`

---