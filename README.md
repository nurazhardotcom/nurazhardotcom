<h1 align="center">Nur Azhar</h1>
<p align="center"><strong>Clojure engineer · local-first AI agents · supply-chain security</strong></p>
<p align="center">
  <a href="https://nurazhar.com">🌐 Blog</a> ·
  <a href="https://gitlab.com/nurazhar">🦊 GitLab</a> ·
  <a href="https://github.com/nurazhardotcom">💻 GitHub</a>
</p>

---

Singapore-based software engineer building **privacy-preserving, local-first** systems.
I write primarily in **Clojure / Babashka** and care about deterministic data contracts,
sovereign compute, and software that respects the user.

> **Note:** my primary development home is [gitlab.com/nurazhar](https://gitlab.com/nurazhar).
> This GitHub account mirrors my public, resume-relevant projects so they're discoverable
> where most recruiters look. Both stay in sync.

### ⚙️ Stack & environment

| Layer | Choice | Why |
|---|---|---|
| **OS** | CachyOS (Linux 7.1, BORE scheduler) | Low-latency desktop tuned for local agent execution — no Docker-in-prod, no root-owned files, everything userspace |
| **Language** | Clojure / Babashka | Immutable data structures, pure functions, REPL-driven development. Scripts ship as single files (Babashka); libraries use the Clojure CLI |
| **Tooling** | mise, bb, clj, just | Version-pinned, declarative, zero "works on my machine" |
| **Git** | GitLab (primary) → GitHub (mirror) | CI on GitLab Pages, discoverability on GitHub |

### 🏛 Architecture philosophy

- **Immutable data, pure functions.** Prompts, configs, and state are Clojure values (maps, EDN). Transformations are pure functions. The only side-effects are at the system boundary — one HTTP call, one file write. ([See the demo](https://github.com/nurazhardotcom/llm-orchestration-clj))
- **Local-first.** User data stays on disk as EDN/JSON. No analytics, no cloud databases, no telemetry. Your machine is the server.
- **Deterministic outputs.** LLM calls use `temperature: 0` where reproducibility matters. Same input → same output.
- **Small tools, sharp tools.** Each repo does one thing (a scanner, a compliance toolkit, a protocol explorer). No monorepos, no frameworks.

### 🛠 Selected work

| Project | What it is | Stack |
|---|---|---|
| [`llm-orchestration-clj`](https://github.com/nurazhardotcom/llm-orchestration-clj) | Data-oriented LLM orchestration demo — prompts as values, pure transforms, one side-effect | Babashka, ~80 lines |
| [`headhunter-agent`](https://github.com/nurazhardotcom/headhunter-agent) | Local-first multi-agent system (MAS) for candidate profiling & interview prep — desktop GUI, no cloud | Clojure, cljfx |
| [`aur-audit`](https://github.com/nurazhardotcom/aur-audit) | Supply-chain security scanner for Arch AUR PKGBUILDs — detects backdoors & obfuscation | Babashka, static analysis |
| [`pdpa-sg-clj`](https://github.com/nurazhardotcom/pdpa-sg-clj) | 🇸🇬 Singapore PDPA compliance toolkit for AI agents — read README, tick checklist, done | Clojure, Babashka |
| [`bsv-clj`](https://github.com/nurazhardotcom/bsv-clj) | Toolkit for exploring Bitcoin's original v0.1 protocol — RPC client, wallet, block explorer | Clojure |
| [`nurazhar.com`](https://github.com/nurazhardotcom/nurazhar.com) | My blog & portfolio — essays on AI agents, Bitcoin, local-first software, security | [nurazhar.com](https://nurazhar.com) |

### 🧭 Focus areas
`AI agents` · `local-first software` · `privacy & compliance` · `supply-chain security` · `Bitcoin SV` · `functional programming`

### 📬 Contact
Site: [nurazhar.com](https://nurazhar.com) · Full portfolio & CI: [gitlab.com/nurazhar](https://gitlab.com/nurazhar)

