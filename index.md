# HN Digest — November 14, 2026

## 1. [Lovable apps expose passport details and more than 200K private messages](https://news.ycombinator.com/item?id=50499017) (↑487, 💬175)
**Article:** A security research report examined 159,041 Lovable projects and found many Supabase-backed apps exposed sensitive data such as passport details, chat messages, profiles, and payment records without login. It attributes the issue to missing access controls/default configurations and argues that Lovable's low-code marketing creates a gap with customers' security responsibilities, while noting methodological limitations and recommending expert review.

**Comments:** The author participated, and commenters debated whether Supabase's permissive defaults or Lovable's marketing bear more blame, with several calling for deny-by-default databases, least-privilege APIs, and automated auth tests. Some stressed that data breaches predate AI but that AI-generated apps are easier to find and more numerous; others pushed back on broad comparisons, noted authorization rather than authentication is the core issue, and suggested using Lovable for prototypes then ejecting and reviewing. There was also discussion of GDPR/liability, platform responsibility, and skepticism toward AI hype.

## 2. [SpaceX Catches the Starship to end Flight 15](https://news.ycombinator.com/item?id=50500963) (↑209, 💬105)
**Article:** The linked item is a SpaceX live broadcast/replay page for Starship Flight 15, showing that the broadcast has ended. It provides almost no written article content beyond the event stream and chat interface.

**Comments:** Commenters overwhelmingly celebrated the catch of the Starship upper stage as a historic, precision engineering achievement and compared it to Apollo-era milestones. They discussed why the booster was not caught, citing low fuel margins and communication/safety concerns, and debated reusability economics, the rocket equation, and whether space spending is justified. A few noted media understatement of the milestone and skepticism about hype or commercialization.

## 3. [A Family Tree of Software Job Titles](https://news.ycombinator.com/item?id=50499038) (↑127, 💬56)
**Article:** The article presents a family tree of 104 software job titles from the 1940s to the present, rendered from Graphviz and JSON and grouped into development, operations, security, data/AI, quality, and support families. It highlights patterns such as coding's clerical origins, titles splitting and recombining, recycled names like "systems engineer," short-lived roles like prompt engineer, and the recurring DevOps/SRE/platform-engineering debate.

**Comments:** Commenters shared personal title histories and agreed that many labels are organization-specific and often meaningless, with DevOps frequently becoming a bottleneck rather than a culture. They noted missing titles such as Member of Technical Staff, systems software engineer, web designer, and prompt engineer, and debated whether Scrum/Agile is declining and how AI will reshape roles. Some criticized the chart's navigation, while others discussed QA erosion, on-call ownership, and the value of history in explaining title differences.

## 4. [PyPI's redesigned project pages with clearer security signals are now live](https://news.ycombinator.com/item?id=50497892) (↑172, 💬78)
**Article:** PyPI launched redesigned project pages with a new security tab that surfaces release provenance and per-file attestations, including full, no, incomplete, inconsistent, changed, and lost provenance states. The redesign adds prominent provenance warnings, reordered metadata, and release-file/history views to help users assess package origins and suspicious changes.

**Comments:** Commenters welcomed the provenance work but debated its centralization around large forges and trusted publishing, with maintainers explaining that publisher providers must meet key-management and security requirements. Some users asked for personal-key, local-build, email, or smaller-forge attestations and reusable workflows, while others argued the signals detect account/package compromise rather than malicious projects and may not be seen by most users. PyPI maintainers also corrected claims about permanence and clarified that Microsoft did not fund the work.

## 5. [KDE: The documentary [video]](https://news.ycombinator.com/item?id=50496976) (↑320, 💬69)
**Article:** The linked item is a PeerTube page for a documentary about KDE's history and community. The available page content only shows a browser-compatibility message rather than substantive article text.

**Comments:** Longtime KDE users shared nostalgia and praise for its stability, configurability, and ancillary tools, while recalling the rough KDE 4 transition and comparing it favorably with GNOME. Commenters discussed Trinity for a KDE 3-style desktop, Valve's support for KDE on SteamOS, Qt's corporate history, and the documentary's limited coverage of the last 10–15 years. Some joked or complained that many interviewees appeared to use macOS.

## 6. [Seagate's new hybrid drive raises some old questions](https://news.ycombinator.com/item?id=50453901) (↑51, 💬21)
**Article:** Seagate announced FireCuda Forge hybrid drives that pair an HDD with a user-supplied NVMe SSD via its Alkemi platform; the 8TB model costs $699 and the 20TB $899, neither includes the SSD, and SSD capacity is capped at 1TB. The article frames this as a revival of hybrid drives amid soaring storage prices and notes unresolved questions about tiering, failure handling, and data placement compared with Apple Fusion Drive and Intel SRT.

**Comments:** Commenters criticize the 8TB model’s value against cheaper high-capacity HDDs and discuss Linux tiering options such as ZFS, bcache, LVM cache, and application-level approaches. Many note global HDD price spikes, reliability and opacity concerns, and skepticism that ordinary users can tune tiered storage, while some see enclosure-managed tiering as sensible.

## 7. ['Grey Rocking': The Life-Improving Power of Being Really, Really Boring (2021)](https://news.ycombinator.com/item?id=50471874) (↑42, 💬18)
**Article:** The article explains grey rocking, a technique coined in 2012 for becoming deliberately boring and unresponsive to deny drama-seeking or toxic people the reaction they want. It describes serious uses with narcissists and psychopaths and everyday uses in family or work groups, while warning that sustained use can suppress genuine feelings and feel like a nuclear option.

**Comments:** Commenters debate whether grey rocking works only against drama addicts or simply invites steamrolling, self-betrayal, and low boundaries; some say toxic people may turn it into a battle of wills. Others share practical variants like brief neutral replies or “Yikes,” compare it to Stoicism, and call it a defensive manipulation tactic best reserved for harmful communication.

## 8. [Why get an expensive Pi when I have an old phone?](https://news.ycombinator.com/item?id=50440709) (↑466, 💬266)
**Article:** The author argues a used Android phone can replace an expensive Raspberry Pi setup for projects needing camera, GPS, storage, battery, display, and cellular, citing ¥300–500 phones versus a Pi build costing far more. They describe rooting a Redmi, using a Huawei in kiosk mode, and note the open question is whether matching used phones can be sourced reliably at scale.

**Comments:** Commenters weigh phones’ advantages against Pis’ maintained OS, GPIO, documentation, consistency, and supply. Major concerns include battery swelling and fire risk, poor long-term software support, difficult rooting and locked bootloaders, 24/7 reliability, and lack of Ethernet or SSD, though some report success with Termux, PostmarketOS/Nerves, k3s clusters, old laptops, or mini PCs.

## 9. [Advancing science and engineering with Antigravity's /teamwork](https://news.ycombinator.com/item?id=50496811) (↑137, 💬33)
**Article:** Google Research describes Antigravity’s /teamwork multi-agent workflows using Gemini 4 models, claiming results on open math problems, formal verification, molecular structure elucidation, kernel optimization, and large Rust rewrites. It explains the design around parallel exploration, external verifiers and falsifiers, context partitioning, and declarative workflow patterns routed per task.

**Comments:** Commenters criticize the post as dense and unclear, suspecting AI-generated writing, and question how /teamwork differs from Claude and Codex agent workflows; some report Antigravity’s harness is slow, ceremony-heavy, and rough. Others cite evidence that role-based multi-agent setups improve performance and welcome the example results, while some question claims such as Rust rewrites being faster than optimized C++.

## 10. [Show HN: DeepSeek V3 in ~200 lines of pure Jax](https://news.ycombinator.com/item?id=50497589) (↑116, 💬7)
**Article:** The Show HN presents a 190-line pure-JAX implementation of DeepSeek V3’s key ideas—MLA, DeepSeekMoE with auxiliary-loss-free balancing, and multi-token prediction—trained from scratch on a MacBook Air. The 36.2M-parameter demo trained for about 2.6 hours on detective fiction and released the checkpoint and data, with a write-up explaining the code.

**Comments:** Commenters praise the first-principles recreation and ask for learning roadmaps; replies recommend 3Blue1Brown and Karpathy resources. One user reports running it end-to-end on an AMD ROCm GPU with specific environment flags and submitted a container PR, while others discuss using standard datasets for comparability and applying the approach to small models.

## 11. [LinkedIn, Monster take down over 1000 fake job postings after CBC investigation](https://news.ycombinator.com/item?id=50499723) (↑122, 💬50)
**Article:** A CBC visual investigation found more than 1,500 misleading job postings on LinkedIn and Monster that funnelled applicants toward the MLM company Evolution Travel. The ads promised remote travel jobs paying up to $75,000, but instead led to information sessions requiring upfront payments and monthly subscriptions plus recruitment of others. LinkedIn removed about 900 listings and Monster removed 600 after CBC flagged them.

**Comments:** Commenters debated how much of the online economy depends on scams, with many citing fake listings, AI-generated posts, and manipulated reviews. Some said LinkedIn is increasingly unreliable for job hunting, while others reported getting jobs through it. There was broad agreement that platforms need stronger enforcement against ghost and misleading listings.

## 12. [Reverse engineering a vintage diode-transistor logic chip](https://news.ycombinator.com/item?id=50416011) (↑73, 💬3)
**Article:** Ken Shirriff reverse-engineered an unidentified vintage IC from CuriousMarc’s collection and identified it as the Signetics ST680A, part of the 600 series from 1965. The chip implements four diode-transistor logic NAND gates, and the article explains its NPN transistors, diodes, resistors, reconstructed metal layer, and DTL operation. It also notes puzzles such as two apparently unused diodes.

**Comments:** The author joined the thread to answer questions about DTL. Commenters asked why DTL is slower than TTL and whether similar reverse-engineering methods could analyze modern chips like Apple’s M1. One commenter simply encouraged the author to write a book.

## 13. [Generative AI uses more energy on non-English text](https://news.ycombinator.com/item?id=50441444) (↑155, 💬89)
**Article:** The article content was unavailable, but the title and discussion concern research finding that generative AI models use more energy on non-English text.

**Comments:** The main debate focused on tokenizer fairness: English is heavily optimized, so non-English prompts can consume more tokens and energy. Some proposed dynamic byte-chunking architectures or language-specific tokenizers, while others criticized the paper’s older models and methodology. Several commenters said they already prompt in English to save tokens and improve efficiency.

## 14. [Show HN: A terminal-native idle factory game, written in Rust with ratatui](https://news.ycombinator.com/item?id=50497132) (↑117, 💬24)
**Article:** This Show HN presents Terminactory, a terminal-native idle factory game written in Rust with ratatui. It is designed to run in a terminal split beside AI agents, and agents can send short in-game messages via Claude Code hooks using a low-token command. The project is hosted on GitLab under an Apache 2.0 license.

**Comments:** Commenters compared it to Factorio and Dwarf Fortress and asked what differentiates it beyond running in a terminal. The developer highlighted agent telegrams, optional lore, and quality-of-life features like blueprints. Others suggested Nerd Font icons and using such games as benchmarks for agent architectures.

## 15. [Will we put data centers in space?](https://news.ycombinator.com/item?id=50498945) (↑37, 💬108)
**Article:** This report assesses the technical and economic feasibility of orbital data centers, arguing the case depends heavily on low launch costs. Space solar could reach parity around $250/kg and beat terrestrial energy near $50/kg, versus current costs around $1,500/kg, with Starship as the key near-term enabler. Cooling appears more manageable than often assumed, but radiation, chip failure, bandwidth limits, and supply-chain immaturity remain obstacles; meaningful scale is unlikely before 2030.

**Comments:** Many commenters were skeptical, citing launch-cost assumptions, cooling and radiation risks, debris/security concerns, and cheaper terrestrial alternatives such as ocean, underground, or remote land sites. Others argued the article’s engineering case is stronger than critics admit and that orbital compute could benefit from 24/7 solar and fewer permitting constraints. A recurring meta-debate concerned whether commenters were engaging with the report’s calculations or just reacting from intuition.

## 16. [Monkey Island: all 13 versions side by side](https://news.ycombinator.com/item?id=50493904) (↑440, 💬141)
**Article:** An interactive fan-made site compares 13 versions of “The Secret of Monkey Island” side by side across 12 scenes, with 156 screens captured via ScummVM and Hatari. It includes version details, CRT shader options, zoom/compare tools, and a Borland Turbo Vision-style interface.

**Comments:** Commenters share nostalgia for CGA/EGA/VGA, Amiga, Atari ST, and Mac versions, debating which looked best and how hardware constraints shaped creativity. Some argue CGA’s palette was genuinely bad, while others praise the site’s design and note missing versions such as C64 or the anniversary release.

## 17. [Dartmouth (Guarini) will not admit math PhD cohort this year](https://news.ycombinator.com/item?id=50499945) (↑44, 💬7)
**Article:** Dartmouth’s Guarini School suspended admissions to its math Ph.D. program for the 2027–2028 cycle pending a department review. Current students’ funding and requirements remain unchanged, but submitted applications will not be reviewed, and faculty and students raised concerns about transparency and effects on undergraduate courses.

**Comments:** Commenters criticize the administration’s decision and messaging, linking it to Dartmouth’s stated $50 million spending reduction and skepticism about salary claims. Several suggest cutting administrative staff or automating admin work instead, while others argue the move damages trust in the program.

## 18. [Project Zero will disclose vulnerabilities 90 days after reporting](https://news.ycombinator.com/item?id=50496051) (↑94, 💬14)
**Article:** Project Zero announced a new “Full X” disclosure policy: vulnerabilities will be disclosed 90 days after reporting now, then 60 days in February 2027 and 30 days in January 2028. It cites AI-assisted vulnerability discovery and exploitation, faster patch reverse-engineering, and growing bug volume as reasons to remove most grace-period and variant exceptions.

**Comments:** Commenters debate whether 90 days is too long, with some disclosing on 30-day timelines and others defending gradual reduction. Threads digress into AI-assisted bug discovery, trust in automated fixes, and skepticism about vendors’ incentives.

## 19. [Demystifying phone unlocking tools: A technical overview](https://news.ycombinator.com/item?id=50497416) (↑48, 💬0)
**Article:** This technical overview explains how commercial phone-unlocking and forensic tools exploit mobile device attack surfaces rather than using magic. It covers Android/iOS hardware security architecture, including TrustZone’s Normal and Secure Worlds, Gatekeeper/Keymaster, Secure Elements, and the verified boot chain.

**Comments:** No comments were provided.

## 20. [Tech Companies Are Trying to Shift the Concept of Privacy (Again)](https://news.ycombinator.com/item?id=50496602) (↑389, 💬151)
**Article:** EFF argues that always-on recording and transcription devices—smart glasses, wearables, and ambient AI gadgets—shift privacy burdens onto bystanders who cannot meaningfully consent or opt out. It says company technical and legal promises mostly protect device owners, while social norms and existing laws are inadequate for passive surveillance.

**Comments:** Commenters discuss workplace AI notetakers, consent norms, unions, and whether people can opt out without career risk. Others debate public-space privacy, advertising-based business models, Google Glass backlash, and whether jammers or stronger laws could help.

## 21. [Show HN: Fursoy – Out-of-order RV64IMAFDV core in SystemVerilog (Linux 6.6)](https://news.ycombinator.com/item?id=50497137) (↑60, 💬19)
**Article:** The GitHub project Fursoy Slice-1 is a 64-bit out-of-order superscalar RISC-V processor in SystemVerilog supporting RV64IMAFDV plus Zba/Zbb, Sv39 virtual memory, and SoC peripherals. It boots mainline Linux 6.6.50 and BusyBox under Verilator and reports 500 MHz timing closure across eight core blocks in standalone Nangate 45nm synthesis, though full place-and-route and fabrication are not done.

**Comments:** Commenters praised the achievement of a one-person out-of-order RISC-V core and debated whether simulation and synthesis count as “real hardware.” Some dismissed it as emulation or likely AI-assisted, while others defended SystemVerilog as standard chip design and noted synthesis to a PDK is meaningful; the author said FPGA bring-up is planned.

## 22. [How to Create Your Own Decentralized Messenger Protocol](https://news.ycombinator.com/item?id=50498073) (↑45, 💬8)
**Article:** The article explains how to design a federated decentralized messenger protocol, using email/SMTP and DNS MX discovery as models. It proposes email-like identities, `.well-known` discovery, server-to-server endpoints for resolving public keys, key IDs for rotation, and end-to-end encryption where servers only see ciphertext.

**Comments:** Commenters pointed to existing systems such as Reticulum/LXMF and Delta Chat/Arcane Chat, arguing email already provides federated messaging infrastructure with queueing, retries, and lookup. Some found it odd to rebuild from scratch, while others discussed email-based chat’s practical tradeoffs and Reticulum’s niche adoption.

## 23. [Italy fines Meta $887M over Android users' data access](https://news.ycombinator.com/item?id=50497009) (↑276, 💬182)
**Article:** The article content was unavailable. The headline reports that Italy fined Meta $887M over Android users’ data access.

**Comments:** Commenters were skeptical about the consent and harm claims, debating whether the fine is justified GDPR enforcement or a stealth tax and cost of doing business. Some cited GDPR’s requirement for purpose-specific informed consent and criticized Meta’s dark patterns, while others said the fine is too small to change behavior and questioned enforcement and payment.

## 24. [Possible Futures](https://news.ycombinator.com/item?id=50464467) (↑8, 💬7)
**Article:** The essay maps “possible futures” from AI in a flowchart, branching on whether ASI is reached, alignment is solved, automation is complete, and how many ASIs exist. Scenarios include misuse doom, Butlerian Jihad, enduring complementarity, permanent underclass, a singleton, classic paperclip doom, Orion’s Arm coexistence, and a world state.

**Comments:** Commenters said the taxonomy omits positive outcomes such as democratic governance or control of AI. Others criticized it as doomer/sci-fi tropes with logical leaps, while one defended the author against “cultist” characterizations and another noted blind spots such as MAD equilibria among multiple ASIs.

## 25. [Let's Write a PostScript Interpreter](https://news.ycombinator.com/item?id=50478632) (↑93, 💬15)
**Article:** The tutorial walks through implementing a small PostScript interpreter in concise JavaScript, covering tokens, operand and dictionary stacks, names, procedures, arrays, and operator execution. It focuses on PostScript as a programming language and omits graphics, strings, and most error handling while matching Ghostscript behavior for the examples.

**Comments:** Commenters shared PostScript stories and projects, including ray tracers, LaserWriter firmware exploration, interpreters in Python and C, and a Deflate decompressor written in PostScript. Some noted the language interpreter is simple but real implementations are mainly about graphics and fonts, while others valued PostScript as a human-scale, grokkable language.

## 26. [A visual explanation of reinforcement learning](https://news.ycombinator.com/item?id=50496885) (↑94, 💬6)
**Article:** This interactive explainer builds a four-neuron “spark” with three tunable brain parameters and lets readers manually wire it to seek light before introducing a reinforcement-learning algorithm. The algorithm randomly perturbs the wiring, rewards improvements, and punishes worsening results, showing learning trajectories that converge from novice to expert over hundreds or thousands of trials. It then shows how changing the reward produces different behaviors such as flee, freeze, fight, or love, and draws an analogy to biological reinforcement learning.

**Comments:** Commenters largely praise the visualization as clear, helpful, and a great example of interactive learning. A central debate is whether the piece adequately frames the brain comparison as an analogy rather than a claim about human neurology. One critic argues it reads more like game design than neuroscience and asks for clearer boundaries and rigor; others say the algorithm explanation works regardless of the analogy.

## 27. [US IRS free online tax filing open source repo (2025)](https://news.ycombinator.com/item?id=50499083) (↑122, 💬68)
**Article:** This GitHub repository hosts the IRS Direct File codebase, a free interview-based federal tax filing service that translates plain-language answers into standard tax forms and submits them through the IRS MeF API. The README describes its Scala-based Fact Graph, state-import API, in-house and vendor development, and legal authorities for open-source release. The repository is archived and unmaintained, with some code and data excluded due to PII, tax-information, and security restrictions.

**Comments:** Commenters discuss how hard it can be to e-file one’s own taxes, the limits of IRS Free File, and the registered-agent barriers that protect commercial tax software. Many praise countries with pre-filled or return-free filing and blame Intuit/TurboTax lobbying and political opposition for U.S. complexity, while others debate whether the tax code itself or filing software is the main problem. There is also interest in AI tax agents, skepticism about the repo’s legitimacy or broken .gov links, and speculation about Direct File returning after being discontinued.

## 28. [Creating a self booting ZIP archive](https://news.ycombinator.com/item?id=50498295) (↑29, 💬6)
**Article:** The author builds a ZIP archive that is also a bootable disk image, starting with a valid ZIP local file header for an executable file that doubles as boot code and contains a Multiboot header. The archive includes its own source and build scripts, and it can boot via QEMU direct kernel boot, as a floppy or hard-disk image, or on real hardware including 486 and 386 machines. The article explains ZIP’s back-to-front central-directory design and the polyglot tricks that make the format useful for self-extracting and bootable archives.

**Comments:** Commenters praise the write-up and note that uncompressed ZIP files are an underappreciated container format, especially because HTTP range requests can fetch individual files from a large archive. One developer jokes that such deep systems work makes their computing knowledge feel close to zero. Others discuss how clients locate the ZIP header, noting that negative HTTP ranges and the end-of-central-directory record’s size and offset let tools request the needed range directly.

## 29. [C3 0.8.6:Library fetching,30% smaller safe-mode binaries,and stricter type rules](https://news.ycombinator.com/item?id=50467987) (↑36, 💬1)
**Article:** C3 0.8.6 adds source-library packaging and a simple repository-based `c3c fetch` system with versions, checksums, and project dependencies. It also reduces safe-mode binary sizes by about 30% through optimized check and panic code, changes the panic function signature, and tightens cast and syntax rules while adding compiler statistics and standard-library updates.

**Comments:** The sole comment is brief praise: “Awesome! Great work.” There is no debate or substantive discussion in the thread.

## 30. [Show HN: Agweb – a browser for agents that stays out of your way](https://news.ycombinator.com/item?id=50497147) (↑76, 💬21)
**Article:** Agweb is a macOS WebKit-based browser designed for coding agents, emphasizing no focus stealing, a dashboard showing all agents’ tabs, idle-tab suspension, and low CPU/memory use. It offers a Playwright-CLI-style command interface with snapshots, diffs, shared named profiles, secret-filling, ad blocking, and video recording. Its stated limits include WebKit-only operation, no Chrome DevTools Protocol or Chrome extensions, and limited request mocking.

**Comments:** Commenters praise the project and ask how it compares with existing agent-browser tools, whether a headless/CLI version exists, and why ad blocking is enabled by default. Concerns focus on shared-profile spillover between agents, stealth and cookie-consent behavior, and the lack of CDP support, which makes it unusable for some workflows. The author responds that WebKit precludes CDP, that commands mirror playwright-cli for familiarity, and that state-save/load can approximate profile forking.

---
_Generated 2026-11-14 16:05 MDT_

---

## Recent Digests

- [Nov 14](./archives/2026/nov/hn-digest-2026-11-14.md)
- [Nov 13](./archives/2026/nov/hn-digest-2026-11-13.md)
- [Nov 12](./archives/2026/nov/hn-digest-2026-11-12.md)
- [Nov 11](./archives/2026/nov/hn-digest-2026-11-11.md)
- [Nov 10](./archives/2026/nov/hn-digest-2026-11-10.md)
- [Nov 9](./archives/2026/nov/hn-digest-2026-11-09.md)
- [Nov 8](./archives/2026/nov/hn-digest-2026-11-08.md)

[Full archive](./archives/) (186 issues)

_If you want more, explore the [archive folder](./archives/)._
