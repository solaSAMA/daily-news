---
layout: default
title: "Daily News 2026-05-12"
date: 2026-05-12
lang: zh
---

> From 281 items, 18 important content pieces were selected

---

1. [TanStack npm 包遭蠕虫攻击，含毁灭性死亡开关](#item-1) ⭐️ 9.0/10
2. [UCLA 发现首款模拟中风康复效果的药物](#item-2) ⭐️ 9.0/10
3. [谷歌称黑客利用 AI 发现并利用重大软件漏洞](#item-3) ⭐️ 9.0/10
4. [Nvidia 发布官方 Rust 到 CUDA 编译器](#item-4) ⭐️ 9.0/10
5. [菲尔兹奖得主实测 ChatGPT 5.5 Pro：17 分钟产出博士级数学成果](#item-5) ⭐️ 9.0/10
6. [GitLab 裁员并替换 CREDIT 价值观为新信条](#item-6) ⭐️ 8.0/10
7. [Interfaze 新模型架构宣称精度提升百倍](#item-7) ⭐️ 8.0/10
8. [Thinking Machines 发布实时多模态 Transformer 交互模型](#item-8) ⭐️ 8.0/10
9. [James Shore：AI 编程代理必须按比例降低维护成本](#item-9) ⭐️ 8.0/10
10. [僵尸互联网：AI 生成内容带来的精神负担](#item-10) ⭐️ 8.0/10
11. [Shopify 的 River AI 代理通过公开 Slack 频道促进学习](#item-11) ⭐️ 8.0/10
12. [OpenAI 收购 Tomoro 并成立部署公司，加速企业 AI 落地](#item-12) ⭐️ 8.0/10
13. [通用汽车因未经同意出售驾驶数据被加州罚款 1275 万美元](#item-13) ⭐️ 8.0/10
14. [中芯国际 406 亿元收购中芯北方获上交所通过](#item-14) ⭐️ 8.0/10
15. [Linux 进入 AI 补丁时代：代码量激增成为新常态](#item-15) ⭐️ 8.0/10
16. [假冒 Codex 网站登上谷歌搜索首位，传播恶意软件](#item-16) ⭐️ 8.0/10
17. [Bun 确认从 Zig 迁移到 Rust](#item-17) ⭐️ 8.0/10
18. [Figure AI 展示双机器人协作铺床](#item-18) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [TanStack npm 包遭蠕虫攻击，含毁灭性死亡开关](https://github.com/TanStack/router/issues/7383) ⭐️ 9.0/10

多个 TanStack npm 包（包括 @tanstack/router）在蠕虫攻击中被攻陷，该攻击窃取凭证并包含一个毁灭性死亡开关，若被盗令牌被撤销，则会删除用户主目录。 此次攻击凸显了 npm 供应链中的关键漏洞，广泛使用的库可能被武器化以窃取敏感凭证并造成不可逆的损害。它强调了加强 CI/CD 安全和可信发布实践的必要性。 恶意软件扫描 AWS/GCP 密钥、Kubernetes 令牌、Vault 令牌、GitHub 令牌、SSH 密钥和 ~/.npmrc 文件。它还安装了一个 systemd 服务或 LaunchAgent，每 60 秒轮询 GitHub API，如果令牌被撤销则执行 rm -rf ~/。

hackernews · varunsharma07 · May 11, 21:08 · [社区讨论](https://news.ycombinator.com/item?id=48100706)

**背景**: npm 包是供应链攻击的常见载体，攻击者通过攻陷合法包来分发恶意软件。死亡开关技术确保即使在检测到后，撤销被盗令牌也会触发破坏性载荷，使修复变得危险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://socket.dev/blog/tanstack-npm-packages-compromised-mini-shai-hulud-supply-chain-attack">Tanstack npm Packages Compromised in Ongoing Mini Shai-Hulud...</a></li>
<li><a href="https://cybersecuritynews.com/dead-mans-switch-npm-supply-chain-attack/">Dead Man's Switch - Widespread npm Supply Chain Attack</a></li>

</ul>
</details>

**社区讨论**: 社区成员警告了死亡开关，并指出 @mistralai/mistralai 包也被攻陷。一些人认为，如果 CI 管道被攻陷，仅靠可信发布不足以防止此类攻击。

**标签**: `#security`, `#npm`, `#supply chain`, `#open source`

---

<a id="item-2"></a>
## [UCLA 发现首款模拟中风康复效果的药物](https://stemcell.ucla.edu/news/ucla-discovers-first-stroke-rehabilitation-drug-repair-brain-damage) ⭐️ 9.0/10

UCLA 研究人员发现了 DDL-920，这是首款能在小鼠身上完全再现物理中风康复效果的药物，针对断开但存活的神经网络以恢复大脑功能。 这一突破可能通过提供强化物理治疗的药物替代方案来改变中风康复，许多患者无法坚持物理治疗。它解决了一个重大的未满足需求，因为目前尚无用于中风康复的药物。 该药物针对康复诱导可塑性中涉及的特定大脑回路，在人体试验前需要进一步研究其安全性和有效性。该化合物被确定为 DDL-920，相关 PubMed 出版物中有所引用。

hackernews · bookofjoe · May 11, 17:53 · [社区讨论](https://news.ycombinator.com/item?id=48098261)

**背景**: 中风是成人残疾的主要原因，因为大多数患者无法完全康复。物理康复有帮助，但其强度往往受限。该药物旨在模拟康复触发的大脑自然修复机制，可能提供更易获得的治疗。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://stemcell.ucla.edu/news/ucla-discovers-first-stroke-rehabilitation-drug-repair-brain-damage">UCLA discovers first stroke rehabilitation drug to repair brain damage</a></li>
<li><a href="https://newsroom.ucla.edu/releases/ucla-discovers-first-stroke-rehabilitation-drug-to-reestablish-brain-connections-in-mice">UCLA discovers first stroke rehabilitation drug to reestablish brain connections in mice | UCLA</a></li>

</ul>
</details>

**社区讨论**: 评论者澄清该药物针对的是“挫伤”但存活的神经元，而非死亡组织，并指出目前尚无干预措施能恢复梗死核心细胞死亡区域的功能。一些人推测其可能应用于其他神经退行性疾病，另一些人则引用了相关科幻作品并提供了底层 PubMed 研究的链接。

**标签**: `#stroke`, `#neuroscience`, `#drug discovery`, `#rehabilitation`, `#UCLA`

---

<a id="item-3"></a>
## [谷歌称黑客利用 AI 发现并利用重大软件漏洞](https://www.nytimes.com/2026/05/11/us/politics/google-hackers-attack-ai.html) ⭐️ 9.0/10

谷歌威胁分析小组报告称，犯罪黑客使用 AI 模型发现并武器化了一个零日漏洞，这是首次已知的真实世界攻击者利用 AI 进行漏洞发现的案例。 这标志着网络安全领域的范式转变，因为 AI 降低了发现零日漏洞的门槛，可能增加攻击的频率和严重性。同时也引发了对强大 AI 模型监管的紧迫问题。 攻击者使用了 AI 模型（可能是 Anthropic 的 Mythos）来发现漏洞，谷歌 TAG 对此归因有高度信心。该漏洞在广泛利用前已被修补，但此事件展示了恶意行为者的新能力。

hackernews · donohoe · May 11, 13:20 · [社区讨论](https://news.ycombinator.com/item?id=48094641)

**背景**: 零日漏洞是软件厂商未知的安全缺陷，在发现之前没有可用的补丁。传统上，发现此类漏洞需要深厚的专业知识和手动努力；AI 模型现在可以自动化并加速这一过程，使其对技能较低的攻击者也可用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zero-day_vulnerability">Zero-day vulnerability</a></li>
<li><a href="https://blog.vidocsecurity.com/blog/hype-ai-vulnerability-discovery-national-level">Reality Check on the Mythos Hype: AI Vulnerability Discovery Is</a></li>
<li><a href="https://excited-pixels.com/2026/02/22/ai-assisted-vulnerability-hunting-is-here/">AI-Assisted Vulnerability Hunting is Here – Excited Pixels</a></li>

</ul>
</details>

**社区讨论**: 评论者就 AI 参与的证据展开辩论，有人质疑谷歌如何能有如此高的信心。其他人指出，AI 辅助黑客攻击可能降低零日漏洞储备的价值，并且安全问题可能被用来限制开放权重 AI 模型。

**标签**: `#AI`, `#cybersecurity`, `#zero-day`, `#vulnerability`, `#Google`

---

<a id="item-4"></a>
## [Nvidia 发布官方 Rust 到 CUDA 编译器](https://nvlabs.github.io/cuda-oxide/index.html) ⭐️ 9.0/10

Nvidia 发布了 CUDA-oxide，这是一个官方编译器，能将 Rust 代码直接翻译为 PTX（CUDA GPU 内核的虚拟指令集）。开发者现在可以用 Rust 编写 GPU 内核，而无需依赖 nvcc 等外部工具。 这一进展将 Rust 的内存安全性和现代语言特性引入 GPU 编程，有望减少 CUDA 内核中的错误。同时，它简化了基于 Rust 的 GPU 项目的构建流程，此前这些项目需要桥接到 C++ CUDA 代码。 CUDA-oxide 直接将 Rust 代码编译为 PTX，绕过了 nvcc，并旨在成为现有 Rust CUDA crate 的近乎即插即用的替代品。该项目是开源的，托管在 Nvidia Labs 的 GitHub 上。

hackernews · adamnemecek · May 11, 15:55 · [社区讨论](https://news.ycombinator.com/item?id=48096692)

**背景**: CUDA 是 Nvidia 的并行计算平台，使用 C++ 扩展进行 GPU 编程。PTX 是一种低级虚拟指令集，可在不同 GPU 架构间提供前向兼容性。Rust 是一种专注于安全性和并发性的系统编程语言，其所有权模型有助于防止常见的 GPU 编程错误，如竞态条件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Parallel_Thread_Execution">Parallel Thread Execution - Wikipedia</a></li>
<li><a href="https://developer.nvidia.com/blog/understanding-ptx-the-assembly-language-of-cuda-gpu-computing/">Understanding PTX, the Assembly Language of CUDA GPU Computing</a></li>
<li><a href="https://docs.nvidia.com/cuda/cuda-programming-guide/02-basics/nvcc.html">2.5. NVCC: The NVIDIA CUDA Compiler — CUDA Programming Guide</a></li>

</ul>
</details>

**社区讨论**: 社区参与度很高，用户称赞相比依赖 nvcc 的现有 Rust CUDA crate，该工具可能带来更快的构建时间。一些评论者质疑直接针对 PTX 而非使用 Nvidia 的 MLIR 或 Tile IR 的选择，另一些人则讨论了将 Rust 内存模型映射到 CUDA 语义的挑战。

**标签**: `#CUDA`, `#Rust`, `#GPU Programming`, `#Compilers`, `#Nvidia`

---

<a id="item-5"></a>
## [菲尔兹奖得主实测 ChatGPT 5.5 Pro：17 分钟产出博士级数学成果](https://www.ithome.com/0/949/032.htm) ⭐️ 9.0/10

菲尔兹奖得主 Timothy Gowers 测试了 ChatGPT 5.5 Pro，将其用于加法数论中的公开问题。AI 在 17 分钟内独立产出了一个他认为完全够格写进博士论文的数学成果，全程未接受任何数学指导。 这一演示表明 AI 正迅速接近独立开展原创数学研究的能力，对博士生和早期职业数学家的就业前景构成紧迫威胁。它迫使学术界重新思考 AI 时代人类数学工作的价值。 Gowers 使用了 Mel Nathanson 论文中的问题，这些问题原本是为新博士生准备的训练素材。AI 不仅解决了问题，还将结果格式化为 LaTeX 预印本，仅需“展开这个想法”和“写成 LaTeX 格式”等提示。

rss · IT之家 · May 11, 15:54

**背景**: 加法数论研究整数的加法结构，例如和集及其性质。Timothy Gowers 是菲尔兹奖得主、剑桥大学教授。ChatGPT 5.5 Pro 是一款具有增强推理能力的高级 AI 模型。该测试凸显了 AI 处理复杂数学推理任务的能力日益增强，而这些任务此前被认为需要人类创造力。

**标签**: `#AI`, `#数学研究`, `#ChatGPT`, `#学术影响`, `#菲尔兹奖`

---

<a id="item-6"></a>
## [GitLab 裁员并替换 CREDIT 价值观为新信条](https://about.gitlab.com/blog/gitlab-act-2/) ⭐️ 8.0/10

GitLab 宣布裁员，并将其长期使用的 CREDIT 价值观（协作、结果、效率、多样性、迭代、透明度）替换为三个新价值观：速度与质量、主人翁心态、客户成果，理由是为了适应“智能体时代”的转变。 此举标志着一家知名科技公司重大战略转向，优先考虑速度和主人翁精神而非协作和多样性，可能影响其他公司对待企业文化和 AI 驱动变革的方式。 新价值观完全去掉了多样性、包容性和归属感，强调个人主人翁精神和客户成果。GitLab 将此描述为“智能体时代”的必要之举，在该时代中 AI 智能体和自动化将重塑工作方式。

hackernews · AnonGitLabEmpl · May 11, 20:51 · [社区讨论](https://news.ycombinator.com/item?id=48100500)

**背景**: GitLab 的 CREDIT 价值观是其文化的核心部分，尤其是在一家完全远程的公司中。“智能体时代”指的是 AI 智能体自主执行任务的趋势，减少了人类协作的需求。GitLab 的裁员和价值观变更反映了行业向 AI 驱动效率的广泛推动。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://handbook.gitlab.com/handbook/values/">GitLab Values | The GitLab Handbook</a></li>
<li><a href="https://slab.com/blog/short-toes-how-gitlabs-values-shape-company-documentation/">Short Toes: How GitLab's Values Shape... - Knock Down Silos by Slab</a></li>

</ul>
</details>

**社区讨论**: 社区评论大多持批评态度，许多人认为新价值观是“更努力而非更聪明”的推动，并背离了 DEI。一些人质疑在声称“最大机遇”的同时削减资源的逻辑，另一些人则对 GitLab 的 AI 能力改善用户体验表示怀疑。

**标签**: `#GitLab`, `#layoffs`, `#corporate values`, `#AI`, `#remote work`

---

<a id="item-7"></a>
## [Interfaze 新模型架构宣称精度提升百倍](https://interfaze.ai/blog/interfaze-a-new-model-architecture-built-for-high-accuracy-at-scale) ⭐️ 8.0/10

Interfaze 推出了一种任务特定的深度神经网络架构，声称在 OCR 和 GUI 检测等任务上可实现高达 100 倍的精度提升。 这可能显著提升文档处理和用户界面自动化中 AI 系统的可靠性，为开发者带来更可预测的工作流程。 该架构能生成边界框和置信度等有用元数据，该公司是 Y Combinator 孵化的初创企业，并于 2026 年 5 月在 YC Launch Live 上进行了展示。

hackernews · yoeven · May 11, 16:22 · [社区讨论](https://news.ycombinator.com/item?id=48097078)

**背景**: 传统的深度神经网络在处理扭曲或嘈杂图像等专门任务时，往往难以达到高精度。任务特定架构专为单一任务优化，可能超越通用模型的性能。

**社区讨论**: 社区成员在扭曲的打字页面上测试了 OCR 并报告了积极结果。其他人则询问能否像 Unix 管道一样串联模型，以及该架构是否可用于编码代理中的代码提取。

**标签**: `#deep learning`, `#model architecture`, `#OCR`, `#AI accuracy`, `#startup`

---

<a id="item-8"></a>
## [Thinking Machines 发布实时多模态 Transformer 交互模型](https://thinkingmachines.ai/blog/interaction-models/) ⭐️ 8.0/10

Thinking Machines 推出了一种基于 Transformer 的交互模型，通过每 200 毫秒的时间对齐微轮次，近乎实时地处理和生成文本、图像和音频。 该架构实现了流畅、类人的多模态交互，有望改变虚拟助手、客户服务和实时协作工具等应用。 该模型以 200 毫秒为块交错处理输入和生成输出，使其能够同时监听和响应，无需等待完整语句。

hackernews · smhx · May 11, 20:53 · [社区讨论](https://news.ycombinator.com/item?id=48100524)

**背景**: 传统的多模态 AI 模型在处理完整输入后才生成响应，导致延迟。时间对齐微轮次方法通过持续交错小块的输入和输出打破了这一模式，实现了实时交互。

**社区讨论**: 评论者对演示印象深刻，尤其是模型在停顿期间自然等待的能力。一些人质疑其经济模式和可扩展性，另一些人则对训练数据和技能保持提出疑问。

**标签**: `#AI`, `#multimodal`, `#transformer`, `#real-time`, `#interaction model`

---

<a id="item-9"></a>
## [James Shore：AI 编程代理必须按比例降低维护成本](https://simonwillison.net/2026/May/11/james-shore/#atom-everything) ⭐️ 8.0/10

James Shore 发表博文指出，AI 编程代理必须按生产力提升的倒数比例降低维护成本，否则将产生不可持续的技术债务。他用简单数学模型说明，若代码产出翻倍而维护成本未减半，总维护负担将变为四倍。 这一观点挑战了“AI 编程代理纯粹提升生产力”的常见叙事，揭示了可能抵消长期收益的隐藏成本。对于采用 AI 辅助开发的工程领导者和团队至关重要，忽视维护成本可能导致严重的技术债务。 Shore 的模型：若生产力倍数为 P，则维护成本倍数必须为 1/P 才能保持总维护成本不变。他警告当前 AI 编程代理生成的代码往往更难维护，加剧了问题。

rss · Simon Willison · May 11, 19:48

**背景**: 技术债务是软件工程中的一个比喻，指因现在选择简单方案而非更优但更耗时的方案而导致的未来返工成本。AI 编程代理可以加速代码生成，但如果生成的代码结构差或缺少文档，就会增加未来的维护工作量。Shore 的论点将经典债务类比应用于 AI 场景，强调生产力提升必须伴随维护开销的按比例降低。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.jamesshore.com/v2/blog/2026/you-need-ai-that-reduces-your-maintenance-costs">James Shore: You Need AI That Reduces Maintenance Costs</a></li>

</ul>
</details>

**标签**: `#AI-assisted development`, `#software maintenance`, `#technical debt`, `#productivity`

---

<a id="item-10"></a>
## [僵尸互联网：AI 生成内容带来的精神负担](https://simonwillison.net/2026/May/11/zombie-internet/#atom-everything) ⭐️ 8.0/10

Jason Koebler 发表了一篇愤怒而深刻的文章《你的 AI 使用正在摧毁我的大脑》，由 Simon Willison 推荐，文中提出了“僵尸互联网”的概念，描述了人类与 AI 交互深度纠缠的现状。 这篇文章清晰地表达了过滤 AI 生成内容带来的精神疲惫，这是一个日益严重的问题，影响着每个人的互联网体验，并引发了对内容质量和真实性的紧迫追问。 Koebler 将“僵尸互联网”与“死互联网”理论区分开来：前者涉及人与机器人对话、使用 AI 的人与未使用 AI 的人交流，以及 AI 代理与人的互动，造成人机沟通的普遍模糊化。

rss · Simon Willison · May 11, 19:21

**背景**: “死互联网”理论是一种阴谋论，声称自 2016 年左右以来，大多数在线内容和互动是由机器人和算法生成的，而非人类。“僵尸互联网”概念针对 AI 时代进行了更新，描述了一个更复杂的现实：AI 生成的内容与人类活动交织在一起，使得区分真实与合成内容变得精神疲惫。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.fastcompany.com/91489308/zombie-internet-devastating-consequences-advertising-social-media-human-web-dead-internet-moltbook-ai-tbpn">The ‘zombie internet’ has arrived—and it has consequences</a></li>
<li><a href="https://en.wikipedia.org/wiki/Dead_Internet_theory">Dead Internet theory</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#content quality`, `#internet culture`, `#AI-generated content`, `#Zombie Internet`

---

<a id="item-11"></a>
## [Shopify 的 River AI 代理通过公开 Slack 频道促进学习](https://simonwillison.net/2026/May/11/learning-on-the-shop-floor/#atom-everything) ⭐️ 8.0/10

Shopify 首席执行官 Tobias Lütke 透露，其内部编码代理 River 完全在公开的 Slack 频道中运行，拒绝私信，以确保所有交互在公司范围内可见且可搜索。 这种方法将 AI 辅助编码转变为透明、协作的学习环境，实现“渗透式学习”，员工通过观察他人与 AI 的互动来获得技能。 River 拒绝私信，并引导用户创建公开频道（例如 #tobi_river），超过 100 人可关注、回应和贡献。Lütke 将此比作德国的“Lehrwerkstatt”（教学工坊），整个车间都成为教室。

rss · Simon Willison · May 11, 15:46

**背景**: River 是 Shopify 的内部 AI 编码代理，帮助开发者进行代码生成、调试和审查。通过公开其交互，该工具促进了透明度和持续学习，类似于 Midjourney 使用公开的 Discord 频道分享提示词并促进社区学习。

**社区讨论**: 社区讨论强调了 AI 工具透明度的价值，许多人称赞“Lehrwerkstatt”概念可作为其他组织的典范。一些人指出，这种方法需要强大的心理安全感文化，以避免因公开错误而感到尴尬。

**标签**: `#AI-assisted coding`, `#software engineering`, `#learning culture`, `#transparency`, `#Shopify`

---

<a id="item-12"></a>
## [OpenAI 收购 Tomoro 并成立部署公司，加速企业 AI 落地](https://36kr.com/newsflashes/3805023424339456?f=rss) ⭐️ 8.0/10

OpenAI 已同意收购咨询与工程公司 Tomoro，并成立名为“OpenAI 部署公司”的新实体，获得 TPG、贝恩资本和软银等机构超 40 亿美元的初始投资。 此举标志着 AI 公司从提供模型向提供端到端企业解决方案的战略转型，有望大幅降低企业使用 AI 的门槛，加速人工智能在各行各业的渗透。 新实体将由 Tomoro 约 150 名资深 AI 部署专家组成，无论客户与 OpenAI、部署公司还是两者合作，都将获得统一服务体验。同日，Anthropic 也宣布与黑石集团和高盛合作，成立 15 亿美元机构部署 Claude AI 模型。

rss · 36氪 · May 11, 23:42

**背景**: Tomoro 成立于 2023 年，与 OpenAI 结盟，专注于为客户设计、构建和扩展 AI 解决方案。OpenAI 部署公司是 OpenAI 与 19 家全球领先投资机构、咨询公司和系统集成商的合作实体，旨在利用 AI 在真实环境中解决高影响力问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://tomoro.ai/">Tomoro.ai - reinventing better | Tomoro.ai</a></li>
<li><a href="https://www.bloomberg.com/news/articles/2026-05-11/openai-to-buy-consulting-firm-for-private-equity-joint-venture">OpenAI Acquires Tomoro to Boost Private Equity-Backed AI Venture - Bloomberg</a></li>
<li><a href="https://openai.com/index/openai-launches-the-deployment-company/">OpenAI launches the OpenAI Deployment Company to... | OpenAI</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#enterprise AI`, `#acquisition`, `#AI deployment`, `#investment`

---

<a id="item-13"></a>
## [通用汽车因未经同意出售驾驶数据被加州罚款 1275 万美元](https://www.ithome.com/0/949/018.htm) ⭐️ 8.0/10

通用汽车同意支付 1275 万美元，以了结加州指控其未经同意将驾驶员位置和行为数据出售给数据经纪商的案件。和解协议还禁止通用汽车在未来五年内向消费者报告机构出售驾驶数据。 此案为追究汽车制造商在联网车辆数据隐私方面的责任树立了先例，凸显了监管机构对车企如何收集和利用敏感驾驶员信息的日益严格审查。 通用汽车通过安吉星系统收集数据，并将其出售给 LexisNexis Risk Solutions 和 Verisk Analytics，在全美范围内获利约 2000 万美元。和解协议要求通用汽车删除这些数据，并确保这些经纪商也同步删除。

rss · IT之家 · May 11, 13:53

**背景**: 现代汽车通常通过远程信息处理系统收集详细的位置和驾驶行为数据。汽车制造商因将这些数据分享给保险公司而面临批评，导致部分司机保费上涨。加州隐私保护局在接到报告称驾驶数据被用于提高保险费率后，对通用汽车展开了调查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LexisNexis_Risk_Solutions">LexisNexis Risk Solutions</a></li>
<li><a href="https://en.wikipedia.org/wiki/Verisk_Analytics">Verisk Analytics</a></li>

</ul>
</details>

**标签**: `#privacy`, `#automotive`, `#data regulation`, `#consumer protection`, `#IoT`

---

<a id="item-14"></a>
## [中芯国际 406 亿元收购中芯北方获上交所通过](https://www.ithome.com/0/949/016.htm) ⭐️ 8.0/10

上交所已批准中芯国际以 406 亿元收购中芯北方剩余 49%股权的方案，交易完成后中芯北方将成为其全资子公司。这是中国晶圆代工行业历史上最大的一笔并购案。 该交易巩固了中芯国际对其 12 英寸晶圆产能的控制，提升了运营协同效应和资产质量。在地缘政治持续紧张的背景下，此举标志着中国加强本土半导体供应链的战略举措。 中芯国际将向国家集成电路基金等五家股东发行股份，以 406.01 亿元收购其持有的 49%股权。交易完成后，中芯国际的主营业务范围不会发生变化。

rss · IT之家 · May 11, 13:48

**背景**: 中芯北方是中芯国际的控股子公司，主要为客户提供不同工艺平台的 12 英寸集成电路晶圆代工及配套服务。此前中芯国际已持有其 51%的股权。此次收购是中芯国际整合制造资产、提升效率的总体战略的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.qq.com/rain/a/20260511A07YLO00?adChannelId=finance">中芯国际406亿元吞下中芯北方，科创板史上最大重组案来了_腾讯新闻</a></li>
<li><a href="https://finance.sina.com.cn/wm/2026-05-11/doc-inhxptqz1777461.shtml">中芯国际406亿元吞下中芯北方，科创板史上最大重组案来了</a></li>
<li><a href="https://www.chinatimes.com/newspapers/20260512000239-260203">中芯國際買回中芯北方股權 - 全球財經 - 工商時報 | 中時新聞網</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#M&A`, `#SMIC`, `#China`, `#wafer foundry`

---

<a id="item-15"></a>
## [Linux 进入 AI 补丁时代：代码量激增成为新常态](https://news.mydrivers.com/1/1121/1121466.htm) ⭐️ 8.0/10

Linus Torvalds 发布了 Linux 7.1-rc3 版本，并指出代码补丁规模异常偏大，这很可能是开发流程中使用 AI 工具导致的。他表示这并非偶发波动，而是内核开发的新常态。 这标志着开源开发实践的重大转变，AI 工具正在推动更高的代码产出和更大的补丁量。它影响整个 Linux 内核社区，包括维护者和贡献者，他们必须适应这一新现实。 本次更新周期中，网络模块补丁占比达到所有变更的三分之一，同时修复了蓝牙和显卡驱动中的释放后重用漏洞。该版本还新增了对苹果 Mac USB-C 网络功能的支持，并优化了龙芯 LoongArch 架构的 KVM 虚拟化。

rss · 快科技 · May 11, 17:07

**背景**: Linux 内核是 Linux 操作系统的核心，由 Linus Torvalds 领导的全球社区维护。AI 辅助编码工具（如大语言模型）可以更快地生成代码，导致提交的补丁规模更大。内核社区最近制定了政策，要求披露 AI 生成的代码以确保责任归属。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.zdnet.com/article/linus-torvalds-and-maintainers-finalize-ai-policy-for-linux-kernel-developers/">The new rules for AI-assisted code in the Linux kernel... | ZDNET</a></li>
<li><a href="https://www.phoronix.com/news/LoongArch-Linux-KVM">LoongArch Linux Patches Enable KVM Virtualization - Phoronix</a></li>
<li><a href="https://www.memorysafety.org/blog/linux-kernel-2025-update/">An Update on Memory Safety in the Linux Kernel - Prossimo</a></li>

</ul>
</details>

**标签**: `#Linux`, `#AI`, `#kernel development`, `#open source`, `#software engineering`

---

<a id="item-16"></a>
## [假冒 Codex 网站登上谷歌搜索首位，传播恶意软件](https://www.v2ex.com/t/1212003#reply29) ⭐️ 8.0/10

一位开发者发现，谷歌搜索“Codex”的第一个结果是假冒网站，它模仿 ChatGPT 官方界面，并通过 base64 混淆的 curl 命令分发恶意软件。该恶意脚本从远程服务器下载并执行载荷。 该攻击针对搜索 AI 编码工具的开发者，利用对搜索结果的信任传播恶意软件。它凸显了 AI 工具生态中 SEO 投毒风险的上升，假冒网站可能绕过用户的警惕。 假冒网站的安装命令使用 `echo` 显示看似无害的 URL，但实际上执行了 base64 解码后的 curl 命令并管道至 zsh。base64 字符串解码后指向 greenactiv.com 上的一个 URL，该 URL 下载并运行恶意脚本。

rss · V2EX · May 11, 14:55

**背景**: Base64 编码是恶意软件作者常用的混淆技术，用于在明处隐藏恶意载荷。攻击者常利用 SEO 投毒将假冒网站推至搜索结果前列，诱骗用户下载恶意软件。搜索 Codex 等工具的开发者是主要目标，因为他们经常从网页上运行命令。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infosecinstitute.com/resources/malware-analysis/using-base64-for-malware-obfuscation/">Using Base64 for malware obfuscation | Infosec</a></li>
<li><a href="https://www.opswat.com/blog/how-base64-encoding-opens-the-door-for-malware">How Base64 Encoding Opens the Door for Malware - OPSWAT</a></li>

</ul>
</details>

**社区讨论**: V2EX 帖子有 29 条回复，许多用户分享了类似经历并提醒他人。一些评论者分析了混淆技术，另一些建议使用广告拦截器或在运行命令前验证 URL。

**标签**: `#security`, `#malware`, `#AI tools`, `#phishing`, `#developer warning`

---

<a id="item-17"></a>
## [Bun 确认从 Zig 迁移到 Rust](https://www.v2ex.com/t/1211992#reply18) ⭐️ 8.0/10

Bun 创始人 Jarred Sumner 确认，下一个版本可能是最后一个基于 Zig 的版本，因为一个通过所有测试套件并修复约 200 个问题的 Rust 重写版正在考虑合并。 这一迁移可能显著提升 Bun 的稳定性和防崩溃能力，通过使 Bun 更可靠地用于生产环境，从而影响 JavaScript 运行时生态系统。 Rust 重写版不使用 Rust 异步机制，且极少依赖第三方库，与 Zig 代码库结构一致。Sumner 指出，没有任何基准测试显示它比 Zig 版本慢。

rss · V2EX · May 11, 13:21

**背景**: Bun 是一个用 Zig 编写的高性能 JavaScript 运行时，旨在作为 Node.js 的直接替代品。Zig 是一种注重简洁和性能的系统编程语言，而 Rust 则提供更强的内存安全保证和更好的防崩溃工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/bun: Incredibly fast JavaScript runtime ...Bun Guide: Install, Configure & Deploy the Fast JS Runtime ...How to Install Bun - commandlinux.comWhat Is Bun JS? Ultra-Fast JavaScript Runtime Explained (2025 ...Bun 2026: How the Anthropic Acquisition Reshapes the ...</a></li>

</ul>
</details>

**社区讨论**: V2EX 上的讨论普遍支持这一迁移，用户称赞 Rust 的工具链和安全性。部分人担心失去 Zig 的简洁性，但多数人认为为了稳定性，这种取舍是值得的。

**标签**: `#Bun`, `#Rust`, `#Zig`, `#JavaScript Runtime`, `#Migration`

---

<a id="item-18"></a>
## [Figure AI 展示双机器人协作铺床](http://www.geekpark.net/news/363963) ⭐️ 8.0/10

2025 年 5 月 8 日，Figure AI 发布新演示，两台 Helix-02 人形机器人通过单一神经网络实现全球首次多机器人协作定位操作，共同完成卧室整理，包括铺床。 该演示标志着多机器人协作无需中央控制或显式通信的突破，仅依靠视觉观察和共享神经网络，可能极大推动家用机器人和人机交互的发展。 每台机器人独立运行模型，通过观察对方动作自主决策。演示中包括处理被子等柔性物体，这是机器人领域公认的难题。

rss · 极客公园 · May 11, 02:58

**背景**: 定位操作（locomanipulation）结合了移动和操作能力，使机器人能同时移动并与物体交互。Figure AI 是领先的人形机器人公司，其 Helix 系统使用视觉-语言-动作（VLA）模型，无需大量手动训练即可控制机器人。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Figure_AI">Figure AI - Wikipedia</a></li>
<li><a href="https://www.theresarobotforthat.com/figures-humanoids-read-each-others-minds-making-beds/">Humanoid Collaboration | Figure's Mind-Reading Robots</a></li>
<li><a href="https://www.maginative.com/article/meet-helix-the-ai-behind-figures-humanoid-robots-that-reason-like-humans/">Meet Helix: The AI Behind Figure’s Humanoid Robots That Reason Like Humans</a></li>

</ul>
</details>

**标签**: `#robotics`, `#AI`, `#multi-robot systems`, `#neural networks`, `#locomanipulation`

---