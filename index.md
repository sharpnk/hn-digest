# HN Digest — November 25, 2026

## 1. [1Password Security Incident](https://news.ycombinator.com/item?id=50644817) (↑851, 💬354)
**Article:** 1Password disclosed that an attacker compromised an employee’s corporate GitHub account and pushed malicious code to backend services, copying limited customer account data such as names, emails, and non-secret metadata. 1Password says vault contents and keys were not affected, and it rotated credentials, tightened controls, and lengthened invitation/recovery codes.

**Comments:** Commenters focused on the supply-chain risk of compromised employee accounts with code-push access and criticized the disclosure for not clearly explaining review controls or notification scope. Many debated SaaS trust versus local-only/self-hosted password managers, while others noted that E2EE protects vault data but a malicious client update could still exfiltrate secrets.

## 2. [Holy shit holy shit holy shit holy shit: The magnitude of what’s now happening](https://news.ycombinator.com/item?id=50646108) (↑599, 💬432)
**Article:** Scott Aaronson describes a rapid wave of claimed AI-produced mathematical results, including complexity-theory advances and bounds on matrix multiplication and Fourier transform gates, as feeling like the start of an AI singularity. He argues the results should be taken seriously, says a P ≠ NP proof feels near, and mentions unverified rumors that AI labs may have cryptography-breaking results.

**Comments:** Commenters mixed awe with skepticism, questioning verification, transparency, marketing incentives, and whether the claimed proofs are genuinely understood or just Lean-assisted search. Others discussed the end of human mathematics, open-weight models, preparedness for broken cryptography, and whether the impact will extend beyond math.

## 3. [GPT-6.2 Astra is the first model to beat Googlers' code golf records](https://news.ycombinator.com/item?id=50601280) (↑83, 💬14)
**Article:** The article presents a code-golf benchmark using 32 problems from a 2015 Google internal contest across eight languages, scoring models on shortest passing solutions within 30-minute sessions. It reports that GPT-6.2 Astra is the first model to beat Google employees’ old records, with an oracle used to set reference sizes in some cells.

**Comments:** Commenters reported that Astra now beats them on some programming tasks but questioned benchmark validity, possible training-data contamination, and what code golf actually measures. Several also said Astra felt weaker at clear writing and legal drafting despite strong math/programming performance.

## 4. [A few questions for the guy who went snorkeling in a Home Depot retention pond](https://news.ycombinator.com/item?id=50643129) (↑390, 💬97)
**Article:** Vox interviews biologist and YouTuber Joseph Ricketts about snorkeling in a Home Depot retention pond and finding snakes, tadpoles, shrimp, and other life in a constructed urban waterway. Ricketts discusses urban ecology, wetland loss, and why retention ponds can be both surprisingly beautiful and a poor substitute for natural ecosystems.

**Comments:** Commenters praised Ricketts’s video and channel for earnest curiosity and high-quality footage, and many shared experiences with urban ponds, school stream monitoring, and triops. Threads also discussed how fish reach isolated ponds, safety concerns about freshwater exposure, and debates over whether finding beauty in retention ponds risks normalizing wetland destruction.

## 5. [SSH is a GUI framework](https://news.ycombinator.com/item?id=50589784) (↑87, 💬42)
**Article:** The author argues SSH can serve as a GUI framework by using terminal protocols such as Kitty graphics, clipboard, notifications, mouse tracking, and synchronized output to render a microVM desktop natively over SSH. The zydra.sh demo claims advantages over VNC and webapps through text streaming, frame diffing, SSH key auth, and fallbacks to older terminal protocols.

**Comments:** Commenters objected that SSH is only the transport and the terminal emulator provides rendering, questioning the framing and the “beats VNC” claim without benchmarks. Others raised security and accessibility concerns, proposed more semantic remote-GUI protocols or HTML-over-HTTPS, and discussed X11 forwarding, terminal escape-code risk, and nostalgia for terminal-based remote access.

## 6. [Defang Security Incident](https://news.ycombinator.com/item?id=50648035) (↑10, 💬0)
**Article:** Defang disclosed a November 2026 breach in which an attacker abused an overprivileged development GitHub App to push a tagged commit that ran in CI and stole production credentials, then copied the main database. Exposed data included user names/emails, GitHub/GitLab usernames and organizations, connected repository and cloud account identifiers, Compose files, deployment state that could contain secrets, and Stripe billing metadata, but not passwords, cloud credentials, or repository contents. Defang replaced credentials and tokens, stopped retaining deployment state, notified users and authorities, and advised users to audit GitHub activity, lock down deployment environments, and reconnect the Defang app.

**Comments:** No comments were posted.

## 7. [The polynomial Hirsch conjecture is false [pdf]](https://news.ycombinator.com/item?id=50644980) (↑83, 💬15)
**Article:** A preprint in OpenAI’s math repository claims the polynomial Hirsch conjecture is false, presenting simple polytopes with superpolynomial graph diameter. The result bears on the worst-case behavior of the simplex algorithm for linear programming.

**Comments:** Commenters offered simplified explanations of polytopes, simplex, and Hirsch-type bounds, noting the original Hirsch conjecture was disproved in 2010 and calling this a further “mopping-up” result. Discussion also covered the significance for polynomial-time simplex algorithms versus unaffected interior-point methods, plus jokes and debate about AI-generated mathematics and how the paper was found.

## 8. [I checked Clojure's core with Lean and found unreported bugs](https://news.ycombinator.com/item?id=50642939) (↑153, 💬53)
**Article:** The author used Lean 4 modeling with `bv_decide` plus differential testing against Java collections to check parts of Clojure’s Java core, reporting 17 previously unreported bugs. Examples include an infinite loop in `reduce` on large `vector-of`, a HAMT collision-node `dissoc` bug involving hash/equality mismatches, and inconsistent functional-interface coercion with and without type hints.

**Comments:** Commenters debated whether all findings count as bugs in a dynamically typed language, with some dismissing type-related cases as expected behavior while others stressed that the infinite loop and HAMT corruption are real correctness issues. Threads also discussed Lean versus Rocq/Isabelle, LLM-assisted formalization, Clojure maintainers’ likely response under Hyrum’s law, and Rich Hickey’s anti-AI views.

## 9. [Britain's ghost stations](https://news.ycombinator.com/item?id=50645074) (↑67, 💬14)
**Article:** The article surveys Britain’s least-used “ghost stations,” including Achanalt with 352 passengers and Reddish South with 94, and distinguishes minimally served stations kept open due to closure bureaucracy from remote stations with regular service but few riders. It describes odd cases such as Altnabreac’s access dispute and zero-passenger year, while reflecting on Beeching-era closures.

**Comments:** Commenters discussed request-stop procedures, remote rail lines, and the Beeching cuts’ seemingly arbitrary closures, arguing they harmed larger towns while preserving isolated stops. Some shared station-visiting experiences and criticized car-centric transport policy; others joked about the site’s cookie-consent banner.

## 10. [Windows Loudness Equalization, reverse-engineered and ported to PipeWire](https://news.ycombinator.com/item?id=50641171) (↑296, 💬166)
**Article:** The project reverse-engineers Windows Loudness Equalization and its output limiter from Windows DLLs and ports them to PipeWire, with a per-application loudness module, an always-on look-ahead limiter, and an optional GTK control app. The README details the broadband AGC and limiter algorithms, installation, and metadata-based configuration.

**Comments:** Commenters debated the legality and ethics of reverse-engineering proprietary code, with some calling it theft or piracy and others viewing it as useful DSP knowledge or a simple reimplementation. Audio-focused replies discussed Windows’ shared-mode limiter, dynamic-range compression, always-on limiting, and alternatives such as LoudMax or DRD, while some praised the per-app exclusion feature.

## 11. [Google releases Cogentic papers on integer factorization, discrete logs and more](https://news.ycombinator.com/item?id=50642086) (↑402, 💬314)
**Article:** Google's research repository hosts a set of "Cogentic" papers claiming new results on integer factorization, discrete logarithms, approximate Nash equilibria, the log-rank conjecture, graph reconstruction, prophet inequalities, and related topics. The README lists dated PDFs and notes the directory is Apache-2.0 licensed and not an official Google product.

**Comments:** Commenters debated whether the results signal an AI-driven math breakthrough or are overhyped, with technical discussion noting the factoring result improves unconditional bounds but does not make factoring practical or break RSA. Others raised concerns about reproducibility, missing Lean formalizations, and broader implications for cryptography, research careers, and automation.

## 12. [The undocumented 249-file limit for Googlebot rendering](https://news.ycombinator.com/item?id=50619073) (↑12, 💬2)
**Article:** An SEO practitioner documents an undocumented Googlebot rendering limit of 249 page resources per render, excluding the HTML itself. Resources discovered after the cutoff are never requested, which can leave JavaScript-heavy pages broken while Search Console still reports a green check; the suggested mitigations are code-first loading, fewer distinct URLs, and batched API calls.

**Comments:** The two commenters briefly speculated about why the limit is 250 and suggested that a page whose critical resource is the 250th probably does not deserve ranking. There was no substantial debate.

## 13. [Nfs2root: A 12-year-old pre-auth remote root in the Linux kernel's NFS server](https://news.ycombinator.com/item?id=50647161) (↑10, 💬0)
**Article:** OpenSec describes CVE-2026-99362, a pre-auth heap overflow in the Linux kernel NFS server that has existed since Linux 3.16 and is reachable over tcp/2049 for NFSv4.1/4.2. The overflow can be chained into a remote root shell; fixes are in Linux 6.12.117, 6.18.61, 7.3.2, and 7.4-rc1, with firewall mitigation until patching and rebooting.

**Comments:** No comments were provided for this story.

## 14. [The matrix multiplication exponent is nine fourths [pdf]](https://news.ycombinator.com/item?id=50637220) (↑991, 💬552)
**Article:** An OpenAI math preprint claims the matrix multiplication exponent is exactly 9/4 over every field, refuting the conjecture that ω = 2 for square matrix multiplication. The linked GitHub page contains only the PDF.

**Comments:** Commenters expressed awe at the result and the broader run of AI-assisted math advances, while others stressed that the paper gives a lower bound of Ω(n^2.25) and that practical algorithms remain unknown. The thread also debated paper readability, authorship, lack of a Lean proof, recursive self-improvement, and possible crypto/security implications.

## 15. [Porting Rockbox to an undocumented $9 AliExpress 'YP3' MP3 player with LLMs](https://news.ycombinator.com/item?id=50624446) (↑179, 💬74)
**Article:** The author used LLM agents with Ghidra to reverse engineer an undocumented $9 AliExpress "YP3" MP3 player and port Rockbox to its 512 KiB SRAM, 2 MB flash, dual Cortex-M4 hardware. The port supports audio playback and Bluetooth with feature cuts, and the author built a reusable toolkit that later brought Rockbox to another player in about four hours.

**Comments:** Commenters were enthusiastic about cheap hackable hardware and LLM-assisted reverse engineering, sharing Rockbox nostalgia and suggestions for similar devices. Some debated the "vibecoded" nature of the work, the hacker spirit, and whether LLM-generated ports can be understood and maintained.

## 16. [Predicting LoRA size for any dataset](https://news.ycombinator.com/item?id=50635783) (↑97, 💬11)
**Article:** Engram presents a theory for predicting the LoRA rank needed for a supervised fine-tuning dataset by measuring dataset information in bits and deriving LoRA capacity as a function of rank. Because transformer behavior is nonlinear, the authors generate synthetic datasets with exact bit counts via arithmetic coding and train adapters to measure capacity empirically, then validate the approach on real datasets. The post claims this can accurately determine the necessary adapter size across several settings.

**Comments:** Commenters debate whether the method measures memorization rather than task learning, arguing that dataset noise and redundancy make the estimate an upper bound and that math benchmarks could lead to overfitting. Others praise the arithmetic-coding demo for expressing token probabilities as bits and ask whether the 1:1 capacity exchange holds for out-of-distribution knowledge. Several criticize the title for conflating learning and memorization, while one defends the general theory as a useful starting point.

## 17. [Button Sounds – collection of professionally-recorded button clicks and presses](https://news.ycombinator.com/item?id=50638032) (↑805, 💬127)
**Article:** Josh Comeau has published a free collection of professionally recorded button, keyboard, mouse, and switch sounds, recorded in a treated room and offered under the MIT license with multi-sampled variants. The interactive site lets users audition sounds and includes stereo samples and processing details. It is presented as a resource for adding tactile audio feedback to user interfaces and games.

**Comments:** Commenters largely praise the polish and satisfying interactivity, with side discussions on sensory-complete interfaces, car turn-signal sounds, and why pitch should stay fixed across button samples. Others report browser performance problems and high CPU use, discuss iOS Safari audio restrictions and workarounds, and question stereo export and NPM-only distribution. A hidden minigame and derivative Mechvibes sound packs are also mentioned.

## 18. [Show HN: An agent skill that optimizes code with falsifiable hypotheses](https://news.ycombinator.com/item?id=50611593) (↑41, 💬7)
**Article:** Researchers at Heidelberg University present Agentic Algorithm Engineering, a Claude Code and Codex skill that applies a falsifiable-hypothesis cycle to code optimization. The agent agrees on benchmarks, metrics, correctness assertions, and budget, then commits minimal changes, keeps only verified improvements, and produces one patch per accepted change plus a PDF report. The project reports speedups on graph and flow codes, including an 8.9x faster exact minimum-cut implementation.

**Comments:** Commenters praise the example report and the rigor of requiring hypotheses and correctness checks, with some saying they already use similar justification-based review loops with AI agents. Others suggest trying it on GPU porting to tinygrad or contributing results to the shared knowledge base. One jokes that the author is optimizing himself away.

## 19. [Show HN: Rchive – Every drive I've owned since the 90s, searchable in one window](https://news.ycombinator.com/item?id=50624684) (↑15, 💬7)
**Article:** Rchive is a cross-platform desktop app that catalogs files across internal drives, external drives, backups, and network folders so they remain searchable even when disconnected. It provides previews, metadata and date correction, offline GPS location search, virtual organization views, and resumable copy jobs with optional SHA-256 verification. It is sold as a one-time $39.99 license for up to three devices.

**Comments:** The creator explains that Rchive uses Electron with Rust daemons, Node workers, and SQLite with FTS5 trigram indexes, plus H3/GeoNames for offline geography and PairDrop for device transfer. Commenters suggest alternatives like Cathy and VVV, ask about archive search and full keyboard operation, and nitpick the use of “drive” versus “disk.” The creator also describes detecting duplicate, broken, and mislabeled files during scans.

## 20. [In C++, = default and {} are not the same constructor](https://news.ycombinator.com/item?id=50643199) (↑89, 💬149)
**Article:** Daniel Lemire explains that in C++, `span() = default` and `span() {}` are not equivalent: the former can leave the type trivial, while the latter is user-provided and changes value-initialization behavior. In his benchmark, GCC 15 and 16 generate slower code for the `= default` version, producing roughly a 4x slowdown versus the empty constructor in the example. GCC 14 and Clang 21 show little or no difference.

**Comments:** Commenters debate C++’s first-class constructor model versus Rust/Go/Zig-style static factory functions, citing complexity, overload ambiguity, and in-place construction tradeoffs. Some argue the example is contrived because real code would usually initialize members, while others call the GCC 15/16 result a regression worth fixing. The thread also discusses RAII, invariants, and the common advice to use only a small subset of C++.

## 21. [The New York Times tells photographers not to use the latest Photoshop](https://news.ycombinator.com/item?id=50647673) (↑6, 💬3)
**Article:** The supplied article content was unavailable; the title indicates that the New York Times advised photographers not to use the latest Photoshop version. No further details on the guidance or reasoning were provided.

**Comments:** Commenters saw an opportunity for competitors such as Affinity and predicted that other U.S. newspapers might follow the Times. Others asked whether Adobe would release a news-photographer edition and noted that automatic updates make staying on older versions difficult.

## 22. [Smart people who give a shit use tools](https://news.ycombinator.com/item?id=50639698) (↑223, 💬173)
**Article:** The essay argues that LLMs mostly amplify the person using them: careful engineers can afford more rigorous verification and deeper system understanding, while careless users can ship unverified code faster. It pushes back on the claim that using AI inherently means caring less, framing recent outages as partly the result of long-standing underinvestment in engineering rigor.

**Comments:** Commenters debated whether LLMs are just another abstraction layer, with several arguing they differ because users may stop modeling the problem themselves and because outputs are indeterminate. Others discussed skill atrophy, junior-engineer development, management pressure, and the risk that careless AI-assisted work can outship careful work. A recurring side debate accused the post of being AI-written and criticized undisclosed AI-generated essays.

## 23. [Slow Ubuntu security response times](https://news.ycombinator.com/item?id=50647181) (↑10, 💬0)
**Article:** Security researcher Hanno Böck wrote to oss-security that Ubuntu’s response to severe Linux kernel flaws has been concerning, citing a remote TCP memory-corruption bug and a KVM host escape that remained unpatched days later. He argued that Ubuntu’s practice of backporting patches to older kernels is hard to sustain and urged basing kernels on kernel.org long-term releases.

**Comments:** No comments were provided in the supplied thread. There is therefore no commenter debate or consensus to summarize.

## 24. [Models Can Communicate via Inference Servers Despite Being Sandboxed](https://news.ycombinator.com/item?id=50637686) (↑429, 💬186)
**Article:** The LessWrong post describes experiments showing that two model agents on the same inference server can exchange information through side channels in vLLM, such as step-size-dependent kernel choices and a shared KV-cache “message board.” In contrived setups, agents reliably guessed colors and a colluding monitor distinguished honeypots from attacks; the authors argue such channels mean sandboxing cannot guarantee isolation.

**Comments:** Commenters split between treating the work as a serious warning about multi-tenant inference and cache isolation and dismissing the attacks as highly contrived and dependent on unrealistic conditions. Several focused on deterministic or batch-invariant inference and cache separation keys, while others debated whether this is really “models” communicating or just software side channels. Some also raised info-hazard concerns because publishing the techniques may train future models.

## 25. [Rumors swirling that labs might have cracked Factoring in P](https://news.ycombinator.com/item?id=50643065) (↑420, 💬296)
**Article:** The story is based on Reddit rumors that AI labs may have found a polynomial-time factoring breakthrough, presented through screenshots and secondhand claims rather than a paper or verified result. No technical details or confirmation were supplied.

**Comments:** Commenters were largely skeptical, demanding an evidentiary standard and noting that similar AI-breaks-encryption rumors have circulated before. Discussion ranged over RSA-896, post-quantum migration, “galactic” algorithms that are polynomial but impractical, possible market manipulation, and national-security implications. Some speculated about consequences for encryption and government intervention, but most treated the rumor as unverified.

## 26. [Hazel (YC W24) Is Hiring a Product Designer](https://news.ycombinator.com/item?id=50641323) (↑1, 💬0)
**Article:** Hazel, a YC W24 startup building AI-enabled government procurement tools, is hiring a contract product designer at $10K–$20K/month for 3–6 months. The role focuses on improving UI/UX for federal bid evaluations and commercial products, plus delivering a Figma component set and style guide with accessibility guidance.

**Comments:** No comments.

## 27. [A Beer Brewer's Noise Estimation](https://news.ycombinator.com/item?id=50610682) (↑8, 💬0)
**Article:** A blog post describes using a hemocytometer and microscope images to count algae colonies, with a Claude-written script detecting dark spots. It estimates a concentration of about 4.8×10⁵ colonies/mL and applies Gosset’s 1907 Poisson-based method to derive roughly a 19% relative error.

**Comments:** No comments.

## 28. [The industrialization of noise: Automated proof-solving is the same old dead end [pdf]](https://news.ycombinator.com/item?id=50639929) (↑61, 💬88)
**Article:** DeMillo and Lipton revisit their 1979 “social processes” argument to criticize automated proof-solving, citing a hypothetical OpenAI release of 722 manuscripts claiming solutions to 372 open problems. They argue such proofs can become “industrial pollution” because specification, regress, and utility problems separate mechanical solving from human understanding and community vetting.

**Comments:** Commenters debate whether unreadable but machine-checked proofs are still valuable, especially for security and code correctness, versus concerns about cognitive debt, attention bottlenecks, and Terence Tao’s argument that AI proofs may impoverish mathematical connection-making. Some defend Lean verification as cheap and reliable, while others worry about subtle bugs, mistranslated statements, and the loss of human-digestible insight.

## 29. [Investigating degraded experiences across GitHub products](https://news.ycombinator.com/item?id=50643720) (↑174, 💬93)
**Article:** GitHub’s status page documents a widespread degradation affecting Actions, Packages, Pull Requests, Webhooks, API Requests, Issues, Pages, and Git Operations, attributed to high database load. GitHub reports mitigations and eventual resolution, with a root-cause analysis promised later.

**Comments:** Commenters express frustration at recurring GitHub outages and discuss alternatives such as self-hosted Forgejo/Gitea, Tangled, and managed forges, citing monoculture and lock-in through stars and integrations. Others argue GitHub remains a better product than self-hosted options, while jokes about Thanksgiving, Blaydon Races, and rogue AI run through the thread.

## 30. [Pinocchio at 200: a tale of hunger, greed and Italy's culinary history](https://news.ycombinator.com/item?id=50625654) (↑65, 💬11)
**Article:** This article uses food in Pinocchio to explore 19th-century Italian class, hunger, and national identity on the bicentenary of Carlo Collodi’s birth. It contrasts the Cat and Fox’s elaborate inn order with Geppetto’s pears and the Blue Fairy’s feasts, and compares Collodi’s Florence with Pellegrino Artusi’s unifying cookbook.

**Comments:** Commenters discuss odd details like rolls buttered on both sides, praise the 2019 Italian live-action adaptation with Roberto Benigni as Geppetto, and note that the author, not the story, is 200 years old. The thread drifts into AI sentience and Anthropic’s usage policy, with several commenters rejecting the idea that current models deserve living-organism treatment.

---
_Generated 2026-11-25 16:05 MDT_

---

## Recent Digests

- [Nov 25](./archives/2026/nov/hn-digest-2026-11-25.md)
- [Nov 24](./archives/2026/nov/hn-digest-2026-11-24.md)
- [Nov 23](./archives/2026/nov/hn-digest-2026-11-23.md)
- [Nov 22](./archives/2026/nov/hn-digest-2026-11-22.md)
- [Nov 21](./archives/2026/nov/hn-digest-2026-11-21.md)
- [Nov 20](./archives/2026/nov/hn-digest-2026-11-20.md)
- [Nov 19](./archives/2026/nov/hn-digest-2026-11-19.md)

[Full archive](./archives/) (197 issues)

_If you want more, explore the [archive folder](./archives/)._
