# Aleksandr Mordvinov

**Founder & Applied AI Architect** · [Scanovich](https://scanovich.ai)

Production-grade AI infrastructure for sensitive business workflows — systems where data quality is imperfect, decisions are expensive, and trust is designed into the architecture.

Work spans:

* document intelligence
* voice and call operations
* retrieval-grounded applications
* governed multi-agent workflows
* local and private AI infrastructure
* compliance-aware automation
* forensic and audit-ready systems

Primary objective: **risk reduction** — data privacy, operational accuracy, compliance exposure, decision quality, and human sign-off when AI runs in production.

[Website](https://scanovich.ai) · [LinkedIn](https://www.linkedin.com/in/aleksandr-mordvinov-3bb853325/) · [Telegram](https://t.me/ScanovichAI)

---

## Current research and build lane

Public research explores one question from multiple domains:

**How can AI systems operate safely around valuable data, sensitive workflows, and high-risk decisions?**

Representative directions:

* agents that cannot publish unsupported claims
* retrieval systems with evidence-bound outputs
* supervisor-approved policy memory
* local-first call analytics
* audit trails and rollback for learned behavior
* private inference and retrieval infrastructure
* structured outputs for operational workflows

Domains differ; the underlying layer is consistent:

**AI should not only be capable. It should be governable, observable, and accountable.**

---

## Flagship projects

| Project | Focus | Repository |
| --- | --- | --- |
| **EvidenceGene Court** | Autonomous DFIR with read-only MCP tools, adversarial review, fail-closed evidence gates, red-team harness, ablation, local model execution | [evidencegene-court](https://github.com/FUYOH666/evidencegene-court) |
| **ConductGene Swarm** | Governed conduct QA: Prosecutor / Defender / Arbiter, Policy Genes, supervisor approval, audit export, Qdrant retrieval, live simulation | [conductgene-swarm](https://github.com/FUYOH666/conductgene-swarm) |
| **AttestRWA** | Settlement attestation and programmable escrow for real-world asset workflows | [attestrwa](https://github.com/FUYOH666/attestrwa) |
| **Scanovich Audio Call** | Local-first call analytics: recordings → transcription → structured scoring → operational review | [Scanovich.ai-audio-call](https://github.com/FUYOH666/Scanovich.ai-audio-call) |

Recommended profile pins:

`evidencegene-court` · `conductgene-swarm` · `attestrwa` · `Scanovich.ai-audio-call`

---

## Main domains

### Private AI infrastructure

Local and private AI for sensitive data, internal knowledge bases, call recordings, operational documents, and regulated workflows.

Typical constraints: privacy, latency, data residency, auditability, model control, cost control, supervisor sign-off, integration with operator systems.

### Document intelligence

Extraction, classification, retrieval, and schema-bound outputs for noisy real-world documents — transport paperwork, customs-oriented inputs, supplier records, degraded scans, handwritten fields, declaration-ready structured outputs.

### Voice and conduct operations

Speech-to-text, call analytics, QA scoring, and supervisor-governed review. Operational value: summaries, entities, risks, scores, policy references, and escalation signals — not transcription alone.

### Governed agents

Multi-agent systems where autonomy is bounded by evidence, tools, approval paths, and audit logs.

Design patterns in active use: adversarial review, citation-bound decisions, abstain paths, human approval, rollback, deterministic baselines, red-team and ablation testing.

### Security and DFIR

Autonomous forensic workflows with the model treated as untrusted by default — read-only tools, evidence re-derivation, tamper-evident logs, fail-closed publication gates for incident findings.

### Cross-border trade and marketplace operations

Document and intelligence systems for cross-border commerce, logistics, marketplace analytics, classification support, supplier normalization, and operational workflows.

### Settlement and attestation

Auditable release paths for real-world asset and settlement workflows — attestations, escrow logic, structured compliance evidence.

---

## Selected public repositories

### Governed agents and AI safety

| Repository | Demonstrates |
| --- | --- |
| [evidencegene-court](https://github.com/FUYOH666/evidencegene-court) | Autonomous DFIR court, read-only MCP, fail-closed validation, red-team harness, local execution |
| [conductgene-swarm](https://github.com/FUYOH666/conductgene-swarm) | Conduct QA, Policy Genes, supervisor-approved learning, audit trails, Qdrant retrieval, benchmark path |

### Voice and call intelligence

| Repository | Demonstrates |
| --- | --- |
| [Scanovich.ai-audio-call](https://github.com/FUYOH666/Scanovich.ai-audio-call) | End-to-end call analytics, structured scoring, saved results, pilot-ready API/UI |
| [VoiceToText](https://github.com/FUYOH666/VoiceToText) | Offline ASR, privacy-first speech processing |
| [ai-agent-tts](https://github.com/FUYOH666/ai-agent-tts) | Low-latency voice agents, streaming speech workflows |

### Retrieval and infrastructure

| Repository | Demonstrates |
| --- | --- |
| [Services-BGE](https://github.com/FUYOH666/Services-BGE) | Embedding and reranking services for hybrid retrieval |
| [linux-defender](https://github.com/FUYOH666/linux-defender) | Security-aware Linux operations, monitoring, audit support |
| [Cleaner-OS](https://github.com/FUYOH666/Cleaner-OS) | Workstation cleanup, dependency awareness, ML cache hygiene |

### Business and settlement systems

| Repository | Demonstrates |
| --- | --- |
| [attestrwa](https://github.com/FUYOH666/attestrwa) | EAS attestations, programmable escrow for RWA settlement |
| [realestate-agent-platform](https://github.com/FUYOH666/realestate-agent-platform) | Multi-channel enterprise agents, grounding, tenant isolation |

### Applied AI prototypes

| Repository | Demonstrates |
| --- | --- |
| [Scanovich.ai-MRI_radiology_assistant](https://github.com/FUYOH666/Scanovich.ai-MRI_radiology_assistant) | Clinical imaging support, structured reporting research |

[Full public repository list →](https://github.com/FUYOH666?tab=repositories)

---

## Stack

**Languages and backend:** Python, FastAPI, Node.js, TypeScript  
**AI systems:** LLMs, RAG, agents, structured outputs, ASR/TTS, local inference  
**Inference:** vLLM, llama.cpp, Ollama, LM Studio, OpenAI-compatible APIs  
**Retrieval:** Qdrant, BGE embeddings, reranking, hybrid search  
**Agents and tools:** MCP, LangGraph-style orchestration, tool-bound workflows  
**Data and operations:** PostgreSQL, Redis, Docker, Linux, Apple Silicon  
**Quality layer:** evals, health checks, audit logs, red-team harnesses, ablation tests, deterministic baselines

---

## Operating doctrine

1. **Architecture before prompts** — prompts guide behavior; architecture defines boundaries.  
2. **Evidence before confidence** — high-stakes systems require traceable evidence, not eloquence alone.  
3. **Human sign-off where it matters** — approval paths, audit trails, and rollback belong in the product.  
4. **Private by default when data is valuable** — deployment model matters as much as model choice.  
5. **Determinism as a baseline** — measurable behavior needs stable baselines, tests, and evaluation paths.  
6. **Vertical slice first, hardening after proof** — end-to-end paths ship early; production discipline follows demonstrated value.

---

## Collaboration

Engagements typically align with:

* private AI infrastructure and enterprise adoption  
* sensitive data workflows and call intelligence  
* cross-border trade and marketplace operations  
* governed agents and AI safety  
* forensic and incident-response automation  
* settlement, attestation, and audit-ready systems  
* design partnerships and selective capital conversations across APAC  

A substantive first conversation usually covers: workflow, data characteristics, risk, current manual process, decision point, deployment constraints, and human approval gate.

---

## Contact

**Email:** [iamfuyoh@gmail.com](mailto:iamfuyoh@gmail.com)  
**Telegram:** [@ScanovichAI](https://t.me/ScanovichAI)  
**Website:** [scanovich.ai](https://scanovich.ai)  
**LinkedIn:** [Aleksandr Mordvinov](https://www.linkedin.com/in/aleksandr-mordvinov-3bb853325/)
