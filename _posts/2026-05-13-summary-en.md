---
layout: default
title: "Daily News 2026-05-13"
date: 2026-05-13
lang: en
---

> From 287 items, 18 important content pieces were selected

---

1. [CERT Releases Six Critical CVEs for dnsmasq](#item-1) ⭐️ 9.0/10
2. [Bambu Lab Accused of Violating Open Source Social Contract](#item-2) ⭐️ 9.0/10
3. [CVE-2026-45185: Critical Unauthenticated RCE in Exim MTA](#item-3) ⭐️ 9.0/10
4. [Needle: 26M Parameter Tool-Calling Model Distilled from Gemini](#item-4) ⭐️ 8.0/10
5. [DuckDB Announces Quack: Client-Server Protocol for Scaling](#item-5) ⭐️ 8.0/10
6. [Obsidian Unveils New Plugin Review System and Community Site](#item-6) ⭐️ 8.0/10
7. [Canada's Bill C-22 Revives Surveillance Threats with Data Retention and Backdoors](#item-7) ⭐️ 8.0/10
8. [Google and SpaceX Partner on Orbital Data Centers, Prototype by 2027](#item-8) ⭐️ 8.0/10
9. [China Telecom Sets World Record with 40Tbps Quantum-Classic Co-Transmission over Hollow-Core Fiber](#item-9) ⭐️ 8.0/10
10. [Google Gemini Intelligence to Automate Tasks on Android This Summer](#item-10) ⭐️ 8.0/10
11. [Malicious Hugging Face clone of OpenAI Privacy Filter infects 200k+](#item-11) ⭐️ 8.0/10
12. [Lunar Soil Fiber Samples Sent to China Space Station for Testing](#item-12) ⭐️ 8.0/10
13. [iOS 27 Overhauls Siri with Standalone App, AI Chat, Third-Party Models](#item-13) ⭐️ 8.0/10
14. [Google and Apple Partner for Cross-Platform File Sharing and eSIM Transfer](#item-14) ⭐️ 8.0/10
15. [Google Report: Hackers Use AI to Find Zero-Day Flaws](#item-15) ⭐️ 8.0/10
16. [Xiaomi to Launch Product with Self-Developed Chip, OS, and AI Model in H2 2025](#item-16) ⭐️ 8.0/10
17. [China sends artificial embryos into space for first time](#item-17) ⭐️ 8.0/10
18. [OpenAI's Former CTO Unveils 'Most Human' AI Interaction Model](#item-18) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [CERT Releases Six Critical CVEs for dnsmasq](https://lists.thekelleys.org.uk/pipermail/dnsmasq-discuss/2026q2/018471.html) ⭐️ 9.0/10

CERT has released six Common Vulnerabilities and Exposures (CVEs) for serious security vulnerabilities in dnsmasq, a widely-used DNS/DHCP server. The vulnerabilities affect versions prior to the latest release and could allow remote code execution or denial of service. dnsmasq is embedded in countless routers, IoT devices, and Linux distributions, so these vulnerabilities have a massive potential attack surface. This event reignites the debate on adopting memory-safe languages like Rust or Go to replace C-based network services. The six CVEs cover multiple memory safety issues including buffer overflows and use-after-free bugs. Patches have been released upstream, but distributions like Debian stable and OpenWRT may be slow to update, leaving users exposed.

hackernews · chizhik-pyzhik · May 12, 18:12 · [Discussion](https://news.ycombinator.com/item?id=48112042)

**Background**: dnsmasq is a lightweight DNS forwarder, DHCP server, and TFTP server commonly used in home routers and embedded systems. It is written in C, a memory-unsafe language, making it prone to memory corruption vulnerabilities. CVE (Common Vulnerabilities and Exposures) is a standardized system for identifying and cataloging security flaws.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dnsmasq">Dnsmasq</a></li>
<li><a href="https://en.wikipedia.org/wiki/Common_Vulnerabilities_and_Exposures">Common Vulnerabilities and Exposures - Wikipedia</a></li>
<li><a href="https://www.memorysafety.org/docs/memory-safety/">What is memory safety and why does it matter? - Prossimo</a></li>

</ul>
</details>

**Discussion**: Commenters are split: some argue this is a tipping point for migrating to memory-safe languages like Rust or Go, while others criticize Debian's slow patching practices. A user also promotes their own audited DNS server MaraDNS as a safer alternative.

**Tags**: `#security`, `#dnsmasq`, `#CVE`, `#memory safety`, `#open source`

---

<a id="item-2"></a>
## [Bambu Lab Accused of Violating Open Source Social Contract](https://www.jeffgeerling.com/blog/2026/bambu-lab-abusing-open-source-social-contract/) ⭐️ 9.0/10

Bambu Lab is restricting LAN mode on its 3D printers, requiring authorization even for local-only operation, and using weak security justifications that critics say violate the open source social contract. This controversy undermines trust in closed ecosystems and highlights tensions between open source communities and hardware companies that build on open source software but impose restrictive policies. Bambu Lab's LAN mode change forces users to authenticate even when not using the cloud, and the company cited unauthorized traffic spikes as a reason, but critics note that blocking based on user-agent strings is not a real security measure.

hackernews · rubenbe · May 12, 14:54 · [Discussion](https://news.ycombinator.com/item?id=48109224)

**Background**: The open source social contract refers to the expectation that open source software remains free and unrestricted, even when used in commercial products. Bambu Lab's firmware is based on open source projects like Marlin and Klipper, but the company has gradually locked down features, angering the community.

<details><summary>References</summary>
<ul>
<li><a href="https://www.jeffgeerling.com/blog/2026/bambu-lab-abusing-open-source-social-contract/">Bambu Lab is abusing the open source social contract</a></li>
<li><a href="https://wiki.bambulab.com/en/knowledge-sharing/enable-lan-mode">How to enable LAN Mode on Bambu Lab printers | Bambu Lab Wiki</a></li>
<li><a href="https://consumerrights.wiki/w/Wiki/Bambu_Lab_Authorization_Control_System">Bambu Lab Authorization Control System - Consumer Rights Wiki</a></li>

</ul>
</details>

**Discussion**: Commenters express outrage, with many noting that LAN mode was only added after previous backlash. Some argue that Bambu Lab's security excuse is flimsy, while others point to broader concerns about Chinese servers and potential espionage, though these claims are speculative.

**Tags**: `#open source`, `#3D printing`, `#community trust`, `#corporate ethics`, `#Bambu Lab`

---

<a id="item-3"></a>
## [CVE-2026-45185: Critical Unauthenticated RCE in Exim MTA](https://xbow.com/blog/dead-letter-cve-2026-45185-xbow-found-rce-exim) ⭐️ 9.0/10

XBOW disclosed CVE-2026-45185, an unauthenticated remote code execution vulnerability in Exim before version 4.99.3, affecting GnuTLS configurations via a use-after-free in BDAT body parsing. Coordinated distro releases were issued on May 12, 2026. Exim is a widely deployed mail transfer agent on Unix-like systems, making this critical RCE a significant threat to millions of servers. The vulnerability allows unauthenticated attackers to execute arbitrary code remotely, potentially leading to full server compromise. The vulnerability is a use-after-free in the BDAT body parsing path, reachable remotely without authentication, and affects Exim versions prior to 4.99.3 when using GnuTLS. The CVSS score is not yet published but is expected to be critical.

hackernews · fedek_ · May 12, 17:52 · [Discussion](https://news.ycombinator.com/item?id=48111748)

**Background**: Exim is a free, open-source mail transfer agent (MTA) used on Unix-like operating systems to route and deliver email. It has a history of critical vulnerabilities, including CVE-2023-42115 and others from 2019-2020. XBOW is a security research firm that focuses on vulnerability discovery and disclosure.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Exim">Exim - Wikipedia</a></li>
<li><a href="https://www.thehackerwire.com/vulnerability/CVE-2026-45185/">CVE-2026-45185 - Info Vulnerability - TheHackerWire</a></li>

</ul>
</details>

**Discussion**: Community members criticized the disclosure timeline, noting that distros received only 2-4 days of advance notice before public release, with no embargo period after coordinated release. Some expressed frustration over the lack of transparency and compared it to past Exim vulnerabilities.

**Tags**: `#CVE`, `#Exim`, `#RCE`, `#security`, `#MTA`

---

<a id="item-4"></a>
## [Needle: 26M Parameter Tool-Calling Model Distilled from Gemini](https://github.com/cactus-compute/needle) ⭐️ 8.0/10

Cactus Compute open-sourced Needle, a 26M parameter function-calling model distilled from Gemini, achieving 6000 tok/s prefill and 1200 tok/s decode on consumer devices. The model uses only attention and gating layers with no MLPs, and was pretrained on 200B tokens then post-trained on 2B tokens of synthesized function-calling data. Needle demonstrates that tool calling can be efficiently handled by a tiny model, enabling on-device agentic AI on phones, watches, and glasses. Its architecture challenges the assumption that large feed-forward networks are necessary, potentially reducing cost and latency for agentic applications. The model beats FunctionGemma-270M, Qwen-0.6B, Granite-350M, and LFM2.5-350M on single-shot function calling, but those models have broader conversational capabilities. Needle is MIT licensed, weights are on Hugging Face, and the full architecture writeup is available on GitHub.

hackernews · HenryNdubuaku · May 12, 18:03 · [Discussion](https://news.ycombinator.com/item?id=48111896)

**Background**: Knowledge distillation transfers knowledge from a large model to a smaller one, enabling deployment on less powerful hardware. Function calling allows models to request data or actions from external systems. Cross-attention captures relationships between two different input sequences, making it suitable for retrieval-and-assembly tasks like tool calling.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Distillation_(machine_learning)">Distillation (machine learning)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Attention_(machine_learning)">Attention (machine learning) - Wikipedia</a></li>
<li><a href="https://docs.oracle.com/en-us/iaas/Content/generative-ai/function.htm">Function Calling</a></li>

</ul>
</details>

**Discussion**: Commenters expressed interest in browser compatibility (ONNX conversion), command-line natural language argument parsing, and live demos. Some praised the push for tiny models and discussed using multiple small agents in orchestration. A minor naming suggestion was to use '0.026B' instead of '26M' for clarity.

**Tags**: `#tool calling`, `#small language models`, `#on-device AI`, `#distillation`, `#function calling`

---

<a id="item-5"></a>
## [DuckDB Announces Quack: Client-Server Protocol for Scaling](https://duckdb.org/2026/05/12/quack-remote-protocol) ⭐️ 8.0/10

DuckDB has announced Quack, a new client-server protocol that enables remote query execution and horizontal scaling, allowing multiple users to query the same DuckDB instance over a network. This expands DuckDB's use cases beyond embedded analytics to multi-user, server-based deployments, making it a viable option for small-to-medium analytical workloads that need concurrency and scaling. Quack uses a custom wire protocol optimized for analytical queries, and it supports features like streaming results, prepared statements, and authentication. It is designed to work with DuckDB's existing ecosystem, including tools that use the DuckDB driver.

hackernews · aduffy · May 12, 17:54 · [Discussion](https://news.ycombinator.com/item?id=48111765)

**Background**: DuckDB is an embedded analytical database that traditionally runs inside the host process, limiting it to single-user scenarios. Quack introduces a separate server process that can handle multiple client connections, enabling horizontal scaling by adding more server nodes. This is similar to how SQLite can be extended with server layers, but Quack is natively built into DuckDB.

<details><summary>References</summary>
<ul>
<li><a href="https://motherduck.com/duckdb-book-summary-chapter7/">DuckDB in Action - Chapter 7 - DuckDB in the Cloud with</a></li>
<li><a href="https://motherduck.com/blog/scaling-duckdb-with-ducklings/">MotherDuck’s approach to scaling DuckDB</a></li>
<li><a href="https://medium.com/@tanejagagan/scaling-duckdb-a-modern-architecture-for-analytical-data-applications-49e5a8dcd24a">Scaling DuckDB: A Modern Architecture for Analytical Data Applications | by Gagan Taneja | Medium</a></li>

</ul>
</details>

**Discussion**: The community is excited about Quack, with users praising it for solving the horizontal scaling problem for internal apps and homelab use. Some users are exploring practical applications like setting up self-replicating wrappers over SSH, while others question whether DuckDB with Quack is suitable for multi-user read-write scenarios compared to alternatives like SQLite.

**Tags**: `#DuckDB`, `#database`, `#client-server`, `#protocol`, `#scalability`

---

<a id="item-6"></a>
## [Obsidian Unveils New Plugin Review System and Community Site](https://obsidian.md/blog/future-of-plugins/) ⭐️ 8.0/10

Obsidian has announced a new community site and an automated review system for plugins, replacing the previous manual review process that had become a bottleneck. The system scans every version for security and code quality, not just initial submissions. This addresses a critical scaling bottleneck for Obsidian's plugin ecosystem, relieving developer frustration and team burnout. It ensures the platform can continue to grow securely without limiting plugin availability. The automated review system checks every plugin version for security and code quality, not just the initial submission. The new community site provides a centralized hub for discovering and discussing plugins.

hackernews · xz18r · May 12, 15:45 · [Discussion](https://news.ycombinator.com/item?id=48109970)

**Background**: Obsidian is a popular note-taking app that supports community-developed plugins via an open API. Previously, all plugin submissions were manually reviewed by a small team, which became unsustainable as the number of plugins grew rapidly, especially with AI-assisted development.

<details><summary>References</summary>
<ul>
<li><a href="https://obsidian.md/blog/future-of-plugins/">The future of Obsidian plugins - Obsidian</a></li>
<li><a href="https://obsidian.md/plugins">Plugins - Obsidian</a></li>
<li><a href="https://obsidian.md/help/community-plugins">Learn how to extend Obsidian with plugins built by the community.</a></li>

</ul>
</details>

**Discussion**: The community largely welcomed the change, with users noting it relieves a major bottleneck. Some expressed concerns about automated checks reliably detecting malicious plugins, suggesting proper sandboxing and permission systems instead.

**Tags**: `#Obsidian`, `#plugins`, `#developer tools`, `#community`, `#security`

---

<a id="item-7"></a>
## [Canada's Bill C-22 Revives Surveillance Threats with Data Retention and Backdoors](https://www.eff.org/deeplinks/2026/05/canadas-bill-c-22-repackaged-version-last-years-surveillance-nightmare) ⭐️ 8.0/10

Canada's Bill C-22, a repackaged version of last year's failed surveillance bill, would mandate data retention and encryption backdoors, threatening services like Signal and WhatsApp. The Electronic Frontier Foundation (EFF) warns that the bill could force encrypted messaging apps to block Canadian users or compromise their security. If passed, Bill C-22 would set a dangerous precedent for government surveillance, potentially undermining end-to-end encryption globally. It could force major tech companies to either violate Canadian law or degrade security for all users, impacting privacy rights and digital trust. The bill includes mandatory data retention requirements for internet service providers and a provision that would compel companies to decrypt communications upon request, effectively creating an encryption backdoor. Critics argue this would make all users vulnerable to hackers and abuse, as backdoors cannot be limited to 'good guys' only.

hackernews · Brajeshwar · May 12, 17:35 · [Discussion](https://news.ycombinator.com/item?id=48111531)

**Background**: Bill C-22 is the latest attempt by the Canadian government to expand surveillance powers, following the failure of similar legislation (Bill C-2) last year. Data retention mandates require companies to store user data for a set period, while encryption backdoors are methods to bypass encryption, often demanded by law enforcement. Civil liberties groups like the EFF and the Canadian Civil Liberties Association have consistently opposed such measures, arguing they violate privacy and security.

<details><summary>References</summary>
<ul>
<li><a href="https://www.jccf.ca/national-post-liberals-have-canada-leading-the-west-in-state-surveillance/">National Post: Liberals have Canada leading the West in state...</a></li>
<li><a href="https://www.eff.org/issues/mandatory-data-retention">Mandatory Data Retention | Electronic Frontier Foundation</a></li>
<li><a href="https://www.internetsociety.org/blog/2025/05/what-is-an-encryption-backdoor/">What Is an Encryption Backdoor? - Internet Society</a></li>

</ul>
</details>

**Discussion**: Commenters expressed strong opposition, with one noting that mandatory data retention and backdoors would force encrypted services to block Canadians. Another commenter sarcastically welcomed the bill as a 'wake-up call' that could drive innovation in censorship-circumvention tools. Some urged readers to contact their MPs and the Minister of Public Safety to reject the legislation.

**Tags**: `#surveillance`, `#encryption`, `#privacy`, `#Canada`, `#legislation`

---

<a id="item-8"></a>
## [Google and SpaceX Partner on Orbital Data Centers, Prototype by 2027](https://www.ithome.com/0/949/562.htm) ⭐️ 8.0/10

Google and SpaceX are in talks to launch orbital data centers under Google's Project Suncatcher, with a prototype satellite planned for 2027. SpaceX has also filed with regulators to launch up to 1 million satellites for its own orbital data center vision. Orbital data centers could bypass land and energy constraints of ground-based facilities, using solar power in space to run AI workloads. This collaboration between two tech giants could accelerate a paradigm shift in cloud computing infrastructure. Google's Project Suncatcher involves solar-powered satellites equipped with Tensor Processing Units (TPUs) for AI computing. SpaceX, which holds a 6.1% stake from Google, has acquired xAI and is preparing for a major IPO.

rss · IT之家 · May 12, 23:41

**Background**: Data centers consume massive amounts of electricity and land, driving interest in space-based alternatives. Orbital data centers would use solar panels for power and radiate heat in vacuum, potentially offering unlimited clean energy. SpaceX's Starlink already provides satellite internet, and similar technology could support orbital computing.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/research/google-project-suncatcher/">Project Suncatcher explores powering AI in space - The Keyword</a></li>
<li><a href="https://money.usnews.com/investing/news/articles/2026-05-12/google-spacex-in-talks-to-explore-data-centers-in-orbit-wsj-reports">Google in Talks With SpaceX for Suncatcher Orbital Data ...</a></li>
<li><a href="https://www.satellitetoday.com/connectivity/2026/02/02/spacex-acquires-xai-to-pursue-orbital-data-center-constellation/">SpaceX Acquires xAI to Pursue Orbital Data Center Constellation</a></li>

</ul>
</details>

**Tags**: `#cloud computing`, `#space technology`, `#data centers`, `#Google`, `#SpaceX`

---

<a id="item-9"></a>
## [China Telecom Sets World Record with 40Tbps Quantum-Classic Co-Transmission over Hollow-Core Fiber](https://www.ithome.com/0/949/561.htm) ⭐️ 8.0/10

China Telecom Research Institute, in collaboration with QuantumCTek, Yangtze Optical Fibre, ZTE, and Beijing University of Posts and Telecommunications, achieved a world record by stably co-transmitting 40 Tbps (50×800 Gbps) classical optical communication and a commercial quantum key distribution (QKD) system over 100 km of hollow-core fiber, with a secure key rate of 9.56 kbps. This breakthrough solves the long-standing noise suppression challenge in co-transmitting high-capacity classical signals and quantum signals over the same fiber, paving the way for cost-effective, scalable deployment of quantum-safe communication networks integrated with existing optical infrastructure. The team pioneered a joint optimization scheme for hollow-core fiber that, for the first time, incorporates classical channel transmission characteristics into the optimization framework, precisely allocating wavelengths and transmit powers to suppress nonlinear noise. The results were published in the top optics journal Photonics Research (SCI Q1, IF:7.2).

rss · IT之家 · May 12, 23:38

**Background**: Quantum key distribution (QKD) provides theoretically unbreakable encryption by using quantum states to share cryptographic keys. However, QKD signals are extremely weak and easily overwhelmed by the high-power classical data signals in standard optical fibers, requiring dedicated fibers or complex noise mitigation. Hollow-core fiber, which guides light through air rather than glass, offers lower latency and reduced nonlinear effects, making it a promising medium for co-transmission. Previous demonstrations over hollow-core fiber achieved only short distances (e.g., 20 km) or lower capacities.

<details><summary>References</summary>
<ul>
<li><a href="https://www.mdpi.com/1099-4300/26/7/601">Enhanced Coexistence of Quantum Key Distribution and Classical Communication over Hollow-Core and Multi-Core Fibers</a></li>
<li><a href="https://opg.optica.org/abstract.cfm?uri=cleo_fs-2025-JPS200_55">Experimental Coexistence of Quantum Key Distribution and Classical Communications over 20 km Hollow-core Fiber</a></li>
<li><a href="https://www.zdnet.com/article/quantum-cryptography-this-air-filled-fiber-optic-cable-can-transport-un-hackable-keys-say-researchers/">Quantum cryptography: This air-filled fiber optic cable can transport un-hackable keys, say researchers | ZDNET</a></li>

</ul>
</details>

**Tags**: `#quantum key distribution`, `#optical fiber`, `#quantum communication`, `#telecommunications`, `#breakthrough`

---

<a id="item-10"></a>
## [Google Gemini Intelligence to Automate Tasks on Android This Summer](https://www.ithome.com/0/949/544.htm) ⭐️ 8.0/10

Google announced Gemini Intelligence, a new AI system for Android that automates multi-step tasks across apps and the web, including complex form filling, widget creation via natural language, and voice polishing in Gboard. The rollout begins this summer on Pixel 10 and Samsung Galaxy S26 devices. Gemini Intelligence marks a shift from passive voice assistants to proactive task automation, potentially transforming how users interact with their Android devices. It could significantly reduce manual effort for common workflows like booking services or shopping, and sets a new standard for AI integration in mobile operating systems. The system uses a hybrid on-device/cloud approach, with Gemini Nano handling simple requests locally. All automated actions require explicit user permission and final confirmation, and the feature is initially experimental. Chrome integration for web automation begins in June 2026.

rss · IT之家 · May 12, 17:45

**Background**: Gemini Intelligence is part of Android 17 (codenamed Cinnamon Bun), the next major Android release. It builds on Google's Gemini AI model family, which includes the lightweight Gemini Nano for on-device processing. The system aims to evolve Gemini from a chatbot into an active Android assistant that understands user context and can execute tasks across apps and websites.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gemini_Intelligence">Gemini Intelligence</a></li>
<li><a href="https://techcrunch.com/2026/05/12/googles-create-my-widget-feature-will-let-you-vibe-code-your-own-widgets/">Google's 'Create My Widget' feature will let you vibe code your own widgets | TechCrunch</a></li>

</ul>
</details>

**Tags**: `#Google`, `#Android`, `#AI`, `#Gemini`, `#automation`

---

<a id="item-11"></a>
## [Malicious Hugging Face clone of OpenAI Privacy Filter infects 200k+](https://www.ithome.com/0/949/518.htm) ⭐️ 8.0/10

A malicious repository named 'Open-OSS/privacy-filter' on Hugging Face impersonated OpenAI's Privacy Filter model, achieving over 200,000 downloads before takedown. The repository contained an information-stealing trojan (Infostealer) disguised as the legitimate model. This incident highlights a critical supply chain risk in the AI/ML ecosystem, where malicious actors can easily impersonate popular models to distribute malware. With over 200,000 downloads, a large number of developers and organizations may have been compromised. The malicious repository's file structure closely matched the official OpenAI Privacy Filter, making it difficult to detect. HiddenLayer, the security firm that discovered it, recommends affected users rebuild their development environments entirely rather than attempting manual cleanup.

rss · IT之家 · May 12, 14:03

**Background**: OpenAI's Privacy Filter is a small model for detecting and masking personally identifiable information (PII) in text, released in April 2026. Hugging Face is a popular platform for hosting AI models, but its open nature makes it a target for supply chain attacks. Infostealer malware is designed to steal credentials, session tokens, and other sensitive data from infected systems.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-openai-privacy-filter/">Introducing OpenAI Privacy Filter | OpenAI</a></li>
<li><a href="https://huggingface.co/openai/privacy-filter">openai/privacy-filter · Hugging Face</a></li>
<li><a href="https://www.breachsense.com/blog/infostealer-malware/">Infostealer Malware: How It Works & How to Detect It</a></li>

</ul>
</details>

**Tags**: `#security`, `#supply chain attack`, `#Hugging Face`, `#malware`, `#AI`

---

<a id="item-12"></a>
## [Lunar Soil Fiber Samples Sent to China Space Station for Testing](https://www.ithome.com/0/949/492.htm) ⭐️ 8.0/10

Lunar soil fiber samples, produced from real Chang'e-5 lunar soil, have been sent to China's space station via the Tianzhou cargo spacecraft for long-term exposure testing on an external platform. This marks a significant step toward in-situ resource utilization on the Moon, potentially reducing the cost of future lunar base construction by using local materials instead of transporting them from Earth. The fiber, about 3 meters long and as thin as a human hair, was produced using a custom-built spinning device that simulates the lunar environment, using only 0.5 grams of real lunar soil.

rss · IT之家 · May 12, 12:08

**Background**: In-situ resource utilization (ISRU) is a key strategy for sustainable space exploration, aiming to use local materials like lunar soil for construction and manufacturing. Traditional spinning equipment fails in the Moon's high-vacuum and microgravity conditions, so the team spent a decade developing a specialized device. The Chang'e-5 mission in 2020 provided the first real lunar soil samples in decades, enabling this breakthrough.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ithome.com/0/949/492.htm">月壤纤维样品进入中国空间站，将接受舱外环境长期验证 - IT之家</a></li>
<li><a href="https://www.chinanews.com.cn/gn/2026/05-12/10619941.shtml">东华大学突破月壤成纤关键技术 首件模拟样品进入空间站验证-中新网</a></li>
<li><a href="https://www.donews.com/news/detail/8/6552740.html">月壤纤维样品随天舟飞船入驻中国空间站开展舱外实验- DoNews快讯</a></li>

</ul>
</details>

**Tags**: `#lunar exploration`, `#materials science`, `#in-situ resource utilization`, `#space technology`, `#fiber manufacturing`

---

<a id="item-13"></a>
## [iOS 27 Overhauls Siri with Standalone App, AI Chat, Third-Party Models](https://news.mydrivers.com/1/1121/1121840.htm) ⭐️ 8.0/10

Apple is introducing a standalone Siri app in iOS 27, transforming the voice assistant into an AI agent with continuous conversation, multimodal input, and system-wide search. The update also allows users to set third-party AI models like ChatGPT or Gemini as the default. This marks Apple's most significant Siri upgrade ever, directly competing with ChatGPT and other mainstream AI assistants. It signals Apple's strategic push into AI, potentially reshaping the iOS ecosystem and user expectations for on-device AI. The Siri app integrates with the Dynamic Island, showing capsule animations and card-based results, and supports natural language editing in apps like Image Playground. However, the new Siri will not be available for users in mainland China.

rss · 快科技 · May 13, 07:23

**Background**: Siri has long been criticized for limited capabilities compared to AI chatbots like ChatGPT. iOS 27 aims to close that gap by giving Siri its own app, persistent conversation history, and the ability to leverage third-party AI models. The Dynamic Island, introduced with iPhone 14 Pro, is a hardware-software feature that displays notifications and interactions around the front camera cutout.

<details><summary>References</summary>
<ul>
<li><a href="https://classiccorvettes.org/article/ios-27-siri-s-big-comeback-what-to-expect">iOS 27: Siri's Big Comeback - What to Expect (2026)</a></li>
<li><a href="https://acoh2023.org/article/ios-27-siri-app-apple-s-new-ai-assistant-unveiled">iOS 27 Siri App: Apple's New AI Assistant Unveiled (2026)</a></li>
<li><a href="https://www.ign.com.cn/tech/40584/video/iphone-14-proling-dong-dao-dynamic-island-zhan-shi-shi-pin">IPhone 14 Pro「灵动岛（ Dynamic Island）」展示视频 | IGN中国</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#iOS`, `#Siri`, `#AI`, `#ChatGPT`

---

<a id="item-14"></a>
## [Google and Apple Partner for Cross-Platform File Sharing and eSIM Transfer](https://news.mydrivers.com/1/1121/1121834.htm) ⭐️ 8.0/10

Google announced a partnership with Apple to enable direct file sharing between Android and iPhone via Quick Share and AirDrop, and to simplify cross-platform data migration including eSIM transfer, with rollout starting in 2026. This collaboration breaks down major ecosystem barriers, allowing seamless interoperability between Android and iOS devices for the first time, significantly improving user experience and reducing switching costs. Quick Share will expand to Samsung, OPPO, OnePlus, vivo, Xiaomi, Honor and other brands by 2026, with a QR code fallback for incompatible devices rolling out within a month. The data migration supports contacts, photos, videos, messages, apps, passwords, home screen layout, and eSIM transfer wirelessly.

rss · 快科技 · May 13, 06:38

**Background**: Quick Share is Android's built-in file sharing feature, similar to Apple's AirDrop. eSIM is a digital SIM that allows users to activate a cellular plan without a physical SIM card. The European Union's Digital Markets Act (DMA) has pushed for greater interoperability between major platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://www.android.com/intl/en_uk/better-together/quick-share-app/">The new Quick Share app for Windows | Android</a></li>
<li><a href="https://support.google.com/android/answer/9286773?hl=en">Use Quick Share on your Android device - Android Help</a></li>

</ul>
</details>

**Tags**: `#Google`, `#Apple`, `#interoperability`, `#file sharing`, `#eSIM`

---

<a id="item-15"></a>
## [Google Report: Hackers Use AI to Find Zero-Day Flaws](https://news.mydrivers.com/1/1121/1121828.htm) ⭐️ 8.0/10

Google's threat intelligence team released a report detailing how a hacker group used AI tools to discover real zero-day vulnerabilities and bypass 2FA authentication. The attack was thwarted by Google's timely intervention. This marks the first known instance of AI being used in the wild for malicious zero-day discovery, lowering the barrier for attackers. It underscores the urgent need for faster patching and proactive defense. The leaked Python script for bypassing 2FA contained detailed comments and fake CVSS scores, which Google identified as AI-generated. The report emphasizes that AI's improving reasoning capabilities enhance vulnerability discovery.

rss · 快科技 · May 13, 00:28

**Background**: Zero-day vulnerabilities are software flaws unknown to the vendor, making them highly valuable to attackers. 2FA (two-factor authentication) adds an extra security layer, but attackers increasingly find ways to bypass it. AI tools can automate and accelerate vulnerability research, previously requiring expert human effort.

<details><summary>References</summary>
<ul>
<li><a href="https://cloud.google.com/blog/topics/threat-intelligence/ai-vulnerability-exploitation-initial-access/">Adversaries Leverage AI for Vulnerability Exploitation ...</a></li>
<li><a href="https://thehackernews.com/2026/05/hackers-used-ai-to-develop-first-known.html">Hackers Used AI to Develop First Known Zero-Day 2FA Bypass ...</a></li>
<li><a href="https://www.csoonline.com/article/4169046/google-discovers-weaponized-zero-day-exploits-created-with-ai.html">Google discovers weaponized zero-day exploits created with AI</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#cybersecurity`, `#zero-day vulnerability`, `#Google threat intelligence`, `#hacker tools`

---

<a id="item-16"></a>
## [Xiaomi to Launch Product with Self-Developed Chip, OS, and AI Model in H2 2025](https://news.mydrivers.com/1/1121/1121731.htm) ⭐️ 8.0/10

Xiaomi plans to launch a commercial terminal product in the second half of 2025 that integrates its self-developed Xuanjie chip, HyperOS, and MiMo AI large model for the first time. This marks the first time all three self-developed technologies will be deployed together in a mass-produced consumer device. This milestone demonstrates Xiaomi's transition from an integrator of third-party components to a full-stack technology company with end-to-end control over hardware, software, and AI. It could strengthen Xiaomi's competitiveness in the premium market and deepen its 'Human x Car x Home' ecosystem strategy. The Xuanjie O1 chip uses TSMC's 3nm process with ~19 billion transistors, while HyperOS is a cross-platform OS and MiMo is Xiaomi's multimodal AI model. The product is not a concept but a fully mass-produced commercial device for consumers.

rss · 快科技 · May 12, 16:40

**Background**: Xiaomi has been developing its own chip (Xuanjie), operating system (HyperOS), and AI large model (MiMo) separately over the past few years. The Xuanjie O1 chip was officially released in 2025, HyperOS has been iterating across devices, and MiMo has been deployed in various terminals. Combining all three in one product represents a significant vertical integration effort, similar to what Apple and Huawei have achieved.

<details><summary>References</summary>
<ul>
<li><a href="https://tele.ofweek.com/2025-06/ART-8320500-8500-30664287.html">玄戒芯片亮相，小米离苹果和华为有多远？ - OFweek通信网</a></li>
<li><a href="https://www.etime.net.cn/site/articalInfo.php?NewsID=76191">小米玄戒芯片：3nm制程工艺的突破与技术解析|ICNET...</a></li>
<li><a href="https://mimo.xiaomi.com/">Xiaomi MiMo, Explore and Love</a></li>

</ul>
</details>

**Tags**: `#Xiaomi`, `#self-developed chip`, `#AI large model`, `#operating system`, `#vertical integration`

---

<a id="item-17"></a>
## [China sends artificial embryos into space for first time](https://news.mydrivers.com/1/1121/1121718.htm) ⭐️ 8.0/10

China's Tianzhou-10 cargo spacecraft launched on May 12, 2026, carrying artificial embryos for the world's first space-based study of early human development in microgravity. This experiment could reveal how gravity affects early embryonic development, providing critical data for long-term space habitation, deep-space exploration, and potential space reproduction. The artificial embryos, which model human development from day 14 to 21 post-fertilization, will develop in orbit for 5 days before being frozen and returned to Earth for analysis.

rss · 快科技 · May 12, 16:20

**Background**: Artificial embryos are stem-cell-derived structures that resemble natural embryos but cannot develop into individuals. They are used to study early developmental biology without ethical concerns. The experiment focuses on the critical window when organ precursors and the body axis form, which is sensitive to environmental disruptions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ncsti.gov.cn/kjdt/kjrd/202605/t20260512_246384.html">“人工胚胎”太空实验将首次开展</a></li>
<li><a href="https://www.sohu.com/a/1021371866_122417797">世界首次！我国“人工胚胎”进入太空：研究微重力的影响</a></li>
<li><a href="https://3g.china.com/act/news/10000169/20260512/49488805.html">“人工胚胎”，首次进入太空！ 探索微重力对发育影响</a></li>

</ul>
</details>

**Tags**: `#space biology`, `#stem cells`, `#embryo development`, `#China space program`

---

<a id="item-18"></a>
## [OpenAI's Former CTO Unveils 'Most Human' AI Interaction Model](http://www.geekpark.net/news/364044) ⭐️ 8.0/10

Thinking Machines Lab, founded by OpenAI's former CTO Mira Murati, has released a research preview of its 'Interaction Model' that enables real-time, multimodal, interruptible conversations, allowing AI to see, hear, and interject like a human. This marks a paradigm shift from the traditional turn-based AI interaction to a continuous, human-like dialogue, potentially making AI assistants more natural and effective in real-time collaboration. The model uses 'Time-Aligned Micro-Turns' processing input and output every 200 milliseconds, integrating audio, video, and text streams into a continuous token sequence, and incorporates a two-layer architecture with an interaction model and a background model.

rss · 极客公园 · May 12, 10:06

**Background**: Current AI chatbots operate on a turn-based model: the user speaks, the AI waits, then responds. This limits real-time collaboration. Thinking Machines Lab's approach trains interaction capabilities directly into the model, rather than relying on external components like voice activity detection (VAD) and text-to-speech (TTS).

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2025/07/15/mira-muratis-thinking-machines-lab-is-worth-12b-in-seed-round/">Mira Murati's Thinking Machines Lab is worth $12B in seed</a></li>
<li><a href="https://www.nytimes.com/2025/02/18/technology/openai-mira-murati-startup.html">Mira Murati, OpenAI’s Former Chief Technology Officer, Starts</a></li>
<li><a href="https://www.wired.com/story/thinking-machines-lab-first-product-fine-tune/">Exclusive: Mira Murati’s Stealth AI Lab Launches Its First</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Human-AI Interaction`, `#Multimodal AI`, `#Startup`

---