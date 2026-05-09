---
layout: default
title: "Daily News 2026-05-09"
date: 2026-05-09
lang: zh
---

> From 288 items, 19 important content pieces were selected

---

1. [Google 更新 reCAPTCHA，屏蔽去谷歌化安卓用户](#item-1) ⭐️ 8.0/10
2. [AI 正在打破两种漏洞文化](#item-2) ⭐️ 8.0/10
3. [AWS 弗吉尼亚数据中心过热导致服务中断](#item-3) ⭐️ 8.0/10
4. [Meta 移除 Instagram 私信端到端加密](#item-4) ⭐️ 8.0/10
5. [Anthropic 教 AI 模型理解行为背后的“为什么”](#item-5) ⭐️ 8.0/10
6. [Mojo 1.0 Beta 发布，带来所有权模型、编译期计算和 SIMD 支持](#item-6) ⭐️ 8.0/10
7. [Thariq Shihipar 主张用 HTML 替代 Markdown 作为 LLM 输出格式](#item-7) ⭐️ 8.0/10
8. [小红书成立 AI 一级部门 Dots，加速 AI 战略布局](#item-8) ⭐️ 8.0/10
9. [清华系 AI 基础设施公司获数亿元融资，推 GPU 核心架构](#item-9) ⭐️ 8.0/10
10. [DeepSeek 拟募资 500 亿元，创中国 AI 融资纪录](#item-10) ⭐️ 8.0/10
11. [马斯克访问英特尔俄勒冈工厂，评估 18A/14A 工艺用于 SpaceX AI 芯片](#item-11) ⭐️ 8.0/10
12. [新紫光发布“紫弦”三维近存计算架构，带宽达 30TB/s](#item-12) ⭐️ 8.0/10
13. [北美电力可靠性公司发布最高级别警报：数据中心威胁电网稳定](#item-13) ⭐️ 8.0/10
14. [苹果与英特尔达成芯片代工协议，减少对台积电依赖](#item-14) ⭐️ 8.0/10
15. [OpenAI 一口气发布三款超强语音 AI 模型](#item-15) ⭐️ 8.0/10
16. [美国调查英伟达 GPU 25 亿美元走私案，泰国公司 OBON 涉案](#item-16) ⭐️ 8.0/10
17. [三星与 SK 海力士争夺第七代 DRAM 标准主导权](#item-17) ⭐️ 8.0/10
18. [研究揭示 API 中转站可劫持 AI Agent，检测工具 Probe 发布](#item-18) ⭐️ 8.0/10
19. [马斯克 550 亿美元芯片工厂计划：SpaceX 在得州的 Terafab](#item-19) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Google 更新 reCAPTCHA，屏蔽去谷歌化安卓用户](https://reclaimthenet.org/google-broke-recaptcha-for-de-googled-android-users) ⭐️ 8.0/10

Google 最新的 reCAPTCHA 更新引入了远程证明要求，导致使用去谷歌化安卓设备（如 GrapheneOS）的用户无法完成验证码挑战。 此举迫使注重隐私的用户在谷歌服务与设备自主权之间做出选择，并引发了对远程证明可能成为网络访问默认要求的担忧。 新版 reCAPTCHA 通过远程证明验证设备完整性，这需要可信平台模块（TPM）和谷歌签名的密钥，而去谷歌化 ROM 中缺少这些组件。因此，移除了谷歌 Play 服务的自定义安卓发行版无法兼容。

hackernews · anonymousiam · May 8, 18:45 · [社区讨论](https://news.ycombinator.com/item?id=48067119)

**背景**: 去谷歌化安卓指 GrapheneOS 或 LineageOS 等自定义 ROM，它们移除谷歌服务以保护隐私。远程证明是一种可信计算技术，硬件通过内置唯一密钥向远程服务器证明身份。批评者认为该技术可用于设备指纹识别和用户追踪。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Remote_attestation">Remote attestation</a></li>
<li><a href="https://tech.yahoo.com/phones/articles/googling-android-simpler-think-no-193119747.html">De-Googling Android is simpler than you think—no special phone...</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了强烈反对，用户称远程证明是一种 KYC 形式，并誓言完全放弃谷歌服务。部分用户寻求替代验证码提供商，另一些则指出 reCAPTCHA 与 Google Cloud Fraud Defense 之间的技术关联。

**标签**: `#privacy`, `#Android`, `#reCAPTCHA`, `#Google`, `#remote attestation`

---

<a id="item-2"></a>
## [AI 正在打破两种漏洞文化](https://www.jefftk.com/p/ai-is-breaking-two-vulnerability-cultures) ⭐️ 8.0/10

AI 工具正在加速漏洞的发现和利用，削弱了传统的协调披露模式，迫使软件安全管理方式发生转变。 这种转变可能导致更短的禁运期和更激进的利用，增加组织快速修补的压力，并推动采用更透明的安全实践。 文章以 Log4Shell 漏洞为例，攻击者通过分析公开的提交记录，在官方披露日期之前就利用了该漏洞。

hackernews · speckx · May 8, 17:55 · [社区讨论](https://news.ycombinator.com/item?id=48066524)

**背景**: 协调漏洞披露（CVD）是一种将漏洞私下报告给供应商，允许在公开披露前有时间修补的过程。传统模式依赖禁运期来给防御者争取时间。然而，借助 AI 和改进的逆向工程工具，攻击者现在可以更快地发现和武器化漏洞，打破了这一模式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Coordinated_vulnerability_disclosure">Coordinated vulnerability disclosure - Wikipedia</a></li>
<li><a href="https://www.cisa.gov/coordinated-vulnerability-disclosure-process">Coordinated Vulnerability Disclosure Program | CISA</a></li>
<li><a href="https://jfrog.com/blog/log4shell-0-day-vulnerability-all-you-need-to-know/">Log4Shell Zero-Day Vulnerability - CVE-2021-44228</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，这个问题在 AI 出现之前就已存在，例如内核提交差异分析。有人认为，更便宜的漏洞利用生成使协调披露变得更加重要，而非更不重要。其他人则强调了网络战争的大背景以及更快防御响应的必要性。

**标签**: `#AI`, `#vulnerability disclosure`, `#software security`, `#Log4Shell`, `#open source`

---

<a id="item-3"></a>
## [AWS 弗吉尼亚数据中心过热导致服务中断](https://www.reuters.com/business/retail-consumer/amazon-cloud-unit-says-data-center-overheating-north-virginia-disrupts-services-2026-05-08/) ⭐️ 8.0/10

2026 年 5 月 8 日，AWS 位于北弗吉尼亚州的数据中心因过热导致多项服务中断，影响了 FanDuel 和 Coinbase 等客户。 此次故障凸显了 us-east-1 区域的脆弱性——该区域承载了不成比例的云工作负载，并引发了对数据中心冷却设计和冗余策略的质疑。 过热可能由冷却设备故障或外部因素引起，而非简单的过度配置。AWS 健康仪表板报告了 EC2 受损，且此次事件发生在历史上多次宕机的 us-east-1 区域。

hackernews · christhecaribou · May 8, 03:31 · [社区讨论](https://news.ycombinator.com/item?id=48058197)

**背景**: AWS us-east-1 是最早且最繁忙的区域，承载着许多关键服务和客户。数据中心依赖精密冷却系统（如 CRAC 机组、冷热通道封闭）来散发服务器热量；冷却失效会导致快速过热和停机。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html">Regions and Zones - Amazon Elastic Compute Cloud</a></li>
<li><a href="https://www.statuscake.com/blog/when-aws-us-east-1-fails-much-of-the-internet-fails-with-it/">When AWS us-east-1 Fails, Much of the Internet Fails... - StatusCake</a></li>
<li><a href="https://www.theregister.com/2025/10/29/aws_us_east_1_more_problems/">AWS US-EAST-1 region is having another bad day • The Register</a></li>

</ul>
</details>

**社区讨论**: 评论者质疑 AWS 是否过度预订冷却容量，或是否因设备故障导致。一些人批评行业过度依赖 us-east-1，称其为单点故障，并建议将数据中心建在海洋附近以改善冷却。

**标签**: `#AWS`, `#outage`, `#data center`, `#cloud`, `#reliability`

---

<a id="item-4"></a>
## [Meta 移除 Instagram 私信端到端加密](https://www.pcmag.com/news/meta-shuts-down-end-to-end-encryption-for-instagram-dms-messaging) ⭐️ 8.0/10

Meta 已停止为 Instagram 私信提供端到端加密，该功能自 2023 年起为可选加入，Meta 称其采用率低且需应对安全问题。 这一决定逆转了重要的隐私承诺，引发关于企业责任的讨论，因为它将安全监控置于用户隐私之上，可能影响数百万用户。 Meta 表示很少有用户选择加入加密功能，这一改变使公司能更好地应对诈骗、骚扰和法律请求。已启用加密的用户可下载其加密消息记录。

hackernews · tcp_handshaker · May 8, 21:47 · [社区讨论](https://news.ycombinator.com/item?id=48069192)

**背景**: 端到端加密确保只有发送方和接收方能读取消息，服务提供商也无法访问。Meta 于 2023 年为 Instagram 私信引入了可选 E2EE，但现在将其移除，这与默认使用 E2EE 的 WhatsApp 形成对比。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.pcmag.com/news/meta-shuts-down-end-to-end-encryption-for-instagram-dms-messaging">Meta Shuts Down End-to-End Encryption for Instagram Messaging</a></li>
<li><a href="https://www.macrumors.com/2026/05/08/instagram-end-to-end-encryption/">Warning: Instagram DMs Lose End-to-End Encryption Starting ...</a></li>
<li><a href="https://www.cnet.com/news/privacy/instagram-messaging-encryption-ending-explainer/">Instagram's Messaging Encryption is Ending. Here's What You ...</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了强烈批评，指责 Meta 将利润置于隐私之上，并质疑为何不像 WhatsApp 那样默认启用加密。有人建议如果关心隐私就避免使用 Meta 产品，还有人讽刺地指出以安全为由移除加密的讽刺性。

**标签**: `#privacy`, `#encryption`, `#Meta`, `#Instagram`, `#surveillance`

---

<a id="item-5"></a>
## [Anthropic 教 AI 模型理解行为背后的“为什么”](https://www.anthropic.com/research/teaching-claude-why) ⭐️ 8.0/10

Anthropic 发布了一项研究，探索用教学法进行 AI 对齐：不仅教模型期望的行为，还教其背后的推理过程。 这有望实现更稳健、更通用的对齐——理解“为什么”的模型能更好地应对新情况并抵御对抗性攻击。 该方法借鉴了人类教学法：教师解释原因而非仅展示示例。该研究是 Anthropic 更广泛的对齐科学工作的一部分。

hackernews · pretext · May 8, 17:59 · [社区讨论](https://news.ycombinator.com/item?id=48066592)

**背景**: AI 对齐旨在确保 AI 系统符合人类的价值观和意图。传统训练通常使用奖励信号或监督学习来塑造行为，但这可能导致结果脆弱或偏离目标。教授底层推理或许能产生更适应性强、更可信的模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/research">Research \ Anthropic</a></li>
<li><a href="https://www.libertify.com/interactive-library/anthropic-ai-safety-research-alignment-and-reasoning-models/">Anthropic AI Safety Research: Alignment and Reasoning Models —...</a></li>

</ul>
</details>

**社区讨论**: 评论者将对齐比作教学法，指出在有限训练数据下引导出期望行为是一个教学问题。还有人提出哲学担忧：如果一个高能力的对齐模型造成了社会危害，它还能被称为对齐吗？这凸显了对齐定义需要改进。

**标签**: `#AI alignment`, `#machine learning`, `#Anthropic`, `#reasoning`, `#ethics`

---

<a id="item-6"></a>
## [Mojo 1.0 Beta 发布，带来所有权模型、编译期计算和 SIMD 支持](https://mojolang.org/) ⭐️ 8.0/10

Mojo 1.0 Beta 已发布，引入了类似 Rust 的所有权模型、强大的编译期元编程以及一流的 SIMD 支持。该语言在 2026 年秋季之前仍为专有，仅标准库开源。 Mojo 旨在将类似 Python 的语法与 Rust 级别的性能相结合，面向机器学习和系统编程。它的发布可能挑战 Rust 和 Zig 等现有高性能语言，但延迟开源可能会阻碍其采用。 Mojo 的所有权模型不同于 Rust 的引用和生命周期，其编译期计算被认为比 Zig 更强大。该语言使用 LLVM 但方式独特，并非简单封装。Python 兼容性仍然有限，Mojo 无法直接运行现有 Python 代码。

hackernews · sbt567 · May 8, 02:49 · [社区讨论](https://news.ycombinator.com/item?id=48057901)

**背景**: Mojo 是由 Modular Inc. 开发的一种编程语言，设计为 Python 的超集，并增加了高性能计算功能。它利用 MLIR（多层中间表示）进行优化，面向 CPU 和 GPU。该语言自 2022 年开始开发，已获得大量社区关注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language) - Wikipedia</a></li>
<li><a href="https://docs.modular.com/mojo/std/builtin/simd/">simd - Modular</a></li>
<li><a href="https://github.com/modular/max/issues/933">[mojo-compiler] CompTime interpreter should be able to fold...</a></li>

</ul>
</details>

**社区讨论**: 社区成员对 Mojo 的性能和功能表示兴奋，但仍担心 Python 兼容性和专有时间线。一些用户指出，Nvidia 的 CUDA 进展（如 CuTile）可能与 Mojo 竞争。延迟到 2026 年秋季开源是一个争议点。

**标签**: `#Mojo`, `#programming language`, `#ML`, `#performance`, `#open source`

---

<a id="item-7"></a>
## [Thariq Shihipar 主张用 HTML 替代 Markdown 作为 LLM 输出格式](https://simonwillison.net/2026/May/8/unreasonable-effectiveness-of-html/#atom-everything) ⭐️ 8.0/10

Anthropic Claude Code 团队成员 Thariq Shihipar 发表文章，主张 HTML 比 Markdown 更适合作为 LLM 的输出格式，并提供了具体示例和提示模板。他展示了 HTML 如何支持 SVG 图表、交互式小部件和页面内导航等更丰富的功能。 这挑战了普遍存在的默认使用 Markdown 作为 LLM 输出格式的做法，该做法源于早期模型对 token 效率的担忧。采用 HTML 可以显著提高 AI 生成解释的质量和交互性，尤其适用于代码审查或安全漏洞等复杂主题。 Shihipar 提供了一个提示示例，要求 Claude 创建用于 PR 审查的 HTML 工件，重点关注流/背压逻辑，并包含内联差异注释和严重性颜色编码。Simon Willison 使用 GPT-5.5 对 Linux 漏洞进行了测试，生成了一个包含标注和逐步解释的丰富 HTML 页面。

rss · Simon Willison · May 8, 21:00

**背景**: 自 GPT-4 时代以来，由于在 8,192 token 限制下的 token 效率，Markdown 一直是许多 LLM 用户的默认输出格式。HTML 虽然更具表现力，但因消耗更多 token 而被避免使用。然而，随着现代模型拥有更大的上下文窗口，HTML 的 token 成本已不再是主要问题，其嵌入丰富媒体和交互性的能力成为显著优势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**标签**: `#LLM`, `#prompt engineering`, `#HTML`, `#Claude`, `#best practices`

---

<a id="item-8"></a>
## [小红书成立 AI 一级部门 Dots，加速 AI 战略布局](https://36kr.com/p/3799028783439111?f=rss) ⭐️ 8.0/10

2026 年 4 月 30 日，小红书宣布成立 AI 一级部门 Dots，整合模型研发、基础设施、工程和产品团队。该部门由原人文智能实验室 Hi Lab 升级而来，并将公司核心 AI 产品“点点”纳入旗下。 此举标志着小红书从谨慎探索转向积极拥抱 AI 的战略转变。这反映了行业将 AI 融入核心产品的紧迫性，并可能重塑 AI 在社区驱动平台中的应用方式。 Dots 直接向新任总裁柯南汇报，下设模型研发、基础设施、工程、产品四个部门。AI 产品“点点”经历了四个探索阶段，包括从自研模型转向接入 DeepSeek，以及近期从独立应用转变为小红书主站内的内置功能。

rss · 36氪 · May 8, 04:38

**背景**: 小红书是一个以社区驱动的内容分享平台，尤其在生活方式和购物领域。自 2022 年 ChatGPT 发布以来，该公司对 AI 一直持谨慎态度，在创新与保持社区“人情味”之间寻求平衡。新部门的成立是一次重大的组织升级，旨在优先发展 AI。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.firecat-web.com/daily-news/8070">小红书成立AI一级部门Dots，从克制到加速的底层逻辑</a></li>
<li><a href="https://finance.sina.com.cn/wm/2026-04-30/doc-inhwhkum4192914.shtml">小红书成立AI一级部门Dots - 新浪财经</a></li>
<li><a href="https://www.10100.com/article/129868990">小红书成立AI一级部门Dots- 大数跨境 - 10100.com</a></li>

</ul>
</details>

**标签**: `#AI strategy`, `#social media`, `#product development`, `#China tech`, `#industry analysis`

---

<a id="item-9"></a>
## [清华系 AI 基础设施公司获数亿元融资，推 GPU 核心架构](https://36kr.com/p/3799984046333186?f=rss) ⭐️ 8.0/10

北京容芯致远科技有限公司完成数亿元天使轮融资，由北京绿色能源和低碳产业基金与赛富投资基金领投，提出以 GPU 为核心的 AGC 架构，颠覆传统以 CPU 为中心的 AI 计算体系。 该架构有望大幅提升大规模 AI 训练和推理场景下的 GPU 利用率和系统效率，解决 AI 基础设施的关键瓶颈。同时它支持国产 CPU 和 GPU 的开放生态，助力国产化替代。 AGC 架构将 GPU 与 CPU 的比例从约 2:1 提升至 20:1 甚至 32:1，支持单一操作系统统一管理多达 64 个 GPU 并实现全局地址空间共享，实现 GPU 热插拔（GPU RAID），将维护时间从约 2 小时压缩至约 1 分钟。公司还自研了微秒级响应的 AI BMC 系统和 Blue Link 光互连方案。

rss · 36氪 · May 8, 01:45

**背景**: 传统 AI 服务器以 CPU 为中心，CPU 负责协调 GPU 之间的数据流，随着 GPU 数量增加，CPU 成为瓶颈。AGC 架构将 GPU 作为核心计算单元，降低对 CPU 的依赖，实现更高效的数据共享和容错能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zhuanlan.zhihu.com/p/1905299140453336100">中国AI计算迎重大突破！首批AGC架构智算整机问世</a></li>

</ul>
</details>

**标签**: `#AI Infrastructure`, `#GPU Architecture`, `#Funding`, `#System Design`, `#Chinese Tech`

---

<a id="item-10"></a>
## [DeepSeek 拟募资 500 亿元，创中国 AI 融资纪录](https://36kr.com/newsflashes/3800574318976257?f=rss) ⭐️ 8.0/10

DeepSeek 正寻求完成首轮外部融资，目标高达 500 亿元人民币，这将成为中国 AI 公司史上最大的一轮融资。公司还计划加快模型发布节奏，包括在 6 月推出 V4.1 更新版本。 这笔创纪录的融资表明投资者对 DeepSeek 及整个中国 AI 生态的信心，可能重塑与全球竞争对手的格局。它也凸显了市场对低成本、开放权重 AI 模型日益增长的需求。 DeepSeek 创始人兼 CEO 梁文锋计划为这轮融资提供最大一笔资金。公司已告知部分投资者，将提高模型发布频率，使其更接近行业标准。

rss · 36氪 · May 8, 11:44

**背景**: DeepSeek 由梁文锋于 2023 年 7 月创立，是一家以开放权重大语言模型（如 DeepSeek-R1 和 V3）闻名的中国 AI 公司。该公司因以远低于竞争对手（如 OpenAI）的成本训练模型而受到全球关注，并在出口限制下使用性能较弱的芯片。公司由对冲基金 High-Flyer 全资拥有，此前未进行过外部融资。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(Company)">DeepSeek (Company)</a></li>
<li><a href="https://api-docs.deepseek.com/news/news260424">DeepSeek V4 Preview Release | DeepSeek API Docs</a></li>

</ul>
</details>

**标签**: `#AI`, `#funding`, `#China`, `#DeepSeek`

---

<a id="item-11"></a>
## [马斯克访问英特尔俄勒冈工厂，评估 18A/14A 工艺用于 SpaceX AI 芯片](https://www.ithome.com/0/948/002.htm) ⭐️ 8.0/10

埃隆·马斯克访问英特尔俄勒冈工厂，评估 Intel 18A 和 14A 工艺用于 SpaceX AI 芯片生产，确认了潜在合作。英特尔 14A 工艺将用于 SpaceXAI 的下一代 AI 芯片，而 18A 工艺用于 Panther Lake。 此次访问标志着英特尔与马斯克公司之间潜在的重大合作，提振了英特尔的代工业务，并为 SpaceX AI 芯片提供先进的美国本土制造能力。这可能减少对台积电和三星在关键 AI 硬件上的依赖。 英特尔 18A 工艺引入了 RibbonFET 全环绕栅极晶体管和 PowerVia 背面供电技术，对 AI 芯片能效至关重要。14A 工艺更先进，但除该潜在交易外尚未获得外部客户订单。

rss · IT之家 · May 8, 23:26

**背景**: 英特尔 18A 是其制造复兴的关键节点，采用 RibbonFET 和 PowerVia 技术。Terafab 项目是 SpaceX、特斯拉和 xAI 的联合计划，旨在每年生产 1 太瓦的计算能力，需要先进芯片。马斯克此前表示计划在 Terafab 中使用英特尔 14A 工艺。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aol.com/finance/intel-18a-process-finally-ready-123000951.html">The Intel 18A Process Is Finally Ready - AOL</a></li>
<li><a href="https://wccftech.com/intels-bspdn-on-18a-is-a-major-technical-win-that-may-also-be-holding-back-external-adoption/">Intel’s “BSPDN” Power-Delivery Method on 18A Is a Major Technical...</a></li>
<li><a href="https://builtin.com/articles/elon-musk-terafab-project">Elon Musk’s Terafab Project: What to Know About His Chip... | Built In</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#AI chips`, `#Intel`, `#SpaceX`, `#manufacturing`

---

<a id="item-12"></a>
## [新紫光发布“紫弦”三维近存计算架构，带宽达 30TB/s](https://www.ithome.com/0/947/993.htm) ⭐️ 8.0/10

2026 年 5 月 6 日，新紫光集团前沿技术研究院发布了“紫弦”三维化近存计算（PNM）架构，宣称存储带宽可达 30TB/s，同等算力下词元吞吐率较英伟达 B200 系列高出 1.5 至 2 倍。 该架构可能挑战英伟达在 AI 硬件领域的统治地位，通过更高的带宽和更低的延迟，有望实现更高效的大规模 AI 模型推理与训练。 该架构采用 3.5D 异质异构集成方案，以 3D DRAM 为核心，访存延迟最多降低至 1/18，并声称可基于国内领先供应链规模化量产。

rss · IT之家 · May 8, 22:51

**背景**: 近存计算（PNM）将计算单元靠近存储单元，以减少数据搬运瓶颈。HBM4 是最新的高带宽内存标准，但“紫弦”声称在带宽和容量上超越它。3.5D 集成通过先进封装垂直堆叠多个芯片。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.qq.com/rain/a/20260508A055XL00">紫弦三维化近存计算架构发布，存储带宽30TB/s，访存延迟降低18倍</a></li>
<li><a href="https://www.ithome.com/0/947/993.htm">新紫光发布“紫弦”三维化近存计算架构：存储带宽可达 30TB/s - IT之家</a></li>
<li><a href="https://www.cls.cn/detail/2365842">新紫光前沿技术研究院发布“紫弦”三维近存架构</a></li>

</ul>
</details>

**标签**: `#近存计算`, `#3D DRAM`, `#AI芯片`, `#存储带宽`

---

<a id="item-13"></a>
## [北美电力可靠性公司发布最高级别警报：数据中心威胁电网稳定](https://www.ithome.com/0/947/943.htm) ⭐️ 8.0/10

北美电力可靠性公司（NERC）发布了罕见的 3 级必要行动警报，这是其最高级别警告，要求电网运营商应对数据中心（尤其是 AI 工作负载）带来的立即风险，这些负载会导致快速电力波动，可能引发停电。 这一警报表明，由 AI 和加密货币挖矿驱动的数据中心电力需求已成为威胁美国、加拿大和墨西哥电网可靠性的紧迫问题。它将迫使公用事业公司和监管机构加速电网现代化和负载管理策略。 NERC 的警报指出，电网运营商缺乏足够的流程来应对可能在数秒内发生的计算负载波动。相关实体必须在 2025 年 8 月 3 日前提交风险缓解计划。

rss · IT之家 · May 8, 11:44

**背景**: NERC 是监管北美大电力系统可靠性的监管机构。其警报级别从 1 级（咨询）到 3 级（必要行动）。数据中心，尤其是运行 AI 训练的数据中心，表现出高度变化的电力消耗，传统电网基础设施并未为此设计。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nerc.com/newsroom/nerc-issues-level-3-alert-reliability-guideline-focused-on-large-load-challenges">NERC Issues Level 3 Alert, Reliability Guideline Focused on ...</a></li>
<li><a href="https://www.utilitydive.com/news/nerc-issues-rare-level-3-alert-over-data-center-load-losses/819295/">NERC issues Level 3 alert, mandates action to address data ...</a></li>
<li><a href="https://www.carbon-direct.com/insights/nerc-level-3-alert-data-center-loads">Inside NERC’s Level 3 Alert on data center loads</a></li>

</ul>
</details>

**标签**: `#data centers`, `#grid stability`, `#AI infrastructure`, `#energy`, `#regulation`

---

<a id="item-14"></a>
## [苹果与英特尔达成芯片代工协议，减少对台积电依赖](https://news.mydrivers.com/1/1121/1121017.htm) ⭐️ 8.0/10

苹果与英特尔经过逾一年谈判，已达成初步芯片制造协议，英特尔将为苹果部分设备代工自研芯片，包括部分 iPad 和 Mac 搭载的低配 M 系列芯片，未来可能延伸至非 Pro 版 iPhone 的 A 系列芯片。这标志着苹果首次打破对台积电的独家代工依赖。 该协议使苹果芯片供应链多元化，降低因 AI 需求导致台积电产能紧张的风险。同时，这也验证了英特尔在 CEO 陈立武领导下代工业务的转型成果，可能重塑半导体制造格局。 初期合作大概率聚焦入门级芯片，采用英特尔先进的 18A（1.8nm）和 14A（1.4nm）工艺，首批芯片预计 2027–2028 年面世。苹果保留芯片设计，英特尔仅负责代工生产。

rss · 快科技 · May 9, 07:12

**背景**: 自 2016 年以来，苹果一直独家使用台积电代工自研芯片，但英伟达等公司的 AI 芯片需求导致台积电先进制程产能紧张，造成苹果 iPhone 17 系列供货短缺。英特尔新任 CEO 陈立武推动代工业务改革，加速 18A 和 14A 工艺开发以吸引外部客户。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.qq.com/rain/a/20251012A04DDJ00">英特尔称18A为自家独享：友商可以选择14A工艺进行代工</a></li>
<li><a href="https://www.doit.com.cn/p/534575.html">英特尔18A与14A制程大揭秘：引领代工技术新飞跃-DOIT-数据产业媒体与...</a></li>
<li><a href="https://baike.baidu.com/item/14A制程工艺/67294484">14A制程工艺 - 百度百科</a></li>

</ul>
</details>

**标签**: `#Apple`, `#Intel`, `#semiconductor`, `#supply chain`, `#chip manufacturing`

---

<a id="item-15"></a>
## [OpenAI 一口气发布三款超强语音 AI 模型](https://news.mydrivers.com/1/1120/1120999.htm) ⭐️ 8.0/10

OpenAI 对其实时 API 进行了重大升级，一次性推出三款新语音 AI 模型：GPT-Realtime-2、GPT-Realtime-Translate 和 GPT-Realtime-Whisper。这些模型带来了 GPT-5 级别的推理能力、支持 70 多种语言的实时翻译以及流式转录功能。 此次更新大幅降低了开发者构建智能语音应用的门槛，实现了更自然、更灵敏的语音交互。这标志着从基础语音问答向集聆听、思考、翻译和转录于一体的综合性智能语音操作系统的转变。 GPT-Realtime-2 支持可配置的推理努力程度，让开发者平衡延迟和输出质量。GPT-Realtime-Translate 支持超过 70 种语言的语音识别和 13 种语言的语音输出，而 GPT-Realtime-Whisper 按音频时长而非文本 token 计费。

rss · 快科技 · May 8, 22:02

**背景**: OpenAI 的实时 API 是一个基于 WebSocket 的接口，支持与 GPT 模型进行实时双向音频通信。此前开发者已能构建语音到语音的体验，但新模型增加了高级推理、翻译和流式转录能力。Whisper 是 OpenAI 的通用语音识别模型，现已针对低延迟流式转录进行了优化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/introducing-the-realtime-api/">Introducing the Realtime API | OpenAI</a></li>
<li><a href="https://www.datacamp.com/blog/gpt-realtime-2">GPT-Realtime-2: A Voice Model with GPT-5-Class Reasoning</a></li>
<li><a href="https://developers.openai.com/api/docs/models/gpt-realtime-whisper">gpt-realtime-whisper Model | OpenAI API</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#voice AI`, `#real-time API`, `#GPT-5`, `#speech recognition`

---

<a id="item-16"></a>
## [美国调查英伟达 GPU 25 亿美元走私案，泰国公司 OBON 涉案](https://news.mydrivers.com/1/1120/1120976.htm) ⭐️ 8.0/10

美国检方确认泰国 OBON 公司为一起 25 亿美元英伟达 AI 服务器走私案的中介，超微电脑联合创始人廖益贤因涉嫌参与被起诉。 此案是 2022 年美国收紧出口管制以来最大规模的 AI 芯片走私打击行动，凸显了限制中国获取先进半导体的高风险，以及超微电脑等主要硬件公司面临的合规挑战。 OBON 在 2024 年第二季度是超微电脑的第 11 大客户，单季度贡献近 1 亿美元营收。超微电脑自 2024 年 10 月起对 OBON 进行了多次合规审计并两次暂停出货，但涉嫌走私活动仍在继续。

rss · 快科技 · May 8, 19:14

**背景**: 自 2022 年 10 月起，美国实施出口管制，限制向中国出售英伟达先进 GPU（如 A100、H100 及后续型号），以减缓中国 AI 发展。走私者利用泰国等第三国中介重新路由受限芯片。OBON 公司是一家鲜为人知的泰国企业，还创建了泰国主权云项目 Siam AI。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.msn.com/en-us/money/other/thai-firm-obon-corp-lands-in-us-probe-over-nvidia-chip-flows-to-china/ar-AA22I6QA">Thai firm OBON Corp lands in US probe over Nvidia chip flows ...</a></li>
<li><a href="https://fortune.com/2026/03/19/supermicro-arrested-founder-smuggling-gpu-china/">Supermicro’s cofounder was just arrested for allegedly smuggling...</a></li>
<li><a href="https://en.wikipedia.org/wiki/United_States_export_controls_on_AI_chips_and_semiconductors">United States export controls on AI chips and semiconductors</a></li>

</ul>
</details>

**标签**: `#Nvidia`, `#export controls`, `#AI chips`, `#smuggling`, `#Supermicro`

---

<a id="item-17"></a>
## [三星与 SK 海力士争夺第七代 DRAM 标准主导权](https://news.mydrivers.com/1/1120/1120935.htm) ⭐️ 8.0/10

三星与 SK 海力士正在争夺第七代 DRAM（1d）制程标准，三星推广 GAAFET 架构，SK 海力士则采用 4F²垂直堆叠方案。双方均计划在 2-3 年内实现量产。 这场竞争将定义下一代 DRAM 技术，影响 AI、高性能计算和移动设备的性能、密度和能效。胜出者可能在未来多年主导内存市场。 三星的 GAAFET 方案借鉴 NAND 闪存设计，将控制电路置于存储阵列下方；SK 海力士的 4F²架构相比传统 6F²设计可减少约 30%的单元面积。三星将在 2026 年 VLSI 研讨会上展示 16 层垂直堆叠 DRAM 方案。

rss · 快科技 · May 8, 17:12

**背景**: DRAM（动态随机存取存储器）是一种用于计算机和设备的易失性存储器。“1d”指第七代 DRAM 制程节点。GAAFET（全环绕栅极晶体管）通过栅极包裹沟道实现更好的控制，4F²是一种单元布局，其中“F”为最小特征尺寸，可实现更密集的存储阵列。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://wccftech.com/samsung-borrows-nand-trick-to-crack-next-gen-dram-while-sk-hynix-bets-on-vertical-stacking-to-win-the-ai-memory-war/">Samsung Borrows NAND Trick To Crack Next-Gen DRAM, While SK ...</a></li>
<li><a href="https://en.eeworld.com.cn/news/manufacture/eic722866.html">Samsung and SK Hynix compete for dominance in 3D DRAM, vying ...</a></li>

</ul>
</details>

**标签**: `#DRAM`, `#semiconductor`, `#Samsung`, `#SK Hynix`, `#memory technology`

---

<a id="item-18"></a>
## [研究揭示 API 中转站可劫持 AI Agent，检测工具 Probe 发布](https://www.v2ex.com/t/1211298#reply1) ⭐️ 8.0/10

一篇题为《Your Agent Is Mine》的研究论文（arXiv 2604.08407）证明，恶意的 API 中转站可以通过提示注入、目标替换和数据外泄来劫持 AI Agent。作者还发布了一款名为 Probe 的检测工具，包含 60 个检测项，用于检查中转站的安全性。 随着越来越多的开发者使用 API 中转站运行 AI Agent 任务，这一攻击面成为关键安全问题。Probe 工具提供了一种实用的检测手段，有助于保护 Agent 工作流和用户数据。 Probe 在本地运行，不泄露 API 密钥，覆盖响应注入、中间人篡改、凭证泄露和模型一致性检查。它支持 LangChain、AutoGen 等 Agent 框架。

rss · V2EX · May 8, 14:28

**背景**: AI Agent 通常通过 API 中转站访问大语言模型，但被攻破的中转站可以篡改响应来劫持 Agent 行为。提示注入攻击利用 Agent 对中转站输出的信任，导致未授权操作或数据窃取。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.pentestpad.com/blog/function-poisoning-hijacking-ai-agent-tool-execution">Evil AI: Hijacking AI Agent Tool Execution | PentestPad</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://github.com/BerriAI/litellm">GitHub - BerriAI/litellm: Python SDK, Proxy Server (AI Gateway) to call...</a></li>

</ul>
</details>

**标签**: `#AI security`, `#API proxy`, `#prompt injection`, `#agent hijacking`, `#detection tool`

---

<a id="item-19"></a>
## [马斯克 550 亿美元芯片工厂计划：SpaceX 在得州的 Terafab](http://www.geekpark.net/news/363854) ⭐️ 8.0/10

SpaceX 提议投资 550 亿美元在得克萨斯州 Grimes County 建设名为 Terafab 的芯片制造设施，如果全部建成，总资本支出可能达到 1190 亿美元。该项目是 SpaceX 和特斯拉的联合计划，旨在为马斯克旗下公司确保半导体供应。 这代表着有史以来最大的私人芯片制造投资之一，标志着马斯克垂直整合从芯片生产到部署的 AI 基础设施的雄心。如果成功，可能减少对台积电和英伟达的依赖，重塑 AI 和汽车行业的半导体供应链。 Terafab 第一阶段预计耗资 550 亿美元，最早要到 2028 年中期才能开始产出芯片。该设施将为特斯拉 Autopilot、xAI 的 Grok 训练以及其他马斯克旗下企业生产 AI 芯片，但由于先进半导体制造的复杂性，面临巨大的执行风险。

rss · 极客公园 · May 8, 07:46

**背景**: 1980 年代，日本主导全球芯片市场，促使美国签署《半导体协议》以保护国内产业。近期，2022 年的《芯片法案》已推动近 4500 亿美元的私人半导体投资进入美国。马斯克的 Terafab 计划延续了这一趋势，旨在为其公司庞大的 GPU 需求确保芯片供应。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/05/06/elon-musks-spacex-chip-fab-in-texas-to-cost-up-to-119-billion.html">Elon Musk's Terafab chip factory in Texas could cost up to ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Terafab">Terafab - Wikipedia</a></li>
<li><a href="https://www.usatoday.com/story/money/business/2026/05/06/spacex-tesla-files-55-billion-plans-to-build-terafab-chip-plant/89958999007/">Musk, SpaceX to invest $55 billion for Terafab chip facility ...</a></li>

</ul>
</details>

**标签**: `#semiconductors`, `#SpaceX`, `#Elon Musk`, `#chip manufacturing`, `#investment`

---