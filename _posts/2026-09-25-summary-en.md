---
layout: default
title: "Horizon Summary: 2026-09-25 (EN)"
date: 2026-09-25
lang: en
---

> From 38 items, 21 important content pieces were selected

---

1. [Dutch Government Builds NixOS-Based Alternative to Microsoft](#item-1) ⭐️ 8.0/10
2. [F-Droid 2.0 Launches Major Redesign, Phases Out Privileged Extension](#item-2) ⭐️ 8.0/10
3. [DHH's Rails World 2026 Keynote Sparks Debate on AI and Rails' Future](#item-3) ⭐️ 8.0/10
4. [LLMs Trace Alchemical Knowledge and Decode 17th-Century Letters](#item-4) ⭐️ 8.0/10
5. [UK Two-Tier Encryption: Apple Pulls Advanced Data Protection](#item-5) ⭐️ 8.0/10
6. [Bastardica: A Web Tool That Creates Cursed Mixed Fonts via OpenType Ligatures](#item-6) ⭐️ 7.0/10
7. [Whiteboard (YC W26) Launches Open-Source IDE for Human-AI Software Design](#item-7) ⭐️ 7.0/10
8. [Why Is the Liver So Uniquely Regenerative?](#item-8) ⭐️ 7.0/10
9. [Google's Project Suncatcher to put ML infrastructure in space](#item-9) ⭐️ 7.0/10
10. [Simon Willison Builds BYOK Playground for Gemini 3.8 TTS](#item-10) ⭐️ 7.0/10
11. [arXiv secures $17.2M to fund its independent nonprofit launch](#item-11) ⭐️ 7.0/10
12. [Pentium II 600MHz with Voodoo 3 Emulated on M6 Mac Mini via 86Box](#item-12) ⭐️ 6.0/10
13. [Economist: Mafia's Long-Term Business Logic May Keep Fentanyl Out of Italy](#item-13) ⭐️ 6.0/10
14. [Blog Post Questions Rails' Future, Sparking HN Debate](#item-14) ⭐️ 6.0/10
15. [Toyota to Electrify Its Best-Selling Corolla](#item-15) ⭐️ 6.0/10
16. [Opus 5.5 Shows Promise for AI-Generated Explainer Videos](#item-16) ⭐️ 6.0/10
17. [ICLR 2027 Submissions Exposed to Program Committee Members](#item-17) ⭐️ 6.0/10
18. [NeurIPS Accepted Papers Now Visible on Conference Site](#item-18) ⭐️ 6.0/10
19. [Reddit user criticizes AAAI review quality and AI-generated reviews](#item-19) ⭐️ 6.0/10
20. [How Much Can a Paper Change Between Acceptance and Camera-Ready?](#item-20) ⭐️ 6.0/10
21. [NeurIPS 2024 Main Track Decisions Released: 7,900 of 30,709 Accepted](#item-21) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Dutch Government Builds NixOS-Based Alternative to Microsoft](https://www.dawo.community/en/) ⭐️ 8.0/10

The Dutch government is developing a NixOS-based alternative to Microsoft software, a move that sparked a Hacker News discussion with 478 points and 235 comments. The project aims to reduce dependence on US big tech by using the declarative, reproducible Linux distribution NixOS. This initiative reflects a broader European push for digital sovereignty, as governments seek to replace proprietary US software with open-source alternatives. If successful, it could serve as a model for other public-sector deployments and strengthen the NixOS ecosystem. NixOS is a Linux distribution built around the Nix package manager, offering declarative configuration, atomic upgrades, and reproducible deployments. However, community members noted that replacing Microsoft 365 with LibreOffice or Collabora remains a major friction point, and the project's repositories were flagged for violating Codeberg's policy against AI-generated code.

hackernews · fjfaase · Sep 25, 08:06 · [Discussion](https://news.ycombinator.com/item?id=49841563)

**Background**: NixOS is a Linux distribution that uses the Nix functional package manager to build the entire system from declarative configuration files, enabling reproducible builds and rollbacks. Digital sovereignty refers to a government's ability to control its own digital infrastructure and data, reducing reliance on foreign proprietary vendors. Several European governments have launched similar open-source projects, such as France's Securix and Bureautix, Germany's openDesk, and France's La Suite.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/NixOS">NixOS</a></li>
<li><a href="https://www.linkedin.com/posts/josh-powell-2522b534_digital-sovereignty-open-source-the-unlikely-activity-7381405246733881344-5MU9">How open source can help governments with digital sovereignty</a></li>
<li><a href="https://digital-strategy.ec.europa.eu/en/factpages/eu-open-source-strategy">EU Open Source Strategy | Shaping Europe’s digital future</a></li>

</ul>
</details>

**Discussion**: Commenters largely welcomed the move away from US big tech, with some citing Microsoft's controversial patent for ad-based program access as motivation. Others highlighted similar French and German projects like Securix, Bureautix, openDesk, and La Suite, while one developer warned that the project's repositories violate Codeberg's AI-generated code policy, and another expressed skepticism that LibreOffice can replace Microsoft 365 without friction.

**Tags**: `#NixOS`, `#open-source`, `#government`, `#Microsoft`, `#digital sovereignty`

---

<a id="item-2"></a>
## [F-Droid 2.0 Launches Major Redesign, Phases Out Privileged Extension](https://f-droid.org/2026/09/24/f-droid-2.0-a-new-chapter-for-android-freedom.html) ⭐️ 8.0/10

F-Droid released version 2.0 on September 24, 2026, its largest update in a decade, featuring a complete UI redesign and a rewrite of core components in Kotlin with Jetpack Compose. The release also begins phasing out the F-Droid Privileged Extension (FPE), which previously granted elevated install permissions. As one of the most widely used open-source Android app repositories, F-Droid's overhaul affects millions of privacy-conscious users and could influence how alternative app stores handle modern Android development. The FPE phase-out simplifies installation on custom ROMs like GrapheneOS and LineageOS, where configuring the extension was often a pain point. The redesign was rebuilt from scratch in Kotlin Compose, the modern standard for Android UI, and the FPE is being retired in favor of smoother built-in install flows. Community feedback highlighted issues such as poor text wrapping in screenshots and a lack of visual differentiation between UI sections.

hackernews · daveoc64 · Sep 24, 15:26 · [Discussion](https://news.ycombinator.com/item?id=49831968)

**Background**: F-Droid is a free and open-source app store for Android that only hosts apps with open-source code, offering an alternative to Google Play. The Privileged Extension was a separate system app that allowed F-Droid to install and uninstall apps without user approval, but it required root or custom ROM integration, making it difficult to set up. Version 2.0 marks the first major redesign in ten years, moving the client to Kotlin and Jetpack Compose.

<details><summary>References</summary>
<ul>
<li><a href="https://f-droid.org/en/2026/09/24/f-droid-2.0-a-new-chapter-for-android-freedom.html">F-Droid 2.0: A New Chapter for Android Freedom | F-Droid - Free and Open Source Android App Repository</a></li>
<li><a href="https://arstechnica.com/gadgets/2026/09/f-droid-gets-its-biggest-update-in-a-decade-with-new-ui-and-smoother-app-installs/">F-Droid gets its biggest update in a decade with new UI and smoother app installs - Ars Technica</a></li>
<li><a href="https://f-droid.org/packages/org.fdroid.fdroid.privileged/">F-Droid Privileged Extension | F-Droid - Free and Open Source Android App Repository</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were sharply divided: some praised the overhaul and the FPE removal, while others criticized the new design's lack of visual hierarchy and called out issues like broken text wrapping in screenshots. A recurring complaint was F-Droid's long-standing lack of app reviews, which makes it hard to distinguish quality apps, and several users said they prefer third-party clients like Droid-ify.

**Tags**: `#F-Droid`, `#Android`, `#Open Source`, `#UI Design`, `#App Store`

---

<a id="item-3"></a>
## [DHH's Rails World 2026 Keynote Sparks Debate on AI and Rails' Future](https://www.youtube.com/watch?v=vDjW_dRyKXY) ⭐️ 8.0/10

David Heinemeier Hansson (DHH) delivered the opening keynote at Rails World 2026, held September 23-24 in Austin, Texas, addressing the future direction of the Rails framework and the growing role of AI in software development. The talk quickly generated a heated Hacker News discussion with 391 comments debating maintainability, developer roles, and industry trends. As the creator of Rails, DHH's views carry significant weight in the Ruby and broader web development community, and his embrace of AI-assisted development signals a potential shift in how mainstream frameworks and their communities approach coding practices. The intense debate reflects a wider industry anxiety about whether AI-generated code will undermine long-term maintainability and devalue developer expertise. The keynote touched on AI's role in development and the future of Rails, with community members noting DHH's perspective appeared to come from a developer-user standpoint rather than a framework maintainer's, which some found surprising. Commenters also referenced specific practices like deleting 180 system tests at Basecamp down to 10 smoke tests, and DHH's reported interest in rewriting components in Rust.

hackernews · an0malous · Sep 23, 15:33 · [Discussion](https://news.ycombinator.com/item?id=49817680)

**Background**: Rails World is an annual two-day, two-track conference for the Ruby on Rails community, featuring technical talks, demos, and keynotes about the latest features and best practices. Rails is a popular open-source web application framework created by DHH in 2004, known for its convention-over-configuration philosophy. The 2026 edition took place in Austin, Texas, with keynotes from DHH, Robby Russell, and Aaron Patterson.

<details><summary>References</summary>
<ul>
<li><a href="https://rubyonrails.org/world/2026/">Rails World 2026 — Rails World 2026 - September 23 & 24 in Austin, TX</a></li>
<li><a href="https://www.rubyevents.org/events/rails-world-2026">Rails World 2026 | RubyEvents.org</a></li>
<li><a href="https://rdrama.net/h/slackernews/post/846386/dhh-on-the-opening-keynote-of">DHH , on the opening keynote of Rails World 2026, tells... - rDrama</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion was sharply divided: some attendees like robbyrussell reported an optimistic on-site vibe, noting most developers remain employed maintaining systems businesses rely on, while others like lovedaddy pushed back hard, preferring to understand their codebase rather than accept AI-generated 'random rust' in production. Several commenters, including robgough, acknowledged the uncomfortable truth in DHH's message but worried that his developer-user framing rather than framework-maintainer perspective bodes poorly for Rails itself.

**Tags**: `#Rails`, `#AI`, `#software-development`, `#keynote`, `#HN-discussion`

---

<a id="item-4"></a>
## [LLMs Trace Alchemical Knowledge and Decode 17th-Century Letters](https://resobscura.substack.com/p/ai-labs-need-to-start-funding-historical) ⭐️ 8.0/10

A new article on the Substack newsletter Res Obscura explores how large language models can be applied to historical research, specifically to trace the transmission of alchemical knowledge and to decode 17th-century letters. The piece argues that AI labs should begin funding historical research, positioning this as a promising and underexplored intersection of AI and the digital humanities. This highlights a growing trend of applying LLMs beyond commercial and coding tasks into the digital humanities, where they can help historians decipher difficult handwriting and trace the spread of esoteric ideas across centuries. If AI labs fund such work, it could accelerate the digitization and analysis of vast historical archives and open new research questions in fields like alchemy, early modern science, and genealogy. The article focuses on 17th-century alchemical texts and letters, which are notoriously difficult to read due to archaic handwriting, specialized terminology, and metaphorical language. Community members also pointed to resources like SourceLibrary.org, a UNESCO-recognized library of alchemy and mysticism in Amsterdam that offers agent-accessible translations and embeddings via API and MCP.

hackernews · benbreen · Sep 24, 19:14 · [Discussion](https://news.ycombinator.com/item?id=49835531)

**Background**: Alchemy was a major intellectual tradition in early modern Europe, blending proto-chemistry, philosophy, and mysticism, and its texts are often written in dense symbolic language that is hard to interpret. Digital humanities is an interdisciplinary field that uses computational tools to analyze cultural and historical artifacts, and recent advances in AI handwriting recognition and historical language models have made it possible to automatically transcribe and interpret old manuscripts. Large language models, trained on vast text corpora, can now assist with tasks like pattern recognition in ciphered letters and contextual analysis of unclear words.

<details><summary>References</summary>
<ul>
<li><a href="https://alchemywebsite.com/texts_17th.html">Alchemical Texts - 17th Century</a></li>
<li><a href="https://www.uio.no/english/research/research-news/articles/2025/ai-assists-researchers-in-decoding-old-secret-letters.html">AI assists researchers in decoding old secret letters - Research News</a></li>
<li><a href="https://sebd2024.unica.it/papers/paper66.pdf">Large Language Models integration in Digital Humanities</a></li>

</ul>
</details>

**Discussion**: Commenters were largely enthusiastic, with one sharing success using AI for genealogical research and another offering SourceLibrary.org as a free resource for agent-accessible alchemical texts. Some expressed hope that LLMs could help resolve ancient Near East chronology or decode difficult 17th-century handwriting, while one commenter framed LLMs as 'idea machines' that open new paths for historical thinking.

**Tags**: `#LLM`, `#digital humanities`, `#history`, `#alchemy`, `#text decoding`

---

<a id="item-5"></a>
## [UK Two-Tier Encryption: Apple Pulls Advanced Data Protection](https://macanorak.com/two-tier-encryption-in-the-uk/) ⭐️ 8.0/10

Apple has disabled its Advanced Data Protection (ADP) feature for UK users after the UK government issued a Technical Capability Notice under the Investigatory Powers Act 2016 demanding access to end-to-end encrypted iCloud data. Because ADP can only be toggled by a user's trusted devices, Apple could not simply switch it off server-side, resulting in a two-tier encryption regime where UK users lose E2EE for nine additional iCloud categories. This marks the first time a major tech company has withdrawn an encryption feature in response to government demands rather than building a backdoor, setting a precedent for how jurisdictions can effectively degrade privacy protections. It affects millions of UK Apple users and raises broader questions about government overreach, cross-border data obligations, and whether other countries will follow the UK's approach. ADP normally expands end-to-end encryption from 14 to 23 iCloud categories, including iCloud Backup, Photos, Notes, and iCloud Drive; UK users without ADP revert those categories to Standard Data Protection where Apple holds the keys. Apple deliberately designed ADP so its servers cannot modify or roll back the setting, which is why the company could not disable it uniformly and instead had to stop offering it in the UK.

hackernews · ReturnoftheHack · Sep 24, 10:39 · [Discussion](https://news.ycombinator.com/item?id=49828731)

**Background**: Advanced Data Protection is an optional Apple feature that extends end-to-end encryption to most iCloud data, meaning only the user's trusted devices hold the decryption keys. The UK's Investigatory Powers Act 2016 allows the Home Secretary to issue secret Technical Capability Notices requiring companies to build interception capabilities, and reports indicate Apple received such a notice targeting its encrypted cloud services. Apple's refusal to build a backdoor led it to withdraw ADP in the UK instead.

<details><summary>References</summary>
<ul>
<li><a href="https://macanorak.com/two-tier-encryption-in-the-uk/">Two-Tier Encryption in the UK</a></li>
<li><a href="https://www.globalencryption.org/2025/02/joint-letter-on-the-uk-governments-use-of-investigatory-powers-act-to-attack-end-to-end-encryption/">Joint Letter on the UK Government’s use of Investigatory ...</a></li>
<li><a href="https://support.apple.com/en-us/108756">How to turn on Advanced Data Protection for iCloud - Apple Support</a></li>

</ul>
</details>

**Discussion**: Commenters largely criticized Apple for not resisting as strongly as it did against the FBI in 2015, with some pointing to mandatory age-verification screens as evidence of eroding principles. Others debated the technical nuances of which iCloud categories remain end-to-end encrypted, and several expressed hope that Apple would pull out of the UK market entirely rather than comply.

**Tags**: `#encryption`, `#privacy`, `#Apple`, `#UK policy`, `#security`

---

<a id="item-6"></a>
## [Bastardica: A Web Tool That Creates Cursed Mixed Fonts via OpenType Ligatures](https://bastardica.mitpit.com/) ⭐️ 7.0/10

A new Show HN project called Bastardica (bastardica.mitpit.com) lets users create 'cursed' mixed fonts by abusing OpenType's ligature feature to swap glyphs from different typefaces. It runs entirely client-side by loading Python in WebAssembly, making the font generation fast and browser-based. This tool demonstrates a clever, unconventional use of OpenType ligatures and shows how Python-in-WASM can enable fast, fully client-side font processing without a server. It highlights the creative potential of web typography and has sparked lively discussion among developers and designers about font hacking and related projects. The tool exploits OpenType ligatures to substitute glyphs from different fonts, and the heavy lifting is done by Python running in WebAssembly, likely via Pyodide or a similar runtime. The result is a downloadable font file that mixes typefaces in a jarring, humorous way, as seen in the community's experiments with Papyrus and Comic Sans.

hackernews · MitPitt · Sep 23, 22:53 · [Discussion](https://news.ycombinator.com/item?id=49823738)

**Background**: OpenType is a font format that supports advanced typographic features, including ligatures—special glyphs that combine multiple characters (like 'fi' or 'ffl') into one. WebAssembly (WASM) is a binary instruction format that allows high-performance code to run in web browsers, and projects like Pyodide enable Python to run in that environment. Times New Bastard is a well-known joke font that mixes Times New Roman with a sans-serif every seventh letter, and Bastardica generalizes that idea into a tool.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/weiweihuanghuang/Times-New-Bastard">GitHub - weiweihuanghuang/ Times - New - Bastard : It's Times New ...</a></li>
<li><a href="https://github.com/pyodide/pyodide">GitHub - pyodide/pyodide: Pyodide is a Python distribution for the browser and Node.js based on WebAssembly · GitHub</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Fonts/OpenType_fonts">OpenType font features - CSS | MDN - MDN Web Docs Usage example</a></li>

</ul>
</details>

**Discussion**: Commenters shared related projects like Paranoia Sans and an ambigram generator, and joked about pranking designers by mixing Papyrus with Comic Sans or Helvetica with Arial. The overall sentiment is enthusiastic and playful, with users appreciating the tool's creative and technical cleverness.

**Tags**: `#fonts`, `#OpenType`, `#WebAssembly`, `#Python`, `#Show HN`

---

<a id="item-7"></a>
## [Whiteboard (YC W26) Launches Open-Source IDE for Human-AI Software Design](https://github.com/devdotfast/whiteboard) ⭐️ 7.0/10

A team of four developers (Sid, Alex, Ketan, and Milan) released Whiteboard, an MIT-licensed open-source desktop app that lets humans and AI agents architect software together on a shared canvas, integrating with tools like Claude Code and Codex. The app is built on top of CodeOSS and includes a Rust-based semantic AST-aware diff viewer, a decision log for tracking agent traces, and a WASM plugin system. As agentic coding becomes standard, developers risk accumulating 'cognitive debt' by merging AI-generated PRs they don't fully understand; Whiteboard aims to keep humans in the loop by visually linking specs and diagrams to code. Its traction at companies like Salesforce and Modal suggests demand for review tools that handle large volumes of AI-generated changes. Whiteboard is currently an early-stage MVP that does not yet allow editing files directly, and Codex reportedly warns users that it requires uploading or exposing repository data to its authoring server, raising questions about how 'local' the tool really is. The team plans to eventually charge for a hosted web version with trajectory storage and multiplayer reviews, while keeping everything self-hostable.

hackernews · sidharthkmenon · Sep 24, 17:21 · [Discussion](https://news.ycombinator.com/item?id=49833867)

**Background**: CodeOSS is the open-source core of Visual Studio Code, which gives Whiteboard VSCode keybindings and LSP support out of the box. Claude Code is Anthropic's terminal-based agentic coding tool, while Codex is OpenAI's cloud-based software engineering agent; both are AI agents that can autonomously write and modify code. Whiteboard's semantic diff viewer uses AST (abstract syntax tree) awareness to summarize large added functions as pseudocode and collapse unit tests or documentation changes.

<details><summary>References</summary>
<ul>
<li><a href="https://appimage.github.io/Code_OSS/">Code OSS – AppImages</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://grokipedia.com/page/Codex_OpenAI">Codex (OpenAI)</a></li>

</ul>
</details>

**Discussion**: Commenters were largely enthusiastic, with one calling the streaming diagram animations a technique that will be everywhere in 12 months, while others questioned how Whiteboard compares to fully open-source alternatives like LikeC4 and Erode, and whether it can still be called an IDE if you cannot edit files. A notable concern was raised about Codex warning that repository data must be exposed to Whiteboard's authoring server, which conflicts with expectations of local operation.

**Tags**: `#open-source`, `#IDE`, `#AI-agents`, `#software-design`, `#developer-tools`

---

<a id="item-8"></a>
## [Why Is the Liver So Uniquely Regenerative?](https://dynomight.substack.com/p/liver) ⭐️ 7.0/10

A widely discussed Substack essay by dynomight explores why the liver is the only visceral organ capable of regenerating itself, drawing on evolutionary trade-offs and medical evidence. The piece sparked 232 comments, including detailed expert commentary from a practicing pathologist and a liver transplant recipient. Liver regeneration underpins lifesaving procedures such as living-donor liver transplantation and partial hepatectomy, so understanding its mechanisms and limits has direct clinical relevance. The discussion also highlights broader questions about why humans and other mammals lost regenerative capacities that some animals retain. The liver can regenerate after partial hepatectomy or injury from hepatotoxic agents, with hepatocytes progressing through distinct phases driven by growth factors and signaling pathways. However, regeneration is not unlimited — severe or chronic injury can overwhelm it, and the regrown tissue may not perfectly restore original structure.

hackernews · jbotz · Sep 24, 16:23 · [Discussion](https://news.ycombinator.com/item?id=49832938)

**Background**: The liver is the only visceral organ known to regenerate, a capacity it uses to replace tissue lost to surgery, toxins, or disease. This regeneration occurs mainly through proliferation of existing hepatocytes rather than stem cells, and it is regulated by a complex network of growth factors and signaling pathways. Other organs, such as the heart and kidneys, have very limited regenerative ability, which is why liver regeneration is considered unusual among mammals.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Liver_regeneration">Liver regeneration - Wikipedia</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12717721/">Liver regeneration: unraveling the molecular mechanisms and ...</a></li>
<li><a href="https://www.nature.com/articles/s41575-020-0342-4">Liver regeneration: biological and pathological mechanisms ...</a></li>

</ul>
</details>

**Discussion**: Commenters broadly agreed the piece was a valuable educational deep-dive, with a pathologist recommending Robert Weinberg's The Biology of Cancer as a starting point. Others debated evolutionary trade-offs, noting that most body parts don't regenerate due to insufficient evolutionary pressure and that even salamander regeneration has limits, while a transplant recipient shared first-hand experience of liver regrowth after receiving a cut-down donor organ.

**Tags**: `#biology`, `#regeneration`, `#liver`, `#evolution`, `#medicine`

---

<a id="item-9"></a>
## [Google's Project Suncatcher to put ML infrastructure in space](https://blog.google/innovation-and-ai/models-and-research/google-research/google-project-suncatcher-facts/) ⭐️ 7.0/10

Google announced Project Suncatcher, a research initiative to explore placing solar-powered ML data centers in orbit, with a first prototype satellite test planned to evaluate how Google Tensor Processing Units (TPUs) perform in space. The announcement was accompanied by a detailed technical brochure and a New York Times article, and it sparked a 413-comment Hacker News discussion. This signals a major industry direction toward space-based AI infrastructure, potentially bypassing terrestrial constraints like land, power, water, and public opposition to data centers. If feasible, it could reshape how hyperscalers plan compute capacity and energy sourcing over the next decade. Google's own brochure lists cooling as a challenge rather than an advantage, and the only stated benefit is near-constant sunlight, which commenters note would need roughly 8x solar efficiency to offset 1000x terrestrial construction costs. The initiative is framed as moonshot research where even negative results are valuable, and Google's feasibility study suggests launch costs would need to fall to about US$200/kg to make orbital data centers economically viable.

hackernews · xnx · Sep 24, 13:53 · [Discussion](https://news.ycombinator.com/item?id=49830606)

**Background**: Space-based data centers are an emerging concept in which satellites carrying compute hardware, such as Google's TPUs, operate in orbit powered by solar energy. The idea is being explored by multiple groups, including academic studies and industry analyses from BCG and JLL, which suggest orbital data centers could become technically feasible at scale within five to ten years but face major hurdles in launch cost, cooling, and networking. Google has been researching this since at least November 2025, when it published a feasibility study and a research blog on modular, interconnected satellite designs.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/google-research/google-project-suncatcher-facts/">Learn about Google ’s Project Suncatcher to put ML infrastructure in...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Space-based_data_center">Space-based data center - Wikipedia</a></li>
<li><a href="https://www.bcg.com/publications/2026/space-based-data-centers-cost-outlook">Space-Based Data Centers: Cost and Outlook to 2040 | BCG</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were largely critical but engaged, noting that the physics and economics are worse than terrestrial data centers while acknowledging the brochure honestly lists cooling as a challenge. Several pointed out that the real motivation may be escaping public opposition to land-based data centers, and one commenter praised the transparent 'moonshot research' framing where even negative results are valuable.

**Tags**: `#Google`, `#ML infrastructure`, `#space data centers`, `#sustainability`, `#industry news`

---

<a id="item-10"></a>
## [Simon Willison Builds BYOK Playground for Gemini 3.8 TTS](https://simonwillison.net/2026/Sep/23/gemini-tts-playground/) ⭐️ 7.0/10

Google released two new text-to-speech models, gemini-3.8-flash-tts and gemini-3.8-flash-lite-tts, featuring a library of over 2,000 voices and custom voice cloning from just a 30-second audio sample. Simon Willison then vibe-coded a bring-your-own-key playground for these models using GPT-6 Astra, leveraging the Gemini API's open CORS policy. The 2,000+ voice library and 30-second voice cloning lower the barrier for developers and creators to build rich multi-speaker audio experiences without expensive recording sessions. The open CORS policy also means browser-based tools can call the Gemini TTS API directly, enabling a new wave of lightweight, client-side voice applications. The playground supports multi-speaker conversations with per-line delivery style instructions, and a demo generated 1 minute 18 seconds of audio in about 20 seconds using gemini-3.8-flash-tts at a cost of 2.74 cents. The API key stays in the page's memory and is sent directly to Google, never saved to browser storage.

rss · Simon Willison · Sep 23, 17:12

**Background**: Text-to-speech (TTS) models convert written text into spoken audio, and recent advances allow them to mimic specific voices from short samples. Bring-your-own-key (BYOK) is a model where users supply their own API key from a provider, so the tool acts as a client connecting directly to the user's account rather than reselling access. CORS (Cross-Origin Resource Sharing) is a browser security mechanism that determines whether a web page can call an API on a different domain; an open CORS policy makes such direct calls possible.

<details><summary>References</summary>
<ul>
<li><a href="https://llmplayground.net/blog/en/what-is-byok">What Is Bring-Your-Own-Key (BYOK) AI Chat? Cost & Privacy ...</a></li>
<li><a href="https://elevenlabs.io/voice-cloning">AI Voice Cloning : Clone Your Voice in Minutes</a></li>
<li><a href="https://discuss.ai.google.dev/t/gemini-api-cors-error-with-openai-compatability/58619">Gemini API CORS Error with OpenAI Compatability - Gemini API ...</a></li>

</ul>
</details>

**Tags**: `#text-to-speech`, `#gemini`, `#google-ai`, `#developer-tools`, `#voice-cloning`

---

<a id="item-11"></a>
## [arXiv secures $17.2M to fund its independent nonprofit launch](https://www.reddit.com/r/MachineLearning/comments/1wox8kt/arxiv_receives_multiyear_philanthropic/) ⭐️ 7.0/10

arXiv has received $17.2 million in multiyear philanthropic commitments from Simons Foundation International, XTX Markets, and Siegel Family Endowment, spanning three to five years, to support its launch as an independent nonprofit. This follows arXiv's spin-out from Cornell University on July 1, 2026, when it became arXiv, Inc., a standalone 501(c)(3) organization. arXiv is a cornerstone of scientific publishing, especially in machine learning and AI, so securing multiyear funding ensures long-term stability for critical research infrastructure that millions of researchers depend on daily. The move toward independent nonprofit status could also serve as a model for how open-access platforms achieve financial sustainability outside of university or commercial control. The $17.2 million commitment is spread over three to five years from three funders: Simons Foundation International, XTX Markets, and Siegel Family Endowment. XTX Markets is a British algorithmic trading firm that uses machine learning for price forecasting, while Simons Foundation International focuses on advancing mathematics and basic sciences research.

reddit · r/MachineLearning · /u/Nunki08 · Sep 24, 09:43

**Background**: arXiv is a free, open-access repository where researchers upload preprints of scientific papers before formal peer review, and it has become the primary venue for sharing AI and machine learning research. It was founded in 1991 and had long been hosted by Cornell University before spinning out as an independent nonprofit on July 1, 2026. Nonprofit status means arXiv must raise its own operating funds through philanthropy, grants, and institutional support rather than relying on a university budget.

<details><summary>References</summary>
<ul>
<li><a href="https://info.arxiv.org/about/spinout_faq.html">arXiv is now an independent nonprofit - arXiv info</a></li>
<li><a href="https://casrai.org/news/arxiv-independent-nonprofit-cornell-spinout">arXiv Spins Out of Cornell as Nonprofit — CASRAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/XTX_Markets">XTX Markets</a></li>

</ul>
</details>

**Tags**: `#arXiv`, `#open-access`, `#research-infrastructure`, `#philanthropy`, `#academic-publishing`

---

<a id="item-12"></a>
## [Pentium II 600MHz with Voodoo 3 Emulated on M6 Mac Mini via 86Box](https://nyaa.sh/reviews/mac-mini-m6-emulation) ⭐️ 6.0/10

A retro-computing enthusiast successfully emulated a Pentium II 600MHz system with a 3dfx Voodoo 3 graphics card on an M6 Mac Mini using the 86Box emulator, as detailed in a review on nyaa.sh. The project demonstrates that modern Apple Silicon hardware can faithfully reproduce late-1990s PC gaming setups. This highlights how far emulation fidelity has come, allowing classic 3D games and hardware to be preserved and enjoyed on modern ARM-based Macs without original hardware. It also fuels nostalgia and community interest in 3dfx and 90s PC gaming culture. 86Box is a low-level x86 emulator that accurately reproduces vintage PC hardware, and the Voodoo 3 emulation includes 3dfx's Glide API support. The M6 Mac Mini's performance is sufficient to run such emulation smoothly, though exact frame rates and compatibility may vary by game.

hackernews · hugh4life · Sep 25, 07:27 · [Discussion](https://news.ycombinator.com/item?id=49841285)

**Background**: 3dfx Interactive was a pioneering American company founded in 1994 that created the Voodoo Graphics card, which brought hardware-accelerated 3D graphics to PC gaming in the mid-1990s. After facing competition from Nvidia and Microsoft's Direct3D, 3dfx went bankrupt in 2002 and its assets were acquired by Nvidia. 86Box is an open-source emulator that lets users run old operating systems and software by emulating x86-based machines from 1981 onward.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/3dfx_Interactive">3dfx Interactive</a></li>
<li><a href="https://86box.net/">86 Box | Emulator of retro x86-based machines</a></li>
<li><a href="https://www.tomshardware.com/picturestory/575-graphics-radeon-geforce.html">The 23 Greatest Graphics Cards Of All Time | Tom's Hardware</a></li>

</ul>
</details>

**Discussion**: Commenters shared nostalgic memories of 3dfx and 3DMark 2000, with one noting they held TDFX shares through bankruptcy and another praising 86Box's fidelity to real Pentium II and Voodoo 3 hardware. A humorous comment asked if it can emulate dual Voodoo II cards with a desk fan, reflecting the quirky passion of the retro community.

**Tags**: `#emulation`, `#retro-computing`, `#86Box`, `#3dfx`, `#hardware`

---

<a id="item-13"></a>
## [Economist: Mafia's Long-Term Business Logic May Keep Fentanyl Out of Italy](https://economist.com/europe/2026/09/24/the-mafia-may-be-keeping-fentanyl-out-of-italy) ⭐️ 6.0/10

An Economist article argues that the Mafia's long-term business perspective may be keeping fentanyl out of Italy, and the piece sparked a Hacker News discussion on drug economics, harm reduction, and illicit market dynamics. The community thread drew on firsthand experience, including wastewater drug monitoring and observations of local drug markets in Quebec. The argument reframes organized crime as a rational economic actor that protects its customer base rather than a purely predatory force, which has implications for drug policy, public health, and how authorities think about supply-side intervention. If criminal groups themselves suppress the most dangerous substances to protect long-term revenue, that complicates simple narratives about cartels and drug markets. Fentanyl is an extremely potent synthetic opioid with a narrow margin between safe and toxic doses, and its metabolites often sit near the detection limit in wastewater testing, meaning absence of detection is not proof of absence. The community also noted that when criminal organizations lose their grip on a market, quality control tends to slip and overdose rates rise, as reportedly happened in Quebec.

hackernews · runeks · Sep 25, 10:20 · [Discussion](https://news.ycombinator.com/item?id=49842487)

**Background**: Fentanyl is a synthetic opioid far more potent than heroin, and small amounts can cause fatal respiratory depression; harm reduction approaches such as drug testing, naloxone distribution, and wastewater monitoring aim to reduce these risks. In Italy, the main criminal organizations control almost all imports of cocaine and heroin, giving them a dominant position in the illicit drug market. The Economist article suggests that this dominant position, combined with a long-term view of customer lifetime value, may explain why fentanyl has not taken hold in Italy the way it has in North America.

<details><summary>References</summary>
<ul>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7233332/">Fentanyl: Receptor pharmacology, abuse potential, and ...</a></li>
<li><a href="https://harmreduction.org/about-us/principles-of-harm-reduction/">Principles - National Harm Reduction Coalition</a></li>
<li><a href="https://dspace.mit.edu/entities/publication/342b56ff-3e91-4545-bddb-e9d806d2963f">Dynamics of the illicit drug market in Italy</a></li>

</ul>
</details>

**Discussion**: Commenters largely agreed with the economic logic, framing it as customer lifetime value: the Mafia protects its customers because it wants recurring revenue, unlike many short-sighted companies. Others pushed back or added nuance, noting that fentanyl is often assumed to be an America-only problem, that wastewater monitoring has detection-limit limitations, and that Quebec's experience shows quality control collapsing when criminal groups lose their grip.

**Tags**: `#economics`, `#public-health`, `#organized-crime`, `#harm-reduction`, `#drug-policy`

---

<a id="item-14"></a>
## [Blog Post Questions Rails' Future, Sparking HN Debate](https://jardo.dev/what-about-rails) ⭐️ 6.0/10

A blog post titled "What About Rails?" questioning the current state and future relevance of Ruby on Rails was published on jardo.dev and subsequently discussed on Hacker News, where it reached 116 points and 64 comments. The discussion expanded beyond the article itself into debates about 37signals' product strategy, open-source governance, and LLM-driven coding practices. Rails has been a foundational web framework for nearly two decades, and renewed debate about its relevance reflects broader questions about whether mature full-stack frameworks can compete with newer tooling and AI-assisted development workflows. The discussion also highlights how influential companies like 37signals shape community expectations around both product design and open-source leadership. Community commenters raised specific points: one noted that 37signals is rewriting Hey as six native apps because web fidelity isn't good enough, while simultaneously the industry pushes API-first and CLI-based interaction; another criticized BDFL culture for creating fork politics when a leader makes controversial decisions. An SRE commenter questioned the emerging stance that developers "don't even necessarily need to read the code the LLMs produce," noting it enables one developer to manage multiple agents but implies a lack of human understanding of the underlying system.

hackernews · jrochkind1 · Sep 25, 02:50 · [Discussion](https://news.ycombinator.com/item?id=49839664)

**Background**: Ruby on Rails is a server-side web application framework written in Ruby under the MIT License, following the model-view-controller (MVC) pattern and providing default structures for databases, web services, and web pages. 37signals is the company behind Basecamp and Hey, and has historically been closely associated with Rails as its creator David Heinemeier Hansson (DHH) is also the framework's creator. BDFL stands for "Benevolent Dictator For Life," a governance model common in open-source projects where a single founder retains final decision-making authority.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ruby_on_Rails">Ruby on Rails - Wikipedia</a></li>
<li><a href="https://rubyonrails.org/">Ruby on Rails: Accelerate your agents with convention over ...</a></li>
<li><a href="https://addyosmani.com/blog/ai-coding-workflow/">My LLM coding workflow going into 2026 | AddyOsmani.com</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed views: some criticized BDFL governance for creating fork politics and questioned whether Hey is truly a marquee product, with one user saying they paid for a "slower, buggier, less feature-rich Gmail." Others debated the trade-offs of LLM-generated code, with an SRE noting that not reading LLM output enables managing multiple agents but sacrifices human understanding, while a Rails maintainer said performance isn't the main motivation to switch but Shopify's native app moves are making them consider it.

**Tags**: `#Ruby on Rails`, `#Web Development`, `#Open Source`, `#AI/LLM`, `#Product Strategy`

---

<a id="item-15"></a>
## [Toyota to Electrify Its Best-Selling Corolla](https://electrek.co/2026/09/23/toyota-best-selling-corolla-electric/) ⭐️ 6.0/10

Toyota is planning to make its best-selling Corolla model electric, according to a report from Electrek. The announcement has sparked a 641-comment Hacker News discussion about EV platform design, charging infrastructure, and consumer preferences. The Corolla is one of the world's highest-volume nameplates, so electrifying it could bring battery-electric driving to a mainstream, price-sensitive audience. It also signals a shift for Toyota, which has long emphasized hybrids over pure EVs and now faces pressure to compete in the mass-market EV segment. It remains unclear whether the electric Corolla will be built on a dedicated EV platform such as e-TNGA or adapted from an existing internal-combustion design, a distinction commenters argue strongly affects the resulting vehicle's quality. Toyota has not yet announced pricing, range, or a launch date for the model.

hackernews · cisc · Sep 23, 22:37 · [Discussion](https://news.ycombinator.com/item?id=49823568)

**Background**: Toyota's TNGA (Toyota New Global Architecture) is a modular platform introduced with the fourth-generation Prius in 2015 that underpins many Toyota and Lexus models across different sizes and drivetrains. A variant called e-TNGA was developed specifically for battery-electric vehicles and is used by the bZ series, Toyota's "beyond Zero" family of EVs introduced in 2021. The Corolla, meanwhile, has traditionally been sold primarily as a gasoline or hybrid vehicle, making a full electric version a notable departure.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Toyota_New_Global_Architecture">Toyota New Global Architecture - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Toyota_bZ">Toyota bZ - Wikipedia</a></li>
<li><a href="https://www.toyota.com/bz/">2027 Toyota bZ | Toyota.com</a></li>

</ul>
</details>

**Discussion**: Commenters were largely skeptical, arguing that EVs designed from the ground up (like the e-TNGA-based bZ models) are far better than EVs shoehorned into internal-combustion designs, citing the mediocre reception of the hybrid-and-EV Lexus ES350e. Others wished for a simple, low-cost, analogue-feeling electric car, questioned what actually makes this a "Corolla" rather than a new model, and noted that apartment dwellers without home charging remain locked out of EV ownership.

**Tags**: `#electric vehicles`, `#Toyota`, `#automotive industry`, `#EV adoption`, `#Hacker News`

---

<a id="item-16"></a>
## [Opus 5.5 Shows Promise for AI-Generated Explainer Videos](https://launchvideo.io/) ⭐️ 6.0/10

A Hacker News post highlights that Anthropic's newly released Claude Opus 5.5 can generate full explainer videos, with community members sharing examples made entirely with the model plus a few dollars of OpenRouter API usage. The thread drew 307 points and 165 comments, mixing enthusiasm with skepticism about the format. This showcases how frontier models like Opus 5.5 are expanding beyond coding and text into end-to-end multimedia production, potentially lowering the barrier for creating marketing and educational content. It also fuels the ongoing debate about whether AI-generated explainer videos add real value or just automate a format many already find annoying. Community members noted that the example videos move too quickly for viewers unfamiliar with the subject, leaving insufficient time to read each slide, though this could likely be fixed with prompt adjustments. One commenter reported that running the same prompt on their own project produced a comparable video for about $4 in API costs.

hackernews · iacguy · Sep 24, 20:28 · [Discussion](https://news.ycombinator.com/item?id=49836374)

**Background**: Claude Opus 5.5 is Anthropic's latest flagship model, positioned as its strongest Opus release yet for long-running agentic tasks, coding, and professional knowledge work, and it reportedly costs 40% less to run than Opus 5 on typical workloads. Explainer videos are short animated or narrated clips that break down a topic, product, or process, and a growing category of AI tools such as Pictory and insMind already automates their creation from text or scripts.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude-opus-5-5">Introducing Claude Opus 5.5 \ Anthropic</a></li>
<li><a href="https://platform.claude.com/docs/en/models/opus-5-5/overview">Claude Opus 5.5 - Claude Platform Docs</a></li>
<li><a href="https://pictory.ai/ai-explainer-video-generator">AI Explainer Video Generator - Pictory.ai</a></li>

</ul>
</details>

**Discussion**: Sentiment was mixed: one commenter dismissed explainer videos as "dark patterns" that replaced written how-to documents to serve ads, while another questioned what is actually gained from the format. Others were impressed by the low cost and speed of generation but found the example videos too fast-paced to be useful, and one developer worried that LLM-wrapping SaaS products may lack real value.

**Tags**: `#AI`, `#video-generation`, `#Opus 5.5`, `#explainer-videos`, `#Hacker News`

---

<a id="item-17"></a>
## [ICLR 2027 Submissions Exposed to Program Committee Members](https://www.reddit.com/r/MachineLearning/comments/1wptsvx/iclr_2027_de_anonymization_d/) ⭐️ 6.0/10

A Reddit post on r/MachineLearning highlights that ICLR 2027 submissions were exposed to program committee members, linking to an OpenReview statement about the incident. The poster asks why this keeps happening to ICLR, pointing to a recurring failure in the conference's double-blind review process. This incident undermines the integrity of double-blind peer review at one of the premier machine learning conferences, potentially biasing acceptance decisions and eroding trust among authors. It affects thousands of researchers who submit to ICLR and raises broader questions about the security of the OpenReview platform used across major AI venues. The exposure was disclosed via an OpenReview forum statement specifically addressing ICLR 2027 submission exposure to program committee members, though the exact number of affected papers and the mechanism of exposure are not detailed in the post. The Reddit discussion is tagged under ICLR, peer-review, anonymity, and community-discussion, indicating it is a community concern rather than a technical breakthrough.

reddit · r/MachineLearning · /u/Striking-Warning9533 · Sep 25, 11:26

**Background**: ICLR (International Conference on Learning Representations) is a leading machine learning conference that uses OpenReview, a platform designed to promote transparency in peer review by capturing submissions, reviews, and decisions. Double-blind review is a standard practice where author identities are hidden from reviewers to reduce bias, and de-anonymization refers to the failure or breach that reveals these identities. ICLR has previously faced similar issues, making this a recurring concern for the community.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/International_Conference_on_Learning_Representations">International Conference on Learning Representations - Wikipedia</a></li>
<li><a href="https://openreview.net/about">About OpenReview</a></li>
<li><a href="https://www.emergentmind.com/topics/openreview-platform">OpenReview: Transparent Peer Review Platform</a></li>

</ul>
</details>

**Discussion**: The Reddit post expresses frustration with the recurring nature of the issue, asking why ICLR specifically keeps experiencing de-anonymization incidents. While the provided content does not include detailed comments, the framing suggests community concern about the reliability of the review process and the platform.

**Tags**: `#ICLR`, `#peer-review`, `#anonymity`, `#conference`, `#community-discussion`

---

<a id="item-18"></a>
## [NeurIPS Accepted Papers Now Visible on Conference Site](https://www.reddit.com/r/MachineLearning/comments/1wp6oi3/neurips_accepted_papers_are_now_visible_r/) ⭐️ 6.0/10

NeurIPS accepted papers have become visible on the conference website, as reported by a Reddit user whose paper was accepted with review scores of 5-4-4, even though no official notification email had yet been received. This is a key moment for the machine learning research community, as authors can now confirm their acceptance status ahead of the official notifications, which affects hiring, travel planning, and publication timelines for thousands of researchers. The paper was accepted with scores of 5-4-4, which is a relatively borderline set of scores, and the author noted that the official notification email is expected to arrive soon.

reddit · r/MachineLearning · /u/levydawg · Sep 24, 16:41

**Background**: NeurIPS (Conference on Neural Information Processing Systems) is one of the most prestigious annual conferences in machine learning and AI, founded in 1987. Papers are evaluated through peer review, with reviewers assigning numeric scores that area chairs use to make acceptance decisions. Accepted papers are typically announced on the conference website around the same time as notification emails are sent to authors.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Conference_on_Neural_Information_Processing_Systems">Conference on Neural Information Processing Systems</a></li>
<li><a href="https://neurips.cc/Conferences/2025">2025 Conference - neurips.cc</a></li>
<li><a href="https://phdflow.ai/guides/neurips-review-scores-explained">NeurIPS review scores: what the numbers actually mean</a></li>

</ul>
</details>

**Tags**: `#NeurIPS`, `#machine learning`, `#academic conferences`, `#peer review`, `#research community`

---

<a id="item-19"></a>
## [Reddit user criticizes AAAI review quality and AI-generated reviews](https://www.reddit.com/r/MachineLearning/comments/1wphteu/whats_up_with_aaai_reviewers_and_organizers_d/) ⭐️ 6.0/10

A Reddit user on r/MachineLearning described their experience reviewing for AAAI, reporting that two of the papers they reviewed received only two-line reviews from other reviewers, with one human review closely resembling an AI-generated review. The user also said AAAI workflow chairs sent emails calling their coauthor "irresponsible" after the user accepted an emergency review invitation, and that no apology or acknowledgment followed. The post adds to growing concerns about peer review quality and the use of AI in reviewing at major machine learning conferences, especially as AAAI-26 received over 30,000 submissions and ran an AI review pilot. If low-effort or AI-generated reviews become common, authors may lose trust in the fairness of conference decisions. The user noted that one reviewed paper did not follow the AAAI template and was unblinded, another was incomplete with missing paragraphs, figures, and code, and a third used LLM-generated math that advanced to the second round despite insufficient references and little exposition. The user's own review of that paper was the longest they wrote, yet it still advanced to Phase 2.

reddit · r/MachineLearning · /u/OutsideSimple4854 · Sep 25, 00:09

**Background**: AAAI is a major artificial intelligence conference that uses a two-phase review process: in Phase 1, each paper is assigned three reviewers, and papers with sufficiently negative reviews may be rejected without further review. AAAI-26 introduced an AI review pilot in which an AI system generated a review for every submission entering the full review phase, and the conference received more than 30,000 initial submissions for 2026, up from about 15,000 for 2025. Concerns about AI-generated reviews have also surfaced at other AI conferences, where a large share of reviews were found to be AI-generated.

<details><summary>References</summary>
<ul>
<li><a href="https://aaai.org/conference/aaai/aaai-26/review-process/">AAAI-26 Review Process - AAAI</a></li>
<li><a href="https://arxiv.org/html/2604.13940">AI-Assisted Peer Review at Scale: The AAAI -26 AI Review Pilot</a></li>
<li><a href="https://www.nature.com/articles/d41586-025-03506-6">Major AI conference flooded with peer reviews written fully ...</a></li>

</ul>
</details>

**Tags**: `#peer-review`, `#AAAI`, `#machine-learning`, `#academic-conferences`, `#AI-review`

---

<a id="item-20"></a>
## [How Much Can a Paper Change Between Acceptance and Camera-Ready?](https://www.reddit.com/r/MachineLearning/comments/1wpjumz/how_much_changes_can_you_make_to_a_paper_between/) ⭐️ 6.0/10

A Reddit user whose paper was accepted to NeurIPS describes making extensive changes before the camera-ready deadline, including rewriting every section except results and conclusion, adding a new theorem with a 9-page proof, and adding roughly 14 extra appendix pages. The author asks the community how much change is acceptable between acceptance and camera-ready, and whether excessive changes could lead to rejection. This question touches on a common but poorly documented norm in machine learning publishing: how much a paper may legitimately evolve after peer review. The answer affects how authors handle rebuttal-driven improvements, resubmission drafts, and the risk of violating conference camera-ready policies. The changes include a restructured paper, a rewritten method section with a pipeline figure, new scaling and smoothing that altered hyperparameters and the sensitivity study graph, a new theorem with a 9-page proof, a one-word title change, and about 5 extra appendix pages requested by reviewers. The author notes the theoretical contribution changed while the method and empirical contributions remained the same.

reddit · r/MachineLearning · /u/d_edge_sword · Sep 25, 01:49

**Background**: In machine learning conferences such as NeurIPS and ICLR, papers go through peer review, and accepted papers must submit a final 'camera-ready' version before the conference. Conference policies generally state that substantial changes to the reviewed paper are not allowed, except for changes that address reviewers' comments and improve the paper. Authors sometimes continue working on a paper after acceptance, for example preparing a resubmission to another conference, which creates tension with these camera-ready rules.

<details><summary>References</summary>
<ul>
<li><a href="https://neurips.cc/Conferences/2025/PaperInformation/NeurIPS-FAQ">NeurIPS 2025 FAQ for Authors</a></li>
<li><a href="https://2025.ieeeicme.org/camera-ready-instructions/">Camera ready instructions – IEEE International Conference on ...</a></li>
<li><a href="https://icpr2026.org/camerareadyInstructions.html">ICPR 2026: Cameraready Instructions | ICPR2026website</a></li>

</ul>
</details>

**Tags**: `#academic publishing`, `#NeurIPS`, `#camera-ready`, `#peer review`, `#research practices`

---

<a id="item-21"></a>
## [NeurIPS 2024 Main Track Decisions Released: 7,900 of 30,709 Accepted](https://www.reddit.com/r/MachineLearning/comments/1wpagoe/neurips_main_track_decision_emails_are_sent_d/) ⭐️ 6.0/10

NeurIPS 2024 Main Track decision emails were sent out, with 7,900 papers accepted out of 30,709 valid submissions, a 25.7% acceptance rate. Among the accepted papers, 112 were selected as orals and 292 as spotlights. NeurIPS is the flagship conference in machine learning, so its acceptance statistics are closely watched by researchers worldwide as a barometer of the field's growth and competitiveness. The results directly affect the careers of thousands of authors and shape which research directions gain visibility in the coming year. The 25.7% acceptance rate is based on 30,709 valid submissions, and only about 1.4% of submissions received the highest honors of oral (112) or spotlight (292) designation. These highlighted papers typically receive longer presentation slots and greater visibility at the conference.

reddit · r/MachineLearning · /u/Invariant_n_Cauchy · Sep 24, 19:02

**Background**: NeurIPS (Conference on Neural Information Processing Systems) was founded in 1987 and is now a multi-track interdisciplinary annual meeting covering machine learning, AI, statistics, and computational neuroscience. Papers accepted to the main track are typically presented as posters, while a small subset is elevated to spotlight or oral presentations based on reviewer and program committee evaluations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Conference_on_Neural_Information_Processing_Systems">Conference on Neural Information Processing Systems</a></li>
<li><a href="https://wiki.eventhosts.cc/topics/main-conference/orals-and-spotlights">Orals and Spotlights - Wiki.EventHosts NeurIPS/ICML/ICLR ...</a></li>

</ul>
</details>

**Tags**: `#NeurIPS`, `#machine-learning`, `#academic-conference`, `#research-community`, `#peer-review`

---