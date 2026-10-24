# HN Digest — October 24, 2026

## 1. [Steal My Bitcoin](https://news.ycombinator.com/item?id=50224916) (↑167, 💬49)
**Article:** A Hacker News user built "stealmybitcoin.com," a deliberately vulnerable PHP server holding a bitcoin key worth about $500, accessible via a print-flag binary and running a pre-CVE PHP version. The challenge asks whether anyone can actually exploit the recent PHP2SHELL vulnerability in practice, with the first successful hacker claiming the wallet. All traffic is logged and the site warns it is not private.

**Comments:** Thread centers on the economics of the challenge — several argue $500 is too little to motivate skilled attackers or to justify revealing a working exploit, and that the time it stays unclaimed undercuts claims that AI agents are trivially exploiting everything at scale. Others counter that a low cost of entry (especially for LLM token spend) makes it worthwhile, that the challenge proves little either way since the server can lie, and that the author may be harvesting exploits from the logs. A subthread debates whether a white-hat hacker faces any real downside to participating.

## 2. [No Signs of AI Payoff Outside the Tech Sector](https://news.ycombinator.com/item?id=50224463) (↑330, 💬295)
**Article:** Apollo chief economist Torsten Slok argues AI has produced no measurable financial payoff outside the tech sector, citing flat revenue-per-worker, profit margins, and productivity growth for the S&P 493 versus rising figures for the Magnificent 7. He contends mainstream firms increasingly treat token spending as a cost center, and that AI's lack of judgment, accountability, and context limits its business value; the AI story will be decided outside the Mag 7.

**Comments:** Many commenters invoke the Solow productivity paradox, arguing it's simply too early and that major gains historically lag adoption by a decade or more, with electrification and PCs cited as analogies. Others argue the gains are being captured entirely as revenue by AI vendors, or that AI currently helps mainly where output is machine-verifiable (software), with non-tech firms lacking validation loops and integration. Skeptics note the "tech sector" finding really just describes seven companies, and some report real adoption friction with enterprise AI tooling.

## 3. [The Goose Programming Language](https://news.ycombinator.com/item?id=50224300) (↑146, 💬52)
**Article:** Goose is a new memory-safe systems language with no heap allocator, GC, or lifetime annotations, instead using compiler-managed data stacks with bump allocation and stable references. It stores nested data inline with no pointers, enables direct memory-mapping and validation of data structures, and reports benchmarks beating idiomatic C++ (3.3x) and safe Rust (1.12x) at lower memory use; it compiles to a single C file.

**Comments:** The main technical debate concerns how to handle arbitrary numbers of dynamically sized values — commenters ask about hash tables with strings and linked lists of strings, and the author explains arrays can hold variable-sized trees inline, with pools or fixed/fixed-capacity arrays as fallbacks. Several commenters criticize the prose as obvious AI writing and the benchmarks as under-optimized for C++/Rust (e.g., missing reserve/with_capacity), while others praise the documentation and design. The author confirms heavy Claude involvement and discusses prior art like ML Kit region inference.

## 4. [John Carmack on the Goose Language: multiple data stacks and relative references](https://news.ycombinator.com/item?id=50224100) (↑116, 💬49)
**Article:** John Carmack praised Goose on X, saying its automatic multi-stack analysis and resizable inline fields move the approach from "lots of work can be done this way" to "basically everything can be," and that relative references and built-in binary validation enable direct memory-mapping of file and network data, which is often 100x slower than necessary to parse. Author Wouter van Oortmerssen replied that people have ported complex code like compilers to it.

**Comments:** The author answers questions on design details: workers are threads with separate memory (runtime uses atomics internally), only top-level growable arrays get stacks, and out-of-order frees require pools; he explains the AI-assisted development process seeded from his Lobster compiler. Commenters ask about region-inference prior art, memory overhead of many address-space reservations, and thread stack limits, while some dispute whether Carmack was actually endorsing Goose or responding to an unseen thread. A smaller thread debates how to register X threads without login.

## 5. [Listen and read USA nuclear forces Emergency Action Messages, heard on 11175 kHz](https://news.ycombinator.com/item?id=50224422) (↑67, 💬33)
**Article:** Missileer.watch is a site presenting intercepted HFGCS Emergency Action Messages heard on 11175 kHz USB, offering recordings, decodes, and a status view under a CC0 public-domain release. The page is mostly static, stores minimal data, and notes that the net is quiet until there are messages. It frames the audio as something anyone outside the force can listen to.

**Comments:** Most commenters downplay significance, emphasizing that EAMs are encrypted (likely one-time pad) and repeat endlessly as tests, with activity spikes meaning nothing; one Navy veteran describes relaying such messages during a doomsday exercise. A recurring aside notes the site's text reads as obviously AI-generated, sparking comparisons of Claude models' writing styles. Others share trivia about Skyking test messages using pop-culture references and link to priyom.org and related resources.

## 6. [Roku developer repositories moved from GitHub to GitLab](https://news.ycombinator.com/item?id=50222622) (↑218, 💬145)
**Article:** Roku moved its developer repositories from GitHub to GitLab. The linked article provides little detail beyond the move itself, so the reason is not clearly established in the available text.

**Comments:** Commenters debate GitHub versus GitLab, citing GitHub outages, Microsoft ownership, CI capabilities, and GitLab’s fit for organizational projects. Some favor self-hosting or alternatives like Dagger, while others question why the move is newsworthy and note incidental issues such as F-Droid’s GitLab requirements and Roku’s pending acquisition by Fox.

## 7. [Dream-1](https://news.ycombinator.com/item?id=50223785) (↑125, 💬62)
**Article:** Dream Labs introduced Dream-1, a World Action Model API that claims zero-shot control of unseen robots and tasks for $3/hour, backed by $90M in seed funding. The article argues cheap robot hardware plus generalizable models could break robotics’ data chicken-and-egg problem.

**Comments:** Commenters are skeptical, calling the announcement overhyped, possibly AI-written, and optimized for investors rather than real automation customers. Others raise concerns about unreliable demos, third-party control of home robots, labor and economic impacts, and whether the approach is more impressive than competing robotics efforts.

## 8. [The St. Helena 5 pence coin shows Jonathan, a roughly 190 year old tortoise](https://news.ycombinator.com/item?id=50222927) (↑76, 💬15)
**Article:** The Numista page catalogs a St. Helena 5 pence coin featuring Jonathan, a roughly 190-year-old giant tortoise. It lists coin specifications, mintage years, values, and designers.

**Comments:** Commenters focus on anecdotes about Jonathan’s companions fighting and flipping over, including human intervention to right them. Others discuss travel to St. Helena and Tristan da Cunha, why evolution has not solved flipping, and whether a sensor could alert staff.

## 9. [FreeDNS](https://news.ycombinator.com/item?id=50222133) (↑214, 💬56)
**Article:** FreeDNS (afraid.org) offers free dynamic DNS, static DNS, subdomain hosting, backup DNS, and URL redirection, with premium options and a public API. The page includes usage examples, service statistics, and account information.

**Comments:** Longtime users praise FreeDNS as a durable, useful service for DDNS, testing, and backup DNS. Commenters also note pain points around the public suffix list, cookies, HTTPS certificate limits, abuse, sustainability, and continuity, while discussing alternatives and whether it is hosted DNS rather than a registrar or resolver.

## 10. [Danish Government silently drops plan to dump MS Office](https://news.ycombinator.com/item?id=50223844) (↑164, 💬101)
**Article:** A Danish Computerworld article reports that the Digitalisation Ministry quietly dropped a pilot testing Collabora as an open-source alternative to Microsoft Office. The pilot began in summer 2025 with about 40 employees, was paused after an election, and was not evaluated, with reported frustrations around typography and track changes.

**Comments:** Commenters debate why office-suite migration is hard, citing social resistance, training demands, Excel lock-in, mail-merge and formatting compatibility, and migration tools. Some argue LibreOffice or OnlyOffice are sufficient, while others say Microsoft Office remains superior for document-heavy work and note repeated European government promises to reduce Microsoft dependence.

## 11. [Neural chip decodes interactions between brain regions](https://news.ycombinator.com/item?id=50222525) (↑73, 💬22)
**Article:** EPFL researchers developed LogSync, a low-power implantable neural system-on-chip that records cross-regional brain activity, extracts synchrony and oscillation biomarkers, and uses machine learning to classify cognitive and emotional states and trigger stimulation. It was validated on human iEEG datasets and in rats, operating under 200 microwatts and targeting adaptive deep brain stimulation for psychiatric disorders.

**Comments:** Commenters question the reported classification metrics without base rates or comparisons to simpler probes, and some note existing implantable neurotech such as NeuroPace. Others discuss how to define cognitive states, the blurred distinction between cognition and emotion, and whether exercise could address mental disorders, with several side threads on sci-fi and ethical implications.

## 12. [I don't understand quantum physics (2018)](https://news.ycombinator.com/item?id=50219666) (↑249, 💬183)
**Article:** The supplied article text is corrupted and unreadable, so a reliable content summary is not possible; commenters identify it as a 2018 lecture-style piece by Prof. Douglas Ross on quantum mechanics and interpretations such as Copenhagen and Many Worlds.

**Comments:** The thread debates Many Worlds versus Copenhagen, whether interpretations add scientific content, Bell’s theorem and hidden variables, and whether quantum mechanics can truly be “understood.” Many commenters recommend books and learning resources, while others argue over instrumentalism, realism, and Feynman’s famous quote.

## 13. [OBS Studio 33](https://news.ycombinator.com/item?id=50218430) (↑430, 💬154)
**Article:** OBS Studio 33.0.0 updates CEF from 127 to 150, overhauls plugin loading, improves source snapping and spinbox behavior, enables NVENC on Arm64, fixes numerous crashes and capture issues, and drops Ubuntu 24.04 support. It also includes developer API changes and updated toolchain requirements.

**Comments:** Commenters praise OBS for uses ranging from VR streaming to lecture recording and family-tape digitization, while criticizing the long-delayed CEF update tied to an RCE and various bugs. A major debate concerns the project’s ban on AI-generated contributions and an AI-banned contributor’s Rust fork, alongside complaints about dynamic display/audio setups and macOS capture issues.

## 14. [Node2Shell evolves to HTTP2Shell, blast radius affects many HTTP libs and apps](https://news.ycombinator.com/item?id=50219177) (↑253, 💬125)
**Article:** CVE-2026-111497 is an out-of-bounds write in Google’s Brotli decoder versions 1.0.3 through 1.2.0, allowing memory corruption or potential remote code execution when decoding attacker-controlled Brotli data. The flaw affects Node.js, Python packages, Bun, Envoy, curl, and other software bundling Brotli, with patches and mitigation advice provided.

**Comments:** Commenters criticize the “HTTP2Shell” name as misleading and sensational, preferring “Brotli2Shell” or the CVE identifier. Discussion covers the unusual delay between the February root-cause fix and public security recognition, urgent patching versus dependency cooldowns, supply-chain risk, C versus Rust, and whether proxies or default configurations mitigate exposure.

## 15. [Symbolic Learning in Python and Julia](https://news.ycombinator.com/item?id=50171936) (↑44, 💬5)
**Article:** PySR is an open-source symbolic regression tool for Python and Julia that searches for interpretable symbolic expressions optimizing an objective, using Julia’s SymbolicRegression.jl as its search engine. It emphasizes performance, configurability, scikit-learn-style APIs, and installation via pip, conda, Docker, or Apptainer.

**Comments:** Commenters ask whether the Julia component is compiled with JuliaC and discuss a related deterministic symbolic-regression project ported to JAX. One commenter complains about the overhead of two interpreters, two GCs, and nondeterministic performance, while another notes the post’s timestamp was refreshed by HN’s second-chance pool.

## 16. [SpeedCrunch 1.1](https://news.ycombinator.com/item?id=50224210) (↑12, 💬2)
**Article:** SpeedCrunch 1.1 is a free, open-source high-precision scientific calculator for Windows, macOS, and Linux, offering up to 50 digits of precision, complex numbers, 140+ functions, units, constants, variables, vectors, and matrices. It also supports history rewriting, customizable keypads and layouts, multiple sessions, 40+ translations, and over 40 color schemes.

**Comments:** One commenter praises SpeedCrunch as the most useful calculator, citing bit shifts and radix conversions and years of use after missing the Windows 2000 calculator. Another links to the changelog and says they used SpeedCrunch heavily but now prefer Numbat.

## 17. [Full Disk Encryption on Fedora with TPM2](https://news.ycombinator.com/item?id=50194602) (↑4, 💬0)
**Article:** The article walks through full-disk encryption on Fedora using LUKS2 and TPM2, covering key slots, header backup, passphrase and keyfile management, recovery keys, and TPM enrollment with systemd-cryptenroll. It also explains binding to PCR 7 with an optional PIN, updating crypttab, and rebuilding the initramfs so Fedora’s encrypted root can unlock automatically.

**Comments:** No comments were posted.

## 18. [Zac-OS-9: The classic Platinum desktop, reborn for modern PCs](https://news.ycombinator.com/item?id=50189981) (↑32, 💬20)
**Article:** Zac-OS-9 is a beta GPLv3 project that recreates a Mac OS 8/9-style Platinum desktop for Debian Linux, with a custom window manager, file browser, menu bar, control panels, and classic Mac visual details. It runs Debian and Flathub applications, includes a SheepShaver emulator for classic Mac OS with a user-supplied ROM, and supports AFP/AppleTalk, SMB, HFS/HFS+, Wine, and live USB installation.

**Comments:** Commenters debate whether the project is “vibe-coded” or AI-generated, with critics citing the commit history and LLM-style writing while others defend the concept and the author’s transparency. The author acknowledges using AI for coding, describes Zac-OS as a personal daily-driver project, and answers questions about SheepShaver integration and drag-and-drop support.

## 19. [Physicists trap a single antimatter particle for a month](https://news.ycombinator.com/item?id=50186450) (↑258, 💬77)
**Article:** Physicists trapped a single positron for about a month by moderating positrons from sodium-22 decay in tungsten and holding them in an electromagnetic trap near absolute zero. The achievement enables precise quantum measurements of the positron’s magnetic moment, which could be compared with the electron’s to test the Standard Model and help explain why the universe is dominated by matter.

**Comments:** Commenters ask how researchers know only one particle is trapped and how annihilation, release, and safety work; detailed replies explain image-current detection and damping, while others discuss antimatter propulsion and PET sources. Many comments are jokes about “antimatter cruelty,” ethics, and sci-fi scenarios, alongside serious notes on the measurement’s significance.

## 20. [GPU-unlock: FP/BF16 instruction issue rate on Nvidia 3000's cards](https://news.ycombinator.com/item?id=50219700) (↑148, 💬56)
**Article:** GPU-unlock is a Linux kernel module that unlocks FP/BF16 FMA instruction issue rates on Nvidia RTX 3000 cards by writing speed selectors before the NVIDIA driver binds, avoiding per-driver patching. Reported gains include large BF16 GEMM speedups on several GA102/GA104/GA106 cards, with benefits mainly for compute-bound workloads such as LLM prefill, diffusion, and training rather than memory-bandwidth-bound decode.

**Comments:** The author explains the approach and users report real gains, while discussion focuses on power limits, heat, cooling, and workload-dependent results. Commenters also mention related P2P and Ada/4090 unlock forks, question headline accuracy and card coverage, and note that Hopper/Blackwell’s different boot security likely makes 50-series unlocks harder.

## 21. [TornadoVM 7 Enables GPU-Native Workloads from Java Applications](https://news.ycombinator.com/item?id=50192975) (↑81, 💬14)
**Article:** TornadoVM 7.3 is an open-source Java framework that automatically accelerates Java programs on CPUs and GPUs while running alongside existing JVMs. Version 7 replaces JNI with the Foreign Function & Memory API, removes JVMCI, unifies compiler metadata access across supported JDKs, and adds deeper Nvidia CUDA integration including cuTile support.

**Comments:** Commenters praise the simple matrix-multiply example and discuss whether this enables Java-based AI infrastructure or a “JAX for Java.” Key questions include TPU support, the future of Java’s Vector API, and why it is called a VM when it ships as a JAR; others point to related projects such as jitllm and qxotic.ai.

## 22. [Local Wikipedia: Wikipedia, but only for things a half hour walk from you](https://news.ycombinator.com/item?id=50202285) (↑1526, 💬240)
**Article:** Local Wikipedia is a browser-based tool that shows geocoded Wikipedia articles near a chosen location, framed as things within about a half-hour walk. It uses Wikipedia’s nearby data, keeps location in the browser, and falls back to the closest 25 articles within roughly six miles when local coverage is sparse.

**Comments:** Users enjoy discovering nearby history and landmarks, but many request configurable distance, language support, category filters, and better handling of rural areas. Commenters note it largely wraps Wikipedia’s Special:Nearby feature, point to alternatives like Inquire, OsmAnd, wiki-map, and LocalWiki, and discuss missing geotags and English-only limitations.

## 23. [Twelve years of distributed SQLite](https://news.ycombinator.com/item?id=50217500) (↑350, 💬57)
**Article:** rqlite creator Philip O’Toole recounts twelve years of distributed SQLite, starting with rqlite’s 2014 design combining SQLite with Raft for a CP replicated database. He traces related projects including dqlite, Litestream, cr-sqlite, libSQL/Turso, and Cloudflare D1, arguing the design space has consensus, streaming, and merge approaches while platform companies captured most of the commercial value.

**Comments:** Commenters debate transaction support, D1 reliability, benchmarks, and when rqlite’s replicated CP model is worth it versus SQLite plus Litestream. Many praise rqlite and its maintainer, while others criticize the post’s ending and accuse it of being AI-generated; some request comparison tables and Jepsen testing.

## 24. [Oai-math-revised: a community hub for revising OpenAI's math write-ups](https://news.ycombinator.com/item?id=50222283) (↑23, 💬17)
**Article:** A guest post on Terence Tao’s blog announces oai-math-revised, a community GitHub hub for improving OpenAI’s math write-ups, which organizers say can be hard to understand and have incomplete citations. It invites students, postdocs, professors, and enthusiasts to browse the repository and volunteer as admins or reviewers by category.

**Comments:** The thread is largely skeptical, framing the effort as unpaid labor for OpenAI, a soft-power move, or a way to generate training data. Some commenters discuss formal verification and “verified-but-unproven” results, while others debate open-weight models and the broader labor effects of AI progress.

## 25. [Why is AI generated language so hard to understand?](https://news.ycombinator.com/item?id=50223647) (↑122, 💬117)
**Article:** An arXiv psycholinguistics paper finds that frontier and near-frontier LLMs use constructions associated with human processing difficulty more often than human writing or round-trip paraphrases, including inanimate subjects with animate verbs, low-frequency n-grams, longer dependencies, and stacked nouns. It hypothesizes that AI text is optimized for information density in math, code, and reasoning rather than communication, and tests this with a length-penalty fine-tuning proof of concept.

**Comments:** Technical writers argue RLHF rewards what looks like good writing—lists, headings, catchy phrases—rather than audience usefulness, while others point to token compression, lack of an audience model, and AI-to-AI communication. Some commenters find AI text dense and hard to parse, others find it fluffy or say they have no trouble; several note model-specific regressions and suggest prompting or editing remedies.

## 26. [Cecilia Berdichevsky, Clementina expert (1961)](https://news.ycombinator.com/item?id=50179920) (↑28, 💬2)
**Article:** Cecilia Berdichevsky was an Argentine computer scientist born Mirjam Tuwjasz in Poland who emigrated as a child. She worked on the Ferranti Mercury computer “Clementina” at the University of Buenos Aires, wrote one of its first programs, and later studied in London before returning as a Clementina expert. After the 1966 coup, she worked in accounting and later banking/IT roles, including representation in IFIP and UNDP projects.

**Comments:** One commenter discusses the origin of the “Clementina” nickname from “Oh My Darling, Clementine” and links related videos. Another notes that the English Wikipedia page is much more detailed than the Spanish one and points to a Spanish-language book on Argentine computing history.

## 27. [PHP Foundation 'under-funded' with one full-time staff member, director says](https://news.ycombinator.com/item?id=50224074) (↑94, 💬51)
**Article:** Article content was unavailable; the title says the PHP Foundation is “under-funded” and has only one full-time staff member, according to its director.

**Comments:** Commenters link Open Collective expense data and note a roughly $350k declining balance, arguing that more corporate sponsorship is needed for core maintenance. The thread debates OSS sustainability and corporate capture, including whether users owe financial support and whether PHP should be sunset or maintained because of widespread legacy use. Suggestions include nonprofit discounts, licensing votes, and a large structured fund from major beneficiaries.

## 28. [How close can pure functional programming get to C?](https://news.ycombinator.com/item?id=50218195) (↑243, 💬81)
**Article:** The post examines how close pure functional programming can get to C performance using Roc’s DEFLATE implementation against libdeflate. On the Silesia corpus, roc-deflate produced identical outputs and was within roughly 2.6% median slowdown on an M1 MacBook Pro and 8.9% on a Ryzen 3900X, while still trailing libdeflate’s highly tuned SIMD implementation.

**Comments:** Commenters debate why C/C++ can be faster, citing copy elision, direct mutation, and memory locality, while others note SIMD is a major factor. Several argue the comparison to miniz_oxide is unfair because zlib-rs is a faster Rust baseline, and others discuss Roc’s immaturity versus reported production use. There is also side debate about type checking, LLM-generated code, and whether functional languages can close the remaining gap.

## 29. [Bringing uv and ty together](https://news.ycombinator.com/item?id=50172962) (↑282, 💬97)
**Article:** Astral announced experimental integration between uv and ty, adding first-class support for PEP 723 Python scripts and a unified `uv check` command. The integration lets ty use uv workspace metadata and script dependency declarations to prepare environments for type checking and editor features, as part of a broader integrated Astral toolchain.

**Comments:** Some commenters welcome the improved editor support for single-file scripts and the convenience of a unified check command. Others worry about CLI fragmentation, uv’s opinionated lockfile and ecosystem lock-in, and whether ty should remain standalone or be integrated with Ruff instead. There is also debate over ty versus Pyrefly/mypy, the value of type hints, and concerns about Astral’s acquisition by OpenAI.

## 30. [Tiling Noise – Procedural GPU Patterns](https://news.ycombinator.com/item?id=50180251) (↑58, 💬2)
**Article:** This Godot shader tutorial explains how to make value noise tile seamlessly, including applying it to a torus and fixing UV seams. It shows how to wrap lattice coordinates, notes limitations such as integer frequencies and even frequencies for animation, and adds an optional tiling toggle.

**Comments:** One commenter shares a compact JavaScript non-GPU Perlin/value-noise implementation with wrapping support, noting it is somewhat cryptic because it is used for size coding. Another praises Catlike Coding and Jasper Flick as a long-standing high-quality resource.

---
_Generated 2026-10-24 16:05 MDT_

---

## Recent Digests

- [Oct 24](./archives/2026/oct/hn-digest-2026-10-24.md)
- [Oct 23](./archives/2026/oct/hn-digest-2026-10-23.md)
- [Oct 22](./archives/2026/oct/hn-digest-2026-10-22.md)
- [Oct 21](./archives/2026/oct/hn-digest-2026-10-21.md)
- [Oct 20](./archives/2026/oct/hn-digest-2026-10-20.md)
- [Oct 19](./archives/2026/oct/hn-digest-2026-10-19.md)
- [Oct 18](./archives/2026/oct/hn-digest-2026-10-18.md)

[Full archive](./archives/) (165 issues)

_If you want more, explore the [archive folder](./archives/)._
