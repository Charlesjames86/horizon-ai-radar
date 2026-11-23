---
layout: default
title: "Horizon Summary: 2026-11-23 (EN)"
date: 2026-11-23
lang: en
---

> From 19 items, 17 important content pieces were selected

---

1. [Nvidia Board Reinstates Jensen Huang as CEO After Government Input](#item-1) ⭐️ 9.0/10
2. [Ladybird, the independent browser engine, enters alpha](#item-2) ⭐️ 9.0/10
3. [Zhipu AI Releases GLM-5.4, Its First Loop Transformer](#item-3) ⭐️ 9.0/10
4. [XNU Linux runs full OS X GUI userspace on Linux](#item-4) ⭐️ 8.0/10
5. [GTA 6 Xbox Build Leak Sparks Public Reverse-Engineering Effort](#item-5) ⭐️ 8.0/10
6. [17M-line Lean formalization of GRH sparks debate on proof comprehensibility](#item-6) ⭐️ 8.0/10
7. [ARM Forces Shutdown of Community Documentation Site](#item-7) ⭐️ 7.0/10
8. [Nospeaker makes MacBook trackpad speak via haptic motor](#item-8) ⭐️ 7.0/10
9. [Spelunkr.tv Turns Internet Archive Videos into Linear TV Channels](#item-9) ⭐️ 7.0/10
10. [Apple removes open-source app FSNotes from EU App Stores after nine years](#item-10) ⭐️ 7.0/10
11. [Gentoo Developer Reflects on the 'Circle of Security Hell' Facing Open Source](#item-11) ⭐️ 7.0/10
12. [Blog post argues against storing SSH keys on disk](#item-12) ⭐️ 7.0/10
13. [Muru: AI-assisted Rust server for ASGI/WSGI Python apps](#item-13) ⭐️ 7.0/10
14. [Kagi Launches Privacy-Focused Email Service in Public Beta](#item-14) ⭐️ 6.0/10
15. [LeCun Accuses Amodei of Hyping AI Risks to Ban Open Models](#item-15) ⭐️ 6.0/10
16. [Win4wine runs Windows XP Explorer as a Linux desktop shell on Wine](#item-16) ⭐️ 6.0/10
17. [Beginner's Guide to Local AI with Inkling, Qwen, and Unsloth](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Nvidia Board Reinstates Jensen Huang as CEO After Government Input](https://www.cnbc.com/2026/11/23/nvidia-jensen-huang-ceo.html) ⭐️ 9.0/10

Nvidia's board of directors reinstated Jensen Huang as President, CEO, and board director, according to an official Nvidia news release. The board stated it received input from senior levels of the U.S. government and concluded that Huang's reinstatement poses no national security risk. This event raises fundamental questions about corporate governance at one of the world's most valuable technology companies, particularly whether board authority is real or nominal when external forces such as the government intervene. It could set a precedent for how political influence shapes leadership decisions in the tech industry. The board's statement explicitly mentions input from senior U.S. government levels and confirmation from the Attorney General that Huang's return poses no national security risk. Community discussion highlights parallels to the 2023 OpenAI board crisis, where nominal governance was overridden by other forces.

hackernews · jaz · Nov 23, 14:00 · [Discussion](https://news.ycombinator.com/item?id=50611576)

**Background**: Corporate governance refers to the mechanisms and processes by which corporations are controlled and operated by their boards, managers, and shareholders. Nvidia, founded in 1993 by Jensen Huang and others, is a leading AI computing company whose GPUs power everything from gaming to supercomputing. The news suggests a unusual situation where a CEO was removed and then reinstated with government involvement, echoing governance debates in the tech industry.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Corporate_governance">Corporate governance - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Nvidia">Nvidia - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters drew parallels to the 2023 OpenAI saga, arguing that a firm's nominal governance structure may not reflect its real governance. Some highlighted the government's role as the operative part of the statement, while others debated whether Nvidia committed wrongdoing or whether the government overstepped.

**Tags**: `#nvidia`, `#corporate-governance`, `#jensen-huang`, `#tech-industry`, `#leadership`

---

<a id="item-2"></a>
## [Ladybird, the independent browser engine, enters alpha](https://ladybird.org/posts/alpha/) ⭐️ 9.0/10

Ladybird, a web browser engine built from scratch, has released its first alpha version for macOS and Linux, as announced on its official website. The release has sparked extensive testing and discussion on Hacker News, with users reporting that many websites render correctly. This is a significant milestone because it introduces a new browser engine independent of Google's Chromium and other major vendors, potentially increasing competition and diversity in the browser market. It offers an alternative free from corporate conflicts of interest, which could benefit web standards and user privacy. The alpha version is currently available for macOS and Linux, with a stable release planned for 2026. Ladybird uses a multi-process architecture where each tab runs in a separate process, which can increase overall memory usage but improves stability and security.

hackernews · janvdberg · Nov 23, 16:13 · [Discussion](https://news.ycombinator.com/item?id=50614249)

**Background**: Ladybird originated as a component of the SerenityOS project, a hobby operating system, before becoming an independent browser engine. It is developed by the Ladybird Browser Initiative, a non-profit organization funded entirely through donations from sponsors such as Cloudflare, FUTO, Shopify, Proton, and 37signals. The project aims to build a truly independent web browser engine from scratch, free from the influence of major tech companies.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ladybird_(web_browser)">Ladybird (web browser ) - Wikipedia</a></li>
<li><a href="https://ladybird.org/">Ladybird</a></li>

</ul>
</details>

**Discussion**: Community response has been overwhelmingly positive, with users praising the browser's ability to render most websites correctly and congratulating the team. Some noted minor issues like jerky scrolling and discussed the trade-offs of using production-grade libraries like SQLite and Skia instead of self-developed ones. Others raised security concerns about using an alpha browser for sensitive activities and highlighted the multi-process architecture's impact on RAM usage.

**Tags**: `#browser-engine`, `#ladybird`, `#open-source`, `#web-standards`, `#software-release`

---

<a id="item-3"></a>
## [Zhipu AI Releases GLM-5.4, Its First Loop Transformer](https://z.ai/blog/glm-5.4) ⭐️ 9.0/10

Zhipu AI has released GLM-5.4, its first model built on a loop transformer architecture that reuses weights across iterations to reduce memory bandwidth bottlenecks during inference. The release includes detailed technical documentation and is available through Zhipu's Coding Plan API. This release is significant because loop transformers address a fundamental inference bottleneck—memory bandwidth—by reusing weights across iterations, potentially enabling more efficient LLM serving. It also highlights a transparency gap, as Zhipu provides detailed technical insights while Western labs often keep such details proprietary. The loop transformer architecture applies a fixed transformer block repeatedly, reusing weights to mimic deeper networks without increasing parameter count. However, community members note that GLM-5.4 is not yet available via OpenRouter or the regular Z.ai API plan, requiring a switch to the Coding Plan, and some users report slow 'marathon thinking' sessions.

hackernews · foohis · Nov 23, 10:06 · [Discussion](https://news.ycombinator.com/item?id=50609685)

**Background**: Loop transformers are a parameter-efficient design that repeatedly applies the same transformer block to achieve the depth and reasoning capabilities of deeper networks. Traditional LLM inference is often memory-bound because each layer's weights must be moved from high-bandwidth memory (HBM) to the chip for computation, and this data movement is a major bottleneck. By reusing weights across iterations, loop transformers can reduce the amount of data movement required per token generated.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/looped-transformer-architecture">Looped Transformer Architecture</a></li>
<li><a href="https://blog.logrocket.com/gpt-vs-looping-transformers/">Traditional GPT vs. looping Transformers : Key... - LogRocket Blog</a></li>
<li><a href="https://www.yottalabs.ai/post/why-llm-inference-has-low-gpu-utilization-cpu-pcie-memory-bandwidth-and-kv-cache-bottlenecks">Why LLM Inference Has Low GPU Utilization: CPU, PCIe, Memory ...</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion was largely positive, with commenters praising Zhipu's transparency and technical detail compared to Western labs. One commenter explained how loop transformers optimize the memory bandwidth bottleneck by reusing weights, while another noted practical issues like model availability and slow 'marathon thinking' sessions.

**Tags**: `#LLM`, `#loop-transformer`, `#model-release`, `#inference-optimization`, `#open-weights`

---

<a id="item-4"></a>
## [XNU Linux runs full OS X GUI userspace on Linux](https://github.com/AFK-surf/xnulinux) ⭐️ 8.0/10

A GitHub project called XNU Linux demonstrates running the full OS X GUI userspace on Linux by adapting Apple's open-source XNU kernel components as a loadable Linux kernel module. The project has sparked significant discussion on Hacker News, garnering 557 points and 233 comments. This project pushes the boundaries of OS portability by allowing macOS applications to run on Linux without a full virtual machine, which could benefit developers and users who rely on macOS-specific software. It also highlights the technical feasibility of running proprietary userspaces on open-source kernels, raising questions about software licensing and hardware lock-in. The approach leverages the fact that macOS, unlike Linux, does not have a stable syscall interface; instead, applications dynamically link to system libraries that change in lockstep with the kernel. By providing these libraries and a compatible XNU-based environment as a Linux module, the project can run macOS binaries with little to no kernel modification. However, it still requires Apple hardware for legal and technical reasons, as noted by community members.

hackernews · mmastrac · Nov 23, 03:49 · [Discussion](https://news.ycombinator.com/item?id=50607261)

**Background**: XNU is the hybrid kernel used by Apple's macOS and iOS, combining the Mach microkernel with components from BSD and I/O Kit. GNUstep is a free software implementation of the Cocoa (formerly OpenStep) Objective-C frameworks, providing a cross-platform alternative for developing macOS-like applications on Linux and other systems. This project builds on the open-source parts of XNU to create a compatibility layer that runs macOS userspace on Linux, similar to how Wine runs Windows applications on Linux.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mach_(kernel)">Mach ( kernel ) - Wikipedia</a></li>
<li><a href="https://www.phoronix.com/news/XNU-Linux">XNU Linux Lets macOS Userspace Processes Run On Linux - Phoronix</a></li>
<li><a href="https://en.wikipedia.org/wiki/GNUstep">GNUstep</a></li>

</ul>
</details>

**Discussion**: Commenters expressed admiration for the technical achievement but debated its practicality: some preferred improving GNUstep as a freer alternative, while others suggested that since macOS lacks a stable syscall interface, running the macOS userspace directly on Linux with minimal kernel work would be more interesting. Concerns were also raised about hardware lock-in and the ephemeral nature of such projects, with one commenter noting that similar projects like Stela have disappeared from GitHub.

**Tags**: `#macOS`, `#Linux`, `#XNU`, `#operating-systems`, `#GUI`

---

<a id="item-5"></a>
## [GTA 6 Xbox Build Leak Sparks Public Reverse-Engineering Effort](https://www.reddit.com/r/GamingLeaksAndRumours/comments/1y3jzqe/cyberleek_posted_the_gta_6_xbox_build_executable/) ⭐️ 8.0/10

A user named Cyberleek posted the executable of a GTA 6 Xbox build, prompting a large-scale public effort to reverse-engineer and recompile the game for PC. The community is coordinating via GitHub, using LLMs to assist with translating Xbox shaders and system calls to standard PC equivalents. This leak shifts attention from PS5 firmware exploitation to direct Xbox build recompilation, potentially accelerating PC access to an unreleased major title. It also demonstrates a novel use of LLMs and crowdsourced GitHub contributions for game preservation and reverse engineering. The effort involves translating Xbox shaders and calls to PC equivalents, with contributors claiming tasks via GitHub issues. Community members report the project is averaging 5-6 pull requests per minute and coordinating over 1,000 people to build an emulator for the executable.

hackernews · monskov · Nov 23, 14:49 · [Discussion](https://news.ycombinator.com/item?id=50612686)

**Background**: GTA 6 is the highly anticipated next entry in Rockstar's Grand Theft Auto series, which has not yet been released. Reverse engineering involves analyzing a compiled program to understand its code, often to create ports or emulators. Recompilation projects aim to convert console game code to run natively on PC, and LLMs are increasingly used to assist with decompilation and code translation tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Grand_Theft_Auto">Grand Theft Auto - Wikipedia</a></li>
<li><a href="https://sourceforge.net/projects/xenia.mirror/">Xenia download | SourceForge.net</a></li>

</ul>
</details>

**Discussion**: Commenters describe this as a major moment for the recompilation scene, noting the shift from PS5 firmware bets to public Xbox recompilation efforts. Some praise LLMs as an excellent tool for reverse engineering, while others raise concerns about potential impacts on game distribution and the future of local play.

**Tags**: `#reverse-engineering`, `#game-preservation`, `#LLM`, `#GTA6`, `#emulation`

---

<a id="item-6"></a>
## [17M-line Lean formalization of GRH sparks debate on proof comprehensibility](https://micjm.com/blog/yes-17m-lines-of-lean-is-a-lot/) ⭐️ 8.0/10

A blog post discusses the scale of a 17-million-line Lean formalization of the Generalized Riemann Hypothesis (GRH), highlighting the massive size of machine-verified proofs. The post sparked a Hacker News discussion with 244 points and 303 comments on formal proof comprehensibility, LLM limitations, and the significance of machine-verified mathematics. This milestone demonstrates the growing feasibility of formalizing deep mathematical results, which could increase trust in complex proofs and enable broader adoption of proof assistants in mathematics. It also raises important questions about the role of human understanding in an era of machine-verified mathematics. The formalization is being actively optimized, with the codebase reportedly reduced to 13 million lines and potentially reaching 11 million lines soon. Commenters note that Lean is analogous to compiled math, where high-level statements expand into many low-level instructions, so line count is not a direct measure of conceptual complexity.

hackernews · seizethecheese · Nov 23, 05:00 · [Discussion](https://news.ycombinator.com/item?id=50607668)

**Background**: The Generalized Riemann Hypothesis is a major unsolved conjecture in number theory that generalizes the Riemann Hypothesis to Dirichlet L-functions. Lean is an interactive theorem prover and programming language that allows mathematicians to write proofs in a formal language that can be mechanically verified. Formal verification of such proofs ensures correctness but can result in very large codebases because every logical step must be explicitly justified.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lean">Lean - Wikipedia</a></li>
<li><a href="https://arxiv.org/html/2412.16075">Formal Mathematical Reasoning: A New Frontier in AI</a></li>

</ul>
</details>

**Discussion**: Commenters debated why LLMs struggle to write human-readable explanations, with one noting that LLMs fail to distinguish between what they know from debugging and what their audience knows. Others clarified that Lean is like compiled math, so line count reflects low-level expansion rather than incomprehensibility, and some mentioned the formalization has been reduced to 13 million lines with potential to reach 11 million. A few drew parallels to Ted Chiang's story about superintelligent science, questioning whether human understanding of such proofs is necessary.

**Tags**: `#Lean`, `#formal verification`, `#mathematics`, `#LLMs`, `#proof assistants`

---

<a id="item-7"></a>
## [ARM Forces Shutdown of Community Documentation Site](https://arm.jonpalmisc.com/) ⭐️ 7.0/10

A community-maintained ARM architecture documentation site, arm.jonpalmisc.com, announced it will be discontinued on December 4, 2026, at ARM's request. The site hosted converted versions of ARM's architecture reference manuals, and its shutdown follows a legal request from ARM. This event highlights a growing trend of hardware vendors restricting access to architecture documentation, which could impact developers, researchers, and hobbyists who rely on accessible technical references. It also raises questions about fair use and corporate control over information about publicly sold hardware. The site was a mirror of ARM's documentation, likely generated using conversion tools to make it more accessible. Community members noted that similar mirrors exist elsewhere, and some have already archived the site on the Wayback Machine.

hackernews · tech234a · Nov 23, 19:17 · [Discussion](https://news.ycombinator.com/item?id=50617499)

**Background**: ARM is a family of RISC instruction set architectures for computer processors, developed by Arm Holdings and licensed to other companies. Arm Holdings designs CPU cores and provides documentation for developers, but access to detailed architecture manuals often requires registration or licensing. Community-run mirrors aim to make this information more freely available, but they can face legal challenges from the copyright holder.

<details><summary>References</summary>
<ul>
<li><a href="https://en.m.wikipedia.org/wiki/ARM_architecture_family">ARM architecture family - Wikipedia</a></li>
<li><a href="https://en.m.wikipedia.org/wiki/ARM_Holdings">Arm Holdings - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed concern over ARM's legal action, questioning whether documenting hardware should be fair use and noting ARM's increasing closedness in recent years, possibly to compete with RISC-V. Some shared alternative mirrors and archival links, while others discussed tools for local archiving.

**Tags**: `#ARM`, `#hardware documentation`, `#legal`, `#open access`, `#RISC-V`

---

<a id="item-8"></a>
## [Nospeaker makes MacBook trackpad speak via haptic motor](https://github.com/os6/nospeaker) ⭐️ 7.0/10

Developer Cody Collier (os6 on GitHub) released Nospeaker, an open-source command-line tool that drives the MacBook's trackpad haptic motor up to 4,000 times per second to produce audible speech. The project turns the Force Touch trackpad into a makeshift speaker, generating sound from the same motor that normally simulates clicks. This clever hardware hack demonstrates how haptic actuators can be repurposed for audio output, blurring the line between tactile feedback and sound. It highlights the creative potential of repurposing existing hardware and has sparked community interest in further haptic-based projects. Nospeaker runs from the command line and drives the haptic motor at high frequency to generate sound; it reportedly speaks in the language set on the Mac, though this may not be an intended feature. Users have noted that it can be loud and may cause wear on the trackpad motor over time.

hackernews · yakkomajuri · Nov 23, 11:31 · [Discussion](https://news.ycombinator.com/item?id=50610318)

**Background**: Apple's Force Touch trackpad does not physically move; instead, a haptic motor taps the glass to simulate the sensation of a click. This motor is typically used for feedback, but Nospeaker exploits its ability to vibrate at high speeds to produce sound waves. The project is reminiscent of older hardware hacks, such as using floppy drive motors to play music.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/os6/nospeaker">os6/ nospeaker : make your macbook's trackpad talk using its haptic ...</a></li>
<li><a href="https://www.notebookcheck.net/New-free-open-source-tool-turns-your-MacBook-s-haptic-motor-not-its-speakers-into-a-voice.1457489.0.html">New free open-source tool turns your MacBook's haptic motor , not its...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed admiration for the project, with some noting that the trackpad's ability to simulate a click is even more impressive than the speech hack. One user reported trying it and being impressed by the loudness, while others shared related projects like haptic music players and floppy drive hacks.

**Tags**: `#hardware-hacking`, `#haptics`, `#macbook`, `#creative-coding`, `#hackernews`

---

<a id="item-9"></a>
## [Spelunkr.tv Turns Internet Archive Videos into Linear TV Channels](https://spelunkr.tv/) ⭐️ 7.0/10

Spelunkr.tv is a free alternative TV network that streams forgotten videos from the Internet Archive in a linear, channel-based format, mimicking traditional TV scheduling. The project gained significant attention on Hacker News, receiving 856 points and 151 comments. This project creatively repurposes public domain and archival content into a shared viewing experience, addressing the loneliness of on-demand streaming by reintroducing synchronous, linear TV. It highlights the potential of the Internet Archive as a source for novel media applications and sparks discussion about nostalgia and the social aspects of media consumption. Spelunkr.tv streams directly from the Internet Archive, bypassing the Archive's own user interface, which raises questions about how the Archive feels about this alternative UI. The service offers themed channels, such as a potential '2am theater' for drive-in movie double features, as suggested by commenters.

hackernews · SockThief · Nov 23, 01:13 · [Discussion](https://news.ycombinator.com/item?id=50606192)

**Background**: The Internet Archive is a non-profit digital library founded in 1996 by Brewster Kahle, providing free access to a vast collection of digitized media, including websites, books, audio, and video. Linear channel-based streaming, like traditional TV or FAST (Free Ad-Supported Streaming TV) channels, offers scheduled programming rather than on-demand selection, which can create a shared viewing experience. Spelunkr.tv combines these concepts by curating forgotten Internet Archive videos into scheduled channels, offering a nostalgic alternative to modern on-demand platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Internet_Archive">Internet Archive</a></li>
<li><a href="https://adwave.com/resources/what-are-fast-channels">What Are FAST Channels ? Free Streaming TV Explained</a></li>

</ul>
</details>

**Discussion**: Commenters praised the project for its nostalgic value and social experience, with one noting that on-demand streaming can feel lonely and that linear TV provides a sense of shared viewership. Others shared enthusiasm for specific content, like 1987 Headbangers Ball, and suggested channel ideas such as '2am theater' for drive-in double features. A few raised questions about the Internet Archive's stance on this alternative interface.

**Tags**: `#internet-archive`, `#streaming`, `#media`, `#nostalgia`, `#hacker-news`

---

<a id="item-10"></a>
## [Apple removes open-source app FSNotes from EU App Stores after nine years](https://github.com/glushchenko/fsnotes/discussions/2056) ⭐️ 7.0/10

The developer of FSNotes, an open-source note-taking app, reported that Apple removed the app from EU App Stores after nine years of availability. The removal was announced in a GitHub discussion, where the developer also noted that customer support requests are now prioritized by upvotes. This case highlights growing concerns about Apple's treatment of long-standing open-source developers and the opacity of App Store removal decisions, especially as the EU's Digital Markets Act reshapes platform rules. It could affect other independent developers who rely on the App Store for distribution in the EU. The developer's report suggests that official support channels now use upvotes as a de-facto entry barrier, and a previously similar issue (GitHub issue #695) was referenced. Apple offers an app review appeal request form, but the outcome for FSNotes remains unclear.

hackernews · fluder · Nov 23, 18:48 · [Discussion](https://news.ycombinator.com/item?id=50616933)

**Background**: FSNotes is an open-source note-taking app for macOS and iOS that has been available for nine years. The App Store is Apple's only official distribution channel for iOS apps, and Apple controls which apps are listed. The EU's Digital Markets Act (DMA) aims to make digital markets fairer and has forced Apple to make changes to iOS, Safari, and the App Store in the EU.

<details><summary>References</summary>
<ul>
<li><a href="https://digital-markets-act.ec.europa.eu/about-dma_en">About the Digital Markets Act</a></li>
<li><a href="https://discuss.appstudio.dev/t/interesting-webapp-article-i/3934">Interesting webapp article i - Community - AppStudio</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration that upvotes have become a de-facto barrier for official customer support, with one calling it 'crazy.' Others shared a link to a similar older issue and pointed to Apple's app review appeal form, while one remarked that this reflects how little Apple cares about its developer ecosystem.

**Tags**: `#Apple`, `#App Store`, `#open-source`, `#developer relations`, `#EU regulation`

---

<a id="item-11"></a>
## [Gentoo Developer Reflects on the 'Circle of Security Hell' Facing Open Source](https://blogs.gentoo.org/mgorny/2026/10/27/the-next-circle-of-security-hell/) ⭐️ 7.0/10

Gentoo developer Michał Górny published a blog post on October 27, 2026, describing an escalating 'circle of security hell' in which open source maintainers are overwhelmed by a constant stream of security vulnerability reports, upstream version bumps, and user expectations. The essay, which sparked over 100 comments on Hacker News, argues that the burden of security response is falling disproportionately on individual maintainers. The post highlights a systemic problem in open source: critical infrastructure depends on a small number of unpaid or underfunded maintainers who must triage an ever-growing volume of security issues. This affects everyone who relies on open source software, from individual users to large corporations, and fuels ongoing debates about memory safety, corporate responsibility, and sustainable maintainer workloads. Górny notes that he performs 'meaningless version bumps' with no real changes just so Gentoo packages are not flagged as outdated, a hassle that nonetheless reassures users. Commenters point out that the past 30 days alone saw at least six high-profile memory safety bugs in critical infrastructure including PHP, Brotli, nginx, Java, and Ruby, underscoring that compiler-level protections cannot catch application-logic flaws.

hackernews · qtqtqt · Nov 23, 11:34 · [Discussion](https://news.ycombinator.com/item?id=50610334)

**Background**: Gentoo is a Linux distribution known for its source-based package management, where users compile software locally, giving maintainers significant responsibility for tracking upstream releases and security patches. In recent years, the open source community has increasingly debated memory safety—the idea that languages like Rust can prevent entire classes of vulnerabilities such as buffer overflows—and maintainer burnout, as volunteer projects struggle to keep up with security demands from corporate users who contribute little back.

<details><summary>References</summary>
<ul>
<li><a href="https://www.zdnet.com/article/7-linux-distros-you-should-avoid-until-youve-mastered-the-command-line/">7 Linux distros you should avoid until you've mastered the... - ZDNET</a></li>

</ul>
</details>

**Discussion**: Commenters broadly agree that security is a shared responsibility, with one arguing that blaming Rust for memory-safety obsession ignores the many recent high-profile memory bugs in critical infrastructure. Others question why maintainers complain instead of simply setting boundaries and telling users to contribute or use software at their own risk, while another notes that version bumps are currently the only way to signal to users that a package has been checked.

**Tags**: `#open-source`, `#security`, `#maintainer-burnout`, `#memory-safety`, `#software-engineering`

---

<a id="item-12"></a>
## [Blog post argues against storing SSH keys on disk](https://jola.dev/posts/you-cant-afford-ssh-keys-disk) ⭐️ 7.0/10

A blog post on jola.dev argues that SSH private keys should not be stored on disk, recommending alternatives like password managers or hardware tokens. The post sparked a substantive Hacker News discussion with 66 comments debating the effectiveness of these protections. SSH keys are widely used for authenticating to servers and services, and their compromise can lead to severe security breaches. This discussion highlights practical trade-offs in key management and raises awareness about threat models, influencing how developers and sysadmins protect their credentials. The post suggests using password managers (like Bitwarden) or YubiKeys with GPG to avoid on-disk keys, but commenters note that if an attacker already has user-level access, these measures may not add meaningful protection. YubiKeys can store GPG keys irretrievably and require a PIN, while password managers can act as SSH agents.

hackernews · shintoist · Nov 23, 09:55 · [Discussion](https://news.ycombinator.com/item?id=50609579)

**Background**: SSH (Secure Shell) uses public-key cryptography for authentication, where a private key on the client proves identity to a server. Typically, private keys are stored on disk (e.g., ~/.ssh/id_rsa) and loaded into an SSH agent for convenience. Storing keys on disk poses a risk if the machine is compromised, as attackers can steal the key file. Alternatives include hardware security keys (like YubiKey) that keep the key isolated, or password managers that encrypt keys at rest.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/YubiKey">YubiKey - Wikipedia</a></li>
<li><a href="https://www.softplorer.com/security/passwords/intents/password-manager-for-ssh-keys">Using a password manager for SSH key storage | Softplorer</a></li>
<li><a href="https://delinea.com/blog/ssh-key-management">SSH Key Management Best Practices : Beyond SSH Keys</a></li>

</ul>
</details>

**Discussion**: Commenters debated the effectiveness of the approach: some argued that if an attacker has user-level access, protections like password manager approval are moot; others advocated for YubiKeys with GPG for hardware-based security. A few questioned the difference from using a passphrase-protected SSH key, and one noted that YubiKeys have writable memory for key storage.

**Tags**: `#security`, `#ssh`, `#authentication`, `#yubikey`, `#password-managers`

---

<a id="item-13"></a>
## [Muru: AI-assisted Rust server for ASGI/WSGI Python apps](https://simonwillison.net/2026/Nov/21/muru/) ⭐️ 7.0/10

Graham Dumpleton, creator of mod_wsgi, has launched Muru, an AI-assisted Rust server designed to run both ASGI and WSGI Python web applications in development and production. Over the past three weeks, he has published a detailed 19-part development journal documenting the project's design and progress. Muru brings the experience of a veteran Python web server maintainer to a modern Rust-based implementation, potentially offering better performance and deployment ergonomics for Python web apps. Its support for both ASGI and WSGI could simplify serving diverse Python frameworks, and the unusually transparent development process offers valuable insights for the community. The project is at an early stage, with blog posts covering topics such as worker internals, import-once-fork-many, HTTPS in development, releases without restarts, canary deployments without a service mesh, Kubernetes integration, scaling to zero, and a debug toolbar with tracing. Dumpleton emphasizes that while AI assists with much of the work, his twenty years of experience with mod_wsgi guides decisions about what is good enough.

rss · Simon Willison · Nov 21, 23:56

**Background**: WSGI (Web Server Gateway Interface) is the traditional synchronous standard for Python web servers to communicate with applications, while ASGI (Asynchronous Server Gateway Interface) is its asynchronous successor that supports WebSockets and long-lived connections. mod_wsgi, created by Graham Dumpleton 20 years ago, is a widely used Apache module for serving Python web applications via WSGI. Muru is a new Rust-based server that aims to modernize this space by natively supporting both interfaces.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Aug/31/introducing-wrapture/">Introducing wrapture | Simon Willison’s Weblog</a></li>
<li><a href="https://grahamdumpleton.me/posts/2026/08/introducing-wrapture/">Introducing wrapture - Graham Dumpleton</a></li>
<li><a href="https://www.geeksforgeeks.org/python/difference-between-asgi-and-wsgi-in-django/">Difference Between ASGI and WSGI in Django - GeeksforGeeks</a></li>

</ul>
</details>

**Tags**: `#python`, `#asgi`, `#wsgi`, `#rust`, `#web-servers`

---

<a id="item-14"></a>
## [Kagi Launches Privacy-Focused Email Service in Public Beta](https://blog.kagi.com/kagi-mail-public-beta) ⭐️ 6.0/10

Kagi, the paid ad-free search engine known for its privacy stance, has launched a public beta of Kagi Mail, expanding its product lineup beyond search. The service is offered as part of Kagi's Ultimate plan, which is priced at $100 per year. Email is the de facto gateway to online identity, used for account recovery by banks, brokerages, healthcare providers, and services like Cloudflare, so a new provider from a privacy-respecting company offers an alternative to ad-based giants. However, entering the crowded email market is an incremental move rather than a technical breakthrough, and success will depend on pricing and security trust. Kagi Mail is priced at $100 per year as part of the Ultimate plan, which some users find expensive compared to services like Fastmail at $60 per year. Kagi's existing practice of using email addresses as usernames without confirmation codes has raised audit concerns among potential users.

hackernews · rdmuser · Nov 23, 17:17 · [Discussion](https://news.ycombinator.com/item?id=50615481)

**Background**: Kagi is a paid, ad-free search engine developed by Kagi Inc. in Palo Alto, California, that pulls results from leading search engines and re-ranks them while filtering spam. Email is often called the 'master key' to online identity because almost every website supports account recovery via email, making the security of an email provider critical. Privacy-focused email providers like ProtonMail and Tuta offer alternatives to mainstream services, often without requiring phone number verification.

<details><summary>References</summary>
<ul>
<li><a href="https://en.m.wikipedia.org/wiki/KAGI">Kagi - Wikipedia</a></li>
<li><a href="https://passji.com/blog/email-is-the-master-key">Passji — Your emoji is your identity</a></li>
<li><a href="https://blog.superhuman.com/create-email-without-phone-number/">Emails that don't require phone number: 12 best providers in 2026</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted that email is the gateway to online identity and advised keeping recovery emails separate if using a niche provider that may lack a top-notch security team. Some balked at the $100/year price compared to Fastmail's $60/year, while others expressed interest in calendar API support and praised Kagi for including Mail in the Ultimate plan.

**Tags**: `#email`, `#privacy`, `#kagi`, `#product-launch`, `#security`

---

<a id="item-15"></a>
## [LeCun Accuses Amodei of Hyping AI Risks to Ban Open Models](https://twitter.com/ylecun/status/2124550037912920090) ⭐️ 6.0/10

Yann LeCun tweeted an accusation that Dario Amodei is exaggerating AI dangers to push for banning open-source models and maintain control, sparking an 87-comment Hacker News debate on regulatory capture and open-model defense. This highlights a growing rift in the AI community over whether safety concerns are being used to entrench incumbents and stifle open-source competition, with direct implications for AI regulation and innovation. Commenters discussed extreme measures like microcode updates to limit consumer GPUs and registration for private compute, while others noted that Amodei has publicly said he does not support banning open-weight models but favors mandatory safety testing.

hackernews · MrBuddyCasino · Nov 23, 17:07 · [Discussion](https://news.ycombinator.com/item?id=50615308)

**Background**: Regulatory capture refers to when an industry co-opts the agencies meant to oversee it. Open-weight models are AI systems whose parameters are publicly released, allowing anyone to run and modify them, which makes bans difficult to enforce.

<details><summary>References</summary>
<ul>
<li><a href="https://www.outlookbusiness.com/corporate/anthropic-ceo-dario-amodei-backs-ai-safety-tests-over-blanket-ban-on-open-weight-models">Anthropic CEO Dario Amodei Backs AI Safety Tests Over Blanket...</a></li>
<li><a href="https://www.mindstudio.ai/blog/ai-regulatory-capture-anthropic-safety-stance-backfired">What Is AI Regulatory Capture ? How Anthropic's Safety... | MindStudio</a></li>

</ul>
</details>

**Discussion**: Commenters were divided: some warned that banning open models would entrench closed-model providers and eliminate a key defense against misuse, while others argued that open models reduce misuse risk but increase loss-of-control risk, and some accused AI companies of using safety as a pretext to force API dependence.

**Tags**: `#AI regulation`, `#open-source AI`, `#AI safety`, `#industry influence`, `#Hacker News discussion`

---

<a id="item-16"></a>
## [Win4wine runs Windows XP Explorer as a Linux desktop shell on Wine](https://github.com/mikuta0407/win4wine) ⭐️ 6.0/10

Win4wine is an experimental project that runs Windows XP's explorer.exe as the desktop shell on Linux by patching Wine, providing a Windows-like desktop environment with Linux app integration and tray icons. It demonstrates the flexibility of Linux desktop stacks and sparks debate about OS design tradeoffs, such as combining Windows' NT kernel with Linux's open-source tools, and highlights security implications of running legacy Windows shell components. The project uses a patched Wine to run the actual Windows XP explorer.exe, which means it inherits vulnerabilities from that legacy shell; alternatives like loss32 aim to build a desktop using only free Win32 software and ReactOS components.

hackernews · hard_times · Nov 23, 12:28 · [Discussion](https://news.ycombinator.com/item?id=50610743)

**Background**: Wine is a compatibility layer that allows Windows applications to run on POSIX systems like Linux without emulation. The Windows shell, explorer.exe, provides the desktop, taskbar, and file management, while on Linux the desktop environment is typically a separate stack (e.g., GNOME, KDE). Win4wine replaces the Linux desktop environment with the Windows XP shell, creating a hybrid experience.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/mikuta0407/win4wine">GitHub - mikuta0407/ win4wine : Windows XP の Explorer を Wine 上で...</a></li>
<li><a href="https://github.com/mikuta0407/win4wine/tree/master/wine">win4wine /wine at master · mikuta0407/ win4wine · GitHub</a></li>
<li><a href="https://www.winehq.org/">WineHQ - Run Windows applications on Linux, BSD, Solaris and...</a></li>

</ul>
</details>

**Discussion**: Commenters found the project technically interesting but debated its direction: one suggested the reverse (running Linux tools on the NT kernel) might be better, another noted it could run AutoHotkey but inherits XP/7 vulnerabilities, and others shared alternatives like the XPTC theme for XFCE and the unreleased loss32 project.

**Tags**: `#wine`, `#linux-desktop`, `#windows`, `#open-source`, `#os-design`

---

<a id="item-17"></a>
## [Beginner's Guide to Local AI with Inkling, Qwen, and Unsloth](https://www.gpupartner.com/blog/beginners-guide-local-ai-inkling-qwen-unsloth) ⭐️ 6.0/10

A new beginner's guide explains how to set up local AI using Inkling, Qwen, and Unsloth, and it sparked a Hacker News discussion with 707 points and 282 comments sharing hardware tips and cost-effective alternatives. This guide lowers the barrier to entry for running AI models locally, which appeals to users concerned about privacy, cost, and cloud dependency, and the community response shows strong interest in practical, affordable setups. The discussion highlights that you don't need a $5k RTX 5090; used hardware like a Dell T5820 with 64GB RAM and a Tesla P100 16GB GPU can run capable models at 30 tok/s for under $1k, and an Nvidia P40 with 24GB GDDR5 costs about $300 on eBay.

hackernews · Retell15 · Nov 22, 21:01 · [Discussion](https://news.ycombinator.com/item?id=50603845)

**Background**: Local AI refers to running large language models (LLMs) on your own hardware rather than through cloud APIs. Inkling is a model designed for local deployment, Qwen is a family of open-weight LLMs from Alibaba Cloud, and Unsloth is an open-source library for running and fine-tuning models locally on Mac, Windows, and Linux.

<details><summary>References</summary>
<ul>
<li><a href="https://unsloth.ai/docs/models/inkling">Inkling - How to Run Locally | Unsloth Documentation</a></li>
<li><a href="https://en.m.wikipedia.org/wiki/Qwen">Qwen - Wikipedia</a></li>
<li><a href="https://unsloth.ai/">Unsloth - Run and Train Models Locally</a></li>

</ul>
</details>

**Discussion**: Commenters shared practical tips for affordable hardware, such as using used GPUs like the Tesla P100 and Nvidia P40, and debated the necessity of high-end GPUs. Some noted that the guide's claim about needing a Windows PC with a GPU is not true, and one commenter described local AI as being in its 'plasma TV phase'—early, heavy, and expensive—predicting it will take about five years for most practical AI to run on personal machines.

**Tags**: `#local-ai`, `#llm`, `#hardware`, `#tutorial`, `#qwen`

---