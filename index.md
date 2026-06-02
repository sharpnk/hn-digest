# HN Digest — June 2, 2026

## 1. [Coreutils for Windows](https://news.ycombinator.com/item?id=48372853) (↑69, 💬48)
**Article:** Microsoft has released a preview build of coreutils for Windows, packaging uutils/coreutils, findutils, and a GNU-compatible grep into a single multi-call binary. The project aims to provide native UNIX-style commands on Windows to reduce friction when moving between environments, though several commands conflict with CMD and PowerShell built-ins, and it requires PowerShell 7.4+. Some POSIX-only commands are intentionally dropped due to Windows limitations around signals, permissions, and file systems.

**Comments:** Commenters noted the project is a restricted uutils fork and question why Microsoft didn't upstream its fixes or provide a more complete port. Many expressed disappointment with the limited command set, shell conflicts, and lack of essential tools like head/tail, while others pointed to existing alternatives like msys2 or busybox-w32. Several users speculated the effort is motivated by AI agent tooling, and opinions ranged from appreciation for Microsoft's effort to dismissals of the project as unnecessary or broken.

## 2. [Three Ways to Get Paid](https://news.ycombinator.com/item?id=48373054) (↑29, 💬10)
**Article:** Jason Zweig shares his father's three-part rule for making a living: 1) Lie to people who want to be lied to, and get rich. 2) Tell the truth to those who want the truth, and make a living. 3) Tell the truth to those who want to be lied to, and go broke. The short post sets up these categories as a framework for understanding professional ethics and financial outcomes.

**Comments:** Commenters expanded on the framework, proposing additional categories like lying to those who want the truth (scams) or the role of telling people what they already know. Some criticized the brevity of the post, noted that the "read rest" link was broken, and questioned the rule's universality, with one commenter listing five jobs where it doesn't apply.

## 3. [A walking tour of surveillance infrastructure in Seattle](https://news.ycombinator.com/item?id=48369980) (↑188, 💬91)
**Article:** This guide provides a walking tour of surveillance infrastructure in downtown Seattle, cataloging visible technologies like surveillance cameras, Amazon Go stores, automated license plate readers (ALPRs), and Wi-Fi tracking devices. Each entry explains how the technology works, its social implications, and prompts discussion questions about privacy, bias, and consent. The guide focuses on making hidden surveillance visible to the public.

**Comments:** Commenters debated the technical accuracy of the guide, with some noting outdated information (Amazon Go has shut down) and overblown claims about MAC address tracking given modern randomization. Several criticized the academic jargon (e.g., "gazes" and "encoded ways of seeing") as inaccessible. A significant thread examined the trade-off between surveillance's crime-solving benefits and risks of abuse, with one user sharing a detailed personal story about the limits of video evidence in Seattle courts.

## 4. [Adafruit Receives Demand Letter from Fenwick Legal Counsel on Behalf of Flux.ai](https://news.ycombinator.com/item?id=48368121) (↑463, 💬187)
**Article:** Adafruit reports receiving a demand letter from Fenwick & West on behalf of Flux.ai, threatening legal action including Computer Fraud and Abuse Act claims over an unpublished article. Adafruit says it accessed only information that Flux made publicly available via a server misconfiguration and has paused publishing while considering its response. The electronics company says it is looking to resolve the matter constructively with Flux's founder.

**Comments:** Commenters overwhelmingly sided with Adafruit, with many noting that they'd previously had poor experiences with Flux's AI PCB tool, describing it as expensive and ineffective. Several called the legal action a SLAPP suit that backfired, since it generated widespread negative publicity for Flux. Limor Fried (ladyada) commented that Adafruit hoped to resolve the matter on a podcast, and multiple users said they would now avoid Flux entirely.

## 5. [Fidonet: Technology, Use, Tools, and History (1993)](https://news.ycombinator.com/item?id=48370291) (↑93, 💬31)
**Article:** This 1993 technical overview describes FidoNet, a store-and-forward email WAN operating over dial-up telephone modems with over 20,000 nodes worldwide. The document details its hierarchical addressing scheme (zone:net/node.point), protocols (Xmodem-based basic standard, Zmodem streaming), and routing topology that minimizes long-distance costs. It also explains gateways to the Internet via UUCP and the DNS zone fidonet.org.

**Comments:** Commenters shared nostalgic memories of running BBSs and FidoNet nodes in the 1980s and 1990s, with several recalling their exact node addresses. Many highlighted the community aspect — tight-knit groups formed around local nodes, the privilege of earning a node number by providing service, and the revolutionary experience of communicating internationally at low cost. Several noted that FidoNet and related "alt nets" like fsxNet are still active today.

## 6. [Why Janet? (2023)](https://news.ycombinator.com/item?id=48367907) (↑354, 💬177)
**Article:** The author makes a case for learning Janet, a small Lisp dialect, highlighting its simplicity (learnable in an afternoon), easy distribution (compiles to a small native binary), built-in parsing expression grammars, a shell scripting DSL, embeddability, and powerful macro system with compile-time value serialization.

**Comments:** Commenters largely praised Janet for its fast startup, portability, and the "sh" DSL. Discussion focused on comparisons to Tcl and Fennel, criticism of Lisp bracket syntax, concerns about limited libraries/package management, and appreciation for the compile-to-runtime value passing feature.

## 7. [Expanding Project Glasswing](https://news.ycombinator.com/item?id=48369863) (↑94, 💬102)
**Article:** Anthropic is expanding Project Glasswing, a program using its "Mythos Preview" AI model to scan critical software for vulnerabilities, to ~150 new organizations. The program aims to spur the industry to adapt to powerful AI cyberattacks by providing defenders with superior tools, and they plan to eventually shift from finding vulnerabilities to patching them.

**Comments:** Many commenters were deeply skeptical, viewing the program as a marketing and scarcity play (to mask limited compute for a public release) or a scheme to lock in enterprise customers. Others debated the model's actual efficacy, with some pointing out missed vulnerabilities and questioning ethical claims.

## 8. [Love systemd timers](https://news.ycombinator.com/item?id=48367904) (↑240, 💬158)
**Article:** The article's content was not retrievable, appearing as corrupted binary data. The title indicates a positive discussion about systemd timers as a replacement for cron for scheduling tasks.

**Comments:** The thread is a strong debate between systemd timer advocates and cron defenders. Supporters praised timers for better logging (journalctl), handling missed runs (e.g., after downtime), and cleaner environment management. Critics cited accidental complexity, hard-to-debug failures, and the elegance and simplicity of cron for basic needs.

## 9. [Preparing for KDE Plasma's Last X11-Supported Release](https://news.ycombinator.com/item?id=48370588) (↑82, 💬73)
**Article:** KDE announced that Plasma 6.8 will be the first release to remove the X11 session entirely, dropping all X11-specific code for the shell. They state 95% of users are on Wayland and that focusing on a single display server will allow for new performance and memory optimizations.

**Comments:** Commenters expressed concern over remaining Wayland issues, particularly for accessibility software, multi-monitor setups with specific window placement, and features like "always on top." While many praised KDE's Wayland implementation, others felt the transition was premature and would break workflows for users with specialized needs.

## 10. [CSS-Native Parallax Effect](https://news.ycombinator.com/item?id=48368291) (↑107, 💬46)
**Article:** The author describes a modern CSS method for creating a parallax scrolling effect using the `view-timeline-name` and `animation-timeline` properties. The technique uses a single utility class, smooths the effect by scaling the child element to prevent empty space, and respects the `prefers-reduced-motion` accessibility setting.

**Comments:** Commenters noted the lack of a live demo on the page, which was a major point of frustration. The primary discussion compared this new scroll-driven timeline method to the older pure-CSS 3D perspective technique, with the consensus that the new method is simpler to set up but suffers from limited browser support, especially on Firefox.

## 11. [Stop Ruining It](https://news.ycombinator.com/item?id=48368059) (↑160, 💬74)
**Article:** Seth Godin argues that desirable qualities like customer delight, curiosity, and trust are not features to be added, but are what remains when you avoid ruining them in the first place. The core idea is that people start with a baseline of positive attributes, and the goal should be to not destroy them through poor design, management, or marketing.

**Comments:** Many comments apply the concept to software, especially criticizing Windows 11's File Explorer for adding unwanted "improvements" that ruin functionality. A major debate centers on whether features like tabs are improvements or ruinations, with a consensus that removing existing utility is more damaging than failing to add new features. A recurring insight is the "via negativa" principle—improvement by subtraction—and the observation that rebuilding trust after ruining it is far more costly than not ruining it in the first place.

## 12. [Reviving Teletext for Ham Radio](https://news.ycombinator.com/item?id=48325668) (↑42, 💬20)
**Article:** The author describes reviving the 1980s teletext system for use in ham radio by sending digital teletext pages over the AX.25 protocol using a computer's sound card. Teletext is praised for being a low-bandwidth, efficient digital system, and the project aims to create a digital counterpart to slow-scan television (SSTV) for transmitting text and images.

**Comments:** Commenters discuss the irony of the Linux kernel dropping AX.25 support just as such projects gain interest, noting userspace workarounds exist. They share nostalgia for teletext and related pre-internet data systems (like VBI data on TV signals), and debate the viability of decentralized, uncensorable networks, noting ham radio's legal limitations on encryption and commercial use.

## 13. [Can the stockmarket swallow Anthropic, SpaceX and OpenAI?](https://news.ycombinator.com/item?id=48364055) (↑615, 💬1050)
**Article:** The Economist article (linked via archive.ph) discusses whether the stock market can absorb the massive IPOs of heavily-valued private companies like Anthropic, SpaceX, and OpenAI, given their trillions in combined valuations.

**Comments:** Comments heavily focus on allegations that rules were changed to force passive index funds (401ks, pensions) to buy these stocks at IPO prices, waiving profitability and seasoning requirements. Many argue the companies are overvalued with no moats, see the IPOs as a race to cash out before a correction, and express skepticism about the sustainability of AI and SpaceX valuations.

## 14. [Show HN: Eyeball](https://news.ycombinator.com/item?id=48367723) (↑159, 💬54)
**Article:** "Eyeball" is a simple precision-clicking game where you click on a line to mark a target fraction. It is built for mouse/trackpad use and tracks your best, average, and streak scores.

**Comments:** Users share their scores and find the game fun and addictive. Many request features like a training mode for missed targets, a time limit, or different shapes (angles, curves). One user notes the game is a modern take on Matthias Wandel's classic "Eyeball" game, which involved guessing geometric attributes like angle bisection.

## 15. [Why Custom Attributes in .NET Give Me Nightmares](https://news.ycombinator.com/item?id=48343435) (↑60, 💬19)
**Article:** The author explains why .NET custom attributes are poorly designed, focusing on the complexity of parsing their binary format. A key problem is that enum arguments require resolving the full type to determine the underlying type's byte size, which involves expensive assembly resolution, type tree traversal, and handling type forwarders.

**Comments:** Commenters generally agree that custom attributes are powerful but easy to misuse. A consensus emerges that attributes are best for pure, static metadata (like [JsonIgnore]), while fluent builders or DI patterns are superior for dynamic per-member logic. One commenter notes that this parsing complexity is only an issue when parsing assemblies manually; .NET's own reflection handles it transparently.

## 16. [Webcam head tracking, webcam to control in‑game FOV](https://news.ycombinator.com/item?id=48336783) (↑72, 💬37)
**Article:** OpenFOV is a webcam-based head tracking tool for iRacing that unlocks VR-style functionality for monitor users. It uses a webcam to control the in-game field of view, offering a middle ground between standard screens and full VR setups.

**Comments:** Commenters debated the practicality of webcam head tracking, with some noting it takes getting used to due to the disconnect between head and eye movement. Many pointed to existing alternatives like OpenTrack and emphasized that the slight head movements required become second nature in sim games, while others questioned its utility compared to true VR.

## 17. [Great Question (YC W21) Is Hiring Applied AI Interns](https://news.ycombinator.com/item?id=48369098) (↑1, 💬0)
**Article:** Great Question (YC W21) is hiring an AI Engineer Intern for summer 2026, offering a 3-month remote role focused on building real features like semantic search and AI moderators. The position requires candidates to demonstrate hands-on AI projects and a self-starter attitude, with mentorship from the CTO.

**Comments:** No comments were provided for this story.

## 18. [Key Chemistry Question Answered, No Quantum Computer Required](https://news.ycombinator.com/item?id=48323220) (↑7, 💬0)
**Article:** A team of chemists led by Garnet Chan used classical computers to understand the nitrogenase enzyme, a complex chemical reaction long thought to require quantum computers. The achievement demonstrates that classical methods can solve intricate biochemical problems, challenging the notion that quantum computers are essential for such tasks.

**Comments:** No comments were provided for this story.

## 19. [Squillions: How money laundering won](https://news.ycombinator.com/item?id=48344535) (↑122, 💬103)
**Article:** The article investigates the vast amount of cash in circulation that remains unaccounted for, arguing it is primarily used for money laundering and criminal transactions. It highlights how central banks are indifferent to this issue, contributing to a massive global illicit financial system estimated at trillions.

**Comments:** Commenters discussed the role of cash in sovereignty and tax evasion, with many criticizing anti-money laundering laws as tools for surveillance that fail to stop crime. Some noted Switzerland's acceptance of high-value notes contrasted with UK policies, while others debated whether cash should be stigmatized and if cryptocurrencies are a better alternative.

## 20. [Rethinking Search as Code Generation](https://news.ycombinator.com/item?id=48372547) (↑4, 💬1)
**Article:** Perplexity introduces "Search as Code" (SaC), an architecture that exposes search stack components as SDK primitives for AI agents to compose custom retrieval pipelines via generated code. This replaces traditional monolithic search APIs, enabling fine-grained control over retrieval, ranking, and filtering for complex agent tasks.

**Comments:** One commenter found the approach interesting but questioned how a coding agent would know enough about a codebase to construct a multi-stage search pipeline based solely on a prompt. They noted that sequential tool calls may be necessary, though existing coding agents already encourage parallel tool calling.

---
_Generated 2026-06-02 11:49 MDT_

---

## Recent Digests

- [Jun 2](./archives/2026/jun/hn-digest-2026-06-02.md)
- [Jun 1](./archives/2026/jun/hn-digest-2026-06-01.md)
- [May 31](./archives/2026/may/hn-digest-2026-05-31.md)
- [May 30](./archives/2026/may/hn-digest-2026-05-30.md)
- [May 29](./archives/2026/may/hn-digest-2026-05-29.md)
- [May 28](./archives/2026/may/hn-digest-2026-05-28.md)
- [May 27](./archives/2026/may/hn-digest-2026-05-27.md)

[Full archive](./archives/) (21 issues)

_If you want more, explore the [archive folder](./archives/)._
