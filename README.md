# Nur Azhar

> Turning myself into my own tools to achieve my own compute.
> Same shape as an Emacs user building their `.emacs` over decades;
> different substrate.

## Currently: Butler

A Hermes-class personal AI agent, self-hosted, in Clojure on Babashka.
Single binary, ~2 ms startup, one user, one machine, single audit trail.

- Multi-provider LLM router with priority + failover
- Tool registry validated by `clojure.spec` at every boundary
- SQLite FTS5 memory via Python bridge
- 3-tier prompt assembly (stable / context / volatile)
- Skills as procedural memory (EDN + auto-evolution)
- Sub-agent delegation by spawning more `bb` processes

Read the build log: [blog.nurazhar.com — *Building an AI Butler*](https://blog.nurazhar.com/building-an-ai-butler.html).

```text
 ┌─ CLI ─┐
 ├─ REPL ┤
 ├─ Web ─┼──▶  Agent loop ──▶  LLM router ──▶  Naraya / OpenRouter / Ollama
 └─ TG  ─┘   (multi-step)        (failover)            │
                          │                        (network)
                          ▼
                  ┌─────────────────┐
                  │ Tools │ Skills  │
                  │ Mem (FTS5)      │
                  └─────────────────┘
```

Butler is the flagship of a larger idea I call **compute sovereignty**:
not "AI as SaaS I rent," but AI as something I author, ship, and run on
my own hardware, with my own rules and my own audit trail.

## Why Lisp

The Emacs tradition: spend decades configuring your editor because the
editor *is* your cognition. I'm doing the same with my AI, except the
medium is Clojure instead of Elisp, and the substrate is a single
binary running on a $5 VPS instead of a 30-year-old text editor.

The reasoning behind the choice:

| Property | What it buys you |
|---|---|
| Clojure (data as code) | Skills, configs, prompts, EDN. Same shape. |
| Babashka (no JVM) | 2 ms cold start; sub-agent fan-out is cheap. |
| `clojure.spec` | Every module boundary is verified. Without types. |
| Single binary | Distribution shape matches a CLI utility, not a SaaS. |
| SQLite FTS5 | Local-first, portable, queryable. |

The negative space I optimise for: no YAML rule files, no JSON tool
schemas scattered across configs, no SaaS lock-in. The repo is small.
The composability is dense.

## Selected work

| Repo | Domain |
|---|---|
| [**butler**](https://github.com/nurazhardotcom/butler) | Hermes-class personal AI agent, Clojure/Babashka |
| [**bsv-clj**](https://github.com/nurazhardotcom/bsv-clj) | Bitcoin SV RPC client + tooling |
| [**pdpa-sg-clj**](https://github.com/nurazhardotcom/pdpa-sg-clj) | Singapore PDPA compliance toolkit |
| [**aur-audit**](https://github.com/nurazhardotcom/aur-audit) | Supply-chain scanner for AUR packages |
| [**headhunter-agent**](https://github.com/nurazhardotcom/headhunter-agent) | Desktop GUI Clojure app |
| [**blog.nurazhar.com**](https://blog.nurazhar.com) | 90+ posts: protocols, agents, security, Clojure |

## Stack

- **Runtime:** Babashka 1.4 (GraalVM native image, single binary)
- **Language:** Clojure (~95% of the language surface)
- **Persistence:** SQLite FTS5, Python bridge for what Babashka lacks
- **HTTP:** `httpkit`, `babashka.http-client`, `cheshire`
- **Validation:** `clojure.spec` at every public function boundary
- **Diagrams:** d2 (the only diagram syntax I trust an LLM near)

## Where I'm pushing next

The next thing I'm shipping in Butler is the **stateless persistence
fix**: a daily EDN bundle that pins yesterday's volatile tier into
today's prompt, plus an eval harness so auto-evolution can run
unattended without skills regressing. Both are documented in the
post-mortem above.

After that, the discipline problems come back: don't add tools the
daily routine hasn't earned; don't add verticals until the existing
ones are mature. Hardest part is not the code.

## Contact

- GitHub: [@nurazhardotcom](https://github.com/nurazhardotcom)
- Blog: [blog.nurazhar.com](https://blog.nurazhar.com)
- Project flagged right now: [butler](https://github.com/nurazhardotcom/butler)
