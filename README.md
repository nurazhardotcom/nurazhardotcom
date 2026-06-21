# 👋 Hi, I'm Nur Azhar

**IT Infrastructure & Security Engineer (7+ yr, Defence/Gov) | Clojure/BSV Protocol Engineering | Building AI Agent Infrastructure**

*Singapore Citizen | Available Aug 2026*

*Singapore | [career@nurazhar.com](mailto:career@nurazhar.com) | [linkedin.com/in/nur-azhar](https://linkedin.com/in/nur-azhar) | [blog.nurazhar.com](https://blog.nurazhar.com)*

---

## 🔐 Core Expertise (7+ Years, Defence/Government)

| Domain | Tools & Scope |
|---|---|
| **Privileged Access Management** | CyberArk PVWA/PSM — daily operations, password rotation, session recording, break-glass, 50+ vendor onboarding/offboarding |
| **Identity & Access (M365/Entra ID)** | Conditional Access, PIM, Entra ID Protection, Purview DLP, Cyber Trust Mark Tier 3, MFA (FIDO2/Passkeys) |
| **Endpoint Detection & Response** | Carbon Black EDR — daily monitoring, alert triage, false positive investigation, 4,000+ endpoints |
| **Vulnerability Management** | Tenable.sc / Tenable Nessus — scheduled scanning, remediation coordination, risk-based prioritization |
| **Data Security / Database Auditing** | IBM Guardium — Oracle DB activity monitoring, compliance reporting (Cat-2 air-gapped environment) |
| **Network & Infrastructure** | VMware, Active Directory, Fortinet firewall, NAS, MFT, patch management, SSL offloading |
| **Application Support / ERP** | Odoo ERP (SME/administrator, authored access governance SOP), Power Automate workflow automation, WordPress CMS |

**Clearance:** ICA Category-2 (Official Secrets Act) | HTX-monitored environment

---

## 🛠️ Technical Stack

**Primary Language:** Clojure 1.12, Babashka 1.4+

**Security & Identity:** CyberArk, Microsoft Entra ID, Purview, Carbon Black EDR, Tenable, IBM Guardium, RSA SecurID, FIDO2/Passkeys

**OS & Scripting:** Linux (Arch, CachyOS, Debian), Windows Server, PowerShell, Bash, Python

**Cloud & Infrastructure:** GCP Cloud Functions (Serverless), VMware, Docker, GitHub Actions, Cloudflare, Tailscale

**Databases:** PostgreSQL (Neon, RLS, triggers), MySQL, SQLite — normalization, audit logging, threshold batching

**Blockchain / Bitcoin:** BSV — RPC, UTXO, OP_RETURN, secp256k1, SPV, BRC-31/77/105, IPv6 CGA (RFC 3972/4982)

**Development:** Django, React, HTMX, Hiccup, cljfx (JavaFX desktop), HTML5/CSS3, JavaScript (ES6+)

---

## 📂 Featured Projects

### 🛡️ [aur-audit](https://github.com/nurazhardotcom/aur-audit)
**Supply chain security scanner for Arch PKGBUILDs** — detects backdoors, persistence hooks, obfuscation, piped execution, environment hijacking. Built in response to June 2026 AUR malicious package incident. Babashka CLI for CI/CD integration.
*Clojure, Babashka, static analysis, IoC detection*

### 🎵 [lagu-lagu](https://github.com/nurazhardotcom/lagu-lagu)
**Serverless royalty settlement engine (SG/SEA):** HTMX + GCP Cloud Functions + Neon Postgres (RLS, triggers) + Tazapay (PayNow/QRIS/GCash) + BSV notary. 80/20 split via DB triggers.
*Serverless, payments, data integrity, SEA fintech*

### ₿ [bsv-clj](https://github.com/nurazhardotcom/bsv-clj)
**Clojure toolkit for Bitcoin v0.1 (BSV)** — idiomatic JSON-RPC client, read-only wallet (UTXO queries, balance tracking), local web block explorer with dark-themed UI.
*Clojure, Bitcoin RPC, Ring/Compojure, Hiccup*

### 🧠 [headhunter-agent](https://github.com/nurazhardotcom/headhunter-agent)
**Local-first multi-agent desktop GUI** for deep candidate profiling and interview preparation. JavaFX interface, 100% local data storage, zero web stack.
*Clojure, cljfx (JavaFX), multi-agent orchestration, privacy-first*

### 🇸🇬 [pdpa-sg-clj](https://github.com/nurazhardotcom/pdpa-sg-clj)
**Singapore PDPA compliance toolkit for AI agents** — CLI and Clojure library covering all 11 PDPA obligations. PII/NRIC/secret scanner, redaction pipeline, policy template generator, local audit runner. Designed for AI agents to self-comply.
*Clojure, Babashka, PDPA, ripgrep, compliance automation*

### 📈 [bsv-de-tracker](https://github.com/nurazhardotcom/bsv-de-tracker)
**High-frequency BSV market data pipeline:** Clojure/Babashka + SQLite, CoinGecko API integration, zero external dependencies, automated cron scheduling. Originally Python, rewritten in Babashka — [blog post](https://blog.nurazhar.com/posts/python-to-babashka-etl-rewrite.html).
*Data engineering, Clojure, ETL, schema design*

---

### 🧪 More Projects

| Project | Description | Stage |
|---------|-------------|-------|
| [ipso-agent](https://github.com/nurazhardotcom/ipso-agent) | IPv6 CGA identity + BSV IP-to-IP micropayments for sovereign AI agents | Design phase |
| [agent-bond](https://github.com/nurazhardotcom/agent-bond) | Programmatic AI agent insurance on BSV — micropayment premiums, on-chain policies | Architecture defined |
| [paperclip-clj](https://github.com/nurazhardotcom/paperclip-clj) | Deterministic business kernel in Clojure — 5 layered modules, 33 tests | Early development |
| [bunker](https://github.com/nurazhardotcom/bunker) | Maritime bunkering automation with BSV-timestamped compliance records | Early architecture |
| [president-dao](https://github.com/nurazhardotcom/president-dao) | Swiss-model rotating AI presidency with quadratic voting and futarchy | Concept design |
| [bitcoin-wiki](https://github.com/nurazhardotcom/bitcoin-wiki) | Bitcoin v0.1 protocol specification wiki for LLM/agent retrieval | Published |
| [lithan-dev-sandbox](https://github.com/nurazhardotcom/lithan-dev-sandbox) | Zero-admin Windows DevEx automation (PowerShell + Babashka + winget) | Released |

---

## 📝 Technical Writing

[**blog.nurazhar.com**](https://blog.nurazhar.com) — **90+ posts** across 40+ categories (192 commits in 22 days).

| Theme | Sample Topics |
|-------|--------------|
| **Bitcoin / BSV Protocol** | v0.1 set in stone analysis, IPv6 integration architecture, BSV as restored Bitcoin, Hyperliquid comparison, decentralization paradox |
| **AI Cognition & Safety** | LLM vs human cognition, sycophancy loops, recursive self-improvement illusions, AGI skepticism, training data poisoning |
| **Clojure / Engineering** | Python-to-Babashka ETL rewrite, desktop GUI pivot, Hermes agent memory, paperclip deterministic engine, quickblog architecture |
| **Security / DevSecOps** | AUR incident analysis, PAM hardening, auth entropy collapse, EDR tuning, red-teaming AI pipelines |
| **Philosophy / Governance** | The Transition to LEV, President DAO, human bottleneck thesis, DAO of everything timeline |

---

## 📫 Contact & Verification

- **LinkedIn:** [linkedin.com/in/nur-azhar](https://linkedin.com/in/nur-azhar)
- **Email:** [career@nurazhar.com](mailto:career@nurazhar.com)
- **Blog:** [blog.nurazhar.com](https://blog.nurazhar.com)
- **H-1B1:** Eligible (Singapore Citizen under US-Singapore FTA)
