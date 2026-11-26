# HN Digest — November 26, 2026

## 1. [Kamil Khan Mumtaz: Pakistani architect, admired at home, almost invisible abroad](https://news.ycombinator.com/item?id=50659841) (↑61, 💬6)
**Article:** The article profiles Pakistani architect Kamil Khan Mumtaz, whose work is widely admired in Lahore but little known abroad. Trained as a modernist in London, he later rejected much of that framework and revived traditional Pakistani and Mughal-derived architecture, craftsmanship, and conservation, including efforts to save Lahore’s Walled City.

**Comments:** Commenters praise Mumtaz’s work and debate whether he is the “greatest” architect, with one nominating Christopher Alexander. Others push back on the idea that educated people should necessarily know an architect from another region, while noting Pakistan’s large population.

## 2. [AMD-specific fork of llama.cpp](https://news.ycombinator.com/item?id=50657265) (↑221, 💬54)
**Article:** The post recommends llama-cpp-rdna-boosts, an AMD-specific patch set for llama.cpp, reporting token generation improving from about 35 to 55 tokens/second and prefill from 700 to 1300 tokens/second on an AMD R9700 eGPU. It contrasts this with newer bespoke inference engines that chase speed partly by changing model behavior, and praises the fork’s minimal, pinned patches to upstream llama.cpp.

**Comments:** AMD users share their own forks, benchmarks, and experiences across RDNA cards, MI50s, 7900XTXs, Apple hardware, and Intel requests. Debate centers on whether speed-focused forks compromise output quality, why upstream llama.cpp does not merge these patches, and the implications of llama.cpp’s ownership via Hugging Face and NVIDIA.

## 3. [YouTube Ad Punisher – Auto-reloads YouTube pages when an ad plays](https://news.ycombinator.com/item?id=50657530) (↑165, 💬231)
**Article:** YouTube Ad Punisher is a browser extension that detects YouTube ads, saves the playback timestamp, reloads the page, and resumes playback, with a fallback redirect to an ad-free mirror after repeated reloads. It also logs ad history locally and claims to avoid YouTube’s anti-adblock detection by using reloads rather than network blocking.

**Comments:** Many commenters say uBlock Origin plus SponsorBlock already solves YouTube ads, while others debate whether paying for YouTube Premium is worthwhile and whether adblocking harms creators. Some criticize the extension as a hacky or LLM-amplified solution, question extension trustworthiness, and note YouTube A/B testing means ad experiences vary widely.

## 4. [CTO of 'RansomwareHelp' Indicted for Wire Fraud](https://news.ycombinator.com/item?id=50657645) (↑159, 💬66)
**Article:** Krebs reports that the CTO and co-founder of RansomwareHelp was indicted for wire fraud after an FBI sting found the company secretly negotiated and paid ransomware groups for decryption keys while claiming it never paid ransoms. The company allegedly charged victims marked-up fees and fabricated technical claims about cryptographic recovery and forensic servers.

**Comments:** Commenters debate whether this was fraud if victims ultimately got their data back, but many argue the false “we never pay ransom” claims and fabricated service descriptions constitute material deception. Thread also includes jokes about the defendant’s name and Florida, discussion of plausible deniability, and criticism of FBI haggling and ransomware-payment legality.

## 5. [Rvoip 0.5 the complete VoIP stack in Rust](https://news.ycombinator.com/item?id=50658632) (↑33, 💬11)
**Article:** rvoip 0.5 is a Rust library providing a SIP/VoIP stack with SIP, RTP, WebRTC, SRTP, QUIC/WebTransport, and AI voice agents under one call model, without external SIP or media servers. The README includes RFC 7502 benchmark results and interoperability claims against Asterisk, FreeSWITCH, Jambonz, Kamailio, and OpenSIPS.

**Comments:** Commenters ask for comparisons with RustPBX and rsipstack and note the README lacks benchmarks against existing systems. Others welcome a Rust option versus C/Go stacks, joke that “complete” VoIP still lacks fax support, warn about AI voice-agent spam, and discuss cheaper Twilio alternatives like BulkVS and their limitations.

## 6. [AI made self-hosting fun again](https://news.ycombinator.com/item?id=50660180) (↑3, 💬0)
**Article:** The author describes self-hosting for years and losing enthusiasm, then regaining it through AI coding agents that reduce friction in managing Git-based infrastructure, trying NixOS and bootc images, automating updates/deployments, and building small custom tools. They also reuse existing hardware and note downsides: added maintenance, bugs/security risks, and the temptation to deploy things just because it is easy.

**Comments:** No comments.

## 7. [Intel One Mono font (2023)](https://news.ycombinator.com/item?id=50653667) (↑424, 💬231)
**Article:** Intel One Mono is an open-source monospaced font designed with low-vision developers for legibility and reduced eyestrain, offering four weights with italics, broad Latin-script language support, and optional programming ligatures. The repo includes installable fonts and editable source files, with guidance for use in editors and font formats.

**Comments:** Commenters discuss favorite coding fonts such as Atkinson Hyperlegible Mono, Iosevka, JetBrains Mono, IBM Plex Mono, and others, while debating specific glyph choices like the lowercase “e,” braces, and “@.” Some question whether another corporate monospace font is necessary, while others praise Intel’s low-vision testing and find the font highly readable.

## 8. [OpenAI may be in cost control mode](https://news.ycombinator.com/item?id=50652527) (↑153, 💬135)
**Article:** The post argues that OpenAI’s Astra 6.2 and Sol 6.2 were tuned for cost savings, citing lower reasoning and output tokens per task versus predecessors and calling them “underthinking outliers.” It uses data from an Agent Duel battle system and reports statistically significant drops.

**Comments:** Commenters debate whether this reflects cost control, benchmark/Pareto optimization, explicit effort settings, model quality declines, or IPO/profitability pressure. Some cite enterprise cost-per-task concerns and OpenAI’s benchmark dominance, while others say more efficient token use is not inherently bad and share switching experiences with Claude and other models.

## 9. [Show HN: Olumino, a Markdown notes and spaced repetition app](https://news.ycombinator.com/item?id=50651099) (↑34, 💬23)
**Article:** Olumino is a browser-based Markdown notes and spaced-repetition app using FSRS-7 scheduling, swipe-based recall grading, moon indicators, Anki import/export, and teacher class dashboards. It offers free core use with paid device syncing and supports LaTeX, code, images, and language-learning features.

**Comments:** Commenters ask about the scheduler and suggest adding an “imperfect” answer option, while comparing Olumino with Anki, Remnote, Obsidian plugins, and Mochi. Some question the AI-assisted SEO blog and non-open-source presentation, and the creator responds about UX goals, inspirations, and mobile-app plans.

## 10. [George Whitesides, 1939-2026](https://news.ycombinator.com/item?id=50657936) (↑32, 💬4)
**Article:** Article content is unavailable; based on the title, the story appears to be an obituary for chemist George Whitesides (1939–2026).

**Comments:** Commenters remember Whitesides’ talk on paper-based microfluidics and his candor that “cheap” diagnostics were still not cheap enough for developing countries. Others note his influence in chemistry and materials science and discuss his widely cited paper on writing papers, with one caveat that his group’s outlining style may not suit every advisor.

## 11. [Top-cited AI scientists at four US companies compared](https://news.ycombinator.com/item?id=50658910) (↑7, 💬1)
**Article:** The article uses the 2026 Stanford–Elsevier top 2% list to compare US-based AI authors at Anthropic, OpenAI, Google, and Meta. It reports median 2025 citations of 4,830 at Anthropic, 2,150 at OpenAI, 1,481 at Google, and 1,295 at Meta, versus 968 for the typical US AI author, while company authors publish fewer papers. It also explains its methodology, including median values, US-only authors, Google DeepMind inclusion, and logarithmic scales.

**Comments:** The sole comment asks for more data beyond the plots, suggesting the visual presentation would benefit from additional supporting figures. It is a minor presentation request rather than a substantive debate.

## 12. [Show HN: Three Linux VMs in a browser tab, each running a different browser](https://news.ycombinator.com/item?id=50656036) (↑96, 💬25)
**Article:** The Show HN presents “Side by Side,” a demo running three Linux VMs in a single browser tab, each VM running a different browser. According to the comments, it appears built on unkernel/trynix, uses WebAssembly and a public Wisp relay for networking, and renders without GPU acceleration.

**Comments:** Commenters praise the demo and unkernel but debate practicality and security, arguing that memory-unsafe host browsers may undermine the isolation and that software rendering makes complex sites impractical. Others note Playwright already covers compatibility testing, while several report connection or vsock errors and ask about networking and ONNX downloads.

## 13. [Largest 2D Chart library in the world using BUI: BlenderUI](https://news.ycombinator.com/item?id=50658193) (↑14, 💬2)
**Article:** BUI Charts is presented as a large 2D chart library for BUI/BlenderUI, offering 80 chart types and 867 runnable examples. Charts are Rust rsx! components that accept arbitrary datasets via closures and support hover, legends, zoom, theming, and cached layouts. The docs organize charts into 7 base and 73 derived types and include installation and usage examples.

**Comments:** The two comments are positive: one says the catalog feels like going back to school and introduces unfamiliar chart types, while the other praises the breadth of examples. There is no debate.

## 14. [NormalScript: A perfectly normal scripting language](https://news.ycombinator.com/item?id=50651430) (↑49, 💬8)
**Article:** NormalScript is a satirical enterprise-styled site for a small JavaScript bytecode VM that embeds in Node or Bun without WASM, native addons, or workers. It runs strict-mode JavaScript subsets against host functions and supports pausing runs to bytes and resuming them, with limits, cancellation, snapshots, durable calls, and code-mode use cases. The site is intentionally absurd in tone and appears to switch branding/content, with PsychoScript referenced alongside NormalScript.

**Comments:** Commenters call the demo impressive and mind-melting, with one reporting a browser crash and linking the open-source site. Much of the thread is confused by the page changing between NormalScript and PsychoScript depending on GPU/cookies, notes WebGPU requirements, and shares spoilers that the “normal” version may be served only once.

## 15. [Curiosity Is No Solo Act](https://news.ycombinator.com/item?id=50636931) (↑108, 💬22)
**Article:** No article text was provided, only the title “Curiosity Is No Solo Act.” Therefore no content summary can be given from the available material.

**Comments:** Commenters heavily criticize the piece as dense, jargon-heavy, and hollow, saying its ideas could fit in two paragraphs and that it reads like an apology for AI or advertising. Others extract useful points about curiosity as connection-making, procedural knowledge, shared reality, and a future collaborative knowledge graph, while a side debate considers whether AI training-data attribution and compensation are technically or economically feasible.

## 16. [Google Will Make AI Agents Use Its MCP Servers. The Gmail One Can't Send Email](https://news.ycombinator.com/item?id=50653477) (↑165, 💬169)
**Article:** Google made its eight Workspace MCP servers generally available and added API terms requiring, from February 2027, any AI-driven tool to access Gmail, Drive, and Calendar through those servers rather than REST. The Gmail server notably omits send, reply, forward, and draft editing — those tools are partner-only — and agents calling REST directly get Standard-tier quotas. The addendum also bans training on Workspace data, caps retention of embeddings and indexes at 30 days, and requires self-declaration of AI-agent OAuth clients.

**Comments:** Commenters are largely skeptical or hostile, calling it a walled garden that favors Gemini and large partners like Anthropic over independent developers, and noting workarounds via SMTP/IMAP, browser automation, or local tooling. Several dispute the safety justification, pointing out MCP elicitation could gate sends, and question the legality of 30-day retention limits on users' own data. Practical fallout is flagged too: rclone's maintainer warns its built-in client ID will be rate-limited into unusability, while others recommend Fastmail or self-hosting.

## 17. [Lions' Commentary on Unix: Why It Was Secretly Copied for 20 Years](https://news.ycombinator.com/item?id=50651719) (↑264, 💬56)
**Article:** John Lions wrote lecture notes in 1976 explaining the Unix Version 6 kernel source for his University of New South Wales students, and the commentary circulated widely among licensees. After AT&T's 1979 Version 7 license restricted teaching that disclosed source code, the book was distributed only as unauthorized photocopies for roughly two decades. The Unix community, including Dennis Ritchie, repeatedly sought permission until SCO agreed and Peer-to-Peer Communications published the official edition in 1996.

**Comments:** Commenters share personal history — bootleg photocopies, original Western Electric copies, and one noting their licensed copy was entered as evidence in USL vs BSDI. There's debate over the book's value by 1996, with one long rebuttal arguing no other book (Bach, Goodheart, Xinu, even MINIX) combines full source with line-by-line commentary, making it uniquely useful for teaching. Others recommend successors like xv6, the Linux 0.12 commentary, and draw analogies to jazz's Real Book, alongside discussion of why AT&T couldn't sell software.

## 18. [Nextcloud Office Desktop app](https://news.ycombinator.com/item?id=50654289) (↑381, 💬190)
**Article:** Nextcloud announced general availability of its Nextcloud Office Desktop app powered by Euro-Office, a sovereign European open-source office suite first released in June 2026. The free app runs on Windows, macOS, and Linux with editors for documents, spreadsheets, presentations, and PDFs, supports offline editing, system fonts, digital signatures, and real-time co-editing when connected to a Nextcloud Hub instance. It's AGPL v3 licensed and available as signed installers or buildable from source.

**Comments:** Much of the thread centers on the app being a fork of ONLYOFFICE, with claims of controversy, counter-claims that it's an uncontroversial fork driven by the original project's AGPL misunderstanding and Russian-origin concerns, and a note that its changelog appears to miss security fixes from ONLYOFFICE 10.0.0. Others criticize the "Euro-Office" branding as bureaucratic or discount-sounding, dislike the Microsoft-style ribbon UI, and complain about Nextcloud's general usability, while some praise the spreadsheet performance and compare it to LibreOffice, SoftMaker, and vibe-coded clones like GridCraft.

## 19. [Show HN: SimDrop – Running iOS simulators in the macOS Finder sidebar](https://news.ycombinator.com/item?id=50657070) (↑25, 💬6)
**Article:** SimDrop is a GPL-3.0 macOS app that lists booted iOS simulators in the Finder sidebar as locations, letting users drag files into Photos and the Files app's Downloads folder, or pull them out. It uses a File Provider extension plus an unsandboxed launchd helper to run `simctl addmedia` and manage simulator folders, requires macOS 15+, and is distributed via Homebrew or a notarized DMG. The README documents quirks like drag-moves-by-default, read-only Photos, and a Photos.sqlite-backed listing.

**Comments:** The small thread mostly requests a screenshot, noting UI/UX repos often lack one. One commenter asks why the author chose a Finder extension over FSKit, and another questions the use of xcodegen given Xcode's newer JSON project format; the replies are terse, including a joke about "iPhone Duo" and an AI-assistant defaulting to xcodegen.

## 20. [Tell HN: Happy Thanksgiving](https://news.ycombinator.com/item?id=50655664) (↑529, 💬130)
**Article:** A short Tell HN post wishing readers a happy Thanksgiving, encouraging them to enjoy the day with friends and family or make it great regardless.

**Comments:** The thread is overwhelmingly warm, with gratitude for HN, its moderators, and the community, plus personal stories about family, health, immigration, and career luck. Notable subthreads include a professor's handwritten thank-you-note assignment, a WKRP "Turkeys Away" history digression, international greetings, and a few jokes about security incidents and quiet work weeks. A handful of comments push back with Indigenous-history links or mild sarcasm about the holiday.

## 21. [Moat: OpenRouter replacement](https://news.ycombinator.com/item?id=50652184) (↑222, 💬129)
**Article:** Moat is a subscription-based AI model router offering discounted wholesale access to models such as GLM, DeepSeek, Ling, and Kimi for $5/month billed yearly or $10/month, with no usage limits and no router fee. It markets itself as the “Costco of AI” and an OpenRouter replacement, listing member discounts and pay-per-token pricing.

**Comments:** Commenters heavily question trust and data governance, noting the site does not say where inference is served or whether prompts are retained/trained on, making it unsuitable for serious organizational use. Others argue it is not an OpenRouter replacement because it lacks prepaid credits and broad model choice, and criticize the “unlimited” subscription and yearly-price framing; some still like the Costco branding and value proposition.

## 22. [Discovery of curse ritual in trash dump surprises Egyptologist](https://news.ycombinator.com/item?id=50619466) (↑84, 💬49)
**Article:** Archaeologists found 40 charred, pierced papyrus fragments in a Thebes trash deposit, showing the Apophis curse ritual was performed and widespread, dating it about 3,400 years ago—1,000 years older than the known ritual manual. The ritual involved destroying images of the serpent Apophis by trampling, spitting, stabbing, and burning; researchers say trash deposits can reveal everyday temple life.

**Comments:** Commenters discuss selection bias in archaeology—common objects may survive poorly while rare valuables are preserved—and debate whether the find really implies widespread practice. The thread drifts into Eye of Horus/US dollar symbolism, cultural borrowing, and jokes about modern superstition and curse rituals.

## 23. [Holy shit holy shit holy shit holy shit: The magnitude of what’s now happening](https://news.ycombinator.com/item?id=50646108) (↑1947, 💬1790)
**Article:** Scott Aaronson describes being stunned by a wave of claimed AI-generated proofs in math and theoretical computer science—VP≠VNP, the Riemann Hypothesis, exact ω=9/4, and FFT gate lower bounds—and argues this feels like the start of an AI singularity in mathematics. He expects P≠NP may not be far off and mentions rumored but unverified AI-lab breakthroughs against deployed cryptography.

**Comments:** Commenters range from awe to skepticism, debating whether these results matter outside formal math, how proofs can be trusted if they take years to verify, and whether crypto-break rumors are credible or gag-ordered. Some frame AI as closing the loop only in verifiable domains like math and code, while others warn general capabilities imply wider disruption.

## 24. [Head of Software Engineering – NOX Metals](https://news.ycombinator.com/item?id=50654353) (↑1, 💬0)
**Article:** NOX Metals is hiring a Head of Software Engineering, citing rapid growth from $100k to $30M+ run rate, 0 to 75 employees, 600+ manufacturers, and $70M+ raised. The founder seeks a highly ambitious leader to scale products and locations, with the stated goal of shipping “every pound of metal in America.”

**Comments:** There are no comments on this story.

## 25. [An algebraic quantization of gravity from the null cone](https://news.ycombinator.com/item?id=50651863) (↑177, 💬57)
**Article:** The arXiv paper proposes a background-independent algebraic quantization of vacuum general relativity using intersecting null cones, a reduced phase space at finite Newton constant, and a type I algebra/Hilbert-space representation. It constructs a Lorentzian path integral, computes graviton pair creation nonperturbatively, derives finite-dimensional causal-diamond Hilbert spaces, recovers Bekenstein-Hawking entropy with a logarithmic correction, and obtains semiclassical Einstein equations at one loop.

**Comments:** Commenters note the author is serious—he coauthored work with Witten—but debate whether the paper is a major advance or AI-assisted “slop,” pointing to LLM collaboration and technical objections. Much discussion focuses on the lack of new testable predictions, whether it connects to the Standard Model/QFT, and calls to wait for field review rather than judge by AI involvement.

## 26. [IBM gives H-1B, green card holders 3 weeks to relocate from US or leave company](https://news.ycombinator.com/item?id=50658170) (↑56, 💬28)
**Article:** IBM has told US-based employees in its IBM Consulting division holding H-1B visas or green cards they have three weeks to decide whether to relocate abroad or leave the company, with December 31, 2026 as the last working day for those who decline. The company is ending visa and green card sponsorship for most consulting roles, and India appears to be the main destination, with 1,125 of 1,278 overseas consulting vacancies listed there.

**Comments:** Commenters immediately corrected the headline, noting green card holders need no sponsorship and can work anywhere, so the change is really about IBM no longer sponsoring applications for permanent residency. The thread splits into political argument over whether this protects US workers or simply offshores jobs to India — one subthread cites Snowflake's founders as evidence that restricting H-1Bs reduces US startups — alongside skepticism that IBM's motives are exploitative rather than economic.

## 27. [Denver man traps Waymo robotaxis with cones, eggs them at least 30 times](https://news.ycombinator.com/item?id=50659918) (↑9, 💬0)
**Article:** A Denver man has been boxing in Waymo robotaxis with orange traffic cones and then pelting them with eggs, with Waymo counting at least 30 incidents attributed to the same person. The cars' cautious programming means they won't drive over cones, and each egged vehicle needed about $2,000 in cleaning; the district attorney declined criminal charges, calling it a civil matter.

**Comments:** No comments were provided for this story.

## 28. [Collection of preserved UI style guides](https://news.ycombinator.com/item?id=50649834) (↑386, 💬91)
**Article:** Marcin Wichary has compiled a collection of preserved UI style guides and interface guidelines from the early 1980s to today, covering Amiga, Android, BlackBerry, CDE, Macintosh, NeXTSTEP, Palm, Nokia, OPEN LOOK, and many others. He scanned some documents himself, created mirrors of several minisites, and organized the collection by theme and era.

**Comments:** The thread is largely nostalgic appreciation, with readers requesting missing guides (Windows Vista/7 UX guidelines, KDE, Maemo, IBM Carbon) and reminiscing about OpenLook, WebOS, Metro, and PenPoint. A 1991 Amiga guide's random-gender-pronoun policy sparked a side debate on inclusive language, while several commenters noted the site appears LLM-assisted, citing typos, broken Symbian Belle and webOS links, and oddly harsh prose.

## 29. [Minipg: PostgreSQL as a Single Executable](https://news.ycombinator.com/item?id=50650892) (↑280, 💬44)
**Article:** minipg packages PostgreSQL into a single executable that embeds the postgres:18-alpine image and runs it via h9, a Plan 9-style kernel/hypervisor that executes Alpine binaries without Docker, a VM image, or a Linux kernel boot. A .pgdb directory holds the data, config, credentials, and version, with a server starting on demand and shutting down when idle; the author warns it is early and roughly 2x slower than native on the non-KVM backend.

**Comments:** Commenters praised the technical feat but questioned the use case, comparing it to PGlite and embedded-postgres, which run as libraries without a hypervisor layer. The author clarified that PGlite's single-connection limitation breaks existing apps, positioning minipg as a CLI-friendly Postgres for self-hosting and CI rather than a library, while others asked how it compares to Nix, Docker, and Podman setups and complained about the demo auto-downloading 35 MB.

## 30. [Show HN: Fuck_data_brokers.py](https://news.ycombinator.com/item?id=50658191) (↑151, 💬25)
**Article:** A developer released f*ck_data_brokers.py, a dependency-free Python script that sends legal opt-out and deletion requests to more than 600 registered data brokers on the user's behalf, tracking replies and following up on silent brokers. The README also promotes "Agent Garrett," a paid service that automates the same process persistently.

**Comments:** Commenters liked the concept but disliked the LLM-written README, the star-begging, and the upsell to a paid service in an open-source project. Others raised practical concerns — whether refusing ID requests lets brokers dodge deletion obligations, whether submitting data to opt-out forms hands brokers new information, and requests for EU (GDPR), Brazilian (LGPD), and California DROP support — plus skepticism about third-party removal services like Incogni.

---
_Generated 2026-11-26 16:06 MDT_

---

## Recent Digests

- [Nov 26](./archives/2026/nov/hn-digest-2026-11-26.md)
- [Nov 25](./archives/2026/nov/hn-digest-2026-11-25.md)
- [Nov 24](./archives/2026/nov/hn-digest-2026-11-24.md)
- [Nov 23](./archives/2026/nov/hn-digest-2026-11-23.md)
- [Nov 22](./archives/2026/nov/hn-digest-2026-11-22.md)
- [Nov 21](./archives/2026/nov/hn-digest-2026-11-21.md)
- [Nov 20](./archives/2026/nov/hn-digest-2026-11-20.md)

[Full archive](./archives/) (198 issues)

_If you want more, explore the [archive folder](./archives/)._
