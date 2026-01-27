## Hi there 👋

<!--
**avsc-sid/avsc-sid** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# Sid (avsc-sid)

I learn best by building. When something bothers my curiosity—*Why do chat apps feel “easy” until you try to make them secure? Why does a Discord bot work fine… until hundreds of messages hit at once?*—I turn it into a project, iterate, and keep refining until I understand what’s really going on under the hood.

My GitHub is a record of that learning arc: **real-time systems**, **security-minded design**, and **algorithmic problem solving**, explored across **Rust, C++, Python, JavaScript, C#, and Java**.

---

## Tech I use (and why)
**Rust** (safety + systems thinking), **C++** (performance + constraints),  
**Python/JS** (rapid iteration + product features), **C#** (Windows services), **Java** (foundations).

---

## My learning arc (what I keep chasing)

### 1) From “it works” → “it holds up”
Early on, I could make features. Over time, I started caring more about:
- **correctness under pressure** (edge cases, scaling, failure modes)
- **security as a design choice** (not a patch)
- **maintainability** (rewrites, cleaner structure, better boundaries)

### 2) From one language → the right language for the job
I’ve built similar ideas in different ecosystems—especially Discord bots—because I wanted to understand tradeoffs:
- rapid iteration (Python / JS)
- performance + safety (Rust)
- clarity and efficiency under constraints (C++)

### 3) From solving problems → explaining and organizing them
USACO work taught me to think in constraints and invariants. Web projects taught me to communicate ideas. Tools taught me to design for real workflows.

---

## Featured Projects (and what each one taught me)

### 🗨️ SkyChatServer-RUST — full-stack chat platform
**What it is:** a product-style chat system with real UX and a clear roadmap.  
**What I learned:** building a system end-to-end forces you to think about everything: auth, storage, UI/UX, and deployment—not just code that passes locally.

Highlights:
- chat + members page, automatic message loading, reply support
- login/register with admin approval, dynamic settings
- security-minded approach to passwords (client-side hashing + server rehashing)
- practical setup/deployment notes  
Repo: https://github.com/avsc-sid/SkyChatServer-RUST

---

### 🔐 ChatServer-RUST — secure chat server
**What it is:** a Rust chat server emphasizing security and robustness.  
**What I learned:** “secure” isn’t a label—it’s a stack of choices. I explored encryption, hashing, and defensive measures as part of the core design.

Highlights:
- encrypted DB file storage (AES-256), hashed passwords (SHA-512)
- HTTP + gzip support, IP/request filtering  
Repo: https://github.com/avsc-sid/ChatServer-RUST

---

### 🤖 DiscordBots — bots as a lab for real-time engineering
**What it is:** a collection of Discord bots and multiple generations of “SkyBot” across languages.  
**What I learned:** bots are small systems that behave like real services—always-on, event-driven, user-facing, and full of edge cases.

Includes:
- moderation/guild tooling and digital currency systems (OctoBot)
- server stats display and utility features
- “SkyBot” iterations in Python and JS + a Rust pre-release rewrite  
Repo: https://github.com/avsc-sid/DiscordBots

---

### 🧠 USACO — learning to think under constraints (C++)
**What it is:** contest submissions + a curated archive of past solutions.  
**What I learned:** competitive programming trained my ability to reason precisely—finding invariants, proving guarantees, and writing efficient implementations.

Repos:
- MyUSACOCode (Jan 2026): https://github.com/avsc-sid/MyUSACOCode
- USACOSamples (Bronze/Silver archive): https://github.com/avsc-sid/USACOSamples

---

### 🧰 SaveLocalWebsiteResources-JS — curiosity turned into a tool
**What it is:** a Chromium extension (with a DevTools panel UI) to save a website’s resources.  
**What I learned:** the web is an ecosystem of moving pieces—building tooling made me understand how pages are composed and loaded.  
Repo: https://github.com/avsc-sid/SaveLocalWebsiteResources-JS

---

### ⚙️ BingRewards-AutoSearch — automation that runs unattended
**What it is:** a C# Windows service that schedules automated browser sessions/jobs.  
**What I learned:** background services require discipline—scheduling, stability, and behavior when nobody is watching.  
Repo: https://github.com/avsc-sid/BingRewards-AutoSearch

---

## Other Projects
- MusicManager-RUST — metadata + ordering for song files  
  https://github.com/avsc-sid/MusicManager-RUST
- WorldHistory-Website-JS — thesis-driven site on capitalism & inequality  
  https://github.com/avsc-sid/WorldHistory-Website-JS
- MyScripts — small utilities/prototypes (fast experiments)  
  https://github.com/avsc-sid/MyScripts
- BankAccountSimulation-Java — fundamentals project  
  https://github.com/avsc-sid/BankAccountSimulation-Java

---

## What I’m excited to explore next
- more rigorous security (sanitization, E2E encryption experiments, safer auth patterns)
- performance profiling and scalability testing for real-time services
- cleaner architectures for bots/services so features don’t become tangled

---



# Sid (avsc-sid)

I build **real-time systems** and **tools that run unattended**—from Discord bots and chat servers to browser extensions and competitive-programming solutions. I like projects where **performance, reliability, and security** actually matter.

---

## What I’m focused on
- **Systems & Security:** auth flows, encrypted storage, safe-by-default design, deployment scripts
- **Product-minded engineering:** features users notice (chat UX, moderation tooling, progressive enhancement)
- **Algorithmic rigor:** USACO-style constraint-driven problem solving in C++

---

## Featured Projects

### 🗨️ SkyChatServer-RUST (full-stack chat platform)
A product-style chat system with real features and a clear roadmap:
- members page, built-in chat, auto message loading, reply support
- login/register with admin approval, dynamic settings
- security-minded approach (client-side password hashing + server rehashing)
- practical setup + deployment notes  
Repo: https://github.com/avsc-sid/SkyChatServer-RUST

### 🔐 ChatServer-RUST (secure chat server)
A Rust chat server emphasizing security and robustness:
- encrypted DB file storage (AES-256), hashed passwords (SHA-512)
- HTTP + gzip support, IP/request filtering  
Repo: https://github.com/avsc-sid/ChatServer-RUST

### 🤖 DiscordBots (multi-bot ecosystem; Python / JS / Rust)
A collection of Discord bots and iterations of “SkyBot” across languages:
- guild tooling + virtual currency + fun commands + leveling + music
- multiple generations (Python / JS) + Rust pre-release rewrite  
Repo: https://github.com/avsc-sid/DiscordBots

### 🧠 USACO (Contest + Practice Archive)
Competitive programming solutions in C++:
- **MyUSACOCode (Jan 2026):** contest implementations (Chip Exchange, COW Splits, Photoshoot)
- **USACOSamples:** curated Bronze/Silver solutions across many classic topics  
Repos:
- https://github.com/avsc-sid/MyUSACOCode
- https://github.com/avsc-sid/USACOSamples

### 🧰 SaveLocalWebsiteResources-JS (Chromium extension)
A browser extension (with DevTools panel UI) to download/save a website’s resources.  
Repo: https://github.com/avsc-sid/SaveLocalWebsiteResources-JS

### ⚙️ BingRewards-AutoSearch (C# Windows service)
A Windows service that schedules automated browser sessions/jobs for Bing searches.  
Repo: https://github.com/avsc-sid/BingRewards-AutoSearch

---

## More Projects
- **MusicManager-RUST** — manage song file metadata and ordering  
  https://github.com/avsc-sid/MusicManager-RUST
- **WorldHistory-Website-JS** — website project on capitalism & inequality (thesis-driven narrative)  
  https://github.com/avsc-sid/WorldHistory-Website-JS
- **MyScripts** — small utilities/prototypes (automation + quick experiments)  
  https://github.com/avsc-sid/MyScripts
- **BankAccountSimulation-Java** — fundamentals project  
  https://github.com/avsc-sid/BankAccountSimulation-Java

---

## Tech I use
**Rust, C++, Python, JavaScript/TypeScript, C#, Java**  
Also: web stacks (HTML/CSS), browser extension APIs, Linux tooling, scripting.

---

## Contact
- GitHub: https://github.com/avsc-sid

GitHub: https://github.com/avsc-sid

