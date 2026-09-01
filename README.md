# Aqsa Siddiqui

**Generative AI Engineer** — production LLM systems, RAG pipelines, multi-agent orchestration, and the evaluation harnesses that keep them honest.

Based in Lucknow, India · working remote · [aqsa-portfolio-mu.vercel.app](https://aqsa-portfolio-mu.vercel.app)

---

## What I actually do

I build LLM systems that are constrained to be truthful, and I measure them. The pattern shows up across most of the work below: retrieval and statistics are deterministic code, the model is confined to the narrowest job that genuinely needs one, and a gate or a scoring harness decides whether its output is allowed through.

Concretely, that means things like a 63-line pure function with final authority over an AI coach's output, a RAGAS harness that scores a retrieval pipeline against ground truth rather than vibes, and a five-agent LangGraph loop whose retry budget lives in the state schema so it structurally cannot spin forever.

## Currently

**Machine Learning & Generative AI Engineer @ Fansify** · Dec 2025 – Present · Remote

- Built and evaluated production ML models with Python and scikit-learn, achieving **15%+ accuracy improvements** through advanced feature engineering and ensemble techniques.
- Architected and deployed Generative AI features into production ML pipelines, and designed REST APIs integrating LLM inference with model predictions — **reducing latency by 40%**.

## Selected work

| Project | What it is | Live |
|---|---|---|
| **[Attune](https://github.com/aqsa-svg/attune)** | Wellness app whose AI coach refuses to invent patterns — a pure, unit-tested grounding gate rejects any model output that references a habit you don't have or claims a pattern before 7 days of data | [demo](https://attune-sigma-khaki.vercel.app) |
| **[ITC Guard](https://github.com/aqsa-svg/itc-guard)** | Reconciles an Indian business's purchase register against GSTR-2B to surface at-risk input tax credit — and states plainly what the data cannot decide | — |
| **[Production RAG Pipeline](https://github.com/aqsa-svg/rag-layer)** | Hybrid BM25 + dense retrieval with Reciprocal Rank Fusion, ONNX cross-encoder reranking, and a RAGAS evaluation layer. No framework — direct API calls | — |
| **[Self-Healing Multi-Agent System](https://github.com/aqsa-svg/multi_agent)** | Five LangGraph agents plan, pull from GitHub, run tests in Docker, review, then patch the failing code and loop back. 30 tests pass with no keys and no daemon | — |
| **[ConvoRAG](https://github.com/aqsa-svg/rag-chatbot)** | Conversation-intelligence RAG over 191,578 messages across 11,000 conversations. Pure scikit-learn retrieval; the LLM only phrases the answer | — |
| **[Agent Memory](https://github.com/aqsa-svg/agent-memory)** | Chat agent with long-term memory that survives across sessions — mem0 + Qdrant + local embeddings, zero running cost | [demo](https://agent-memory-beryl.vercel.app) |
| **[Stroke Risk Prediction](https://github.com/aqsa-svg/stroke-risk-prediction)** | Eight classifiers benchmarked on 4.87%-positive clinical data, where the 95.13% majority baseline beats every model and 91% accuracy hides 20% recall | — |
| **[PocketCode](https://github.com/aqsa-svg/pocketcode-app)** | Drive Claude Code from your phone — end-to-end encrypted, with approve-from-phone permissions | [demo](https://pocketcode-zeta.vercel.app) |
| **[SheetSense](https://github.com/aqsa-svg/SheetSense)** | Gemini as a Google Sheets formula — `=SENTIMENT(A2)` filled down a column, with MD5-keyed response caching so a fill-down doesn't burn your quota | — |
| **[Adaptive Persona Engine](https://github.com/aqsa-svg/persona-engine)** | Persona drift detection, offline intent classification, and recency-weighted resolution of contradictory retrieved sources | — |

Every README above reports what was actually measured, and marks what wasn't as `[TODO]` with instructions for measuring it.

## Stack

**Generative AI** — LangChain · LangGraph · Hugging Face · RAG systems · retrieval optimization · prompt engineering · RAGAS · BM25 · hybrid search · reranking · vector search

**LLM & APIs** — Claude API · Gemini API · Groq API · FastAPI · Flask · REST APIs · Next.js

**Vector & data stores** — ChromaDB · Qdrant · PostgreSQL

**Machine learning** — scikit-learn · XGBoost · LightGBM · SMOTE · TF-IDF · cosine similarity · feature engineering · model evaluation

**Languages** — Python · SQL · TypeScript · JavaScript · HTML · CSS

**BI & tooling** — Power BI · Tableau · Streamlit · Docker

## Background

- **2025** — Data Science & Generative AI Certification, Top Mentor, India
- **2021–2024** — B.Sc., University of Lucknow

## Reach me

[Portfolio](https://aqsa-portfolio-mu.vercel.app) · [LinkedIn](https://www.linkedin.com/in/aqsa-siddiqui-619695249/) · [aqsasiddiqui3146@gmail.com](mailto:aqsasiddiqui3146@gmail.com)

Open to Generative AI and ML engineering roles.
