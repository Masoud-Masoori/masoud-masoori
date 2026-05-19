<div align="center">

<a href="https://daena.mas-ai.co">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3500&pause=900&color=D4A843&center=true&vCenter=true&width=820&height=46&lines=Governance-First+AI+for+a+Safer+Agent+Era;Architect+of+Daena+%E2%80%94+10+Stages%2C+60+Agents%2C+10+Departments;AI+Safety+%E2%80%A2+Agentic+Systems+%E2%80%A2+Adversarial+Robustness;2+USPTO+Provisionals+%E2%80%A2+Google+for+Startups+'26" alt="Headline" />
</a>

# Masoud Masoori

**AI Safety & Security Researcher · Agentic AI Architect**
**Founder & CEO — [MAS-AI Technologies Inc.](https://mas-ai.co)** *(incorporated Ontario, Jan 2026)*

Building **[Daena](https://daena.mas-ai.co)** — the governance layer for autonomous AI agents.
Researching adversarial robustness in open-source agent ecosystems (OpenClaw, NVIDIA NemoClaw).

📍 Richmond Hill, Ontario, Canada

[![Website](https://img.shields.io/badge/mas--ai.co-0F1419?style=for-the-badge&logo=safari&logoColor=D4A843)](https://mas-ai.co)
[![Daena](https://img.shields.io/badge/daena.mas--ai.co-0F1419?style=for-the-badge&logo=spring&logoColor=2DD4BF)](https://daena.mas-ai.co)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/masoud-masoori/)
[![X](https://img.shields.io/badge/X%20%2F%20Twitter-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/masoud_masoori)
[![Email](https://img.shields.io/badge/Contact-D4A843?style=for-the-badge&logo=protonmail&logoColor=0F1419)](mailto:masoud.masoori@mas-ai.co)
[![GitHub Org](https://img.shields.io/badge/MAS--AI--Official-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mas-AI-Official)

</div>

---

## 🛡️ Mission

> **Reduce catastrophic risk from advanced AI by making autonomous agents safe, interpretable, and steerable — at production scale, not in slideware.**

Most agent platforms ship hot-path LLM calls with no immutable guardrails. Daena inverts that: **every agent action passes through a 10-stage deterministic pipeline** — SecurityGate → LoadSession → QueryUnderstanding → GovernanceCheck → CostPreflight → ModelRouter → MemoryRecall → BuildRequest → LLMStream → Persist + Audit — Merkle-notarized end-to-end. Governance is enforced by **three always-on layers**:

- **Shield** — prompt-injection scanner, behavior guard, tenant isolation at DB-middleware level
- **Security** — SecurityGate, tool-call classifier, loop detector, async approval manager
- **Asset Shield** *(NEW in v3.7.0)* — AES-GCM vault adapter + egress filter + consent tokens + initiator-aware tier collapse, protecting api_keys / finance / identity / legal / founder_memory from exfiltration regardless of which agent initiates

Modes are user-controlled: **UNLEASHED** (Shield only) → **BALANCED** (light gates) → **GOVERNED** (full 9-law enforcement).

---

## 🆕 What Shipped Recently (Apr–May 2026)

| Date | Ship |
|:---|:---|
| **2026-05-08** | **Task Control Registry & Dashboard** — central `registry.yaml` + web UI at `127.0.0.1:8450` to register, enable/disable, and audit every cron task, Windows Scheduled Task, and daemon across 30+ MAS-AI projects. Replaces 4+ CMD-window-flashing background jobs with hidden PowerShell wrappers. |
| **2026-05-04** | **Token Discipline Protocol** — formal output-bloat governance for AI orchestrators: terse-by-default, narrow reads, no gratuitous sub-agent fan-out, delegate mechanical work to local GGUF models on a 4060. ~3× cost reduction per typical engineering day. |
| **2026-04-29** | **ADR-001: Honesty + Persistence + Visibility** — no silent error suppression, no demo-data fallbacks, in-memory registries must hydrate from DB on startup, no auto-retry of destructive operations across restart. Locked across the Daena UI + backend. |
| **2026-04-26** | **Cross-AI Delegation Protocol** — formal Claude Code ↔ Codex CLI hand-off table grounded in SWE-Bench Pro / Terminal-Bench 2.0; Port Registry; Organize-by-Umbrella file taxonomy. |
| **2026-04-25** | **Three-Tier Escalation Router** + **Mixture-of-Agents + Karpathy 3-Stage Council** — gate Council/Quintessence by query complexity + risk (arXiv 2604.02460); anonymized peer review with chairman synthesis (Together-AI MoA, arXiv 2406.04692). |
| **2026-04-21** | **Daena v3.7.1-production-lock-in** — 58 new unit tests closing zero-coverage gaps on `governance_engine`, `audit_service`, and `cognitive_scan_engine`. DB integrity confirmed clean. |
| **2026-04-19** | **Daena v3.7.0-security-supercharge** — Asset Shield always-on; `SECURITY_SCAN` intent with 8-kind target detection (URL/domain/IP/CIDR/host:port/APK/IPA/AAB/Android pkg/git repo); 6-channel intel fanout (Web + NVD + GitHub Advisories + codebase-memory + NBMF T3 + KG); zero-FP gate; BeyondMythos enrichment (ErrorOracle, AdversarialSimulator, CompositionalPlanner). |
| **2026-04-20** | **Local LLM runtime swap** — Ollama → `llama.cpp llama-server`; `LlamaServerManager` with mutex-locked hot-swap, cooldown thrash suppression, and `respect_external` mode that refuses to kill an MCP-bridge-owned process. |

---

## 📊 Daena at a Glance

<div align="center">

| Dimension | Status |
|:---|:---|
| 🧪 **Test Suite** | **3,086 / 3,086 backend tests passing** *(verified 2026-04-18)* · 0 TypeScript errors · 6/6 Playwright E2E |
| 🤖 **Agent Fleet** | **10 unified agents × 6 capabilities** (MIND · EYES · HANDS · VOICE · SHIELD · MEMORY) across **10 departments**, including Security Operations as Department 10 |
| 🧠 **LLM Routing** | **9 providers**: Ollama (local llama.cpp) · Anthropic · OpenAI · Gemini · Groq · OpenRouter · Together.ai · Perplexity · Azure OpenAI |
| 🛡️ **Governance Layers** | **3 always-on**: Shield + Security + Asset Shield · **3 modes**: UNLEASHED / BALANCED / GOVERNED |
| 🧠 **Reasoning Modes** | **Standard** (single mind) · **Council** (3-model parallel) · **Quintessence** (Council + 15 DCP expert lenses + Karpathy anonymized peer review) |
| 📜 **Patents Filed** | **2 USPTO Provisionals** — PhiLattice (#63/877,082, 25 claims) + NBMF stack (#64/020,421, 14 claims) |
| ⚡ **Token Efficiency** | **87.5% overhead reduction** per session via Tool Lifecycle Manager (NBMF) |
| 🧬 **Memory Architecture** | **NBMF — 5 tiers**: T0 Ephemeral (1hr) → T1 Working (7d) → T2 Project (1yr) → T3 Institutional (founder-approved) → T4 Founder-Private. Hallucinations auto-expire; only verified knowledge persists. |
| 🏆 **Programs** | **Google for Startups** (Accepted '26) · **Consensus Hong Kong 2026** Developer Pass |
| 💰 **Business Model** | BYOK with **75–82% gross margins** · FREE (Ollama local) / PRO ($29–99/mo) / ENTERPRISE ($500+/mo) |

</div>

---

## 🏗️ Architecture Snapshot

```mermaid
flowchart LR
    U([User / Agent Caller]) --> SG[🛡️ SecurityGate<br/>+ Asset Shield egress]
    SG --> LS[LoadSession]
    LS --> QU[QueryUnderstanding<br/>intent · complexity · risk]
    QU --> GC[GovernanceCheck<br/>9 immutable laws]
    GC --> CP[CostPreflight]
    CP --> MR[ModelRouter<br/>tag · locality · cost · ctx]
    MR --> MC[MemoryRecall<br/>NBMF T0–T4]
    MC --> BR[BuildRequest]
    BR --> RC[ReasoningCore<br/>Standard / Council / Quintessence]
    RC --> LS2[LLMStream<br/>SSE chunks]
    LS2 --> PA[(Persist + AuditLog<br/>Merkle-notarized)]
    PA --> R([Response])

    style SG fill:#D4A843,stroke:#0F1419,color:#0F1419
    style GC fill:#2DD4BF,stroke:#0F1419,color:#0F1419
    style RC fill:#6C3AFF,stroke:#0F1419,color:#FFFFFF
    style PA fill:#0F1419,stroke:#D4A843,color:#D4A843
```

**Three reasoning modes**, gated by a complexity + risk router (arXiv 2604.02460):
- **Standard** — single primary mind with extended thinking. Default for SIMPLE / MODERATE queries.
- **Council** — 3-model parallel proposers + anonymized Karpathy-style peer review + chairman synthesis. Promoted on COMPLEX / MULTI_STEP / HIGH_RISK.
- **Quintessence** — Council + 15 DCP expert-lens injection across Engineering / Product / Design.

**EXE mode** adds DaenaBot tool dispatch (FileAgent · TerminalAgent · BrowserAgent · MCPAgent) between BuildRequest and LLMStream, gated by per-tool Allow / Ask / Block permissions.

---

## 📜 Intellectual Property — USPTO Provisionals Filed

<table>
<tr>
<td width="50%">

### 🌻 PhiLattice Architecture
**(Sunflower-Honeycomb)**

`USPTO Provisional #63/877,082`
`Confirmation #1142 · Filed Sept 2025`

Fibonacci-derived hexagonal topology for scalable agent placement. Golden-angle spacing produces optimal information flow + ABAC governance tiers + consensus learning + Merkle-notarized audit lineage.

**25 claims · 11 figures · 1,112 reference numerals**

</td>
<td width="50%">

### 🧬 NBMF + TLM + eDNA + Dream Engine
**(Neural-Backed Memory Fabric stack)**

`USPTO Provisional #64/020,421`
`Confirmation #7683 · Filed March 2026`

5-tier neural-backed memory fabric · 87.5% token-reduction Tool Lifecycle Manager · Experience DNA with tamper-evident Merkle lineage · autonomous 6-phase Dream Engine consolidation.

**14 claims · 20 figures**

</td>
</tr>
</table>

---

## 🚀 Projects & Inventions

### Flagship

<table>
<tr>
<td width="33%" align="center">

#### [🛡️ Daena](https://github.com/Mas-AI-Official/daena)
**Governed AI Orchestration Platform**
10-stage pipeline · 10 depts × 60 capabilities
**3,086 tests** · **v3.7.1**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

</td>
<td width="33%" align="center">

#### [🔀 MergeLoop](https://github.com/Mas-AI-Official/MergeLoop)
**Host-Agnostic Model Council**
Run multi-model synthesis across MCP, CLI & API workers
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

</td>
<td width="33%" align="center">

#### [🧠 Vibe Agent](https://github.com/Mas-AI-Official/vibe-agent)
**Visual Agent Builder**
Vibe-code your agent → see the blueprint → deploy
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

</td>
</tr>
</table>

### Research & Security

<table>
<tr>
<td width="50%">

#### [🔍 Klyntar](https://github.com/Mas-AI-Official/klyntar)
Security-AI vulnerability finder. Open-source agent-ecosystem safety research applied to OpenClaw (247K+ stars) and NVIDIA NemoClaw — prompt injection, skill-registry poisoning, credential exposure, unvetted skill execution.
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

</td>
<td width="50%">

#### [⚖️ CaseWright](https://github.com/Masoud-Masoori/casewright)
AI paralegal for Canadian administrative tribunals. Wedge: Ontario Landlord & Tenant Board. Governed legal-document drafting on top of Daena.
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
</table>

### Applications Built on Daena

| Project | What it does | Stack |
|---|---|---|
| [🎬 ContentOps Core](https://github.com/Mas-AI-Official/contentops-core) | Autonomous multi-platform, multi-niche content engine — scrape → generate → schedule → publish | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JS](https://img.shields.io/badge/-JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [🌐 ContentOps Web](https://github.com/Mas-AI-Official/contentops-web) | Approval-queue dashboard for ContentOps drafts and rejections | ![JS](https://img.shields.io/badge/-JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [💻 Daena Coder](https://github.com/Mas-AI-Official/Daena-Coder) | Free multi-LLM local swarm — governed code assistance with security-aware output validation | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| [🎥 LingoVids](https://github.com/Mas-AI-Official/lingovids) | AI video translator under the MAS-AI portfolio | ![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| [🩺 MedScan](https://github.com/Masoud-Masoori/MedScan) | Medical scanner & prescription-reminder system | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| [🌿 NatureNLP](https://naturenlp.mas-ai.co) | Nature-inspired NLP — ~2.4× token throughput, 35% lower perplexity vs GPT-2 baseline | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| [🤖 AI Autonomous Company OS](https://github.com/Mas-AI-Official/AI-Autonomus-company-OS) | AI-native company operating system | *In development* |
| [💼 Daena Auto-Apply](https://github.com/Mas-AI-Official/daena-auto-apply) | Apply for jobs with AI + local LLMs automatically | ![JS](https://img.shields.io/badge/-JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| 🎯 **Career OPS** | AI job search command center — evaluate offers, generate CVs, scan portals, track applications | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| 📊 **WorldSignal** | Trading intelligence + scenario engine — deterministic live path, sparse-simulation background research, three-path architecture (live/warm/background) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| 🎲 **Poly Bet** | Prediction-market discovery + arbitrage scanner over Polymarket-style venues | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| 🛰️ **KYA / Mission Control** | Know-Your-Agent telemetry + mission-control dashboard for agent fleets in production | ![JS](https://img.shields.io/badge/-JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| 🗓️ **Task Control** | Central registry + web dashboard for every cron task, scheduled job, and daemon across 30+ MAS-AI projects. Replaces CMD-flashing background jobs with hidden, auditable schedules. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| 🧬 **NBMF / Daena-Mind** | Tier-mapped memory vault (T0–T4) with Obsidian compatibility; founder-private tier; hallucination auto-expiry | ![Markdown](https://img.shields.io/badge/-Markdown-000000?style=flat-square&logo=markdown&logoColor=white) |
| 🛠️ **GitNexus** | Code-intelligence graph indexed over Daena (24,541 symbols · 63,085 relationships · 300 execution flows) for impact analysis and safe refactor | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| 🏗️ **Construction AI** | Civil-engineering domain port: governed estimation + risk analysis on Daena | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |

### Demos & Showcases

| Demo | Audience |
|---|---|
| [🪙 Daena DeFi Demo](https://github.com/Mas-AI-Official/hackathon_demo) | Hackathon — Daena governance applied to DeFi |
| [🎤 Daena Live Demo](https://github.com/Mas-AI-Official/Daena-live-demo) | Investors & partners — interactive walkthrough |
| [🌐 MAS-AI Site](https://github.com/Mas-AI-Official/Mas-AI-Official) | Company website |
| [📈 Daena Investor Site](https://github.com/Mas-AI-Official/Daena-website) | Daena product landing page |

---

## 💼 Three Ways to Engage

<table>
<tr>
<td width="33%" align="center">

#### 🛠️ Product
**Self-Serve SaaS**
[daena.mas-ai.co](https://daena.mas-ai.co)

Governed multi-agent orchestration with FREE / PRO / ENTERPRISE tiers. Hosted, tenant-isolated, audit-logged. Sign in with Google or email.

</td>
<td width="33%" align="center">

#### ⚙️ Automation
**Done-With-You**
[mas-ai.co](https://mas-ai.co)

Integrate your existing job, workflow, or department with Daena agents and external LLMs. Auto-triage tickets, auto-run weekly reviews, auto-scan staging, auto-research competitors. Ships running with playbook + SOP.

</td>
<td width="33%" align="center">

#### 🧭 Consulting
**Done-For-You Strategic**
[mas-ai.co/consulting](https://mas-ai.co/book)

AI-readiness audits, governance design, agent architecture for regulated industries. Built on the patent stack (PhiLattice + NBMF). Retainer model.

</td>
</tr>
</table>

---

## 🧰 Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/-Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**AI / Agentic**

![Anthropic](https://img.shields.io/badge/-Anthropic_Claude-D4A574?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI_GPT-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/-Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![DeepSeek](https://img.shields.io/badge/-DeepSeek-0A0A0A?style=for-the-badge)
![Qwen](https://img.shields.io/badge/-Qwen-6C3AFF?style=for-the-badge)
![MCP](https://img.shields.io/badge/-Model_Context_Protocol-2DD4BF?style=for-the-badge)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)

**Backend & Data**

![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-D71F00?style=for-the-badge)
![WebSockets](https://img.shields.io/badge/-WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/-React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer](https://img.shields.io/badge/-Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

**Cloud & Infrastructure**

![Azure](https://img.shields.io/badge/-Azure_OpenAI-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/-Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

**Security & Governance**

![OAuth](https://img.shields.io/badge/-OAuth_2.0-3C4858?style=for-the-badge&logo=auth0&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Merkle](https://img.shields.io/badge/-Merkle_Audit-D4A843?style=for-the-badge)
![RBAC%2FABAC](https://img.shields.io/badge/-RBAC%2FABAC-2DD4BF?style=for-the-badge)

</div>

---

## 🔬 Research Interests

- **AI safety & alignment** in multi-agent systems
- **Adversarial robustness** + prompt-injection defense in agentic architectures
- **Hallucination detection, containment, auto-expiry** (NBMF trust-gated promotion)
- **Tamper-evident lineage** for AI decision tracking (eDNA + Merkle)
- **Scalable oversight** of LLM-powered agent fleets (9-law immutable governance)
- **Memory safety** + trust-gated information flow in AI systems
- **Open-source agent safety** research on OpenClaw / NVIDIA NemoClaw ecosystems
- **AI-driven cybersecurity** — autonomous threat detection, anomaly classification

---

## 🎓 Background

| | |
|:---|:---|
| 🎓 **Graduate Certificate · Artificial Intelligence (AIG)** | Seneca College, Toronto, ON · 2025 |
| 🎓 **M.Sc. Civil Engineering — Transportation** | Tehran, Iran · 2020 |
| 🎓 **Professional Certificate · Computer Systems Technology** | Tehran College · 2020 |
| 🏅 **Anthropic Academy** | Claude API Fundamentals · MCP · Claude Code · AI Fluency *(2025–26)* |
| ☁️ **AWS Cloud Practitioner** | Cloud + Security · 2025 |
| 🛡️ **Cisco** | Introduction to Cybersecurity · 2024 |
| 🐍 **University of Michigan** | Python for Everybody · Programming for Everybody *(2024)* |

Civil-engineering origin → robotics (ROS1/ROS2, Gazebo, JetAuto) → deep learning (CNNs, ResNet-18, CIFAR-10) → full-stack → governed agentic systems. Built Daena solo from architecture through **3,086 passing tests** (v3.7.1-production-lock-in), 2 USPTO patent filings, and 25+ public repos across the [MAS-AI org](https://github.com/Mas-AI-Official). Daily operator across ~30 projects under `D:\Ideas\` — orchestrated by Claude Code + Codex CLI through a formal cross-AI delegation protocol.

---

## 🔗 Connect

<table>
<tr>
<td>

**Company**
[mas-ai.co](https://mas-ai.co)

</td>
<td>

**Product**
[daena.mas-ai.co](https://daena.mas-ai.co)

</td>
<td>

**Org**
[github.com/Mas-AI-Official](https://github.com/Mas-AI-Official)

</td>
</tr>
<tr>
<td>

**LinkedIn**
[masoud-masoori](https://www.linkedin.com/in/masoud-masoori/)

</td>
<td>

**X / Twitter**
[@masoud_masoori](https://x.com/masoud_masoori)

</td>
<td>

**Email**
[masoud.masoori@mas-ai.co](mailto:masoud.masoori@mas-ai.co)

</td>
</tr>
</table>

---

<div align="center">

### 📈 GitHub Activity

<a href="https://github.com/Masoud-Masoori">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Masoud-Masoori&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&icon_color=D4A843&title_color=2DD4BF&text_color=FFFFFF&bg_color=0F1419" alt="GitHub Stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Masoud-Masoori&layout=compact&theme=github_dark&hide_border=true&title_color=2DD4BF&text_color=FFFFFF&bg_color=0F1419&langs_count=8" alt="Top Languages" />
</a>

<a href="https://github.com/Masoud-Masoori">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Masoud-Masoori&theme=dark&hide_border=true&background=0F1419&stroke=D4A843&ring=2DD4BF&fire=D4A843&currStreakLabel=2DD4BF" alt="Streak" />
</a>

<a href="https://github.com/Mas-AI-Official">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Masoud-Masoori&bg_color=0F1419&color=2DD4BF&line=D4A843&point=FFFFFF&area=true&hide_border=true" alt="Activity Graph" />
</a>

<br/>

**`2,038+ contributions in the last 12 months`** · **`25+ public repos shipped`** · **`30+ active projects under D:\Ideas`**
**Currently shipping** — v3.7.1 production lock-in · Task Control registry · Asset Shield · Cross-AI delegation

<img src="https://komarev.com/ghpvc/?username=Masoud-Masoori&color=D4A843&style=for-the-badge&label=Profile+Views" alt="Profile Views" />

---

> *"Make AI systems safe, interpretable, and steerable — at the speed of execution, not at the speed of approval queues."*
> — **Masoud Masoori**, MAS-AI Technologies Inc.

</div>
