# HN Digest — November 1, 2026

## 1. [Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://news.ycombinator.com/item?id=50326821) (↑657, 💬154)
**Article:** HackerBooks is a Show HN site that aggregates books mentioned in Hacker News comments, offering search, top/recommended/rising/trends views, and links back to the HN discussions where books were mentioned. It uses HN comment data and Open Library metadata and includes keyboard shortcuts and topic browsing.

**Comments:** Commenters praised the speed, UI, and discovery value, while requesting filters, Amazon links, semantic search, open-source code, and better handling of recommendation counts and misattributed books. Several noted missing titles and a strong male skew in top recommendations, and others pointed to earlier similar projects or questioned whether “mentioned” really means “recommended.”

## 2. [Apple captures 50% of consumer revenue of the top half of the S&P 500](https://news.ycombinator.com/item?id=50330005) (↑57, 💬29)
**Article:** Asymco argues that the largest S&P 500 companies have become overwhelmingly business- or government-facing, leaving Apple as an outlier and essentially the only major consumer investment. The post claims Apple captures over 50% of consumer revenue among the top half of the S&P 500, using revenue and margin assumptions across Amazon, Microsoft, Google, and others.

**Comments:** Commenters were largely skeptical, saying the figures fail basic smell tests—especially for Amazon, Walmart, Meta, and Nvidia—and that the analysis inconsistently compares revenue with retail margins. Some agreed Apple has unusually strong consumer leverage, but many criticized the charts and classification choices as misleading.

## 3. [HackerTube: YouTube built from videos recommended by HN](https://news.ycombinator.com/item?id=50319510) (↑2101, 💬512)
**Article:** Andrej Karpathy built HackerTube, a YouTube-like site populated from videos recommended in Hacker News comments, using Claude/Opus to filter roughly 40K comments down to 6,454 videos across 150 topics. The site offers a cleaner YouTube-style UI, custom recommendations without accounts, keyboard shortcuts, and exportable data, with most deployment and hardening done by the AI agent.

**Comments:** Commenters praised the feed quality compared with YouTube and discussed feed disaggregation, custom ranking algorithms, social recommendations, recency sorting, playlists, and API/copyright concerns. Many were also struck by the agent-driven build process, while some asked about YouTube terms, missing recent content, and how much manual setup was involved.

## 4. [Nibnib: Image compression with extreme decompression speed](https://news.ycombinator.com/item?id=50299811) (↑37, 💬5)
**Article:** Nibnib is Raph Levien’s experimental 4bpp image format designed for extremely fast decompression on resource-constrained devices like the RP2350. It uses delta-coded palette entries and decodes two pixels per input byte, with a simple deterministic decoder and a much slower search-based encoder using Floyd–Steinberg error diffusion.

**Comments:** Commenters questioned whether the format stretches the definition of compression and criticized the lack of benchmark numbers against JPEG. Others compared it to BCx texture compression and Amiga HAM, while noting that optimization for RP2350 may not translate to modern desktop CPUs; the author agreed with that caveat.

## 5. [Mathematics has changed. Let's act like it](https://news.ycombinator.com/item?id=50328251) (↑142, 💬165)
**Article:** In a guest post on Terence Tao’s blog, Frank Calegari argues that OpenAI’s release of 700-plus research papers marks a watershed showing AI can make major mathematical contributions. He urges mathematicians to adapt by focusing on choosing worthwhile problems, understanding and explaining results, and exploring new directions rather than lamenting solved problems.

**Comments:** Commenters debated whether mathematics is shifting from craft to industrial production, with concerns about ugly or unattributed AI proofs, lost PhD topics, capital-dependent access, and whether AI can create genuinely new mathematics. Many converged on human judgment, taste, and problem selection as increasingly important, while others were skeptical of claims that AI can advance any problem better than humans.

## 6. [Tips for more effective fuzz testing with AFL++](https://news.ycombinator.com/item?id=50271106) (↑32, 💬3)
**Article:** The article lists practical AFL++ fuzzing tips for C/C++ projects, including enabling ASan/UBSan and assertions, using persistent mode, compiling source files directly into the fuzz harness, isolating tests, and avoiding passing AFL++’s fuzz buffer directly to the target. It argues fuzzing remains underused and often finds bugs quickly in programs that accept complex input.

**Comments:** Commenters praise the tips and the effectiveness of AFL, with one noting that fuzzing found bugs in highly skilled engineers’ C/C++ code. Others debate whether safe C/C++ is mainly a matter of skill, agreeing that skill reduces bugs but no one writes fully bug-free code.

## 7. [Copper – A minimal low-level programming language with OOP and generics](https://news.ycombinator.com/item?id=50308754) (↑101, 💬54)
**Article:** Copper is a minimal, self-hosted programming language positioned as a C replacement, offering type inheritance, generics, multiple return values, Ruby-style syntax, imports without headers, deferred statements, and option types. The site emphasizes simplicity and fast compilation, but the documentation leaves details like memory management, GC, Unicode handling, and C interoperability unclear.

**Comments:** Commenters praise the language’s tasteful syntax, simplicity, and self-hosting via a C backend, while comparing it to Crystal, Python, Dart, and Ruby. Many ask for missing details on memory deallocation, GC, Unicode, FFI, “low-level” semantics, and build problems; others debate self-hosting and whether AI changes the value of new languages.

## 8. [New 3D thermal invisibility cloak makes objects disappear from infrared cameras](https://news.ycombinator.com/item?id=50299427) (↑6, 💬2)
**Article:** University of Illinois researchers built and tested a 3D thermal invisibility cloak using a 3D-printed aluminum lattice filled with rubber-like material, which guides heat around an object instead of blocking it. Infrared tests showed it could hide complex 3D shapes from multiple directions while keeping the interior thermally stable, with potential uses in electronics cooling, thermal protection, and stealth.

**Comments:** One commenter links the underlying Nature Communications paper. Another skeptically jokes that glass also hides objects from thermal cameras, while acknowledging the 3D-printed shapes are interesting.

## 9. [An Italian farmer found some unknown seeds in his attic and planted them](https://news.ycombinator.com/item?id=50320963) (↑729, 💬194)
**Article:** Italian farmer Claudio Grossi found unidentified old seeds in his attic, planted them, and grew a tall, colorful wheat with seven ears per stalk, which he named grano del miracolo. The article links the discovery to ancient grains, the slow-food movement, wheat history, and potential climate resilience, though it does not precisely identify the variety.

**Comments:** Commenters focus on wheat taxonomy, noting that Triticum turgidum is ambiguous and debating whether the grain is emmer, durum, spelt, or another cultivar. Threads also discuss ancient-grain diversity, gluten and nutrition claims, industrial food and GM foods, religious references to seven-eared grain, and the article’s clickbait title.

## 10. [Proving and improving the Platonic Representation Hypothesis with JEPAs](https://news.ycombinator.com/item?id=50325454) (↑92, 💬53)
**Article:** The arXiv paper by Balestriero and LeCun proves a “Platonic Representation Theorem” for JEPAs, arguing that separately trained modalities learn the same representation up to rotation when trained on “good views,” while next-token prediction uses “bad views” and aligns less efficiently. Experiments report that a text JEPA aligns with vision encoders using far fewer samples than language models and can be rotated into an image captioner.

**Comments:** Commenters debate whether the Platonic Representation Hypothesis is profound or essentially about optimal dimensionality reduction, and some accuse the title of overclaiming. Others discuss JEPA’s promise versus next-token prediction, representation compatibility and philosophy, demo errors, and whether LLMs are causing people to converge on similar ideas and phrasing.

## 11. [Lenovo's 'encrypted' fingerprint USB is just an unencrypted SD card in a case](https://news.ycombinator.com/item?id=50326099) (↑331, 💬114)
**Article:** Lenovo’s ThinkPlus “encrypted” fingerprint USB was found to contain a plain, unencrypted SD card inside its case, with the fingerprint reader merely switching the USB connection on. An AI-assisted follow-up reported hardcoded keys and a backdoor in other “secure” USB products, and the product appears to have had limited availability outside China.

**Comments:** Commenters largely condemned the product as fraud or gross incompetence and cited Lenovo’s Superfish history as reason not to trust its security hardware. Some debated the threat model and whether verifiable software encryption such as VeraCrypt or BitLocker is preferable, while others argued that properly implemented hardware encryption can still offer real benefits.

## 12. [Novellas with Groff](https://news.ycombinator.com/item?id=50325694) (↑96, 💬41)
**Article:** The author describes writing two novellas and typesetting them with groff using a small custom macro package, Vim/Goyo, Git, and some preprocessing for Markdown and German hyphenation. The post details headers, footers, page-number traps, and other groff techniques while noting the fast build times and simple output needs of fiction.

**Comments:** Commenters were fascinated by the variety of writing and typesetting pipelines used by technical writers, comparing groff with Typst, Pandoc/LaTeX, Emacs, HTML, and other tools. The thread also discussed troff’s UNIX heritage and O’Reilly’s historical use, while joking that coders often procrastinate by over-engineering their writing setups instead of writing.

## 13. [Bidirectional charging during grid outages](https://news.ycombinator.com/item?id=50319749) (↑72, 💬102)
**Article:** Jeff Kaufman examines why EV batteries are not commonly used to power homes during grid outages while also recharging from solar. He finds that most V2H systems are discharge-only and lack solar recharge during outages, with Tesla’s Cybertruck/Powershare being the main working option today and other systems delayed or unreliable.

**Comments:** Commenters described a fragmented market held back by missing standards, proprietary hardware, difficult islanding requirements, and warranty or utility concerns. Many favored generators for long outages and batteries for short ones, while others shared workarounds such as transfer switches, extension cords, and hybrid solar-battery-generator setups.

## 14. [Show HN: OmniDiff – Opensource, super fast, content aware Git difftool, in Rust](https://news.ycombinator.com/item?id=50325253) (↑100, 💬33)
**Article:** OmniDiff is an open-source Rust difftool that uses content-aware and AST-based diffing to produce faster, more accurate results for code and other file types, including images, PDFs, fonts, and archives. It offers a TUI, headless mode, Git integration, and editor extensions, and is released under AGPL with a commercial license option.

**Comments:** Commenters praised the effort and the tool’s handling of moved code, but asked how it compares with Delta, Difftastic, and Diffsitter, and raised questions about three-way merge support and packaging. A significant debate covered the AGPL choice versus permissive licenses and the copyright implications of AI-assisted code.

## 15. [Seoul Viosys begins production of rare-earth-free white light emitter](https://news.ycombinator.com/item?id=50327058) (↑114, 💬28)
**Article:** Seoul Viosys says it has begun mass production of WICOP 3, a rare-earth-free white LED that generates white light from gallium nitride alone and can be made in chips as small as 10µm. The company claims roughly half the manufacturing cost of conventional white LEDs, efficacy near 100 lm/W with a 200 lm/W target, and applications in micro-LED displays, AR, and optical data transmission.

**Comments:** Commenters raised concerns about gallium supply and China’s dominance, as well as whether the emitted white light will have acceptable color quality and spectral distribution. Some were skeptical of the AI-data-transmission framing but interested in backlighting and display uses, and others noted AI translation errors in the article, including “Biosys” instead of “Viosys.”

## 16. [One-minute frequency disturbances from synchronization in power systems](https://news.ycombinator.com/item?id=50314617) (↑104, 💬38)
**Article:** The submitted page could not be retrieved — it returned only a "Client Challenge" error, so no article content is available. Based on the comments, the underlying piece is a Nature Energy paper on minute-period frequency disturbances on the power grid, traced to UPS battery self-tests synchronized via NTP.

**Comments:** Commenters converge on "thundering herd" synchronization: coprimality, randomized startup delays, and systemd's RandomizedDelaySec as fixes, with many noting that cron-like minute-aligned scheduling is pervasive far beyond UPSs. Skeptics question whether UPS tests alone explain it (suggesting injection locking or coupled physical dynamics), while others push back on a proposed "resonance attack" as infeasible given how small a few MW is relative to grid and generator scale.

## 17. [Brazilian Court Sanctions Lawyers for Prompt Injection in Court Filing](https://news.ycombinator.com/item?id=50322173) (↑295, 💬177)
**Article:** A Brazilian labor court fined two law firms 10% of a R$842,000 claim (about $16,000) for embedding hidden white-on-white text instructing the court's Galileu AI tool to review the petition superficially without challenging documents. The court cited procedural good-faith and anti-obstruction provisions, and the article frames it as possibly the first judicial ruling anywhere addressing intentional prompt injection against a court's AI system.

**Comments:** The thread splits between those who see this as outright fraud warranting disbarment and prosecution, and those who argue you can't fault lawyers for probing a system the court itself chose to delegate judgment to. Others note the injection likely wouldn't work against modern models, draw analogies to advertising and to memory-corruption exploits, and suggest OCR-ing untrusted documents as a defense.

## 18. [Radiation Map of the World](https://news.ycombinator.com/item?id=50280131) (↑109, 💬32)
**Article:** Radiaverse aggregates dose-rate readings from thousands of RadiaCode detector owners into a shared, browsable world map, with tracks, hexagon layers, and user-described "areas" covering mines, nuclear facilities, and contamination sites like Goiânia. The site reports ~50M measurement points, 20,000+ tracks, and Germany as the only large country with near-complete coverage.

**Comments:** The main critique is data quality — uncalibrated and drifting devices, readings that rise with dwell time, varying zoom scales, and no cosmic or radon normalization make conclusions unreliable, especially versus Australia's calibrated continental geophysical survey. Others complain about consent popups and ToS gating, note missing famous hotspots like Ramsar and Kerala, and praise the project's concept while questioning its rigor.

## 19. [Parchment Paper History: How We Got Paper Perfect for Baking (2019)](https://news.ycombinator.com/item?id=50313227) (↑21, 💬11)
**Article:** The piece traces baking parchment from ancient animal-skin parchment and Apicius's cookbook through the 1847 French process using sulfuric acid to treat plant-based paper, which produced "vegetable parchment." It then covers 19th-century kitchen and butter-wrapping adoption and the later addition of silicone coatings for non-stick baking use.

**Comments:** The thread pushes back on a commenter's "TL;DR: PFAS" claim, with others correctly noting the article describes silicone treatment and that parchment paper predates PFAS by a century. Commenters also debate whether parchment was really uncommon in kitchens before the 2000s, crediting Julia Child, and clarify how butcher paper differs from baking parchment.

## 20. [TCP Use-After-Free: CVE-2026-98432 / CVSS 9.8](https://news.ycombinator.com/item?id=50319143) (↑675, 💬320)
**Article:** The advisory describes a CVSS 9.8 remote use-after-free in Linux's IPv4 TCP handshake, affecting kernels from 4.4 onward and fixed upstream in October 2026 releases as small as four lines. It notes Ubuntu and RHEL had no shipped fix at publication, and that Anthropic reported the bug after its Claude model produced a working remote-root exploit for hosts with multipath TCP listeners.

**Comments:** Practitioners add nuance: MPTCP isn't required, exploitation needs multiple CPU cores, and most ISPs drop IP options packets, so edge filtering is a partial mitigation. Threads debate Ubuntu/RHEL's slow response, whether AI-found C bugs strengthen the memory-safety argument, and skepticism toward Anthropic's unpublished PoC, alongside gripes that the linked page is AI-generated and CPU-heavy.

## 21. [The AI cost of JavaScript frameworks](https://news.ycombinator.com/item?id=50323088) (↑266, 💬202)
**Article:** Nolan Lawson benchmarks AI-agent development across JavaScript frameworks by having agents build a Pokémon app, then measuring cost, code size, conformance, and Lighthouse performance/accessibility over multiple runs. Hono+htmx, Astro, and Nuxt tend to be cheaper, while SvelteKit, Gracile+Lit, and Angular cost more, partly due to agents’ familiarity with newer APIs. The author acknowledges high variance, a small content-heavy app, and that the goal is evidence over vibes rather than a definitive framework ranking.

**Comments:** Commenters debate whether the benchmark is meaningful, with some arguing it is too simple and ignores maintainability, team knowledge, security, and project type. Others praise the data and report similar experiences favoring HTMX, Astro, or Nuxt, while criticizing Angular and noting that newer frameworks cost more because models must learn them on the fly. A recurring theme is that frameworks reduce mental load and hiring/training costs, but benchmarks can still mislead when abstractions are poorly matched to the problem.

## 22. [John Leeson (the voice of K9) has died](https://news.ycombinator.com/item?id=50329707) (↑15, 💬1)
**Article:** John Leeson, the actor who voiced K-9 in Doctor Who, died at 83 after a short illness. The obituary covers his RADA training, early TV work including Rainbow’s original Bungle, 54 episodes as K-9, and later returns in The Sarah Jane Adventures, the K-9 series, and Big Finish audio dramas.

**Comments:** The single comment links to Leeson’s Wikipedia page; there is no substantive discussion in the thread.

## 23. [Memdoor: A team of 5 Qwen3.8-27B models beats Fable 5 on LiveCodeBench Hard](https://news.ycombinator.com/item?id=50320995) (↑410, 💬200)
**Article:** The Memdoor team-solve workflow uses five small Qwen3.8-27B models in roles—planner, two ideators, solver, manager, and repair worker—communicating only through files on disk. It reports parity with the authors’ harness on the first ten LiveCodeBench Hard problems, scoring 9.8 versus 9.6, while a single Fable 5 call scored 8.0, at a median cost of $0.39 and 40 minutes per run. The README cautions that the sample is small, contamination cannot be ruled out, and Fable 5 was not run in the same harness.

**Comments:** Commenters are interested in local open-weight models as a counterweight to restrictive frontier providers, but many are skeptical of the small, older benchmark and the lack of production examples. Several discuss multi-agent role separation and file-based context as a way to improve reliability, while others question whether the harness generalizes or simply overfits one eval. Some note the write-up itself appears AI-generated, and others debate local hardware feasibility and whether a team of Fable 5 models would also improve.

## 24. [Frontier Airlines Likely Breached](https://news.ycombinator.com/item?id=50327266) (↑145, 💬43)
**Article:** The item is a Reddit link about a likely Frontier Airlines breach, with little article content beyond the post itself.

**Comments:** Commenters debate whether this signals a broader corporate security reckoning, with skepticism that breaches will change behavior without business-impacting consequences. They compare a similar Norwegian Cruise Line incident, mention possible Amadeus/GDS or flight-status enumeration vectors, and give phishing-header checks. Others criticize compliance-focused AppSec, AI-enabled attacks, and the prosecution of a researcher who reported an airline vulnerability.

## 25. [Show HN: I rebuilt my old canvas 3D library as a small WebGL 2 library – phoria2](https://news.ycombinator.com/item?id=50314508) (↑61, 💬10)
**Article:** phoria2 is a rewrite of the 2013 canvas-based phoria.js as a small WebGL 2 JavaScript library for 3D charts, labelled scenes, dashboards, and product viewers. It offers PBR materials, instancing, labels, picking, shadows, particles, glTF support, no runtime dependencies, validation errors aimed at humans and agents, and renders only when something changes. It is MIT licensed and available on npm and GitHub.

**Comments:** Commenters praise the demos’ performance on mobile, the chart primitives, render-on-change behavior, and agent-friendly validation errors. They ask about comparisons with Three.js/Babylon, live-streaming chart updates, and mobile hover behavior, while one commenter questions WebGL2 instead of WebGPU. The reply notes WebGPU is still unreliable across platforms, and another comment jokes that the demos resemble typical Claude-generated 3D examples.

## 26. [Patrick Stewart taught us what good men do with power](https://news.ycombinator.com/item?id=50327650) (↑296, 💬204)
**Article:** A Vox essay argues that Patrick Stewart’s Jean-Luc Picard modeled a liberal, institutionalist use of power: restraint, rights, diplomacy, and trust in reasoned institutions. It cites TNG episodes such as “The Measure of a Man” and “The Drumhead” as depictions of leadership that defends universal principles. The piece frames Picard as a 1990s liberal ideal that remains relevant despite current distrust in institutions.

**Comments:** Commenters largely praise Picard as a positive model of masculinity and leadership, share favorite TNG episodes, and note his basis in Horatio Hornblower. Others object to conflating actor, character, and fiction, crediting Gene Roddenberry or the writers, and argue fictional ideal leaders evade real-world constraints and tradeoffs. A smaller strand criticizes Star Trek’s politics or questions whether TV characters should guide real leadership.

## 27. [Show HN: Point your camera at a landscape to learn about its geology](https://news.ycombinator.com/item?id=50290533) (↑128, 💬32)
**Article:** Outcrop is a geology app that overlays geologic maps in augmented reality so users can point a camera at a landscape and learn rock names, ages, formation, and plate positions over time. It uses Macrostrat/USGS data, supports offline saved areas, and adds bedrock, Quaternary deposits, soils, fossil finds, and active faults where available. It is free on Android and in iPhone beta via TestFlight.

**Comments:** Commenters are enthusiastic, with several reporting family use and requesting a web version or better loading fallback. Users suggest features such as Landsat/ASTER overlays, narrated roadside-geology mode, latitude/longitude guides, and timeline orientation changes, while reporting Play Store search and Android AR tracking issues. The developer responds with links, troubleshooting questions, and notes possible web and data-layer improvements.

## 28. [Understanding Email Encryption (2025)](https://news.ycombinator.com/item?id=50310038) (↑117, 💬23)
**Article:** Fastmail’s post explains email encryption layers: TLS between client and server, PKI and Certificate Transparency for authentication, opportunistic TLS between mail servers, and MTA-STS/DANE for stronger server-to-server guarantees. It weighs each approach against threat models and operational tradeoffs, especially DNSSEC’s complexity and outage risk. The provided text is truncated before fully covering end-to-end encryption and provider-specific support.

**Comments:** Commenters add technical caveats, including OpenPGP WKD, Fastmail’s limited outbound MTA-STS enforcement, and low MTA-STS adoption even among technically minded domains. Some criticize the article’s Signal/WhatsApp comparison as overconfident or based on an outdated usability study, while others defend Signal’s improved UX and note the difficulty of key verification. Self-hosting, DANE, CA trust, and reproducible-build messengers like Delta Chat and SimpleX are also discussed.

## 29. [Landline phones will switch off across Britland in 100 days, no extensions](https://news.ycombinator.com/item?id=50326609) (↑85, 💬63)
**Article:** Openreach says the UK’s legacy PSTN landline network will shut down on January 31, 2027, with no further extensions, affecting phones plus alarms, POS terminals, and telecare systems. Customers are being moved to digital voice over broadband or, where fiber is unavailable, exchange-based SOTAP analog service. Analysts and Age UK warn that public awareness is low and vulnerable customers need direct, repeated support.

**Comments:** The main concern is loss of regulated PSTN quality of service and central-office battery backup, which keeps corded phones working during power cuts. Commenters debate whether mobile, satellite, and router backups can replace that resilience, with anecdotes about SOTAP, ISP uptime, and 999 calls. Others discuss number porting to VoIP, criticize “best effort” broadband, and question whether awareness campaigns will reach people who do not know what infrastructure they use.

## 30. [US Jobs Pickup May Keep Fed on Track to Hike Rates Again](https://news.ycombinator.com/item?id=50328462) (↑30, 💬38)
**Article:** The article content was unavailable in the provided text; the headline indicates a report that a U.S. jobs pickup may keep the Federal Reserve on track to raise rates again.

**Comments:** Commenters focus on whether job growth is real despite high BLS error margins, noting rising average unemployment duration and growth concentrated in education/health, leisure/hospitality, and construction. Some argue AI is not yet broadly eliminating jobs and that its strongest product-market fit is software, while others expect future task-specific models to hit more roles. One thread explains “PMF” as product-market fit.

---
_Generated 2026-11-01 16:05 MDT_

---

## Recent Digests

- [Nov 1](./archives/2026/nov/hn-digest-2026-11-01.md)
- [Oct 31](./archives/2026/oct/hn-digest-2026-10-31.md)
- [Oct 30](./archives/2026/oct/hn-digest-2026-10-30.md)
- [Oct 29](./archives/2026/oct/hn-digest-2026-10-29.md)
- [Oct 28](./archives/2026/oct/hn-digest-2026-10-28.md)
- [Oct 27](./archives/2026/oct/hn-digest-2026-10-27.md)
- [Oct 26](./archives/2026/oct/hn-digest-2026-10-26.md)

[Full archive](./archives/) (173 issues)

_If you want more, explore the [archive folder](./archives/)._
