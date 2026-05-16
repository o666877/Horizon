---
layout: default
title: "Horizon Summary: 2026-05-16 (EN)"
date: 2026-05-16
lang: en
---

> From 23 items, 9 important content pieces were selected

---

1. [Google Project Zero Details Pixel 10 0-Click Exploit Chain](#item-1) ⭐️ 9.0/10
2. [Erlang/OTP 29.0 Released with Security and CLI Improvements](#item-2) ⭐️ 9.0/10
3. [Tech Leader Warns of Corporate 'AI Psychosis'](#item-3) ⭐️ 8.0/10
4. [Why Sigmoid Curves Won't Predict AI's End](#item-4) ⭐️ 8.0/10
5. [Zulip Transitions to Nonprofit Foundation as Core Team Joins Anthropic](#item-5) ⭐️ 8.0/10
6. [AI Coding Agents Reduce Programming Language Lock-In](#item-6) ⭐️ 8.0/10
7. [AI Makes Programming Languages Fungible, Says Mitchell Hashimoto](#item-7) ⭐️ 8.0/10
8. [Project Gutenberg Announces Recent Website Improvements](#item-8) ⭐️ 7.0/10
9. [California Bill Mandates Patches or Refunds for Shut Down Online Games](#item-9) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Google Project Zero Details Pixel 10 0-Click Exploit Chain](https://projectzero.google/2026/05/pixel-10-exploit.html) ⭐️ 9.0/10

Google Project Zero has detailed a new 0-click exploit chain for the Pixel 10 that allows attackers to gain root access through a Dolby bug and a kernel flaw. This discovery highlights that even though previous similar vulnerabilities were patched, new attack paths remain accessible, particularly through AI-powered messaging features that decode media before a user opens the message. This exploit chain is significant because it demonstrates how AI-powered features designed for user convenience inadvertently expand the 0-click attack surface by processing data before user interaction. It also raises broader concerns about the security of the Android ecosystem, as fast patch response times appear to be the exception rather than the rule for driver vulnerabilities. The exploit chain requires remarkably few bugs to gain kernel privileges from a 0-click context, combining a Dolby vulnerability with a kernel flaw. Notably, the researcher highlighted that this was the first time an Android driver bug they reported was patched within the standard 90-day vendor notification period.

hackernews · happyhardcore · May 15, 13:39 · [Discussion](https://news.ycombinator.com/item?id=48148460)

**Background**: Google Project Zero is a team of security analysts employed by Google to find zero-day vulnerabilities in software, operating under a strict 90-day disclosure deadline. A 0-click exploit allows an attacker to compromise a device without any interaction from the victim, making it highly dangerous. Recently, mobile operating systems have integrated AI-powered messaging features that automatically parse and decode incoming media to provide smart suggestions, which inadvertently processes potentially malicious payloads before the user even opens the message.

<details><summary>References</summary>
<ul>
<li><a href="https://projectzero.google/2026/01/pixel-0-click-part-3.html">A 0 - click exploit chain for the Pixel 9 Part 3: Where do... - Project Zero</a></li>
<li><a href="https://oxo.is/blog/2026/05/13/news-2026-05-13-a-0-click-exploit-chain-for-the-pixel-10-when-a-door-closes/">A 0 - click exploit chain for the Pixel 10: When a Door Closes...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Google_Project_Zero">Google Project Zero</a></li>

</ul>
</details>

**Discussion**: The community expressed frustration that AI features are automatically decoding messages before user interaction, expanding the attack surface despite past lessons. Commenters also noted that while Google's sub-90-day patch response is commendable, it highlights how slow the rest of the Android ecosystem typically is, and there is ongoing debate about whether the rate of AI-related exploits is genuinely increasing or simply receiving more media hype.

**Tags**: `#security`, `#0-click exploit`, `#android`, `#project-zero`, `#ai-attack-surface`

---

<a id="item-2"></a>
## [Erlang/OTP 29.0 Released with Security and CLI Improvements](https://www.erlang.org/news/188) ⭐️ 9.0/10

Erlang/OTP 29.0 has been officially released, introducing significant security enhancements such as disabling the SSH daemon and SFTP by default. Additionally, it adds the new io_ansi standard library module to support ANSI escape sequences for terminal styling and CLI applications. This release strengthens the out-of-the-box security posture of Erlang systems by eliminating default running services that could be exploited. The inclusion of io_ansi in the standard library also provides native support for building sophisticated CLI applications, filling a notable gap in the ecosystem. The io_ansi module allows developers to emit Virtual Terminal Sequences (ANSI sequences) to add colors and styling to text directly from the standard library. The decision to disable the SSH daemon and SFTP by default means administrators must now explicitly enable these services if required, reducing the system's attack surface.

hackernews · pyinstallwoes · May 15, 23:33 · [Discussion](https://news.ycombinator.com/item?id=48155297)

**Background**: Erlang is a concurrent, functional programming language and runtime system designed for building distributed, fault-tolerant, and highly available applications, originally developed by Ericsson in 1986. OTP (Open Telecom Platform) is the accompanying set of middleware, libraries, and design principles that standardize the creation of robust systems. The language's ability to support hot swapping and lightweight processes makes it a popular choice for telecommunications and messaging platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://www.erlang.org/news/188">Erlang/OTP 29.0 - Erlang/OTP</a></li>
<li><a href="https://en.wikipedia.org/wiki/Erlang/OTP">Erlang/OTP</a></li>

</ul>
</details>

**Discussion**: The community reacted positively to the security improvements, agreeing that disabling SSH and SFTP by default is a necessary modern precaution. Users are enthusiastic about the io_ansi module, noting that it significantly improves Erlang's previously lacking capabilities for building complex CLI applications, while others are curious about how new records will impact the broader ecosystem.

**Tags**: `#Erlang`, `#OTP`, `#Release Notes`, `#Distributed Systems`, `#Functional Programming`

---

<a id="item-3"></a>
## [Tech Leader Warns of Corporate 'AI Psychosis'](https://twitter.com/mitchellh/status/2055380239711457578) ⭐️ 8.0/10

Prominent tech leader Mitchell Hashimoto stated that entire companies are currently suffering from "AI psychosis" by outsourcing their core thinking and decision-making to AI systems rather than just using them as productivity tools. This highlights a growing risk in the tech industry where blind reliance on AI for strategic reasoning can lead to catastrophic system failures and poor business decisions. It also signals a potential market shift where traditional engineering rigor is being bypassed by prompt-driven development. The critique specifically targets the outsourcing of thinking and decision-making to AI, not the use of AI for writing code or automating tasks. Commenters noted that purely AI-generated systems could eventually reach a complexity threshold where AI introduces more defects than it fixes, creating a need for future "AI rescue consulting."

hackernews · reasonableklout · May 15, 20:26 · [Discussion](https://news.ycombinator.com/item?id=48153379)

**Background**: As generative AI tools like ChatGPT have become highly capable, many organizations have rapidly integrated them into workflows, sometimes replacing human analysis with AI-generated outputs. While AI excels at generating code or text based on prompts, it lacks true understanding and contextual reasoning, which can lead to confidently incorrect conclusions or fragile technical architectures if left unsupervised.

**Discussion**: The community displayed mixed sentiments: some agreed that outsourcing decision-making to AI is dangerous and predicted a future need for "AI rescue consulting" to fix unmaintainable AI-generated systems. Others argued that using AI for coding in standardized environments significantly boosts productivity without increasing incidents, while one commenter suggested this crisis might finally force software engineering to adopt true engineering discipline.

**Tags**: `#AI`, `#Software Engineering`, `#Industry Trends`, `#Tech Hype`, `#Decision Making`

---

<a id="item-4"></a>
## [Why Sigmoid Curves Won't Predict AI's End](https://www.astralcodexten.com/p/the-sigmoids-wont-save-you) ⭐️ 8.0/10

The article argues against relying on sigmoid (S-curve) curve-fitting to predict when AI progress will plateau. It asserts that such forecasts require understanding the fundamental physical or algorithmic limits of AI scaling rather than merely extrapolating historical technology trends. This perspective challenges the common assumption that AI scaling will inevitably hit a plateau similar to past technologies, which directly impacts long-term AI safety timelines, investment strategies, and policy planning. The author emphasizes that historical technology plateaus often occurred because a new generation of technology (like turbojets replacing propellers) took over, rather than a single technology simply topping out. Furthermore, without identifying the specific fundamental limits of neural networks, assuming an imminent plateau is logically flawed.

hackernews · Tomte · May 15, 10:51 · [Discussion](https://news.ycombinator.com/item?id=48147021)

**Background**: In machine learning, neural scaling laws are empirical observations that AI performance improves as the number of parameters, dataset size, and computational resources increase. Technology adoption and progress often follow a sigmoid or S-curve, where initial slow growth accelerates before plateauing as the technology reaches its fundamental limits or market saturation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_scaling_law">AI scaling law</a></li>
<li><a href="https://medium.com/@chemaballarin/the-most-important-curve-of-all-explains-tech-adoption-too-f2e0ac94f1c6">The most important curve of all explains tech adoption too | Medium</a></li>

</ul>
</details>

**Discussion**: The community highlighted Lindy's Law as an alternative heuristic, suggesting that without known fundamental limits, a trend will likely continue for about as long as it has existed. However, commenters also pointed out the author's potential bias toward continuous progress due to his personal prediction of AGI arriving soon, and noted that paradigm shifts—where new technologies replace old ones—complicate simple curve-fitting.

**Tags**: `#AI`, `#Scaling Laws`, `#S-Curves`, `#Technology Trends`, `#Forecasting`

---

<a id="item-5"></a>
## [Zulip Transitions to Nonprofit Foundation as Core Team Joins Anthropic](https://blog.zulip.com/2026/05/15/announcing-zulip-foundation/) ⭐️ 8.0/10

Zulip is transitioning to an independent nonprofit foundation called The Zulip Foundation, with the core leadership team stepping down and donating the company to this new entity. Simultaneously, the founding team and three senior members are leaving to join Anthropic. This transition guarantees that Zulip remains permanently free from commercial pressures like selling user data or inserting ads, securing its long-term open-source sustainability. The departure of the core team to a major AI company, however, raises questions about project continuity and leadership transitions in the open-source ecosystem. The announcement was made on a Friday afternoon, which some community members interpreted as an attempt to minimize attention, especially given recent controversial acquisitions in the open-source space. The departing team members emphasized that this is a donation to a nonprofit, distinctly different from an acquisition like Bun's.

hackernews · boramalper · May 15, 18:37 · [Discussion](https://news.ycombinator.com/item?id=48152168)

**Background**: Zulip is a popular open-source team collaboration tool distinguished by its unique topic-based threading, which combines the asynchronous nature of email with the immediacy of chat. It is widely used by Fortune 500 companies and major open-source projects, offering both a cloud solution and a self-hosted option for full data sovereignty.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/zulip/zulip">GitHub - zulip/zulip: Zulip server and web application. Open ...</a></li>
<li><a href="https://zulip.com/">Zulip — organized team chat</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed but generally positive regarding the nonprofit transition, with users praising the structural guarantee against future commercial enshittification. However, there is notable skepticism about the Friday afternoon announcement timing and the optics of the core team leaving for Anthropic, drawing unfavorable comparisons to recent events like the Bun acquisition, though others defend the founders' intentions.

**Tags**: `#open-source`, `#zulip`, `#governance`, `#anthropic`, `#sustainability`

---

<a id="item-6"></a>
## [AI Coding Agents Reduce Programming Language Lock-In](https://simonwillison.net/2026/May/14/not-so-locked-in/#atom-everything) ⭐️ 8.0/10

Simon Willison highlights that AI coding agents are drastically reducing the risk and cost of large-scale codebase rewrites, such as migrating legacy native mobile apps to React Native or Bun's migration from Zig to Rust. This shift means that if a technology choice turns out to be wrong, companies can now afford to port their code back to the original framework or language. This represents a major paradigm shift in software engineering, as traditional vendor and language lock-in is diminishing, fundamentally changing how companies evaluate platform risk and technology selection. Legacy modernization becomes much less daunting when the cost of reversing a rewrite is no longer prohibitive. A medium-sized tech company successfully used coding agents to rewrite legacy iPhone and Android apps to React Native, explicitly citing the ability to easily port back to native if needed as a deciding factor. This trend is further exemplified by Mitchell Hashimoto's observation regarding the Bun runtime's ongoing migration from the Zig programming language to Rust.

rss · Simon Willison · May 14, 22:53

**Background**: Historically, choosing a programming language or framework represented a massive, often irreversible investment, creating lock-in where switching costs were prohibitively high. Zig is a system programming language designed as a modern alternative to C, while Bun is a JavaScript runtime that was originally built with Zig but is now migrating parts to Rust. React Native is a popular framework that allows developers to build mobile applications for multiple platforms using a single codebase.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**Tags**: `#AI coding agents`, `#software engineering`, `#tech lock-in`, `#paradigm shift`, `#React Native`

---

<a id="item-7"></a>
## [AI Makes Programming Languages Fungible, Says Mitchell Hashimoto](https://simonwillison.net/2026/May/14/mitchell-hashimoto/#atom-everything) ⭐️ 8.0/10

Mitchell Hashimoto highlighted that programming languages are becoming increasingly fungible, using Bun's rapid AI-assisted port from Zig to Rust in just a week or two as a prime example. This signifies a potential paradigm shift in software engineering where AI drastically reduces language lock-in, making the choice of programming language expendable and transforming how architectural decisions are made. Hashimoto points out that while the Bun rewrite might seem like a win for Rust, it actually demonstrates that the project could adopt almost any language quickly, rendering the specific language choice expendable once it ceases to be useful.

rss · Simon Willison · May 14, 22:31

**Background**: Bun is a high-performance, all-in-one JavaScript runtime originally written in the Zig programming language, designed as a drop-in replacement for Node.js. Zig is a system programming language focused on performance and manual memory management, while Rust is another systems language known for its memory safety guarantees. Historically, rewriting a complex runtime in a different language would take months or years, creating massive lock-in, but AI-assisted coding tools are drastically compressing this timeline.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/bun: Incredibly fast JavaScript runtime ... Bun Guide: Install, Configure & Deploy the Fast JS Runtime ... Bun: The Fast JavaScript Runtime, Bundler, Test Runner, and ... Bun 2026: How the Anthropic Acquisition Reshapes the ... How to Install Bun - commandlinux.com</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**Tags**: `#ai`, `#llms`, `#rust`, `#zig`, `#software-engineering`

---

<a id="item-8"></a>
## [Project Gutenberg Announces Recent Website Improvements](https://www.gutenberg.org/) ⭐️ 7.0/10

Project Gutenberg has implemented significant improvements to its website over the past few months, with a project programmer confirming that even more updates are on the way. These changes have prompted users to revisit the platform and engage in extensive discussions about its utility and integration. As the oldest digital library, continuous improvements to Project Gutenberg ensure that this vital open-access resource remains accessible and user-friendly for modern readers. Enhancing the site's functionality directly benefits millions of readers who rely on it for free public domain ebooks. While specific technical updates were not detailed, the community highlighted ongoing friction with e-reader integrations, noting that devices like Kindle are actively hostile to direct downloads while others require third-party software like Calibre. Additionally, Italian users reported severe access issues, including a 404 error and an official police seizure notice from the tribunal of Rome.

hackernews · JSeiko · May 15, 16:15 · [Discussion](https://news.ycombinator.com/item?id=48150431)

**Background**: Project Gutenberg is the world's oldest digital library, founded by Michael S. Hart in 1971 when he digitized the United States Declaration of Independence on a Xerox Sigma V mainframe. It focuses on digitizing and archiving cultural works to provide free access to public domain ebooks, and has grown alongside the internet from its early ARPANET days.

**Discussion**: The community discussion was highly engaged, featuring personal stories of how the library profoundly impacted readers, such as helping an elderly veteran access classic literature. Users also debated the lack of native e-reader integrations—criticizing Kindle's hostility and the friction of using Calibre—and raised concerns about regional censorship, specifically regarding a police seizure notice blocking access in Italy.

**Tags**: `#digital-libraries`, `#ebooks`, `#project-gutenberg`, `#open-access`

---

<a id="item-9"></a>
## [California Bill Mandates Patches or Refunds for Shut Down Online Games](https://arstechnica.com/gaming/2026/05/bill-to-keep-online-games-playable-clears-key-hurdle-in-california/) ⭐️ 7.0/10

A proposed California bill has cleared a key hurdle, aiming to legally require game publishers to either provide offline patches or issue refunds when they shut down their online games. This legislation represents a major potential shift in digital consumer rights and software lifecycle management, directly challenging the industry norm where players permanently lose access to purchased games when servers are turned off. The bill appears to treat subscription-based and free-to-play games with in-game purchases differently than one-time purchase games, and games offered solely for the duration of a subscription are currently exempt from regulation.

hackernews · Lihh27 · May 15, 19:48 · [Discussion](https://news.ycombinator.com/item?id=48152994)

**Background**: Many modern games use always-online DRM (Digital Rights Management), requiring a constant internet connection to authenticate with a server, which means the game becomes completely unplayable when official servers shut down. In the past, communities have sometimes created server emulators or offline patches to revive these abandoned games, but this requires significant reverse-engineering effort and often exists in a legal gray area.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Always-on_DRM">Always - on DRM - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Server_emulator">Private server - Wikipedia</a></li>
<li><a href="https://kotaku.com/stormgate-rts-patch-offline-mode-after-server-provider-ditches-them-for-ai-2000683998">Stormgate Adding Offline Mode After Server Provider Ditches It For AI</a></li>

</ul>
</details>

**Discussion**: The community is divided, with some users advocating for open-sourcing server code as a fair compromise, while developers express concern that compliance costs and legal risks could make it harder to create online games or even bankrupt smaller studios. Others worry about unintended consequences, such as the bill's exemption for subscription games potentially accelerating the industry's shift toward that model to avoid compliance.

**Tags**: `#gaming`, `#legislation`, `#consumer-rights`, `#digital-ownership`, `#software-lifecycle`

---