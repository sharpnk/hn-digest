# HN Digest — November 24, 2026

## 1. [Ternary Bonsai 2.5 27B](https://news.ycombinator.com/item?id=50633922) (↑165, 💬54)
**Article:** PrismML released Ternary Bonsai 2.5 27B, a ternary-compressed Qwen3.8 27B derivative with a 5.9 GB footprint and improved agentic coding, multi-turn tool use, and multi-step execution. It reports benchmarks closer to the full-precision base model, faster generation on H100/RTX 4090, and availability under Apache 2.0 via llama.cpp and MLX.

**Comments:** Commenters benchmarked the Q2 GGUF on Mac hardware and debated whether the strong SWE-bench numbers reflect real capability or benchmarkmaxxing; several said prior Bonsai versions looped or needed prompt tuning, while others praised the size/performance tradeoff. There were also questions about the business model, ternary hardware acceleration, and comparisons to Inkling 2 Mini and full-precision Qwen.

## 2. [Launch HN: Versine (YC F26) – MCP to send and receive money](https://news.ycombinator.com/item?id=50634426) (↑32, 💬13)
**Article:** Versine launches an MCP-enabled wallet that lets AI agents send and request money with passkey approval, trusted-contact exceptions, and payouts to non-users via claim forwarding. Balances are held in self-custodial USDC wallets on Base, and the team positions this as a wedge into an agent-first bank.

**Comments:** Commenters focused on practical trust and fraud: passkey/1Password failures, dispute/reversal flows when an agent pays the wrong person, and what happens to unclaimed OTP-forwarded USDC. Others asked how Versine monetizes and warned that Venmo/CashApp could copy it, while some praised the bulk-request use case and landing page.

## 3. [Active intrusion campaign against Check Point security management servers](https://news.ycombinator.com/item?id=50630594) (↑232, 💬95)
**Article:** GreyNoise describes GT13, an intrusion campaign between Oct 17 and Nov 2, 2026, targeting Check Point Security Management Servers at 22+ organizations across multiple regions and sectors. The actor used 99 IPs, multiple CVEs, an operational relay box, and tooling including Nmap, Chisel, Impacket, and Paramiko; GreyNoise suspects LLM/agentic assistance and expects the campaign is ongoing.

**Comments:** The thread debated whether LLM-enabled attackers will make cybercrime dramatically worse, with some arguing existing fraud/scam ecosystems are already large and others warning that automation lowers skill and cost. Technical comments focused on insecure Math.random(), internet-exposed management planes, attackers patching compromised hosts, and whether switching firewall vendors or using pfSense/NixOS actually helps.

## 4. [Working with AI](https://news.ycombinator.com/item?id=50634734) (↑29, 💬21)
**Article:** Anthropic’s economics team summarizes 66 interviews with 58 enterprise customers, finding AI value mostly from increased output rather than cost cuts and few domestic AI-driven layoffs, though hiring and contractor use often fell. Companies reported bottlenecks, resistance, and uneven top-down/bottom-up adoption, with the highest-value uses involving reorganizing roles and workflows around AI.

**Comments:** Commenters found the report more grounded than expected but questioned its qualitative sample and timing, and disputed whether recent layoffs were really AI-driven. Much discussion focused on coding agents for nontechnical roles, the disappearance or merging of QA/PM/analyst roles, and Anthropic’s business prospects.

## 5. [The Spray Bottle](https://news.ycombinator.com/item?id=50598555) (↑275, 💬80)
**Article:** An illustrated interactive explainer dissects a 1970s-style spray bottle, labeling parts and stepping through trigger, piston, spring, nozzle, and one-way valve operation. It uses animations and cutaways to show how pulling the trigger sprays and releasing reloads the chamber.

**Comments:** Commenters praised the interactive illustrations and compared them to Bartosz Ciechanowski and Sendung mit der Maus, while some questioned whether AI was involved. Others criticized the one-way-valve explanation as confusing or inaccurate, especially how the ball seats and why fluid doesn’t flow backward; the author’s FAQ says the breakdowns are CAD/illustrated manually.

## 6. [From CUDA and Jax to TorchTPU: Lessons from a Cayley Graph Solver](https://news.ycombinator.com/item?id=50633424) (↑32, 💬0)
**Article:** The author ported a Cayley graph puzzle solver from CUDA/A100 and JAX/TPU to Google’s TorchTPU, initially finding training 1.65x slower and beam search 5.7x slower. After fused eager execution, an attention rewrite, static shapes, deduplication fixes, and attention-routing fixes, training matched A100 wall-clock performance and optimized beam search was 25% faster per level than JAX on eight v6e chips. The work also produced an upstream TorchTPU GitHub issue and Kaggle notebooks.

**Comments:** No comments were posted. There is no discussion to summarize.

## 7. [Gödel Enigma](https://news.ycombinator.com/item?id=50625265) (↑15, 💬0)
**Article:** The University of Helsinki’s Gödel Enigma project aims to study Gödel’s unpublished notebooks, lecture notes, and correspondence, much of it in shorthand, alongside Bernays archives to build a fuller historical picture of his role in logic and foundations. It argues these sources are underexplored compared with quantum mechanics historiography and could reveal unknown scientific developments. The project lists notebook series such as Resultate Grundlagen, Arbeitshefte, Logik und Grundlagen, and Max Phil as key sources.

**Comments:** No comments were posted. There is no discussion to summarize.

## 8. [Jetty Pro](https://news.ycombinator.com/item?id=50630462) (↑228, 💬90)
**Article:** John Siracusa introduces Jetty Pro, an unsandboxed macOS app that creates customizable Dock-like floating palettes for files, folders, apps, Shortcuts, and Trash. It grew out of his long wish to recreate DragThing-style folder palettes and replace Dock behavior; after abandoning a sandboxed Mac App Store version, he built the direct-distributed Pro app using private APIs over three and a half months with AI coding agents. The post details features such as custom icons, backgrounds, badge hiding, and folder label colors.

**Comments:** Most discussion centers on the subscription model: many users say they would buy a one-time license or prefer a “pay for updates” perpetual-fallback model, while others argue subscriptions are fair because private APIs can break with macOS updates. Some commenters report replacing niche Mac apps with AI-generated personal tools, and several were confused by the name because Jetty is a well-known Java web server.

## 9. [2035 came early](https://news.ycombinator.com/item?id=50624497) (↑914, 💬344)
**Article:** Farid Zakaria describes trynix.dev now booting GUI programs through unkernel, a Linux compiled to WebAssembly with user programs emulated, enabling networking, sound, Wayland windows, and GL rendering in the browser. The post benchmarks unkernel as 2x to 32x faster than qemu-wasm depending on workload and demonstrates Firefox running inside Firefox inside the browser. It frames this as Gary Bernhardt’s “2035” JavaScript-dominance vision arriving early, though the implementation relies heavily on WebAssembly.

**Comments:** Commenters express amazement at the nested browser/Linux demo and discuss possible uses, performance, WASM sandboxing/determinism, and the relationship to unkernel and the Wisp protocol. A major debate questions the “2035” framing because the stack is WebAssembly rather than JavaScript, and many commenters criticize JavaScript’s ecosystem while others say JS dominance is overstated. Some note similar projects are appearing quickly with LLM assistance, and one commenter says they abandoned a competing project after unkernel gained attention.

## 10. [Calculate how many mesh radio nodes your city needs](https://news.ycombinator.com/item?id=50609483) (↑34, 💬3)
**Article:** The Mesh coverage calculator is a browser tool that estimates required mesh radio nodes and coverage for Meshtastic/LoRa, Wi-Fi, and Wi-Fi HaLow using terrain DEM data, OpenStreetMap buildings, antenna patterns, radio settings, and sampling resolution. It outputs heatmaps, link profiles, CSV/GeoJSON, and airtime/voice-call estimates.

**Comments:** Commenters note the selectable area is limited because terrain and building data load slowly, and one wishes they could cover an entire metro area. The site was also briefly overwhelmed (“Too many requests”), and one commenter jokes that deploying actual radios is far slower than loading the data.

## 11. [Splitting USB-C: USB 3 and USB 2 on one port](https://news.ycombinator.com/item?id=50629106) (↑108, 💬73)
**Article:** The post describes a USB-C dongle design that keeps USB 2 on a cheap hub while passing USB 3 SuperSpeed lanes straight through the same port using muxes, reaching 10 Gbps and costing less than an earlier USB-2-only board. It explains USB-C pinouts, the separation of USB 2 and USB 3 buses, and bench results showing both buses active simultaneously on macOS.

**Comments:** Commenters debate spec compliance and power management, warning that splitting USB 2 and USB 3 topology can confuse port power control and fallback behavior, though several note it works in practice for expert tools. Others discuss USB-C’s complexity versus USB-A, hub quirks, and whether this approach is appropriate outside narrow, non-production uses.

## 12. [A training engine for your local model, using your idle compute](https://news.ycombinator.com/item?id=50629231) (↑136, 💬38)
**Article:** Songe is a local training engine that proxies an OpenAI-compatible model, records agent interactions, corrections, and tool errors, then uses idle time for “Quick Dream” instruction updates or “Deep Dream” adapter training. It validates new versions against the user’s own conversations and keeps data local with no account or telemetry.

**Comments:** Commenters ask for concrete improvement metrics, evaluation details, hardware requirements, and clearer documentation; some identify it as a ChatCompletions proxy that harvests examples to train a LoRA adapter and swaps it in if eval passes. Discussion also covers distributed SETI-like training, local-model motivations like privacy and control, and related work such as Hugging Face harness adapters.

## 13. [GTA 6 Running on Windows](https://news.ycombinator.com/item?id=50627783) (↑203, 💬221)
**Article:** An X post claims GTA 6 is running on Windows with nearly complete shaders shortly after an Xbox build leak, referencing the VIctory project, Vulkan, and AI-assisted work. The linked post is light on technical detail and mainly conveys excitement about rapid progress.

**Comments:** Commenters clarify that this is a Wine-like compatibility effort translating Xbox/RDNA 2 shaders and handling unified-memory differences, not a full recompilation or decompilation. Debate centers on whether this pressures Rockstar toward earlier PC releases, pushes publishers toward streaming/lockdowns, or is mostly hype given fake videos, low frame rates, and the leaked Xbox build’s limitations.

## 14. [Cloudflare hides shortcomings of the underlying infrastructure](https://news.ycombinator.com/item?id=50632883) (↑122, 💬80)
**Article:** The author argues Cloudflare presents modern TLS, IPv6, and post-quantum support at the edge while origin connections may still be unencrypted or IPv4-only, and says the dashboard should warn administrators more proactively. The post criticizes Cloudflare’s documented IPv4 preference for origins and proposes exposing origin TLS/IP-version metadata to users and researchers.

**Comments:** A Cloudflare employee points to the SSL/TLS Recommender, automatic origin TLS, and post-quantum origin work, while others say Cloudflare already pushes strict TLS and that IPv4 origin preference is minor or configurable. Commenters also argue the bigger issue is Flexible SSL, question the wisdom of exposing origin details, and discuss DDoS/WAF value, uptime tradeoffs, and Cloudflare Tunnel use.

## 15. [Grafana 12.4.16, 13.0.14, 13.1.11, 13.2.7 and 13.3.2 (multiple CVEs)](https://news.ycombinator.com/item?id=50633159) (↑89, 💬17)
**Article:** The linked Grafana download page lists releases including 13.3.2 and related versions, but the page itself provides no CVE details despite the title referencing multiple CVEs. The post functions mainly as a pointer to updated Grafana releases.

**Comments:** Commenters supply CVE references from GitHub release pages, correct a version typo, and link to Grafana’s security advisories and GitHub releases for more detail. They debate why the post reached the front page, note most issues appear medium severity except a cookie decryption oracle requiring a secret, and discuss adding auth in front of self-hosted Grafana or switching to lighter alternatives.

## 16. [Weave (YC W25) is hiring ML, AI, product, & design engineers](https://news.ycombinator.com/item?id=50631041) (↑1, 💬0)
**Article:** Weave (YC W25) is hiring for ML, AI, product, and design engineering roles; the article content is a jobs listing.

**Comments:** No comments.

## 17. [An unclassified CIA system was breached in a cyberattack](https://news.ycombinator.com/item?id=50634933) (↑25, 💬2)
**Article:** The article content was unavailable, but the title reports a cyberattack on an unclassified CIA system; comment excerpts say no classified information was involved, the issue was resolved, and the affected system handled open-source intelligence.

**Comments:** One commenter calls the submission title technically correct but more sensationalist than the original AP wording. Another speculates that recent issues at the NSA, FAA, and CIA may be fallout from DOGE.

## 18. [Quad9 pulled their DNS service from France](https://news.ycombinator.com/item?id=50625384) (↑298, 💬157)
**Article:** Quad9 says it will disable DNS service for French users on November 24, 2026, after a court upheld beIn’s demands that it block piracy-related domains and it faced fines for non-compliance. Quad9 argues recursive DNS is the wrong mechanism for content blocking and that geoIP-based selective blocking is imprecise and was previously rejected in a German case.

**Comments:** Commenters debate whether Quad9 is taking a principled stand against overreach or simply refusing lawful orders, with many criticizing DNS blocking as technically ineffective and harmful. Others discuss geoIP limitations, ISP-level enforcement, French judges and policy, and offer workarounds such as alternative resolvers or a proxy for French users.

## 19. [Show HN: Mason – A lightweight Postgres read-replica, built on columnar storage](https://news.ycombinator.com/item?id=50630294) (↑72, 💬11)
**Article:** Mason is an Apache-2.0, lightweight drop-in Postgres read replica that syncs selected data into DuckDB’s columnar engine and rewrites Postgres queries for fast analytical workloads. It advertises large speedups on aggregations and joins, along with RBAC, row-level security, MCP support, monitoring, and local or cloud deployment.

**Comments:** Commenters ask about storing replicated tables as S3/Parquet, using CDC or ADBC instead, SQL transpilation, and how Mason differs from DuckDB plus Postgres. The author explains that Mason focuses on replication and query rewriting, avoids load on the Postgres primary, and aims to return the same answers as Postgres rather than faster but different results.

## 20. [An Italian folding bicycle design that fits into a suitcase](https://news.ycombinator.com/item?id=50610820) (↑71, 💬58)
**Article:** The article profiles the 1963 T&C Pocket Bici, an Italian folding bicycle whose components fold into a racetrack-shaped frame and fit inside its own suitcase. Its origin is unclear, with accounts differing on whether it was made for the Chinese market and how many units were produced or sold.

**Comments:** Commenters compare it with Brompton and other folding bikes, discussing wheel size versus ride quality, compactness, weight, and suitcase practicality. Some suggest municipal bike-share systems or larger-wheel folders, while others share experiences with Brompton, Bike Friday, Helix, Montague, Tern, and other designs.

## 21. [GPT-6 models demonstrate intrinsic protein-design capabilities](https://news.ycombinator.com/item?id=50634658) (↑9, 💬0)
**Article:** OpenAI reports that its GPT-6 models can design protein structures and amino-acid sequences using reasoning and code without calling specialized biology models, matching or beating specialized tools on many tasks. Lab tests with Onava found evidence of binding for designs against five targets, though full protein-structure prediction remained a weakness. OpenAI frames this as evidence of intrinsic “universal” protein-biology capabilities in general-purpose models.

**Comments:** The sole comment asks how such protein designs could be checked without growing them in a lab. It implicitly raises the gap between computational design claims and wet-lab validation.

## 22. [LLM agents work for their parent companies, not for you](https://news.ycombinator.com/item?id=50627340) (↑832, 💬346)
**Article:** The author describes building a Claude Code skill to identify music from Instagram reels and find artists’ Bandcamp pages, then criticizes Claude for refusing to work around a Bandcamp challenge while still allowing YouTube downloads. He argues commercial LLM agents ultimately serve their parent companies’ policies rather than users’ interests, raising concerns about enshittification and product placement. He concludes that local or open models are needed for agents that genuinely work for their owners.

**Comments:** Commenters are split: many defend the refusal as respecting Bandcamp’s terms and avoiding agentic anarchy, while others sympathize with the author’s concern about corporate control and advocate local/open models. Threads debate whether models should have fiduciary-like duties, whether refusals come from models or harness prompts, and how common refusals actually are. A recurring theme is that guardrails can protect site operators but also constrain legitimate user goals.

## 23. [Worshipping at the altar of Brendan Gregg](https://news.ycombinator.com/item?id=50626413) (↑205, 💬38)
**Article:** Farid Zakaria introduces a new “rewind time” command for the Rewind deterministic VM that analyzes a recording’s critical path, off-CPU time, and process tree, using a libuv build as an example. The tool is presented as an extension of Brendan Gregg’s flame-graph and off-CPU analysis ideas, with the ability to drill into source lines and replay the run under gdb. The example shows most of the critical path spent asleep, with test processes and timers dominating runtime.

**Comments:** Commenters show strong interest in deterministic VMs and compare Rewind with rr and Antithesis, while asking about single-threaded replay and async workloads. Several criticize the article’s title, lack of a fixed-problem example, and perceived LLM-generated phrasing, while others discuss flame graphs, production profiling, and off-CPU analysis. The author responds that the simplifications were intentional and that the piece aimed to explain the idea rather than a single bug fix.

## 24. [Cento fine foods has been sued for “tomato fraud”](https://news.ycombinator.com/item?id=50604355) (↑69, 💬114)
**Article:** Slate examines a lawsuit accusing Cento Fine Foods of “tomato fraud” over cans labeled San Marzano, explaining the DOP/Consortium rules, limited authentic supply, and earlier tomato-deception lawsuits. The author finds Cento’s tomatoes excellent despite doubts about authenticity, while noting that U.S. labeling rules are weaker than Europe’s. The piece explores whether consumers are paying a premium for a legendary name rather than verified provenance.

**Comments:** A detailed commenter explains that San Marzano is both a cultivar and a protected regional name, and that Cento sources the cultivar outside the DOP zone, which is legal in the U.S. but contested by the Consortium. Others debate DOP as a quality signal, U.S.-Europe price differences, calcium chloride’s effect on cooking, and brand taste tests. Many conclude that labels are unreliable and that buyers should judge by taste, though some insist DOP certification still matters.

## 25. [How a Mechanical Watch Keeps Time (Interactive 3D)](https://news.ycombinator.com/item?id=50599458) (↑195, 💬50)
**Article:** This interactive 3D explainer walks through the hairspring, balance wheel, escapement, gears, gear train, and mainspring of a mechanical watch. It uses simplified animations and analogies to show how oscillations are converted into counted ticks and how gear ratios drive the hands, aiming at a beginner-friendly introduction. The page credits Bartosz Ciechanowski’s mechanical-watch essay as inspiration and deeper reference.

**Comments:** Several watch-knowledgeable commenters note that the simplified escapement lacks the impulse that replenishes the balance wheel’s energy, so the depicted watch would not actually run. The author replies that this was an intentional pedagogical simplification for a “101” explanation. Other comments praise the visuals but criticize AI-assisted writing and Claudisms, compare it unfavorably with Ciechanowski’s page, and debate jewels, friction, and whether starting with the mainspring would be clearer.

## 26. [Show HN: Brickie – Deploy sandboxes in your own AWS account](https://news.ycombinator.com/item?id=50629936) (↑16, 💬0)
**Article:** Brickie is an open-source (MIT) tool from Hatchet for running durable agent sandboxes inside your own Kubernetes cluster or Docker engine, using the agent-sandbox controller with custom snapshot/restore backed by any S3-compatible, GCS, or Azure object store. Every workspace-changing call produces an immutable, forkable snapshot keyed by sandbox and Hatchet run ID, so sandbox calls become retryable, observable Hatchet tasks with no duplicate execution on retry. It supports Kata, gVisor, and AWS Nitro runtime isolation, warm pod pools for fast starts, mTLS between provider and sandboxes, FIPS 140-3 mode, and is currently in beta.

**Comments:** No comments were posted on this story.

## 27. [Microsoft declares 'Code Red' after historic outage, internal memos show](https://news.ycombinator.com/item?id=50631157) (↑177, 💬150)
**Article:** The article's content was unavailable, but the headline and thread indicate Bloomberg reporting that Microsoft declared an internal "Code Red" after a major outage, which it attributed to an undetected Windows scalability defect introduced in July. Responders reportedly exchanged over 11,000 messages across 11 Teams chats, and Microsoft has set a target of one-hour worldwide resolution plus plans for AI agents to aid diagnosis.

**Comments:** A major thread debates whether the outage stems from deep staff cuts and buyouts; one highly upvoted correction notes headcount has stayed roughly flat (~221k–228k) since 2022, and the CFO expects only ~5% uptake on buyouts. Many commenters blame culture and engineering quality rather than headcount — citing fragmented diagnostic tooling, Teams itself, legacy front-end code, and speculation that LLM-generated code contributed — while others argue the cuts will continue until the damage becomes undeniable. A recurring subthread notes that falling below IPO prices and "Code Red" are both unremarkable, and discusses chaos engineering and incident-response tooling.

## 28. [The KL Divergence Is Never Negative, Except in PyTorch](https://news.ycombinator.com/item?id=50629962) (↑70, 💬29)
**Article:** The arXiv paper documents that PyTorch's KL divergence implementations return negative values and large relative errors precisely where ML work needs accuracy most — comparing nearby distributions — across 8.5 million inputs, 18 closed-form KL families, and `F.kl_div` on CPU and GPU. Over 85% of FP32 scalar values near KL 1e-7 have at least 1% relative error and about 30% go negative at smaller divergences; raising precision does not fix it. Stable closed-form decompositions, compensated arithmetic, and analytic gradients eliminate over 97% of significant errors, affecting parameter fitting, Bayesian decisions, distillation, and GPT-2 circuit scores.

**Comments:** Commenters validate the finding and share related float pitfalls, including a `MAX(x, 0)` clamp failing on negative zero, with one noting IEEE 754 requires sqrt(-0) == 0. Much of the thread instead argues over the paper's LLM-generated prose — several call the writing "slop" or note AI-detector results, while others defend the title's phrasing and say the finding is significant and well covered. Others note the built-in KL is rarely used directly, that ML tolerates numerical slop, and that PyTorch has many lightly exercised buggy operations.

## 29. [The new set of problems for engineers to solve](https://news.ycombinator.com/item?id=50605361) (↑106, 💬81)
**Article:** Katelyn Lesse (who leads platform engineering at Anthropic) argues that multiagent systems — thousands of persistent agents working on research, discovery, and hardware design — create a new and exciting set of engineering problems. She identifies four areas: infrastructure (Kubernetes assumes stateless replicated apps, while agents are isolated, stateful, idle-heavy single instances), agent identity and authorization including on-behalf-of consent, security and isolation against untrusted code and prompt-injected agent-to-agent traffic, and monitoring with tamper-proof tracing and kill switches. Her conclusion is that engineers' skills are what will make these systems trustworthy and capable.

**Comments:** Many commenters push back hard on the framing: the listed problems are "plumbing," boring, and accidental complexity created by AI, and "software engineers should be excited" reads as tone-deaf given layoffs and burnout. Several note the author's employer gives her an agenda, and some dispute the premise that agent swarms are proven, while others share interview whiplash over expected AI usage and describe jobs reduced to reviewing endless agent output. Constructive threads discuss testing generated code via differential execution, sandboxing with read-only access to production, old-fashioned database-level permissions for agents, and pointers to zero-trust tooling like Octelium.

## 30. [Anthropic breaks below $83 IPO price](https://news.ycombinator.com/item?id=50627836) (↑271, 💬548)
**Article:** The Bloomberg article (paywalled; only a bot-check page was retrievable) reports that Anthropic's stock fell below its $83 IPO price in premarket trading, with commenters noting it dipped under $80 after the open. The piece appears to cover early post-IPO weakness in a broadly declining AI trade.

**Comments:** The dominant view is that breaking below the IPO price is ordinary and largely meaningless — most IPOs do this in the first 90 days, and Amazon, Meta, Netflix, and Tesla all fell after listing. Skeptics argue there is no moat against open-weight models like DeepSeek and GLM, that hyperscalers can subsidize tokens indefinitely, and that valuations aren't grounded in fundamentals; bulls counter that Anthropic raised the capital it needs for compute and could compound for years. Several threads mention insider selling, lockup schedules, and the overlap with a sector-wide AI selloff.

---
_Generated 2026-11-24 16:05 MDT_

---

## Recent Digests

- [Nov 24](./archives/2026/nov/hn-digest-2026-11-24.md)
- [Nov 23](./archives/2026/nov/hn-digest-2026-11-23.md)
- [Nov 22](./archives/2026/nov/hn-digest-2026-11-22.md)
- [Nov 21](./archives/2026/nov/hn-digest-2026-11-21.md)
- [Nov 20](./archives/2026/nov/hn-digest-2026-11-20.md)
- [Nov 19](./archives/2026/nov/hn-digest-2026-11-19.md)
- [Nov 18](./archives/2026/nov/hn-digest-2026-11-18.md)

[Full archive](./archives/) (196 issues)

_If you want more, explore the [archive folder](./archives/)._
