---
layout: default
title: "Daily News 2026-05-12"
date: 2026-05-12
lang: en
---

> From 281 items, 18 important content pieces were selected

---

1. [TanStack npm Packages Compromised in Worm Attack with Dead-Man's Switch](#item-1) ⭐️ 9.0/10
2. [UCLA discovers first drug to mimic stroke rehabilitation effects](#item-2) ⭐️ 9.0/10
3. [Criminal hackers used AI to find a major software flaw, Google says](#item-3) ⭐️ 9.0/10
4. [Nvidia Releases Official Rust-to-CUDA Compiler](#item-4) ⭐️ 9.0/10
5. [Fields Medalist Tests ChatGPT 5.5 Pro: PhD-Level Math in 17 Minutes](#item-5) ⭐️ 9.0/10
6. [GitLab Lays Off Staff, Replaces CREDIT Values with New Ethos](#item-6) ⭐️ 8.0/10
7. [Interfaze: New Model Architecture Claims 100x Accuracy Boost](#item-7) ⭐️ 8.0/10
8. [Thinking Machines Unveils Real-Time Multimodal Transformer](#item-8) ⭐️ 8.0/10
9. [James Shore: AI coding agents must cut maintenance costs proportionally](#item-9) ⭐️ 8.0/10
10. [Zombie Internet: The Mental Toll of AI-Generated Content](#item-10) ⭐️ 8.0/10
11. [Shopify's River AI Agent Fosters Learning Through Public Slack Channels](#item-11) ⭐️ 8.0/10
12. [OpenAI Acquires Tomoro, Launches Deployment Company for Enterprise AI](#item-12) ⭐️ 8.0/10
13. [GM Fined $12.75M in California for Selling Driver Data Without Consent](#item-13) ⭐️ 8.0/10
14. [SMIC's $40.6B Acquisition of SMIC North Approved by Shanghai Stock Exchange](#item-14) ⭐️ 8.0/10
15. [Linux Enters AI Patch Era: Larger Code Volumes Become New Normal](#item-15) ⭐️ 8.0/10
16. [Fake Codex site tops Google search, distributes malware](#item-16) ⭐️ 8.0/10
17. [Bun Confirms Migration from Zig to Rust](#item-17) ⭐️ 8.0/10
18. [Figure AI Shows Two Robots Collaborating to Make a Bed](#item-18) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [TanStack npm Packages Compromised in Worm Attack with Dead-Man's Switch](https://github.com/TanStack/router/issues/7383) ⭐️ 9.0/10

Multiple TanStack npm packages, including @tanstack/router, were compromised in a worm attack that steals credentials and includes a destructive dead-man's switch that deletes the user's home directory if the stolen token is revoked. This attack highlights critical vulnerabilities in the npm supply chain, as widely-used libraries can be weaponized to steal sensitive credentials and cause irreversible damage. It underscores the need for stronger CI/CD security and trusted publishing practices. The malware scans for AWS/GCP keys, Kubernetes tokens, Vault tokens, GitHub tokens, SSH keys, and ~/.npmrc files. It also installs a systemd service or LaunchAgent that polls GitHub API every 60 seconds and executes rm -rf ~/ if the token is revoked.

hackernews · varunsharma07 · May 11, 21:08 · [Discussion](https://news.ycombinator.com/item?id=48100706)

**Background**: npm packages are a common vector for supply chain attacks, where attackers compromise legitimate packages to distribute malware. The dead-man's switch technique ensures that even after detection, revoking the stolen token triggers destructive payload, making remediation dangerous.

<details><summary>References</summary>
<ul>
<li><a href="https://socket.dev/blog/tanstack-npm-packages-compromised-mini-shai-hulud-supply-chain-attack">Tanstack npm Packages Compromised in Ongoing Mini Shai-Hulud...</a></li>
<li><a href="https://cybersecuritynews.com/dead-mans-switch-npm-supply-chain-attack/">Dead Man's Switch - Widespread npm Supply Chain Attack</a></li>

</ul>
</details>

**Discussion**: Community members warned about the dead-man's switch and noted that the @mistralai/mistralai package was also compromised. Some argued that Trusted Publishing alone is insufficient to prevent such attacks if CI pipelines are compromised.

**Tags**: `#security`, `#npm`, `#supply chain`, `#open source`

---

<a id="item-2"></a>
## [UCLA discovers first drug to mimic stroke rehabilitation effects](https://stemcell.ucla.edu/news/ucla-discovers-first-stroke-rehabilitation-drug-repair-brain-damage) ⭐️ 9.0/10

UCLA researchers have discovered DDL-920, the first drug that fully reproduces the effects of physical stroke rehabilitation in mice, targeting disconnected but surviving neural networks to restore brain function. This breakthrough could transform stroke recovery by providing a pharmacological alternative to intensive physical therapy, which many patients cannot sustain. It addresses a major unmet need, as no drugs currently exist for stroke rehabilitation. The drug targets a specific brain circuit involved in rehabilitation-induced plasticity, and further studies are needed to assess its safety and efficacy before human trials. The compound is identified as DDL-920, as referenced in a related PubMed publication.

hackernews · bookofjoe · May 11, 17:53 · [Discussion](https://news.ycombinator.com/item?id=48098261)

**Background**: Stroke is a leading cause of adult disability because most patients do not fully recover. Physical rehabilitation can help, but its intensity is often limited. The drug aims to mimic the brain's natural repair mechanisms triggered by rehab, potentially offering a more accessible treatment.

<details><summary>References</summary>
<ul>
<li><a href="https://stemcell.ucla.edu/news/ucla-discovers-first-stroke-rehabilitation-drug-repair-brain-damage">UCLA discovers first stroke rehabilitation drug to repair brain damage</a></li>
<li><a href="https://newsroom.ucla.edu/releases/ucla-discovers-first-stroke-rehabilitation-drug-to-reestablish-brain-connections-in-mice">UCLA discovers first stroke rehabilitation drug to reestablish brain connections in mice | UCLA</a></li>

</ul>
</details>

**Discussion**: Commenters clarified that the drug targets 'bruised' but surviving neurons, not dead tissue, and noted that no intervention can yet recover function from cell death at the infarct core. Some speculated about applications for other neurodegenerative diseases, while others referenced related science fiction and provided a link to the underlying PubMed study.

**Tags**: `#stroke`, `#neuroscience`, `#drug discovery`, `#rehabilitation`, `#UCLA`

---

<a id="item-3"></a>
## [Criminal hackers used AI to find a major software flaw, Google says](https://www.nytimes.com/2026/05/11/us/politics/google-hackers-attack-ai.html) ⭐️ 9.0/10

Google's Threat Analysis Group reported that criminal hackers used an AI model to discover and weaponize a zero-day vulnerability, marking the first known case of real-world attackers leveraging AI for vulnerability discovery. This signals a paradigm shift in cybersecurity, as AI lowers the barrier for discovering zero-day vulnerabilities, potentially increasing the frequency and severity of attacks. It also raises urgent questions about the regulation of powerful AI models. The attackers used an AI model, possibly Anthropic's Mythos, to find the vulnerability, and Google's TAG has high confidence in this attribution. The vulnerability was patched before widespread exploitation, but the incident demonstrates a new capability for malicious actors.

hackernews · donohoe · May 11, 13:20 · [Discussion](https://news.ycombinator.com/item?id=48094641)

**Background**: A zero-day vulnerability is a security flaw unknown to the software vendor, leaving no patch available until discovered. Traditionally, finding such flaws required deep expertise and manual effort; AI models can now automate and accelerate this process, making it accessible to less skilled attackers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zero-day_vulnerability">Zero-day vulnerability</a></li>
<li><a href="https://blog.vidocsecurity.com/blog/hype-ai-vulnerability-discovery-national-level">Reality Check on the Mythos Hype: AI Vulnerability Discovery Is</a></li>
<li><a href="https://excited-pixels.com/2026/02/22/ai-assisted-vulnerability-hunting-is-here/">AI-Assisted Vulnerability Hunting is Here – Excited Pixels</a></li>

</ul>
</details>

**Discussion**: Commenters debated the evidence for AI involvement, with some questioning how Google could be confident. Others noted that AI-assisted hacking could devalue zero-day exploit stashes and that security concerns may be used to restrict open-weight AI models.

**Tags**: `#AI`, `#cybersecurity`, `#zero-day`, `#vulnerability`, `#Google`

---

<a id="item-4"></a>
## [Nvidia Releases Official Rust-to-CUDA Compiler](https://nvlabs.github.io/cuda-oxide/index.html) ⭐️ 9.0/10

Nvidia has released CUDA-oxide, an official compiler that translates Rust code directly to PTX, the virtual instruction set for CUDA GPU kernels. This allows developers to write GPU kernels in Rust without relying on external tools like nvcc. This development brings Rust's memory safety and modern language features to GPU programming, potentially reducing bugs in CUDA kernels. It also simplifies the build pipeline for Rust-based GPU projects, which previously required bridging to C++ CUDA code. CUDA-oxide compiles Rust code directly to PTX, bypassing nvcc, and aims to be a near drop-in replacement for existing Rust CUDA crates. The project is open-source and hosted on Nvidia Labs' GitHub.

hackernews · adamnemecek · May 11, 15:55 · [Discussion](https://news.ycombinator.com/item?id=48096692)

**Background**: CUDA is Nvidia's parallel computing platform that uses C++ extensions for GPU programming. PTX is a low-level virtual instruction set that provides forward compatibility across GPU architectures. Rust is a systems programming language focused on safety and concurrency, and its ownership model could help prevent common GPU programming errors like race conditions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Parallel_Thread_Execution">Parallel Thread Execution - Wikipedia</a></li>
<li><a href="https://developer.nvidia.com/blog/understanding-ptx-the-assembly-language-of-cuda-gpu-computing/">Understanding PTX, the Assembly Language of CUDA GPU Computing</a></li>
<li><a href="https://docs.nvidia.com/cuda/cuda-programming-guide/02-basics/nvcc.html">2.5. NVCC: The NVIDIA CUDA Compiler — CUDA Programming Guide</a></li>

</ul>
</details>

**Discussion**: The community is highly engaged, with users praising the potential for faster build times compared to existing Rust CUDA crates that rely on nvcc. Some commenters question the choice of targeting PTX directly instead of using Nvidia's MLIR or Tile IR, and others discuss challenges in mapping Rust's memory model to CUDA semantics.

**Tags**: `#CUDA`, `#Rust`, `#GPU Programming`, `#Compilers`, `#Nvidia`

---

<a id="item-5"></a>
## [Fields Medalist Tests ChatGPT 5.5 Pro: PhD-Level Math in 17 Minutes](https://www.ithome.com/0/949/032.htm) ⭐️ 9.0/10

Fields Medalist Timothy Gowers tested ChatGPT 5.5 Pro on open problems in additive number theory. Within 17 minutes, the AI independently produced a result he deemed worthy of a PhD thesis, without any mathematical guidance from him. This demonstration signals that AI is rapidly approaching the ability to conduct original mathematical research, posing an urgent threat to the career prospects of PhD students and early-career mathematicians. It forces the academic community to reconsider the value of human mathematical work in the AI era. Gowers used problems from a paper by Mel Nathanson, which were originally intended as training material for new PhD students. The AI not only solved the problems but also formatted the results into a LaTeX preprint, requiring only prompts like 'expand on that idea' and 'write it in LaTeX.'

rss · IT之家 · May 11, 15:54

**Background**: Additive number theory studies the additive structure of integers, such as sumsets and their properties. Timothy Gowers is a Fields Medalist and professor at Cambridge University. ChatGPT 5.5 Pro is an advanced AI model with enhanced reasoning capabilities. The test highlights AI's growing ability to handle complex mathematical reasoning tasks that were previously thought to require human creativity.

**Tags**: `#AI`, `#数学研究`, `#ChatGPT`, `#学术影响`, `#菲尔兹奖`

---

<a id="item-6"></a>
## [GitLab Lays Off Staff, Replaces CREDIT Values with New Ethos](https://about.gitlab.com/blog/gitlab-act-2/) ⭐️ 8.0/10

GitLab announced a workforce reduction and replaced its long-standing CREDIT values (Collaboration, Results, Efficiency, Diversity, Iteration, Transparency) with three new values: Speed with Quality, Ownership Mindset, and Customer Outcomes, citing the shift to the 'agentic era' as the reason. This move signals a major strategic pivot at a prominent tech company, prioritizing speed and ownership over collaboration and diversity, which could influence how other companies approach corporate culture and AI-driven transformation. The new values drop Diversity, Inclusion & Belonging entirely, and emphasize individual ownership and customer outcomes. GitLab frames this as necessary for the 'agentic era,' where AI agents and automation reshape work.

hackernews · AnonGitLabEmpl · May 11, 20:51 · [Discussion](https://news.ycombinator.com/item?id=48100500)

**Background**: GitLab's CREDIT values were a core part of its culture, especially as a fully remote company. The 'agentic era' refers to a trend where AI agents autonomously perform tasks, reducing the need for human collaboration. GitLab's layoffs and value change reflect a broader industry push toward AI-driven efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://handbook.gitlab.com/handbook/values/">GitLab Values | The GitLab Handbook</a></li>
<li><a href="https://slab.com/blog/short-toes-how-gitlabs-values-shape-company-documentation/">Short Toes: How GitLab's Values Shape... - Knock Down Silos by Slab</a></li>

</ul>
</details>

**Discussion**: Community comments are largely critical, with many seeing the new values as a push to 'work harder, not smarter' and a retreat from DEI. Some question the logic of cutting resources while claiming the 'largest opportunity,' and others express skepticism about GitLab's AI capabilities improving UX.

**Tags**: `#GitLab`, `#layoffs`, `#corporate values`, `#AI`, `#remote work`

---

<a id="item-7"></a>
## [Interfaze: New Model Architecture Claims 100x Accuracy Boost](https://interfaze.ai/blog/interfaze-a-new-model-architecture-built-for-high-accuracy-at-scale) ⭐️ 8.0/10

Interfaze has introduced a task-specific deep neural network architecture that claims up to 100x accuracy improvements for tasks like OCR and GUI detection. This could significantly improve the reliability of AI systems in document processing and user interface automation, potentially enabling more predictable workflows for developers. The architecture produces useful metadata like bounding boxes and confidence scores, and the company is a Y Combinator startup that presented at YC Launch Live in May 2026.

hackernews · yoeven · May 11, 16:22 · [Discussion](https://news.ycombinator.com/item?id=48097078)

**Background**: Traditional deep neural networks often struggle with high accuracy on specialized tasks like OCR when images are distorted or noisy. Task-specific architectures are designed to optimize for a single task, potentially outperforming general-purpose models.

**Discussion**: Community members tested the OCR on a distorted typewritten page and reported positive results. Others asked about chaining models like Unix pipes and whether the architecture could be used for code extraction in coding agents.

**Tags**: `#deep learning`, `#model architecture`, `#OCR`, `#AI accuracy`, `#startup`

---

<a id="item-8"></a>
## [Thinking Machines Unveils Real-Time Multimodal Transformer](https://thinkingmachines.ai/blog/interaction-models/) ⭐️ 8.0/10

Thinking Machines has introduced a transformer-based interaction model that processes and generates text, image, and audio in near real-time using time-aligned micro-turns of 200ms each. This architecture enables fluid, human-like multimodal interactions, potentially transforming applications like virtual assistants, customer service, and real-time collaboration tools. The model interleaves input processing and output generation in 200ms chunks, allowing it to listen and respond simultaneously without waiting for complete utterances.

hackernews · smhx · May 11, 20:53 · [Discussion](https://news.ycombinator.com/item?id=48100524)

**Background**: Traditional multimodal AI models process entire inputs before generating responses, causing latency. The time-aligned micro-turn approach breaks this pattern by continuously interleaving small chunks of input and output, enabling real-time interaction.

**Discussion**: Commenters were impressed by the demos, especially the model's ability to wait naturally during pauses. Some questioned the economic model and scalability, while others wondered about training data and skill retention.

**Tags**: `#AI`, `#multimodal`, `#transformer`, `#real-time`, `#interaction model`

---

<a id="item-9"></a>
## [James Shore: AI coding agents must cut maintenance costs proportionally](https://simonwillison.net/2026/May/11/james-shore/#atom-everything) ⭐️ 8.0/10

James Shore published a blog post arguing that AI coding agents must reduce maintenance costs inversely to productivity gains, otherwise they create unsustainable technical debt. He uses a simple mathematical model to show that doubling code output without halving maintenance costs quadruples total maintenance burden. This insight challenges the common narrative that AI coding agents purely boost productivity, highlighting a hidden cost that could negate long-term gains. It is highly relevant for engineering leaders and teams adopting AI-assisted development, as ignoring maintenance costs may lead to crippling technical debt. Shore's model: if productivity multiplier is P, maintenance cost multiplier must be 1/P to keep total maintenance constant. He warns that current AI coding agents often generate code that is harder to maintain, exacerbating the problem.

rss · Simon Willison · May 11, 19:48

**Background**: Technical debt is a metaphor in software engineering for the implied cost of additional rework caused by choosing an easy solution now instead of a better approach that would take longer. AI coding agents can accelerate code generation, but if the generated code is poorly structured or undocumented, it increases future maintenance effort. Shore's argument applies the classic debt analogy to the AI context, emphasizing that productivity gains must be accompanied by proportional reductions in maintenance overhead.

<details><summary>References</summary>
<ul>
<li><a href="https://www.jamesshore.com/v2/blog/2026/you-need-ai-that-reduces-your-maintenance-costs">James Shore: You Need AI That Reduces Maintenance Costs</a></li>

</ul>
</details>

**Tags**: `#AI-assisted development`, `#software maintenance`, `#technical debt`, `#productivity`

---

<a id="item-10"></a>
## [Zombie Internet: The Mental Toll of AI-Generated Content](https://simonwillison.net/2026/May/11/zombie-internet/#atom-everything) ⭐️ 8.0/10

Jason Koebler published an angry, insightful article titled 'Your AI Use Is Breaking My Brain,' which Simon Willison highlighted, introducing the concept of a 'Zombie Internet' where human and AI interactions are deeply entangled. This article articulates the exhausting mental burden of filtering AI-generated content online, a growing problem that affects everyone's internet experience and raises urgent questions about content quality and authenticity. Koebler distinguishes 'Zombie Internet' from the 'Dead Internet' theory: the former involves people talking to bots, people using AI talking to non-AI users, and AI agents interacting with people, creating a pervasive blurring of human and machine communication.

rss · Simon Willison · May 11, 19:21

**Background**: The 'Dead Internet' theory is a conspiracy theory claiming that since around 2016, most online content and interactions are generated by bots and algorithms, not humans. The 'Zombie Internet' concept updates this for the AI era, describing a more complex reality where AI-generated content and human activity are interwoven, making it mentally taxing to distinguish real from synthetic.

<details><summary>References</summary>
<ul>
<li><a href="https://www.fastcompany.com/91489308/zombie-internet-devastating-consequences-advertising-social-media-human-web-dead-internet-moltbook-ai-tbpn">The ‘zombie internet’ has arrived—and it has consequences</a></li>
<li><a href="https://en.wikipedia.org/wiki/Dead_Internet_theory">Dead Internet theory</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#content quality`, `#internet culture`, `#AI-generated content`, `#Zombie Internet`

---

<a id="item-11"></a>
## [Shopify's River AI Agent Fosters Learning Through Public Slack Channels](https://simonwillison.net/2026/May/11/learning-on-the-shop-floor/#atom-everything) ⭐️ 8.0/10

Shopify CEO Tobias Lütke revealed that their internal coding agent, River, operates entirely in public Slack channels, refusing direct messages to ensure all interactions are visible and searchable across the company. This approach turns AI-assisted coding into a transparent, collaborative learning environment, enabling 'osmosis learning' where employees gain skills by observing others' interactions with the AI. River declines direct messages and directs users to create public channels (e.g., #tobi_river), where over 100 people may follow, react, and contribute. Lütke likens this to a German 'Lehrwerkstatt' (teaching workshop), where the entire shop floor becomes a classroom.

rss · Simon Willison · May 11, 15:46

**Background**: River is Shopify's internal AI coding agent that assists developers with code generation, debugging, and reviews. By making its interactions public, the tool promotes transparency and continuous learning, similar to how Midjourney used public Discord channels to share prompts and foster community learning.

**Discussion**: The community discussion highlights the value of transparency in AI tooling, with many praising the 'Lehrwerkstatt' concept as a model for other organizations. Some note that this approach requires a strong culture of psychological safety to avoid embarrassment from public mistakes.

**Tags**: `#AI-assisted coding`, `#software engineering`, `#learning culture`, `#transparency`, `#Shopify`

---

<a id="item-12"></a>
## [OpenAI Acquires Tomoro, Launches Deployment Company for Enterprise AI](https://36kr.com/newsflashes/3805023424339456?f=rss) ⭐️ 8.0/10

OpenAI has agreed to acquire consulting and engineering firm Tomoro and established a new entity called the OpenAI Deployment Company, backed by TPG, Bain Capital, and SoftBank with an initial investment of over $4 billion. This move signals a strategic shift from providing AI models to delivering end-to-end enterprise solutions, potentially lowering the barrier for businesses to adopt AI and accelerating industry-wide AI penetration. The new entity will be staffed by approximately 150 senior AI deployment experts from Tomoro, and will offer a unified service experience whether clients work with OpenAI, the deployment company, or both. On the same day, Anthropic announced a $1.5 billion partnership with Blackstone and Goldman Sachs for similar enterprise AI deployment.

rss · 36氪 · May 11, 23:42

**Background**: Tomoro was founded in 2023 in alliance with OpenAI, specializing in designing, building, and scaling AI solutions for clients. The OpenAI Deployment Company is a committed partnership between OpenAI and 19 leading global investment firms, consultancies, and system integrators, aiming to solve high-impact problems using AI in real-world environments.

<details><summary>References</summary>
<ul>
<li><a href="https://tomoro.ai/">Tomoro.ai - reinventing better | Tomoro.ai</a></li>
<li><a href="https://www.bloomberg.com/news/articles/2026-05-11/openai-to-buy-consulting-firm-for-private-equity-joint-venture">OpenAI Acquires Tomoro to Boost Private Equity-Backed AI Venture - Bloomberg</a></li>
<li><a href="https://openai.com/index/openai-launches-the-deployment-company/">OpenAI launches the OpenAI Deployment Company to... | OpenAI</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#enterprise AI`, `#acquisition`, `#AI deployment`, `#investment`

---

<a id="item-13"></a>
## [GM Fined $12.75M in California for Selling Driver Data Without Consent](https://www.ithome.com/0/949/018.htm) ⭐️ 8.0/10

General Motors agreed to pay $12.75 million to settle California charges that it sold driver location and behavior data to data brokers without consent. The settlement also bans GM from selling driving data to consumer reporting agencies for five years. This case sets a precedent for holding automakers accountable for privacy violations involving connected vehicle data. It highlights growing regulatory scrutiny on how car companies collect and monetize sensitive driver information. GM collected data through its OnStar system and sold it to LexisNexis Risk Solutions and Verisk Analytics, earning about $20 million nationwide. The settlement requires GM to delete the data and ensure those brokers also delete it.

rss · IT之家 · May 11, 13:53

**Background**: Modern vehicles often collect detailed location and driving behavior data through telematics systems. Automakers have faced backlash for sharing this data with insurers, leading to higher premiums for some drivers. The California Privacy Protection Agency investigated GM after reports that driver data was used to raise insurance rates.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LexisNexis_Risk_Solutions">LexisNexis Risk Solutions</a></li>
<li><a href="https://en.wikipedia.org/wiki/Verisk_Analytics">Verisk Analytics</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#automotive`, `#data regulation`, `#consumer protection`, `#IoT`

---

<a id="item-14"></a>
## [SMIC's $40.6B Acquisition of SMIC North Approved by Shanghai Stock Exchange](https://www.ithome.com/0/949/016.htm) ⭐️ 8.0/10

The Shanghai Stock Exchange has approved SMIC's plan to acquire the remaining 49% stake in SMIC North for 40.6 billion yuan, making it a wholly-owned subsidiary. This is the largest merger and acquisition in China's wafer foundry history. This deal consolidates SMIC's control over its 12-inch wafer production capacity, enhancing operational synergy and asset quality. It signals a strategic push to strengthen China's domestic semiconductor supply chain amid ongoing geopolitical tensions. SMIC will issue shares to five shareholders including the National Integrated Circuit Fund to acquire the 49% stake at a price of 40.601 billion yuan. After the transaction, SMIC's main business scope will remain unchanged.

rss · IT之家 · May 11, 13:48

**Background**: SMIC North is a subsidiary of SMIC that provides 12-inch wafer foundry services using various process platforms. SMIC already held a 51% stake before this acquisition. The deal is part of SMIC's broader strategy to integrate its manufacturing assets and improve efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://news.qq.com/rain/a/20260511A07YLO00?adChannelId=finance">中芯国际406亿元吞下中芯北方，科创板史上最大重组案来了_腾讯新闻</a></li>
<li><a href="https://finance.sina.com.cn/wm/2026-05-11/doc-inhxptqz1777461.shtml">中芯国际406亿元吞下中芯北方，科创板史上最大重组案来了</a></li>
<li><a href="https://www.chinatimes.com/newspapers/20260512000239-260203">中芯國際買回中芯北方股權 - 全球財經 - 工商時報 | 中時新聞網</a></li>

</ul>
</details>

**Tags**: `#semiconductor`, `#M&A`, `#SMIC`, `#China`, `#wafer foundry`

---

<a id="item-15"></a>
## [Linux Enters AI Patch Era: Larger Code Volumes Become New Normal](https://news.mydrivers.com/1/1121/1121466.htm) ⭐️ 8.0/10

Linus Torvalds released Linux 7.1-rc3 and noted that code patch sizes are unusually large, attributing this to the use of AI tools in development workflows. He stated that this is not a temporary fluctuation but a new normal for kernel development. This marks a significant shift in open-source development practices, as AI tools are now driving higher code output and larger patch volumes. It affects the entire Linux kernel community, including maintainers and contributors, who must adapt to this new reality. The update cycle saw network module patches accounting for one-third of all changes, along with fixes for use-after-free vulnerabilities in Bluetooth and graphics drivers. The release also adds support for Apple Mac USB-C networking and LoongArch KVM virtualization optimizations.

rss · 快科技 · May 11, 17:07

**Background**: The Linux kernel is the core of the Linux operating system, maintained by a global community led by Linus Torvalds. AI-assisted coding tools, such as large language models (LLMs), can generate code faster, leading to larger patch submissions. The kernel community has recently established policies requiring disclosure of AI-generated code to ensure accountability.

<details><summary>References</summary>
<ul>
<li><a href="https://www.zdnet.com/article/linus-torvalds-and-maintainers-finalize-ai-policy-for-linux-kernel-developers/">The new rules for AI-assisted code in the Linux kernel... | ZDNET</a></li>
<li><a href="https://www.phoronix.com/news/LoongArch-Linux-KVM">LoongArch Linux Patches Enable KVM Virtualization - Phoronix</a></li>
<li><a href="https://www.memorysafety.org/blog/linux-kernel-2025-update/">An Update on Memory Safety in the Linux Kernel - Prossimo</a></li>

</ul>
</details>

**Tags**: `#Linux`, `#AI`, `#kernel development`, `#open source`, `#software engineering`

---

<a id="item-16"></a>
## [Fake Codex site tops Google search, distributes malware](https://www.v2ex.com/t/1212003#reply29) ⭐️ 8.0/10

A developer discovered that the top Google result for 'Codex' leads to a fake website that mimics the official ChatGPT interface and distributes malware via a base64-obfuscated curl command. The malicious script downloads and executes a payload from a remote server. This attack targets developers searching for AI coding tools, exploiting trust in search results to deliver malware. It highlights the growing risk of SEO poisoning in the AI tool ecosystem, where fake sites can bypass user vigilance. The fake site's installation command uses `echo` to display a benign-looking URL but actually executes a base64-decoded curl command piped to zsh. The base64 string decodes to a URL on greenactiv.com, which downloads and runs a malicious script.

rss · V2EX · May 11, 14:55

**Background**: Base64 encoding is a common obfuscation technique used by malware authors to hide malicious payloads in plain sight. Attackers often use SEO poisoning to push fake websites to the top of search results, tricking users into downloading malware. Developers searching for tools like Codex are prime targets because they often run commands from the web.

<details><summary>References</summary>
<ul>
<li><a href="https://www.infosecinstitute.com/resources/malware-analysis/using-base64-for-malware-obfuscation/">Using Base64 for malware obfuscation | Infosec</a></li>
<li><a href="https://www.opswat.com/blog/how-base64-encoding-opens-the-door-for-malware">How Base64 Encoding Opens the Door for Malware - OPSWAT</a></li>

</ul>
</details>

**Discussion**: The V2EX thread has 29 replies, with many users sharing similar experiences and warning others. Some commenters analyze the obfuscation technique, while others suggest using ad blockers or verifying URLs before running commands.

**Tags**: `#security`, `#malware`, `#AI tools`, `#phishing`, `#developer warning`

---

<a id="item-17"></a>
## [Bun Confirms Migration from Zig to Rust](https://www.v2ex.com/t/1211992#reply18) ⭐️ 8.0/10

Bun founder Jarred Sumner confirmed that the next version may be the last in Zig, as a Rust rewrite that passes all test suites and fixes ~200 issues is being considered for merge. This migration could significantly improve Bun's stability and crash prevention, impacting the JavaScript runtime ecosystem by potentially making Bun more reliable for production use. The Rust rewrite uses no async Rust and very few third-party libraries, mirroring the Zig codebase structure. Sumner noted no benchmark shows it slower than the Zig version.

rss · V2EX · May 11, 13:21

**Background**: Bun is a high-performance JavaScript runtime written in Zig, designed as a drop-in replacement for Node.js. Zig is a systems programming language focused on simplicity and performance, while Rust offers stronger memory safety guarantees and better tooling for preventing crashes.

<details><summary>References</summary>
<ul>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/bun: Incredibly fast JavaScript runtime ...Bun Guide: Install, Configure & Deploy the Fast JS Runtime ...How to Install Bun - commandlinux.comWhat Is Bun JS? Ultra-Fast JavaScript Runtime Explained (2025 ...Bun 2026: How the Anthropic Acquisition Reshapes the ...</a></li>

</ul>
</details>

**Discussion**: The V2EX discussion largely supports the migration, with users praising Rust's tooling and safety. Some express concern about losing Zig's simplicity, but most see the trade-off as worthwhile for stability.

**Tags**: `#Bun`, `#Rust`, `#Zig`, `#JavaScript Runtime`, `#Migration`

---

<a id="item-18"></a>
## [Figure AI Shows Two Robots Collaborating to Make a Bed](http://www.geekpark.net/news/363963) ⭐️ 8.0/10

Figure AI released a new demo on May 8, 2025, showing two Helix-02 humanoid robots collaboratively tidying a bedroom, including making a bed, using a single neural network for multi-robot locomanipulation for the first time globally. This demo marks a breakthrough in multi-robot collaboration without central control or explicit communication, relying solely on visual observation and a shared neural network, which could significantly advance household robotics and human-robot interaction. Each robot runs the model independently, deciding its own actions by observing the other's movements. The demo includes handling flexible objects like a blanket, a notoriously difficult task in robotics.

rss · 极客公园 · May 11, 02:58

**Background**: Locomanipulation combines locomotion and manipulation, enabling robots to move and interact with objects simultaneously. Figure AI is a leading humanoid robotics company; its Helix system uses a Vision-Language-Action (VLA) model to control robots without extensive manual training.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Figure_AI">Figure AI - Wikipedia</a></li>
<li><a href="https://www.theresarobotforthat.com/figures-humanoids-read-each-others-minds-making-beds/">Humanoid Collaboration | Figure's Mind-Reading Robots</a></li>
<li><a href="https://www.maginative.com/article/meet-helix-the-ai-behind-figures-humanoid-robots-that-reason-like-humans/">Meet Helix: The AI Behind Figure’s Humanoid Robots That Reason Like Humans</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#AI`, `#multi-robot systems`, `#neural networks`, `#locomanipulation`

---