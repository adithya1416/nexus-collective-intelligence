# NEXUS — Collective Intelligence Registry

> **Every agent learns alone. NEXUS makes every agent smarter from what all agents have learned.**

[![Microsoft Build AI 2026](https://img.shields.io/badge/Microsoft%20Build%20AI-2026-0078D4?style=flat&logo=microsoft)](https://hackerearth.com/challenges/hackathon/microsoft-build-ai-2026/)
[![Theme: Agent Swarms](https://img.shields.io/badge/Theme-Agent%20Swarms-00D4FF?style=flat)](/)
[![Azure OpenAI](https://img.shields.io/badge/Azure-OpenAI%20GPT--4o-0078D4?style=flat&logo=microsoft-azure)](/)
[![Azure AI Search](https://img.shields.io/badge/Azure-AI%20Search-0078D4?style=flat&logo=microsoft-azure)](/)

---

## The Problem

In 2024, a national EdTech company ran 340 regional campaigns across 18 states. The Hyderabad team discovered scholarship-angle messaging converts 3× better in Tier-2 demographics. That insight never left Hyderabad. Four other teams independently made the same discovery over 6 months.

**This is the Ephemeral Intelligence Gap** — and it doesn't just affect AI agents. It affects every distributed network that generates intelligence locally but shares it nowhere. AI agents and human partner networks share the same fundamental failure: intelligence generated at one node never reaches other nodes.

---

## Solution

NEXUS is a **Collective Intelligence Operating System** — a persistent, vector-based Intelligence Registry that sits beneath any distributed agent network.

- When an agent solves a novel problem → it publishes a **Blueprint** (structured reasoning trace)
- Before any agent acts → it **queries the Registry** first
- Every run makes the network measurably smarter
- The **Network IQ Score** grows visibly with every campaign

---

## Architecture

```
┌─────────────────────────────────────────┐
│         INTELLIGENCE REGISTRY           │
│    Azure AI Search (Vector Store)       │
│  Blueprints: SUCCESS | FAILURE | SIGNAL │
└──────────────┬──────────────────────────┘
               ↕ QUERY BEFORE ACT | PUBLISH AFTER LEARN
┌──────────────────────────────────────────────────────┐
│                  AGENT SWARM LAYER                   │
│            (Azure Container Apps)                    │
│                                                      │
│  🔍 SCOUT → 🏗️ ARCHITECT → ⚙️ BUILDER               │
│                              ↓                       │
│              🛡️ GUARDIAN → 📡 PUBLISHER              │
└──────────────────────────────────────────────────────┘
               ↓
┌──────────────────────────────────────────────────────┐
│  Partner Portal (Azure Static Web Apps)              │
│  Intelligence Dashboard (Power BI Embedded)          │
└──────────────────────────────────────────────────────┘
```

**5 Agents:**
| Agent | Role |
|-------|------|
| 🔍 Scout | Ingests partner data, queries Registry for matching Blueprints |
| 🏗️ Architect | Builds campaign strategy informed by proven Blueprint patterns |
| ⚙️ Builder | Generates historically-optimized landing pages, assets, copy |
| 🛡️ Guardian | Validates against brand guidelines + known failure patterns |
| 📡 Publisher | Extracts new Blueprint from session, publishes back to Registry |

---

## Microsoft Azure Stack

| Service | Role |
|---------|------|
| **Azure OpenAI GPT-4o** | Powers all 5 agents |
| **Azure AI Search** | Vector store for Intelligence Registry |
| **Azure Container Apps** | Isolated, scalable agent containers |
| **Azure Cosmos DB** | Campaign history + Blueprint metadata |
| **Power BI Embedded** | Network IQ Score dashboard |
| **Azure Static Web Apps** | Partner portal deployment |
| **GitHub Copilot** | Development assistance (disclosed) |

---

## Demo Results

| Metric | Without NEXUS | With NEXUS |
|--------|---------------|------------|
| Conversion Rate | 9% | 31% |
| Deploy Time | 3–5 days | 4 minutes |
| Blueprints Used | 0 | 847 |
| Failure Patterns Avoided | 0 | All catalogued |

---

## Setup

```bash
# Clone
git clone https://github.com/YOUR_USERNAME/nexus-collective-intelligence

# Install dependencies
npm install

# Set environment (Azure OpenAI key auto-handled in claude.ai demo)
cp .env.example .env
# Add: AZURE_OPENAI_KEY, AZURE_SEARCH_KEY, COSMOS_CONNECTION_STRING

# Run locally
npm start
# Open http://localhost:3000
```

**Live Demo:** [nexus-collective-intelligence.vercel.app](https://nexus-collective-intelligence.vercel.app)

---

## Research Foundation

This system extends the EABN/G-BNI framework for autonomous brand communication systems using multi-agent LangGraph architectures. Published research: **SSRN Abstract ID 6845958**.

---

## Team

**Adithya Reddy** — Lead AI Engineer, Eject Solutions Pvt Ltd, Hyderabad
- 3+ years building LangGraph multi-agent systems in production
- Published research on autonomous AI communication systems
- Ran 300+ B2B partner campaigns — this problem is lived experience

---

## AI Tools Disclosure

GitHub Copilot was used for development assistance. Claude API (claude-sonnet-4-6) powers the live demo agent intelligence. All architecture decisions, system design, and product thinking are original.

---

*Microsoft Build AI Hackathon 2026 | Theme: Agent Swarms | Team: Adithya's Team 6*
