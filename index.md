# HN Digest — November 9, 2026

## 1. [USPS now offers official ZIP Code boundary polygons](https://news.ycombinator.com/item?id=50431058) (↑234, 💬114)
**Article:** USPS has released official ZIP Code boundary polygons, offered as paid datasets with quarterly updates and license terms for mapping, marketing, logistics, insurance, and routing uses. The page describes internal, enterprise, and publication tiers and provides sample files, technical guides, and order forms.

**Comments:** Commenters largely object to the cost, arguing government-produced boundary data should be free or available via FOIA-like access, and many suggest Census ZCTAs as a free if imperfect alternative. Others stress that ZIP codes are delivery-route labels rather than true geographic regions, while some defend USPS pricing given its budget constraints and quasi-commercial status.

## 2. [Claude Fable 5.2 Scores 65 on Artificial Analysis, Highest So Far](https://news.ycombinator.com/item?id=50431144) (↑116, 💬64)
**Article:** Artificial Analysis ranks Claude Fable 5.2 (max) first on its Intelligence Index with a score of 65, but notes it is expensive, slow per task, and very verbose. The model supports text and image input, a 1M-token context window, and costs $8/M input and $40/M output tokens.

**Comments:** Much of the discussion focuses on cost per task rather than raw score, with commenters noting a large increase in output/reasoning tokens and debating whether “max” settings are misleading versus medium/high configurations. Some argue Fable is competitive on the Pareto frontier at lower effort levels, while others criticize Anthropic’s pricing, refusals, benchmark methodology, and rapid release cadence.

## 3. [E-means: 10x faster k-means at equal loss](https://news.ycombinator.com/item?id=50429734) (↑165, 💬11)
**Article:** Meta FAIR’s e-means is presented as a modern k-means replacement using mini-batch exponential moving average updates, scaling-law-derived hyperparameters, improved initialization/revival, and fused GPU kernels. It claims roughly 10x fewer epochs and 10–45x GPU wall-clock speedups versus Flash-KMeans while achieving lower loss.

**Comments:** Commenters find the speedups impressive and discuss adapting e-means to other centroid-relaxation problems, though one tried it on spherical mesh relaxation and found it slower and noisier than Lloyd’s. Others ask about the automatic hyperparameter laws, suggest SciPy integration, and connect the work to broader approximate/randomized algorithms and operations research.

## 4. [Payments Canada announces launch of Canada's Real-Time Rail (RTR) payment system](https://news.ycombinator.com/item?id=50427362) (↑417, 💬227)
**Article:** Payments Canada launched the Real-Time Rail, a 24/7 real-time clearing and settlement system using ISO 20022 messaging and centralized fraud controls. The initial participant list includes Wealthsimple, KOHO, and others, with major banks expected in later rollout phases and broader availability targeted within a year.

**Comments:** Commenters compare RTR to Interac e-Transfer, Brazil’s Pix, India’s UPI, Australia’s NPP, and FedNow, questioning whether it will change consumer experience or adoption given major banks’ later participation. Threads also debate Canadian startup/tax advantages, fraud and transaction reversibility, privacy, US real-time payment nuances, and concerns about relying on government or large vendors.

## 5. [Our Smallest, Most Efficient Model: Muse Ember](https://news.ycombinator.com/item?id=50429024) (↑186, 💬76)
**Article:** Meta introduces Muse Ember as its smallest and most efficient model, aimed at agentic tool calls, coding subtasks, routing, extraction, and long-document parsing. It claims strong intelligence-per-dollar results versus Claude Haiku 5.5 and GPT-6 Luna, with API pricing of $0.10/M input and $0.50/M output tokens.

**Comments:** Commenters praise the cost-performance positioning but are disappointed the model is not open-weight, and some question Meta’s relevance and whether benchmark comparisons are selective. Others discuss workload-specific evals, model-release fatigue, cache pricing, and use the “pelican SVG” test across reasoning settings as an informal capability check.

## 6. [Google Gemini routes personal Drive files and emails to human annotators](https://news.ycombinator.com/item?id=50429426) (↑140, 💬24)
**Article:** A GitHub repository documents that consumer Google Gemini with Connected Apps can autonomously retrieve Gmail and Drive content during ordinary chats, sometimes ingesting full files. It reports that Google’s updated help documentation confirms such data may enter human review pipelines and provides reproduction steps showing retrieval is probabilistic.

**Comments:** Commenters distinguish consumer Gemini from Workspace Gemini, which still claims no human review, and criticize the privacy erosion. Many express anger and advocate self-hosting or local LLMs, while others note enterprise trust risks and share anecdotes of Gemini seeming to use personal email context.

## 7. [Claude Fable 5.2 and Mythos 5.2](https://news.ycombinator.com/item?id=50429906) (↑751, 💬422)
**Article:** Anthropic announces Claude Fable 5.2 and Claude Mythos 5.2, describing them as the same underlying model with different safeguards for cyber and biology misuse. The post claims gains in coding, science, robotics, and reasoning, faster output, lower pricing, and benchmark improvements over Opus 5.5 and competitors.

**Comments:** A major thread debates whether Opus 5.5 was “nerfed” before the release and questions benchmark fairness, especially model effort levels and Gemini comparisons. Others discuss cost versus capability, Anthropic’s limits on AI R&D-related capabilities, and the significance of the claimed 1,000-agent Fermat formalization.

## 8. [CUI – Native UI components for C](https://news.ycombinator.com/item?id=50430621) (↑85, 💬51)
**Article:** CUI is presented as a native UI component library for C, with overview, components, showcase, and app examples. The provided article content is mostly site navigation, so details of implementation are limited.

**Comments:** Commenters largely suspect the project is AI-generated and only days old, questioning its long-term maintainability, security, and use of “native.” Some praise its clean look and lightweight alternative to Electron, while others criticize UX-design misunderstandings, immediate-mode rendering, and the CUI acronym collision.

## 9. [Fold Epic Paper Airplanes](https://news.ycombinator.com/item?id=50424581) (↑743, 💬128)
**Article:** Foldable Flight is a website collecting paper airplane designs with difficulty, speed, glide, and accuracy ratings plus folding tutorials and a shop. It highlights record-holding and popular designs such as Firefly, Unite, Arrowhead, and Mystic.

**Comments:** The thread is largely nostalgic and enthusiastic, with users sharing childhood paper-airplane stories and praising the Mystic design. Others criticize the site’s UX, video-only instructions, sorting limitations, and popups, while the site creator responds and asks for feedback.

## 10. [Infineon marks innovation milestone with 300mm power silicon carbide wafer](https://news.ycombinator.com/item?id=50429430) (↑65, 💬28)
**Article:** Infineon announces the first functional power devices processed on 300mm silicon carbide wafers, calling it an industry milestone. The company says the process feasibility supports future SiC supply for automotive, renewable energy, industrial, and AI data-center applications.

**Comments:** Commenters discuss why 300mm SiC took so long, citing material difficulty and defect sensitivity, and debate GaN versus SiC by voltage and application. A side thread argues about reviving DRAM production in Europe, while others question Wolfspeed’s earlier 300mm claims and clarify Infineon’s “first” as processing functional devices rather than merely producing substrates.

## 11. [Magenta solar panels may be agrivoltaics' cleverest trick yet](https://news.ycombinator.com/item?id=50426175) (↑223, 💬128)
**Article:** The article describes an agrivoltaics experiment using semi-transparent solar panels that pass red and some blue light while generating electricity, casting magenta shade. Broccoli under the panels took 25 extra days to mature but produced roughly the same yield, with improved microclimate and water-use efficiency; the study is preliminary and calls for larger multi-season trials.

**Comments:** Commenters were broadly skeptical of large-scale agrivoltaics, citing tractor and center-pivot access, structural costs, maintenance, and the economics of separate solar farms versus farmland. Several argued the technology is more promising for small farms, greenhouses, specialty crops, and shade-tolerant plants, and many pointed to corn ethanol as a better target for replacement by solar; some noted shade benefits and CdTe tellurium constraints.

## 12. [Show HN: Every satellite that passed over any place this week, and its photos](https://news.ycombinator.com/item?id=50428907) (↑142, 💬30)
**Article:** The Show HN presents a site that shows which satellites passed over a given location in the past week and links to imagery they captured. The page emphasizes a visual, animated interface for exploring satellite overpasses and photos.

**Comments:** Commenters praised the combination of design and substance, the smooth UI and animations, and its usefulness for trip planning and geospatial work. Some called it cool but slightly creepy, asked about image resolution—the author said ~10 m/px is typical public resolution—and a few suspected AI involvement while the author thanked users.

## 13. [A primer on GPUs and kernel optimization](https://news.ycombinator.com/item?id=50386246) (↑46, 💬1)
**Article:** The linked article is a primer on GPUs and kernel optimization, but the provided content includes only the title and no article body. It therefore cannot be summarized in more detail from the supplied material.

**Comments:** The sole comment criticizes the primer for omitting benchmarking and evaluation of kernels altogether. It lists practical concerns such as hot vs. cold caches, bitwise equivalence to a reference, error margins, thermal noise, testing across GPUs, CUDA graph launch overhead, and A/B interleaving.

## 14. [Show HN: MeowDisplay Is iPhone Mirroring, but in Reverse](https://news.ycombinator.com/item?id=50429636) (↑54, 💬20)
**Article:** MeowDisplay is an open-source app that turns an iPhone, iPad, Android device, or another Mac into a display for a Mac, supporting mirroring, extending, touch input, window management, and remote access. It is a fork of OpenDisplay and is free on Apple platforms, with Android in closed testing.

**Comments:** Commenters praised the polished marketing site and asked about latency, benchmarks, color/HDR support, account requirements, and how it compares with OpenDisplay, Sill, and Apple Sidecar. The author said median capture-to-receiver latency was about 14–17 ms on Wi-Fi with occasional spikes, that it does not require the same Apple ID, and explained its phone-first design and differences from OpenDisplay and Sill.

## 15. [Is Opus 5.5 nerfed? Thinking patterns changed on November 3](https://news.ycombinator.com/item?id=50422069) (↑657, 💬429)
**Article:** A viral X post by Shane Melaugh claims Opus 5.5 was “nerfed” around November 3, based on an analysis of 1,400 Claude Code sessions by Gemini 4 Argon; he says high-effort reasoning dropped while xhigh performed better on a test bug. He later clarified this was personal frustration and not a scientifically rigorous benchmark.

**Comments:** Commenters largely shared anecdotal reports of quality drops, higher token use, faster limits, and more errors, with speculation about quantization, compute reallocation, A/B testing, or preparation for a new model. Others pushed back that such claims are vibes-based and lack eval evidence, while some reported no degradation or better results and debated open-weight/self-hosted alternatives and provider lock-in.

## 16. [Y/N (YC S23) is hiring a growth lead to distribute superhuman A.I. storytelling](https://news.ycombinator.com/item?id=50428266) (↑1, 💬0)
**Article:** Y/n, a YC-backed startup building interactive AI-generated storytelling, is hiring a founding growth marketer in San Francisco at $130K–$300K plus equity. The role focuses on finding and owning growth channels, including paid ads, creator partnerships, and UGC programs for a teen/young-adult audience. The posting says Y/n has raised $14M and users have sent over one billion messages.

**Comments:** No comments were posted.

## 17. [DeepX claims inference up to 100B parameters at less than 5 W](https://news.ycombinator.com/item?id=50429545) (↑113, 💬14)
**Article:** The article content was unavailable; based on the title and comments, it concerns a DeepX chip claim of running inference for models up to 100B parameters at under 5 W.

**Comments:** Commenters debate the claim’s practical meaning, comparing 80 TOP/s and 150 GB/s memory bandwidth to consumer GPUs and estimating slow but potentially useful local AI performance for MoE models. They also discuss whether such compute-in-memory efficiency could disrupt data centers, note likely memory-cost tradeoffs, and joke about human-brain power comparisons.

## 18. [Parking-app convenience fees in 312 U.S. cities (median $0.35 per session)](https://news.ycombinator.com/item?id=50430991) (↑15, 💬3)
**Article:** Park Graph published a dataset of parking-app convenience fees across 312 U.S. places, finding a median fee of $0.35 per session among places that publish one. The most common fee is $0.35, the highest flat fee listed is $0.70 in Anchorage, and 15 places charge no app fee. The data covers multiple app providers, with ParkMobile dominating the listed places.

**Comments:** PayByPhone’s co-founder questions the dataset’s $0 fee claims for PayByPhone and asks why cities or providers would not choose a $0 option. Other commenters complain that parking-app fees have become excessive and argue the apps persist because of city-government corruption rather than technical barriers, with some hoping AI will disrupt the market.

## 19. [An ode to livelyness analysis; SSA to registers](https://news.ycombinator.com/item?id=50405274) (↑11, 💬0)
**Article:** This technical blog explains liveness analysis as a step toward register allocation for the author’s Purple Garden language, targeting both a bytecode VM and an x86 JIT. It describes an SSA IR using block parameters and terminators instead of phi nodes, then shows how to compute each virtual register’s live range by walking blocks, instructions, and terminators. The resulting ranges are intended to support assigning virtual registers to physical registers and stack slots.

**Comments:** No comments were posted.

## 20. [Supply chain attack on Qubole customers](https://news.ycombinator.com/item?id=50432147) (↑8, 💬1)
**Article:** Sentra describes a Qubole supply-chain attack in which stolen vendor credentials were used to assume Qubole-trusted cross-account roles at dozens of customer organizations. The attacker read data and credentials without write actions, using infrastructure such as an OVH server and Mullvad VPN, while presenting valid ExternalIds that made access look legitimate to AWS. The article details how Sentra, Wiz, and Mandiant traced the activity through behavioral anomalies, external-identity mapping, and logs tied to encrypted-file access and secret reads.

**Comments:** Only one comment was posted, expressing surprise (“Wowww”), with no substantive discussion.

## 21. [What is malloc doing, anyway?](https://news.ycombinator.com/item?id=50424157) (↑193, 💬52)
**Article:** The post explains what glibc’s malloc does under the hood, using brk/sbrk syscalls, address-space layout, chunk headers, free lists, splitting, and coalescing to build a toy allocator. It benchmarks syscall and malloc costs to show why allocators request larger blocks from the kernel and manage small allocations in userspace.

**Comments:** Commenters debate whether brk-based allocation is obsolete, with some arguing modern allocators like jemalloc and mimalloc rely on mmap while others note glibc malloc remains relevant and uses this strategy for many allocations. Threads also recommend allocator resources, discuss Zig’s explicit allocators and stack-only languages like Goose, and raise side issues such as PHP worker memory growth and code-fragment quality.

## 22. [Show HN: DBDelve – Open-Source DB Client Made with Rust and GPUI](https://news.ycombinator.com/item?id=50427934) (↑80, 💬28)
**Article:** The author introduces DBDelve, an open-source Rust/GPUI database client focused on performance and pleasant UX, with benchmarks comparing it favorably to DBeaver on launch time, memory, and large result sets. It lists features such as access modes, themes, customizable keybindings, project organization, connection imports, and limitations including unsigned macOS builds and incomplete feature parity.

**Comments:** Comments are largely supportive but ask about database support, query-editor intelligence, import options, sustainability, and comparisons with dbx, DataGrip, and Beekeeper Studio. Some users are skeptical of the “rewrite in Rust” trend and question whether client performance matters when queries dominate wait time, while the author argues rendering, scrolling, memory use, and UX still matter after queries finish.

## 23. [Show HN: Someone Was Here – Find out who used your Mac while you were away](https://news.ycombinator.com/item?id=50429812) (↑27, 💬9)
**Article:** “Someone Was Here” is a macOS app that photographs anyone who uses an idle or locked Mac and sends alerts to an iPhone app, with local face recognition to avoid alerting the owner. It claims local-only photo storage, no accounts or tracking, visible camera use, and optional one-time paid alerts via iCloud, Pushover, ntfy, Telegram, or webhook.

**Comments:** Some commenters find the app itself creepy and privacy-invasive, while the author compares it to a doorbell camera or audit trail that complements account security. Others suggest alternatives like Objective-See’s DoNotDisturb or email/iMessage alerts, and a few joke about the app being inspired by an ex.

## 24. [Deuterium's Impact on OLED Displays (2024)](https://news.ycombinator.com/item?id=50411515) (↑15, 💬6)
**Article:** This sponsored Clearsynth post explains how deuterium substitution can improve OLED efficiency, brightness, and lifetime, especially for blue emitters, with claims such as a 4x increase in LT50 for deuterated host materials. It also discusses deuterium’s use in neutron studies and potential expansion from TVs to phones, automotive displays, and wearables.

**Comments:** Commenters note the article lacks detail and may describe lab methods that are hard to scale, while linking a more technical reference. The thread drifts into heavy-water production, CANDU reactors, deuterium in semiconductors, and the WWII Norwegian sabotage of Nazi deuterium production.

## 25. [When will this stop? The Raspberry Pi 5 16GB SBC now sells for $385](https://news.ycombinator.com/item?id=50428801) (↑239, 💬199)
**Article:** CNX Software reports that the Raspberry Pi 5 16GB now costs $385 after another increase, with CM5 modules also rising, amid broader RAM shortages and AI-driven demand. It lists recent price hikes across SBCs and SoMs and notes uncertainty over when memory prices might ease.

**Comments:** Commenters largely criticize the pricing, arguing that used mini PCs, thin clients, phones, or cheaper microcontrollers are better value and that 16GB is excessive for most Pi use cases. Some debate whether Raspberry Pi is still worthwhile for embedded or industrial buyers, while others attribute the increases to the AI/RAM bubble and recommend fast SSD storage over extra RAM for performance.

## 26. [Show HN: Recalc – Spreadsheet where cells can be Claude Code or Codex terminals](https://news.ycombinator.com/item?id=50413970) (↑19, 💬3)
**Article:** Recalc is an early-beta open-source spreadsheet app (Rust/Tauri) where each cell can hold a value, formula, terminal command, or a Claude Code/Codex agent, letting users watch agents work in real time and catch failed tests or correct outputs directly. It includes features like batch document querying with cited answers, a "Needs You" queue, a driver agent, and local-only data storage via an MCP server interface.

**Comments:** With only two comments, the key debate concerns cell-reference integrity—one user asks how agent outputs at a cell like A3 behave when rows are inserted above, since LLM pointers won't survive like formulas do. The author responds that row insertion/deletion is blocked mid-execution, references are rewritten uniformly, and "Named cells" offer an alternative for stable references.

## 27. [Zebkit – Chromium as an embeddable library](https://news.ycombinator.com/item?id=50426207) (↑105, 💬37)
**Article:** Zebkit packages Chromium's engine (Blink, V8, PDFium, FFmpeg) as an embeddable library you link into your own app in C, Rust, Python, or Go, rather than running your app inside Electron's runtime. It claims 34% smaller size, faster cold start (2.3s vs 6.6s), native Playwright API without CDP/Node, and exports 7,000+ functions from Chromium's bundled libraries.

**Comments:** A large thread compares it to CEF, with users questioning whether the same-process/CFFI approach loses sandboxing and crash isolation, while the author clarifies it retains Chromium's sandboxed renderer processes. Others raise licensing/notarization pitfalls (FFmpeg, Blink), Google login detection of embedders, and the name "zebkit"; several call the project AI-generated "slop," while others defend it as a genuinely useful step toward lightweight browser embedding.

## 28. [Pigshell: Unix the Web](https://news.ycombinator.com/item?id=50426831) (↑53, 💬18)
**Article:** Pigshell is an old project (last updated 2015) presenting "Unix the Web"—a browser-based shell environment for navigating web resources, with Plan 9 influences. The page itself is minimal, loading just the kernel interface.

**Comments:** Discussion centers on the site's HTTPS-to-HTTP redirect causing Chrome's generic "Not Secure" warning, prompting complaints about Chrome hiding protocol/security details versus Firefox. Commenters note the project is 11 years stale, muse about mapping the web to a filesystem and plan9/9p ideas, and share related projects like mkfifo.com.

## 29. [Cryptocurrency lawsuit: Ethereum Foundation required "suicide pledge"](https://news.ycombinator.com/item?id=50426899) (↑170, 💬160)
**Article:** A Boulder woman sued the Ethereum Foundation, alleging it distributed a 38-page "mandate" containing an illustrated "Source Seppuku License" suicide pledge and demanded employees commit to it by Monday or leave. She was fired after leading resistance, and the suit alleges the visual style drew on controversial online imagery that founder Vitalik Buterin defended as intentional.

**Comments:** Many argue the pledge is clearly a joke but legally reckless, questioning enforceability of such clauses and noting courts can't reliably interpret "joke" terms in signed documents. Others see it as a loyalty test/culture filter and criticize the 1,000-year vision and crypto culture, while a few defenders say employees are over-literalizing an obvious meme.

## 30. [Children of Men: The future is a mirror for the present](https://news.ycombinator.com/item?id=50425303) (↑148, 💬113)
**Article:** A Reactor essay argues Children of Men (2006) is among the best sci-fi films of the century, framing all future-set fiction as commentary on the present. It details Cuarón's loose adaptation of P.D. James's novel, his deliberate refusal to explain the infertility, and the film's narrowed focus on authoritarianism's effect on the powerless.

**Comments:** Commenters share personal reactions, with many noting the film's growing relevance amid declining fertility rates and political decay; some dispute comparisons to current US/UK conditions. Others highlight the Christian/nativity allegory the essay omits, praise the long-take action scenes and sound design, and digress into a debate over Mad Max: Fury Road's merits and fertility-crisis theories.

---
_Generated 2026-11-09 16:05 MDT_

---

## Recent Digests

- [Nov 9](./archives/2026/nov/hn-digest-2026-11-09.md)
- [Nov 8](./archives/2026/nov/hn-digest-2026-11-08.md)
- [Nov 7](./archives/2026/nov/hn-digest-2026-11-07.md)
- [Nov 6](./archives/2026/nov/hn-digest-2026-11-06.md)
- [Nov 5](./archives/2026/nov/hn-digest-2026-11-05.md)
- [Nov 4](./archives/2026/nov/hn-digest-2026-11-04.md)
- [Nov 3](./archives/2026/nov/hn-digest-2026-11-03.md)

[Full archive](./archives/) (181 issues)

_If you want more, explore the [archive folder](./archives/)._
