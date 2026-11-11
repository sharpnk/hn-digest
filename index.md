# HN Digest — November 11, 2026

## 1. [AWS emulator](https://news.ycombinator.com/item?id=50456631) (↑480, 💬165)
**Article:** AWS Emulator is an official local emulator of AWS APIs for testing software without an AWS account, running as a server endpoint or embedded in Rust tests. It requires a very large source build, offers no binary releases, and enables telemetry by default.

**Comments:** Commenters debated whether it is a maintained product or an agentic demo, comparing it with LocalStack, Floci, Ministack, and fakecloud. Supporters highlighted AWS’s Smithy models and embedded Rust mode, while critics cited telemetry, missing reset/state features, build cost, and heavy signs of AI-generated code.

## 2. [Tim Peters has died](https://news.ycombinator.com/item?id=50450488) (↑657, 💬65)
**Article:** Guido van Rossum announced that Tim Peters died on July 15, praising his deep influence on Python, including mixed int/float arithmetic, the Zen of Python, Timsort, and early core-development culture. The post emphasizes his patience, humor, technical judgment, and mentoring.

**Comments:** The thread is largely a tribute filled with the Zen of Python, Timsort references, and anecdotes about Peters’ kindness, precision, and influence on Python’s community. Some commenters also discussed his later forum suspension and whether Python’s complexity grew after his departure.

## 3. [United Airlines bans AI agents from booking flights on behalf of travelers](https://news.ycombinator.com/item?id=50458900) (↑28, 💬14)
**Article:** United Airlines banned third-party personal AI agents from booking flights or checking in, citing credential-sharing risks, unintended purchases, and possible federal-rule violations. An analyst said United also wants to control intermediaries and avoid costs from AI-driven flight searches, while Southwest has taken a more open approach.

**Comments:** Commenters were skeptical of the cost rationale, arguing United mainly wants to protect dynamic pricing and prevent customers from finding better deals. Many said AI agents using computer-use tools will be hard to block, and criticized airlines for fighting consumer-side automation while using passenger data themselves.

## 4. [A false smoke alarm almost drowned Jane Street's only NYC datacenter](https://news.ycombinator.com/item?id=50455394) (↑336, 💬166)
**Article:** A false smoke alarm at Jane Street’s NYC datacenter shut down cooling, pressurizing sprinkler pipes while server-room temperatures rose toward the heat-trigger threshold. The author ran to the datacenter and manually pulled power from every rack before the sprinklers could activate, limiting downtime.

**Comments:** Commenters questioned why the facility lacked an emergency power-off system, dry sprinklers, or clean-agent suppression, and debated whether CRACs should shut down on smoke alarms. Much of the thread shared Hurricane Sandy and Fog Creek diesel-hauling stories, while praising the author’s response and criticizing single-site datacenter risk.

## 5. [Show HN: I recreated Papers Please but you're deciding which YC startups to fund](https://news.ycombinator.com/item?id=50457230) (↑119, 💬56)
**Article:** A Show HN game recreates Papers Please’s document-inspection mechanics as a VC deciding which YC startups to fund. Players review startup paperwork and choose to pass, fund, or hold.

**Comments:** The main criticism was that the game does not credit Papers Please creator Lucas Pope, with debate over derivative works, AI-generated creation, and whether the parody trivializes the original’s themes of state oppression. Others gave gameplay feedback on confusing document flow, missing valuation data, and YC branding, while some found the concept fun.

## 6. [Gemini Decisions API](https://news.ycombinator.com/item?id=50456791) (↑142, 💬45)
**Article:** Google introduced the Gemini Decisions API and Gemini Decision 1 model for fast closed-set multimodal decisions. It evaluates up to 1,000 yes/no, multiple-choice, and rubric-scoring questions in one pass over text, images, audio, video, and PDFs, returning confidence scores with low latency and no output-token billing. Google claims leading benchmark performance and calibration for tasks such as routing, policy checks, grading, and tool selection.

**Comments:** Commenters compare it with Jev and OpenAI’s decision endpoints, debating whether it is merely structured output or a meaningfully calibrated probability product. Several discuss how such probabilities are computed and whether LLM logprobs remain reliable after instruction tuning; others mention use cases like data labeling, routing, and file organization. Pricing, Google’s product longevity, and enterprise adoption are recurring concerns.

## 7. [GitHub Incident with Webhooks, Actions, etc.](https://news.ycombinator.com/item?id=50458532) (↑47, 💬22)
**Article:** GitHub’s status page reported degraded availability across Actions, Pages, Webhooks, and Copilot, with updates tracking investigation, mitigation, recovery, and processing of the Actions backlog. The incident was eventually marked resolved, with GitHub saying full recovery was observed and a root-cause analysis would follow. The page listed the affected services and provided subscription options for incident updates.

**Comments:** Commenters express frustration with repeated GitHub outages and discuss moving to alternatives such as self-hosted GitLab, Forgejo, Codeberg, or Blacksmith. Some note that self-hosted Actions were still affected through queued builds and webhooks, while others report Copilot degradation not reflected on the dashboard. There is also broader skepticism about GitHub reliability and continued dependence on the platform.

## 8. [Emacs in the Age of Magic](https://news.ycombinator.com/item?id=50458208) (↑63, 💬14)
**Article:** The essay argues that AI coding agents like Claude Code have eroded Emacs’s traditional advantages in editing speed, customization, and Lisp expressiveness. It traces rules-based AI and Lisp history, then presents examples of AI-generated Emacs modes that reimplement large software stacks for seemingly impractical purposes. The piece frames these quixotic projects as newly cheap because AI can attempt them for little more than token cost.

**Comments:** Commenters largely agree that AI coding agents are changing editor workflows, with some saying they now rarely open a traditional editor. Others debate the relevance of free software and user control when generated code becomes opaque, and raise concerns about scaling, maintainability, and modular APIs. Some commenters question specific claims about AI-generated replacements, while others joke about vibecoding and software quality.

## 9. [Huawei releases MACaQ, its internal quantizer for local inference](https://news.ycombinator.com/item?id=50458166) (↑26, 💬9)
**Article:** Huawei researchers released MACaQ, an Apache-2.0 model-agnostic quantization project for GGUF and local inference. It supports text, image, video, and audio models across llama.cpp, vLLM, Diffusers, and PyTorch, and claims it can quantize a 122B-parameter model in 64 minutes using 32.5 GB of device memory. The repository also describes Ascend kernel support and comparisons with MR-GPTQ and DuQuant++.

**Comments:** Much of the discussion focuses on the project name “MACaQ” and its apparent macaque-monkey reference. Commenters also debate why HN users often prefer GitHub links over official product pages, with some citing code visibility and others warning about sanctions or third-party hosting risk. A few ask whether models were released and whether the work is useful for related projects.

## 10. [Faster Retrieval for Better, More Efficient RAG](https://news.ycombinator.com/item?id=50455633) (↑116, 💬22)
**Article:** Apple researchers describe a learned approach to maximum inner product search for RAG and related retrieval systems. Instead of relying only on centroid-based clustering, they train small neural networks offline on the query distribution to approximate support functions and route queries more accurately. The method uses SupportNet for learned routing and KeyNet to predict best-matching keys, trading upfront training cost for faster retrieval at inference.

**Comments:** Commenters debate learned retrieval versus simpler lexical methods, with several saying BM25 or grep plus an LLM often works better outside hyperscale systems. Others argue that semantic search still matters for multilingual, typo-tolerant, or very large production retrieval, while noting tradeoffs in latency and relevance. The thread also digresses into Apple’s slow-burn AI strategy, local inference, and skepticism about Siri.

## 11. [IBM Quantum Nighthawk Demonstrates New Levels of Speed and Quality](https://news.ycombinator.com/item?id=50457669) (↑33, 💬13)
**Article:** IBM announced Quantum Nighthawk r3, designed for 10,000 operations across 520 programmable qubits, with plans to link two processors into a 1,040-qubit system in 2027. IBM says Nighthawk r2 has delivered speedups up to 19x for partners and is integrating quantum workflows with classical/HPC resources on its platform.

**Comments:** Commenters debate whether the system can outperform classical machines and ask whether “programmable qubits” are error-corrected or merely gate-addressable. Others raise dilution-fridge power/helium concerns, defend quantum as specialized research/coprocessor technology, and joke about running Shor’s algorithm or Doom.

## 12. [Launch HN: Pomerado (YC F26) – Turn any website into an MCP for agents](https://news.ycombinator.com/item?id=50455811) (↑38, 💬32)
**Article:** Pomerado (YC F26) turns websites into deterministic, self-healing MCP APIs by having an agent perform a task once, then generating and testing a reusable HTTP/Playwright integration. It supports authentication/2FA, repair jobs, an open-source version, and a hosted service with browser/proxy infrastructure.

**Comments:** Commenters probe credential storage, session isolation, prompt injection, bot detection, and how repairs handle failures; founders respond that tools return structured fields and that most errors are auto-repaired. Discussion also compares Pomerado with CLI-based tools and asks whether OpenAI or Anthropic could implement similar functionality natively.

## 13. [My AI agents found an unmapped Maya site](https://news.ycombinator.com/item?id=50452455) (↑883, 💬318)
**Article:** The author describes using 48 LLM agents to scan NASA lidar imagery, flag a possible Maya civic center, and send a report to Mexico’s INAH, which said no site was registered there. An update notes the site had already been mapped in a 2025 paper, so the agents rediscovered rather than discovered it.

**Comments:** Commenters praise the experiment but stress that the site was already known and that LLM outputs need expert verification. Threads debate archaeology’s limited capacity to protect/excavate new finds, looting and data-access risks, agent-swarm cost and methodology, and whether AI-generated reports to institutions are appropriate.

## 14. [Flying on Green: Why Farmers Are Turning to Drones for Cover Crop Seeding](https://news.ycombinator.com/item?id=50433042) (↑14, 💬3)
**Article:** Farmers in Illinois and Nebraska are using drones to broadcast cover crop seed into standing corn before rain, avoiding soil compaction and reaching wet or terraced areas. Custom drone seeding costs roughly $12–$15 per acre, with USDA EQIP cost-share helping offset adoption.

**Comments:** Commenters question whether drones can replace drilling, which inserts seed into soil, and suggest drones are better suited to fertilizer or pesticides. Others note the original meaning of “broadcast” and joke about bioengineered squirrels as alternative seeders.

## 15. [Hyper-Realistic Sand with WebGL2](https://news.ycombinator.com/item?id=50453288) (↑257, 💬57)
**Article:** This browser demo uses WebGL2 and JavaScript to simulate hyper-realistic sand that responds to touch, device tilt, and shaking, with different sand types and optional sound/haptics. It is designed for phones, tablets, and desktops.

**Comments:** Many commenters enjoy the tactile, playful simulation and share mobile experiences, while others criticize loud default sound, low frame rates on some phones, and physics issues like friction, momentum, and particles appearing stuck. Some link the source repo and compare the demo to other sandbox games.

## 16. [The Utah Teapot](https://news.ycombinator.com/item?id=50457618) (↑17, 💬5)
**Article:** The official Utah Teapot page presents the computer-graphics model’s history and downloadable/customizable versions, from Martin Newell’s 1975 original through later revisions up to a 2026 version by Cem Yuksel. It explains the teapot’s role as a standard graphics test model and its appearance at SIGGRAPH 1976, along with attribution guidance and model customization options.

**Comments:** Commenters share a roundup of earlier HN threads and note that many users knew the teapot from graphics tools but not its origin. One compares it to the Stanford dragon, while others reply that the Utah Teapot is far better known and predates it by more than 20 years; another links an eBay listing for a physical teapot and asks about historical base-rim changes.

## 17. [The hardest notes to find on the guitar](https://news.ycombinator.com/item?id=50454995) (↑33, 💬51)
**Article:** The article analyzes 275,169 answers from Gitori’s Find the Notes game to map which guitar-fretboard notes players misidentify most. It finds the upper-middle neck hardest—especially the G string at frets 6–9—while open strings, the 12th fret, and the outer E strings are easiest; accidentals are also harder and slower than natural notes.

**Comments:** Guitarists debate whether naming notes matters, with many saying they play by intervals, shapes, and muscle memory rather than explicit note names, while others say learning note names was high-leverage. Some question whether a browser game translates to real playing, and the thread also covers left-handed/front-view fretboard orientation, solfège and German note naming, and theory versus ear-based playing.

## 18. [Show HN: Yogurt – Free, private, open-source alternative to Granola](https://news.ycombinator.com/item?id=50454625) (↑128, 💬60)
**Article:** Yogurt is a free, open-source, MIT-licensed AI meeting-notes app from Frigade that records calls without adding a bot and runs local transcription/models; it is available for macOS, Windows, and Linux and uses Electron. The GitHub README emphasizes privacy and points to downloads, local build instructions, and related documentation.

**Comments:** Commenters compare Yogurt with OpenWhispr, Muesli, OpenOats, Steno, and other local transcription tools, asking about differentiation, diarization, multilingual support, and model choice. Others discuss the generic name, Electron’s memory use, the “Backed by Y Combinator” wording, and privacy/consent concerns around recording meetings.

## 19. [The Apple Support Community will permanently close on November 20, 2026](https://news.ycombinator.com/item?id=50449440) (↑72, 💬186)
**Article:** Apple has announced that the Apple Support Community will permanently close on November 20, 2026, and has already made it read-only and stopped accepting new posts. The notice directs users to the official Apple Support site and thanks community members for their contributions.

**Comments:** Most commenters say the forum had long been unhelpful, full of outdated or wrong answers, and a source of search-result pollution, though some recall useful workarounds and sympathize with prolific volunteer contributors. Others worry about losing an archive/training corpus and note that Apple’s Developer Forums appear to remain open.

## 20. [Play GTA5 on Browser](https://news.ycombinator.com/item?id=50458710) (↑9, 💬6)
**Article:** The linked page appears to be a browser-based attempt to run GTA5, showing only a loading screen at the time captured. The article content itself provides little detail beyond the game starting at 0%.

**Comments:** Commenters report freezes—one at 82%, another after about two minutes—while one says it works in Chrome but froze in Firefox and another notes it loads roughly 800 MB of assets. A related article explains how the browser version works, and one commenter argues such high-budget streaming/live-service approaches will become more common despite inefficiency.

## 21. [Atuin Threads: All your agent sessions on every machine](https://news.ycombinator.com/item?id=50453637) (↑169, 💬62)
**Article:** Atuin Threads, released in Atuin 18.24, provides searchable, synced history for AI agent sessions across machines and lets users resume or fork sessions between harnesses such as Claude Code and Codex. It is opt-in, end-to-end encrypted when synced, supports self-hosting or local-only use, and includes MCP tooling so agents can search prior sessions. The post frames this as an extension of Atuin’s shell-history mission: preserving the intent and reasoning behind work, not just commands.

**Comments:** Many commenters say they have built or are building similar session-history tools, citing noise from throwaway sessions, token-usage concerns, and privacy worries about syncing. Replies emphasize that Threads is encrypted, can be self-hosted or kept local, and does not by default affect token usage. Some debate tool proliferation and competition with session managers like herdr, while Atuin’s author discusses integrations, retention, and opt-in sharing.

## 22. [Retirement Savings Are Fueling the AI Bubble](https://news.ycombinator.com/item?id=50457164) (↑116, 💬120)
**Article:** The article argues that retirement and pension savings are increasingly exposed to the AI data-center buildout through private credit and equity funds, which finance projects whose risks are opaque and may not be disclosed to savers. It cites recent tech-stock selloffs, S&P warnings about hyperscaler credit quality, rising credit-default-swap activity, and estimates that private equity backs a large share of data-center financing. It suggests pension trustees avoid risky private assets and redirect savings toward housing, renewables, or public asset managers.

**Comments:** Commenters debate whether retirement savings fuel every bubble and whether the article overstates the risk, with several calling it politically motivated and noting the cited market drop was only about 4%. Others focus on pension boards versus 401(k) choice, index-fund exposure to mega-cap tech, bailout narratives, and OpenAI’s survival risk. Some defend ordinary index investing, while others argue pension beneficiaries have little control over risky allocations.

## 23. [Can a Linear Program Do Weight-Space Programming?](https://news.ycombinator.com/item?id=50452655) (↑220, 💬33)
**Article:** The post analyzes MIT CSAIL’s “weight-space programming” result, where GPT-6 Astra edited Qwen3.5-0.8B weights to reduce thinking loops and improve math performance. It argues Astra’s eight-hour trial-and-error search for which weights to edit was effectively solving a linear program, and shows that LP solves can find a similar sparse rank-1 edit with about 8x fewer changed weights in roughly a minute. Results match or slightly exceed Astra’s edit on several benchmarks.

**Comments:** Commenters praise the LP insight and the return to classical optimization methods, suggesting solvers could make agent-driven weight editing more efficient or be incorporated into training. Others debate whether this diminishes the “weight-space programming” framing, distinguishing direct weight understanding from tool-assisted optimization, and discuss backpropagation, self-editing, and RSI implications. Some are skeptical of the original headlines, while others see the work as a meaningful step toward models editing themselves.

## 24. [Using voltage glitching to unleash the A100 in my mining card](https://news.ycombinator.com/item?id=50451903) (↑239, 💬98)
**Article:** The author discovers a voltage fault-injection vulnerability in NVIDIA’s GA100 fuse controller that allows arbitrary fuse blowing, then uses it to unlock a CMP 170HX mining card into effectively an A100-80G. The unlocked card exposes more SMs, HBM, PCIe Gen4, NVLink, ECC, and MIG, and can outperform a retail A100 because it enables more functional SMs. The post explains GA100 product segmentation, fuse regions, and the glitching process.

**Comments:** Commenters are astonished that cards shipped with large amounts of disabled HBM and debate whether the disabled resources reflect binning defects or market segmentation. Several warn that unlocked cards may have bad RAM, need better cooling, and have already risen sharply in price. Others discuss NVIDIA’s product-tiering economics, the long reverse-engineering effort, and joke about “downloading more VRAM.”

## 25. [Tools for exploring the souls of large language models](https://news.ycombinator.com/item?id=50458434) (↑10, 💬4)
**Article:** The post discusses growing interest in mechanistic interpretability and metaphysical questions about whether LLMs have “souls,” then introduces TinyGPT Visualizer, an open-source tool for inspecting a small but real language model’s internals. The author aims to make interpretability techniques more accessible so more people can examine how models form outputs.

**Comments:** One commenter says mechanistic interpretability is accessible to anyone willing to learn, and another calls the tool a nice find. Others dismiss the soul framing as fictional or unrelated to religious conceptions of the soul.

## 26. [Tinfoil (YC P25) is hiring an applied AI security engineer in San Francisco](https://news.ycombinator.com/item?id=50452404) (↑1, 💬0)
**Article:** Tinfoil, a security research lab building a private, verifiable AI cloud, is hiring an Applied AI Security Engineer in San Francisco. The customer-facing role involves turning threat models into deployment architectures, building pilots and evals, leading security reviews, and feeding customer needs back into product and research.

**Comments:** (no comments)

## 27. [The tiny transmitter tracking monarch butterflies' migration, Canada to Mexico](https://news.ycombinator.com/item?id=50438435) (↑23, 💬5)
**Article:** Project Monarch uses a 60-milligram solar-powered Bluetooth transmitter, attached with eyelash glue, to track monarch butterflies on their migration from Canada to Mexico. Smartphones and dedicated receivers relay signals to map routes, identify habitat gaps, and guide “monarch waystation” planting.

**Comments:** Commenters were impressed that an RF tracker can be placed on a butterfly and asked how the smartphone-relay mechanism works, comparing it to AirTags. Others raised espionage and tracking implications, while one said the app’s plotted paths appeared plausible.

## 28. [We need more goat sacrifices](https://news.ycombinator.com/item?id=50452652) (↑169, 💬99)
**Article:** Adam Mastroianni argues that many well-intentioned social interventions fail and proposes ritual “goat sacrifices” as procedural humility before launching policies. He cites examples such as School Improvement Grants, diversity officers, One Laptop Per Child, and Rossi’s satirical “Iron Law” of evaluation.

**Comments:** Commenters debated whether the failures reflect flawed social science, bad implementation, political incentives, or cherry-picked examples. Several discussed measurement problems and Goodhart’s law, while others challenged specific claims and argued for more systematic experimentation rather than passivity.

## 29. [AI, activity, and outcomes in software engineering](https://news.ycombinator.com/item?id=50455332) (↑99, 💬95)
**Article:** Christian Bird’s talk examines the “activity-outcome gap” in software engineering: AI speeds up code writing, but shipping does not improve proportionally because review, QA, deployment, and organizational processes remain bottlenecks. It draws on interviews and studies of developer AI use and autonomy.

**Comments:** Many commenters rejected the title’s premise, saying they are shipping faster, while others agreed that review, QA, product alignment, and deployment are now the limiting factors. Some noted increased complexity and bug rates, and the author clarified the talk asks why shipping is not even faster given coding gains.

## 30. [Pharo in the Browser with WebAssembly](https://news.ycombinator.com/item?id=50453763) (↑113, 💬32)
**Article:** Pharo World runs the Pharo Smalltalk environment in the browser via WebAssembly, with image and file loading, a console, and Git proxy settings. It aims to make a full live Smalltalk system accessible without local installation.

**Comments:** Commenters shared nostalgia for Smalltalk’s coherent live-programming environment and expressed surprise at how well Pharo runs in a browser, including on mobile. Others reported Firefox zoom and Android back-button bugs, asked about the implementation and real-world uses, and noted existing Pharo applications.

---
_Generated 2026-11-11 16:05 MDT_

---

## Recent Digests

- [Nov 11](./archives/2026/nov/hn-digest-2026-11-11.md)
- [Nov 10](./archives/2026/nov/hn-digest-2026-11-10.md)
- [Nov 9](./archives/2026/nov/hn-digest-2026-11-09.md)
- [Nov 8](./archives/2026/nov/hn-digest-2026-11-08.md)
- [Nov 7](./archives/2026/nov/hn-digest-2026-11-07.md)
- [Nov 6](./archives/2026/nov/hn-digest-2026-11-06.md)
- [Nov 5](./archives/2026/nov/hn-digest-2026-11-05.md)

[Full archive](./archives/) (183 issues)

_If you want more, explore the [archive folder](./archives/)._
