# Katara AI

**Compliance-native RAG infrastructure for teams deploying AI in regulated environments.**

Katara provides the governed data access layer that enterprise AI deployments require — 
chunk-level access controls, tamper-evident audit logging, authenticated MCP, and data 
lineage — built for teams that need to govern, audit, and defend what their AI systems 
access.

---

## What Katara is

Most RAG deployments retrieve data and generate responses without enforcing who is 
authorised to see what — and without producing a record of what was accessed, by whom, 
and when. That works in a sandbox. It does not work in a regulated environment where 
audit trails are a legal obligation and cross-dataset data assembly is a compliance risk.

Katara enforces access controls at the retrieval layer — before data enters the LLM 
context window — and produces a tamper-evident record of every query, every dataset 
accessed, and every user action. The same prompt returns different answers for different 
users based on their permission level. Every interaction is logged, exportable, and 
defensible.

---

## Core capabilities

- **Chunk-level RBAC** — per-user, per-group permission enforcement at retrieval time, 
  not at the application layer
- **Authenticated MCP** — OAuth 2.1 implementation of the Model Context Protocol; 
  every agent connection is identity-verified
- **Tamper-evident audit logging** — immutable record of every query, dataset access, 
  chunk retrieved, and user action; exportable for regulatory examination
- **Collection isolation** — logical separation of datasets with configurable sharing 
  rules; the same query returns different results based on access level
- **Data lineage** — traceable provenance for every piece of data in the system
- **LLM and cloud agnostic** — works with any model provider, deployable in any GCP 
  region; on-prem deployment on the roadmap

---

## Who it is for

Teams in regulated industries — financial services, healthcare, legal, education, 
government — deploying AI across sensitive datasets where access controls, audit trails, 
and regulatory compliance are requirements, not nice-to-haves.

Specifically useful if your AI system:
- Evaluates, scores, or ranks people in a consequential context
- Processes sensitive documents across users with different access rights
- Must demonstrate what data was accessed and why to a regulator or auditor
- Is subject to EU AI Act, DORA, NIST AI RMF, or GDPR obligations

---

## Integrations

**n8n** — the Katara node is live in the n8n community node library. Connect governed 
RAG collections to any n8n workflow. [katara-ai-inc/n8n-nodes-katara](https://github.com/katara-ai-inc/n8n-nodes-katara)

**MCP** — Katara's authenticated MCP server connects any MCP-compatible agent framework 
to governed collections. Endpoint: `mcp.katara.ai`

LangChain and LangGraph integrations are on the roadmap.

---

## Pioneer Programme

We are currently running a structured six-month engagement for two founding design 
partners. The programme combines platform access, a full EU AI Act readiness assessment 
with legal review, and hands-on implementation support from the founding team.

[pioneer.katara.ai](https://pioneer.katara.ai/)

---

## Documentation

[docs.katara.ai](https://docs.katara.ai)

---

## Contact

- **Website**: [katara.ai](https://katara.ai)
- **Email**: hello@katara.ai
- **LinkedIn**: [company/katara-ai](https://www.linkedin.com/company/katara-ai/)

---

*Katara AI is based in Barcelona, Spain. Delaware C-corp.*

Built by AI enthusiasts. Let's supercharge your AI journey!
