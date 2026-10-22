# HN Digest — October 22, 2026

## 1. [Quad9 (DNS Resolver) to Exit France](https://news.ycombinator.com/item?id=50195959) (↑820, 💬305)
**Article:** Quad9 says a French court ruled for beIN and ordered it to block DNS resolution of certain domains for users in France, with penalties reduced from €580,000 to €1,000 per day. Quad9 argues recursive DNS is neutral, geoIP blocking is technically and legally unreliable, and global blocking would improperly extend a French ruling worldwide, so it will withdraw service from France on November 24.

**Comments:** Quad9’s CTO clarified that the service will likely geoIP-block French users entirely rather than selectively block domains, because complying with domain blocking would concede that DNS resolvers are appropriate censorship points. Commenters largely criticized the court and rights holders, cited Cisco’s earlier exit from France, debated the technical consistency of geoIP blocking, and suggested donations, boycotts, or self-hosted DoH/DoT alternatives.

## 2. [OpenShell – A safe, private runtime for fleets of autonomous AI agents](https://news.ycombinator.com/item?id=50198675) (↑220, 💬116)
**Article:** NVIDIA’s OpenShell is presented as a safe, private runtime for autonomous AI agents, enforcing file, syscall, and network access at the kernel level inside sandboxes. It also uses formal verification to flag risky policy changes, injects credentials only for approved endpoints, and offers SDKs, gateways, Kubernetes deployment, and optional telemetry.

**Comments:** Commenters debated the marketing claim that agents can be both highly capable and tightly restricted, with several sharing container, VM, proxy, and credential-swapping setups to limit exfiltration. Telemetry was criticized, some questioned NVIDIA’s long-term maintenance and the “Open” naming, and others compared it with Anthropic’s sandbox-runtime and simpler Docker-based approaches.

## 3. [Getting ready to operate GNU Taler in Germany](https://news.ycombinator.com/item?id=50197404) (↑175, 💬61)
**Article:** GNU Taler announced that Taler Operations AG is being founded in Bochum to apply for a BaFin e-money license and operate Taler in euros, first in Germany and then across the eurozone. The move follows GLS Bank’s withdrawal from the e-money issuer role; Taler remains free software, and the company is raising capital from investors.

**Comments:** Much of the thread debated Taler’s privacy model: payers can remain private through blind signatures, but merchants and withdrawals are subject to KYC/AML and are not anonymous. Some commenters called the privacy claims misleading or honeypot-like, while others explained the compliance rationale, compared Taler with Wero and stablecoins, and discussed German/EU regulation and Chaum-style e-cash.

## 4. [Show HN: Run full iOS 16.5 firmware on Android Devices](https://news.ycombinator.com/item?id=50196718) (↑269, 💬93)
**Article:** HackiOS is a research project that boots Apple’s open-source XNU kernel from iOS 16.5 on Android phone hardware and in QEMU, running unmodified iOS user space with custom EFI loaders and driver replacements. It works partially on a POCO X5 Pro 5G via a RAM-only fastboot boot, with SpringBoard, apps, Wi-Fi, and GPU support, but lacks cellular, Bluetooth, charging, and App Store/Apple ID functionality.

**Comments:** Commenters were impressed by the technical feat but questioned its practical use, legal risk, crypto-token funding, and AI-assisted development. Discussion also covered the iOS 16.5 choice, the Secure Enclave/App Store roadblock, counterfeit-phone concerns, and jokes about running Android on iPhones or Linux on iPads.

## 5. [Woman faces six years in prison over Cash App account she never opened](https://news.ycombinator.com/item?id=50194833) (↑339, 💬316)
**Article:** Amanda Smith was arrested and extradited over a fraudulent Cash App account opened in her name using her Social Security number and date of birth, spending jail time and facing up to six years in prison. Cash App initially refused to provide account details because she could not prove ownership, and evidence including address, carrier, and phone OS discrepancies suggests she did not control the account; she has refused a plea deal.

**Comments:** Commenters expressed outrage at the prosecution, plea-bargain pressure, and Cash App/Block’s apparent lack of accountability, arguing identity-theft victims are forced to prove innocence. Some discussed possible lawsuits or EFF involvement, criticized the investigation’s weak link between account data and the person, and debated how police should handle such claims and whether stronger digital identity systems would help.

## 6. [AI and the Enclosure of the Scientific Commons](https://news.ycombinator.com/item?id=50199230) (↑75, 💬37)
**Article:** A preprint argues that scientific literature functions as an information commons and that AI enables a modern “enclosure” of it, turning shared knowledge into private wealth while undermining supporting social systems through slop spam. It draws on historical enclosure movements and economic frameworks to frame AI as a potential attack on a whole way of life.

**Comments:** Commenters challenged the “no one owns” premise by pointing to major commercial publishers, and debated whether AI will democratize science or concentrate it among a few labs. Others discussed open-science licensing, reviewer collapse under AI-generated submissions, and tangential debates over science funding and politics.

## 7. [Hedra is a 3D open world game I wrote from scratch while in highschool](https://news.ycombinator.com/item?id=50199389) (↑76, 💬16)
**Article:** A GitHub repository showcases “Project Hedra,” a low-poly 3D open-world RPG and game engine written from scratch in C# and OpenGL, with about 100k lines of code, procedural worlds, and Linux/Windows support. The author began it in high school to learn OpenGL, and scope creep turned it into a full game and engine.

**Comments:** Commenters praised the handmade project, its aesthetic, and the learning value of building a game from scratch. A major debate centered on AI coding: some called the project a relic of a pre-LLM era, while others rejected that framing and defended hand-built passion projects.

## 8. [Every AI model has the same "controversial" take on humans](https://news.ycombinator.com/item?id=50197313) (↑112, 💬146)
**Article:** ModelCompare asked 12 AI models three times for their most controversial take on humans, and 29 of 35 answers shared the theme that people prioritize belonging, group loyalty, or social status over truth. The article lists each model’s answers and notes a few different or refused responses.

**Comments:** Many commenters said the models are simply reflecting patterns in training data rather than holding genuine opinions, and some found irony in the models’ apparent groupthink. Others debated anthropomorphism, the prompt’s methodological limits, and whether the shared take reflects a real human tendency or a clichéd online worldview.

## 9. [What Is Gridifcation](https://news.ycombinator.com/item?id=50150163) (↑366, 💬181)
**Article:** The article compares Billboard top songs from 1975 and 2025 using tempo analysis, arguing that modern production “gridifies” human performance by treating timing variation as error and correcting it to machine-perfect precision. It highlights Shaboozey’s “A Bar Song (Tipsy)” as an exception built around a voice memo with natural timing.

**Comments:** Musicians and producers discussed quantization, click tracks, DAWs, and the loss of human feel, while some criticized the article’s premise and noted that hip-hop and electronic music often use programmed or intentionally off-grid beats. Others raised concerns about the publication’s marketing angle and debated whether gridified music is worse or just different.

## 10. [eMudhra to exit global SSL/TLS certificate business](https://news.ycombinator.com/item?id=50195110) (↑858, 💬592)
**Article:** eMudhra announced it will voluntarily exit the global SSL/TLS certificate business after a recent incident, saying it revoked affected CAs within 14 hours, issued no end-entity certificates from them, and suffered no infrastructure compromise or data breach. The company said SSL/TLS is about 1% of global revenue and that it will focus on other enterprise trust services.

**Comments:** Commenters heavily criticized the company’s response and competence, referencing reports that a private key was effectively “4” and questioning its remaining trust businesses. Discussion also covered the Web PKI trust model, browser versus Apple revocation delays, customer impact including InCommon, and the stock drop.

## 11. [Jailbreaking the Switch 2](https://news.ycombinator.com/item?id=50192536) (↑650, 💬231)
**Article:** The post describes ns2jb, a software-only tethered jailbreak for Switch 2 firmware 23.0.1, enabling native code execution in ordinary and fs sysmodules. It details WebKit and SmileBASIC exploit paths, a path-normalization buffer overflow in fs, and use of Codex with KVMs, HDMI capture, and a Bluetooth switch to automate testing. It demonstrates the jailbreak by modding Mario Kart World.

**Comments:** Commenters call the work impressive and expect faster Switch 2 game dumping and emulation due to LLM-assisted reverse engineering, while warning that Nintendo may ban accounts or take legal action. Several focus on the AI-assisted hardware harness and debate whether Codex should permit security research; others criticize Nintendo’s business practices and note the potential bug bounty value.

## 12. [Show HN: UI micro interactions prompts for AI](https://news.ycombinator.com/item?id=50199290) (↑59, 💬28)
**Article:** Article content was unavailable; from comments it appears to be a Show HN for a library of prompts and MCP context for building UI micro-interactions, with free examples and a paid tier. The site invites users to copy prompts, but access appears to require signup and/or subscription.

**Comments:** Commenters criticize the signup/copy flow and unclear free-versus-paid offering, and question why to buy prompts when an LLM can replicate the visible examples. Many say the demos lack polish and that the $30/month price is hard to justify against Claude subscriptions or free component libraries; the makers respond that the MCP server and natural-language prompts add value and that they are bootstrapped.

## 13. [Tell HN: I unknowingly broke the PHP RCE embargo. I am sorry.](https://news.ycombinator.com/item?id=50193416) (↑250, 💬101)
**Article:** The poster apologizes for a Tell HN post about forthcoming PHP RCEs CVE-2026-109618 and CVE-2026-109619, saying they had been told there was no embargo. They acknowledge the post disrupted coordinated disclosure, caused extra workload, and say they take responsibility and have learned from it.

**Comments:** Many commenters say the poster did not break an embargo they were not informed of and that responsibility lies further up the disclosure chain; others are skeptical, arguing the severity and missing CVE should have signaled an embargo. The thread discusses embargo rationale, prior exploitation and leaks, and the meaning of “taking responsibility,” with some defending the apology as honorable.

## 14. [Railpass](https://news.ycombinator.com/item?id=50201414) (↑4, 💬0)
**Article:** The provided content only repeats the title and credits Sami Smith, so no substantive summary is possible. There are no article details beyond that.

**Comments:** The comment thread consists of a single flagged comment, and no readable content is available. There is no discussion, debate, or consensus to summarize.

## 15. [Xbox wants you to pay 24 to 40 cents per hour to stream games you bought](https://news.ycombinator.com/item?id=50194009) (↑132, 💬161)
**Article:** Microsoft rolled out a la carte Cloud Playtime packs for Xbox Insiders: 10 hours for $4, 25 for $8, or 50 for $12, required on top of owning a cloud-playable game. The article compares this metered model with Stadia and PlayStation Now and notes free ad-supported streams for Insiders. It questions the market for hourly streaming access to already-purchased games.

**Comments:** Commenters split on whether the fee is fair, with some framing it as renting cloud GPUs akin to GeForce Now and a reasonable option for casual players without consoles. Others warn it normalizes metered access and future price increases, criticize the “games you already bought” framing, and prefer ownership models like GOG or local hardware. Several compare it unfavorably with competitors and see it as another sign of Xbox’s decline.

## 16. [A farewell to Arc browser](https://news.ycombinator.com/item?id=50197601) (↑197, 💬172)
**Article:** The Browser Company is sunsetting Arc on December 22, 2026, after which macOS/Windows Arc will stop working and accounts and personal data will be deactivated and deleted. It is directing users to Dia, a new AI-capable browser from the same team, with import support for passwords, bookmarks, extensions, Spaces, pinned tabs, and tab groups. The article provides a timeline and export/import instructions for Arc and Arc Search on mobile.

**Comments:** Commenters largely mourn Arc while recommending alternatives such as Zen, Orion, Safari add-ons, and Vivaldi, with Zen frequently cited as the closest replacement. Many criticize the pivot to Dia, Atlassian ownership, VC-backed incentives, AI features, and the remote shutdown, and several call for Arc to be open-sourced. Some report Dia is improving but still incomplete or aimed at a different user, while others defend its UX.

## 17. [Solving the 1950 cipher meant to test life after death](https://news.ycombinator.com/item?id=50167267) (↑8, 💬5)
**Article:** The article describes how T. E. Wood’s 1950 cryptogram, intended as a post-death survival test using Robert Thouless’s method, was finally solved by computational search. The key turned out to be the Lord’s Prayer from a 1912 Luther Bible in German, producing the mixed-language message “HIER BIN ICH TOTSIENS TEW”—“Here I am,” Afrikaans “Goodbye,” and Wood’s initials. The solution was confirmed by Klaus Schmeh in October 2026.

**Comments:** The author explains this was the last of four cryptograms from Klaus Schmeh’s list, remaining unsolved for 76 years, and that Claude/OpenAI tools helped write search code and verify results. Other commenters joke that the solution either disproves survival or proves ghosts are in Claude, and one criticizes the AI-assisted writing style.

## 18. [Show HN: Turn regular JavaScript into a neural net](https://news.ycombinator.com/item?id=50172984) (↑24, 💬9)
**Article:** Handwired presents a way to write numeric JavaScript-like programs that compile into neural-net-style circuits, with exact, differentiable behavior runnable in a browser without GPU or training. Demos include a mini OS, a learned gallery, and parallel JSON search turned into WebGPU kernels.

**Comments:** The main criticism is that the landing page overclaims “regular JavaScript” conversion; commenters note the demos use a DSL with constructs like `emiRelu`, and the docs reportedly say no tool converts existing JS source. Others are confused by the page’s purpose and demos, while some discuss the idea as a compiler from programs to weights and debate LLMs replacing code.

## 19. [What’s getting pwned right now](https://news.ycombinator.com/item?id=50195543) (↑309, 💬147)
**Article:** pwn.watch is a live security-incident tracker listing CVEs, affected products, severity, patch status, and advisories, with examples including an exploited Arista VeloCloud zero-day, banks detecting third-party AI agents, GitLab’s CVSS 10 RCE, Keycloak account takeover, leaked Linux kernel reports, LiteLLM supply-chain compromise, Node.js flaws, and BIND issues. It includes filters, a heatmap, notification signup, and AI-readable briefs.

**Comments:** Much of the thread criticizes the site’s dense “AI slop” aesthetic, dark mode, visual clutter, and confusing categorization, though some praise the concept and the “copy brief for your AI” feature. Commenters debate whether AI is driving an unprecedented wave of vulnerabilities, with others citing historical compromise data and arguing defenses will catch up. The author responds that the site was quickly vibe-coded and promises cleanup and historical data.

## 20. [The phenomena that brighten dawn and dusk (2016)](https://news.ycombinator.com/item?id=50172660) (↑15, 💬1)
**Article:** The article explains dawn and dusk optical phenomena caused by sunlight taking a longer path through the atmosphere, which scatters short wavelengths and leaves reds, oranges, and yellows. It describes the Earth’s shadow rising as a blue band, the Belt of Venus as an orchid/lavender band above it, and alpenglow as backscattered light on snow-covered mountains.

**Comments:** The sole commenter notes that the Pacific Northwest is entering a cloudy season and says the article reminds them to appreciate sunrise and sunset in the next few days.

## 21. [Dungeon Generation in the Gnomish Mines of NetHack](https://news.ycombinator.com/item?id=50154109) (↑99, 💬11)
**Article:** The post explains how NetHack’s Gnomish Mines use cellular automata to generate organic cave levels: 40% of cells start as floor, then four passes modify the grid, followed by corridor fixes for disconnected areas. It details the pass rules and notes confusion about the purpose of pass 2, which turns cells to rock when they have exactly five floor neighbors.

**Comments:** Commenters suggest pass 2 adds concavity and a spiny, organic feel rather than a bubbly cave shape, and one offers a JavaScript experiment to compare results without it. Others joke about dwarven archaeologists, praise the interactive procgen explanation, and clarify that the numbers refer to neighbor counts rather than tile indices.

## 22. [Faster than earcut: triangulating 3.7M map polygons in 489 ms](https://news.ycombinator.com/item?id=50193170) (↑187, 💬36)
**Article:** Globus released earstrip, a C++/WebAssembly polygon triangulator that replaces constrained Delaunay with optimized ear clipping for map rendering. It benchmarks 3.7 million map polygons in 489 ms and reports being faster than earcut in both C++ and browser comparisons, while explaining holes, ear tests, and performance tradeoffs.

**Comments:** The earcut author discusses bundle-size constraints and Mapbox’s hybrid triangulation approach, while others debate triangle quality, slivers, Seidel’s method, and GPU rendering costs. The author posts benchmark comparisons against delaunay32, and commenters also speculate about LLM involvement and discuss mobile tile rendering and Nanite-style systems.

## 23. [AI analysis of CT scans finds 42.9% of patients have coronary inflammation](https://news.ycombinator.com/item?id=50198940) (↑61, 💬32)
**Article:** Biograph reports that AI analysis of cardiac CT scans found coronary inflammation in 42.9% of asymptomatic, low-risk patients, including many with no detectable plaque. It claims standard bloodwork and risk calculators did not correlate with the inflammation findings and frames this as early risk detection.

**Comments:** Many commenters are skeptical, noting that BMI was the only correlate surviving correction and that the study omits or contradicts established measures such as coronary calcium and hs-CRP. Others share heart-attack anecdotes about CAC scores missing soft plaque, question the $17,500 program cost, and debate whether inflammation is a marker or causal driver.

## 24. [Mini brain organoids ‘reading’ Braille key step towards biohybrid computing](https://news.ycombinator.com/item?id=50197450) (↑28, 💬26)
**Article:** Researchers connected a tactile sensor to brain organoids and found that their neural responses could be decoded into Braille letters, with single organoids reaching about 61% accuracy and a trio reaching 83%. The work is presented as a step toward energy-efficient biohybrid computing.

**Comments:** Commenters focus on ethics, fearing that larger or more complex organoids could raise serious consciousness and welfare concerns, while others argue that outlawing promising research preemptively is shortsighted. Discussion also covers existing neuroethics recommendations, uncertainty about sentience, comparisons to IVF and stem-cell debates, and whether human organoids offer advantages over animal tissue.

## 25. [Show HN: Uberblok – an interactive museum of ZFS internals](https://news.ycombinator.com/item?id=50180257) (↑60, 💬19)
**Article:** Uberblok is an interactive museum of ZFS internals that walks through the uberblock, copy-on-write, transaction groups, vdevs, RAID-Z, snapshots, ARC, and other features. Its explanations and animations are tied to specific lines in OpenZFS zfs-2.4.4 and include source links.

**Comments:** ZFS users praise the project and discuss FreeBSD/macOS history, ARC tradeoffs such as sendfile zero-copy issues, and why ZFS is not more widespread. Critics object to the LLM-generated prose and question how much the author understands; the author acknowledges that agents wrote code and most text while he directed and reviewed it.

## 26. [Award-winning AI literature](https://news.ycombinator.com/item?id=50199232) (↑48, 💬50)
**Article:** The article compiles literary awards involving AI-assisted works, separating cases where AI was allowed, disclosed by organizers/publishers, confirmed by authors, or merely suspected. It includes examples from Japanese short-story prizes, poetry collections, interactive fiction, and contests later reviewed or reversed over AI use.

**Comments:** Commenters debate whether AI winning literary awards reflects genuine quality, increased submissions, or flawed judging. Many criticize lumping minor AI use with extensive generation, while others argue that craft, process, and human authorship still matter to readers; some contend output quality is what ultimately counts.

## 27. [Show HN: agent-usage-guard – a Claude Code mod to protect your usage window](https://news.ycombinator.com/item?id=50198936) (↑18, 💬7)
**Article:** agent-usage-guard is a Claude Code mod that monitors plan usage and intercepts subagent fan-out, heavy-context prompts, and retry loops before they consume the usage window. It counts agents across sessions, asks through Claude Code’s dialog, stores minimal local data, and fails open except for agents it cannot judge in time.

**Comments:** The author explains building it after repeatedly exhausting usage windows, reporting large reductions in agent bursts and high-context requests. Commenters ask about compaction costs and plan-specific presets, and note that newer Claude Code versions often auto-compact near cache expiry.

## 28. [Startup taps underwater volcano as energy source in “proof point” test](https://news.ycombinator.com/item?id=50157456) (↑119, 💬48)
**Article:** Endurance Energy demonstrated a subsea geothermal prototype at the Axial Seamount, producing net-positive electricity for about 8.7 seconds after an initial well delivered insufficient fluid. The company used a nearby natural vent, hit software and cable failures, and plans deeper wells plus a larger Tonga deployment.

**Comments:** Commenters raise concerns about impacts on hydrothermal vent ecosystems and skepticism about the economics and LCOE. Others see promise for remote island power, while many make supervillain, volcano-lair, and science-fiction jokes.

## 29. [The Last Museum: Semantic search across 5.8M artworks from major museums](https://news.ycombinator.com/item?id=50194522) (↑93, 💬27)
**Article:** The Last Museum offers semantic search across more than 6.3 million artworks from major museums, with natural-language queries and date filtering. The site showcases well-known works alongside broad thematic and stylistic searches.

**Comments:** Commenters like the concept but criticize incomplete coverage, weak artist/name search, missing filters, and the grandiose name. Others discuss museum curation, compare Europeana’s larger index, and question whether embeddings rely on uneven catalog metadata.

## 30. [A complete bypass of eMudhra’s 1FA OTP login system](https://news.ycombinator.com/item?id=50199757) (↑133, 💬39)
**Article:** The linked post claims a complete bypass of eMudhra’s 1FA OTP login system, described as less severe than a leaked CA key but still a serious authentication flaw. The available content is mostly the post title and surrounding discussion rather than a full technical write-up.

**Comments:** Commenters interpret the flaw as OTP brute-forcing enabled by missing rate limiting or invalidation and a small code space, noting the demo’s result was slightly off due to concurrent connections. They discuss the impact on CA customers and domain/CSR signing, mention eMudhra leaving the CA business, and complain that anti-bot measures obscure the original post.

---
_Generated 2026-10-22 16:05 MDT_

---

## Recent Digests

- [Oct 22](./archives/2026/oct/hn-digest-2026-10-22.md)
- [Oct 21](./archives/2026/oct/hn-digest-2026-10-21.md)
- [Oct 20](./archives/2026/oct/hn-digest-2026-10-20.md)
- [Oct 19](./archives/2026/oct/hn-digest-2026-10-19.md)
- [Oct 18](./archives/2026/oct/hn-digest-2026-10-18.md)
- [Oct 17](./archives/2026/oct/hn-digest-2026-10-17.md)
- [Oct 16](./archives/2026/oct/hn-digest-2026-10-16.md)

[Full archive](./archives/) (163 issues)

_If you want more, explore the [archive folder](./archives/)._
