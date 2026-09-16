# Nishaanth K N
[LinkedIn](https://www.linkedin.com/in/nishaanth-k-n-a59a38232) · [Email](mailto:knnishaanth@gmail.com) · [Portfolio](https://k2n.online)

I build AI systems that work outside the notebook.

Not just the model — the pipeline behind it, the infra under it,
and the context window you have to fight for every token of.
I pick up whatever the problem needs. Polyglot by habit, not by resume.

---

## things I'm actually good at

- Tracing why a system behaves differently in prod than it did on my machine
- Knowing where in a RAG pipeline the answer went wrong — retrieval, chunking, prompt, or model
- Wiring together the unglamorous parts: queues, deduplication, alert routing, context management
- Working with LLMs without trusting them — evals, fallbacks, and knowing when to not use one

---

## layers I've gotten my hands dirty in

| | |
|---|---|
| Retrieval | Documents, embeddings, hybrid search — and the ranking decisions nobody talks about |
| Agent orchestration | Multi-turn flows with LangChain and LangGraph, tool use, and graceful failure modes |
| Infra | Kubernetes, Docker, Azure, event-driven pipelines that need to stay up |
| Model work | BERT fine-tuning, prompt engineering, inference pipelines, HuggingFace |
| Interfaces | Streamlit apps and Teams bots — whatever gets the output in front of the person who needs it |

Things I've used: Python, LangChain, LangGraph, FAISS, PyTorch, Azure, AKS,
Docker, Kubernetes, PostgreSQL, HuggingFace, Streamlit, SQL, Java.
The list keeps changing. That's the point.

---

## Stuff I've Worked on

**[SRE incident bot](https://github.com/Nishaanth419/SRE_Bot_Bosch)** — RAG system for AKS cluster debugging. The hard part wasn't
the retrieval. It was deduplication, conversational coherence, and getting
engineers to trust it at 2am.

**[AKS observability dashboard](https://github.com/Nishaanth419/AKS_diagnosis_Dashboard)** — cluster health monitoring. Useful tools are
boring tools.

**[Real-time ingestion pipeline](https://github.com/Nishaanth419/Delta_Writing_Risingwave)** — Kafka + RisingWave for continuous stream
processing with materialized views. Fresh state without full rebuilds.

**[MovieLens analytics](https://github.com/Nishaanth419/Business-Analytics-Movielens)** — collaborative filtering, graph analysis, text mining.
The point where algorithms get real.

---

## what's keeping me up right now

Production AI systems break in ways demos never do — the model returns something
plausible but wrong, the tool call fails silently, the user asks something
the system was never designed to handle. I'm interested in the gap between
"it works in the demo" and "it works six months later with real users."

---
