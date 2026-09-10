---
layout: default
title: "Horizon Summary: 2026-09-10 (EN)"
date: 2026-09-10
lang: en
---

> From 40 items, 27 important content pieces were selected

---

1. [DeepSeek Releases V4.1 Flash: 552B MoE Model With MIT License](#item-1) ⭐️ 9.0/10
2. [Automattic Board Forces CEO Matt Mullenweg Into Paid Leave](#item-2) ⭐️ 9.0/10
3. [Calif Research Unveils WeWorm, First Zero-Click WeChat Worm Built with AI](#item-3) ⭐️ 9.0/10
4. [OpenAI Claims Navier–Stokes Breakthrough Amid Priority Dispute](#item-4) ⭐️ 9.0/10
5. [Apple Announces iPhone Duo, Its First Foldable Phone](#item-5) ⭐️ 8.0/10
6. [Interactive Visualization Scales Speed of Light to 5 km/h](#item-6) ⭐️ 8.0/10
7. [Shopify acquires Tailwind Labs, the maker of Tailwind CSS](#item-7) ⭐️ 8.0/10
8. [Raschka Explains Looped Transformers and Hidden Reasoning Amid GPT-6 Astra Rumors](#item-8) ⭐️ 8.0/10
9. [Formally Verified Polynomial Evaluation with Half the Multiplications](#item-9) ⭐️ 8.0/10
10. [Qwen 3.8 Distillation Detected via Recovered GPT-5.5 Pro Reasoning Prefills](#item-10) ⭐️ 8.0/10
11. [Terence Tao Warns AI Could End Open Science in Mathematics](#item-11) ⭐️ 8.0/10
12. [Intro Explainer on Visa and Mastercard Card Networks Sparks Debate](#item-12) ⭐️ 7.0/10
13. [IEEE Spectrum argues autonomous cars save lives, sparking debate](#item-13) ⭐️ 7.0/10
14. [Desert Ant Labs launches on-device AI models with free tier up to 100k devices](#item-14) ⭐️ 7.0/10
15. [OpenAI Releases ChatGPT Images 2.5 with Two New API Models](#item-15) ⭐️ 7.0/10
16. [Anthropic Allegedly Building Predictive Surveillance System to Monitor Activists](#item-16) ⭐️ 7.0/10
17. [Anthropic Calls 'Double-Check Your Work' an Anti-Pattern for Modern Models](#item-17) ⭐️ 7.0/10
18. [Anthropic Researcher Resigns, Accuses Anthropic and OpenAI of 'Gambling With Our Lives'](#item-18) ⭐️ 7.0/10
19. [Spotify's Portal Plugins Cut Claude Code Costs by 90%](#item-19) ⭐️ 7.0/10
20. [Windows XP's initial user picture algorithm revealed by Raymond Chen](#item-20) ⭐️ 6.0/10
21. [Nine streaming subscriptions now cost $702/year more than in 2021](#item-21) ⭐️ 6.0/10
22. [No Man's Sky Cosmos Update Marks 10th Anniversary](#item-22) ⭐️ 6.0/10
23. [Apple Announces AirPods 5 With Open-Ear ANC](#item-23) ⭐️ 6.0/10
24. [Apple Debuts iPhone 18 Pro with 2nm A20 Pro and Signed-Sensor Photo Authenticity](#item-24) ⭐️ 6.0/10
25. [Terence Tao Reflects on Childlike Curiosity and AI](#item-25) ⭐️ 6.0/10
26. [Personal essay laments the modern internet's decline, sparks HN debate](#item-26) ⭐️ 6.0/10
27. [Claude Code reportedly burns 50 million tokens on a simple Markdown check](#item-27) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [DeepSeek Releases V4.1 Flash: 552B MoE Model With MIT License](https://twitter.com/deepseek_ai/status/2097930608790167907) ⭐️ 9.0/10

DeepSeek released DeepSeek-V4.1-Flash, a 552B-parameter multimodal Mixture-of-Experts model with up to 1M token context, published on Hugging Face under the MIT license alongside a detailed technical report. The model is now live on the DeepSeek API with lower prices and native multimodal support, and tests by multiple parties put it ahead of V4-Pro on performance, cost, speed, and total runtime. The release is notable because DeepSeek pairs near-frontier scale with an unusually detailed technical report and permissive MIT licensing, raising the bar for transparency among major AI labs. Its lower API prices and strong benchmark gains also make it a compelling option for developers seeking a cost-effective alternative or backup model. The model uses an asymmetric MoE architecture with a smaller KV cache for greater efficiency, and the previous v4-flash and v4-flash-vision-exp endpoints temporarily route to V4.1-Flash for compatibility. At 552B parameters it is nearly twice the size of the original 284B v4-flash, which makes local deployment much harder despite the 'Flash' name.

hackernews · Liwink · Sep 10, 06:11 · [Discussion](https://news.ycombinator.com/item?id=49639090)

**Background**: DeepSeek is a Chinese AI lab known for releasing open-weight large language models with strong performance and detailed research disclosures. Mixture-of-Experts (MoE) models activate only a subset of parameters per token, allowing large total parameter counts while keeping inference costs lower. The 'Flash' branding typically signals a faster, cheaper variant, and the MIT license allows broad commercial and research use.

<details><summary>References</summary>
<ul>
<li><a href="https://www.deepseek.com/en/news/deepseek-v4-1-flash/">Introducing DeepSeek - V 4 . 1 - Flash : smarter, faster, more efficient.</a></li>
<li><a href="https://deepinfra.com/deepseek-ai/DeepSeek-V4.1-Flash">DeepSeek V4.1 Flash API - Demo - DeepInfra</a></li>
<li><a href="https://www.orcarouter.ai/blog/deepseek-v4-1-flash-leak">DeepSeek V 4 . 1 Flash Goes GA: 552B, MIT Weights, 1M Context</a></li>

</ul>
</details>

**Discussion**: Commenters widely praised DeepSeek's technical report for its depth and transparency, contrasting it favorably with Anthropic's safety-heavy system cards, and many called DeepSeek the best AI lab in the world. Some raised practical concerns that at 552B parameters the model is no longer realistically local-friendly, and others highlighted its lower prices as making it an excellent backup model.

**Tags**: `#DeepSeek`, `#LLM`, `#model release`, `#AI research`, `#open source`

---

<a id="item-2"></a>
## [Automattic Board Forces CEO Matt Mullenweg Into Paid Leave](https://techcrunch.com/2026/09/09/automattics-board-forces-ceo-matt-mullenweg-into-leave-of-absence/) ⭐️ 9.0/10

Automattic's board of directors voted to place founder and CEO Matt Mullenweg on a paid leave of absence against his will, as he announced in a company-wide Slack message. Mullenweg said CFO Mark Davies conspired with board members Ann Dunwoody, Toni Schneider, and Sue Decker behind his back, and that he voted against the decision. Automattic is the parent company of WordPress.com and a major contributor to the WordPress open-source project, which powers a large percentage of the web, so a forced leadership change could reshape the governance and direction of a critical piece of internet infrastructure. The move also raises questions about how much control Mullenweg still retains over the broader WordPress ecosystem. Mullenweg framed the move as a conspiracy by named board members and the CFO, and he noted he voted against it, signaling a likely escalation rather than a quiet transition. The leave is paid, and no interim CEO or return timeline was specified in the announcement.

hackernews · LeoPanthera · Sep 9, 23:49 · [Discussion](https://news.ycombinator.com/item?id=49636283)

**Background**: Matt Mullenweg co-founded WordPress in 2003 and founded Automattic in 2005; the company runs WordPress.com and contributes heavily to the open-source WordPress software. WordPress is a free, open-source content management system maintained by a global community, and it powers a very large share of websites worldwide. Because of his dual role as Automattic CEO and a central figure in the WordPress project, Mullenweg has long held unusual influence over both the commercial and community sides of the ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/09/09/automattics-board-forces-ceo-matt-mullenweg-into-leave-of-absence/">Automattic's board forces CEO Matt Mullenweg into leave of ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Matt_Mullenweg">Matt Mullenweg</a></li>
<li><a href="https://en.wikipedia.org/wiki/Automattic">Automattic - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters largely saw the board's move as difficult but necessary, with one noting WordPress powers a large share of the internet and that Mullenweg's recent tenure was marked by repeated unforced errors. Others warned that Mullenweg retains a stranglehold on Automattic and WordPress and is likely to retaliate against the board, predicting the situation will get worse before it improves. A few found dark humor in the reported timing around his annual Burning Man trip.

**Tags**: `#Automattic`, `#WordPress`, `#leadership`, `#open-source`, `#corporate-governance`

---

<a id="item-3"></a>
## [Calif Research Unveils WeWorm, First Zero-Click WeChat Worm Built with AI](https://simonwillison.net/2026/Sep/10/calif-research/) ⭐️ 9.0/10

Calif Research released a demo of WeWorm, described as the first zero-click worm that spreads through WeChat voice calls on both iOS and Android. The team says it found the bug and wrote the first remote code execution (RCE) exploit in about two days with AI assistance, then built the worm in one more week. This is a significant security disclosure because a zero-click worm that spreads through a widely used messaging app could compromise accounts at massive scale without any user action. It also signals a paradigm shift in AI-assisted vulnerability discovery and exploit development, lowering the time and team size needed to build serious attacks. The victim does not need to answer the call or interact with the phone at all, and even if they answer, they hear nothing while the exploit still succeeds. According to coverage, WeWorm exploits a memory corruption flaw in WeChat's VoIP stack and Calif reported the bug to the vendor.

rss · Simon Willison · Sep 10, 00:56

**Background**: A zero-click exploit is one that works without any action from the victim, making it far more dangerous than attacks that require a link click or file download. A worm is malware that self-propagates by infecting new victims through trusted contacts or services, and remote code execution (RCE) means an attacker can run their own code on a target device over a network. WeChat is a messaging app with over a billion users, and its voice-call feature relies on VoIP (Voice over IP) software that processes network data and can contain memory-safety bugs.

<details><summary>References</summary>
<ul>
<li><a href="https://cybersecuritynews.com/weworm-first-0-click-worm/">WeWorm – First 0-Click Worm Spreading Through WeChat Calls ...</a></li>
<li><a href="https://www.techtimes.com/articles/327153/20260910/wechat-zero-click-worm-built-ai-days-voip-bug-put-billion-accounts-risk.htm">WeChat Zero-Click Worm Built by AI in Days: VoIP Bug Put ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Arbitrary_code_execution">Arbitrary code execution - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#security`, `#AI`, `#mobile`, `#zero-click`, `#exploit`

---

<a id="item-4"></a>
## [OpenAI Claims Navier–Stokes Breakthrough Amid Priority Dispute](https://simonwillison.net/2026/Sep/8/on-navier-stokes/) ⭐️ 9.0/10

OpenAI announced on September 8, 2026 that an unreleased internal model, using a swarm of roughly 10,000 AI agents, produced a counterexample resolving the Navier–Stokes existence and smoothness problem, one of the seven Millennium Prize Problems, with Lean formalization completed by GPT-6 Astra. The claim is overshadowed by a priority dispute: NYU professor Tristan Buckmaster and Anthropic employee Levent Alpöge say they had reached closely related results on August 15 after nearly a year of work using Claude and Codex, and Buckmaster accuses OpenAI of launching its effort only after hearing about their work and of refusing to clarify whether the model was trained on their private Codex sessions. If verified, this would be only the second Millennium Prize Problem ever solved and the first major mathematical breakthrough attributed primarily to AI agents, potentially reshaping how frontier mathematics is done. The dispute also raises urgent questions about research ethics, data provenance, and whether AI companies can fairly claim credit when their models may have been trained on competitors' private work. OpenAI says its agents resolved the problem on September 5, about 88 hours after launch, sending 2.7 million messages and consuming roughly 130 billion output tokens for Navier–Stokes alone (about 300 billion tokens across all attempted problems, which at public GPT-6 Astra API prices would cost around $15 million). The counterexample builds on a 2023 blowup method by Diego Córdoba and Luis Martínez-Zoroa, has not been verified by external mathematicians or the Clay Mathematics Institute, and OpenAI stated it would not claim the $1 million prize.

rss · Simon Willison · Sep 8, 23:55

**Background**: The Navier–Stokes equations are partial differential equations describing fluid motion; the Millennium Problem asks whether smooth solutions always exist in three-dimensional space for all time, or whether they can break down (blow up). In 2000 the Clay Mathematics Institute named it one of seven Millennium Prize Problems, each carrying a $1 million award, and only the Poincaré conjecture has been officially solved so far. AI agents here are autonomous systems that iteratively generate and check mathematical arguments, with Lean serving as a proof assistant that mechanically verifies each step.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Navier-Stokes_existence_and_smoothness_problem">Navier-Stokes existence and smoothness problem</a></li>
<li><a href="https://en.wikipedia.org/wiki/Millennium_Prize_Problems">Millennium Prize Problems</a></li>
<li><a href="https://www.indiatimes.com/trending/who-is-tristan-buckmaster-nyu-mathematician-at-centre-of-openai-navier-stokes-controversy-over-private-codex-logs-and-research-credit/articleshow/133954116.html">Who is Tristan Buckmaster ? NYU mathematician at centre of...</a></li>

</ul>
</details>

**Discussion**: Commentary centers on the ethics of the race: many question whether OpenAI's model was trained on Buckmaster and Alpöge's private Codex sessions, and criticize OpenAI's refusal to invite Alpöge as a co-author because he works for Anthropic. Others note the result remains unverified and that the $15 million token cost underscores how resource-intensive AI-driven mathematics has become.

**Tags**: `#AI`, `#mathematics`, `#Millennium Prize`, `#OpenAI`, `#research ethics`

---

<a id="item-5"></a>
## [Apple Announces iPhone Duo, Its First Foldable Phone](https://www.apple.com/iphone-duo/) ⭐️ 8.0/10

Apple has announced the iPhone Duo, its first foldable phone, according to a page on Apple's website. The announcement has sparked extensive community debate about the device's design, utility, and its potential to drive foldable app development. Apple's entry into the foldable phone market is a significant industry development, as it could legitimize the category and push developers to build apps optimized for foldable screens. It also puts pressure on Android foldable makers and signals a new direction for Apple's flagship hardware lineup. Community members report that hands-on videos show no visible crease on the display, and some suggest Apple's presentation did not do the device justice. Others note that current foldable apps on Android are often broken or merely stretched, highlighting the need for better foldable app design.

hackernews · thecosmicfrog · Sep 9, 18:15 · [Discussion](https://news.ycombinator.com/item?id=49630931)

**Background**: Foldable phones are devices with flexible displays that can bend or unfold to provide a larger screen, a category pioneered by companies like Samsung and Google. Apple has historically been late to adopt new hardware form factors, preferring to wait until the technology matures. The iPhone Duo marks Apple's first entry into this market, and its success could influence how apps are designed for foldable screens across platforms.

**Discussion**: The Hacker News discussion is highly active and diverse. Some commenters praise the Duo's design and lack of crease, while others question the demand for a foldable phone and find it neither pretty nor functional. A recent Android foldable owner is excited that Apple's entry will push developers to properly design apps for foldables, and another commenter plans to wait for future versions before switching.

**Tags**: `#Apple`, `#foldable phones`, `#iPhone`, `#mobile hardware`, `#tech industry`

---

<a id="item-6"></a>
## [Interactive Visualization Scales Speed of Light to 5 km/h](https://rivendell.dmitrybrant.com/relativity/) ⭐️ 8.0/10

Developer Dmitry Brant released an interactive web visualization that scales the speed of light down to 5 km/h, allowing users to experience relativistic effects like time dilation and length contraction with everyday objects. The project, shared on Hacker News as 'Show HN: What if the speed of light was 5 km/h?', quickly gained 418 points and 166 comments. This tool makes abstract relativistic physics intuitive by mapping the cosmic speed limit to human-scale speeds, potentially improving physics education and public understanding of special relativity. It also invites comparison with prior efforts like MIT's 'Slower Speed of Light' game, highlighting ongoing interest in interactive science communication. The visualization runs in a web browser and simulates effects such as relativistic Doppler shift and time dilation, but community members noted it may omit subtle phenomena like Thomas rotation (the rotation of a moving object's orientation under successive non-parallel boosts). The author describes it as a first version, implying potential updates.

hackernews · dmitrybrant · Sep 10, 01:58 · [Discussion](https://news.ycombinator.com/item?id=49637385)

**Background**: Special relativity predicts that as an object approaches the speed of light (about 299,792 km/s), time slows down and lengths contract relative to a stationary observer. These effects are negligible at everyday speeds, so scaling the speed of light down to 5 km/h makes them perceptible in a virtual environment. The project builds on a tradition of interactive relativity demonstrations, including MIT's 2012 game 'Slower Speed of Light'.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Relativistic_effects">Relativistic effects</a></li>
<li><a href="https://www.jalopnik.com/this-scale-visualization-of-the-speed-of-light-fill-you-1843997468/">Let This Scale Visualization Of The Speed Of Light Fill You With...</a></li>

</ul>
</details>

**Discussion**: Commenters praised the visualization as more accurate than MIT's 'Slower Speed of Light', though some pointed out missing effects like Thomas rotation and questioned whether changing the speed of light would alter atomic sizes. Others shared philosophical reflections on the slowness of light on cosmic scales, such as the 2.5-million-year journey to Andromeda even at near-light speed.

**Tags**: `#relativity`, `#visualization`, `#physics`, `#interactive`, `#education`

---

<a id="item-7"></a>
## [Shopify acquires Tailwind Labs, the maker of Tailwind CSS](https://tailwindcss.com/blog/tailwind-is-joining-shopify) ⭐️ 8.0/10

Shopify has acquired Tailwind Labs, the company behind the widely used Tailwind CSS utility-first framework, as announced on the official Tailwind blog. The acquisition comes after Tailwind Labs reportedly saw an 80% drop in revenue and laid off 75% of its engineering team due to AI's impact on documentation traffic. This is a major acquisition of a widely-used open-source CSS framework by a large e-commerce platform, raising questions about the sustainability of open-source projects whose business models depend on documentation traffic. It also highlights how AI coding assistants are disrupting developer tooling companies by answering questions directly instead of sending users to documentation sites. Tailwind CSS is an open-source utility-first CSS framework that, unlike Bootstrap, does not provide predefined component classes but instead lets developers compose small utility classes like flex, pt-4 and text-center directly in markup. Community discussion noted that Tailwind Labs' documentation traffic fell roughly 40-50% from early 2023 despite the framework being more popular than ever, and that AI agents now account for a large share of documentation site traffic.

hackernews · EdwinHoksberg · Sep 9, 13:27 · [Discussion](https://news.ycombinator.com/item?id=49626190)

**Background**: Tailwind CSS is a popular open-source CSS framework that uses a utility-first approach, meaning developers style elements by combining small single-purpose classes rather than writing custom CSS or using prebuilt components. Tailwind Labs is the company that created and maintains the framework, and its business model has relied heavily on traffic to its documentation site. In recent years, AI coding assistants and agents have increasingly answered developers' questions directly, reducing visits to documentation pages and threatening the revenue of documentation-driven developer tools.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tailwind_CSS">Tailwind CSS - Wikipedia</a></li>
<li><a href="https://grokipedia.com/page/Tailwind_Labs">Tailwind Labs</a></li>
<li><a href="https://www.mintlify.com/blog/ai-traffic">Almost half your docs traffic is AI, time to understand the agent experience</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed reactions: some questioned whether Tailwind is still necessary for new sites given modern vanilla CSS and AI-assisted editing, while others criticized the framework's compatibility with older devices. Several users also reacted with surprise or skepticism about Shopify's involvement, and one commenter shared context showing that AI-driven documentation traffic decline led to major layoffs at Tailwind Labs.

**Tags**: `#Tailwind CSS`, `#Shopify`, `#acquisition`, `#AI impact`, `#web development`

---

<a id="item-8"></a>
## [Raschka Explains Looped Transformers and Hidden Reasoning Amid GPT-6 Astra Rumors](https://magazine.sebastianraschka.com/p/gpt-6-astra-looped-transformers-and) ⭐️ 8.0/10

Sebastian Raschka published a technical deep-dive explaining that the 'recurrent depth' or 'looped transformer' technique reportedly used by OpenAI's GPT-6 Astra is simply reusing transformer layers with shared weights, not a novel secret method for hiding reasoning. The article responds to a recent 'The Information' report that framed the technique as making chain-of-thought monitoring harder. The clarification matters because it corrects a misconception that could mislead the AI safety and interpretability community about how models like GPT-6 Astra actually work, and it highlights that true hidden reasoning comes from recursive latent reasoning rather than layer looping. This distinction affects how researchers approach monitoring and understanding LLM internals. Looped transformers reuse a fixed set of transformer blocks iteratively over the same latent representation, saving GPU memory compared to stacking more layers, and they are equivalent to deeper models in function. Hidden reasoning, by contrast, involves computation in activation space without appearing in the chain-of-thought, such as partial verbalization or hidden utilization of test-time compute.

hackernews · ModelForge · Sep 9, 14:37 · [Discussion](https://news.ycombinator.com/item?id=49627370)

**Background**: GPT-6 Astra is a large language model developed by OpenAI, initially released to approved users on September 3, 2026, with general availability the following day. Looped transformers are a parameter-efficient, recursion-based variant of standard deep transformers in which a fixed set of blocks is applied iteratively. Hidden reasoning refers to important reasoning steps computed in activation space without being verbalized in the chain-of-thought, a topic of growing interest in LLM interpretability.

<details><summary>References</summary>
<ul>
<li><a href="https://sebastianraschka.com/blog/2026/openai-astra-looped-transformers.html">OpenAI Astra and Looped Transformers | Sebastian Raschka, PhD</a></li>
<li><a href="https://www.alignmentforum.org/posts/ZrgFfeWuckpwK5Lyi/hidden-reasoning-in-llms-a-taxonomy">Hidden Reasoning in LLMs : A Taxonomy — AI Alignment Forum</a></li>
<li><a href="https://en.wikipedia.org/wiki/GPT-6_Astra">GPT-6 Astra</a></li>

</ul>
</details>

**Discussion**: Commenters largely agreed with Raschka's clarification, with one noting that looping a transformer is by definition hidden reasoning if the output trace is fed back into the model, while another pointed to Will Merrill's research on computational problems and CoT requirements. A key question raised was whether any major lab uses recursive latent reasoning and whether an additional network could decipher the latent thinking trace.

**Tags**: `#LLM`, `#transformers`, `#interpretability`, `#reasoning`, `#AI research`

---

<a id="item-9"></a>
## [Formally Verified Polynomial Evaluation with Half the Multiplications](https://thomasahle.com/fast-polynomials/) ⭐️ 8.0/10

Thomas Ahle and a coauthor have published a new method for evaluating polynomials that uses roughly half the multiplications of standard approaches, now backed by a complete Lean proof after years of uncertainty about a 100-page paper proof. An interactive website lets users compare the method against Horner, Estrin, and other classical schemes on their own polynomials. Polynomial evaluation is a core primitive in hashing, cryptography, error-correcting codes, and numerical computing, so halving the multiplication count could translate into meaningful speedups in those areas. The formal Lean verification also raises confidence in a result that was previously too complex to trust by hand, and the interactive demo lowers the barrier for practitioners to test applicability. The method is particularly attractive in finite fields, where the reduced multiplication count matters most, though community members note that coefficients can blow up quickly over the rationals. The demo supports switching between algorithms and monic or non-monic polynomials, and open questions remain about how the method maps onto fused multiply-add (FMA) operation counts compared to Horner.

hackernews · thomasahle · Sep 9, 08:53 · [Discussion](https://news.ycombinator.com/item?id=49623398)

**Background**: Evaluating a polynomial at a point is one of the most common operations in computer science. Horner's method is the classic approach, using one multiplication and one addition per coefficient, while Estrin's scheme trades more multiplications for parallelism. Lean is a dependently typed proof assistant that lets mathematicians write machine-checkable proofs, so a full Lean proof means the correctness argument has been verified by computer rather than only by human review.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Horner's_method">Horner's method - Wikipedia</a></li>
<li><a href="https://www.wikiwand.com/en/Estrin's_scheme">Estrin ' s scheme - Wikiwand</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lean_(proof_assistant)">Lean (proof assistant) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters were enthusiastic, with one asking whether the method could speed up the algebraic k-path algorithm and suggesting entry into the PACE challenge. Others raised practical concerns: coefficient blow-up over the rationals, a UI quirk where the demo flips back to 'monic', and curiosity about how the method and Horner compare in FMA operation counts.

**Tags**: `#polynomial-evaluation`, `#formal-verification`, `#lean`, `#algorithms`, `#hashing`

---

<a id="item-10"></a>
## [Qwen 3.8 Distillation Detected via Recovered GPT-5.5 Pro Reasoning Prefills](https://gist.github.com/wsxiaoys/e0286dc6bb624ff5fdf49e7f4c528ba3) ⭐️ 8.0/10

A GitHub gist and Hacker News discussion describe a technique for detecting distillation in open-source models by recovering reasoning prefills from proprietary models such as GPT-5.5 Pro and feeding the first ~1% of that chain-of-thought into an open-source model like Qwen 3.8 as if it were the start of the model's own reasoning. The method builds on prior work that recovered readable chain-of-thought from OpenAI and Anthropic APIs, and commenters note that Qwen 3.8 0902 was trained after the relevant paper appeared on August 10, so it could plausibly have seen those specific traces. If distillation from proprietary frontier models can be reliably detected, it raises major questions about the provenance, licensing, and trustworthiness of open-weight models, and could affect how labs like Alibaba's Qwen team are perceived in the open-source ecosystem. It also matters for anyone relying on open models for research or products, since hidden distillation may carry legal and reproducibility risks. The technique relies on access to raw reasoning tokens rather than just summarized outputs, and commenters debate whether such raw chain-of-thought is actually exposed by APIs or whether the authors had privileged access. A key caveat is that the only GPT-5.5 Pro thoughts available may come from the 'stolen thoughts' exploit, so overlap between Qwen and GPT outputs could also reflect shared training data or common solutions rather than deliberate distillation.

hackernews · wsxiaoys · Sep 9, 17:24 · [Discussion](https://news.ycombinator.com/item?id=49630026)

**Background**: Knowledge distillation is a common technique in which a smaller 'student' model is trained to imitate the outputs or internal representations of a larger 'teacher' model, often to compress capability into a cheaper model. In large language models, reasoning models produce chain-of-thought tokens before their final answer, and recent research has shown that portions of these traces can sometimes be recovered from proprietary APIs. Qwen is Alibaba Cloud's family of predominantly open-weight models, with Qwen 3.8 being a recent large release, making it a natural candidate for distillation-detection studies.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2607.09692v1">Reference-Based Distillation Detection in LLMs</a></li>
<li><a href="https://arxiv.org/pdf/2608.09867">Stealing Reasoning Traces from Proprietary LLM APIs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen</a></li>

</ul>
</details>

**Discussion**: Commenters were fascinated but divided: one shared a personal anecdote about peeking at Gemini's reasoning tokens and finding an anxious, people-pleasing inner monologue, while others questioned whether raw reasoning tokens are actually accessible or whether the authors had privileged access. Several raised the counterargument that overlap between Qwen and GPT outputs might simply reflect training on the same solutions or public data, and one noted that Qwen 3.8 0902 was trained after the stolen-thoughts paper appeared, so it could have seen those traces.

**Tags**: `#AI`, `#model distillation`, `#reasoning tokens`, `#LLM`, `#research`

---

<a id="item-11"></a>
## [Terence Tao Warns AI Could End Open Science in Mathematics](https://simonwillison.net/2026/Sep/9/terence-tao/) ⭐️ 8.0/10

Terence Tao, one of the world's leading mathematicians, warned in a Mastodon post that AI-powered problem-solving is now so fast that even the rumor of someone working on an open problem can trigger a massive effort to "flatten" it before the original research reaches its full potential. He argues this could reverse centuries of open-science tradition, as researchers may stop sharing promising research directions to avoid being scooped. Tao's warning highlights a structural risk to open science: if sharing a good problem guarantees it will be rapidly solved by AI, the incentive to publish open problems — the very fuel of mathematical progress — may disappear. This could affect not only mathematics but any research field where AI can quickly exhaust shared open questions. Tao describes good open problems as a scarce, non-renewable resource that is being "mined" faster than new ones can be identified, and notes that AI effort can be triggered merely by the rumor of someone working on a problem, before the original project matures. The concern is about incentives rather than any specific AI system or result.

rss · Simon Willison · Sep 9, 00:20

**Background**: In mathematics, open problems are unsolved questions that guide research; the culture of publicly sharing them has driven progress for centuries. Recent AI systems have become increasingly capable at mathematical reasoning and problem-solving, prompting mathematicians like Tao to examine how AI changes research incentives and norms. Tao has previously written about open problems being mined in a non-renewable fashion, and this quote extends that argument to the sharing culture itself.

<details><summary>References</summary>
<ul>
<li><a href="https://ai-tldr.dev/releases/terry-tao-mined-open-problems-sep8/">Terence Tao — good open math problems are a… | AI/TLDR</a></li>
<li><a href="https://decrypt.co/377818/ai-math-best-problems-terence-tao">AI Is Solving Math's Best Problems Faster Than They Can Be Replaced, Terence Tao Warns - Decrypt</a></li>
<li><a href="https://simonwillison.net/2026/Sep/9/terence-tao/">A quote from Terence Tao</a></li>

</ul>
</details>

**Tags**: `#ai-ethics`, `#mathematics`, `#open-science`, `#research-culture`, `#ai-impact`

---

<a id="item-12"></a>
## [Intro Explainer on Visa and Mastercard Card Networks Sparks Debate](https://tautology.town/2026/06/01/card-networks.html) ⭐️ 7.0/10

A new introductory article on tautology.town explains what Visa and Mastercard actually do as card networks, distinguishing them from card issuers and acquirers. The piece reached the front page of Hacker News with 569 upvotes and 347 comments, where readers debated interchange fees, merchant costs, and payment data practices. Card networks sit at the center of nearly every consumer payment, so understanding their fee structures and data practices matters for merchants, fintech builders, and regulators alike. The discussion highlights growing friction over interchange fees that can reach 3-5% of a merchant's revenue, a cost that increasingly gets passed to consumers. Commenters cited concrete figures: Visa transactions cost about €0.22 per €1 payment, Mastercard about €0.23, and the French CB network about €0.17. One commenter also raised the claim that merchants are offered lower processing fees in exchange for transmitting detailed purchase data that could be resold to advertisers.

hackernews · evakhoury · Sep 8, 18:11 · [Discussion](https://news.ycombinator.com/item?id=49614280)

**Background**: Visa and Mastercard are card networks, not banks: they operate the rails that route payment authorization and settlement between a customer's issuing bank and a merchant's acquiring bank. They earn revenue largely through fees such as interchange, which is set by the networks and paid by the acquirer to the issuer, plus assessments paid to the network itself. Because these fees are baked into the price of goods, consumers often pay for card rewards indirectly, which is why the topic is perennially contentious.

<details><summary>References</summary>
<ul>
<li><a href="https://stripe.com/ie/resources/more/interchange-fees-101-what-they-are-how-they-work-and-how-to-cut-costs">Interchange Fees 101: What They Are And How They Work | Stripe</a></li>
<li><a href="https://www.airwallex.com/en-eu/blog/interchange-fees-explained">Interchange Fees : What They Are & How They Work | Airwallex EU</a></li>
<li><a href="https://solidgate.com/blog/interchange-fees-explained/">Interchange fees explained : what merchants need to know</a></li>

</ul>
</details>

**Discussion**: Sentiment was broadly critical of the card network model. Several commenters said credit card rewards encourage overspending, one noted that merchants are charged 3-5% of revenue and increasingly pass card fees to customers, and another questioned why per-transaction costs remain so high despite global scale. A recurring concern was the potential resale of detailed purchase data to advertisers.

**Tags**: `#fintech`, `#payments`, `#card-networks`, `#visa`, `#mastercard`

---

<a id="item-13"></a>
## [IEEE Spectrum argues autonomous cars save lives, sparking debate](https://spectrum.ieee.org/are-self-driving-cars-safe) ⭐️ 7.0/10

An IEEE Spectrum article titled 'Are Self-Driving Cars Safe?' compiles data arguing that autonomous vehicles reduce fatalities compared to human drivers, and it drew 376 points and 650 comments on Hacker News. Commenters scrutinized the statistics, noting that Waymo compares its crash rates to average drivers rather than the rideshare drivers its vehicles actually replace. The debate matters because autonomous vehicle safety data is increasingly used to justify regulatory approval and public trust, yet the choice of baseline (average driver vs. rideshare driver vs. public transit) can dramatically change how impressive the numbers look. It also raises broader questions about whether AV investment should compete with or complement public transit funding. According to mandatory Autonomous Vehicle Collision Reports, autonomous test vehicles were involved in 132 collisions in 2023, a crash rate of 14.6 per million vehicle miles, but reporting varies widely across companies and disengagement data is inconsistent. Commenters also noted that fatality data is heavily skewed by factors like seatbelt non-use (44%), speeding (29%), alcohol involvement (~30%), and vulnerable road users such as pedestrians and cyclists (about 20% of fatalities).

hackernews · bookofjoe · Sep 9, 17:14 · [Discussion](https://news.ycombinator.com/item?id=49629886)

**Background**: Autonomous vehicles are tested on public roads under state regulations, and companies like Waymo publish safety data comparing their crash rates to human drivers. In California, the DMV requires companies to report 'disengagements' — when the autonomous system is deactivated because of a failure or because safe operation requires a human to take over — but definitions and reporting practices vary, making comparisons difficult. The debate over AV safety is intertwined with transportation policy, as cities and federal agencies weigh whether to fund self-driving pilots or traditional public transit.

<details><summary>References</summary>
<ul>
<li><a href="https://www.statista.com/chart/32985/collisions-crashes-per-motor-vehicle-vehicle-miles-traveled-by-type-of-vehicle/">Chart: The State of Autonomous Vehicle Safety | Statista</a></li>
<li><a href="https://spectrum.ieee.org/have-selfdriving-cars-stopped-getting-better">Have Self-Driving Cars Stopped Getting Better? - IEEE Spectrum</a></li>
<li><a href="https://www.governing.com/transportation/will-self-driving-cars-short-circuit-urban-public-transit">Will Self-Driving Cars Short-Circuit Urban Public Transit?</a></li>

</ul>
</details>

**Discussion**: Commenters broadly agreed that AVs can reduce crashes but challenged the framing: some argued that better driver education, higher test standards, and alcohol bans would also save lives but lack societal buy-in, while others said the resources going into AVs would be better spent on public transit, biking, and walking infrastructure. Several noted that AVs are an 'additive' rather than 'subtractive' solution, and that fatality statistics are skewed by seatbelt non-use, speeding, alcohol, and vulnerable road user deaths.

**Tags**: `#autonomous vehicles`, `#road safety`, `#public transit`, `#technology policy`, `#data analysis`

---

<a id="item-14"></a>
## [Desert Ant Labs launches on-device AI models with free tier up to 100k devices](https://desertant.com/blog/introducing-desert-ant-labs/) ⭐️ 7.0/10

Desert Ant Labs has launched a platform for local, fast AI models that run entirely on-device, offering free usage up to 100,000 monthly active devices with no tokens or logins required. The company provides SDKs for Swift, Kotlin, and JavaScript, targeting phones, tablets, and laptops rather than cloud servers. This represents a notable shift in the local AI space, where running models on-device eliminates per-call cloud costs, round-trip latency, and data privacy concerns. It could affect developers building mobile and edge applications who want AI capabilities without recurring cloud billing or sending user data off-device. The free tier covers up to 100k monthly active devices with no token-based billing, and the SDKs target Swift, Kotlin, and JavaScript. However, community members noted that many models appear iOS-only, benchmarks run on modern iPhones, and a Python SDK is not yet available, which limits web and server-side use cases.

hackernews · willwhitedc · Sep 9, 11:39 · [Discussion](https://news.ycombinator.com/item?id=49624823)

**Background**: On-device AI refers to running machine learning models directly on a user's phone, tablet, or laptop instead of sending requests to cloud servers, which is a form of edge computing that brings computation closer to where data is generated. Local LLMs are models deployed and executed on local hardware, offering privacy and lower latency but typically constrained by device memory and compute. Desert Ant Labs is positioning itself in this space by shipping small, task-specific models optimized for the chips already present in most modern devices.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Edge_computing">Edge computing</a></li>
<li><a href="https://scrapfly.io/blog/posts/guide-to-local-llm">Guide to Local LLMs</a></li>
<li><a href="https://on-device.app/">On Device AI — Powerful AI , 100% Private</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (461 points, 97 comments) was broadly positive about the technical approach, with users praising local, task-specific small models for bio-imaging and other niche uses. The main concerns centered on the unclear business model, the lack of a Python SDK, and the iOS-centric model lineup that makes web and cross-platform adoption harder.

**Tags**: `#on-device AI`, `#local LLMs`, `#edge computing`, `#SDK`, `#AI business models`

---

<a id="item-15"></a>
## [OpenAI Releases ChatGPT Images 2.5 with Two New API Models](https://simonwillison.net/2026/Sep/8/introducing-chatgpt-images-25/) ⭐️ 7.0/10

OpenAI released ChatGPT Images 2.5, introducing two new API model IDs: gpt-image-2.5-sunburst for editing precision and gpt-image-2.5-flare for fast everyday generation. The update improves multi-turn instruction following, responds faster, and better preserves subjects from reference photos. This matters for developers building image generation features, since the new model IDs and improved multi-turn editing make iterative workflows more practical. OpenAI reports its image models have been used for more than 3 billion images, underscoring how central image generation has become to the ChatGPT ecosystem. Sunburst is positioned for workflows where editing precision matters most, while Flare is the default for most applications and delivers higher-quality images than GPT-Image-2 at 50% lower latency. Flare supports low, medium, high, xhigh, max, and auto quality settings, and image output is priced at $30 per million tokens.

rss · Simon Willison · Sep 8, 22:46

**Background**: GPT-Image is OpenAI's family of image generation and editing models available through the API, while ChatGPT Images is the consumer-facing experience. Multi-turn instruction following refers to a model's ability to retain context and honor evolving constraints across successive prompts, which is important for iterative image editing. Simon Willison, a well-known developer and blogger, upgraded his openai_image.py CLI tool to support passing one or more reference images to the new models.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-chatgpt-images-2-5/">Introducing ChatGPT Images 2.5 | OpenAI</a></li>
<li><a href="https://developers.openai.com/api/docs/models/gpt-image-2.5-flare">GPT-Image-2.5 Flare Model | OpenAI API</a></li>
<li><a href="https://developers.openai.com/api/docs/models/gpt-image-2.5-sunburst">GPT-Image-2.5 Sunburst Model | OpenAI API</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#image-generation`, `#API`, `#GPT-Image`, `#AI-models`

---

<a id="item-16"></a>
## [Anthropic Allegedly Building Predictive Surveillance System to Monitor Activists](https://www.reddit.com/r/ClaudeAI/comments/1wc7frn/anthropic_is_building_a_predictive_surveillance/) ⭐️ 7.0/10

An investigation published by The American Prospect on September 9, 2026, alleges that Anthropic is building a predictive surveillance system designed to monitor activists who oppose rapid AI development. The report cites new hires and comments made in interviews with senior security officials at the frontier AI lab, and the story was widely reshared on Reddit's r/ClaudeAI community. If accurate, the allegations suggest a leading AI safety-focused company is turning its capabilities against dissenters, raising serious ethical, privacy, and civil-liberties concerns. This could intensify scrutiny of Anthropic and the broader AI industry, potentially influencing regulation and public trust around AI surveillance tools. The reporting is based on job postings and interviews with senior security officials rather than published product documentation, so the exact scope and capabilities of the alleged system remain unverified. The term 'predictive surveillance' refers to systems that analyze behavior patterns and contextual data to anticipate events before they happen, rather than simply recording them after the fact.

reddit · r/ClaudeAI · /u/jesssoul · Sep 10, 03:26

**Background**: Predictive surveillance systems use AI to analyze behavior patterns, contextual data, and real-time feeds to anticipate incidents instead of reacting to them after they occur. Anthropic is a frontier AI lab known for its safety-focused research and its Claude family of models, and it has publicly positioned itself as a responsible steward of AI development. The American Prospect is a US political magazine, and the report was also covered by outlets such as Common Dreams, which framed the system as a 'pre-crime' tool aimed at anti-AI activists.

<details><summary>References</summary>
<ul>
<li><a href="https://prospect.org/2026/09/09/anthropic-artificial-intelligence-surveillance-system-monitor-activists/">Anthropic Is Building a Predictive Surveillance System to ...</a></li>
<li><a href="https://www.commondreams.org/news/anthropic-pre-crime-surveillance">Anthropic Building a 'Pre-Crime' System to Surveil Anti-AI ...</a></li>
<li><a href="https://www.cryptogon.com/?p=75838">cryptogon.com » Anthropic Is Building a Predictive ...</a></li>

</ul>
</details>

**Discussion**: The Reddit post in r/ClaudeAI, titled 'What are we doing here, guys?', reflects a critical and concerned tone, with the community engaging in ethical debate over the allegations. The framing suggests users are questioning Anthropic's direction and the broader implications for AI ethics and surveillance.

**Tags**: `#AI ethics`, `#surveillance`, `#Anthropic`, `#privacy`, `#AI policy`

---

<a id="item-17"></a>
## [Anthropic Calls 'Double-Check Your Work' an Anti-Pattern for Modern Models](https://www.reddit.com/r/ClaudeAI/comments/1wcdisq/anthropic_says_doublecheck_your_work_is_now_an/) ⭐️ 7.0/10

Anthropic published guidance stating that common prompt instructions like "double-check your work" and "be maximally thorough" are now anti-patterns for current Claude models, causing wasted compute and worse outputs. A Reddit user audited their own config and found 125 instances of "must" and "never" rules, unable to tell which were useful nudges versus hard constraints. This marks a significant shift in prompt engineering best practices: instructions that once improved older models now degrade performance and increase cost on current models. It affects anyone maintaining long-lived system prompts or agent configurations, forcing a rethink of how we write and audit prompt rules. The guidance distinguishes between harmful nudges (like "be maximally thorough") and necessary hard constraints (like "never click publish twice"), and notes that contradictory rules caused four valid refunds to never be issued. Anthropic also provides a separate control for how hard the model works, which should be tuned rather than replaced with prompt nudges.

reddit · r/ClaudeAI · /u/Frequent-Ad-836 · Sep 10, 08:50

**Background**: Prompt engineering is the practice of structuring inputs to a language model to get desired outputs. Older LLMs often cut corners, so users added instructions like "double-check your work" to force thoroughness. Current models like Claude are more capable and self-directed, so such instructions can cause redundant work, higher costs, and conflicts with the model's own reasoning.

**Discussion**: The Reddit post sparked discussion among users running long-lived Claude configurations, with many sharing similar experiences of bloated rule files and asking how to audit which lines are doing real work. The overall sentiment reflects surprise at the counterintuitive guidance and a desire for practical methods to distinguish nudges from hard constraints.

**Tags**: `#prompt-engineering`, `#LLM`, `#Anthropic`, `#best-practices`, `#AI-performance`

---

<a id="item-18"></a>
## [Anthropic Researcher Resigns, Accuses Anthropic and OpenAI of 'Gambling With Our Lives'](https://www.reddit.com/r/ClaudeAI/comments/1wbi2pr/anthropic_researcher_quits_saying_anthropic_and/) ⭐️ 7.0/10

An Anthropic researcher has publicly resigned, stating that both Anthropic and OpenAI are recklessly 'gambling with our lives' through their AI development practices. The resignation was shared on Reddit's r/ClaudeAI community, drawing significant attention to internal dissent at a leading AI safety-focused lab. A resignation from a safety-focused lab like Anthropic signals that even insiders believe current AI development pace may be dangerously reckless, potentially eroding public trust in corporate AI safety commitments. This could intensify pressure on both Anthropic and OpenAI to demonstrate genuine safety practices rather than performative ones. The resignation was submitted by Reddit user /u/thisisinsider and links to a news article, though the specific identity of the researcher and the full text of their resignation statement are not detailed in the available content. The post scored 7.0/10 for newsworthiness, reflecting its significance as an insider critique without accompanying technical breakthroughs.

reddit · r/ClaudeAI · /u/thisisinsider · Sep 9, 10:45

**Background**: Anthropic and OpenAI are two of the leading AI labs, both publicly committed to AI safety research and responsible development. Anthropic emphasizes a 'portfolio approach' to AI safety and advocates for government obligations on capable model developers, while OpenAI describes a 'balanced, scientific approach' integrating safety from the outset. AI existential risk concerns—voiced by researchers and CEOs alike—center on the possibility that advanced AI could become uncontrollable and cause catastrophic harm.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/core-views-on-ai-safety">Anthropic's core views on AI safety \ Anthropic</a></li>
<li><a href="https://openai.com/index/openai-safety-update/">OpenAI safety practices</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_existential_risk">AI existential risk</a></li>

</ul>
</details>

**Discussion**: The Reddit post sparked important community discussion around AI safety and corporate ethics, with the overall sentiment reflecting concern that leading labs may be prioritizing competitive speed over genuine safety. Commenters likely debated whether the resignation represents a legitimate alarm or an isolated viewpoint.

**Tags**: `#AI safety`, `#Anthropic`, `#OpenAI`, `#AI ethics`, `#resignation`

---

<a id="item-19"></a>
## [Spotify's Portal Plugins Cut Claude Code Costs by 90%](https://www.reddit.com/r/ClaudeAI/comments/1wbmcgw/cut_your_claude_code_cost_by_90_using_the_spotify/) ⭐️ 7.0/10

A Reddit post by /u/fsharpman describes how to use Spotify's Portal AI plugins to cut Claude Code token costs by roughly 90% by offloading bulk file reading to a cheaper worker model. Users can install the plugins via the spotify/portal-ai-plugins marketplace and run /portal:setup to authenticate the Portal CLI. Token costs are a major pain point for developers using AI coding assistants, and this plugin-based routing approach offers a practical, reusable way to keep expensive frontier models focused on reasoning while cheaper models handle bulk reading. It signals a broader trend of multi-model orchestration and cost-tiering inside coding agents. The setup requires installing both the portal and shunt plugins, where shunt delegates through the Portal CLI provided by the portal plugin; the bulk-reader and code-writer modes are already public and can be forked in Portal to customize the worker model or instructions, with forked versions automatically taking precedence. The plugin enforces routing automatically, so users do not need to manage it manually.

reddit · r/ClaudeAI · /u/fsharpman · Sep 9, 13:57

**Background**: Claude Code is Anthropic's agentic coding tool that bills by token usage, and reading large numbers of files can quickly consume expensive input tokens. Spotify's Portal is an internal developer portal built on Backstage, and the portal-ai-plugins project brings Portal capabilities into coding agents like Claude Code, Codex, and Cursor. The Portal AI Gateway lets teams configure and manage AI providers and models centrally, which is what enables routing bulk reads to a cheaper model.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/spotify/portal-ai-plugins">Spotify Portal AI Plugins - GitHub</a></li>
<li><a href="https://backstage.spotify.com/docs/portal/core-features-and-plugins/ai-gateway">AI Gateway - Spotify for Backstage</a></li>
<li><a href="https://code.claude.com/docs/en/costs">Manage costs effectively - Claude Code Docs</a></li>

</ul>
</details>

**Tags**: `#Claude Code`, `#cost optimization`, `#AI plugins`, `#token usage`, `#Spotify`

---

<a id="item-20"></a>
## [Windows XP's initial user picture algorithm revealed by Raymond Chen](https://devblogs.microsoft.com/oldnewthing/20260909-00/?p=112683) ⭐️ 6.0/10

Microsoft engineer Raymond Chen explained on his Old New Thing blog that Windows XP selected a user's initial account picture using RtlRandomEx, seeded with the current value of GetTickCount(), and a one-pass random selection algorithm. The routine is a special case of reservoir sampling where k=1, avoiding a second pass over the file system. The post highlights how a seemingly trivial feature required careful engineering to handle edge cases such as directories changing mid-scan, offering a lesson in thoughtful design for developers. It also gives retroactive insight into a quirky Windows XP behavior that millions of users encountered but never questioned. The algorithm caps the directory scan at 100 pictures as a safety measure, and because it uses a single pass, it gracefully handles directories that change while being enumerated. The random seed comes from system uptime via GetTickCount(), making the selection deterministic given the same timing conditions.

hackernews · soheilpro · Sep 10, 09:04 · [Discussion](https://news.ycombinator.com/item?id=49640646)

**Background**: Windows XP, released in 2001, was a major version of Microsoft's Windows NT operating system that introduced a redesigned Start menu and user account system. When creating a new account, XP automatically assigned one of several default pictures from a Default Pictures folder. Raymond Chen is a longtime Microsoft engineer known for his Old New Thing blog, which explains the history and design decisions behind Windows internals.

<details><summary>References</summary>
<ul>
<li><a href="https://devblogs.microsoft.com/oldnewthing/20260909-00/?p=112683">What algorithm did Windows XP use to choose your initial user ...</a></li>
<li><a href="https://zeli.app/story/49640646">Windows XP picked your first user · Hacker News | Zeli</a></li>
<li><a href="https://en.wikipedia.org/wiki/Windows_XP">Windows XP - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters praised the thoughtful engineering and edge-case handling, with some noting that such awareness is often drowned out by modern task loads. Others expressed appreciation for Raymond Chen's Windows internals stories, and one quoted a joke about his posts conveying 'no useful information.'

**Tags**: `#windows`, `#software-engineering`, `#algorithms`, `#history`, `#design`

---

<a id="item-21"></a>
## [Nine streaming subscriptions now cost $702/year more than in 2021](https://honestlyranked.com/guides/streaming-price-increases/) ⭐️ 6.0/10

A data analysis published on HonestlyRanked shows that the same nine popular streaming subscriptions cost $702 more per year in 2025 than they did in 2021, a roughly 61% increase over five years. The article aggregates price changes across major services and sparked a Hacker News discussion with 156 points and 149 comments. The figure quantifies how much streaming has shifted from a cheap cable replacement into a substantial recurring household expense, affecting millions of subscribers who must decide whether to keep, downgrade, or cancel services. It also highlights broader subscription fatigue and the pricing tactics that software and entertainment companies increasingly rely on. The $702 figure is an absolute increase across nine services, which commenters noted represents about a 61% rise over five years; the analysis is presented on a site whose editor claims to verify every figure against its source. The discussion also raised concerns about tier restructuring, where features are moved to higher-priced plans to force upgrades.

hackernews · honestlyranked · Sep 10, 10:13 · [Discussion](https://news.ycombinator.com/item?id=49641215)

**Background**: Streaming services such as Netflix, Disney+, and others launched with low monthly prices to attract users away from traditional cable TV. Over time, many have raised prices, introduced ad-supported tiers, and cracked down on password sharing to boost revenue as subscriber growth slowed. This article compares the cumulative cost of nine such subscriptions between 2021 and 2025 to illustrate the trend.

**Discussion**: Commenters were divided: some criticized the site's obviously LLM-generated template design, while others shared personal experiences of price hikes and hostile tier restructuring in software services. Several users said they had cancelled most subscriptions or avoided them entirely by buying CDs/Blu-rays, and one noted the $702 figure is meaningless without the baseline, since it represents a 61% increase over five years.

**Tags**: `#streaming`, `#pricing`, `#consumer`, `#subscription`, `#economics`

---

<a id="item-22"></a>
## [No Man's Sky Cosmos Update Marks 10th Anniversary](https://www.nomanssky.com/cosmos-update/) ⭐️ 6.0/10

Hello Games released the free 'Cosmos' update for No Man's Sky, coinciding with the game's 10th anniversary. The update overhauls space gameplay, letting players become space station directors, join galactic alliances, build space bases, and finally reach stars. This update continues Hello Games' decade-long redemption arc, transforming a disastrous 2016 launch into one of gaming's most celebrated turnarounds. It reinforces the studio's free content model, which has generated an estimated $500–700 million in revenue and over 15–20 million copies sold, setting a benchmark for post-launch support. The Cosmos update is free for all existing players and introduces a new star system map, the ability to strip colossal hulks for parts before hull integrity fails, and deep-space marvels. It is the 40th major free update, arriving after over 45 major updates in 10 years.

hackernews · Limb · Sep 9, 15:47 · [Discussion](https://news.ycombinator.com/item?id=49628493)

**Background**: No Man's Sky is a procedurally generated space exploration game released in 2016 by Hello Games. Its launch was widely criticized for missing promised features, but the studio has since released dozens of free major updates that added multiplayer, base building, and more. The Cosmos update marks the game's 10th anniversary and continues this tradition.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nomanssky.com/cosmos-update/">Cosmos Update - No Man's Sky</a></li>
<li><a href="https://blog.playstation.com/2026/09/09/introducing-no-mans-sky-cosmos-update-live-on-ps5-today/">Introducing No Man’s Sky: Cosmos update, live on PS5 today</a></li>
<li><a href="https://www.ign.com/articles/no-mans-sky-10th-anniversary-cosmos-update-actually-updates-space-lets-players-finally-reach-stars">No Man's Sky 10th Anniversary Cosmos Update Actually Updates Space, Lets Players Finally Reach Stars</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters are sharply divided: some praise Hello Games' redemption and the sheer amount of content, citing 40 free updates and strong sales, while others argue the game still feels like an impressive tech demo with little substantial gameplay. Many recent players share positive experiences, calling it one of their favorite games.

**Tags**: `#gaming`, `#no-mans-sky`, `#game-development`, `#community-discussion`, `#update`

---

<a id="item-23"></a>
## [Apple Announces AirPods 5 With Open-Ear ANC](https://www.apple.com/newsroom/2026/09/apple-introduces-airpods-5-with-best-in-class-open-ear-active-noise-cancellation/) ⭐️ 6.0/10

Apple announced AirPods 5, featuring what it calls best-in-class open-ear Active Noise Cancellation that removes up to 50 percent more external noise than AirPods 4 with ANC, alongside a redesigned acoustic architecture and a new force sensor with volume swipe on the stem. Open-ear ANC is technically difficult because there is no sealed cavity to block sound, so a meaningful improvement here could push the whole open-ear category forward and pressure rivals like Sony and Bose; the $129 price also makes premium AirPods features more accessible, which matters as Apple faces growing competition in the wireless earbud market. The volume swipe is a first for the open-ear form factor, though it has existed on AirPods Pro for years; Apple also claims a more natural Transparency mode, and the $129 price point brings features previously reserved for higher-end models down to the entry tier.

hackernews · awad · Sep 9, 17:39 · [Discussion](https://news.ycombinator.com/item?id=49630253)

**Background**: Open-ear earbuds rest outside the ear canal rather than sealing it, which makes them comfortable and lets wearers stay aware of their surroundings, but this design also makes noise cancellation much harder because sound leaks in freely. Active Noise Cancellation works by using microphones to sample ambient noise and generating inverse sound waves to cancel it out, a technique that is far more effective inside a sealed ear canal. Apple's AirPods line has been the dominant force in wireless earbuds since 2016, and each generation has gradually added features like ANC and transparency mode.

<details><summary>References</summary>
<ul>
<li><a href="https://www.apple.com/newsroom/2026/09/apple-introduces-airpods-5-with-best-in-class-open-ear-active-noise-cancellation/">Apple introduces AirPods 5 with best-in-class open-ear Active Noise Cancellation - Apple</a></li>
<li><a href="https://www.theverge.com/tech/988479/apple-airpods-5-announcement-september-2026-event">Apple announces AirPods 5 with ‘best-in-class open‑ear active noise cancellation’ | The Verge</a></li>
<li><a href="https://www.soundcore.com/blogs/open-ear/how-anc-works-in-open-ear">The Science Of Silence: How Active Noise Cancellation Works In Open-ear Headphones</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were largely skeptical: some argued that Bluetooth audio quality has regressed compared to wired headphones from 2005, others complained that AirPods features like Find My remain locked behind iPhone ownership, and several dismissed the volume swipe as pure marketing since AirPods Pro have had it for years. There was also discussion of pricing and Apple's fading dominance as users increasingly choose brands like Sony.

**Tags**: `#Apple`, `#AirPods`, `#audio`, `#product-announcement`, `#Hacker News`

---

<a id="item-24"></a>
## [Apple Debuts iPhone 18 Pro with 2nm A20 Pro and Signed-Sensor Photo Authenticity](https://www.apple.com/newsroom/2026/09/apple-debuts-iphone-18-pro-and-iphone-18-pro-max/) ⭐️ 6.0/10

Apple announced the iPhone 18 Pro and iPhone 18 Pro Max, featuring the A20 Pro chip built on a 2nm process, a second-generation vapor chamber cooling system, and a new 'Apple Reference Image' feature that uses a signed sensor in the Main camera to cryptographically authenticate photos. The feature captures signed sensor data processed via Private Cloud Compute into an unalterable reference image viewable in the Photos app. This release marks Apple's first 2nm smartphone chip, potentially setting a new performance-per-watt bar for mobile computing, while the Reference Image feature directly addresses growing concerns about AI-generated deepfakes by providing hardware-level photo provenance. The combination of advanced silicon and cryptographic authenticity could influence how other manufacturers approach both performance and content verification. The A20 Pro uses a new architecture with smaller, more densely packed transistors on the 2nm node, and the second-generation vapor chamber is designed to improve heat dissipation for sustained performance. The Reference Image feature is opt-in and relies on Private Cloud Compute to develop the signed sensor data into an unalterable reference image, though community members noted that RAM and memory bandwidth specifications were not disclosed.

hackernews · meetpateltech · Sep 9, 17:33 · [Discussion](https://news.ycombinator.com/item?id=49630151)

**Background**: The 2nm process technology refers to the size of transistors on a chip—smaller nodes allow more transistors in the same area, generally improving performance and power efficiency. A vapor chamber is a cooling component that spreads heat across a larger surface using a sealed liquid, helping prevent thermal throttling during demanding tasks. Apple's Reference Image feature builds on the concept of content provenance, using a hardware sensor to cryptographically sign image data so that later verification can prove a photo was captured by the camera and not generated or edited by AI.

<details><summary>References</summary>
<ul>
<li><a href="https://www.macrumors.com/2026/09/09/apple-unveils-a20-pro-as-first-2nm-smartphone-chip/">Apple Unveils A 20 Pro as First 2 nm Smartphone Chip - MacRumors</a></li>
<li><a href="https://appleinsider.com/articles/26/09/09/apple-reference-image-is-a-new-way-to-authenticate-iphone-photography">Apple Reference Image is a new way to authenticate iPhone ...</a></li>
<li><a href="https://celsiainc.com/heat-sink-blog/vapor-chamber-cooling-design-guide/">Vapor Chamber Cooling Design Principles | Celsia</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters expressed enthusiasm for the 2nm A20 Pro chip, second-generation vapor chamber, and the Reference Image authenticity feature, with one calling the ability to prove images came from the real world a standout. However, many criticized the high European pricing (iPhone 18 Pro at 1479 euros versus iPhone 17 at 969 euros), lamented the lack of pro features like dual eSIM modems or Thunderbolt, and noted that missing RAM and memory bandwidth specs are concerning.

**Tags**: `#apple`, `#iphone`, `#hardware`, `#image-authenticity`, `#consumer-tech`

---

<a id="item-25"></a>
## [Terence Tao Reflects on Childlike Curiosity and AI](https://mathstodon.xyz/@tao/117244102901892965) ⭐️ 6.0/10

Terence Tao, the Fields Medal-winning mathematician, posted a reflection on Mathstodon about the value of retaining childlike curiosity and how it relates to understanding AI. His post sparked a rich discussion on Hacker News, with commenters drawing on literature, philosophy, and personal anecdotes. Tao's perspective highlights a growing conversation about the limitations of AI, emphasizing that human qualities like curiosity and playfulness are essential for deep understanding. This resonates with ongoing debates in the tech community about the role of AI and what it means to be human. The discussion included references to William Wordsworth's poem 'The Child is father of the Man' and Astrid Lindgren's ability to remember childhood feelings. Commenters also debated whether AI's non-human nature is its fundamental problem, and shared anecdotes about piñatas and Alan Watts' talks.

hackernews · yurivish · Sep 10, 04:04 · [Discussion](https://news.ycombinator.com/item?id=49638280)

**Background**: Terence Tao is an Australian-American mathematician known for his work in partial differential equations, combinatorics, and number theory, and is often called the 'Mozart of Math'. Hacker News is a social news website focused on computer science and entrepreneurship, where discussions often explore intellectual curiosity. The post touches on themes from Romantic poetry and developmental psychology, connecting them to contemporary AI debates.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Terence_Tao">Terence Tao</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hacker_News">Hacker News</a></li>

</ul>
</details>

**Discussion**: Commenters largely agreed with Tao's emphasis on curiosity, sharing literary references and personal stories. Some argued that AI's fundamental flaw is its lack of human experience, while others highlighted how children's playful approach contrasts with adult goal-oriented thinking. The overall sentiment was reflective and appreciative of Tao's perspective.

**Tags**: `#AI`, `#philosophy`, `#childhood`, `#curiosity`, `#Terence Tao`

---

<a id="item-26"></a>
## [Personal essay laments the modern internet's decline, sparks HN debate](https://strategictree.bearblog.dev/i-think-i-hate-the-internet/) ⭐️ 6.0/10

A personal essay titled "I think I hate the internet" published on a Bear Blog laments how the internet has shifted from a source of connection to an ad-ridden, engagement-optimized space. The post sparked a rich discussion on Hacker News, with commenters sharing diverse viewpoints on nostalgia, platform incentives, and personal responsibility. This essay and the ensuing discussion reflect a growing disillusionment with the modern internet, a sentiment that resonates with many users and ties into broader conversations about platform decay and digital wellbeing. It highlights how the incentives of ad-driven social media platforms are reshaping online life for billions of people. The essay is a reflective personal piece rather than a technical analysis, and the Hacker News discussion includes comments from users like donatj, who describes growing up as a lonely teen in the late 1990s and finding community online, and willtemperley, who argues that people hate "The Web" rather than "The Internet" and suggests an ad-free, decentralized web is possible.

hackernews · saikatsg · Sep 10, 06:12 · [Discussion](https://news.ycombinator.com/item?id=49639104)

**Background**: The modern internet is dominated by a handful of large platforms whose algorithms prioritize engagement, often amplifying sensational or divisive content to keep users scrolling. This dynamic has been described as "enshittification," a term coined by Cory Doctorow to explain how platforms first attract users, then degrade their experience to serve advertisers and business customers. Hacker News is a popular technology-focused discussion forum where such critiques often surface.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sprinklr.com/blog/social-media-algorithm/">Social Media Algorithm and How They Work in 2025 | Sprinklr</a></li>
<li><a href="https://www.theguardian.com/commentisfree/2023/mar/11/users-advertisers-we-are-all-trapped-in-the-enshittification-of-the-internet">Users, advertisers – we are all trapped in the ‘ enshittification ’ of the ...</a></li>
<li><a href="https://news.ycombinator.com/?ref=dtf.ru">Hacker News</a></li>

</ul>
</details>

**Discussion**: Commenters expressed a mix of nostalgia and frustration: donatj described the internet as a former haven for lonely teens that now feels bizarre, while willtemperley distinguished between hating "The Web" and "The Internet" and called for a forkable, ad-free alternative. Others, like arjie, pushed back on the idea that costs are prohibitive, noting that not everyone needs the latest expensive phone or subscriptions.

**Tags**: `#internet-culture`, `#social-media`, `#technology-criticism`, `#hacker-news`, `#digital-wellbeing`

---

<a id="item-27"></a>
## [Claude Code reportedly burns 50 million tokens on a simple Markdown check](https://www.reddit.com/r/ClaudeAI/comments/1wce8dh/claude_code_just_burned_fifty_million_tokens_in/) ⭐️ 6.0/10

A Reddit user on r/ClaudeAI reported that Claude Code unexpectedly consumed 50 million tokens while simply checking their Markdown files for consistency, despite the tool being able to use workflows. The post is a brief, informal complaint without technical analysis, but it quickly drew attention to the issue of runaway token usage in AI coding agents. This incident highlights a growing concern for developers using AI coding agents: token consumption can spiral out of control, leading to unexpectedly high API costs. As more teams adopt tools like Claude Code, understanding and managing token usage becomes critical for keeping AI-assisted development affordable. The user did not provide logs, configuration details, or a reproduction case, so the exact cause remains unclear. However, the scale of 50 million tokens is extreme for a Markdown consistency check, suggesting a possible loop, excessive context re-sending, or misconfigured workflow.

reddit · r/ClaudeAI · /u/Lazy_Assistance_1137 · Sep 10, 09:30

**Background**: Claude Code is Anthropic's command-line AI coding agent that can read files, run commands, and execute multi-step workflows. It charges based on token usage, and because agentic tools re-send context on every tool call, their token consumption can be 10-100x higher than simple chat interactions. This has led to reports of developers spending hundreds to thousands of dollars per month on AI coding agents.

<details><summary>References</summary>
<ul>
<li><a href="https://restato.github.io/blog/claude-code-token-economy/">How Claude Code token usage works and how to estimate your costs.</a></li>
<li><a href="https://leanopstech.com/blog/agentic-ai-cost-runaway-token-budget-2026/">AI Agents Burn 50x More Tokens Than Chats | LeanOps</a></li>
<li><a href="https://techcrunch.com/2026/06/05/the-token-bill-comes-due-inside-the-industry-scramble-to-manage-ais-runaway-costs/">The token bill comes due: Inside the industry scramble to ...</a></li>

</ul>
</details>

**Tags**: `#Claude Code`, `#token usage`, `#AI coding agents`, `#cost management`, `#Reddit`

---