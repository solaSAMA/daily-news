---
layout: default
title: "Daily News 2026-05-10"
date: 2026-05-10
lang: zh
---

> From 271 items, 12 important content pieces were selected

---

1. [数学家实测 ChatGPT 5.5 Pro 解决研究问题](#item-1) ⭐️ 9.0/10
2. [Bun 实验性 Rust 重写达到 99.8% 测试兼容性](#item-2) ⭐️ 8.0/10
3. [Let-go：用 Go 实现的类 Clojure 语言，启动仅需 7 毫秒](#item-3) ⭐️ 8.0/10
4. [LLM 在委托任务中会损坏文档](#item-4) ⭐️ 8.0/10
5. [网络自由意志主义的虚伪](#item-5) ⭐️ 8.0/10
6. [提议将 Web 分叉为更简单的文档协议](#item-6) ⭐️ 8.0/10
7. [百度发布文心 5.1，训练成本降低 94%](#item-7) ⭐️ 8.0/10
8. [中芯国际创始人：执着 3nm/2nm 是误区](#item-8) ⭐️ 8.0/10
9. [嫦娥六号月壤揭示小行星撞击类型转变](#item-9) ⭐️ 8.0/10
10. [我国第四代超导量子计算机“本源悟空-180”上线](#item-10) ⭐️ 8.0/10
11. [英特尔重返苹果供应链，代工部分芯片](#item-11) ⭐️ 8.0/10
12. [三家中国 AI 公司一周内融资超百亿美元](#item-12) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [数学家实测 ChatGPT 5.5 Pro 解决研究问题](https://gowers.wordpress.com/2026/05/08/a-recent-experience-with-chatgpt-5-5-pro/) ⭐️ 9.0/10

菲尔兹奖得主蒂莫西·高尔斯报告称，ChatGPT 5.5 Pro 成功解决了几个温和的数学研究问题，展示了先进的推理和自我修正能力。 这表明大语言模型正接近协助真正数学研究的能力，可能改变博士生的培养方式和研究开展方式。 高尔斯指出，该模型能追踪自身推理并纠正错误，但仍需仔细引导且会出错。该模型是 OpenAI 于 2026 年 4 月 23 日发布的 GPT-5.5 Pro。

hackernews · _alternator_ · May 9, 02:41 · [社区讨论](https://news.ycombinator.com/item?id=48071262)

**背景**: 像 GPT-5.5 这样的大语言模型在大量文本数据上训练，能生成类似人类的文本。最近的基准测试显示，GPT-5.5 Pro 在 FrontierMath 问题（难度 1-3）上得分为 51.7%，表明其数学推理能力较强。该模型使用“思考”模式进行更深层次的推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.5">GPT-5.5 - Wikipedia</a></li>
<li><a href="https://help.openai.com/en/articles/11909943-gpt-5-1-in-chatgpt">GPT-5.5 in ChatGPT | OpenAI Help Center</a></li>
<li><a href="https://maa.org/math-values/how-will-ai-impact-mathematics-research/">How Will the New AI Impact Mathematics Research? – Mathematical Association of America</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍同意高尔斯评估，指出模型自我修正能力提升，但成本高且易犯概念性错误。一些人提出哲学问题：当 AI 能轻易产生想法时，人类思想的价值何在。

**标签**: `#AI`, `#LLM`, `#mathematics`, `#research`, `#education`

---

<a id="item-2"></a>
## [Bun 实验性 Rust 重写达到 99.8% 测试兼容性](https://twitter.com/jarredsumner/status/2053047748191232310) ⭐️ 8.0/10

Bun 的创建者 Jarred Sumner 在 Twitter 上宣布，Bun 的实验性 Rust 重写已在 Linux x64 glibc 上达到 99.8% 的测试兼容性。 这一里程碑表明对 Bun 进行完整的 Rust 重写是可行的，有望在保持与现有 Node.js 应用兼容的同时，提升内存安全性和性能。 重写仅用了 6 天时间，并借助了 LLM 辅助；一位 Bun 开发者指出，该代码是实验性的，可能会被完全丢弃。

hackernews · heldrida · May 9, 10:12 · [社区讨论](https://news.ycombinator.com/item?id=48073680)

**背景**: Bun 是一个旨在替代 Node.js 的 JavaScript 运行时，最初用 Zig 编写。实验性的 Rust 重写旨在利用 Rust 的内存安全保证和生态系统，而 99.8% 的测试兼容性意味着几乎所有现有的 Bun 测试都能在 Rust 版本上通过。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/bun: Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one</a></li>
<li><a href="https://thecodersblog.com/bun-runtime-migration-from-zig-to-rust-2026/">Bun's Rust Pivot: What the Zig-to-Rust Migration Means for JavaScript Runtime Performance in 2026 | The Coders Blog | Home</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：一些人称赞重写的速度和潜力，而另一些人则因大量使用 LLM 以及放弃 Zig 设计理念而表示不信任。一位 Bun 开发者澄清说，重写是实验性的，可能不会被采用。

**标签**: `#Bun`, `#Rust`, `#JavaScript runtime`, `#rewrite`, `#LLM`

---

<a id="item-3"></a>
## [Let-go：用 Go 实现的类 Clojure 语言，启动仅需 7 毫秒](https://github.com/nooga/let-go) ⭐️ 8.0/10

Let-go 是一种用纯 Go 实现的类 Clojure 语言，启动时间约 7 毫秒，比 JVM 上的 Clojure 快约 50 倍，比 Babashka 快 3 倍。它打包为约 10MB 的静态二进制文件，并包含与 Calva 和 CIDER 兼容的 nREPL 服务器。 该项目将 Clojure 的表达性语法和函数式范式带入了对快速启动和小体积二进制文件有严格要求的场景，如 CLI、Web 服务器和脚本。它还展示了类 Lisp 语言可以高效嵌入 Go 程序，可能扩大 Clojure 在 JVM 之外的影响力。 Let-go 与 JVM Clojure 的兼容性约为 90%，使用手工打造的编译器和栈式虚拟机。它支持 AOT 编译为可移植字节码或独立二进制文件，并且可以嵌入 Go 程序，实现函数、结构体和通道的无缝互操作。

hackernews · marcingas · May 9, 17:52 · [社区讨论](https://news.ycombinator.com/item?id=48076815)

**背景**: Clojure 是一种动态、函数式的 Lisp 方言，主要运行在 JVM 上，以不可变数据结构和并发支持著称。Babashka 是一个用于脚本的原生 Clojure 解释器，利用 GraalVM 实现快速启动；sci 也是一个基于 GraalVM 的 Clojure 解释器库。Let-go 旨在通过利用 Go 的编译和运行时，提供更快的启动和更简单的嵌入体验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Babashka">Babashka</a></li>
<li><a href="https://babashka.org/">Babashka</a></li>
<li><a href="https://nrepl.org/nrepl/usage/server.html">nREPL Server :: nREPL</a></li>

</ul>
</details>

**社区讨论**: 社区表现出浓厚兴趣，有用户称其为“我一直寻找的那种 Clojure 移植版本”。其他人提到了相关项目如 Glojure，并指出 Let-go、Glojure 和 Gloat 在 AOT 编译方面的合作。还有人建议将 Let-go 加入 awesome-clojure-likes 列表。

**标签**: `#Clojure`, `#Go`, `#Programming Language`, `#Performance`, `#REPL`

---

<a id="item-4"></a>
## [LLM 在委托任务中会损坏文档](https://arxiv.org/abs/2604.15597) ⭐️ 8.0/10

一项新研究通过实验证明，大型语言模型在用于委托任务时会系统性地损坏文档，每次传递都会降低意图和精确度，类似于有损压缩。 这一发现挑战了基于 LLM 的代理在需要精确文档处理的任务（如科学写作或法律起草）中的可靠性，并强调了谨慎设计代理的必要性。 该研究使用了一个基本的代理框架，包含文件读写和代码执行工具，发现即使使用工具，文档损坏仍然存在。研究者创造了“语义消融”一词来描述细微差别的逐渐丧失。

hackernews · rbanffy · May 9, 08:44 · [社区讨论](https://news.ycombinator.com/item?id=48073246)

**背景**: 大型语言模型通过预测下一个词元来生成文本，在处理长文档时可能导致信息丢失。这类似于反复保存 JPEG 图像，每次压缩都会降低质量。该研究为委托场景中的这一现象提供了实验证据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2604.07569">Learning is Forgetting: LLM Training As Lossy Compression</a></li>
<li><a href="https://www.researchgate.net/figure/Syntactic-similarity-with-semantic-ablation-The-shaded-colored-areas-represent-1_fig2_399595405">Syntactic similarity with semantic ablation. The shaded colored areas... | Download Scientific Diagram</a></li>

</ul>
</details>

**社区讨论**: 社区成员普遍同意这一发现，一些人指出经常使用 LLM 的用户已经避免来回传递内容。一位评论者对工具使用的结果表示怀疑，认为代理框架可能不是最优的。其他人则强调设计代理时应尽量减少 LLM 的往返调用。

**标签**: `#LLMs`, `#document corruption`, `#semantic ablation`, `#AI agents`, `#empirical study`

---

<a id="item-5"></a>
## [网络自由意志主义的虚伪](https://matduggan.com/the-intolerable-hypocrisy-of-cyberlibertarianism/) ⭐️ 8.0/10

Mat Duggan 的一篇文章指出，网络自由意志主义是虚伪的，因为科技领袖在原则变得不便时就会抛弃自由和去中心化的理念。 这一批评挑战了硅谷的根基意识形态，质疑科技领袖是否真正信奉他们所宣扬的自由意志主义价值观，还是仅仅利用这些价值观来为放松管制和牟利辩护。 文章指出了诸多矛盾，例如一方面主张最小化政府干预，另一方面又寻求国家保护知识产权；一方面鼓吹去中心化，另一方面却构建中心化平台。

hackernews · ColinWright · May 9, 13:48 · [社区讨论](https://news.ycombinator.com/item?id=48074952)

**背景**: 网络自由意志主义是一种源于早期互联网文化的政治意识形态，主张在线领域最小化政府监管、最大化个人自由。它影响了许多科技企业家和互联网的早期精神。该文章认为，这种意识形态内部存在矛盾，且其支持者在与商业利益冲突时常常将其抛弃。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://matduggan.com/the-intolerable-hypocrisy-of-cyberlibertarianism/">The Intolerable Hypocrisy of Cyberlibertarianism</a></li>
<li><a href="https://en.wikipedia.org/wiki/Technolibertarianism">Technolibertarianism - Wikipedia</a></li>
<li><a href="https://news.ycombinator.com/item?id=48074952">The Intolerable Hypocrisy of Cyberlibertarianism | Hacker News</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的评论反应不一：有人同意这一批评，指出科技领袖在规模化后往往转向支持监管；也有人为网络自由意志主义辩护，认为理想本身仍然有效，只是应用不完美。用户 schoen 是约翰·佩里·巴洛的崇拜者，他部分同意文章观点，但指出《网络空间独立宣言》中的细微差别。

**标签**: `#cyberlibertarianism`, `#tech criticism`, `#internet culture`, `#politics`

---

<a id="item-6"></a>
## [提议将 Web 分叉为更简单的文档协议](https://dillo-browser.org/lab/web-fork/) ⭐️ 8.0/10

Dillo 浏览器网站上的一项提议建议将 Web 分叉为一个更简单的、仅用于文档的协议，重新引发了关于 Web 从文档向应用程序演变的讨论。 该提议挑战了当前以应用程序为中心的 Web 模式，可能影响未来的协议设计、安全性和用户体验，尤其对那些寻求像 Gemini 这样轻量级、不可执行替代方案的人。 该提议强调严格的正式语法并拒绝不符合规范的页面，这让人联想到因采用率低而失败的 XHTML。它还突出了文档范式与应用范式之间的紧张关系。

hackernews · wrxd · May 9, 11:33 · [社区讨论](https://news.ycombinator.com/item?id=48074087)

**背景**: Web 最初是为超文本文档设计的，但后来演变成了复杂应用程序的平台。像 Gemini 这样的协议提供了更简单的、仅用于文档的替代方案，但缺乏现代 Web 的交互能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gemini_(protocol)">Gemini (protocol)</a></li>
<li><a href="https://news.ycombinator.com/item?id=45498068">It's not against the rules, but it is hostile to the web. Forking the web.....</a></li>
<li><a href="https://geminiprotocol.net/">Gemini protocol</a></li>

</ul>
</details>

**社区讨论**: 评论者就严格仅文档协议的实用性展开辩论，引用了 XHTML 的失败以及浏览器作为应用程序引擎的角色。一些人主张为了安全和乐趣而简化 Web，而另一些人则认为这无利可图或不切实际。

**标签**: `#web`, `#browsers`, `#protocols`, `#standards`, `#gemini`

---

<a id="item-7"></a>
## [百度发布文心 5.1，训练成本降低 94%](https://36kr.com/newsflashes/3801731549371905?f=rss) ⭐️ 8.0/10

百度正式发布新一代基础大模型文心 5.1，该模型在 LMArena 搜索榜上位列国内第一、全球第四，而预训练成本仅为业界同规模模型的 6%。 此次发布表明，高性能基础模型可以以极低的成本训练，有望降低先进 AI 能力的门槛。同时，它巩固了百度在中国 AI 市场与 DeepSeek 等对手竞争的地位。 文心 5.1 采用“多维弹性预训练”技术，将总参数压缩至文心 5.0 的三分之一左右，激活参数压缩至二分之一左右，同时继承了 5.0 的知识储备。它在 LMArena 搜索榜上获得 1223 分，在智能体能力上超越 DeepSeek-V4-Pro，创意写作能力与 Gemini 3.1 Pro 持平。

rss · 36氪 · May 9, 07:21

**背景**: LMArena（原名 Chatbot Arena）是 LMSYS 创建的开放式 AI 模型评测平台，通过人类偏好评估模型。文心 5.1 这样的基础模型是在海量数据上训练的大型神经网络，可执行多种任务。“多维弹性预训练”技术允许一次训练生成多种规模的模型，从而降低成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chinaz.com/2026/0509/1751121.shtml">百度文心大模型5.1正式发布</a></li>
<li><a href="https://www.chinaz.com/ainews/27813.shtml">百度发布文心大模型5.1：搜索能力位居国内首位，预训练成本仅为业界6%</a></li>
<li><a href="https://www.donews.com/news/detail/1/6548337.html">百度文心大模型 5.1发布：登上LMArena搜索榜国内第一- DoNews</a></li>

</ul>
</details>

**标签**: `#AI`, `#large language model`, `#Baidu`, `#foundation model`, `#benchmark`

---

<a id="item-8"></a>
## [中芯国际创始人：执着 3nm/2nm 是误区](https://news.mydrivers.com/1/1121/1121139.htm) ⭐️ 8.0/10

中芯国际创始人张汝京近日接受专访时指出，半导体产业过度追求 3nm/2nm 等先进制程是认知误区，超过 80%的市场需求来自成熟制程和利基型市场，中国企业更容易在这些领域打破海外垄断。 这一观点挑战了“唯先进制程论”的主流叙事，为中国半导体产业提供了更务实的突围策略，可能引导资源向利基市场和边缘 AI 领域倾斜，提升中国企业的全球竞争力。 张汝京强调，工业控制、车载电子、可穿戴设备等利基市场常被忽视但潜力巨大。他还提醒初创企业应避免扎堆云端大算力芯片的烧钱赛道，转而聚焦分布式 AI 和边缘计算应用。

rss · 快科技 · May 9, 20:07

**背景**: 半导体制造通常分为先进制程（如 7nm、5nm、3nm）和成熟制程（如 28nm 及以上）。先进制程对智能手机和 AI 数据中心等高性能芯片至关重要，而成熟制程服务于汽车、物联网、电源管理等多种应用。利基市场指具有特定需求的细分领域，常被少数成熟厂商垄断。边缘 AI 是指在设备本地运行 AI 算法而非云端，可实现实时处理和隐私保护。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.dramx.com/News/made-sealing/20240711-36651.html">晶圆代工成熟制程芯片“不香”了？-全球半导体观察</a></li>
<li><a href="https://www.inhand.com.cn/support/blogs/what-is-edge-ai/">什么是边缘AI - 映翰通</a></li>

</ul>
</details>

**标签**: `#semiconductors`, `#China`, `#advanced nodes`, `#niche markets`, `#AI chips`

---

<a id="item-9"></a>
## [嫦娥六号月壤揭示小行星撞击类型转变](https://news.mydrivers.com/1/1121/1121116.htm) ⭐️ 8.0/10

中科院研究人员通过分析嫦娥六号月壤中的铁镍金属颗粒，发现 43 亿至 28 亿年前撞击地月系统的小行星类型从普通球粒陨石转变为碳质球粒陨石。 这一发现为早期地月系统水和有机物的输送提供了关键约束，因为碳质小行星富含挥发分。同时有助于完善太阳系动力学演化模型和晚期增生时间线。 研究团队识别出 40 个含金属颗粒的撞击碎屑，其中 28 个来自 28 亿年前的月海玄武岩，12 个来自 43 亿年前的古老高地物质。较年轻的碎屑中碳质球粒陨石特征比例显著更高。

rss · 快科技 · May 9, 17:21

**背景**: 月球表面保存了近 40 亿年小行星撞击的完整记录，而地球上的古老撞击痕迹已被抹去。碳质球粒陨石是一类小行星，含水率高达 22%，并含有有机化合物，被认为是生命组成成分的关键输送者。嫦娥六号于 2024 年从月球背面带回样本，为这类研究提供了新材料。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnsa.gov.cn/n6758823/n6758838/c10633840/content.html">嫦娥六号月壤样本首批研究成果发布！</a></li>
<li><a href="https://zh.wikipedia.org/zh-hans/碳質球粒隕石">碳质球粒陨石 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.cas.cn/syky/202511/t20251117_5089008.shtml">嫦娥六号月背样品中首次发现晶质赤铁矿和磁赤铁矿----中国科学院</a></li>

</ul>
</details>

**标签**: `#lunar science`, `#asteroid impacts`, `#Chang'e-6`, `#planetary evolution`, `#space exploration`

---

<a id="item-10"></a>
## [我国第四代超导量子计算机“本源悟空-180”上线](https://news.mydrivers.com/1/1121/1121031.htm) ⭐️ 8.0/10

我国第四代自主超导量子计算机“本源悟空-180”正式上线，搭载单核 180 个计算比特和 251 个耦合比特，单比特逻辑门保真度达 99.9%，双比特门保真度 99%，读取保真度 99%，即日起面向全球接收量子计算任务。 这标志着中国超导量子计算从 72 比特迈入 180 比特时代，展示了全链条自主可控的进展。高保真度量子门和开放访问将加速全球量子算法、材料模拟和药物研发等领域的研究。 该计算机采用单芯片架构，包含 180 个计算比特和 251 个耦合比特，全部由本源量子自主研发。其前身 72 比特“本源悟空”自 2024 年 1 月上线以来，已服务来自 163 个国家和地区的超过 4700 万次访问。

rss · 快科技 · May 9, 10:08

**背景**: 超导量子比特是一种领先的量子计算技术，需要在接近绝对零度的温度下运行。量子门保真度衡量量子操作的精确度；99.9%的保真度被认为很高，但仍低于 MIT 利用 fluxonium 量子比特实现的 99.998%纪录。中国的量子计算生态系统包括从芯片到操作系统的全栈自主研发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://originqc.com.cn/en/">Origin Quantum – Building China's Independently Controllable...</a></li>
<li><a href="https://www.chinadaily.com.cn/a/202504/07/WS67f3a2bba3104d9fd381df3e.html">China's Origin Wukong quantum computer... - Chinadaily.com.cn</a></li>
<li><a href="https://news.mit.edu/2025/fast-control-methods-enable-record-setting-fidelity-superconducting-qubit-0114">Fast control methods enable record-setting fidelity in...</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#superconducting qubits`, `#China`, `#hardware`, `#technology`

---

<a id="item-11"></a>
## [英特尔重返苹果供应链，代工部分芯片](https://news.mydrivers.com/1/1121/1121017.htm) ⭐️ 8.0/10

苹果与英特尔达成初步协议，由英特尔代工部分苹果芯片，包括低端 M 系列和可能的 A 系列，从而减少对台积电的依赖。 这标志着苹果供应链战略的重大转变，打破了台积电对苹果芯片制造的垄断，为苹果提供了第二来源，以缓解产能风险和成本压力。 合作初期聚焦于 iPad 和 Mac 的低端 M 系列芯片，未来可能延伸至非 Pro 版 iPhone 的 A 系列芯片。英特尔的 18A（1.8nm）和 14A（1.4nm）工艺是赢得订单的关键，首批芯片预计 2027-2028 年面世。

rss · 快科技 · May 9, 07:12

**背景**: 自 2020 年从英特尔处理器过渡以来，苹果一直独家使用台积电生产其自研芯片。然而，台积电的产能因英伟达等公司的 AI 需求而紧张，导致苹果供应短缺。英特尔在新 CEO 陈立武的领导下，正通过 18A 和 14A 等先进节点重振代工业务，旨在与台积电竞争。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.intel.com/content/www/us/en/foundry/process/18a.html">Intel 18A | See Our Biggest Process Innovation</a></li>
<li><a href="https://www.tomshardware.com/pc-components/cpus/intels-18a-production-starts-before-tsmcs-competing-n2-tech-heres-how-the-two-process-nodes-compare">Intel's 18A production starts before TSMC’s competing N2 tech ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_silicon">Apple silicon - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Apple`, `#Intel`, `#chip manufacturing`, `#supply chain`, `#semiconductors`

---

<a id="item-12"></a>
## [三家中国 AI 公司一周内融资超百亿美元](https://www.tmtpost.com/7981913.html) ⭐️ 8.0/10

一周内，中国 AI 初创公司 DeepSeek、阶跃星辰和月之暗面合计融资超百亿美元，其中 DeepSeek 估值三周翻五倍。这标志着国内大模型市场定价博弈结束，淘汰赛正式进入下半场。 这轮融资潮标志着中国 AI 行业进入关键整合期，只有资金雄厚的玩家才能生存。同时加剧了全球大语言模型竞争，挑战美国的主导地位。 DeepSeek 以其高性价比的 R1 模型闻名，由对冲基金 High-Flyer 支持；阶跃星辰融资约 25 亿美元，正筹备港股 IPO；月之暗面为其 Kimi K2 模型融资约 20 亿美元。总额超百亿美元。

rss · 钛媒体 · May 9, 07:04

**背景**: 中国 AI 大模型初创公司此前陷入激烈的价格战以争夺市场份额。DeepSeek 的开源权重模型训练成本仅为美国同行的零头，在 2025 年初颠覆了行业。本轮融资表明竞争从价格战转向优胜劣汰阶段。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://www.thepaper.cn/newsDetail_forward_33120328">阶跃星辰将完成近25亿美元融资，已拆除红筹架构，加速冲刺港股IPO_10%...</a></li>
<li><a href="https://www.geekpark.net/news/363775">传月之暗面新融 20 亿美元，估值超 200...</a></li>

</ul>
</details>

**标签**: `#AI`, `#funding`, `#China`, `#large language models`, `#market consolidation`

---