<h1 align="center">Nur Azhar</h1>
<p align="center"><strong>Identity & Security Systems Practitioner — IAM/PAM · Security Automation · Human, Workload & Agent Access</strong></p>

<p align="center">
  <a href="https://nurazhar.com"><img src="https://img.shields.io/badge/Website-nurazhar.com-005500?style=flat-square&logo=firefox" alt="Website" /></a>
  <a href="https://linkedin.com/in/nur-azhar"><img src="https://img.shields.io/badge/LinkedIn-Nur%20Azhar-0077B5?style=flat-square&logo=linkedin" alt="LinkedIn" /></a>
  <a href="https://gitlab.com/nurazhar"><img src="https://img.shields.io/badge/GitLab-nurazhar-FC6D26?style=flat-square&logo=gitlab" alt="GitLab" /></a>
  <a href="mailto:career@nurazhar.com"><img src="https://img.shields.io/badge/Email-career@nurazhar.com-D14836?style=flat-square&logo=gmail" alt="Email" /></a>
</p>

---

### 🛡️ About Me

**Identity and security systems practitioner** with **7+ years** of enterprise infrastructure, IAM/PAM, and security operations experience across government-sector critical environments (HTX/ICA, DCS, NEC). Delivered **CSA CyberTrust Mark certification (Promoter Tier)** as sole ISMS Lead — executed the consultant-designed ISMS internally across **7 Annex A control domains** — and operated enterprise **CyberArk PAM** vaults in production government environments.

**Current direction:** turning identity principles—authentication, authorization, privilege, delegation, and auditability—into deterministic automation. **Foundation:** **policy-as-code** (OPA/Rego gates enforcing IAM controls in CI), **zero-dependency compliance automation** (Babashka/Clojure, Python/Bash), **IAM/PAM operations** (CyberArk, Active Directory/Entra ID RBAC), and **CI/CD pipeline security**.

---

### 🔁 The Identity Control Loop

This portfolio is one deliberate progression—not unrelated projects:

```text
enterprise IAM/PAM experience
        → identity primitives
        → declarative Clojure/EDN policy
        → agent-gated execution
        → short-lived, scoped access
        → revocation and audit evidence
        → workload and AI-agent identity
```

The open-source code is the proof layer. Paid value comes from implementation, integration, deployment, policy design, support, and operating identity controls in real environments.

| Foundation | Direction |
|---|---|
| CyberArk PAM · Active Directory · Entra ID · regulated operations | Security automation · workload identity · non-human identity · AI-agent authorization |

### 🔬 Featured Open-Source Repositories

| Repository | Focus & Description |
|---|---|
| 🚦 [**`identity-policy-as-code`**](https://github.com/nurazhardotcom/identity-policy-as-code) | **OPA/Rego IAM Security Gate** — denies wildcard IAM permissions and inline policies over normalized Terraform-plan input. Dual-fixture verified (vulnerable denied / clean allowed), enforced by GitHub Actions on every push. |
| 🛡️ [**`security-tools`**](https://github.com/nurazhardotcom/security-tools) | **Zero-Dependency Compliance & IAM Automation Toolkit** — 6 assistants: vulnerability prioritiser, findings triage, IAM job matcher, access review summariser, policy-to-ticket generator, PAM request classifier. 50 tests, 175 assertions. |
| 🔒 [**`pdpa-sg-clj`**](https://github.com/nurazhardotcom/pdpa-sg-clj) | **Singapore PDPA Compliance CLI & CI/CD Scanner** — NRIC Mod-11 static scanning, PII redaction, 11-obligation checklist. Built for AI agents. |
| 🇸🇬 [**`mcpf-adapter`**](https://github.com/nurazhardotcom/mcpf-adapter) | **MyCareersFuture API Adapter** — zero-dependency CLI bridging Singapore MCF v2 APIs to structured job intelligence (JSONL/SQLite). |

---

### ✍️ Research & Writing

Sustained technical publishing at [**nurazhar.com**](https://nurazhar.com) — 200+ posts on systems architecture, agent-era security, and compliance pipelines.

| Essay | Focus |
|---|---|
| 🚦 [**Replacing Imperative Scan Code with Rego**](https://nurazhar.com/rego-replaces-clojure-iam.html) | Migrating IAM validation from custom scripts to declarative OPA policies |
| 🧠 [**Cognitive Asymmetry: The Epistemic Bandwidth Bottleneck**](https://nurazhar.com/cognitive-asymmetry-epistemic-bandwidth.html) | Why abstraction capacity — not hardware access — defines the agent era divide |
| 🛡️ [**Agentic AI Security**](https://nurazhar.com/agentic-ai-security.html) | Trust boundaries, tool integrity, and contained execution for autonomous systems |

The site is fully LLM-readable ([`llms.txt`](https://nurazhar.com/llms.txt), [`llms-full.txt`](https://nurazhar.com/llms-full.txt)).

---

### ⚙️ Core Technical Capabilities

- **Identity & Access Management (IAM/PAM):** CyberArk PAM Vaulting, Session Recording, Active Directory & Entra ID, Least-Privilege RBAC.
- **Policy-as-Code & Pipeline Security:** OPA/Rego deny-set policies validating Terraform-plan IAM output; GitHub Actions security gates; GitLab CI integration.
- **Security Compliance & Frameworks:** ISO 27001 Annex A ISMS Delivery, CSA CyberTrust Mark Promoter Tier, IBM Guardium DAM, Carbon Black EDR, Tenable Nessus.
- **Developer Tooling:** Zero-dependency CLI scanners (Babashka/Clojure, Python/Bash), ripgrep-backed static analysis, REST/gRPC.

---

