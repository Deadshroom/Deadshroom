# Brendon Hurst | `"Deadshroom"`

**AI & Automation Engineer | MCP · Agentic Systems · Workflow Architecture**

I build automation and AI systems to understand how the pieces actually work together — models, tools, APIs, workflows, infrastructure, state, evidence, and the humans using them.

This GitHub is where I keep the evidence.

## Featured Work

### 🛡️ HALON
Portable Windows troubleshooting and evidence-analysis system designed to reconstruct what happened on a machine before attempting to explain why.

HALON collects, normalizes, and correlates Windows telemetry into structured evidence that can later be consumed by a reasoning layer.

Current capabilities include:

- Windows Event Log collection and chronology reconstruction
- Process inventory and parent/child lineage mapping
- Identity and logon-session reconstruction
- Process-to-session and process-to-logon correlation
- Canonical JSON evidence artifacts
- Historical evidence repackaging through a Python pipeline
- Controlled failure validation using known process crashes
- Portable PowerShell-based endpoint collection
- Architecture designed for local/offline reasoning

The project separates **evidence gathering from reasoning**:

`Evidence → Knowledge → Reasoning`

The goal is not to ask an LLM to guess what happened from raw logs. HALON first builds a defensible chain of evidence, then gives the reasoning layer structured facts to work from.

> Observability tells you what the system reported. HALON is an experiment in reconstructing what actually happened.

**[Repository](https://github.com/Deadshroom/HALON)**

---

### 🧠 JobOS
AI-driven job search and application orchestration system.

- Playwright job discovery
- Resume parsing and candidate profiling
- Local LLM integration with Ollama
- Job qualification and S–F ranking
- FastAPI + SQLite backend
- Interactive web dashboard
- Planned application, Gmail, and Calendar orchestration

**[Live Demo](https://deadshroom.github.io/jobos/)** · **[Repository](https://github.com/Deadshroom/jobos)**

---

### 🔌 MCP Chat
Work-in-progress Model Context Protocol client/server application exploring:

- MCP tools, resources, and prompts
- Claude integration
- Multi-server MCP clients
- Dynamic tool discovery and routing
- LLM → tool → result → LLM orchestration

**[Repository](https://github.com/Deadshroom/mcp-chat)**

---

### ⚙️ n8n Automation Lab
Hands-on workflow implementations covering:

- REST APIs and webhooks
- Data transformation and routing
- Sub-workflows and persistence
- Error handling
- AI agents and tool-enabled workflows
- Structured LLM outputs

**[Repository](https://github.com/Deadshroom/n8n-automation-lab)**

## Current Focus

AI engineering, agentic systems, MCP, workflow orchestration, RAG, local AI, observability, evidence-driven troubleshooting, and building systems that connect models to real-world capabilities.

> **Don’t just say I understand it. Build something that proves it.**
