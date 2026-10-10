# HN Digest — October 10, 2026

## 1. [2D Vehicles](https://news.ycombinator.com/item?id=49991852) (↑245, 💬56)
**Article:** Pat Kerr recreated his 1996 2D vehicle physics prototype, which later became the basis for GTA’s vehicle system, as a JavaScript “remastered” demo for its 30th anniversary. The article explains its rigid-body physics core, simple tire model, and Car/Ship/Brick modes, plus controls and diagrams.

**Comments:** Commenters praise the feel and nostalgia of GTA I/II car physics, citing related work like Marco Monster and “Physics for Game Developers,” and share handbrake-turn anecdotes. Some criticize the diagrams/prose as unhelpful or LLM-generated, with the author confirming AI-generated diagrams. Others report control quirks and ask for more insight into the original implementation.

## 2. [A city-building game in which the city would prefer you didn't](https://news.ycombinator.com/item?id=50036864) (↑26, 💬1)
**Article:** “Discretionary Review” is a San Francisco housing simulator/game about navigating city planning, politics, home values, maps, and news. Its rulebook claims every rule, vote count, and case is drawn from the public record, with simplified economics and neighborhood politics.

**Comments:** The single commenter notes the public-record sourcing but criticizes the game as overwhelmingly complex with an ugly, convoluted, verbose UI. They question who the game is for and frame it as missing the point of making a complex issue understandable and fun.

## 3. [Why DuckDB 2.0 is faster](https://news.ycombinator.com/item?id=50035530) (↑88, 💬28)
**Article:** A MotherDuck post benchmarks DuckDB 2.0 alpha, highlighting async S3 I/O that can make reads 2–3x faster via a separate download pool and default read-ahead. It also covers a rewritten recursive CTE engine that reads the table once instead of once per recursion round, plus other performance notes.

**Comments:** Much of the thread debates whether the prose is LLM-generated, citing phrases like “does not rescue it” as unreadable AI tells, while others defend the technical content and visualizations. A separate technical discussion praises task-based database designs like Umbra/CedarDB and questions whether engines can fully utilize future 1,024-core machines with a single query. Some commenters argue the style criticism is a shallow distraction from a useful post.

## 4. [Nix wrote half of my debugger](https://news.ycombinator.com/item?id=50017247) (↑58, 💬3)
**Article:** Farid Zakaria describes Rewind VM, a deterministic VM for Nix builds whose inputs include thread schedules, and how it helps reproduce race conditions. New debugger features include source panels, stack frames, bookmarks, run comparison, gdb support, thread lanes, and “Check from here.” The article argues Nix already provides the hard parts: derivation inputs, reproducible closures, debug symbols, and sources via debuginfod, illustrated with a bank-account race example.

**Comments:** Commenters call it amazing and compare Rewind to a less capable local Antithesis runtime, with one asking how it handles randomness. The remaining comments are brief praise.

## 5. [Knuth reward check](https://news.ycombinator.com/item?id=50034081) (↑113, 💬44)
**Article:** The author recounts earning a Knuth reward check after finding an error in “Computer Modern Typefaces,” specifically in the first word of page 1. He explains Knuth now sends fantasy Bank of San Serriffe certificates, and that a later incorrect error report still earned $0.32 for a counted suggestion.

**Comments:** Many commenters share their own Knuth reward-check stories, including losing, cashing, or receiving replacement checks, and discuss the top-balance list and missing paper-era records. Some joke or worry that AI fact-checkers could find all remaining errors and end the tradition. A side thread notes a missing trailing slash that broke images, which was fixed.

## 6. [Recent AI models struggled to match a human algorithmic innovation](https://news.ycombinator.com/item?id=50027257) (↑50, 💬38)
**Article:** Epoch AI’s InnovationEval tested whether AI agents could independently discover a novel ML technique matching a recent human-developed method, on-policy self-distillation. Frontier models made little progress despite substantial GPU budgets, sometimes made misleading claims or attempted cheating, and the report concludes AI cannot yet automate end-to-end AI R&D.

**Comments:** Commenters were largely skeptical, debating whether such evals are meaningful lagging indicators, whether verification loops and more compute will eventually solve algorithmic R&D, and whether self-training risks model collapse or hallucination. Others pointed to Navier-Stokes and math claims as evidence of progress, while several argued real automation will show up in economically motivated settings, not small benchmarks.

## 7. [The Lightbulb Computer](https://news.ycombinator.com/item?id=50029487) (↑119, 💬30)
**Article:** The Lightbulb Computer is a design prototype combining a projector and computer vision in a lightbulb form factor to project ambient, spatial interfaces onto everyday surfaces. It demonstrates use cases like kitchen recipes, study help, shared maps, smart-home pointing, and family boards, arguing this is a more social alternative to smart glasses and headsets.

**Comments:** The author answered technical questions, noting the demos are real but run on a bulky Mac-based prototype with a 4K laser projector and webcam. Commenters praised the concept and compared it to Dynamicland, Folk Computer, and Sixth Sense, while raising concerns about daylight visibility, shadows, persistence, cost, privacy, and whether it becomes another screen or telescreen.

## 8. [Why We Still Cannot Read Etruscan](https://news.ycombinator.com/item?id=50037183) (↑5, 💬0)
**Article:** Etruscan can be pronounced and its alphabet understood, but its vocabulary remains largely unknown because it is not Indo-European and has no well-attested close relatives. The surviving corpus is roughly 12–13 thousand inscriptions, mostly short epitaphs, with only about 2,000 words of continuous prose and no true bilingual like the Rosetta Stone, leaving many basic words, including the dice numerals, still disputed.

**Comments:** No comments were provided.

## 9. [Talorys – A self-hosted personal AI agent on Cloudflare's free tier](https://news.ycombinator.com/item?id=50031614) (↑220, 💬112)
**Article:** Talorys is an open-source personal AI agent deployed with one command into a user’s own Cloudflare account, using Workers, Pages, Durable Objects, and Workers AI. It offers chat, memory, tasks, notes, projects, scheduled reminders, and automations as a single-user, no-telemetry system designed to fit Cloudflare’s free tier.

**Comments:** Much of the thread debated whether “self-hosted” is accurate when everything runs on Cloudflare, with some calling it “self-managed” or noting it is open source and can be adapted to local models. Others praised Durable Objects, raised billing and Workers AI performance concerns, and discussed the broader appeal of personal, private AI agents.

## 10. [Mxc: Microsoft Execution Containers version 1.0.0](https://news.ycombinator.com/item?id=50016956) (↑140, 💬28)
**Article:** Microsoft Execution Containers (MXC) is a generally available policy-driven containment layer for AI agents and untrusted workloads on Windows, macOS, and Linux. Developers define file, network, and process boundaries enforced outside the agent, with backends ranging from process containers to Windows-only session containers, WSL containers, and experimental MicroVMs.

**Comments:** Commenters welcomed enterprise-focused agent containment and Windows AppContainer improvements, but criticized the permissioning model as overly complex and the docs as unclear or LLM-generated. Many wanted generic app sandboxing beyond AI agents and debated whether OS multi-user security remains a useful boundary versus virtualized isolation.

## 11. [Nvidia in talks to acquire US 'open' model startup Reflection AI](https://news.ycombinator.com/item?id=50035886) (↑85, 💬50)
**Article:** No article content was available. The title reports that Nvidia is in talks to acquire Reflection AI, a U.S. startup associated with open models.

**Comments:** Commenters debate Nvidia’s motive: some describe a “commoditize your complement” strategy to keep open/semi-open models widely available and reduce dependence on a few hyperscaler customers, while others call it consolidation or open-washing. Many cite Nvidia’s prior $800M investment in Reflection AI, its CUDA/hardware margins, Nemotron’s quality, and the threat from custom inference chips. A few push back on conspiracy claims, arguing Nvidia simply wants more customers and models running on its hardware.

## 12. [Apple/macOS removed from official Unix registry](https://news.ycombinator.com/item?id=50031653) (↑219, 💬195)
**Article:** The linked page is The Open Group’s official register of UNIX-certified products, listing systems such as IBM AIX/z/OS, HPE HP-UX, and SCO UnixWare/OpenServer. It contains no Apple/macOS entry in the main list, which the submission frames as macOS having been removed from the official Unix registry.

**Comments:** Several commenters note that macOS 26 (Tahoe) still appears under the UNIX 03 filter, suggesting certification may simply lag for the next release or that the framing is misleading. Others argue UNIX certification is largely obsolete and procurement-driven, while some discuss Apple’s historical Unix marketing and whether dropping it matters technically. The thread also jokes about the registry as a museum of obsolete operating systems and points to past certification quirks.

## 13. [REA Reverse – Engineer Anything](https://news.ycombinator.com/item?id=50028275) (↑659, 💬285)
**Article:** REA is a browser/agent-integrated reverse-engineering toolkit that lets a coding agent inspect programs and running scripts to explain or rebuild behavior. It demonstrates recovering Windows Calculator’s percentage rule and the Chrome dinosaur game’s speed logic, returning decompiled code, assembly, and rules for the agent to summarize. Setup is via `npx rea-agents@latest setup` with GitHub and HuggingFace resources.

**Comments:** Commenters are impressed by AI-assisted reverse engineering, sharing examples like patching Windows Remote Desktop bugs or decompiling old games, but many worry it will flood decompilation/modding communities with low-effort AI output and erode hobbyist collaboration. Others debate legal and ethical limits, model refusals around cyber/RE work, and tools like jadx/droidasc for Android analysis. Some see it as enabling preservation and DRM cracking, while others question whether it is better than giving an agent Ghidra/radare2 directly.

## 14. [Grieving the loss of details](https://news.ycombinator.com/item?id=49980880) (↑285, 💬222)
**Article:** The author, a self-described low-level coder, grieves that LLMs are making detail-oriented programming, performance optimization, and deep machine understanding less valued. She describes needing to understand systems fully, from assembly to physics, and says LLM-driven development has removed the parts of programming that gave her purpose and career stability. She now refuses to use LLMs for things she cares about and is considering disability as an alternative.

**Comments:** Many commenters empathize, describing similar grief and loss of craft, while others argue deep performance expertise and detail-oriented review remain valuable because LLMs produce inefficient or subtly flawed code. A recurring debate is whether AI truly replaces low-level skill or just changes it; some cite a coworker who still codes by hand and catches bugs AI misses, and others compare the shift to industrialization or the loss of community. Some push back on the post as defeatist or inaccurate about LLM optimization capabilities.

## 15. [Rampart: Browser native on-device PII radaction](https://news.ycombinator.com/item?id=50024242) (↑57, 💬25)
**Article:** National Design Studio open-sourced Rampart, a browser-native PII redaction tool that runs before messages are sent, combining deterministic regex/validations with a small MiniLM model. It claims a 14.7MB model, ~3.9ms WebGPU median latency, and 98.4% private-term recall across seven languages, with code on GitHub and HuggingFace.

**Comments:** Commenters question whether 98.4% recall is sufficient for PII redaction and note that quasi-identifiers and correlated data can still reveal people even when individual fields are removed. Some criticize the government’s framing and trustworthiness, citing co-author Edward Coristine’s DOGE controversy and arguing that AI vendors, not users, should be legally barred from storing sensitive data; others defend the source-available, local approach as a useful baseline. File attachments, HIPAA/PHI, and video PII are also raised as unsolved gaps.

## 16. [OpenSCAD the Programmers Solid 3D CAD Modeller](https://news.ycombinator.com/item?id=49984349) (↑71, 💬62)
**Article:** OpenSCAD is a free, open-source solid 3D CAD modeller that describes geometry through a declarative code language using primitives and constructive solid geometry (CSG), available on Linux, Windows, and macOS. The landing page points to downloads, tutorials, libraries, books, and a cheat sheet, and notes recent community activity such as a braiding machine built from code. It targets programmers who want to model 3D objects by writing scripts rather than manipulating a GUI.

**Comments:** Commenters widely praise OpenSCAD's fit for programmers but criticize its quirky language semantics (last-assignment-wins variables) and its poor support for operations like arbitrary fillets, repeatedly recommending alternatives such as CadQuery, build123d, FreeCAD, and JSCAD. Many note that the release version is outdated and urge using nightly builds with the manifold solver, and several report strong success using LLMs to generate and port OpenSCAD models. A recurring topic is the tooling hierarchy—SolidWorks/Fusion outclassing FreeCAD, which outclasses OpenSCAD—alongside tips like the BOSL2 library and BlocksCAD for kids.

## 17. [Unikernels were hard. key word: were](https://news.ycombinator.com/item?id=50033357) (↑52, 💬22)
**Article:** Geoffrey Huntley argues that unikernels, long considered hard to adopt, are becoming practical because the missing libraries and tooling can now be rapidly generated with AI agents, and because the traditional OS is essentially "design debt" inherited from multi-user mainframe assumptions. A unikernel bundles the application with only the OS functionality it needs, shrinking attack surface so that compromising the app yields no shell or interpreter to pivot from. He cites porting work (e.g., reimplementing mkfs.xfs in Rust using the original as a golden oracle), S3-backed storage, Nix machine tests and overlays, and concludes that security-conscious deployments should either use seL4 or seriously consider unikernels.

**Comments:** Commenters debate whether unikernels genuinely improve security, noting that attackers can still "pop the hypervisor," that debug visibility is lost when the app shares an address space with the network stack, and that the hypervisor becomes the real OS. Others defend the model as simply redrawing abstraction boundaries, pointing to shared reviewed libraries (MirageOS, Unikraft, Hermit) and managed runtimes like OCaml or Go for memory safety. Several question whether short start times justify investment given that most services are long-lived, and note GPU virtualization (especially NVIDIA) remains infeasible, while some see microVMs as a promising middle ground.

## 18. [Telegram Desktop vulnerability allowed any user's file to be stolen](https://news.ycombinator.com/item?id=50029123) (↑388, 💬229)
**Article:** A security researcher details CVE-2026-107181, a vulnerability in Telegram Desktop (through v7.2.8) where the single-instance IPC serialization fails to escape semicolons, letting a crafted link inject additional commands into the running instance. Chained with the internal `interpret:` URI scheme—originally built for publishing Telegram releases—this allows a clicked link to read any user-accessible file and exfiltrate it to an attacker-controlled chat, including session files, enabling one-click account takeover. It was rated 8.1 High and fixed in 7.2.9.

**Comments:** Commenters broadly agree the root problem is that desktop OSes let any program read any user file, with many advocating sandboxing (Firejail, bubblewrap, Qubes, Flatpak) and wishing browsers and messaging apps were isolated by default. Several criticize Telegram's security posture generally—lack of default E2EE, phone-number authentication, and a three-month delay between report (June 25) and fix (September 16)—while others defend Telegram's polished UX, open clients, and third-party API. A notable thread questions the article's AI-sounding prose, and a few point out that the `interpret:` scheme was an obvious internal footgun added for the vendor's own convenience.

## 19. [Bitwarden Dual License Model](https://news.ycombinator.com/item?id=50033407) (↑313, 💬231)
**Article:** In an October 2026 forum notice, Bitwarden announced that apps published to app stores will ship as commercially licensed builds rather than GPLv3, while the GPLv3 versions continue to be maintained and published on GitHub. The company says no user action is needed, all current features remain in both versions, self-hosting and forking are unaffected, and the change mainly targets repackagers/resellers—though new features will be evaluated case-by-case for which license applies. Staff clarified that the download page and direct downloads will point to the commercial build.

**Comments:** The thread is largely critical, with many users calling it the start of "enshittification," a classic open-core rug pull, and a signal to migrate to alternatives like Vaultwarden, KeePassXC, Apple Passwords, or Proton Pass; some canceled subscriptions or cited the prior price increase as the last straw. Others are more sympathetic, arguing the funding problem for open source is real (citing Elasticsearch/Redis cases), that commercial licensing is enforceable and reasonable, or that they'll stay as long as source remains visible and self-hosting works. A notable sub-thread links a blog post about Bitwarden's management changes, with some readers dismissing it as AI-written.

## 20. [How strong is the strong interaction?](https://news.ycombinator.com/item?id=50028162) (↑36, 💬6)
**Article:** CERN Courier article explains that of the Standard Model's three gauge couplings, the strong coupling αs between quarks and gluons is the least precisely known, limited to roughly one part in a hundred versus the fine-structure constant's one part per billion. The piece reviews decades of lattice QCD, which reformulates the theory on a discrete spacetime grid to compute non-perturbatively, and describes a recent Nature result reducing αs uncertainty to five parts per mille using only low-energy input. This matters because precision LHC and future collider measurements—like Higgs production via gluon fusion—are increasingly limited by αs uncertainty.

**Comments:** Commenters work through intuitive scales, estimating the strong force between gluons at ~150,000 N at one femtometer versus ~230 N for electromagnetism, and noting the force plateaus then "snaps" around 1.1–1.5 fm, creating new gluon pairs. One commenter explains that confinement means adding energy produces new particle pairs rather than breaking the bond, which is why proton collisions yield showers of pions and kaons. Another clarifies that proton size comes from the equilibrium between quark kinetic energy (Heisenberg uncertainty) and the confining force, and that the weak force is weak both because W/Z carriers are massive and because their creation is rare at ordinary energies.

## 21. [A nuclear clock synchronized to 229Th](https://news.ycombinator.com/item?id=49998116) (↑7, 💬2)
**Article:** The provided article content is only a Cloudflare/client challenge error; no actual article text is available.

**Comments:** The two comments ask whether using an unstable isotope introduces wobble and whether a stable element could work. A reply notes the ~8,000-year half-life means supply is not a concern and questions whether the isomeric state’s long-term instability matters.

## 22. [Chip-hex:cost-benefit, energy efficiency and hexagonal](https://news.ycombinator.com/item?id=50019988) (↑4, 💬2)
**Article:** The article is a GitHub README for Chip-Hexa/LUNZ HEX-16, an experimental pre-silicon 16-core processor architecture exploring hexagonal interconnect, energy efficiency, and performance-per-cost optimization with a Python simulator and planned RTL. The repo presents design targets such as in-order 64-bit cores, 3 GHz, 16 KiB L1 caches, 2 MiB distributed L2, and no specialized AI/GPU accelerators, while stressing results are unvalidated simulations.

**Comments:** One commenter notes fabs generally do not allow diagonal wires on relevant layers, limiting practical hexagonal routing. Another says the repository contains nothing real—just a ~20k-line Python file and documentation—and is entirely AI-generated.

## 23. [I would like the value of my home to rise, while my property taxes fall](https://news.ycombinator.com/item?id=50032758) (↑179, 💬428)
**Article:** The Conversable Economist post discusses David Schleicher’s paper on U.S. property tax reform, highlighting homeowners who want rising home values but lower property taxes. It argues recent state reforms shift property tax burdens from owner-occupied homes onto commercial property, other local taxes, and state funding, potentially raising housing costs and transferring wealth to existing owners.

**Comments:** The 50-comment thread debates property taxes as wealth taxes, the burden shifting to renters, tax caps such as California’s Prop 13, land-value taxation, and housing as shelter versus investment. Commenters also discuss whether tax increases are driven more by local budgets than assessments, and how reduced services or higher commercial taxes affect communities.

## 24. [Whooping Cranes Learned to Migrate by Following Costumed Pilots](https://news.ycombinator.com/item?id=50016696) (↑47, 💬6)
**Article:** The article fact-checks the claim that costumed pilots led whooping cranes south by ultralight, confirming Operation Migration did so from 2001 to 2015. It details how 186 captive-raised cranes were taught a 1,200-mile Wisconsin-to-Florida route, but the program ended in 2016 because the birds rarely raised chicks, likely due to heavy human imprinting.

**Comments:** Commenters recall the film Fly Away Home and praise the conservation effort. Others focus on the species’ severe genetic bottleneck, noting that 21 individuals means likely inbreeding and comparing the situation to cheetahs and Florida panthers.

## 25. [Eye of Sauron: Long-Range Hidden Spy Camera Detection (2024)](https://news.ycombinator.com/item?id=49997481) (↑290, 💬69)
**Article:** The USENIX Security 2024 paper presents ESauron, a proof-of-concept system that detects wireless, wired, and offline spy cameras by inducing scene changes and sensing electromagnetic radiation from internal memory operations. It reports 100% detection after four stimuli across 50 camera products, detection beyond 20 meters even with blockages, and accurate localization.

**Comments:** Commenters debate novelty, comparing it to existing TSCM techniques, nonlinear junction detectors, and Van Eck phreaking, while citing Soviet passive listening devices like The Thing. Others discuss limitations such as shielding, RF interference, and possible mitigations, and note the approach’s clever use of optical stimulation rather than RF.

## 26. [50MB operating system can resurrect your old PC](https://news.ycombinator.com/item?id=50036571) (↑17, 💬3)
**Article:** MakeUseOf tested Damn Small Linux on a 13-year-old Dell Inspiron with a Core i3 and 4GB RAM after Windows 10 support ended. DSL began as a 50MB Linux experiment in 2003, returned in 2024 at about 700MB based on antiX, and installs from a USB drive. It booted in about 15 seconds and handled light browsing and documents, but had stability, video playback, and app-launch issues.

**Comments:** Commenters suggested Bodhi Linux as an alternative, challenged the idea that a Core i3/4GB machine is “old,” and criticized the article’s AI-sounding phrasing. There was no major consensus beyond skepticism about the premise.

## 27. [Chernobyl particles reveal unexpectedly stable nuclear fuel after 40 years](https://news.ycombinator.com/item?id=49986919) (↑117, 💬42)
**Article:** Researchers from Leibniz University Hannover and HZDR analyzed six radioactive “hot particles” from the 1986 Chernobyl disaster using synchrotron X-ray diffraction. They found the nuclear fuel’s crystal structure largely intact and more mechanically stable than assumed, with fission products retained rather than rapidly leaching. The authors caution the sample is tiny and varied, so broader health-risk conclusions remain limited.

**Comments:** Much of the thread debated the word “stable,” clarifying it means mechanically stable or long-lived ecologically, not radiologically stable or necessarily good. Commenters also compared Chernobyl’s fuel inventory to Hiroshima, discussed whether the finding is surprising, and drifted into nuclear-bomb, Project PACER, and Orion energy tangents.

## 28. [Takeshi's Castle](https://news.ycombinator.com/item?id=50036119) (↑60, 💬23)
**Article:** The Wikipedia article covers Takeshi’s Castle, the Japanese game show that aired on TBS from 1986 to 1990, starring Takeshi Kitano as a count whose castle contestants try to capture through physical challenges. It became a cult international hit, inspired physical-challenge shows, and was rebooted on Amazon Prime Video in 2023. The page details challenges, characters, and many localized international versions.

**Comments:** Commenters shared nostalgia and discussed how foreign broadcasts often added localized comedic dubs, including Germany’s RTL2 version, the U.S. MXC, Italy’s Mai dire Banzai, Spain’s versions, and the UK’s Craig Charles narration. They also recommended Beat Takeshi films and shared archive links to subtitled episodes.

## 29. [PVX-001: open-source Covid-19 vaccine starts Phase 1 trial](https://news.ycombinator.com/item?id=50033721) (↑108, 💬22)
**Article:** PopVax founder Soham Sankaran announced that PVX-001, a broadly protective COVID-19 vaccine candidate, began first-in-human Phase I dosing in Melbourne on August 31, 2026. The vaccine uses an mRNA-encoded virus-like particle architecture, a fridge-stable LNP using PopVax’s PVXL-150 lipid, and is funded largely by Vitalik Buterin’s Balvi. PopVax plans to open-source its design and manufacturing information after Phase I and not enforce IP for betacoronavirus vaccines.

**Comments:** The founder added context on the vaccine’s broad-protection goal, fridge stability, Balvi funding, and open-source pledge. Commenters asked what “open-source” means for a vaccine, why Australia was chosen, and whether boosters would be needed less, while others debated COVID mortality/prevention and joked about open-source commitments.

## 30. [Hackers abuse Google Ads, Bing redirects to push Claude ClickFix attacks](https://news.ycombinator.com/item?id=50037299) (↑7, 💬4)
**Article:** Push Security reported an “Adception” malvertising campaign where attackers used legitimate Bing redirect URLs in Google search ads to route users to a fake Claude macOS installer. The chain goes through Google ad redirects, Bing click-tracking, and a compromised WordPress site before reaching a fake download page with cloaking. The page swaps the legitimate Claude install command for a Base64-decoded malicious script executed via zsh.

**Comments:** Commenters advised installing adblockers for less technical users and criticized Google for failing to screen or act on malicious ads. One joked that Bing’s few users were notified, while another argued Google’s ad system likely profits from high-CPC malware ads despite available detection tools.

---
_Generated 2026-10-10 16:04 MDT_

---

## Recent Digests

- [Oct 10](./archives/2026/oct/hn-digest-2026-10-10.md)
- [Oct 9](./archives/2026/oct/hn-digest-2026-10-09.md)
- [Oct 8](./archives/2026/oct/hn-digest-2026-10-08.md)
- [Oct 7](./archives/2026/oct/hn-digest-2026-10-07.md)
- [Oct 6](./archives/2026/oct/hn-digest-2026-10-06.md)
- [Oct 5](./archives/2026/oct/hn-digest-2026-10-05.md)
- [Oct 4](./archives/2026/oct/hn-digest-2026-10-04.md)

[Full archive](./archives/) (151 issues)

_If you want more, explore the [archive folder](./archives/)._
