---
layout: default
title: "Daily News 2026-05-13"
date: 2026-05-13
lang: zh
---

> From 287 items, 18 important content pieces were selected

---

1. [CERT 发布 dnsmasq 六个严重 CVE 漏洞](#item-1) ⭐️ 9.0/10
2. [Bambu Lab 被指滥用开源社会契约](#item-2) ⭐️ 9.0/10
3. [CVE-2026-45185：Exim 邮件服务器严重未授权远程代码执行漏洞](#item-3) ⭐️ 9.0/10
4. [Needle：从 Gemini 蒸馏出的 2600 万参数工具调用模型](#item-4) ⭐️ 8.0/10
5. [DuckDB 发布 Quack 客户端-服务器协议，实现水平扩展](#item-5) ⭐️ 8.0/10
6. [Obsidian 推出新插件审核系统与社区网站](#item-6) ⭐️ 8.0/10
7. [加拿大 C-22 法案重提数据留存与加密后门，隐私面临新威胁](#item-7) ⭐️ 8.0/10
8. [谷歌与 SpaceX 合作推进太空数据中心，计划 2027 年发射原型](#item-8) ⭐️ 8.0/10
9. [中国电信实现 40Tbps 量子-经典空芯共纤传输创全球纪录](#item-9) ⭐️ 8.0/10
10. [谷歌今夏推出 Gemini Intelligence，重塑安卓 AI 交互](#item-10) ⭐️ 8.0/10
11. [Hugging Face 现山寨 OpenAI 隐私过滤器，下载超 20 万次含木马](#item-11) ⭐️ 8.0/10
12. [月壤纤维样品进入中国空间站开展舱外验证](#item-12) ⭐️ 8.0/10
13. [iOS 27 重磅改版：Siri 独立应用上线，对标 ChatGPT](#item-13) ⭐️ 8.0/10
14. [谷歌与苹果合作实现安卓与 iPhone 跨平台互传及 eSIM 转移](#item-14) ⭐️ 8.0/10
15. [谷歌报告：黑客利用 AI 发现零日漏洞](#item-15) ⭐️ 8.0/10
16. [小米下半年将推出自研芯片+OS+AI 大模型商用终端](#item-16) ⭐️ 8.0/10
17. [世界首次！我国将人工胚胎送入太空](#item-17) ⭐️ 8.0/10
18. [OpenAI 前 CTO 发布最人性化 AI 交互模型](#item-18) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [CERT 发布 dnsmasq 六个严重 CVE 漏洞](https://lists.thekelleys.org.uk/pipermail/dnsmasq-discuss/2026q2/018471.html) ⭐️ 9.0/10

CERT 发布了六个针对广泛使用的 DNS/DHCP 服务器 dnsmasq 的严重安全漏洞的 CVE。这些漏洞影响最新版本之前的版本，可能导致远程代码执行或拒绝服务。 dnsmasq 嵌入在无数路由器、物联网设备和 Linux 发行版中，因此这些漏洞具有巨大的潜在攻击面。这一事件重新引发了关于采用 Rust 或 Go 等内存安全语言来替代基于 C 的网络服务的讨论。 这六个 CVE 涵盖多个内存安全问题，包括缓冲区溢出和释放后使用漏洞。上游已发布补丁，但 Debian stable 和 OpenWRT 等发行版可能更新缓慢，导致用户暴露在风险中。

hackernews · chizhik-pyzhik · May 12, 18:12 · [社区讨论](https://news.ycombinator.com/item?id=48112042)

**背景**: dnsmasq 是一个轻量级 DNS 转发器、DHCP 服务器和 TFTP 服务器，常用于家用路由器和嵌入式系统。它使用内存不安全的 C 语言编写，因此容易受到内存损坏漏洞的影响。CVE（通用漏洞与暴露）是一个用于识别和编目安全缺陷的标准化系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dnsmasq">Dnsmasq</a></li>
<li><a href="https://en.wikipedia.org/wiki/Common_Vulnerabilities_and_Exposures">Common Vulnerabilities and Exposures - Wikipedia</a></li>
<li><a href="https://www.memorysafety.org/docs/memory-safety/">What is memory safety and why does it matter? - Prossimo</a></li>

</ul>
</details>

**社区讨论**: 评论者意见不一：一些人认为这是迁移到 Rust 或 Go 等内存安全语言的转折点，而另一些人则批评 Debian 的补丁更新缓慢。还有用户推广自己经过审计的 DNS 服务器 MaraDNS 作为更安全的替代方案。

**标签**: `#security`, `#dnsmasq`, `#CVE`, `#memory safety`, `#open source`

---

<a id="item-2"></a>
## [Bambu Lab 被指滥用开源社会契约](https://www.jeffgeerling.com/blog/2026/bambu-lab-abusing-open-source-social-contract/) ⭐️ 9.0/10

Bambu Lab 正在限制其 3D 打印机的局域网模式，即使仅本地操作也需要授权，并采用薄弱的安全理由，批评者认为这违反了开源社会契约。 这一争议削弱了对封闭生态系统的信任，并凸显了开源社区与基于开源软件但施加限制性政策的硬件公司之间的紧张关系。 Bambu Lab 的局域网模式更改强制用户即使在不使用云服务时也要进行身份验证，公司以未授权流量激增为由，但批评者指出基于用户代理字符串进行拦截并非真正的安全措施。

hackernews · rubenbe · May 12, 14:54 · [社区讨论](https://news.ycombinator.com/item?id=48109224)

**背景**: 开源社会契约指的是开源软件即使在商业产品中使用也应保持自由和无限制的期望。Bambu Lab 的固件基于 Marlin 和 Klipper 等开源项目，但该公司逐渐锁定功能，激怒了社区。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.jeffgeerling.com/blog/2026/bambu-lab-abusing-open-source-social-contract/">Bambu Lab is abusing the open source social contract</a></li>
<li><a href="https://wiki.bambulab.com/en/knowledge-sharing/enable-lan-mode">How to enable LAN Mode on Bambu Lab printers | Bambu Lab Wiki</a></li>
<li><a href="https://consumerrights.wiki/w/Wiki/Bambu_Lab_Authorization_Control_System">Bambu Lab Authorization Control System - Consumer Rights Wiki</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了愤怒，许多人指出局域网模式是在之前的强烈反对后才添加的。一些人认为 Bambu Lab 的安全借口站不住脚，而另一些人则指出对中国服务器和潜在间谍活动的更广泛担忧，尽管这些说法是推测性的。

**标签**: `#open source`, `#3D printing`, `#community trust`, `#corporate ethics`, `#Bambu Lab`

---

<a id="item-3"></a>
## [CVE-2026-45185：Exim 邮件服务器严重未授权远程代码执行漏洞](https://xbow.com/blog/dead-letter-cve-2026-45185-xbow-found-rce-exim) ⭐️ 9.0/10

XBOW 披露了 CVE-2026-45185，这是 Exim 4.99.3 之前版本中的一个未授权远程代码执行漏洞，影响使用 GnuTLS 的配置，源于 BDAT 正文解析中的释放后使用。协调的发行版更新已于 2026 年 5 月 12 日发布。 Exim 是类 Unix 系统上广泛使用的邮件传输代理，此严重 RCE 漏洞对数百万台服务器构成重大威胁。未授权攻击者可远程执行任意代码，可能导致服务器完全沦陷。 该漏洞是 BDAT 正文解析路径中的释放后使用，可远程触发且无需认证，影响使用 GnuTLS 的 Exim 4.99.3 之前版本。CVSS 评分尚未公布，但预计为严重级别。

hackernews · fedek_ · May 12, 17:52 · [社区讨论](https://news.ycombinator.com/item?id=48111748)

**背景**: Exim 是一款免费开源的邮件传输代理（MTA），用于类 Unix 操作系统上路由和投递邮件。它曾有多个严重漏洞的历史，包括 CVE-2023-42115 以及 2019-2020 年的其他漏洞。XBOW 是一家专注于漏洞发现和披露的安全研究公司。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Exim">Exim - Wikipedia</a></li>
<li><a href="https://www.thehackerwire.com/vulnerability/CVE-2026-45185/">CVE-2026-45185 - Info Vulnerability - TheHackerWire</a></li>

</ul>
</details>

**社区讨论**: 社区成员批评了披露时间线，指出发行版在公开披露前仅获得 2-4 天的提前通知，且协调发布后没有缓冲期。一些人对缺乏透明度表示不满，并将其与过去的 Exim 漏洞进行比较。

**标签**: `#CVE`, `#Exim`, `#RCE`, `#security`, `#MTA`

---

<a id="item-4"></a>
## [Needle：从 Gemini 蒸馏出的 2600 万参数工具调用模型](https://github.com/cactus-compute/needle) ⭐️ 8.0/10

Cactus Compute 开源了 Needle，一个从 Gemini 蒸馏出的 2600 万参数函数调用模型，在消费级设备上达到 6000 tok/s 预填充和 1200 tok/s 解码。该模型仅使用注意力和门控层，没有 MLP，经过 2000 亿 token 预训练和 20 亿 token 合成函数调用数据后训练。 Needle 证明了工具调用可以由极小的模型高效处理，从而在手机、手表和眼镜上实现设备端智能体 AI。其架构挑战了大型前馈网络是必要的假设，有望降低智能体应用的成本和延迟。 该模型在单次函数调用上优于 FunctionGemma-270M、Qwen-0.6B、Granite-350M 和 LFM2.5-350M，但这些模型具有更广泛的对话能力。Needle 采用 MIT 许可，权重在 Hugging Face 上，完整架构说明在 GitHub 上。

hackernews · HenryNdubuaku · May 12, 18:03 · [社区讨论](https://news.ycombinator.com/item?id=48111896)

**背景**: 知识蒸馏将知识从大模型转移到小模型，使其能够在性能较低的硬件上部署。函数调用允许模型从外部系统请求数据或操作。交叉注意力捕获两个不同输入序列之间的关系，使其适合像工具调用这样的检索与组装任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Distillation_(machine_learning)">Distillation (machine learning)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Attention_(machine_learning)">Attention (machine learning) - Wikipedia</a></li>
<li><a href="https://docs.oracle.com/en-us/iaas/Content/generative-ai/function.htm">Function Calling</a></li>

</ul>
</details>

**社区讨论**: 评论者对浏览器兼容性（ONNX 转换）、命令行自然语言参数解析和实时演示表示兴趣。一些人赞扬了对小型模型的推动，并讨论了使用多个小型智能体进行编排。一个小建议是使用 '0.026B' 而不是 '26M' 以更清晰。

**标签**: `#tool calling`, `#small language models`, `#on-device AI`, `#distillation`, `#function calling`

---

<a id="item-5"></a>
## [DuckDB 发布 Quack 客户端-服务器协议，实现水平扩展](https://duckdb.org/2026/05/12/quack-remote-protocol) ⭐️ 8.0/10

DuckDB 宣布推出 Quack，一种新的客户端-服务器协议，支持远程查询执行和水平扩展，允许多个用户通过网络查询同一个 DuckDB 实例。 这使 DuckDB 的用例从嵌入式分析扩展到多用户、基于服务器的部署，使其成为需要并发和扩展的中小型分析工作负载的可行选择。 Quack 使用针对分析查询优化的自定义有线协议，支持流式结果、预编译语句和身份验证等功能。它旨在与 DuckDB 现有生态系统配合使用，包括使用 DuckDB 驱动程序的工具。

hackernews · aduffy · May 12, 17:54 · [社区讨论](https://news.ycombinator.com/item?id=48111765)

**背景**: DuckDB 是一种嵌入式分析数据库，传统上在宿主进程内运行，仅限于单用户场景。Quack 引入了一个独立的服务器进程，可以处理多个客户端连接，并通过添加更多服务器节点实现水平扩展。这类似于 SQLite 通过服务器层进行扩展的方式，但 Quack 是原生内置于 DuckDB 中的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://motherduck.com/duckdb-book-summary-chapter7/">DuckDB in Action - Chapter 7 - DuckDB in the Cloud with</a></li>
<li><a href="https://motherduck.com/blog/scaling-duckdb-with-ducklings/">MotherDuck’s approach to scaling DuckDB</a></li>
<li><a href="https://medium.com/@tanejagagan/scaling-duckdb-a-modern-architecture-for-analytical-data-applications-49e5a8dcd24a">Scaling DuckDB: A Modern Architecture for Analytical Data Applications | by Gagan Taneja | Medium</a></li>

</ul>
</details>

**社区讨论**: 社区对 Quack 感到兴奋，用户称赞它解决了内部应用和家庭实验室使用的水平扩展问题。一些用户正在探索实际应用，比如通过 SSH 设置自复制包装器，而另一些用户则质疑与 SQLite 等替代方案相比，带有 Quack 的 DuckDB 是否适合多用户读写场景。

**标签**: `#DuckDB`, `#database`, `#client-server`, `#protocol`, `#scalability`

---

<a id="item-6"></a>
## [Obsidian 推出新插件审核系统与社区网站](https://obsidian.md/blog/future-of-plugins/) ⭐️ 8.0/10

Obsidian 宣布推出新的社区网站和自动化插件审核系统，取代了此前成为瓶颈的人工审核流程。该系统不仅审核初始提交，还会对每个版本进行安全性和代码质量扫描。 这解决了 Obsidian 插件生态系统的关键扩展瓶颈，缓解了开发者的挫败感和团队的工作压力。它确保平台能够在保障安全的同时继续发展，而不会限制插件的可用性。 自动化审核系统会检查每个插件版本的安全性和代码质量，而不仅仅是初始提交。新的社区网站为发现和讨论插件提供了一个集中枢纽。

hackernews · xz18r · May 12, 15:45 · [社区讨论](https://news.ycombinator.com/item?id=48109970)

**背景**: Obsidian 是一款流行的笔记应用，通过开放 API 支持社区开发的插件。此前，所有插件提交都由一个小团队手动审核，随着插件数量快速增长（尤其是借助 AI 辅助开发），这种方式变得不可持续。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://obsidian.md/blog/future-of-plugins/">The future of Obsidian plugins - Obsidian</a></li>
<li><a href="https://obsidian.md/plugins">Plugins - Obsidian</a></li>
<li><a href="https://obsidian.md/help/community-plugins">Learn how to extend Obsidian with plugins built by the community.</a></li>

</ul>
</details>

**社区讨论**: 社区普遍欢迎这一变化，用户指出这缓解了一个主要瓶颈。一些人担心自动化检查能否可靠地检测恶意插件，建议改用适当的沙箱和权限系统。

**标签**: `#Obsidian`, `#plugins`, `#developer tools`, `#community`, `#security`

---

<a id="item-7"></a>
## [加拿大 C-22 法案重提数据留存与加密后门，隐私面临新威胁](https://www.eff.org/deeplinks/2026/05/canadas-bill-c-22-repackaged-version-last-years-surveillance-nightmare) ⭐️ 8.0/10

加拿大的 C-22 法案是去年失败监控法案的翻版，要求强制数据留存和加密后门，威胁到 Signal 和 WhatsApp 等服务。电子前哨基金会（EFF）警告，该法案可能迫使加密通讯应用封锁加拿大用户或削弱其安全性。 若通过，C-22 法案将为政府监控树立危险先例，可能在全球范围内削弱端到端加密。它可能迫使大型科技公司要么违反加拿大法律，要么降低所有用户的安全保障，影响隐私权和数字信任。 该法案包括对互联网服务提供商的强制数据留存要求，以及一项迫使公司在接到请求时解密通信的条款，实际上创建了加密后门。批评者认为，这将使所有用户面临黑客和滥用的风险，因为后门无法仅限于“好人”使用。

hackernews · Brajeshwar · May 12, 17:35 · [社区讨论](https://news.ycombinator.com/item?id=48111531)

**背景**: C-22 法案是加拿大政府继去年类似法案（C-2 法案）失败后，扩大监控权力的最新尝试。数据留存强制要求公司在一定期限内存储用户数据，而加密后门则是绕过加密的方法，常被执法部门要求。EFF 和加拿大公民自由协会等公民自由团体一直反对此类措施，认为它们侵犯隐私和安全。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.jccf.ca/national-post-liberals-have-canada-leading-the-west-in-state-surveillance/">National Post: Liberals have Canada leading the West in state...</a></li>
<li><a href="https://www.eff.org/issues/mandatory-data-retention">Mandatory Data Retention | Electronic Frontier Foundation</a></li>
<li><a href="https://www.internetsociety.org/blog/2025/05/what-is-an-encryption-backdoor/">What Is an Encryption Backdoor? - Internet Society</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了强烈反对，有人指出强制数据留存和后门将迫使加密服务封锁加拿大用户。另一评论者讽刺地欢迎该法案，称其为‘警钟’，可能推动反审查工具的创新。一些人呼吁读者联系自己的议员和公共安全部长，拒绝该立法。

**标签**: `#surveillance`, `#encryption`, `#privacy`, `#Canada`, `#legislation`

---

<a id="item-8"></a>
## [谷歌与 SpaceX 合作推进太空数据中心，计划 2027 年发射原型](https://www.ithome.com/0/949/562.htm) ⭐️ 8.0/10

谷歌与 SpaceX 正就轨道数据中心项目展开谈判，谷歌的 Project Suncatcher 计划在 2027 年前发射原型卫星。SpaceX 也已向监管机构申请发射多达 100 万颗卫星，以支撑其轨道数据中心愿景。 太空数据中心可利用太阳能供电，规避地面设施的土地占用和能耗瓶颈，有望推动云计算基础设施的范式转变。两大科技巨头的合作可能加速这一进程。 谷歌的 Project Suncatcher 计划使用搭载 Tensor 处理单元（TPU）的太阳能卫星进行 AI 计算。SpaceX 持有谷歌 6.1%的股份，已收购 xAI 并正在筹备大规模 IPO。

rss · IT之家 · May 12, 23:41

**背景**: 数据中心消耗大量电力和土地，促使业界探索太空替代方案。轨道数据中心利用太阳能板供电，在真空中辐射散热，可能提供无限的清洁能源。SpaceX 的星链已提供卫星互联网，类似技术可支撑轨道计算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/research/google-project-suncatcher/">Project Suncatcher explores powering AI in space - The Keyword</a></li>
<li><a href="https://money.usnews.com/investing/news/articles/2026-05-12/google-spacex-in-talks-to-explore-data-centers-in-orbit-wsj-reports">Google in Talks With SpaceX for Suncatcher Orbital Data ...</a></li>
<li><a href="https://www.satellitetoday.com/connectivity/2026/02/02/spacex-acquires-xai-to-pursue-orbital-data-center-constellation/">SpaceX Acquires xAI to Pursue Orbital Data Center Constellation</a></li>

</ul>
</details>

**标签**: `#cloud computing`, `#space technology`, `#data centers`, `#Google`, `#SpaceX`

---

<a id="item-9"></a>
## [中国电信实现 40Tbps 量子-经典空芯共纤传输创全球纪录](https://www.ithome.com/0/949/561.htm) ⭐️ 8.0/10

中国电信研究院联合科大国盾量子、长飞、中兴及北京邮电大学等团队，在百公里空芯光纤上成功实现 40Tbps（50×800Gbps）经典光通信与商用量子密钥分发（QKD）系统的稳定共传，安全密钥率达 9.56kbps，创下全球新纪录。 这一突破解决了在同一光纤中共传大容量经典信号与量子信号时长期存在的噪声抑制难题，为与现有光基础设施集成的量子安全通信网络的经济高效、规模化部署铺平了道路。 该团队首创了基于空芯光纤的量子-经典联合优化方案，首次将经典信道传输特性纳入优化框架，通过精确分配波长和发射功率来抑制非线性噪声。相关成果已发表于顶级光学期刊《光子学研究》（SCI 一区，影响因子 7.2）。

rss · IT之家 · May 12, 23:38

**背景**: 量子密钥分发（QKD）通过使用量子态共享加密密钥，提供理论上不可破解的加密。然而，QKD 信号极其微弱，容易被标准光纤中高功率的经典数据信号淹没，因此需要专用光纤或复杂的噪声抑制措施。空芯光纤通过空气而非玻璃导光，具有更低的延迟和更小的非线性效应，是共传的理想介质。此前在空芯光纤上的演示仅实现了较短距离（如 20 公里）或较低容量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.mdpi.com/1099-4300/26/7/601">Enhanced Coexistence of Quantum Key Distribution and Classical Communication over Hollow-Core and Multi-Core Fibers</a></li>
<li><a href="https://opg.optica.org/abstract.cfm?uri=cleo_fs-2025-JPS200_55">Experimental Coexistence of Quantum Key Distribution and Classical Communications over 20 km Hollow-core Fiber</a></li>
<li><a href="https://www.zdnet.com/article/quantum-cryptography-this-air-filled-fiber-optic-cable-can-transport-un-hackable-keys-say-researchers/">Quantum cryptography: This air-filled fiber optic cable can transport un-hackable keys, say researchers | ZDNET</a></li>

</ul>
</details>

**标签**: `#quantum key distribution`, `#optical fiber`, `#quantum communication`, `#telecommunications`, `#breakthrough`

---

<a id="item-10"></a>
## [谷歌今夏推出 Gemini Intelligence，重塑安卓 AI 交互](https://www.ithome.com/0/949/544.htm) ⭐️ 8.0/10

谷歌宣布推出 Gemini Intelligence，这是一套面向安卓的全新 AI 系统，可跨应用和网页自动完成多步骤任务，包括复杂表单填写、通过自然语言创建小组件以及 Gboard 语音润色。首批适配机型为 Pixel 10 和三星 Galaxy S26，今年夏季起分批推送。 Gemini Intelligence 标志着从被动语音助手向主动任务自动化的转变，可能彻底改变用户与安卓设备的交互方式。它有望大幅减少预订服务、购物等常见流程的手动操作，并为移动操作系统的 AI 集成树立新标杆。 该系统采用端云结合策略，简单请求由本地 Gemini Nano 处理。所有自动化操作都需要用户明确授权和最终确认，该功能初期为实验阶段。Chrome 浏览器集成将于 2026 年 6 月启动。

rss · IT之家 · May 12, 17:45

**背景**: Gemini Intelligence 是下一代安卓系统 Android 17（代号 Cinnamon Bun）的一部分。它基于谷歌的 Gemini AI 模型系列，其中包括用于设备端处理的轻量级模型 Gemini Nano。该系统旨在将 Gemini 从聊天机器人转变为主动的安卓助手，能够理解用户上下文并跨应用和网站执行任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gemini_Intelligence">Gemini Intelligence</a></li>
<li><a href="https://techcrunch.com/2026/05/12/googles-create-my-widget-feature-will-let-you-vibe-code-your-own-widgets/">Google's 'Create My Widget' feature will let you vibe code your own widgets | TechCrunch</a></li>

</ul>
</details>

**标签**: `#Google`, `#Android`, `#AI`, `#Gemini`, `#automation`

---

<a id="item-11"></a>
## [Hugging Face 现山寨 OpenAI 隐私过滤器，下载超 20 万次含木马](https://www.ithome.com/0/949/518.htm) ⭐️ 8.0/10

Hugging Face 上名为 'Open-OSS/privacy-filter' 的恶意仓库冒充 OpenAI 的 Privacy Filter 模型，在被下架前下载量已超过 20 万次。该仓库中隐藏了信息窃取木马（Infostealer），伪装成合法模型。 此事件凸显了 AI/ML 生态系统中严重的供应链风险，恶意行为者可轻易冒充热门模型传播恶意软件。超过 20 万次下载意味着大量开发者及组织可能已遭入侵。 恶意仓库的文件结构与官方 OpenAI Privacy Filter 高度相似，难以察觉。发现此事件的安全公司 HiddenLayer 建议受影响用户彻底重建开发环境，而非尝试手动清理。

rss · IT之家 · May 12, 14:03

**背景**: OpenAI 的 Privacy Filter 是一个用于检测和遮蔽文本中个人身份信息（PII）的小型模型，于 2026 年 4 月发布。Hugging Face 是托管 AI 模型的流行平台，但其开放性使其成为供应链攻击的目标。信息窃取木马旨在从受感染系统中窃取凭证、会话令牌等敏感数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/introducing-openai-privacy-filter/">Introducing OpenAI Privacy Filter | OpenAI</a></li>
<li><a href="https://huggingface.co/openai/privacy-filter">openai/privacy-filter · Hugging Face</a></li>
<li><a href="https://www.breachsense.com/blog/infostealer-malware/">Infostealer Malware: How It Works & How to Detect It</a></li>

</ul>
</details>

**标签**: `#security`, `#supply chain attack`, `#Hugging Face`, `#malware`, `#AI`

---

<a id="item-12"></a>
## [月壤纤维样品进入中国空间站开展舱外验证](https://www.ithome.com/0/949/492.htm) ⭐️ 8.0/10

利用嫦娥五号真实月壤制成的月壤纤维样品，已随天舟货运飞船进入中国空间站，将在舱外暴露平台接受长期空间环境测试。 这标志着月球原位资源利用迈出重要一步，未来月球科研站建设可利用当地材料，大幅降低从地球运输的成本。 该纤维长约 3 米、直径与头发丝相当，采用自主研制的模拟月球环境纺丝装置，仅用 0.5 克真实月壤制备而成。

rss · IT之家 · May 12, 12:08

**背景**: 原位资源利用（ISRU）是可持续太空探索的关键策略，旨在利用月球土壤等当地材料进行建造和制造。传统纺丝设备在月球高真空、微重力环境下无法工作，团队耗时十年研制专用装置。2020 年嫦娥五号任务提供了数十年来首批真实月壤样品，促成了这一突破。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ithome.com/0/949/492.htm">月壤纤维样品进入中国空间站，将接受舱外环境长期验证 - IT之家</a></li>
<li><a href="https://www.chinanews.com.cn/gn/2026/05-12/10619941.shtml">东华大学突破月壤成纤关键技术 首件模拟样品进入空间站验证-中新网</a></li>
<li><a href="https://www.donews.com/news/detail/8/6552740.html">月壤纤维样品随天舟飞船入驻中国空间站开展舱外实验- DoNews快讯</a></li>

</ul>
</details>

**标签**: `#lunar exploration`, `#materials science`, `#in-situ resource utilization`, `#space technology`, `#fiber manufacturing`

---

<a id="item-13"></a>
## [iOS 27 重磅改版：Siri 独立应用上线，对标 ChatGPT](https://news.mydrivers.com/1/1121/1121840.htm) ⭐️ 8.0/10

苹果在 iOS 27 中首次推出独立 Siri 应用，将传统语音助手改造为具备持续对话能力的 AI 智能体，支持图文输入、系统级搜索，并开放第三方 AI 模型（如 ChatGPT、Gemini）作为默认选项。 这是 Siri 史上最大升级，直接对标 ChatGPT 等主流 AI 产品，标志着苹果在 AI 战略上的关键一步，可能重塑 iOS 生态和用户对设备端 AI 的期待。 Siri 应用与灵动岛深度整合，唤醒时显示胶囊动画，结果以卡片呈现；图乐园等应用支持自然语言修改图片。但国行用户目前无法体验该功能。

rss · 快科技 · May 13, 07:23

**背景**: Siri 长期以来因功能有限而受到批评，远不及 ChatGPT 等 AI 聊天机器人。iOS 27 通过为 Siri 提供独立应用、持续对话历史和第三方 AI 模型支持来缩小差距。灵动岛是 iPhone 14 Pro 引入的软硬件结合功能，可在前置摄像头挖孔周围显示通知和交互。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://classiccorvettes.org/article/ios-27-siri-s-big-comeback-what-to-expect">iOS 27: Siri's Big Comeback - What to Expect (2026)</a></li>
<li><a href="https://acoh2023.org/article/ios-27-siri-app-apple-s-new-ai-assistant-unveiled">iOS 27 Siri App: Apple's New AI Assistant Unveiled (2026)</a></li>
<li><a href="https://www.ign.com.cn/tech/40584/video/iphone-14-proling-dong-dao-dynamic-island-zhan-shi-shi-pin">IPhone 14 Pro「灵动岛（ Dynamic Island）」展示视频 | IGN中国</a></li>

</ul>
</details>

**标签**: `#Apple`, `#iOS`, `#Siri`, `#AI`, `#ChatGPT`

---

<a id="item-14"></a>
## [谷歌与苹果合作实现安卓与 iPhone 跨平台互传及 eSIM 转移](https://news.mydrivers.com/1/1121/1121834.htm) ⭐️ 8.0/10

谷歌宣布与苹果合作，通过 Quick Share 和 AirDrop 实现安卓与 iPhone 之间的直接文件互传，并简化跨平台数据迁移（包括 eSIM 转移），该功能将于 2026 年开始推送。 此次合作打破了主要的生态壁垒，首次实现安卓与 iOS 设备之间的无缝互操作，显著提升用户体验并降低换机成本。 Quick Share 将于 2026 年扩展至三星、OPPO、一加、vivo、小米、荣耀等品牌，不兼容设备可通过二维码回退方案分享文件（一个月内推送）。数据迁移支持通讯录、照片、视频、短信、应用、密码、主屏布局及 eSIM 无线传输。

rss · 快科技 · May 13, 06:38

**背景**: Quick Share 是安卓内置的文件分享功能，类似于苹果的 AirDrop。eSIM 是一种数字 SIM 卡，用户无需实体 SIM 卡即可激活蜂窝网络套餐。欧盟《数字市场法案》（DMA）推动了主要平台之间的更大互操作性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.android.com/intl/en_uk/better-together/quick-share-app/">The new Quick Share app for Windows | Android</a></li>
<li><a href="https://support.google.com/android/answer/9286773?hl=en">Use Quick Share on your Android device - Android Help</a></li>

</ul>
</details>

**标签**: `#Google`, `#Apple`, `#interoperability`, `#file sharing`, `#eSIM`

---

<a id="item-15"></a>
## [谷歌报告：黑客利用 AI 发现零日漏洞](https://news.mydrivers.com/1/1121/1121828.htm) ⭐️ 8.0/10

谷歌威胁情报团队发布报告，披露某黑客组织利用 AI 工具成功发现真实零日漏洞并绕过 2FA 认证，但攻击被谷歌及时阻止。 这是首次发现 AI 被用于恶意零日漏洞挖掘的实例，降低了攻击门槛，凸显了加快补丁修复和主动防御的紧迫性。 泄露的用于绕过 2FA 的 Python 脚本包含详细注释和伪造的 CVSS 评分，谷歌确认这些由 AI 生成。报告指出 AI 推理能力的提升增强了漏洞发现能力。

rss · 快科技 · May 13, 00:28

**背景**: 零日漏洞是厂商未知的软件缺陷，对攻击者极具价值。2FA（双因素认证）增加安全层，但攻击者不断寻找绕过方法。AI 工具可自动化并加速漏洞研究，此前需要专家人工完成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cloud.google.com/blog/topics/threat-intelligence/ai-vulnerability-exploitation-initial-access/">Adversaries Leverage AI for Vulnerability Exploitation ...</a></li>
<li><a href="https://thehackernews.com/2026/05/hackers-used-ai-to-develop-first-known.html">Hackers Used AI to Develop First Known Zero-Day 2FA Bypass ...</a></li>
<li><a href="https://www.csoonline.com/article/4169046/google-discovers-weaponized-zero-day-exploits-created-with-ai.html">Google discovers weaponized zero-day exploits created with AI</a></li>

</ul>
</details>

**标签**: `#AI security`, `#cybersecurity`, `#zero-day vulnerability`, `#Google threat intelligence`, `#hacker tools`

---

<a id="item-16"></a>
## [小米下半年将推出自研芯片+OS+AI 大模型商用终端](https://news.mydrivers.com/1/1121/1121731.htm) ⭐️ 8.0/10

小米计划在 2025 年下半年推出一款商用终端产品，首次同时搭载自研玄戒芯片、澎湃 OS 和 MiMo AI 大模型。这是小米首次将三项自研技术整合在同一款量产消费设备中。 这一里程碑标志着小米从第三方组件整合商转型为全栈技术公司，实现了对硬件、软件和 AI 的端到端控制。这可能增强小米在高端市场的竞争力，并深化其“人车家全生态”战略。 玄戒 O1 芯片采用台积电 3nm 工艺，集成约 190 亿个晶体管；澎湃 OS 是跨平台操作系统；MiMo 是小米的多模态 AI 模型。该产品并非概念机，而是面向消费者的完全量产商用设备。

rss · 快科技 · May 12, 16:40

**背景**: 小米过去几年分别研发了自研芯片（玄戒）、操作系统（澎湃 OS）和 AI 大模型（MiMo）。玄戒 O1 芯片于 2025 年正式发布，澎湃 OS 已在多设备上迭代，MiMo 也已部署到各类终端。将三者整合到一款产品中，是小米在垂直整合方面的重要举措，类似于苹果和华为已实现的模式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://tele.ofweek.com/2025-06/ART-8320500-8500-30664287.html">玄戒芯片亮相，小米离苹果和华为有多远？ - OFweek通信网</a></li>
<li><a href="https://www.etime.net.cn/site/articalInfo.php?NewsID=76191">小米玄戒芯片：3nm制程工艺的突破与技术解析|ICNET...</a></li>
<li><a href="https://mimo.xiaomi.com/">Xiaomi MiMo, Explore and Love</a></li>

</ul>
</details>

**标签**: `#Xiaomi`, `#self-developed chip`, `#AI large model`, `#operating system`, `#vertical integration`

---

<a id="item-17"></a>
## [世界首次！我国将人工胚胎送入太空](https://news.mydrivers.com/1/1121/1121718.htm) ⭐️ 8.0/10

2026 年 5 月 12 日，我国天舟十号货运飞船成功发射，搭载人工胚胎开展全球首次太空早期人类发育研究。 该实验可揭示重力对早期胚胎发育的影响，为人类长期太空驻留、深空探索乃至太空繁衍提供关键数据。 人工胚胎模拟人类受精后第 14 至 21 天的发育阶段，将在轨发育 5 天，随后冻存并返回地面分析。

rss · 快科技 · May 12, 16:20

**背景**: 人工胚胎是用干细胞构建的、与真正胚胎相似的结构，但不具备发育成个体的能力，可用于研究早期发育生物学而不涉及伦理问题。实验聚焦于器官前体和体轴形成的关键窗口期，该阶段对环境干扰高度敏感。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ncsti.gov.cn/kjdt/kjrd/202605/t20260512_246384.html">“人工胚胎”太空实验将首次开展</a></li>
<li><a href="https://www.sohu.com/a/1021371866_122417797">世界首次！我国“人工胚胎”进入太空：研究微重力的影响</a></li>
<li><a href="https://3g.china.com/act/news/10000169/20260512/49488805.html">“人工胚胎”，首次进入太空！ 探索微重力对发育影响</a></li>

</ul>
</details>

**标签**: `#space biology`, `#stem cells`, `#embryo development`, `#China space program`

---

<a id="item-18"></a>
## [OpenAI 前 CTO 发布最人性化 AI 交互模型](http://www.geekpark.net/news/364044) ⭐️ 8.0/10

由 OpenAI 前 CTO Mira Murati 创立的 Thinking Machines Lab 发布了其“交互模型”的研究预览，该模型支持实时、多模态、可打断的对话，让 AI 能像人一样看、听和插话。 这标志着从传统的回合制 AI 交互向连续、类人对话的范式转变，可能使 AI 助手在实时协作中更加自然和高效。 该模型采用“时间对齐的微回合”技术，每 200 毫秒处理一次输入和输出，将音频、视频和文本流整合为连续的 token 序列，并采用包含交互模型和背景模型的两层架构。

rss · 极客公园 · May 12, 10:06

**背景**: 当前的 AI 聊天机器人采用回合制模型：用户说话，AI 等待，然后回复。这限制了实时协作。Thinking Machines Lab 的方法将交互能力直接训练到模型中，而不是依赖语音活动检测（VAD）和文本转语音（TTS）等外部组件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2025/07/15/mira-muratis-thinking-machines-lab-is-worth-12b-in-seed-round/">Mira Murati's Thinking Machines Lab is worth $12B in seed</a></li>
<li><a href="https://www.nytimes.com/2025/02/18/technology/openai-mira-murati-startup.html">Mira Murati, OpenAI’s Former Chief Technology Officer, Starts</a></li>
<li><a href="https://www.wired.com/story/thinking-machines-lab-first-product-fine-tune/">Exclusive: Mira Murati’s Stealth AI Lab Launches Its First</a></li>

</ul>
</details>

**标签**: `#AI`, `#Human-AI Interaction`, `#Multimodal AI`, `#Startup`

---