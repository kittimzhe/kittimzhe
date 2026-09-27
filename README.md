# Hi, I'm Mengzhe Gan 👋

> Full-Stack Engineer · AI Application Engineering · Agent Tooling  
> Building observable, auditable, and measurable infrastructure for production-grade AI agents.

I'm a software engineer with hands-on experience in **full-stack delivery** and **AI application engineering**. My career started in application software development and has grown into end-to-end engineering ownership across frontend, backend, system integration, and production delivery.

I currently focus on turning AI capabilities into real productivity systems for enterprise workflows — not just impressive demos, but systems that can be integrated, governed, evaluated, and operated over time.

> **Governance and operations separate production systems from experimental AI demos.**  
> **The depth of engineering determines how far AI value can be realized.**

---

## 🧭 About Me

I have worked on complex business systems as well as AI agent systems built from zero to one. Rather than treating AI applications as isolated model calls, I care about how they enter real workflows, connect with existing systems, respect permission boundaries, and remain understandable after execution.

My current work revolves around combining:

- LLM service integration and orchestration
- Knowledge bases and retrieval-augmented generation
- Tool calling and agent workflows
- Multi-turn session state management
- Permission models and security boundaries
- Session evidence, auditability, and postmortems
- Agent behavior evaluation and regression tracking
- Full-stack system integration and delivery

I’m especially interested in the engineering gap between "the agent worked once" and "the agent can be trusted as part of a production workflow."

---

## 🔧 What I Build

### AI Agent Tooling

Infrastructure around real agent sessions: recall, transcript export, evaluation, and regression tracking — so agent behavior can be searched, reviewed, compared, and improved.

### Enterprise AI Applications

AI systems for productivity scenarios such as office workflows, developer efficiency, operations support, and knowledge management, with attention to governance, observability, and operational control.

### Full-Stack Business Systems

End-to-end applications covering frontend interaction, backend services, data modeling, permission design, integration, deployment, and delivery documentation.

---

## 🧩 Featured Projects

### [`insightloom`](https://github.com/kittimzhe/insightloom)

> A self-hosted knowledge workbench with a visible multi-agent pipeline.

InsightLoom turns saved articles, papers, links, and notes into actionable knowledge. It uses a visible multi-agent workflow to classify, summarize, link, challenge, and assemble knowledge proposals, while keeping humans in control before anything is written to the knowledge base.

**Highlights**

- Provides a self-hosted personal knowledge workspace for articles, notes, papers, and links
- Uses a visible multi-agent pipeline: classifier, summarizer, linker, challenger, and assembler
- Keeps knowledge writes human-approved: agents create proposals, users approve before Markdown is persisted
- Stores knowledge as plain Markdown files, making it Obsidian-compatible and avoiding vendor lock-in
- Supports semantic search, RAG Q&A, browser capture, approval workflow, and daily knowledge digests

**Tech:** `Python` · `FastAPI` · `LangGraph` · `LLM` · `RAG` · `SQLite` · `JavaScript` · `HTML/CSS`

---

### [`dsh-session-export`](https://github.com/kittimzhe/dsh-session-export)

> Evidence-grade session transcript export for DeepSeek Harness.

A DeepSeek Harness plugin that exports agent sessions into human-readable HTML, Markdown, JSON, and archive formats. It focuses on auditability, reproducibility, and operational review.

**Highlights**

- Reads canonical session logs through `ctx.sessionQuery`, avoiding recorder drift
- Generates self-contained HTML reports with KPI cards, turn timelines, tool rankings, and error highlighting
- Supports Markdown, JSON, ZIP archives, SHA-256 manifests, and review bundles
- Provides masking and hash-based redaction for sensitive information
- Useful for debugging, postmortems, team review, and delivery evidence

**Tech:** `TypeScript` · `JavaScript` · `DeepSeek Harness` · `Plugin System` · `Session Query`

---

### [`dsh-session-recall`](https://github.com/kittimzhe/dsh-session-recall)

> Cross-session full-text recall for DeepSeek Harness agents.

A model-facing recall tool that allows agents to search their own past session transcripts, such as previous decisions, bugs, configurations, or project context.

**Highlights**

- Exposes a typed `recall` tool for model-facing session search
- Searches original transcript events instead of lossy LLM-generated memory summaries
- Uses persistent full-text indexing with CJK fallback support
- Provides explicit scope controls including cwd scoping, time filters, tool filters, and all-project policy
- Includes redaction and access-control options for safer retrieval

**Tech:** `TypeScript` · `SQLite FTS5` · `Agent Memory` · `Session Search` · `DeepSeek Harness`

---

### [`dsh-session-eval`](https://github.com/kittimzhe/dsh-session-eval)

> Retrospective evaluation for real DeepSeek Harness agent sessions.

A deterministic evaluation layer that grades sessions that already happened and compares performance across sessions, without benchmark authoring or LLM judges.

**Highlights**

- Produces reproducible grade cards from persisted session logs
- Measures reliability, re-ask signals, and tool-call load
- Supports `/eval`, `/eval-diff`, and `/eval-history`
- Helps detect regressions after prompt, model, plugin, or configuration changes
- Designed for real-world agent operations rather than synthetic benchmarks

**Tech:** `TypeScript` · `JavaScript` · `Agent Evaluation` · `Regression Tracking` · `DeepSeek Harness`

---

### [`dsh-plugin-authoring-guide`](https://github.com/kittimzhe/dsh-plugin-authoring-guide)

> A hands-on guide to building DeepSeek Harness plugins.

A practical authoring guide based on real plugin development experience, covering plugin structure, tool registration, command registration, configuration, debugging, and common pitfalls.

**Highlights**

- Built from real experience developing `dsh-session-export` and `dsh-session-recall`
- Covers the practical lifecycle of DeepSeek Harness plugin development
- Includes bilingual material for both English and Chinese readers
- Helps developers understand the DSH plugin ecosystem faster

**Tech:** `Documentation` · `DeepSeek Harness` · `Plugin Authoring` · `Developer Tooling`

---

## 🛠️ Tech Stack

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

### AI Engineering

![AI Agent](https://img.shields.io/badge/AI_Agent-Workflow-orange?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Knowledge_Base-blueviolet?style=flat-square)
![Tool Calling](https://img.shields.io/badge/Tool_Calling-Agentic_Workflow-4B5563?style=flat-square)
![LLM](https://img.shields.io/badge/LLM_Application-Engineering-111827?style=flat-square)

### Backend & Tooling

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### Full-Stack Delivery

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

## 🧠 Engineering Interests

- Making AI agent sessions searchable, reviewable, and auditable
- Turning agent behavior into evidence chains for debugging and postmortems
- Evaluating real-world agent quality with deterministic metrics
- Designing governance boundaries for enterprise AI applications
- Connecting models, tools, knowledge bases, and business systems into stable workflows
- Building engineering bridges from AI demos to production systems

---

## 📌 Current Focus

```text
Agent Memory
Session Evidence
Agent Evaluation
Developer Tooling
AI Application Engineering
Enterprise Productivity
Governance & Observability
```

---

## 📍 Selected Repositories

| Repository | Focus |
|---|---|
| [`insightloom`](https://github.com/kittimzhe/insightloom) | Self-hosted knowledge workbench with a visible multi-agent pipeline |
| [`dsh-session-export`](https://github.com/kittimzhe/dsh-session-export) | Evidence-grade transcript export for DeepSeek Harness sessions |
| [`dsh-session-recall`](https://github.com/kittimzhe/dsh-session-recall) | Cross-session recall and full-text search for agent memory |
| [`dsh-session-eval`](https://github.com/kittimzhe/dsh-session-eval) | Deterministic retrospective evaluation for real agent sessions |

---

## 🤝 Connect With Me

- GitHub: [github.com/kittimzhe](https://github.com/kittimzhe)
- Location: Beijing, China

---

## 🌱 Motto

> AI value is not only about generating answers.  
> It is about entering workflows, connecting systems, and supporting decisions.
