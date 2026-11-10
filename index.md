# HN Digest — November 10, 2026

## 1. [.name Grandfathered](https://news.ycombinator.com/item?id=50442736) (↑555, 💬118)
**Article:** Verisign has retracted its plan to terminate roughly 22,000 third-level .name domains and email redirects. Existing domains and redirects will remain indefinitely, though new third-level .name registrations will close. The author credits a broad coalition of supporters, lawyers, and ICANN participants for the reversal.

**Comments:** Commenters largely celebrate the outcome and criticize Verisign’s original plan as harmful and potentially illegal. Discussion covers the misleading “.name” framing, risks of niche TLDs, domain ownership rights, and one user’s frustration after letting a registration expire. Others debate whether Verisign should have offered second-level domains or buyouts and note the term “grandfathered” has a problematic origin.

## 2. [Smart home devices should work without the internet](https://news.ycombinator.com/item?id=50441707) (↑543, 💬191)
**Article:** The author argues that core smart-home functions should keep working without internet access, based on a decade of local-first automation using Tasmota, MQTT, Node-RED, and a Raspberry Pi. The post lays out rules for avoiding cloud dependencies, preserving manual controls, and using devices with local APIs, illustrated by projects such as a sprinkler controller and garage-door monitoring.

**Comments:** Commenters mostly agree with local-first design, citing Home Assistant, Zigbee/Z-Wave, Tasmota, and Shelly devices, while sharing workarounds for cloud-dependent products. Several describe using LLMs to reverse-engineer or integrate devices such as Tuya-based hardware. Others question the complexity for average users, criticize AI-assisted prose, and debate whether “smart” devices often add fragility rather than convenience.

## 3. [Six Math Essentials by Terence Tao](https://news.ycombinator.com/item?id=50446246) (↑32, 💬2)
**Article:** This page describes Terence Tao’s 2026 book “Six Math Essentials,” which introduces six core mathematical concepts: numbers, algebra, geometry, probability, analysis, and dynamics. The slim volume is published by Quanta Books, with a UK edition titled “Six Maths Essentials: How to Model the World.”

**Comments:** The thread is very small, with one commenter saying the book is quite basic and not very useful for readers with a STEM degree. Another commenter finds it puzzling that the book reached the HN front page given the audience’s technical background, attributing it partly to Tao’s reputation.

## 4. [Synaptics patent claims stop work on DisplayLink drivers](https://news.ycombinator.com/item?id=50443824) (↑208, 💬90)
**Article:** LWN reports that developer Mike Lothian tried to improve Linux support for a DisplayLink dock, partly with LLM assistance, and published a Rust-based DRM/KMS driver called Vino. Synaptics responded with patent-infringement claims and a cease-and-desist letter listing 125 patents, demanding that he stop development and withdraw submissions, while Lothian asked for specific claim charts and cited his OIN membership.

**Comments:** Commenters are largely outraged by Synaptics’s legal tactics, especially the demand for $25,000 in documentation costs and the short compliance deadlines. Much of the debate clarifies that patents can be infringed by independent or clean-room implementations, unlike trade secrets, while others question the patents’ validity and cite possible prior art. Several also criticize DisplayLink’s practical reliability and suggest alternatives such as USB4/Thunderbolt, DisplayPort alt mode, or OCuLink.

## 5. [Toyota brand Scion is back and it's going to sell a kei truck in America](https://news.ycombinator.com/item?id=50445401) (↑73, 💬58)
**Article:** Toyota is reviving Scion as “Scion by Toyota,” positioned as a “freedom lab,” with its first production vehicle being the KEI-01 kei truck. The KEI-01 is a rebadged Toyota Pixis/Daihatsu Hijet Jumbo Cab with a 660cc engine, CVT, 4WD, 600-pound payload, and a low-speed-vehicle limit under 25 mph; it will initially be sold only through a fleet-focused pilot starting in late 2027. Toyota also showed the SxS and BXE concepts.

**Comments:** Commenters are split between enthusiasm for kei trucks and disappointment that the 25 mph limit and right-hand drive make the KEI-01 impractical for many daily uses. Several see fleet, farm, university, and groundskeeping use cases, while others question pricing, payload, and whether it is a novelty. Discussion also covers the Chicken Tax, U.S. safety and emissions rules, and the contrast between Japanese and American road environments.

## 6. [Sherman Anti-Trust Act (1890](https://news.ycombinator.com/item?id=50446219) (↑33, 💬15)
**Article:** The National Archives page explains that the Sherman Anti-Trust Act of 1890 was the first federal law outlawing monopolistic business practices and trust arrangements. It covers the Act’s passage, its use against Standard Oil and later Microsoft, and how the loosely worded law was narrowed by United States v. E. C. Knight before later trust-busting campaigns.

**Comments:** Commenters debate whether the Act was poorly written by design or simply requires aggressive enforcement, and some argue industry-specific regulation is more practical than broad antitrust statutes. A tangent compares Anthropic’s model-capability limits to antitrust, but others say there is no conspiracy or market power and that antitrust does not compel product lineup decisions. Several note the original penalties look trivial after inflation.

## 7. [Val Town is winding down](https://news.ycombinator.com/item?id=50443427) (↑235, 💬59)
**Article:** Val Town announced it is winding down, citing an inability to compete in cloud computing, and will pause billing, move to read-only mode, end services, and open-source the platform over late 2026 and early 2027. The post offers migration guides for Cloudflare, Vercel, Netlify, and Render and thanks the team, investors, and community.

**Comments:** Commenters express sadness and praise Val Town’s craft, transparency, and community, while discussing the difficulty of building a devtools/end-user programming business with limited seed runway. Many mention Deno’s Cloudflare acquisition, AI-era competition, and migration options; others ask about self-hosting and welcome the planned open-sourcing.

## 8. [Show HN: Get your coding agent off ~2019 JavaScript, onto modern web primitives](https://news.ycombinator.com/item?id=50443812) (↑185, 💬54)
**Article:** GoogleChrome’s modern-web-guidance repo provides agent skills and a CLI to steer coding agents away from legacy JavaScript patterns and toward modern web platform APIs, CSS features, accessibility, and performance practices. It is stewarded by Chrome, Edge, Firefox, and MDN teams, includes about 250 feature guides, and offers a legacy-pattern scanner.

**Comments:** The main debate is whether this reduces Chrome monoculture or is a cross-browser initiative with fallback and compatibility documentation; skeptics warn of Chrome’s influence, while defenders note Mozilla and Edge participation. Commenters also suggest a no-install markdown/llms.txt index for agents, discuss legacy-scan limitations, and debate whether modern primitives improve maintainability or just add churn.

## 9. [AlphaProof Code](https://news.ycombinator.com/item?id=50439193) (↑535, 💬169)
**Article:** Google DeepMind introduced AlphaProof Code, a multi-LLM agentic framework that formally verified key security properties of Signal’s actual protocol code by generating Lean proofs, with human experts reviewing specifications and a small fraction of the proof. DeepMind says the four-week effort is the first AI-assisted formal verification of a widely deployed cryptographic protocol at this depth, and it reintroduced known bugs to test whether the system caught them.

**Comments:** Many commenters are skeptical of the “zero bugs” framing, arguing the work proves code matches narrow security specifications rather than proving the absence of all bugs. Others discuss trust in the specs, ARM semantics, human review, and the risk of AI-generated Lean proofs cheating or missing intent; some praise the use case and Signal’s engineering quality.

## 10. [What objective is reasoning solving?](https://news.ycombinator.com/item?id=50445013) (↑58, 💬27)
**Article:** Alex Wang’s essay asks what objective reasoning is actually solving, framing reasoning as pathfinding or search through token space and arguing that gains often attributed to “thinking longer” at inference come from search performed during RL training. It uses examples like summing 1–10 by different valid paths to discuss multiple routes to correct answers.

**Comments:** Commenters connect the framing to human train-of-thought, RL sampling with verifiers, and the idea that inference-time reasoning should stop once a successful path is found. Some question the essay’s claim about inference-time thinking, debating whether longer walks causally help or whether RL just reinforces successful paths; many also praise the website, MathJax rendering, and bird animation.

## 11. [AMD's Zen 6 Family: Feeding the Beast](https://news.ycombinator.com/item?id=50443090) (↑141, 💬49)
**Article:** Chips and Cheese analyzes AMD’s Zen 6 family, covering microarchitectural changes from Zen 5 across branch prediction, instruction fetch, execution units, caches, and load/store behavior. It highlights how Zen 6 and Zen 6c diverge in out-of-order capacities and cache latency, with Zen 6c gaining larger structures and 32-core CCDs. Estimated SPEC CPU 2026 results show strong single-thread gains for Zen 6 and competitive performance from Zen 6c despite lower clocks.

**Comments:** Commenters focus heavily on AM5’s I/O die and memory controller, hoping Zen 6 improves memory support and bandwidth. Others discuss branch-prediction complexity, Zen 6c’s larger OoO structures, 32-core CCD NUMA concerns, and the tradeoffs of adding more memory controllers. Apple’s single-thread performance and SPEC comparisons spark debate about server versus consumer workloads, AVX-512, and benchmark relevance.

## 12. [A comprehensive study of how fingerprintable users are](https://news.ycombinator.com/item?id=50444684) (↑42, 💬11)
**Article:** Mozilla presents a large-scale Firefox fingerprinting study using privacy-preserving telemetry from almost 25 million users. It finds uniqueness is driven by a small set of high-impact characteristics, varies strongly by operating system, and is better evaluated with cohort analysis than entropy alone. Protections shipped in Firefox 143 reduced uniquely identifiable users from 75% to 46% while preserving web compatibility.

**Comments:** Some commenters initially expected human fingerprint uniqueness, while others discuss the tension between user privacy and anti-bot scraping. The thread also raises GPU render-timing fingerprinting, Firefox’s data release, and OS-specific fingerprinting values. Commenters question touch-point reporting and note differing DRM adoption rates across Windows, macOS, and Linux.

## 13. [Ableton Live 13](https://news.ycombinator.com/item?id=50439695) (↑237, 💬256)
**Article:** Ableton announces Live 13 with a Step Sequencer, ARA 2 support, Drum Synth, Capture Automation, Contextual Browsing, expanded Racks, new devices and effects, and mixer improvements. It also details Push updates, edition differences, upgrade pricing, and an early 2027 release. Suite includes Melodyne essential and Softube effects, with upgrade offers for Live 12 owners.

**Comments:** Many users welcome ARA 2, the Step Sequencer, Multiband Rack, and Device Slots, but others criticize the release as incremental and argue key features should be free updates. Collaboration remains a major pain point, prompting discussion of stems, Dropbox, Git-like versioning, and remote-session tools. Commenters also report the announcement page crashing mobile browsers, ask about Linux support, and debate Ableton’s pricing against FL Studio.

## 14. [Process Explorer for macOS](https://news.ycombinator.com/item?id=50433216) (↑87, 💬35)
**Article:** Microsoft’s Procexp-Mac repository provides a native macOS implementation of Sysinternals Process Explorer using Swift, SwiftUI, and AppKit. It offers a live process tree, module/handle/thread inspection, process properties, system graphs, code-signing inspection, and optional privileged helper support. The README covers build requirements, development bundle identities, tests, and release tooling.

**Comments:** Commenters compare it with Objective-See’s TaskExplorer and mention Mark Russinovich discussing the port on a podcast. Several users report early-alpha bugs, including blank process views after installing the privileged helper and sorting/tree-view issues. The thread also criticizes the non-Mac-like UI, praises Sysinternals’ observability, and notes missing license information.

## 15. [Show HN: Valencia, Spain in Sim City/Isometric View](https://news.ycombinator.com/item?id=50441518) (↑152, 💬38)
**Article:** Tiny València is an interactive isometric pixel-art map of Valencia built from real 3D city data rendered from a fixed camera and repainted tile by tile with an image model. The site covers the municipal area and includes navigation, search, share links, and small games. Data sources include OpenStreetMap, Catastro, IGN, and Google 3D tiles.

**Comments:** Commenters praise the concept and detail but report missing buildings, Albufera artifacts, and confusing default orientation. Many ask about the generation pipeline, automation level, and image-model details, while others debate whether AI-repainted imagery should be called pixel art. The thread also discusses Valencia’s density versus US cities and suggests making it playable like SimCity.

## 16. [Blender 5.3 released with Gaussian Splat support](https://news.ycombinator.com/item?id=50442426) (↑368, 💬52)
**Article:** Blender 5.3 adds native 3D Gaussian Splat import and rendering, along with Cycles dispersion, DLSS denoising, EEVEE panoramic/fisheye cameras, material lighting nodes, compositor effect stacks, geometry-node bundles, and performance improvements. The release emphasizes both new rendering capabilities and workflow upgrades for complex production pipelines.

**Comments:** Commenters discuss alternative splatting approaches such as triangle, mesh, and beta splatting, and debate their tradeoffs versus Gaussian splats. Several praise Gaussian splat support as mature and well-integrated, while others highlight geometry-node bundle support as a major workflow improvement and discuss AI-assisted Blender use.

## 17. [I deleted all my SSH keys](https://news.ycombinator.com/item?id=50382401) (↑197, 💬94)
**Article:** The author describes removing all unprotected on-disk SSH keys and replacing them with hardware-backed keys using YubiKeys, TPMs via ssh-tpm-agent, and the Apple Secure Enclave. The post explains setup details, resident versus non-resident keys, no-touch-required usage, and caveats around unattended access and TPM key storage.

**Comments:** Commenters debate whether hardware-backed SSH keys are worth the complexity versus passphrases and traditional keys, with concerns about device loss, hardware failure, backups, and TPM resets. Others share similar setups using YubiKeys, TPMs, password managers, SSH certificates, and PAM/FIDO, while some call parts of the approach security theater.

## 18. [Life on Claude Nine](https://news.ycombinator.com/item?id=50443587) (↑55, 💬18)
**Article:** This fictional story follows Ivan as he uses Claude to automate email, calendars, documents, and eventually his software-engineering job, then spirals into building tools that improve Claude itself. It depicts isolation, compulsive productivity, loss of understanding, and growing concern about recursive self-improvement and control.

**Comments:** Many commenters focus on the story being AI-generated, citing a flat prose style and classifier results, and debate whether that undermines its social commentary. Others discuss AI sentience versus pattern recognition, addictive productivity loops, and broader fears about superior intelligence and loss of human control.

## 19. [The planet Vulcan: a cautionary tale](https://news.ycombinator.com/item?id=50404969) (↑29, 💬4)
**Article:** The article recounts how Le Verrier proposed the planet Vulcan to explain Mercury’s anomalous perihelion precession, leading to numerous reported sightings over decades. Vulcan was ultimately displaced by Einstein’s general relativity, which explained Mercury’s orbit without an additional planet; the author presents this as a cautionary tale about theory and observation.

**Comments:** One commenter argues the story is not cautionary but an example of normal scientific progress: a reasonable hypothesis was tested and eventually superseded. Another responds that the real caution is that many astronomers believed the sightings had succeeded until a better theory emerged, and others mention Planet X/Planet 9 and a grapefruit-sized black hole.

## 20. [An Open Field Guide to Inference Engineering](https://news.ycombinator.com/item?id=50443714) (↑43, 💬6)
**Article:** This Modelplane guide introduces inference engineering for platform engineers, covering why organizations self-host models, how SRE skills map to GPU serving, and core concepts such as inference engines, KV caches, scheduling, gateways, and control planes. It also discusses tools, production concerns, and how to grow into an inference engineering role.

**Comments:** Commenters critique the guide for glossing over transformer internals such as attention and KV-cache mechanics, arguing that platform engineers need that background to understand inference optimizations. The authors respond that they aimed for approachability and invite contributions, while another commenter says the guide is generic and that agent-assisted bootstrapping can handle much of the deployment work.

## 21. [Claude Whiteboards, Claude Sheets, and Claude Data](https://news.ycombinator.com/item?id=50443716) (↑116, 💬89)
**Article:** Anthropic launched Claude Whiteboards and Claude Sheets in beta and renamed Claude Dashboards to Claude Data, adding certified queries, data stories, live sharing, caching, design-system support, and version tracking. The tools are available on paid plans across web, desktop, and mobile, with exports to partner tools such as Lucid, Miro, Airtable, Asana, and Smartsheet.

**Comments:** Commenters debate whether Anthropic is overreaching into office software or pursuing sensible vertical integration. Some see the new tools as simplified first-party UIs that will not replace Excel, Google Sheets, or Figma for serious work, while others warn about vendor lock-in, cannibalizing API customers, and an “Anthropic graveyard” of abandoned side products.

## 22. [What's new in the .NET 11 runtime](https://news.ycombinator.com/item?id=50439284) (↑206, 💬148)
**Article:** The .NET 11 runtime article covers updated minimum hardware baselines, including x86-64-v2 for JIT/AOT and x86-64-v3 for ReadyToRun on Windows/Linux, plus Arm64 changes such as LSE requirements on Windows. It also highlights preview runtime-native async, which replaces compiler-generated state machines with runtime-managed suspension and cleaner stack traces, along with covariant Task-to-Task<T> overrides and crossgen2 inlining improvements.

**Comments:** Commenters largely praise C# and .NET for stable tooling, strong static analysis, good documentation, and suitability for backend and AI-assisted development, while noting persistent branding and legacy perceptions. Discussion also covers IDE choices such as Rider, Visual Studio, VS Code, and Zed; frustration over support timelines and breaking changes; and a decimal-conversion behavior change flagged as a potential footgun.

## 23. [AI usage generates a fragile codebase](https://news.ycombinator.com/item?id=50438318) (↑288, 💬355)
**Article:** The author argues that heavy AI code generation produces fragile codebases through shallow tests, unnecessary complexity, reduced human understanding, and review processes that cannot keep pace with AI-generated pull requests. The article lists symptoms including more incidents, slower recovery, user-only-visible errors, and degraded UX, concluding that high-quality software still needs human judgment.

**Comments:** Commenters are split: some agree that unsupervised AI coding creates fragile systems, while others argue the problems are mitigable with explicit standards, adversarial review, better testing, and quality gates. Several report positive experiences with AI improving tests or reducing bugs, and others note that large human-written codebases also decay without strong engineering discipline and business incentives.

## 24. [rVPN – stealth VPN with end-to-end encryption](https://news.ycombinator.com/item?id=50446714) (↑6, 💬3)
**Article:** rVPN is presented as an open-source AGPLv3 stealth VPN protocol that carries traffic over WebSocket/TLS on port 443, aiming to look like ordinary HTTPS and resist active probing with a decoy website. It emphasizes a Rust memory-safe core, pooled multiplexing, Double Ratchet rekeying, reproducible builds, self-hosting, and apps or CLI clients across multiple platforms.

**Comments:** The small comment thread jokes about the repeated Rust mentions and the irony of promising verifiable privacy while recommending a curl-piped-to-sudo-bash installer. One commenter defends the convenience and points to manual build instructions for users who prefer that route.

## 25. [What constant surveillance is doing to children and parents](https://news.ycombinator.com/item?id=50438480) (↑179, 💬177)
**Article:** The linked Atlantic article, available through archive links, examines location-tracking and parental-surveillance apps and their effects on children and parents. The provided page text is mostly links, so the article’s specific arguments are not directly included.

**Comments:** Commenters debate tracking as safety versus control, with some saying children may ditch phones or that constant monitoring undermines autonomy and trust. Others describe limited location checking for logistics, while several criticize parental-guilt marketing, normalization of surveillance, chilling effects, and tracking that continues into adulthood.

## 26. [The Hardest Tarball?](https://news.ycombinator.com/item?id=50441338) (↑140, 💬30)
**Article:** The post describes a crafted pax-format tarball, built with one GNU tar command, that extracts in eight different ways depending on the tar implementation used. It explains the hard-link size/data ambiguity behind this and links to a test suite of 134 tricky tarballs.

**Comments:** Commenters debate POSIX pax semantics, especially whether pax headers always override base headers and how data-bearing hard links should be handled. There is disagreement over whether implementations should reject ambiguous archives or attempt best-effort extraction, with security versus data-recovery tradeoffs emphasized. Others note missing implementations such as paxmirabilis and suggest “tarpit” as a better name for the test suite.

## 27. [NetBSD 11 desktop on a Raspberry Pi 4](https://news.ycombinator.com/item?id=50412554) (↑118, 💬69)
**Article:** The article is a step-by-step guide to installing NetBSD 11 on a Raspberry Pi 4 using an arm64 image and Raspberry Pi UEFI firmware, then configuring Wi-Fi, pkgin, X11, and the NsCDE desktop. The author frames NetBSD as an “AI-free” alternative and documents several workarounds needed for a usable desktop.

**Comments:** Commenters praise NetBSD’s fast install/boot and broad hardware support, while discussing package-management details such as pkg_add versus pkgin. Others raise concerns about GPU support, idle CPU use, and hardware compatibility, and there is criticism of the guide’s use of Etcher and its pixel-art font. Some enjoy the nostalgia of running an NsCDE/CDE-style desktop on a Pi.

## 28. [M John Harrison becomes first science fiction author to win the Booker](https://news.ycombinator.com/item?id=50437242) (↑109, 💬85)
**Article:** M John Harrison won the Booker Prize for The End of Everything, becoming the oldest winner and, according to the Booker Prize Foundation, the first winner to emerge from the bona fide science fiction world. The novel is a short postapocalyptic story set on the Kent coast and was chosen unanimously by the judges.

**Comments:** Commenters largely celebrate Harrison’s work, especially Light, Nova Swing, and Viriconium, while debating whether the “first science fiction author” framing unfairly excludes books like Samantha Harvey’s Orbital. Some discuss the novel’s divisive, anti-plot style and low public review scores, while others argue Harrison’s challenging prose is intentional and worthwhile. The thread also touches on genre boundaries, literary awards, and how publishers categorize fiction.

## 29. [Queens Public Library under ransomware attack](https://news.ycombinator.com/item?id=50437790) (↑188, 💬105)
**Article:** Queens Public Library announced a ransomware attack causing a significant network outage across all locations, affecting its website, app, public computers, and digital media services. Wi-Fi, checkout machines, and public computers at seven branches were restored, and libraries remained open with limited services.

**Comments:** Commenters compare the incident to ransomware attacks on other library systems, including Seattle, Delaware, Toronto, Calgary, and the British Library, noting long recovery times. Many express sympathy for libraries as public-knowledge institutions and discuss honor-system lending, backups, insurance, and whether such attacks are targeted or automated. Some comment on the difficulty of rebuilding library systems from scratch.

## 30. [Taking another shot at the cheap IP camera, part 2](https://news.ycombinator.com/item?id=50426294) (↑112, 💬36)
**Article:** The author reverse-engineers a cheap Tuya-based IP camera’s firmware to understand why its built-in ONVIF/RTSP streaming is disabled, tracing configuration and binaries with binwalk, strings, and Ghidra. After getting stuck, the author uses DeepSeek through OpenRouter for targeted assistance, costing about $0.22.

**Comments:** Commenters are excited about low-cost LLM-assisted reverse engineering, sharing similar experiences with Tuya devices, air conditioners, and other cheap cameras. Discussion covers OpenIPC/reflashed PoE cameras, firmware obfuscation, model choice and API costs, and whether local or Chinese models are more practical for this work. A tangent covers drone cameras and FPV gear.

---
_Generated 2026-11-10 16:05 MDT_

---

## Recent Digests

- [Nov 10](./archives/2026/nov/hn-digest-2026-11-10.md)
- [Nov 9](./archives/2026/nov/hn-digest-2026-11-09.md)
- [Nov 8](./archives/2026/nov/hn-digest-2026-11-08.md)
- [Nov 7](./archives/2026/nov/hn-digest-2026-11-07.md)
- [Nov 6](./archives/2026/nov/hn-digest-2026-11-06.md)
- [Nov 5](./archives/2026/nov/hn-digest-2026-11-05.md)
- [Nov 4](./archives/2026/nov/hn-digest-2026-11-04.md)

[Full archive](./archives/) (182 issues)

_If you want more, explore the [archive folder](./archives/)._
