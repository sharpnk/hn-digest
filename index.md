# HN Digest — November 8, 2026

## 1. [Goldman Sachs Is Pulling Claude Code from Its Bankers and Traders](https://news.ycombinator.com/item?id=50415628) (↑453, 💬277)
**Article:** Goldman Sachs has restricted Claude Code and GitHub coding agents to its engineers, cutting off bankers and traders who had used them for client-flow tracking and market modeling. The bank cited productivity and risk concerns, including unreviewed code and information barriers, and the change comes shortly before Goldman helps underwrite Anthropic’s IPO.

**Comments:** Commenters debate the real motive: security risks from agents with access to sensitive data and networks, token-cost overages, IPO timing, or a possible operational incident such as a bad trade. Many agree non-engineers should not run unreviewed code in regulated finance, while some criticize Goldman for withdrawing tools without supporting the useful workflows traders had built.

## 2. [RAM Altman: Linux Script Emails Sam Altman Daily How Much Unused RAM in Your PC](https://news.ycombinator.com/item?id=50415172) (↑192, 💬72)
**Article:** A developer created “Ram Altman,” a Linux Bash script that monitors unused RAM and can email Sam Altman satirical reports about local memory not being in a data center. It does not send mail by default, includes dry-run and test modes, and responds to Altman’s comments about global RAM allocation.

**Comments:** Some commenters say Altman’s remarks were overblown and merely about economic efficiency, while others argue his position is self-serving and tied to rising RAM prices. The thread also questions whether mass emailing would amount to a DDoS, notes duplicate submissions, and complains about the source site’s intrusive ad-blocker modal.

## 3. [Dux: Free, open-source Wayland desktop shell with file manager and theming](https://news.ycombinator.com/item?id=50416053) (↑98, 💬33)
**Article:** Dux is a free, open-source Wayland desktop shell with a file manager, search, calendar, system monitor, theming, and plugin support for compositors such as niri, Hyprland, Sway, and labwc. The project highlights dynamic app theming, preconfigured distributions, and a modular desktop experience.

**Comments:** Users praise Dux/DMS with niri as stable and polished enough to settle on, and note the recent rebrand from “Dank Material Shell.” Others prefer more minimal shells or Noctalia, worry Dux is becoming heavy, and discuss the name’s connotations, comparisons to Omarchy and Regolith, and custom widget development.

## 4. [Declarative Dragging](https://news.ycombinator.com/item?id=50368481) (↑180, 💬17)
**Article:** “Declarative Dragging” presents a UIST 2026 system where authors make elements draggable by specifying future model states, with the engine speculatively rendering those states to synthesize drag-and-drop behavior. The Dragology library implements the approach for SVG web interfaces and supports composable modifiers like snapping and transitions.

**Comments:** Commenters call the approach elegant and potentially valuable for web interactions and agentic coding, where verifying motion “feel” is difficult. Questions focus on speculative rendering cost and exponential blowup, prior art, use cases, and spring animations; the author answers questions and users also highlight the Hazel programming environment.

## 5. [Outlook.com Is Quietly Rejecting Email from Domains Without DMARC](https://news.ycombinator.com/item?id=50416158) (↑125, 💬103)
**Article:** Since November 5, 2026, Outlook.com has been rejecting some email from domains without a DMARC record, producing 550 5.7.1 bounces even for small senders. The article says the change was unannounced and recommends adding a basic `v=DMARC1; p=none` record, provided SPF or DKIM alignment passes.

**Comments:** Many commenters say DMARC is overdue and easy to configure, while others criticize Microsoft for silent, inconsistent rejection and opaque blocklists that hurt self-hosters. There is debate over whether a `p=none` record adds security beyond SPF/DKIM, plus reports of affected domains and complaints about centralization of email deliverability.

## 6. [Ask HN: What are you working on? (November 2026)](https://news.ycombinator.com/item?id=50417407) (↑12, 💬11)
**Article:** An Ask HN thread invites users to share what they are working on and what has recently sparked their curiosity. The prompt is open-ended and intended to surface personal projects, side projects, and current interests.

**Comments:** Users describe a wide range of projects, including a fantasy-themed personal website, a React implementation in Godot, an SDK observability tool, freelancer time tracking, a one-handed racing game, and fiction writing. Several comments are meta-discussions about duplicate reposts and moderation, with a moderator saying duplicate threads will be merged and automation is planned.

## 7. [The Web Is More Than Enough, by Paul Ford](https://news.ycombinator.com/item?id=50416456) (↑17, 💬5)
**Article:** Paul Ford argues that browsers have become extremely powerful, cheap, and accessible platforms for building rich applications, citing his TinyLittleOffice project and browser APIs like Web Crypto, WebAssembly, WebGL, and Web Audio. He suggests AI-assisted development may broaden who can build software, potentially destabilizing app stores, while noting a mixed blessing as software work becomes more like writing.

**Comments:** Some commenters agree that browser capabilities are underappreciated amid the AI boom, while others are skeptical that modern web development is easier than older tools like Visual Basic. A more pessimistic thread argues the web is increasingly unusable due to bad software and AI bots, though another commenter notes how hard it is to avoid the web in daily life.

## 8. [Llama-modchip: 284B DeepSeek on 64GB RAM, no GPU](https://news.ycombinator.com/item?id=50411961) (↑316, 💬119)
**Article:** The llama-modchip GitHub project provides ggml/llama.cpp patches, quantization tools, and runtime optimizations to run large Mixture-of-Experts models entirely on CPUs. It claims a 284B DeepSeek-V4-Flash model can run in 64GB RAM with no GPU at 256K context, using aggressive quantization, SIMD/cache tuning, and speculative decoding.

**Comments:** Much of the debate centers on whether extremely low-bit quantization, especially around 2-bit, produces useful quality, with skeptics calling it a benchmark stunt and others defending tradeoffs for local use. Commenters also criticize the README as AI-generated and hard to follow, report mixed setup success, and discuss local-vs-cloud economics and llama.cpp’s upstream PR backlog.

## 9. [Writing as a thinking tool](https://news.ycombinator.com/item?id=50412067) (↑233, 💬72)
**Article:** The post argues that writing is a thinking tool that externalizes cognition, comparing it to giving a Turing machine paper and pencil, and says drafting, editing, and freewriting help surface and refine ideas. It warns that LLMs can produce polished text without doing the thinking, making personal writing a growing comparative advantage.

**Comments:** Commenters largely agree, sharing examples from PhD research, design, coding, and note-taking where the act of writing clarified their thinking. Several debate how to use LLMs honestly—as editors, questioners, or rubber ducks—while others nitpick the finite-automaton/Turing-machine analogy and warn about overanalysis or AI-generated writing as a shortcut.

## 10. [Edward Hopper's Iconic Painting, "Nighthawks](https://news.ycombinator.com/item?id=50372838) (↑39, 💬8)
**Article:** The article traces the creation of Edward Hopper’s “Nighthawks,” including preparatory sketches, possible Greenwich Avenue diner sources, and Hopper’s use of himself and his wife Jo as models. It places the painting in the context of Pearl Harbor, wartime blackout fears, and Hopper’s obsessive focus, drawing on Jo’s letters.

**Comments:** Commenters note the painting’s home at the Art Institute of Chicago and mention other iconic works there, link to a higher-resolution Wikipedia image, and recommend related films and videos. Several complain about aggressive mobile popups obscuring the artwork, with one noting Firefox mobile reduces them, while others describe the painting as soothing and nostalgic.

## 11. [A Little Snitch for Windows](https://news.ycombinator.com/item?id=50415135) (↑69, 💬33)
**Article:** PacketHound is a free Windows 10/11 outbound firewall that prompts users when installed apps try to connect, then stores their decisions as ordinary Windows Firewall rules. It aims to distinguish Windows components from user apps, watch risky tools like PowerShell, and avoid kernel drivers or telemetry.

**Comments:** Commenters compare it with ZoneAlarm, Portmaster, Simplewall, Fort Firewall, and Windows Firewall Control, debating usability and feature gaps. A major thread criticizes the site and app as likely LLM-generated “vibeslop,” while others defend LLM-assisted development and note alternatives like Simplewall have their own annoyances.

## 12. [How I Fight AI Brain Fry](https://news.ycombinator.com/item?id=50416363) (↑94, 💬80)
**Article:** The author describes using a git-based ticket queue and an “owner inbox” to manage many Claude Code/Codex sessions without losing context. Agents work the board and surface decisions; the author handles one item at a time and closes it by returning it to the queue.

**Comments:** Commenters debate whether the approach solves the real problem, with many arguing that parallel agent sessions cause context switching and review bottlenecks and that working more serially may be better. Others share similar workflows using issue trackers, markdown boards, or agent-management tools, while some mock the article’s AI-assisted writing and the tendency to build elaborate systems instead of doing less.

## 13. [Show HN: Vegetable Gardening for Engineers](https://news.ycombinator.com/item?id=50362963) (↑119, 💬23)
**Article:** This guide aims to teach engineers vegetable gardening with more technical depth than popular books or social media, focusing on indoor and balcony hydroponics/container growing. It covers environmental parameters, growth stages, light, temperature, nutrition, media, water, pests, crop data, techniques, and economics.

**Comments:** Commenters offer corrections, including concerns that the photoperiodism examples are reversed and that a temperature/quality tradeoff quote may be misleading. Discussion ranges from automation and sensor-based gardening to skepticism about ROI, debates over soil complexity and sustainability, and warnings about pests and seasonal challenges.

## 14. [I'm not a fan of Deno's security model (2024)](https://news.ycombinator.com/item?id=50413769) (↑73, 💬32)
**Article:** The author argues Deno’s permission model is insecure and misleading, citing terminal-based permission prompts that can be manipulated by attacker-controlled output and `--allow-run` weaknesses involving PATH and environment variables like `LD_PRELOAD`. The piece contends these issues undermine the “secure by default” promise.

**Comments:** Commenters debate whether the terminal-prompt issue is Deno-specific or a general TUI problem, and some note Node now has a similar permission model. Others argue OS-level sandboxing or capability systems are better, criticize Deno’s broader trajectory, and discuss practical ways to handle sensitive terminal input safely.

## 15. [Nvidia Board of Directors Is Investigating Jensen Huang](https://news.ycombinator.com/item?id=50416801) (↑212, 💬163)
**Article:** NVIDIA’s board announced an independent investigation after reporting that CEO Jensen Huang was the target of a foreign intelligence effort. The board says it has no reason to believe national security or NVIDIA secrets were compromised, and Huang says he will cooperate.

**Comments:** Many commenters call the submission title misleading, arguing the board is investigating what happened to Huang rather than treating him as the accused. Discussion also focuses on reported allegations involving a Chinese spy and infidelity, national-security and economic implications, possible blackmail or honeypot scenarios, and whether Huang will face consequences.

## 16. [Goodbye Claude, hello Pi](https://news.ycombinator.com/item?id=50410107) (↑647, 💬411)
**Article:** A longtime Claude Code user explains why they migrated to Pi, citing friction between CLAUDE.md and AGENTS.md, VSCode session limitations, GUI extension problems, frequent unstable releases, and system-prompt/tool-description bloat. They praise Pi’s minimalism, stability, extensibility, and customizability, and describe writing small extensions after switching.

**Comments:** Commenters debate harness choice, with some defending Claude Code’s native model integration and warning that using Pi with Anthropic subscriptions may violate terms or lose caching/behavior optimizations. Others praise Pi for giving users control and enabling custom workflows, while discussion also covers TUI vs. GUI use, token overhead, subscription economics, and feature bloat versus stability.

## 17. [The Reconstruction of Torn Documents](https://news.ycombinator.com/item?id=50389923) (↑80, 💬46)
**Article:** The German Federal Archives describes efforts to reconstruct Stasi documents torn by Ministry for State Security staff around 1989–90, including 16,000 bags of fragments. Manual reconstruction has reassembled 1.7 million pages from 600 bags, while a computer-assisted pilot reconstructed about 91,000 pages from 23 bags but failed to reach mass-production targets; the archive is now reassessing requirements and continuing manual work.

**Comments:** Commenters question why reconstruction is so hard, citing the DARPA Shredder Challenge and other recovered-document projects, and discuss scanning, sorting, ML matching, and bag-level constraints. Others debate the €6.5 million pilot cost, privacy law, whether shredded material was destroyed, and whether political or institutional factors explain the slow progress.

## 18. [Playing with the STM32MP2](https://news.ycombinator.com/item?id=50416014) (↑6, 💬1)
**Article:** The author describes bare-metal experimentation with the STM32MP2 applications processor, aiming to use it like a fast MCU with PCIe/SERDES for FPGA integration without Linux, vendor SDKs, or TrustZone. The post covers bringing up the Cortex-M33 auxiliary core from SRAM and flash, creating FSBL images and a flasher, and working toward PCIe support; it also notes a silicon security bug delayed publication.

**Comments:** The single comment wonders whether restricted crypto-accelerator documentation is driven by export controls or government contract requirements.

## 19. [Porting Android 16 to my blind mother's keypad phone](https://news.ycombinator.com/item?id=50366821) (↑137, 💬40)
**Article:** The author tries to replace their blind mother’s aging Nokia keypad phone with a used Kapsys SmartVision3, but finds outdated Android, poor performance, bloatware, crashes, and unmet update promises. After debloating, backup attempts, bootloader unlocking, and flashing a LineageOS Android 16 GSI, they discover Kapsys patched Android’s input and system apps to integrate the keypad with TalkBack, requiring a custom keypad/home/keyboard approach.

**Comments:** Commenters praise the project and offer accessibility and Android expertise, including notes on TalkBack keyboard commands and Android key mapping. The thread also discusses niche accessibility hardware pricing, GSI functionality, keyboard-phone history, and criticism of the article’s lowercase style; author replies mention later adding capitalization, font, and contrast options and that the phone mostly worked except Bluetooth.

## 20. [Playing Zork 1 on a CP/M emulator on Linux (2021)](https://news.ycombinator.com/item?id=50415750) (↑20, 💬11)
**Article:** A tutorial explains how to run Zork 1 under CP/M on Linux using the z80pack Z80 emulator, including building z80pack and cpmtools, creating disk images, copying ZORK1.COM and ZORK1.DAT, fixing backspace behavior, and launching the game. The author notes there is no practical reason to do this except learning about CP/M and retro computing.

**Comments:** Readers share simpler alternatives such as a Go-based CP/M emulator with Docker and a curated CP/M software collection, plus nostalgia for playing Zork on RC2014, Kaypro II, and TOPS-20 systems. Others mention frotz and classic Zork references, while one criticizes an AI-illustrated web version for inconsistent images.

## 21. [A field guide to CAPTCHA types and how they break](https://news.ycombinator.com/item?id=50415078) (↑36, 💬12)
**Article:** A GitHub field guide catalogs 39 CAPTCHA types, including identification signals, documented free/open-source bypass methods, and paid alternatives, with a searchable web version. It frames itself as an educational and authorized-research reference and includes difficulty ratings and links to solver/service indexes.

**Comments:** Commenters discuss reCAPTCHA v3 as invisible behavioral profiling rather than a puzzle, and some report endless reCAPTCHA v2 loops or QR-code challenges tied to phone numbers. Others are skeptical of the repo’s authorized-research disclaimer, argue it mainly helps bots/spammers, or note that the guide appears LLM-written and that AI is not a practical CAPTCHA-solving approach at scale.

## 22. [The History of Djgpp](https://news.ycombinator.com/item?id=50353814) (↑5, 💬0)
**Article:** The post recounts how DJGPP began around 1989 after Richard Stallman said porting GCC to MS-DOS was impractical. DJ Delorie built early GCC versions on Unix, wrote custom system-call replacements and a 32-bit extender called go32, ported BSD libc, and released successive DJGPP versions before version 2 added self-bootstrapping, djasm, and CWSDPMI.

**Comments:** No comments were posted.

## 23. [What I run on my $10 USD OpenStick homelab](https://news.ycombinator.com/item?id=50406670) (↑759, 💬129)
**Article:** The author describes running a homelab on a $10 OpenStick with 512 MB RAM, four ARM Cortex-A53 cores, 4 GB eMMC, Wi-Fi, and a 4G modem, running Debian and Podman. Services include CastSponsorSkip, an AdGuard Home fork, the Zeroclaw AI agent, Cloudflare Tunnel, Beszel, Dozzle, Gatus, Fusion RSS, Shiori, and Diun.

**Comments:** Commenters compare the device to old dual-Pentium servers, ask about USB networking/AP mode/console use and current availability, and debate whether giving an AI agent root on a networked device is safe. Others discuss lighter alternatives, Podman memory overhead, auto-updating containers, RSS readers, and skepticism about Cloudflare/NSA trade-offs or whether the article was AI-written.

## 24. [Claude Code's "Don't Ask Again" exposes passwords in 1,122 public GitHub files](https://news.ycombinator.com/item?id=50407882) (↑557, 💬387)
**Article:** The article reports that Claude Code’s “Don’t Ask Again” permission feature stores approved full command strings, including embedded secrets, in `.claude/settings.local.json`, and that 1,122 public GitHub files were found exposing passwords. It focuses on how committed local settings can leak credentials.

**Comments:** A Claude Code team member says the file is meant to stay local, recommends auto mode and secret scanning, and says secret scrubbing is being considered. Many commenters dispute the headline as user error, recommend env vars, global gitignore, password managers, gitleaks, or VM sandboxing, and debate whether auto mode is actually safer without hard sandboxing; others criticize the article’s repetition and apparent LLM authorship.

## 25. [How to prove equations using diagrams, part 1](https://news.ycombinator.com/item?id=50412830) (↑54, 💬4)
**Article:** The post introduces a category-theoretic approach to equational reasoning with diagrams, connecting e-graphs and egglog to initial functors. It defines diagrams in categories and explains initial functors via limit-preservation or connected comma categories, aiming toward categorical and operational semantics for e-graph computation.

**Comments:** Commenters nitpick the use of “shape” for a diagram’s index category, while the author and another mathematician note that terminology varies and “shape” is used in sources such as nLab. One commenter asks for resources on functors and non-symbolic logic.

## 26. [JIT bitmap text rendering for microcontrollers](https://news.ycombinator.com/item?id=50412072) (↑89, 💬15)
**Article:** The post describes a technique for fast bitmap text rendering on RP2350 microcontrollers using a JIT that generates optimized rendering code per string. It combines beam-racing, packed font storage, proportional spacing/kerning, and a display-list renderer to stay within a tight per-pixel cycle budget.

**Comments:** Commenters connect the approach to prior art such as 1990s glyph-compilation patents, Macintosh-era FrameMaker, DOS “sprite compilation,” and Atari display-list programming. There is enthusiasm for the low-level retro aesthetic and symbolasm, plus some discussion of memory tradeoffs, JIT caching, and how the packed-font scheme might scale.

## 27. [Agent memory needs its OpenTelemetry moment](https://news.ycombinator.com/item?id=50411467) (↑159, 💬102)
**Article:** The article argues that agent memory tools each use incompatible formats and should converge on a shared data model, protocol, and conventions, analogous to OpenTelemetry. It surveys existing memory shapes and proposals, then sketches a possible record format covering address, identity, lifecycle, authorship, and content.

**Comments:** Many commenters agree the fragmentation is real but argue standardization is premature while memory approaches are still rapidly evolving. Others say LLMs already handle varied formats well or that plain filesystems/Markdown are sufficient; a large subthread criticizes the post as LLM-written and debates AI-assisted writing.

## 28. [Clj.rs – a Clojure dialect implemented in Rust](https://news.ycombinator.com/item?id=50366902) (↑153, 💬59)
**Article:** clj.rs is an experimental Clojure dialect implemented in Rust, offering persistent data structures, macros, native interop, and compiled or interpreted execution. The project is early-stage and published on crates.io, with a browser REPL and documentation.

**Comments:** Discussion centers on Clojure’s host interop, with commenters noting Rust interop appears less seamless than JVM interop, and on what makes Clojure attractive versus other Lisps. Others compare it to jank, Steel, scheme-rs, and Babashka, while some raise concerns about it being AI-assisted or “vibecoded.”

## 29. [Starship Flight 15 on 11/13 plans to catch both booster and ship](https://news.ycombinator.com/item?id=50416471) (↑42, 💬19)
**Article:** SpaceX’s Flight 15 is planned to attempt the first return and catch of both Super Heavy and Starship at the launch site. The mission would also deploy 26 Starlink V3 satellites and test heatshield improvements during a roughly 22-hour flight.

**Comments:** Much of the thread debates why the flight carries only 26 Starlink V3 satellites, with speculation about testing caution, engine-out margins, dispenser limits, satellite production timing, and Raptor performance. Other comments praise SpaceX’s lead and reusability progress, while some raise concerns about launch-market dominance and political controversy around Elon Musk.

## 30. [Ads in Popular Apps Give Police a Powerful Tool to Spy on Users](https://news.ycombinator.com/item?id=50415281) (↑91, 💬18)
**Article:** Article content was unavailable; the title indicates the story concerns how advertising-related data collection in popular apps can provide police with a powerful surveillance tool.

**Comments:** Commenters argue Google’s Play policies should prevent this kind of data sharing and question what the Play Store fee is for. Suggested mitigations include minimal app use, browser-based access with ad blockers, DNS-level blocking, and stricter location permissions, while others note browser apps and platform constraints limit those defenses.

---
_Generated 2026-11-08 16:05 MDT_

---

## Recent Digests

- [Nov 8](./archives/2026/nov/hn-digest-2026-11-08.md)
- [Nov 7](./archives/2026/nov/hn-digest-2026-11-07.md)
- [Nov 6](./archives/2026/nov/hn-digest-2026-11-06.md)
- [Nov 5](./archives/2026/nov/hn-digest-2026-11-05.md)
- [Nov 4](./archives/2026/nov/hn-digest-2026-11-04.md)
- [Nov 3](./archives/2026/nov/hn-digest-2026-11-03.md)
- [Nov 2](./archives/2026/nov/hn-digest-2026-11-02.md)

[Full archive](./archives/) (180 issues)

_If you want more, explore the [archive folder](./archives/)._
