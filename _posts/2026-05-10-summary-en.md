---
layout: default
title: "Daily News 2026-05-10"
date: 2026-05-10
lang: en
---

> From 271 items, 12 important content pieces were selected

---

1. [Mathematician Tests ChatGPT 5.5 Pro on Research Problems](#item-1) ⭐️ 9.0/10
2. [Bun's experimental Rust rewrite hits 99.8% test compatibility](#item-2) ⭐️ 8.0/10
3. [Let-go: A Clojure-like language in Go boots in 7ms](#item-3) ⭐️ 8.0/10
4. [LLMs Corrupt Documents in Delegation Tasks](#item-4) ⭐️ 8.0/10
5. [The Hypocrisy of Cyberlibertarianism](#item-5) ⭐️ 8.0/10
6. [Proposal to Fork the Web into a Simpler Document Protocol](#item-6) ⭐️ 8.0/10
7. [Baidu Releases Wenxin 5.1 with 94% Cost Reduction](#item-7) ⭐️ 8.0/10
8. [SMIC Founder: Obsessing Over 3nm/2nm Is a Misconception](#item-8) ⭐️ 8.0/10
9. [Chang'e-6 lunar soil reveals shift in asteroid impact types](#item-9) ⭐️ 8.0/10
10. [China Launches 180-Qubit Superconducting Quantum Computer 'Origin Wukong-180'](#item-10) ⭐️ 8.0/10
11. [Intel Re-Enters Apple Supply Chain to Manufacture Some Chips](#item-11) ⭐️ 8.0/10
12. [Three Chinese AI startups raise $10B+ in a week](#item-12) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Mathematician Tests ChatGPT 5.5 Pro on Research Problems](https://gowers.wordpress.com/2026/05/08/a-recent-experience-with-chatgpt-5-5-pro/) ⭐️ 9.0/10

Timothy Gowers, a Fields Medalist, reported that ChatGPT 5.5 Pro successfully solved several gentle research problems in mathematics, demonstrating advanced reasoning and self-correction abilities. This suggests that LLMs are approaching the ability to assist in genuine mathematical research, potentially transforming how PhD students are trained and how research is conducted. Gowers noted that the model could trace its own reasoning and correct mistakes, but it still required careful guidance and made errors. The model is available as GPT-5.5 Pro, released by OpenAI on April 23, 2026.

hackernews · _alternator_ · May 9, 02:41 · [Discussion](https://news.ycombinator.com/item?id=48071262)

**Background**: Large language models (LLMs) like GPT-5.5 are trained on vast text data and can generate human-like text. Recent benchmarks show GPT-5.5 Pro scoring 51.7% on FrontierMath problems (difficulty 1-3), indicating strong mathematical reasoning. The model uses a 'Thinking' mode for deeper reasoning.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.5">GPT-5.5 - Wikipedia</a></li>
<li><a href="https://help.openai.com/en/articles/11909943-gpt-5-1-in-chatgpt">GPT-5.5 in ChatGPT | OpenAI Help Center</a></li>
<li><a href="https://maa.org/math-values/how-will-ai-impact-mathematics-research/">How Will the New AI Impact Mathematics Research? – Mathematical Association of America</a></li>

</ul>
</details>

**Discussion**: Commenters generally agreed with Gowers' assessment, noting the model's improved self-correction but also its high cost and tendency to make conceptual errors. Some raised philosophical questions about the value of human ideas when AI can generate them easily.

**Tags**: `#AI`, `#LLM`, `#mathematics`, `#research`, `#education`

---

<a id="item-2"></a>
## [Bun's experimental Rust rewrite hits 99.8% test compatibility](https://twitter.com/jarredsumner/status/2053047748191232310) ⭐️ 8.0/10

Bun's experimental Rust rewrite has achieved 99.8% test compatibility on Linux x64 glibc, as announced by Bun's creator Jarred Sumner on Twitter. This milestone indicates that a full Rust rewrite of Bun is feasible, potentially improving memory safety and performance while maintaining compatibility with existing Node.js applications. The rewrite was done in just 6 days using LLM assistance, and a Bun developer noted that the code is experimental and may be discarded entirely.

hackernews · heldrida · May 9, 10:12 · [Discussion](https://news.ycombinator.com/item?id=48073680)

**Background**: Bun is a JavaScript runtime designed as a drop-in replacement for Node.js, originally written in Zig. The experimental Rust rewrite aims to leverage Rust's memory safety guarantees and ecosystem, while the 99.8% test compatibility means nearly all existing Bun tests pass on the Rust version.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/bun: Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one</a></li>
<li><a href="https://thecodersblog.com/bun-runtime-migration-from-zig-to-rust-2026/">Bun's Rust Pivot: What the Zig-to-Rust Migration Means for JavaScript Runtime Performance in 2026 | The Coders Blog | Home</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: some praise the speed and potential of the rewrite, while others express distrust due to heavy LLM involvement and concerns about abandoning Zig's design philosophy. A Bun developer clarified that the rewrite is experimental and may not be adopted.

**Tags**: `#Bun`, `#Rust`, `#JavaScript runtime`, `#rewrite`, `#LLM`

---

<a id="item-3"></a>
## [Let-go: A Clojure-like language in Go boots in 7ms](https://github.com/nooga/let-go) ⭐️ 8.0/10

Let-go is a Clojure-like language implemented in pure Go that boots in about 7ms, roughly 50x faster than JVM Clojure and 3x faster than Babashka. It ships as a ~10MB static binary and includes an nREPL server compatible with Calva and CIDER. This project brings Clojure's expressive syntax and functional paradigm to environments where fast startup and small binary size are critical, such as CLIs, web servers, and scripting. It also demonstrates that a Lisp-like language can be efficiently embedded in Go programs, potentially broadening Clojure's reach beyond the JVM. Let-go is about 90% compatible with JVM Clojure and uses a handcrafted compiler and stack VM. It supports AOT compilation to portable bytecode or standalone binaries, and can be embedded in Go programs with seamless interop for functions, structs, and channels.

hackernews · marcingas · May 9, 17:52 · [Discussion](https://news.ycombinator.com/item?id=48076815)

**Background**: Clojure is a dynamic, functional Lisp dialect that runs primarily on the JVM, known for its immutable data structures and concurrency support. Babashka is a native Clojure interpreter for scripting that uses GraalVM for fast startup, while sci is a Clojure interpreter library also built on GraalVM. Let-go aims to provide a similar experience but with even faster startup and easier embedding by leveraging Go's compilation and runtime.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Babashka">Babashka</a></li>
<li><a href="https://babashka.org/">Babashka</a></li>
<li><a href="https://nrepl.org/nrepl/usage/server.html">nREPL Server :: nREPL</a></li>

</ul>
</details>

**Discussion**: The community expressed strong interest, with one user calling it "the kind of Clojure port that I always was looking for." Others noted related projects like Glojure and pointed to collaborative efforts between Let-go, Glojure, and Gloat for AOT compilation. There was also a suggestion to add Let-go to the awesome-clojure-likes list.

**Tags**: `#Clojure`, `#Go`, `#Programming Language`, `#Performance`, `#REPL`

---

<a id="item-4"></a>
## [LLMs Corrupt Documents in Delegation Tasks](https://arxiv.org/abs/2604.15597) ⭐️ 8.0/10

A new study empirically demonstrates that large language models systematically corrupt documents when used for delegation, with each pass degrading intent and precision, similar to lossy compression. This finding challenges the reliability of LLM-based agents for tasks requiring precise document handling, such as scientific writing or legal drafting, and highlights the need for careful agent design. The study used a basic agentic harness with file reading, writing, and code execution tools, and found that even with tool use, corruption persisted. The term 'semantic ablation' was coined to describe the gradual loss of nuance.

hackernews · rbanffy · May 9, 08:44 · [Discussion](https://news.ycombinator.com/item?id=48073246)

**Background**: Large language models generate text by predicting the next token, which can lead to loss of information when processing long documents. This is analogous to repeatedly saving a JPEG image, where each compression degrades quality. The study provides empirical evidence for this phenomenon in delegation contexts.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2604.07569">Learning is Forgetting: LLM Training As Lossy Compression</a></li>
<li><a href="https://www.researchgate.net/figure/Syntactic-similarity-with-semantic-ablation-The-shaded-colored-areas-represent-1_fig2_399595405">Syntactic similarity with semantic ablation. The shaded colored areas... | Download Scientific Diagram</a></li>

</ul>
</details>

**Discussion**: Community members largely agreed with the findings, with some noting that frequent LLM users already avoid round-tripping content. One commenter expressed skepticism about the tool-use results, suggesting the agent harness may not have been optimal. Others emphasized designing agents to minimize LLM round trips.

**Tags**: `#LLMs`, `#document corruption`, `#semantic ablation`, `#AI agents`, `#empirical study`

---

<a id="item-5"></a>
## [The Hypocrisy of Cyberlibertarianism](https://matduggan.com/the-intolerable-hypocrisy-of-cyberlibertarianism/) ⭐️ 8.0/10

An essay by Mat Duggan argues that cyberlibertarian ideals are hypocritical, as tech leaders abandon principles of freedom and decentralization when they become inconvenient. This critique challenges the foundational ideology of Silicon Valley, questioning whether tech leaders truly believe in the libertarian values they espouse or simply use them to justify deregulation and profit. The essay highlights contradictions such as advocating for minimal government while seeking state protection for intellectual property, and promoting decentralization while building centralized platforms.

hackernews · ColinWright · May 9, 13:48 · [Discussion](https://news.ycombinator.com/item?id=48074952)

**Background**: Cyberlibertarianism is a political ideology that emerged from early internet culture, advocating for minimal government regulation and maximum individual freedom online. It influenced many tech entrepreneurs and the early ethos of the internet. The essay argues that this ideology is internally inconsistent and often abandoned by its proponents when it conflicts with business interests.

<details><summary>References</summary>
<ul>
<li><a href="https://matduggan.com/the-intolerable-hypocrisy-of-cyberlibertarianism/">The Intolerable Hypocrisy of Cyberlibertarianism</a></li>
<li><a href="https://en.wikipedia.org/wiki/Technolibertarianism">Technolibertarianism - Wikipedia</a></li>
<li><a href="https://news.ycombinator.com/item?id=48074952">The Intolerable Hypocrisy of Cyberlibertarianism | Hacker News</a></li>

</ul>
</details>

**Discussion**: Comments on Hacker News show mixed reactions: some agree with the critique, noting that tech leaders often pivot to supporting regulation after scaling; others defend cyberlibertarianism, arguing that the ideals remain valid but are imperfectly applied. A user named schoen, an admirer of John Perry Barlow, partially agrees but points out nuance in the Declaration of Independence of Cyberspace.

**Tags**: `#cyberlibertarianism`, `#tech criticism`, `#internet culture`, `#politics`

---

<a id="item-6"></a>
## [Proposal to Fork the Web into a Simpler Document Protocol](https://dillo-browser.org/lab/web-fork/) ⭐️ 8.0/10

A proposal on the Dillo browser website suggests forking the web into a simpler, document-only protocol, reigniting debate about the web's evolution from documents to applications. This proposal challenges the dominant application-centric web model and could influence future protocol design, security, and user experience, especially for those seeking a lightweight, non-executable alternative like Gemini. The proposal emphasizes strict formal grammar and rejection of non-conforming pages, reminiscent of XHTML, which failed due to poor adoption. It also highlights the tension between document and application paradigms.

hackernews · wrxd · May 9, 11:33 · [Discussion](https://news.ycombinator.com/item?id=48074087)

**Background**: The web was originally designed for hypertext documents but evolved into a platform for complex applications. Protocols like Gemini offer a simpler, document-only alternative, but lack the interactive capabilities of the modern web.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gemini_(protocol)">Gemini (protocol)</a></li>
<li><a href="https://news.ycombinator.com/item?id=45498068">It's not against the rules, but it is hostile to the web. Forking the web.....</a></li>
<li><a href="https://geminiprotocol.net/">Gemini protocol</a></li>

</ul>
</details>

**Discussion**: Commenters debated the practicality of a strict document-only protocol, citing XHTML's failure and the role of browsers as application engines. Some argued for a simpler web for security and fun, while others saw it as unprofitable or unrealistic.

**Tags**: `#web`, `#browsers`, `#protocols`, `#standards`, `#gemini`

---

<a id="item-7"></a>
## [Baidu Releases Wenxin 5.1 with 94% Cost Reduction](https://36kr.com/newsflashes/3801731549371905?f=rss) ⭐️ 8.0/10

Baidu officially released Wenxin 5.1, a new foundation model that achieves top ranking on the LMArena search benchmark (first in China, fourth globally) with only 6% of the typical training cost for models of similar scale. This release demonstrates that high-performance foundation models can be trained at a fraction of the usual cost, potentially democratizing access to advanced AI capabilities. It also strengthens Baidu's competitive position in the Chinese AI market against rivals like DeepSeek. Wenxin 5.1 uses a novel 'multi-dimensional elastic pre-training' technique that compresses total parameters to about one-third and activated parameters to about one-half of Wenxin 5.0, while inheriting its knowledge. It scored 1223 points on LMArena's search leaderboard, surpassing DeepSeek-V4-Pro in agent capabilities and matching Gemini 3.1 Pro in creative writing.

rss · 36氪 · May 9, 07:21

**Background**: LMArena (formerly Chatbot Arena) is an open platform by LMSYS that evaluates AI models through human preference. Foundation models like Wenxin 5.1 are large neural networks trained on vast data to perform a wide range of tasks. 'Multi-dimensional elastic pre-training' allows training one model that can be scaled to different sizes, reducing cost.

<details><summary>References</summary>
<ul>
<li><a href="https://www.chinaz.com/2026/0509/1751121.shtml">百度文心大模型5.1正式发布</a></li>
<li><a href="https://www.chinaz.com/ainews/27813.shtml">百度发布文心大模型5.1：搜索能力位居国内首位，预训练成本仅为业界6%</a></li>
<li><a href="https://www.donews.com/news/detail/1/6548337.html">百度文心大模型 5.1发布：登上LMArena搜索榜国内第一- DoNews</a></li>

</ul>
</details>

**Tags**: `#AI`, `#large language model`, `#Baidu`, `#foundation model`, `#benchmark`

---

<a id="item-8"></a>
## [SMIC Founder: Obsessing Over 3nm/2nm Is a Misconception](https://news.mydrivers.com/1/1121/1121139.htm) ⭐️ 8.0/10

Zhang Rujing, founder of SMIC, stated in a recent interview that the semiconductor industry's obsession with advanced nodes like 3nm and 2nm is a misconception, as over 80% of market demand comes from mature nodes and niche markets where Chinese firms can more easily break foreign monopolies. This perspective challenges the prevailing narrative that advanced nodes are the only path to success, offering a more pragmatic strategy for China's semiconductor industry. It could redirect resources toward niche markets and edge AI, where Chinese companies have a higher chance of competing globally. Zhang emphasized that niche markets, such as industrial control, automotive electronics, and wearables, are often overlooked but hold huge potential. He also warned that startups should avoid the capital-intensive cloud AI chip race and instead focus on distributed AI and edge computing applications.

rss · 快科技 · May 9, 20:07

**Background**: Semiconductor manufacturing is typically divided into advanced nodes (e.g., 7nm, 5nm, 3nm) and mature nodes (e.g., 28nm and above). While advanced nodes are crucial for high-performance chips like those used in smartphones and AI data centers, mature nodes serve a wide range of applications including automotive, IoT, and power management. Niche markets refer to specialized segments with specific requirements, often dominated by a few established players. Edge AI involves running AI algorithms locally on devices rather than in the cloud, enabling real-time processing and privacy benefits.

<details><summary>References</summary>
<ul>
<li><a href="https://www.dramx.com/News/made-sealing/20240711-36651.html">晶圆代工成熟制程芯片“不香”了？-全球半导体观察</a></li>
<li><a href="https://www.inhand.com.cn/support/blogs/what-is-edge-ai/">什么是边缘AI - 映翰通</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#China`, `#advanced nodes`, `#niche markets`, `#AI chips`

---

<a id="item-9"></a>
## [Chang'e-6 lunar soil reveals shift in asteroid impact types](https://news.mydrivers.com/1/1121/1121116.htm) ⭐️ 8.0/10

Chinese Academy of Sciences researchers analyzed iron-nickel metal particles in Chang'e-6 lunar soil samples and discovered that the dominant type of asteroid impacting the Earth-Moon system shifted from ordinary to carbonaceous chondrites between 4.3 and 2.8 billion years ago. This finding provides crucial constraints on the delivery of water and organic materials to the early Earth-Moon system, as carbonaceous asteroids are rich in volatiles. It also helps refine models of solar system dynamical evolution and the timing of late accretion. The team identified 40 impact debris particles with metal grains, tracing 28 of them to 2.8-billion-year-old lunar basalts and 12 to 4.3-billion-year-old highland materials. The younger debris showed a significantly higher proportion of carbonaceous chondrite signatures.

rss · 快科技 · May 9, 17:21

**Background**: The Moon's surface preserves a nearly complete record of asteroid impacts over the past 4 billion years, unlike Earth where ancient craters are erased. Carbonaceous chondrites are a type of asteroid that contain up to 22% water and organic compounds, making them key candidates for delivering the building blocks of life. Chang'e-6 returned samples from the lunar far side in 2024, providing new material for such studies.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cnsa.gov.cn/n6758823/n6758838/c10633840/content.html">嫦娥六号月壤样本首批研究成果发布！</a></li>
<li><a href="https://zh.wikipedia.org/zh-hans/碳質球粒隕石">碳质球粒陨石 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.cas.cn/syky/202511/t20251117_5089008.shtml">嫦娥六号月背样品中首次发现晶质赤铁矿和磁赤铁矿----中国科学院</a></li>

</ul>
</details>

**Tags**: `#lunar science`, `#asteroid impacts`, `#Chang'e-6`, `#planetary evolution`, `#space exploration`

---

<a id="item-10"></a>
## [China Launches 180-Qubit Superconducting Quantum Computer 'Origin Wukong-180'](https://news.mydrivers.com/1/1121/1121031.htm) ⭐️ 8.0/10

China's fourth-generation superconducting quantum computer, Origin Wukong-180, has been launched, featuring 180 computational qubits and 251 coupling qubits on a single chip. It achieves single-qubit gate fidelity of 99.9%, two-qubit gate fidelity of 99%, and readout fidelity of 99%, and is now open for global quantum computing tasks. This marks a significant leap from 72 to 180 qubits in China's superconducting quantum computing capability, demonstrating progress in full-stack independent development. The high-fidelity gates and open access could accelerate research in quantum algorithms, materials science, and drug discovery globally. The computer uses a single-chip architecture with 180 computational qubits and 251 coupling qubits, all developed by Origin Quantum. Its predecessor, the 72-qubit Origin Wukong, has served over 47 million visits from 163 countries since January 2024.

rss · 快科技 · May 9, 10:08

**Background**: Superconducting qubits are a leading quantum computing technology that operate at near absolute zero temperatures. Gate fidelity measures how accurately quantum operations are performed; 99.9% fidelity is considered high but still below the 99.998% record achieved by MIT using fluxonium qubits. China's quantum computing ecosystem includes full-stack development from chips to operating systems.

<details><summary>References</summary>
<ul>
<li><a href="https://originqc.com.cn/en/">Origin Quantum – Building China's Independently Controllable...</a></li>
<li><a href="https://www.chinadaily.com.cn/a/202504/07/WS67f3a2bba3104d9fd381df3e.html">China's Origin Wukong quantum computer... - Chinadaily.com.cn</a></li>
<li><a href="https://news.mit.edu/2025/fast-control-methods-enable-record-setting-fidelity-superconducting-qubit-0114">Fast control methods enable record-setting fidelity in...</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#superconducting qubits`, `#China`, `#hardware`, `#technology`

---

<a id="item-11"></a>
## [Intel Re-Enters Apple Supply Chain to Manufacture Some Chips](https://news.mydrivers.com/1/1121/1121017.htm) ⭐️ 8.0/10

Apple and Intel have reached a preliminary agreement for Intel to manufacture some of Apple's chips, including low-end M-series and possibly A-series, reducing reliance on TSMC. This marks a major shift in Apple's supply chain strategy, breaking TSMC's monopoly on Apple chip manufacturing and giving Apple a second source to mitigate capacity risks and cost pressures. The partnership initially focuses on low-end M-series chips for iPads and Macs, potentially extending to non-Pro iPhone A-series chips. Intel's 18A (1.8nm) and 14A (1.4nm) processes are key to winning the deal, with first chips expected in 2027–2028.

rss · 快科技 · May 9, 07:12

**Background**: Apple has been exclusively using TSMC for its custom chips since transitioning from Intel processors in 2020. However, TSMC's capacity has been strained by AI demand from companies like Nvidia, causing supply shortages for Apple. Intel, under new CEO Lip-Bu Tan, is revitalizing its foundry business with advanced nodes like 18A and 14A, aiming to compete with TSMC.

<details><summary>References</summary>
<ul>
<li><a href="https://www.intel.com/content/www/us/en/foundry/process/18a.html">Intel 18A | See Our Biggest Process Innovation</a></li>
<li><a href="https://www.tomshardware.com/pc-components/cpus/intels-18a-production-starts-before-tsmcs-competing-n2-tech-heres-how-the-two-process-nodes-compare">Intel's 18A production starts before TSMC’s competing N2 tech ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_silicon">Apple silicon - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#Intel`, `#chip manufacturing`, `#supply chain`, `#semiconductors`

---

<a id="item-12"></a>
## [Three Chinese AI startups raise $10B+ in a week](https://www.tmtpost.com/7981913.html) ⭐️ 8.0/10

In a single week, Chinese AI startups DeepSeek, Stepfun, and Moonshot AI collectively raised over $10 billion, with DeepSeek's valuation tripling in three weeks. This marks the end of the pricing war and the beginning of a knockout phase in China's large model market. This funding surge signals a critical consolidation phase in China's AI industry, where only well-capitalized players can survive. It also intensifies global competition in large language models, challenging US dominance. DeepSeek, known for its cost-efficient R1 model, is backed by hedge fund High-Flyer; Stepfun raised ~$2.5B and is preparing for a Hong Kong IPO; Moonshot AI raised ~$2B for its Kimi K2 model. The total exceeds $10B.

rss · 钛媒体 · May 9, 07:04

**Background**: Chinese AI large model startups have been in a fierce pricing war to gain market share. DeepSeek's open-weight models, trained at a fraction of the cost of US counterparts, disrupted the industry in early 2025. The recent funding round indicates a shift from price competition to a survival-of-the-fittest phase.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://www.thepaper.cn/newsDetail_forward_33120328">阶跃星辰将完成近25亿美元融资，已拆除红筹架构，加速冲刺港股IPO_10%...</a></li>
<li><a href="https://www.geekpark.net/news/363775">传月之暗面新融 20 亿美元，估值超 200...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#funding`, `#China`, `#large language models`, `#market consolidation`

---