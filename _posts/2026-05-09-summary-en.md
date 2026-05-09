---
layout: default
title: "Daily News 2026-05-09"
date: 2026-05-09
lang: en
---

> From 288 items, 19 important content pieces were selected

---

1. [Google's reCAPTCHA Update Blocks De-Googled Android Users](#item-1) ⭐️ 8.0/10
2. [AI is breaking two vulnerability cultures](#item-2) ⭐️ 8.0/10
3. [AWS data center overheating in North Virginia disrupts services](#item-3) ⭐️ 8.0/10
4. [Meta Removes End-to-End Encryption from Instagram DMs](#item-4) ⭐️ 8.0/10
5. [Anthropic Teaches AI Models the 'Why' Behind Desired Behaviors](#item-5) ⭐️ 8.0/10
6. [Mojo 1.0 Beta Released with Advanced Features](#item-6) ⭐️ 8.0/10
7. [Thariq Shihipar advocates HTML over Markdown for LLM outputs](#item-7) ⭐️ 8.0/10
8. [Xiaohongshu Accelerates AI Strategy with New Department Dots](#item-8) ⭐️ 8.0/10
9. [Tsinghua AI Infra Startup Raises Hundreds of Millions for GPU-Centric Architecture](#item-9) ⭐️ 8.0/10
10. [DeepSeek Plans Record $7 Billion Funding Round](#item-10) ⭐️ 8.0/10
11. [Musk Visits Intel Oregon Fab for 18A/14A AI Chip Production](#item-11) ⭐️ 8.0/10
12. [New Unisplendour Unveils 'Zixuan' 3D Near-Memory Compute Architecture with 30TB/s Bandwidth](#item-12) ⭐️ 8.0/10
13. [NERC Issues Highest Alert on Data Center Grid Risks](#item-13) ⭐️ 8.0/10
14. [Apple and Intel Reach Chip Manufacturing Deal, Reducing TSMC Reliance](#item-14) ⭐️ 8.0/10
15. [OpenAI Releases Three Powerful Voice AI Models](#item-15) ⭐️ 8.0/10
16. [US Probes $2.5B Nvidia GPU Smuggling via Thai Firm OBON](#item-16) ⭐️ 8.0/10
17. [Samsung and SK Hynix Battle Over 7th-Gen DRAM Standard](#item-17) ⭐️ 8.0/10
18. [Research reveals API proxies can hijack AI agents; Probe tool released](#item-18) ⭐️ 8.0/10
19. [Musk's $55B chip fab plan: SpaceX's Terafab in Texas](#item-19) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Google's reCAPTCHA Update Blocks De-Googled Android Users](https://reclaimthenet.org/google-broke-recaptcha-for-de-googled-android-users) ⭐️ 8.0/10

Google's latest reCAPTCHA update now requires remote attestation, effectively blocking users of de-Googled Android devices (e.g., GrapheneOS) from completing CAPTCHA challenges. This move forces privacy-conscious users to choose between using Google services and maintaining device autonomy, raising concerns about remote attestation becoming a de facto requirement for web access. The new reCAPTCHA uses remote attestation to verify device integrity, which requires a trusted platform module (TPM) and Google-signed keys—features absent in de-Googled ROMs. This breaks compatibility with custom Android distributions that remove Google Play Services.

hackernews · anonymousiam · May 8, 18:45 · [Discussion](https://news.ycombinator.com/item?id=48067119)

**Background**: De-Googled Android refers to custom ROMs like GrapheneOS or LineageOS that strip out Google services for privacy. Remote attestation is a Trusted Computing technique where hardware proves its identity to a remote server, often using a unique burned-in key. Critics argue it can be used for device fingerprinting and user tracking.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Remote_attestation">Remote attestation</a></li>
<li><a href="https://tech.yahoo.com/phones/articles/googling-android-simpler-think-no-193119747.html">De-Googling Android is simpler than you think—no special phone...</a></li>

</ul>
</details>

**Discussion**: Community comments express strong opposition, with users calling remote attestation a form of KYC and vowing to abandon Google services entirely. Some seek alternative CAPTCHA providers, while others highlight the technical link between reCAPTCHA and Google Cloud Fraud Defense.

**Tags**: `#privacy`, `#Android`, `#reCAPTCHA`, `#Google`, `#remote attestation`

---

<a id="item-2"></a>
## [AI is breaking two vulnerability cultures](https://www.jefftk.com/p/ai-is-breaking-two-vulnerability-cultures) ⭐️ 8.0/10

AI tools are accelerating the identification and exploitation of vulnerabilities, undermining the traditional coordinated disclosure model and forcing a shift in how software security is managed. This shift could lead to shorter embargo periods and more aggressive exploitation, increasing pressure on organizations to patch faster and adopt more transparent security practices. The article uses the Log4Shell vulnerability as a real-world example, where attackers exploited the bug before the official disclosure date by analyzing public commits.

hackernews · speckx · May 8, 17:55 · [Discussion](https://news.ycombinator.com/item?id=48066524)

**Background**: Coordinated vulnerability disclosure (CVD) is a process where a vulnerability is reported privately to the vendor, allowing time for a patch before public disclosure. The traditional model relies on embargo periods to give defenders a head start. However, with AI and improved reverse engineering tools, attackers can now discover and weaponize vulnerabilities faster, breaking this model.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Coordinated_vulnerability_disclosure">Coordinated vulnerability disclosure - Wikipedia</a></li>
<li><a href="https://www.cisa.gov/coordinated-vulnerability-disclosure-process">Coordinated Vulnerability Disclosure Program | CISA</a></li>
<li><a href="https://jfrog.com/blog/log4shell-0-day-vulnerability-all-you-need-to-know/">Log4Shell Zero-Day Vulnerability - CVE-2021-44228</a></li>

</ul>
</details>

**Discussion**: Commenters note that this problem predates AI, citing examples like kernel commit diffing. Some argue that cheaper exploit generation makes coordinated disclosure more important, not less. Others highlight the broader context of cyber warfare and the need for faster defensive responses.

**Tags**: `#AI`, `#vulnerability disclosure`, `#software security`, `#Log4Shell`, `#open source`

---

<a id="item-3"></a>
## [AWS data center overheating in North Virginia disrupts services](https://www.reuters.com/business/retail-consumer/amazon-cloud-unit-says-data-center-overheating-north-virginia-disrupts-services-2026-05-08/) ⭐️ 8.0/10

On May 8, 2026, an overheating incident at an AWS data center in North Virginia caused service disruptions across multiple AWS services, affecting customers like FanDuel and Coinbase. This outage highlights the fragility of the us-east-1 region, which hosts a disproportionate share of cloud workloads, and raises questions about data center cooling design and redundancy practices. The overheating was likely caused by cooling equipment failure or external factors, not simply overprovisioning. AWS's health dashboard reported EC2 impairment, and the incident occurred in the us-east-1 region, which has a history of outages.

hackernews · christhecaribou · May 8, 03:31 · [Discussion](https://news.ycombinator.com/item?id=48058197)

**Background**: AWS us-east-1 is the oldest and busiest AWS region, hosting many critical services and customers. Data centers rely on sophisticated cooling systems (e.g., CRAC units, hot/cold aisle containment) to dissipate heat from servers; failure can lead to rapid overheating and shutdowns.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html">Regions and Zones - Amazon Elastic Compute Cloud</a></li>
<li><a href="https://www.statuscake.com/blog/when-aws-us-east-1-fails-much-of-the-internet-fails-with-it/">When AWS us-east-1 Fails, Much of the Internet Fails... - StatusCake</a></li>
<li><a href="https://www.theregister.com/2025/10/29/aws_us_east_1_more_problems/">AWS US-EAST-1 region is having another bad day • The Register</a></li>

</ul>
</details>

**Discussion**: Commenters questioned whether AWS overbooks cooling capacity or if equipment failure was to blame. Some criticized the industry's over-reliance on us-east-1, calling it a single point of failure, and suggested building data centers near oceans for better cooling.

**Tags**: `#AWS`, `#outage`, `#data center`, `#cloud`, `#reliability`

---

<a id="item-4"></a>
## [Meta Removes End-to-End Encryption from Instagram DMs](https://www.pcmag.com/news/meta-shuts-down-end-to-end-encryption-for-instagram-dms-messaging) ⭐️ 8.0/10

Meta has discontinued end-to-end encryption for Instagram direct messages, a feature that was opt-in since 2023, citing low adoption and the need to address safety concerns. This decision reverses a major privacy commitment and sparks debate over corporate responsibility, as it prioritizes safety monitoring over user privacy, potentially affecting millions of users. Meta stated that very few users opted into the encryption feature, and the change allows the company to better respond to scams, harassment, and legal requests. Users who had enabled encryption can download their encrypted message history.

hackernews · tcp_handshaker · May 8, 21:47 · [Discussion](https://news.ycombinator.com/item?id=48069192)

**Background**: End-to-end encryption ensures that only the sender and recipient can read messages, preventing even the service provider from accessing them. Meta had introduced opt-in E2EE for Instagram DMs in 2023, but now removes it, contrasting with WhatsApp which uses E2EE by default.

<details><summary>References</summary>
<ul>
<li><a href="https://www.pcmag.com/news/meta-shuts-down-end-to-end-encryption-for-instagram-dms-messaging">Meta Shuts Down End-to-End Encryption for Instagram Messaging</a></li>
<li><a href="https://www.macrumors.com/2026/05/08/instagram-end-to-end-encryption/">Warning: Instagram DMs Lose End-to-End Encryption Starting ...</a></li>
<li><a href="https://www.cnet.com/news/privacy/instagram-messaging-encryption-ending-explainer/">Instagram's Messaging Encryption is Ending. Here's What You ...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed strong criticism, accusing Meta of prioritizing profit over privacy and questioning why encryption wasn't made default like in WhatsApp. Some suggested avoiding Meta products if privacy is a concern, while others sarcastically noted the irony of citing safety to justify removing encryption.

**Tags**: `#privacy`, `#encryption`, `#Meta`, `#Instagram`, `#surveillance`

---

<a id="item-5"></a>
## [Anthropic Teaches AI Models the 'Why' Behind Desired Behaviors](https://www.anthropic.com/research/teaching-claude-why) ⭐️ 8.0/10

Anthropic published research exploring a pedagogical approach to AI alignment, where models are taught the reasoning behind desired behaviors rather than just the behaviors themselves. This could lead to more robust and generalizable alignment, as models that understand the 'why' may better handle novel situations and resist adversarial attacks. The approach draws inspiration from human pedagogy, where teachers explain reasons rather than just showing examples. The research is part of Anthropic's broader alignment science efforts.

hackernews · pretext · May 8, 17:59 · [Discussion](https://news.ycombinator.com/item?id=48066592)

**Background**: AI alignment aims to ensure AI systems act in accordance with human values and intentions. Traditional training often uses reward signals or supervised learning to shape behavior, but this can lead to brittle or misaligned outcomes. Teaching the underlying reasoning may produce more adaptable and trustworthy models.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/research">Research \ Anthropic</a></li>
<li><a href="https://www.libertify.com/interactive-library/anthropic-ai-safety-research-alignment-and-reasoning-models/">Anthropic AI Safety Research: Alignment and Reasoning Models —...</a></li>

</ul>
</details>

**Discussion**: Commenters compared alignment to pedagogy, with one noting that given finite training data, eliciting desired behavior is a pedagogical problem. Others raised philosophical concerns: if a highly capable aligned model causes societal harm, can it still be called aligned? This highlights the need for better definitions of alignment.

**Tags**: `#AI alignment`, `#machine learning`, `#Anthropic`, `#reasoning`, `#ethics`

---

<a id="item-6"></a>
## [Mojo 1.0 Beta Released with Advanced Features](https://mojolang.org/) ⭐️ 8.0/10

Mojo 1.0 Beta has been released, introducing an ownership model similar to Rust, powerful comptime metaprogramming, and first-class SIMD support. The language remains proprietary until Fall 2026, with only the standard library open-sourced. Mojo aims to combine Python-like syntax with Rust-level performance, targeting machine learning and systems programming. Its release could challenge existing high-performance languages like Rust and Zig, but the delayed open-sourcing may hinder adoption. Mojo's ownership model differs from Rust's references and lifetimes, and its comptime is considered more powerful than Zig's. The language uses LLVM but in a unique way, not as a simple wrapper. Python compatibility remains limited; Mojo cannot directly run existing Python code.

hackernews · sbt567 · May 8, 02:49 · [Discussion](https://news.ycombinator.com/item?id=48057901)

**Background**: Mojo is a programming language developed by Modular Inc., designed as a superset of Python with additional features for high-performance computing. It leverages MLIR (Multi-Level Intermediate Representation) for optimization and targets both CPUs and GPUs. The language has been in development since 2022 and has gained significant community interest.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language) - Wikipedia</a></li>
<li><a href="https://docs.modular.com/mojo/std/builtin/simd/">simd - Modular</a></li>
<li><a href="https://github.com/modular/max/issues/933">[mojo-compiler] CompTime interpreter should be able to fold...</a></li>

</ul>
</details>

**Discussion**: Community members express excitement about Mojo's performance and features, but concerns remain about Python compatibility and the proprietary timeline. Some users note that Nvidia's CUDA advancements (e.g., CuTile) may compete with Mojo. The delayed open-sourcing until Fall 2026 is a point of contention.

**Tags**: `#Mojo`, `#programming language`, `#ML`, `#performance`, `#open source`

---

<a id="item-7"></a>
## [Thariq Shihipar advocates HTML over Markdown for LLM outputs](https://simonwillison.net/2026/May/8/unreasonable-effectiveness-of-html/#atom-everything) ⭐️ 8.0/10

Thariq Shihipar, a member of Anthropic's Claude Code team, published a piece arguing that HTML is a superior output format for LLMs compared to Markdown, providing concrete examples and prompt templates. He demonstrates how HTML enables richer features like SVG diagrams, interactive widgets, and in-page navigation. This challenges the widespread practice of defaulting to Markdown for LLM outputs, which originated from token-efficiency concerns in earlier models. Adopting HTML could significantly improve the quality and interactivity of AI-generated explanations, especially for complex topics like code review or security exploits. Shihipar provides a prompt example asking Claude to create an HTML artifact for PR review, focusing on streaming/backpressure logic with inline diff annotations and severity color-coding. Simon Willison tested the approach with GPT-5.5 on a Linux exploit, producing a rich HTML page with callouts and step-by-step explanations.

rss · Simon Willison · May 8, 21:00

**Background**: Markdown has been the default output format for many LLM users since the GPT-4 era due to its token efficiency under the 8,192 token limit. HTML, while more expressive, was avoided because it consumes more tokens. However, with larger context windows in modern models, the token cost of HTML is less of a concern, and its ability to embed rich media and interactivity becomes a significant advantage.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#prompt engineering`, `#HTML`, `#Claude`, `#best practices`

---

<a id="item-8"></a>
## [Xiaohongshu Accelerates AI Strategy with New Department Dots](https://36kr.com/p/3799028783439111?f=rss) ⭐️ 8.0/10

On April 30, 2026, Xiaohongshu announced the establishment of a new AI first-level department called Dots, integrating model R&D, infrastructure, engineering, and product teams. The department was upgraded from the previous Hi Lab (Humane Intelligence Lab) and now oversees the company's key AI product 'Dots' (点点). This move signals a strategic shift from cautious exploration to aggressive pursuit of AI opportunities for Xiaohongshu, a major Chinese social platform. It reflects the industry-wide urgency to integrate AI into core products and could reshape how AI is applied in community-driven platforms. Dots reports directly to new president Ke Nan and consists of four sub-departments: model R&D, infrastructure, engineering, and product. The AI product 'Dots' has undergone four phases of exploration, including a shift from self-developed models to integrating DeepSeek, and recently moved from a standalone app to an in-app feature within Xiaohongshu's main interface.

rss · 36氪 · May 8, 04:38

**Background**: Xiaohongshu is a Chinese social platform known for its community-driven content sharing, particularly in lifestyle and shopping. Since ChatGPT's launch in 2022, the company has been cautious about AI, balancing innovation with preserving its 'human touch' community atmosphere. The new department represents a major organizational upgrade to prioritize AI development.

<details><summary>References</summary>
<ul>
<li><a href="https://www.firecat-web.com/daily-news/8070">小红书成立AI一级部门Dots，从克制到加速的底层逻辑</a></li>
<li><a href="https://finance.sina.com.cn/wm/2026-04-30/doc-inhwhkum4192914.shtml">小红书成立AI一级部门Dots - 新浪财经</a></li>
<li><a href="https://www.10100.com/article/129868990">小红书成立AI一级部门Dots- 大数跨境 - 10100.com</a></li>

</ul>
</details>

**Tags**: `#AI strategy`, `#social media`, `#product development`, `#China tech`, `#industry analysis`

---

<a id="item-9"></a>
## [Tsinghua AI Infra Startup Raises Hundreds of Millions for GPU-Centric Architecture](https://36kr.com/p/3799984046333186?f=rss) ⭐️ 8.0/10

Beijing Rongxin Zhiyuan Technology completed a hundreds-of-millions-yuan angel round led by Beijing Green Energy and Low-Carbon Industry Fund and SAIF Partners, proposing the AGC architecture that places the GPU at the center of AI computing systems instead of the CPU. This architecture could significantly improve GPU utilization and system efficiency for large-scale AI training and inference, addressing a critical bottleneck in AI infrastructure. It also promotes an open ecosystem compatible with domestic Chinese CPUs and GPUs, supporting national self-reliance goals. AGC architecture increases the GPU-to-CPU ratio from about 2:1 to 20:1 or even 32:1, supports unified memory address space across up to 64 GPUs, and enables hot-swappable GPU RAID that reduces maintenance downtime from ~2 hours to ~1 minute. The company also developed a microsecond-response AI BMC system and Blue Link optical interconnect.

rss · 36氪 · May 8, 01:45

**Background**: Traditional AI servers rely on a CPU-centric architecture where CPUs coordinate data flow among GPUs, creating bottlenecks as GPU counts scale. The AGC architecture redefines the GPU as the primary computing unit, reducing CPU dependency and enabling more efficient data sharing and fault tolerance.

<details><summary>References</summary>
<ul>
<li><a href="https://zhuanlan.zhihu.com/p/1905299140453336100">中国AI计算迎重大突破！首批AGC架构智算整机问世</a></li>

</ul>
</details>

**Tags**: `#AI Infrastructure`, `#GPU Architecture`, `#Funding`, `#System Design`, `#Chinese Tech`

---

<a id="item-10"></a>
## [DeepSeek Plans Record $7 Billion Funding Round](https://36kr.com/newsflashes/3800574318976257?f=rss) ⭐️ 8.0/10

DeepSeek is seeking to raise up to 50 billion yuan (about $7 billion) in its first external funding round, which would be the largest ever for a Chinese AI company. The company also plans to accelerate model releases, including a V4.1 update in June. This record-breaking round signals strong investor confidence in DeepSeek and the broader Chinese AI ecosystem, potentially reshaping the competitive landscape against global players. It also underscores the growing demand for cost-efficient, open-weight AI models. DeepSeek founder and CEO Liang Wenfeng plans to contribute the largest portion of the funding. The company has informed some investors that it will increase model release frequency to align with industry standards.

rss · 36氪 · May 8, 11:44

**Background**: DeepSeek, founded in July 2023 by Liang Wenfeng, is a Chinese AI company known for its open-weight large language models like DeepSeek-R1 and V3. It gained global attention for training models at a fraction of the cost of rivals like OpenAI, using weaker chips due to export restrictions. The company is owned by hedge fund High-Flyer and has not previously taken external funding.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(Company)">DeepSeek (Company)</a></li>
<li><a href="https://api-docs.deepseek.com/news/news260424">DeepSeek V4 Preview Release | DeepSeek API Docs</a></li>

</ul>
</details>

**Tags**: `#AI`, `#funding`, `#China`, `#DeepSeek`

---

<a id="item-11"></a>
## [Musk Visits Intel Oregon Fab for 18A/14A AI Chip Production](https://www.ithome.com/0/948/002.htm) ⭐️ 8.0/10

Elon Musk visited Intel's Oregon fab to evaluate the Intel 18A and 14A processes for producing SpaceX AI chips, confirming a potential partnership. Intel's 14A process is slated for SpaceXAI's next-generation AI chips, while 18A is used for Panther Lake. This visit signals a major potential partnership between Intel and Musk's companies, boosting Intel's foundry business and providing advanced US-based manufacturing for SpaceX AI chips. It could reduce reliance on TSMC and Samsung for critical AI hardware. Intel's 18A process introduces RibbonFET gate-all-around transistors and PowerVia backside power delivery, crucial for AI chip energy efficiency. The 14A process is more advanced but has not yet secured external customer orders beyond this potential deal.

rss · IT之家 · May 8, 23:26

**Background**: Intel's 18A is a key node in its manufacturing comeback, using RibbonFET and PowerVia technologies. The Terafab project is a joint initiative by SpaceX, Tesla, and xAI to produce 1 terawatt of computing power annually, requiring advanced chips. Musk previously stated plans to use Intel's 14A for Terafab.

<details><summary>References</summary>
<ul>
<li><a href="https://www.aol.com/finance/intel-18a-process-finally-ready-123000951.html">The Intel 18A Process Is Finally Ready - AOL</a></li>
<li><a href="https://wccftech.com/intels-bspdn-on-18a-is-a-major-technical-win-that-may-also-be-holding-back-external-adoption/">Intel’s “BSPDN” Power-Delivery Method on 18A Is a Major Technical...</a></li>
<li><a href="https://builtin.com/articles/elon-musk-terafab-project">Elon Musk’s Terafab Project: What to Know About His Chip... | Built In</a></li>

</ul>
</details>

**Tags**: `#semiconductor`, `#AI chips`, `#Intel`, `#SpaceX`, `#manufacturing`

---

<a id="item-12"></a>
## [New Unisplendour Unveils 'Zixuan' 3D Near-Memory Compute Architecture with 30TB/s Bandwidth](https://www.ithome.com/0/947/993.htm) ⭐️ 8.0/10

New Unisplendour Group's Frontier Technology Research Institute released the 'Zixuan' 3D near-memory computing (PNM) architecture on May 6, 2026, claiming a memory bandwidth of 30TB/s and 1.5-2x token throughput over NVIDIA B200 series. This architecture could challenge NVIDIA's dominance in AI hardware by offering superior bandwidth and latency, potentially enabling more efficient large-scale AI model inference and training. The architecture uses a 3.5D heterogeneous integration scheme with 3D DRAM, reducing memory access latency by up to 18x, and is claimed to be mass-producible using domestic supply chains.

rss · IT之家 · May 8, 22:51

**Background**: Near-memory computing (PNM) moves computation closer to memory to reduce data movement bottlenecks. HBM4 is the latest high-bandwidth memory standard, but 'Zixuan' claims to exceed its bandwidth and capacity. The 3.5D integration stacks multiple dies vertically with advanced packaging.

<details><summary>References</summary>
<ul>
<li><a href="https://news.qq.com/rain/a/20260508A055XL00">紫弦三维化近存计算架构发布，存储带宽30TB/s，访存延迟降低18倍</a></li>
<li><a href="https://www.ithome.com/0/947/993.htm">新紫光发布“紫弦”三维化近存计算架构：存储带宽可达 30TB/s - IT之家</a></li>
<li><a href="https://www.cls.cn/detail/2365842">新紫光前沿技术研究院发布“紫弦”三维近存架构</a></li>

</ul>
</details>

**Tags**: `#近存计算`, `#3D DRAM`, `#AI芯片`, `#存储带宽`

---

<a id="item-13"></a>
## [NERC Issues Highest Alert on Data Center Grid Risks](https://www.ithome.com/0/947/943.htm) ⭐️ 8.0/10

The North American Electric Reliability Corporation (NERC) issued a rare Level 3 Essential Action Alert, its highest warning level, requiring grid operators to address immediate risks from data centers, especially AI workloads, that cause rapid power fluctuations potentially leading to blackouts. This alert signals that data center power demand, driven by AI and crypto mining, has become an urgent threat to grid reliability across the US, Canada, and Mexico. It forces utilities and regulators to accelerate grid modernization and load management strategies. NERC's alert notes that grid operators lack adequate processes to handle computational load fluctuations that can occur within seconds. Entities must submit risk mitigation plans by August 3, 2025.

rss · IT之家 · May 8, 11:44

**Background**: NERC is the regulatory authority overseeing bulk power system reliability in North America. Its alerts range from Level 1 (advisory) to Level 3 (essential action). Data centers, especially those running AI training, exhibit highly variable power draw, which traditional grid infrastructure was not designed to handle.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nerc.com/newsroom/nerc-issues-level-3-alert-reliability-guideline-focused-on-large-load-challenges">NERC Issues Level 3 Alert, Reliability Guideline Focused on ...</a></li>
<li><a href="https://www.utilitydive.com/news/nerc-issues-rare-level-3-alert-over-data-center-load-losses/819295/">NERC issues Level 3 alert, mandates action to address data ...</a></li>
<li><a href="https://www.carbon-direct.com/insights/nerc-level-3-alert-data-center-loads">Inside NERC’s Level 3 Alert on data center loads</a></li>

</ul>
</details>

**Tags**: `#data centers`, `#grid stability`, `#AI infrastructure`, `#energy`, `#regulation`

---

<a id="item-14"></a>
## [Apple and Intel Reach Chip Manufacturing Deal, Reducing TSMC Reliance](https://news.mydrivers.com/1/1121/1121017.htm) ⭐️ 8.0/10

Apple and Intel have reached a preliminary agreement for Intel to manufacture some of Apple's chips, including low-end M-series chips for iPads and Macs, and potentially A-series chips for non-Pro iPhones. The deal marks Apple's first break from exclusive reliance on TSMC for chip production. This deal diversifies Apple's chip supply chain, reducing risk from TSMC's capacity constraints amid AI-driven demand. It also validates Intel's foundry turnaround under CEO Lip-Bu Tan, potentially reshaping the semiconductor manufacturing landscape. Initial production likely focuses on entry-level chips using Intel's advanced 18A (1.8nm) and 14A (1.4nm) processes, with first chips expected in 2027–2028. Apple retains chip design, while Intel handles manufacturing only.

rss · 快科技 · May 9, 07:12

**Background**: Apple has exclusively used TSMC for its custom chips since 2016, but AI chip demand from companies like Nvidia has strained TSMC's advanced capacity, causing supply shortages for Apple's iPhone 17 series. Intel's new CEO Lip-Bu Tan has pushed foundry reforms, accelerating 18A and 14A process development to attract external customers.

<details><summary>References</summary>
<ul>
<li><a href="https://news.qq.com/rain/a/20251012A04DDJ00">英特尔称18A为自家独享：友商可以选择14A工艺进行代工</a></li>
<li><a href="https://www.doit.com.cn/p/534575.html">英特尔18A与14A制程大揭秘：引领代工技术新飞跃-DOIT-数据产业媒体与...</a></li>
<li><a href="https://baike.baidu.com/item/14A制程工艺/67294484">14A制程工艺 - 百度百科</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#Intel`, `#semiconductor`, `#supply chain`, `#chip manufacturing`

---

<a id="item-15"></a>
## [OpenAI Releases Three Powerful Voice AI Models](https://news.mydrivers.com/1/1120/1120999.htm) ⭐️ 8.0/10

OpenAI has upgraded its Realtime API with three new voice AI models: GPT-Realtime-2, GPT-Realtime-Translate, and GPT-Realtime-Whisper. These models bring GPT-5-level reasoning, real-time translation across 70+ languages, and streaming transcription capabilities. This update significantly lowers the barrier for developers to build intelligent voice applications, enabling more natural and responsive voice interactions. It marks a shift from basic voice Q&A to a comprehensive voice operating system that listens, thinks, translates, and transcribes in real time. GPT-Realtime-2 supports configurable reasoning effort, allowing developers to balance latency and output quality. GPT-Realtime-Translate supports speech recognition in over 70 languages and voice output in 13 languages, while GPT-Realtime-Whisper is priced by audio duration rather than text tokens.

rss · 快科技 · May 8, 22:02

**Background**: OpenAI's Realtime API is a WebSocket-based interface that enables real-time, bidirectional audio communication with GPT models. Previously, developers could build speech-to-speech experiences, but the new models add advanced reasoning, translation, and streaming transcription capabilities. Whisper is OpenAI's general-purpose speech recognition model, now optimized for low-latency streaming transcription.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-the-realtime-api/">Introducing the Realtime API | OpenAI</a></li>
<li><a href="https://www.datacamp.com/blog/gpt-realtime-2">GPT-Realtime-2: A Voice Model with GPT-5-Class Reasoning</a></li>
<li><a href="https://developers.openai.com/api/docs/models/gpt-realtime-whisper">gpt-realtime-whisper Model | OpenAI API</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#voice AI`, `#real-time API`, `#GPT-5`, `#speech recognition`

---

<a id="item-16"></a>
## [US Probes $2.5B Nvidia GPU Smuggling via Thai Firm OBON](https://news.mydrivers.com/1/1120/1120976.htm) ⭐️ 8.0/10

US prosecutors have identified Thai company OBON Corp as the intermediary in a $2.5 billion scheme to smuggle Nvidia AI servers to China, and Supermicro co-founder Wally Liaw has been indicted for his alleged involvement. This case represents the largest crackdown on AI chip smuggling since US export controls were tightened in 2022, highlighting the high stakes in controlling advanced semiconductor access to China and the risks for major hardware companies like Supermicro. OBON was Supermicro's 11th-largest customer in Q2 2024, contributing nearly $100 million in quarterly revenue. Supermicro conducted multiple compliance audits on OBON starting in October 2024 and briefly halted shipments, but the alleged smuggling continued.

rss · 快科技 · May 8, 19:14

**Background**: Since October 2022, the US has imposed export controls restricting the sale of advanced Nvidia GPUs (such as A100, H100, and later models) to China, aiming to slow China's AI development. Smugglers have used intermediaries in third countries like Thailand to reroute restricted chips. OBON Corp, a little-known Thai firm, also created Siam AI, Thailand's sovereign cloud champion.

<details><summary>References</summary>
<ul>
<li><a href="https://www.msn.com/en-us/money/other/thai-firm-obon-corp-lands-in-us-probe-over-nvidia-chip-flows-to-china/ar-AA22I6QA">Thai firm OBON Corp lands in US probe over Nvidia chip flows ...</a></li>
<li><a href="https://fortune.com/2026/03/19/supermicro-arrested-founder-smuggling-gpu-china/">Supermicro’s cofounder was just arrested for allegedly smuggling...</a></li>
<li><a href="https://en.wikipedia.org/wiki/United_States_export_controls_on_AI_chips_and_semiconductors">United States export controls on AI chips and semiconductors</a></li>

</ul>
</details>

**Tags**: `#Nvidia`, `#export controls`, `#AI chips`, `#smuggling`, `#Supermicro`

---

<a id="item-17"></a>
## [Samsung and SK Hynix Battle Over 7th-Gen DRAM Standard](https://news.mydrivers.com/1/1120/1120935.htm) ⭐️ 8.0/10

Samsung and SK Hynix are competing to set the 7th generation DRAM (1d) standard, with Samsung promoting GAAFET architecture and SK Hynix adopting 4F² vertical stacking. Both aim for mass production within 2-3 years. This competition will define the next-generation DRAM technology, impacting performance, density, and power efficiency for AI, HPC, and mobile devices. The winner could dominate the memory market for years. Samsung's GAAFET approach borrows NAND flash design by placing control circuits beneath the memory array, while SK Hynix's 4F² architecture reduces cell area by ~30% compared to traditional 6F². Samsung will present a 16-layer vertical stacked DRAM at the 2026 VLSI symposium.

rss · 快科技 · May 8, 17:12

**Background**: DRAM (Dynamic Random Access Memory) is a type of volatile memory used in computers and devices. The '1d' refers to the 7th generation DRAM process node. GAAFET (Gate-All-Around Field-Effect Transistor) wraps the gate around the channel for better control, while 4F² is a cell layout where 'F' is the minimum feature size, enabling denser memory arrays.

<details><summary>References</summary>
<ul>
<li><a href="https://wccftech.com/samsung-borrows-nand-trick-to-crack-next-gen-dram-while-sk-hynix-bets-on-vertical-stacking-to-win-the-ai-memory-war/">Samsung Borrows NAND Trick To Crack Next-Gen DRAM, While SK ...</a></li>
<li><a href="https://en.eeworld.com.cn/news/manufacture/eic722866.html">Samsung and SK Hynix compete for dominance in 3D DRAM, vying ...</a></li>

</ul>
</details>

**Tags**: `#DRAM`, `#semiconductor`, `#Samsung`, `#SK Hynix`, `#memory technology`

---

<a id="item-18"></a>
## [Research reveals API proxies can hijack AI agents; Probe tool released](https://www.v2ex.com/t/1211298#reply1) ⭐️ 8.0/10

A research paper titled 'Your Agent Is Mine' (arXiv 2604.08407) demonstrates that malicious API proxies can hijack AI agents through prompt injection, goal replacement, and data exfiltration. The authors also released a detection tool called Probe that checks proxy security with 60 test items. As more developers use API proxies for AI agent tasks, this attack vector becomes a critical security concern. The Probe tool provides a practical way to detect proxy hijacking, helping protect agent workflows and user data. Probe runs locally without exposing API keys and covers response injection, man-in-the-middle tampering, credential leakage, and model consistency checks. It supports agent frameworks like LangChain and AutoGen.

rss · V2EX · May 8, 14:28

**Background**: AI agents often use API proxies to access large language models, but a compromised proxy can alter responses to hijack agent behavior. Prompt injection attacks exploit the agent's trust in the proxy's output, leading to unauthorized actions or data theft.

<details><summary>References</summary>
<ul>
<li><a href="https://www.pentestpad.com/blog/function-poisoning-hijacking-ai-agent-tool-execution">Evil AI: Hijacking AI Agent Tool Execution | PentestPad</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://github.com/BerriAI/litellm">GitHub - BerriAI/litellm: Python SDK, Proxy Server (AI Gateway) to call...</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#API proxy`, `#prompt injection`, `#agent hijacking`, `#detection tool`

---

<a id="item-19"></a>
## [Musk's $55B chip fab plan: SpaceX's Terafab in Texas](http://www.geekpark.net/news/363854) ⭐️ 8.0/10

SpaceX has proposed a $55 billion investment to build a chip manufacturing facility called Terafab in Grimes County, Texas, with total capital expenditure potentially reaching $119 billion if fully built out. The project is a joint effort between SpaceX and Tesla to secure semiconductor supply for Musk's companies. This represents one of the largest private chip manufacturing investments ever, signaling Musk's ambition to vertically integrate AI infrastructure from chip production to deployment. If successful, it could reduce dependence on TSMC and NVIDIA, reshaping the semiconductor supply chain for AI and automotive industries. The first phase of Terafab is estimated to cost $55 billion, with initial chip output not expected until mid-2028 at the earliest. The facility would produce AI chips for Tesla Autopilot, xAI's Grok training, and other Musk ventures, but faces significant execution risks due to the complexity of advanced semiconductor manufacturing.

rss · 极客公园 · May 8, 07:46

**Background**: In the 1980s, Japan dominated the global chip market, prompting the U.S. to sign the Semiconductor Agreement to protect domestic industry. More recently, the 2022 CHIPS Act has spurred nearly $450 billion in private semiconductor investments in the U.S. Musk's Terafab plan extends this trend, aiming to secure chip supply for his companies' massive GPU demands.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/05/06/elon-musks-spacex-chip-fab-in-texas-to-cost-up-to-119-billion.html">Elon Musk's Terafab chip factory in Texas could cost up to ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Terafab">Terafab - Wikipedia</a></li>
<li><a href="https://www.usatoday.com/story/money/business/2026/05/06/spacex-tesla-files-55-billion-plans-to-build-terafab-chip-plant/89958999007/">Musk, SpaceX to invest $55 billion for Terafab chip facility ...</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#SpaceX`, `#Elon Musk`, `#chip manufacturing`, `#investment`

---