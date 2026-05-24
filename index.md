# HN Digest — May 23, 2026

## 1. [Time to talk about my writerdeck](https://news.ycombinator.com/item?id=48250144) (↑282, 💬146)
**Article:** The author details converting an old laptop into a console-only "writerdeck" running Debian without a desktop environment to eliminate distractions for writing. The setup uses kmscon, tmux, neovim, and Syncthing for backup, with customizations for battery and brightness.

**Comments:** Commenters debate whether the extensive setup itself is a distraction, with some calling it productive "yak shaving" and others seeing it as avoiding actual writing. The thread explores ADHD perspectives, simpler alternatives like just using a TTY, and the broader irony of optimizing tools instead of using them.

## 2. [Justice Department scrubs its website of news releases about Jan. 6 defendants](https://news.ycombinator.com/item?id=48253182) (↑43, 💬2)
**Article:** The Justice Department has removed press releases about January 6 defendants from its website, as reported by AP News.

**Comments:** One commenter laments the fragility of digital archives, questioning why wealthy tech figures don't fully fund the Internet Archive, while noting the paradox of relying on a web that increasingly erases its own history.

## 3. [My I3-Emacs Integration](https://news.ycombinator.com/item?id=48252535) (↑23, 💬6)
**Article:** The author describes patching the i3 window manager to forward keypresses to Emacs when it has focus, avoiding the latency of using xdotool. The patch allows specific bindings to pass through to Emacs based on window class, though it doesn't solve focus loss after forwarding.

**Comments:** Several commenters suggest using separate modifier keys for i3 and Emacs commands as a simpler solution, calling the patching approach overengineering. Others note they use dedicated hyper/super keys to avoid conflicts without custom patches.

## 4. [Sales and Dungeons: Thermal printer TTRPG utility](https://news.ycombinator.com/item?id=48232721) (↑41, 💬12)
**Article:** Sales & Dungeons is a free, open-source application that lets users turn thermal printers into TTRPG companions, creating printable handouts, random generators, and session grids. It supports HTML templates, LLM integration, and various data imports, with printer connections via USB, CUPS, or serial.

**Comments:** Commenters are enthusiastic about the idea but raise health concerns about BPA and similar chemicals in thermal paper. Some share information on safer "phenol-free" alternatives using vitamin C or urea-based coatings, while others note cashiers handle the paper all day.

## 5. [My two-part desk setup (2025)](https://news.ycombinator.com/item?id=48214311) (↑211, 💬125)
**Article:** The author describes converting a single long desk into two zones: a minimal digital side for work and an analog side for reading, writing, and building LEGO with kids. Facing the room instead of the wall improved the space's feel and created a clear mental boundary between tasks.

**Comments:** Commenters praise the Feng Shui principle of facing the room and discuss aesthetics, with many calling the USM Haller desk and Vitsoe shelving a "dream setup." Others critique the approach as requiring a large room and accuse the article of status signaling, while some debate whether the paper globe lamp is a fire hazard.

## 6. [On The <dl> (2021)](https://news.ycombinator.com/item?id=48247325) (↑346, 💬106)
**Article:** The article explains the underrated HTML <dl> (description list) element for marking up name-value pairs, covering its anatomy (<dl>, <dt>, <dd>) and the ability to wrap groups in a <div>. It argues for semantic HTML's accessibility benefits, such as better screen reader navigation, using examples from book metadata to Dungeons & Dragons statblocks.

**Comments:** Commenters debate the practical utility of <dl> versus nested <div>s, with some criticizing HTML semantics as inflexible for real-world use cases. Key points include technical corrections on ARIA roles for accessibility, historical roots in IBM GML, and mixed screen reader support, with some users finding it a semantic win and others preferring pragmatic approaches.

## 7. [Green card seekers must leave U.S. to apply, Trump administration says](https://news.ycombinator.com/item?id=48241890) (↑529, 💬922)
**Article:** The Trump administration announced a policy requiring most green card applicants currently in the U.S. on temporary visas to leave the country and apply from their home country, framing adjustment of status as an extraordinary exception. This effectively ends the common practice of applying for permanent residency while living and working in the U.S.

**Comments:** Comments overwhelmingly condemn the policy as cruel, impractical, and economically damaging, arguing it will break apart families, create multi-year backlogs at consulates, and force skilled workers from tech and healthcare to leave. Some note it may be partly walked back for H1-B workers and see it as a tactic to reduce legal immigration, sparking debate about U.S. competitiveness and the moral basis of immigration restrictions.

## 8. [wake up! 16b](https://news.ycombinator.com/item?id=48253060) (↑8, 💬2)
**Article:** This article describes a 16-byte x86 assembly program called "wake up! 16b" that simultaneously generates a Sierpinski triangle fractal on screen and outputs it as sound via the PC speaker. It provides a deep mathematical explanation of how XOR operations, memory layout, and the specific 56-byte step produce both the visual "Matrix rain" effect and the audio bytebeat.

**Comments:** One commenter initially mistook the title for a 16-billion parameter LLM, not a 16-byte demo. The other comment links to a previous discussion thread with more comments.

## 9. [Byrne's Euclid](https://news.ycombinator.com/item?id=48252146) (↑9, 💬3)
**Article:** The site is a digital reproduction of Oliver Byrne's 1847 edition of Euclid's "Elements," featuring colorful diagrams and symbols for geometry proofs. It includes interactive diagrams, posters, and puzzles based on the original illustrations.

**Comments:** Commenters appreciate the visual clarity for learning geometry, with one noting colored diagrams would have made high school geometry much easier. A link is provided to a higher-tech interactive version of Euclid's Elements.

## 10. [.NET (OK, C#) finally gets union types](https://news.ycombinator.com/item?id=48234954) (↑131, 💬116)
**Article:** The article announces that C# 15 (.NET 11) introduces union types via the `union` keyword, allowing a type to represent one of several cases (e.g., `SupportedOS(Windows, Linux, MacOS)`). It explains usage with switch expressions, compiler-enforced exhaustiveness, and implementation details, noting the feature works on older runtimes via compiler support.

**Comments:** Commenters celebrate the long-awaited feature while criticizing it for boxing value types and lacking some flexibility like `Either<string, string>`. Many note F# has had this for decades, and debate whether C# is catching up to languages like Rust and TypeScript, with some questioning its necessity and others praising its potential for cleaner domain modeling.

## 11. [Hengefinder: Finding when the sun aligns with your street](https://news.ycombinator.com/item?id=48241335) (↑106, 💬25)
**Article:** A software developer describes creating Hengefinder, a tool that calculates when the sun aligns with a given street, inspired by Manhattanhenge. The article details technical challenges like correctly calculating road bearing on a non-flat Earth and precisely defining "sunset" for the henge moment, using a boundary binary search.

**Comments:** Commenters suggest related tools like The Photographer's Ephemeris and ShadeMap, and express a desire for features such as sunrise alignment, calendar downloads, and a mobile app. A few commenters note that Stonehenge is technically not a true henge, and there is discussion about the safety and pedestrianization of streets during such events.

## 12. [New map reveals lost roads of the Roman Empire](https://news.ycombinator.com/item?id=48206543) (↑38, 💬6)
**Article:** A new high-resolution digital map of Roman roads has nearly doubled the known extent of the network to 300,000 km, though only 2.7% is precisely located. The map reveals that Rome's innovation was integrating existing local roads into the first continent-scale network, not all of which led to Rome.

**Comments:** The top comment points to the actual project website, Itiner-e, and lists previous related HN discussions. One commenter critiques the article's infographic and common misconceptions about Roman road construction, arguing they were not typically paved with large stones.

## 13. [ICE Awards $25M Iris-Scanning Contract to Bi2 Technologies](https://news.ycombinator.com/item?id=48252720) (↑63, 💬9)
**Article:** ICE has awarded a $25.1 million no-bid contract to Bi2 Technologies for iris-scanning devices, allowing agents to authenticate identities during field operations. The contract bypassed standard security reviews and independent audits, and the devices are due by late June.

**Comments:** Commenters express strong concerns about the no-bid contract, lack of oversight, and the potential for mass surveillance and human rights violations. There is skepticism about the competence of the contractor and speculation about corruption or kickbacks in the selection process.

## 14. [Toxic chemical leak at a manufacturing facility in Orange County](https://news.ycombinator.com/item?id=48252060) (↑104, 💬69)
**Article:** A state of emergency was declared in Orange County, California, after a tank containing 7,000 gallons of volatile methyl methacrylate at an aerospace facility began to fail. Emergency crews sprayed the tank with water to prevent an explosion or spill, while thousands were evacuated from the surrounding area.

**Comments:** A key comment links the incident to a recent EPA proposal to deregulate chemical facility safety rules. Commenters discuss the toxicology of the chemical, the challenge of draining the tank due to a stuck valve, and the urban planning issue of residential areas developing around industrial plants.

## 15. [Judson's Last Ride](https://news.ycombinator.com/item?id=48246993) (↑16, 💬1)
**Article:** The article content is unavailable.

**Comments:** The single comment expresses gratitude for having read the story and appreciation that the internet remains a place for sharing personal life stories.

## 16. [Reverse engineering circuitry in a Spacelab computer from 1980](https://news.ycombinator.com/item?id=48248954) (↑82, 💬16)
**Article:** The article reverse-engineers an ALU/register board from the 1980 Spacelab computer (Mitra 125 MS), which used multiple 74181 ALU chips for a 32-bit ALU instead of a microprocessor. It describes how the computer's processor was built from TTL logic chips and details the board's architecture and components.

**Comments:** Commenters discuss the PCB's unusual grid of holes, with debate about whether it was multi-layer or two-layer, and how traces ran between holes. The thread also covers the software (HAL/S and Fortran) that ran on the computer and memory segmentation details.

## 17. [SpaceX launches Starship v3 rocket](https://news.ycombinator.com/item?id=48242959) (↑355, 💬232)
**Article:** SpaceX launched Starship Version 3 for the first time on Flight 12, successfully reaching space despite engine failures on both the booster and upper stage. The mission included deploying dummy payloads and achieving a pinpoint landing in the Indian Ocean, marking major progress in heat shield performance.

**Comments:** Commenters note the mixed results - engine failures and a failed boostback burn were disappointing, but the successful re-entry, payload deployment, and soft landing were major achievements. There is debate about the program's progress toward reusability and lunar landing timelines, with some praising the iterative development approach while others question the overall schedule and costs.

## 18. [Show HN: Anyone interested in a tool helps to explore C++ ASTs](https://news.ycombinator.com/item?id=48228106) (↑13, 💬1)
**Article:** ACAV is an interactive AST visualization tool for C, C++, and Objective-C that uses Clang and Qt to let users explore abstract syntax trees from real codebases via a compilation database. It provides source-AST navigation, declaration context views, and caching for responsiveness, targeting students, researchers, and developers building Clang-based tools.

**Comments:** Only one comment, from the author, provides the GitHub repository link and invites questions.

## 19. [Don't Roll Your Own](https://news.ycombinator.com/item?id=48252192) (↑75, 💬58)
**Article:** The author argues that web developers should not override native browser behaviors like scrolling, link navigation, text selection, context menus, copy-paste, password fields, and date pickers. The article laments that custom implementations often break user expectations, accessibility, and security, citing examples like GitHub's link handling and custom form controls.

**Comments:** Commenters strongly agree with the article, with many arguing that JavaScript shouldn't even be allowed to intercept these actions. Some debate valid exceptions like Google Docs requiring custom controls, while others note that "rolling your own" is often driven by business incentives like ads and tracking rather than user experience.

## 20. [80386 microcode disassembled](https://news.ycombinator.com/item?id=48247004) (↑217, 💬43)
**Article:** The author describes the collaborative reverse-engineering of the 80386 microcode from die photos, using neural networks, image processing, and human verification to extract and disassemble 94,720 bits of microcode. The work revealed 215 microcode entry points, the interfaces between hardware accelerators (multiply/divide, barrel shifter, protection test unit), and a potential 40-year-old security bug in I/O permission bitmap handling.

**Comments:** Commenters express admiration for the reverse-engineering effort, with many describing it as "peak Hacker News." Contributors explain the extraction process details, including the use of convolutional neural networks to classify bits and manual verification, while others discuss related projects like nand2tetris and homebrew CPUs.

---
_Generated 2026-05-23 19:22 MDT_

---

## Recent Digests

- [May 23](./archives/2026/may/hn-digest-2026-05-23.md)
- [May 22](./archives/2026/may/hn-digest-2026-05-22.md)
- [May 21](./archives/2026/may/hn-digest-2026-05-21.md)
- [May 20](./archives/2026/may/hn-digest-2026-05-20.md)
- [May 19](./archives/2026/may/hn-digest-2026-05-19.md)
- [May 18](./archives/2026/may/hn-digest-2026-05-18.md)
- [May 17](./archives/2026/may/hn-digest-2026-05-17.md)

[Full archive](./archives/) (11 issues)

_If you want more, explore the [archive folder](./archives/)._
