---
layout: default
title: "Horizon Summary: 2026-05-21 (EN)"
date: 2026-05-21
lang: en
---

> From 26 items, 13 important content pieces were selected

---

1. [OpenAI Model Disproves Central Conjecture in Discrete Geometry](#item-1) ⭐️ 10.0/10
2. [SpaceX S-1 Reveals Anthropic's $1.25B Monthly Cloud Deal](#item-2) ⭐️ 10.0/10
3. [GitHub Confirms Breach of 3,800 Repos via Malicious VSCode Extension](#item-3) ⭐️ 9.0/10
4. [Google Releases Gemini 3.5 Flash with Major Price Hike and Massive Deployment](#item-4) ⭐️ 9.0/10
5. [SpiderMonkey Engine Deprecates asm.js in Favor of WebAssembly](#item-5) ⭐️ 8.0/10
6. [Reverse Engineering Apple's macOS Video Wallpapers with Phosphene](#item-6) ⭐️ 7.0/10
7. [Donald Knuth's 1980 Paper on Digitally Rendering the Letter 'S'](#item-7) ⭐️ 7.0/10
8. [Flipper One Tech Specs Announced with Linux SoC](#item-8) ⭐️ 7.0/10
9. [Intuit Lays Off Over 3,000 Employees Amid AI Pivot Debate](#item-9) ⭐️ 7.0/10
10. [The Deportation of Qian Xuesen and the Rise of China's Missile Program](#item-10) ⭐️ 7.0/10
11. [Google Quietly Fights Manipulation of Its AI Search Overviews](#item-11) ⭐️ 7.0/10
12. [Simon Willison Reviews Google I/O: Gemini Spark and Antigravity](#item-12) ⭐️ 7.0/10
13. [DOS Zone Brings Classic DOS Games to the Browser](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI Model Disproves Central Conjecture in Discrete Geometry](https://openai.com/index/model-disproves-discrete-geometry-conjecture/) ⭐️ 10.0/10

An OpenAI model has successfully disproved a central conjecture in discrete geometry by finding a specific counterexample to Erdős' original conjecture. This marks a significant milestone where an AI system has generated a novel mathematical proof with non-trivial tweaks to existing literature. This breakthrough demonstrates the potential of AI to assist in advanced mathematical research and break through the increasing super-specialization in science. It highlights the impressive ability of large language models to transfer sophisticated concepts across different domains, such as applying algebraic number theory to geometric questions. The disproof was achieved by finding a counterexample rather than proving the conjecture true, which some note requires less theoretical grounding. The model's proof successfully brought unexpected, sophisticated ideas from algebraic number theory to bear on an elementary geometric question, making the overall publication novel.

hackernews · tedsanders · May 20, 19:05 · [Discussion](https://news.ycombinator.com/item?id=48212493)

**Background**: Automated theorem proving (ATP) is a subfield of automated reasoning that deals with proving mathematical theorems by computer programs. Historically, a major challenge in ATP has been formalizing the mathematical problem into a computable format, such as the Lean programming language. Recent advancements in large language models are shifting this landscape, enabling AI to move beyond mere computation to pattern recognition and cross-domain knowledge transfer in mathematical research.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Automated_theorem_proving">Automated theorem proving</a></li>

</ul>
</details>

**Discussion**: The community views this as an exciting and novel achievement, particularly praising the model's ability to transfer sophisticated ideas from algebraic number theory to geometry. However, some commenters point out that finding a counterexample is somewhat less interesting than proving a conjecture true, as the latter requires deeper theoretical crafting, while others predict the emergence of more specialized math AI resembling chess engines like Stockfish.

**Tags**: `#AI`, `#Mathematics`, `#Discrete Geometry`, `#OpenAI`, `#Automated Theorem Proving`

---

<a id="item-2"></a>
## [SpaceX S-1 Reveals Anthropic's $1.25B Monthly Cloud Deal](https://simonwillison.net/2026/May/20/spacex-s1/#atom-everything) ⭐️ 10.0/10

SpaceX's S-1 filing reveals that Anthropic has entered into a Cloud Services Agreement to access compute capacity on COLOSSUS and COLOSSUS II, agreeing to pay a staggering $1.25 billion per month through May 2029. This monumental financial commitment signals a major paradigm shift in the AI industry, as a leading AI lab is relying on the infrastructure of a rival entity for massive compute resources. It also suggests a strategic pivot for xAI towards becoming an AI infrastructure provider rather than solely a model developer. The agreement features a reduced fee for capacity ramping in May and June 2026, and either party can terminate the contract with just 90 days' notice. Meanwhile, xAI continues to use COLOSSUS II to train its own proprietary model, Grok 5.

rss · Simon Willison · May 20, 22:26

**Background**: COLOSSUS is xAI's AI training supercomputer located in Memphis, Tennessee, which became operational in July 2024 and is currently the world's largest AI supercomputer. Originally built to train xAI's chatbot Grok, the immense cluster is now being leveraged to provide computing support to third parties like Anthropic to meet the soaring global demand for AI infrastructure.

<details><summary>References</summary>
<ul>
<li><a href="https://www.datacenterdynamics.com/en/news/anthropic-to-use-all-of-spacex-xais-colossus-1-data-center-compute/">Anthropic to use all of SpaceX-xAI's Colossus 1 data center compute - DCD</a></li>
<li><a href="https://x.ai/news/anthropic-compute-partnership">New Compute Partnership with Anthropic | xAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Colossus_(supercomputer)">Colossus (supercomputer) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community is debating whether xAI leasing out its premier compute indicates a plateau in its own frontier model improvements or a strategic pivot to infrastructure and space compute. Other significant concerns include the environmental impact of Colossus's unpermitted gas turbine generators and the security risks of a rival CEO potentially having access to Anthropic's model training data and token streams.

**Tags**: `#AI Infrastructure`, `#Cloud Computing`, `#SpaceX`, `#Anthropic`, `#AI Industry`

---

<a id="item-3"></a>
## [GitHub Confirms Breach of 3,800 Repos via Malicious VSCode Extension](https://www.bleepingcomputer.com/news/security/github-confirms-breach-of-3-800-repos-via-malicious-vscode-extension/) ⭐️ 9.0/10

GitHub officially confirmed that a malicious VSCode extension was used to breach 3,800 repositories, marking a significant supply chain attack on the platform. This incident directly resulted from the editor's insecure extension model allowing unauthorized access to internal codebases. This breach highlights a systemic vulnerability in the software supply chain, where widely-used developer tools like VSCode can become dangerous attack vectors due to a lack of strict permission models. It affects the broader developer ecosystem by demonstrating how a compromised local editor can lead to massive repository breaches on core platforms like GitHub. The breach occurred because VSCode extensions currently operate with almost no security boundaries or explicit permission systems, allowing them to access and exfiltrate sensitive repository data. Users have noted that the editor frequently prompts installing unverified third-party extensions based on file types, making it difficult to distinguish official extensions from malicious ones.

hackernews · Timofeibu · May 20, 13:43 · [Discussion](https://news.ycombinator.com/item?id=48207660)

**Background**: A software supply chain attack occurs when an adversary compromises a seemingly low-level or unimportant software component to inject malicious code into the larger software that depends on it. In the context of code editors like VSCode, extensions often require deep access to the developer's workspace and environment, yet they lack granular permission controls, making them an ideal vector for such attacks. Previous incidents, such as the malicious "solidity-macos" extension, have demonstrated how malicious code can be injected into legitimate dependencies to execute supply chain attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Supply_chain_attack">Supply chain attack - Wikipedia</a></li>
<li><a href="https://dev.to/changfeng/critical-security-alert-malicious-vscode-extension-solidity-macos-contains-backdoor-ck6">Critical Security Alert: Malicious VSCode Extension "solidity-macos..."...</a></li>

</ul>
</details>

**Discussion**: The community expressed strong frustration over VSCode's lack of an explicit permission system, with many considering it grossly irresponsible for a company like GitHub to allow employees to install random extensions. Several users shared their mitigation strategies, such as switching to the Zed editor for its WASM-based extension model, using Code Server in Docker containers, or strictly limiting installations to official company-owned extensions.

**Tags**: `#security`, `#github`, `#vscode`, `#supply-chain-attack`, `#developer-tools`

---

<a id="item-4"></a>
## [Google Releases Gemini 3.5 Flash with Major Price Hike and Massive Deployment](https://simonwillison.net/2026/May/19/gemini-35-flash/#atom-everything) ⭐️ 9.0/10

Google announced the general availability of Gemini 3.5 Flash at Google I/O, skipping the preview phase and immediately deploying it across billions of users via Google Search, the Gemini app, and enterprise platforms. Alongside the release, Google introduced a new beta Interactions API for server-side history management. The immediate, massive deployment of Gemini 3.5 Flash across consumer products signals Google's aggressive push to integrate its latest AI into everyday tools, despite a significant price increase for API users. This move reflects a broader industry trend where major AI labs are testing the price tolerance of developers while subsidizing free consumer access. Gemini 3.5 Flash is priced at $1.50 per million input tokens and $9 per million output tokens, making it three times more expensive than Gemini 3 Flash Preview and six times more than 3.1 Flash-Lite. The model features a January 2025 knowledge cut-off, supports up to 1,048,576 input tokens and 65,536 output tokens, but notably lacks computer use capabilities.

rss · Simon Willison · May 19, 22:40

**Background**: The Gemini "Flash" models are traditionally Google's faster, more cost-efficient alternatives to the "Pro" models, making this significant price increase a notable departure from previous expectations. Google Antigravity is an AI-powered, agent-first integrated development environment (IDE) designed for building AI agents, while the Gemini Enterprise Agent Platform provides businesses with tools to build and scale enterprise-grade agents. The new Interactions API mirrors OpenAI's Responses API, specifically focusing on server-side conversation history management to simplify development.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Google_Antigravity">Google Antigravity - Wikipedia</a></li>
<li><a href="https://cloud.google.com/products/gemini-enterprise-agent-platform">Gemini Enterprise Agent Platform (formerly Vertex AI) | Google Cloud</a></li>

</ul>
</details>

**Tags**: `#AI/ML`, `#Google`, `#Gemini`, `#LLM`, `#Product Launch`

---

<a id="item-5"></a>
## [SpiderMonkey Engine Deprecates asm.js in Favor of WebAssembly](https://spidermonkey.dev/blog/2026/05/20/saying-goodbye-to-asmjs.html) ⭐️ 8.0/10

Mozilla's SpiderMonkey JavaScript engine has officially announced the deprecation and removal of asm.js, marking the end of this transitional technology. This move signals that WebAssembly has fully matured as the standard for running native-speed code in the browser. This marks a significant milestone in web evolution, as a major browser engine officially retires a transitional hack in favor of a robust, standardized alternative. It impacts the broader ecosystem by closing the chapter on early experiments to bring C++ to the web, solidifying WebAssembly as the definitive path forward. Unlike WebAssembly, asm.js is still standard JavaScript, which results in larger bundle sizes and requires the code to be parsed into an Abstract Syntax Tree (AST), leading to slower load times. The deprecation means that engines will no longer need to maintain the specific optimizations required to run this highly optimizable JS subset at near-native speeds.

hackernews · eqrion · May 20, 12:01 · [Discussion](https://news.ycombinator.com/item?id=48206340)

**Background**: asm.js was a strict, low-level subset of JavaScript designed by Mozilla to allow C and C++ code to be compiled for the web while maintaining performance considerably better than standard JavaScript. It served as Mozilla's response to Google's NaCl and PNaCl initiatives, which also aimed to run native code in the browser. Eventually, the industry converged on WebAssembly, a safe, portable, low-level code format designed for efficient execution and compact representation, making asm.js's complex workarounds obsolete.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Asm.js">asm . js - Wikipedia</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/WebAssembly">WebAssembly | MDN</a></li>
<li><a href="https://spidermonkey.dev/">Home | SpiderMonkey JavaScript /WebAssembly Engine</a></li>

</ul>
</details>

**Discussion**: The community sentiment is bittersweet, acknowledging that while the deprecation makes sense, it is sad to see a groundbreaking technology fade away. Commenters highlighted asm.js's historical importance, noting how it enabled early browser-based applications like Figma and Unreal Engine, and fondly recalled Gary Bernhardt's famous 'Birth and Death of JavaScript' talk which seemingly predicted this trajectory.

**Tags**: `#asm.js`, `#WebAssembly`, `#SpiderMonkey`, `#Web Standards`, `#JavaScript`

---

<a id="item-6"></a>
## [Reverse Engineering Apple's macOS Video Wallpapers with Phosphene](https://github.com/kageroumado/phosphene) ⭐️ 7.0/10

A developer has reverse-engineered Apple's private WallpaperExtensionKit.framework and released Phosphene, an open-source tool that enables users to set custom video wallpapers on macOS. Unlike Apple's default Aerials, these custom videos continue playing on the desktop rather than just the lock screen. This breakthrough provides macOS users with a highly requested customization feature that Apple does not natively support, allowing personal videos to be seamlessly integrated into the system settings. It also demonstrates that Apple's private wallpaper frameworks can be successfully replicated, opening the door for further system-level customizations. The renderer drives AVSampleBufferDisplayLayer directly using PTS-offset gapless looping to ensure smooth playback, and it intelligently pauses or downshifts quality based on thermal state, battery level, brightness, and window occlusion. Because an add button could not be added to the native Settings app, a companion app is required to place the custom videos in the correct system directory.

hackernews · kageroumado · May 20, 23:54 · [Discussion](https://news.ycombinator.com/item?id=48215979)

**Background**: Apple's macOS uses a private framework called WallpaperExtensionKit.framework to control what is displayed in the Settings app and manage system wallpapers. AVSampleBufferDisplayLayer is an Apple AVFoundation class designed to display compressed or uncompressed video frames efficiently. PTS-offset gapless looping is a technique used to loop video seamlessly without visible or audible gaps by manipulating presentation time stamps.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.apple.com/documentation/avfoundation/avsamplebufferdisplaylayer">AVSampleBufferDisplayLayer | Apple Developer Documentation</a></li>

</ul>
</details>

**Discussion**: The community is highly enthusiastic, with users expressing excitement that they can finally use their own videos for both the desktop and lock screen. Some users noted nostalgia for Windows Vista's video wallpapers, while others suggested the developer should emphasize the custom video capability more in the project's title to better highlight its main value.

**Tags**: `#macos`, `#reverse-engineering`, `#open-source`, `#customization`, `#apple`

---

<a id="item-7"></a>
## [Donald Knuth's 1980 Paper on Digitally Rendering the Letter 'S'](https://gwern.net/doc/design/typography/1980-knuth.pdf) ⭐️ 7.0/10

Donald Knuth's 1980 paper, recently resurfaced, explores the intricate mathematical and typographical challenges of digitally rendering the letter 'S' using the METAFONT system. It highlights the specific geometrical and path construction difficulties inherent in translating a curved letterform into a precise digital description. This paper is significant because it demonstrates the profound mathematical complexity hidden behind seemingly simple typographic elements, which was foundational for the evolution of digital typesetting. Knuth's work on METAFONT directly influenced the quality and feasibility of digital font design, ensuring that systems like TeX could produce aesthetically precise documents. The paper specifically addresses the difficulty of defining the smooth, double-curved shape of an 'S' using METAFONT's geometrical equations and path construction operations. A reader also identified a potential error in Figure 9 of the scanned PDF, where several distinct glyphs appear pixel-by-pixel identical.

hackernews · bambax · May 20, 23:58 · [Discussion](https://news.ycombinator.com/item?id=48216016)

**Background**: METAFONT is a description language and interpreter created by Donald Knuth to define raster fonts, originally designed as a companion to his TeX typesetting system. Unlike drawing fonts manually, METAFONT uses geometrical equations and macro instructions to define glyph shapes and design parameters like x-height and slant, allowing for the algorithmic generation of entire font families.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Metafont">Metafont</a></li>

</ul>
</details>

**Discussion**: The community appreciates the historical and mathematical depth of the paper, with one user humorously summarizing it as a highly technical version of "draw an S; next draw a more different S." Discussions also include a spotted error in Figure 9 of the scan, a charming anecdote about Knuth's wife asking why early attempts weren't "S shaped," and a recommendation for a related lecture by Étienne Ghys.

**Tags**: `#typography`, `#donald-knuth`, `#metafont`, `#tex`, `#mathematics`

---

<a id="item-8"></a>
## [Flipper One Tech Specs Announced with Linux SoC](https://docs.flipper.net/one/general/tech-specs) ⭐️ 7.0/10

Flipper has officially revealed the technical specifications for the upcoming Flipper One, featuring a Linux System on a Chip (SoC), dual RJ45 Ethernet ports, a USB-A port, and a nano SIM slot. The device also introduces an M.2 slot for interchangeable radio cards and a 256x144 pixel monochrome LCD display. This announcement marks a significant evolution from the original Flipper Zero, shifting from a simple multi-tool to a more powerful, network-centric Linux device capable of advanced pentesting and routing tasks. However, the apparent lack of built-in sub-1GHz, NFC, and IR radios raises questions about its identity as a direct successor to the Flipper Zero's hallmark capabilities. Notably, the display is routed to the microcontroller (MCU) rather than the Linux SoC, and it uses a 6-bit low-resolution grayscale screen despite the premium aluminum and Gorilla glass enclosure. While built-in radio capabilities for RFID, NFC, and IR seem absent, the device includes an M.2 slot that allows users to add SDR, LTE, or Wi-Fi cards, and it supports DisplayPort via USB-C for external monitors.

hackernews · gregsadetsky · May 20, 18:33 · [Discussion](https://news.ycombinator.com/item?id=48212046)

**Background**: The original Flipper Zero is a highly popular, portable multi-tool known for its built-in sub-1GHz radio (CC1101 chip), RFID, NFC, and infrared capabilities, making it a favorite for hardware hacking and pentesting. A System on a Chip (SoC) integrates all major electronic components of a computer onto a single chip, enabling more complex operating systems like Linux to run on handheld devices. Penetration testing (pentesting) involves authorized simulated cyberattacks to evaluate system security, a task for which the Flipper devices are commonly utilized.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.flipper.net/one/general/tech-specs">Tech specs - Flipper One Documentation</a></li>
<li><a href="https://sapsan-sklep.pl/en/blogs/articles/discover-flipper-one-what-it-has-to-offer">Flipper One is Coming - What We Already Know? | Sapsan Blog</a></li>

</ul>
</details>

**Discussion**: The community is highly divided, with some users appreciating the powerful networking features like dual Ethernet and a SIM slot for use as a mobile router, while others are deeply disappointed by the apparent removal of core radio features (RFID, NFC, IR, sub-1GHz). Critics also find the design choices baffling, specifically questioning why a premium device with an aluminum enclosure and Gorilla glass would use a 6-bit grayscale display routed to the MCU instead of the SoC, and many doubt its practical utility compared to the novelty of the original Flipper Zero.

**Tags**: `#hardware`, `#infosec`, `#flipper`, `#pentesting`, `#embedded-linux`

---

<a id="item-9"></a>
## [Intuit Lays Off Over 3,000 Employees Amid AI Pivot Debate](https://techcrunch.com/2026/05/20/intuit-to-lay-off-over-3000-employees-to-refocus-on-ai/) ⭐️ 7.0/10

Intuit is laying off over 3,000 employees, though there is conflicting information on whether the cuts are a strategic pivot to focus on AI or simply a move to increase corporate effectiveness. The CEO stated the layoffs have 'nothing to do with AI,' contradicting some media narratives framing it as an AI refocus. This event highlights a growing industry trend where companies may use the AI narrative to restructure or downsize, raising questions about the genuine integration of AI in enterprise software. It also sparks critical debate on the suitability of non-deterministic AI models in highly regulated, accuracy-dependent fields like tax preparation. The layoffs affect over 3,000 workers at the financial software company known for TurboTax. While TechCrunch framed the layoffs around an AI refocus, the CEO explicitly told CNBC that the cuts were about becoming more effective, not AI.

hackernews · wapasta · May 21, 00:36 · [Discussion](https://news.ycombinator.com/item?id=48216278)

**Background**: Intuit is a major American business and financial software company that produces products like TurboTax, QuickBooks, and Credit Karma. Tax preparation is a highly regulated domain where accuracy and determinism are crucial, making the integration of probabilistic AI models like LLMs potentially risky. Recently, many tech companies have cited AI investments as a reason for restructuring, even when the immediate connection to AI product development is unclear.

**Discussion**: The community is sharply divided on the narrative behind the layoffs, pointing out the contradiction between the CEO's statement and the media's AI framing. Users also debated the practical value of AI in tax software, with some expressing concern over non-determinism in tax filing, while others shared success stories of bypassing TurboTax entirely to file taxes using general-purpose LLMs like Claude and ChatGPT.

**Tags**: `#AI`, `#layoffs`, `#Intuit`, `#industry-trends`, `#tax-tech`

---

<a id="item-10"></a>
## [The Deportation of Qian Xuesen and the Rise of China's Missile Program](https://www.usni.org/magazines/naval-history/2025/december/missile-genius-america-lost-and-china-gained) ⭐️ 7.0/10

A 2025 article revisits the historical case of Qian Xuesen, a brilliant aerospace engineer who was deported from the US and subsequently founded China's missile program. The piece highlights the profound consequences of this US security apparatus error on global aerospace dynamics. This historical event serves as a critical case study on how immigration policies and national security apparatuses can inadvertently damage a country's technological advantage. It remains highly relevant today as the US continues to grapple with balancing national security with the influx of foreign scientific talent. Qian Xuesen's primary genius lay not just in technical expertise, but in his exceptional ability to build and lead massive aerospace organizations. Despite his deportation, the counterfactual that China could not have indigenously achieved its missile capabilities remains unlikely, though significantly delayed.

hackernews · thnaks · May 20, 17:48 · [Discussion](https://news.ycombinator.com/item?id=48211409)

**Background**: Qian Xuesen was a prominent Chinese aerospace engineer who worked on jet propulsion and helped found the Jet Propulsion Laboratory (JPL) in the US during the 1940s. During the Red Scare, he was falsely accused of being a communist, stripped of his security clearance, and deported to China in 1955. Upon returning, he became the father of China's space and missile programs, leading the development of the Dongfeng missile and the Long March rocket.

**Discussion**: The Hacker News discussion highlights that Qian's organizational genius makes for a boring movie, contrasting with more dramatic biopics. Commenters debate the ongoing US immigration hurdles for Chinese scientists, noting that while the US still attracts a net influx of talent, an error rate of zero in security is unachievable, and China's indigenous missile success might have eventually happened anyway. The story is noted to be highly mythologized in China today.

**Tags**: `#history`, `#aerospace`, `#immigration`, `#us-china`, `#biography`

---

<a id="item-11"></a>
## [Google Quietly Fights Manipulation of Its AI Search Overviews](https://www.bbc.com/future/article/20260519-google-tackles-attempts-to-hack-its-ai-results) ⭐️ 7.0/10

Google is actively working to combat attempts to manipulate its AI Overviews feature, which generates AI-powered summaries for search queries. The company is quietly implementing defenses against actors trying to hack or alter these AI-generated search results. This is significant because the manipulation of AI search summaries could spread misinformation on critical topics like health and finance, undermining trust in the internet's primary information gateway. It also highlights the broader industry challenge of ensuring AI reliability as AI-powered search increasingly replaces traditional search engines. The article highlights a specific example where a query for the 2026 South Dakota International Hot Dog Eating Champion was manipulated, though critics argue this is a trivial case. Additionally, a link in the article claiming to provide examples of manipulated health and financial information was broken, pointing to a local file path instead.

hackernews · tigerlily · May 20, 10:57 · [Discussion](https://news.ycombinator.com/item?id=48205782)

**Background**: Google AI Overviews is an artificial intelligence feature integrated into Google Search that provides AI-generated summaries of search results. Since its introduction, the feature has faced criticism regarding its accuracy and the potential to reduce traffic to external websites. The rise of such AI features has also sparked a new frontier in SEO, where bad actors attempt to game the AI's reasoning to surface their own content.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Google_AI_Overviews">Google AI Overviews</a></li>

</ul>
</details>

**Discussion**: The community is highly skeptical, with users pointing out that the highlighted manipulation example is trivial and unconvincing, while others argue that Google's primary incentive is not truth but keeping users on the page to drive SEO revenue. Several commenters also noted that AI lacks true reasoning and that the degradation of search quality is driving users toward chatbots instead.

**Tags**: `#AI`, `#SEO`, `#Google`, `#Search`, `#Misinformation`

---

<a id="item-12"></a>
## [Simon Willison Reviews Google I/O: Gemini Spark and Antigravity](https://simonwillison.net/2026/May/20/google-io/#atom-everything) ⭐️ 7.0/10

At Google I/O, Google announced Gemini Spark, a 24/7 personal AI agent that connects natively to Google apps and runs on Gemini 3.5 Flash and Antigravity, alongside the release of the Gemini 3.5 Flash model. Additionally, Google is transitioning its open-source Gemini CLI to the closed-source Antigravity CLI starting June 18th. The launch of Gemini Spark signals Google's major push into the personal AI agent space, directly competing with projects like OpenClaw, but it raises significant security concerns regarding prompt injection and sensitive data handling. The shift from open-source to closed-source tooling for the CLI also represents a notable change for the developer ecosystem. Gemini Spark operates in a fully managed, secure runtime using fresh, isolated, ephemeral VMs, routing traffic through a secure Agent Gateway with Data Loss Prevention (DLP) policies to protect user credentials. Antigravity serves as the underlying infrastructure, featuring a desktop app, a Go-based CLI, and a Python SDK wrapping a closed-source Go binary.

rss · Simon Willison · May 20, 15:32

**Background**: Gemini 3.5 Flash is Google's latest model optimized for real-world tasks and rapid agentic loops, offering frontier-level intelligence at a lower cost. OpenClaw is an open-source personal AI assistant that runs locally and integrates with external LLMs for autonomous workflows. Prompt injection remains a critical vulnerability for AI agents, as malicious inputs can manipulate the agent into executing unintended actions, making robust isolation and security measures essential when agents access sensitive user data.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/products/gemini-app/next-evolution-gemini-app/">The Gemini app becomes more agentic, delivering proactive, 24/7 help</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/models/gemini-3.5-flash">Gemini 3 . 5 Flash | Gemini API | Google AI for Developers</a></li>
<li><a href="https://github.com/openclaw/openclaw">GitHub - openclaw/openclaw: Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞</a></li>

</ul>
</details>

**Tags**: `#AI Agents`, `#Google I/O`, `#Gemini`, `#LLM`, `#Tech Commentary`

---

<a id="item-13"></a>
## [DOS Zone Brings Classic DOS Games to the Browser](https://dos.zone/) ⭐️ 6.0/10

DOS Zone offers a comprehensive platform where users can play classic DOS and Windows games directly in their web browser without registration or advertisements. The site also features a multiplayer portal for playing retro titles like Quake and Doom online with friends. This platform significantly lowers the barrier to entry for retro gaming and software preservation by eliminating the need for local emulators or complex configurations. However, it also sparks important ethical debates regarding the distribution of abandonware, especially when some hosted titles are still commercially available on platforms like Steam and GOG. The site was created by the developer of js-dos, a robust browser-based emulator that allows for on-the-fly patching of DOS game ZIP bundles. Technically-minded users have noted that legacy games running on modern systems or emulators can experience speed anomalies due to changes in OS schedulers at the NT kernel level compared to older DOS and Windows ME environments.

hackernews · rglover · May 20, 22:53 · [Discussion](https://news.ycombinator.com/item?id=48215418)

**Background**: Abandonware refers to software, typically older video games, that is no longer sold or supported by its creator, but distributing it for free is still legally considered software piracy since the copyright is not actually abandoned. Running DOS games in a browser relies on web porting and emulation technologies like js-dos to recreate the original hardware and software environment, which can sometimes lead to compatibility or performance quirks that differ from the original experience on vintage hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://dos.zone/">DOS Zone | DOS games in browser</a></li>
<li><a href="https://en.wikipedia.org/wiki/Abandonware">Abandonware</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights a mix of technical insights and ethical concerns, with one user pointing out that hosting games still available on Steam or GOG stretches the definition of abandonware. Others discussed technical quirks like NT kernel scheduler changes causing speed issues in legacy games like Sim City 3000, and the desire for more streamlined multiplayer interfaces, with one developer sharing their own modern web port of Quake 3.

**Tags**: `#retro-gaming`, `#emulation`, `#web-ports`, `#abandonware`, `#browser-games`

---