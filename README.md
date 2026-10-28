# Malaksima Baghirova

AI engineering · document retrieval · evaluation · guardrails

I build document-grounded AI workflows with traceable sources, explicit failure
handling, and reproducible tests.

## Featured Projects

### [Healthcare LLM Guardrails](https://github.com/baghirovamalaksima-ui/healthcare-llm-guardrails)

FastAPI onboarding API with consent gates, human handoff, FAISS policy retrieval,
and constrained quote validation. Includes 40 documented local tests and synthetic
route evaluation; these checks do not establish clinical safety.

### [Enterprise RAG Document Pipeline](https://github.com/baghirovamalaksima-ui/enterprise-rag-document-pipeline)

Tenant-scoped ingestion with durable SQLite jobs, transactional upserts, FTS5,
FAISS, and reciprocal-rank fusion. Includes 30 documented local tests and a
1,000-document synthetic retrieval experiment reporting both gains and failures.

### [Onboarding Agent](https://github.com/baghirovamalaksima-ui/onboarding-agent)

Bounded function-calling loop with availability, booking, and handoff tools backed
by a FastAPI mock. Application-owned consent, slot confirmation, idempotency, and
23 passing local and Docker tests. The OpenAI adapter is protocol-tested; no live
model result is claimed.

### [AI Reliability Lab](https://github.com/baghirovamalaksima-ui/ai-reliability-lab)

Precision/Recall, MRR, nDCG, citation grounding, and adversarial behavior checks.
All 35 local tests passed, including real multilingual embeddings; offline CI
passed on Python 3.11–3.13. Docker execution is also validated.

## Toolkit Used in These Projects

| Area | Technologies |
|---|---|
| Language and storage | Python, SQL, SQLite |
| APIs and retrieval | FastAPI, FAISS, SQLite FTS5 |
| Evaluation | pytest, sentence-transformers |
| Delivery | Docker, GitHub Actions |
| Optional provider integration | OpenAI API adapters; protocol-tested, without claimed live API results |

## Experience

- **NextGen Health Tech Solutions:** clinical prompt refinement, guardrails, and patient-onboarding workflows.
- **Polish Institute of Cognitive Technologies:** NLP extraction, document retrieval, and database optimization.
- **Melora Psychological Center / Freelance:** service operations and documentation workflows.

## Earlier Work

[Grounded Document Q&A](https://github.com/baghirovamalaksima-ui/grounded-doc-qa)
and [RAG Evaluation Benchmark](https://github.com/baghirovamalaksima-ui/rag-eval-bench)
cover deterministic retrieval, citations, abstention, and case-level evaluation.

## Reported Professional Outcomes

Self-reported professional figures: 95%+ conversational accuracy, 70% workflow
efficiency improvement, and 40% hallucination reduction. Employer datasets and
evaluation definitions are not published; these are not public-repository results.

Public projects use synthetic data and AI-assisted development, with tests and
documented limitations. No employer code or patient records are included.

[All repositories](https://github.com/baghirovamalaksima-ui?tab=repositories)
