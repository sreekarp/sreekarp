# Hey, I'm Sreekar 👋

AI/ML Engineer building **agentic AI systems** — LLM systems that don't just respond, but reason, plan, retrieve, and act.

I'm currently at **Sandvik**, where I operate as a 2-person AI team inside a 40,000-person enterprise — independently owning architecture, infrastructure, and deployment end-to-end. My main project is an agentic LLM platform on Azure that automates CNC post-processor generation through multi-step reasoning and custom client-side tool orchestration over a session-scoped RAG pipeline across 5,000+ documents. I re-architected the backend into four independently deployable FastAPI microservices behind an API gateway handling routing, rate limiting, and Azure Entra ID authentication, running on Azure Container Apps and provisioned with Terraform (IaC), Docker containerization, and CI/CD pipelines.

---

## What I Care About

- **Agentic AI** — tool orchestration, agentic harness, multi-step reasoning, stateful streaming agents
- **RAG Architecture** — hybrid search, reranking, retrieval that holds up in production
- **LLM Evaluation** — automated frameworks that measure what actually matters
- **Inference Optimization** — speculative decoding, KV caching, quantization

---

## Selected Work

- **[Accelerated-LLM-Inference](https://github.com/sreekarp/Accelerated-LLM-Inference)** — LLM decoding engine with KV cache + speculative decoding: >10× lower latency and ~4× fewer target-model forward passes on long contexts, plus a benchmarking suite for latency / throughput / quantization (4-bit vs FP16) tradeoffs.
- **[research_and_summarize_agent](https://github.com/sreekarp/research_and_summarize_agent)** — async multi-agent research system in LangGraph with parallel scraping and a critique-and-refine loop where an evaluator autonomously triggers revisions until quality thresholds are met.
- **[multiModalRAG_onYtVideos](https://github.com/sreekarp/multiModalRAG_onYtVideos)** — multimodal RAG fusing visual embeddings (BLIP) with audio transcripts, plus a temporal context-expansion algorithm for time-aligned retrieval across video.

At work I've also shipped a generative-AI evaluation framework (automated test-case generation + evaluation loops, ~60% less validation time) and an internal-docs RAG assistant (~40% lower onboarding/support load), and replaced a rule-based classifier with a Graph Neural Network for 3D CAD part classification. Earlier on, I fine-tuned BERT for hate-speech detection, benchmarked against a logistic-regression baseline.

---

## Stack

```
Python · C++
PyTorch · HuggingFace · LangChain · LangGraph · LlamaIndex
FastAPI · Docker · Terraform · CI/CD
Azure · AWS · Qdrant · Pinecone
```

---

## Background

🎓 B.Tech, ECE — **IIT (ISM) Dhanbad** · Top 2.6% JEE Advanced · Top 0.25% JEE Mains

Open to agentic AI / LLM engineering roles — remote, hybrid, or relocation.

---

📬 **<sreekar0664@gmail.com>** · [LinkedIn](https://linkedin.com/in/sreekzzz)
