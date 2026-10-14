# Raghu Sharma

### Senior AI/ML Engineer · Agentic AI, LLM Evaluation, RAG & MLOps

I design and ship AI systems that survive production: retrieval pipelines, agent workflows, LLM evaluation, distributed data systems, model-serving platforms, and cloud-native infrastructure across GCP and AWS.

I bring **7+ years of engineering experience** across applied machine learning, MLOps, computer vision, retail forecasting, and GenAI, with a focus on reliability, scale, and measurable product outcomes.

[Portfolio](https://rs-portfolio-teal.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/raghu-sharma-7091b4115/) · [Upwork](https://www.upwork.com/freelancers/raghurs) · [Email](mailto:raghusharma0404@gmail.com)

---

## What I work on

- **Agentic workflows & evaluation:** Temporal orchestration (signals, retries, human approval), Langfuse tracing, hidden-test evaluation, guardrails, and quality gates for AI-generated work
- **Generative AI:** RAG, LangGraph, MCP, vector search, embeddings, retrieval evaluation, guardrails, and agent reliability
- **Retail forecasting & ML systems:** demand forecasting, time-series modelling, feature engineering, model optimization, monitoring, and production serving
- **Cloud & MLOps:** Vertex AI, BigQuery, Cloud Run, AWS Bedrock, S3, IAM, Kubernetes, CI/CD, and observability
- **Data engineering:** Python, SQL, PySpark, distributed pipelines, APIs, and batch/stream processing

## Selected engineering work

### [Agentic Delivery Pipeline](https://github.com/raghurs49/agentic-delivery-pipeline)
A spec-to-delivery agent pipeline orchestrated with **Temporal**: structured spec, a human-approval checkpoint (signal with timeout), tests written from the spec before any code, a bounded repair loop, sandboxed test runs, review, and a quality gate. Every run is traced in **Langfuse**, and an evaluation harness scores results against hidden tests the agents never see, so the gate itself is measured (precision, false accepts, false rejects). Real-model runs on free local models showed that repair loops can turn working code into broken code by chasing flawed generated tests. **106 automated tests**, including real Temporal workflow scenarios and a deterministic replay regression in CI. Personal project.

### [RAG Quality Workbench](https://github.com/raghurs49/rag-quality-workbench)
A production-shaped Next.js and FastAPI RAG system with OpenAI, Claude, and Gemini adapters, Postgres/pgvector hybrid retrieval, reranking, citations, abstention, and latency/token/cost traces. Its evaluation harness compares chunking and retrieval configurations through the same pipeline used by the live API. **77 automated tests**, including a real application-startup smoke path.

### [Reliable LangGraph Support Agent](https://github.com/raghurs49/langgraph-support-agent)
A reliability-focused router/supervisor graph with knowledge and order agents, SQLite-backed state, structured node outputs, human approval for risky actions, low-confidence escalation, retries, timeouts, circuit breaking, tracing, and scenario-based evaluation through the compiled graph. **66 automated tests and 11 labeled evaluation scenarios.**

### [Secure BigQuery MCP Gateway](https://github.com/raghurs49/secure-bigquery-mcp-gateway)
A Cloud Run-ready, multi-connector MCP gateway with OIDC authentication, RBAC, constrained BigQuery and PostgreSQL access, governed REST tools, PII masking, rate limits, structured audit logging, and separate caller/workload identities. **34 automated tests plus 7 connector subtests.**

### [AWS Bedrock RAG API](https://github.com/raghurs49/aws-bedrock-rag-api)
A deployable FastAPI reference service with S3-backed ingestion, Bedrock Knowledge Bases, grounded answers with citations, least-privilege IAM, guardrail support, structured logging, CI, tests, and container delivery. Independent portfolio engineering, not client work.

### Policy Intelligence & Semantic Search Platform *(private organization work)*
Built a production policy-intelligence system combining a Dash/Flask application, Vertex AI embeddings, ScaNN semantic retrieval, and Cloud SQL. Delivered the supporting API and scheduled workflows on Cloud Run with private database connectivity, Secret Manager, Artifact Registry, and workload identity federation. The source remains private; architecture and engineering decisions can be discussed in interviews.

### Recommendation from a former manager
Bill Karr, Chief Scientist at Open Insights, described me as a core contributor to the Open ML 1.5 forecasting platform and highlighted my ability to move between model training, deployment, PySpark, and GCP infrastructure.

> "Raghu was a core contributor to Open ML 1.5... comfortable moving between training and deploying ML models, writing and optimizing PySpark jobs, and managing cloud infrastructure on GCP, including BigQuery and Dataproc."

### [Vector Embeddings Ingestion Pipeline](https://github.com/raghurs49/vector_embeddings_ingestion_pipeline)
A containerized pipeline that reads records from Cloud SQL, generates embeddings with Vertex AI, and writes enriched records to a dedicated database table for downstream retrieval workflows.

### [GCP Data Ingestion Workflows](https://github.com/raghurs49/fetch_data_gcp)
Notebook-driven GCS-to-BigQuery ingestion workflows with service-account authentication and environment-aware CI/CD patterns.

### [Python Interview Solutions](https://github.com/raghurs49/python-interview-solutions)
Readable Python solutions with reasoning, complexity analysis, tests, and interview-oriented explanations.

## Experience snapshot

- **Independent AI/ML Engineer** — production-oriented AI and cloud engineering
- **Open Insights** — Machine Learning Engineer (ML/MLOps)
- **Capgemini** — MLOps Engineer
- **Hughes Systique** — Data Scientist / ML Engineer
- **Integration Wizards** — Machine Learning Intern

## Credentials

- Google Cloud Professional credentials earned: **Cloud Architect** and **Machine Learning Engineer**
- NVIDIA Jetson AI certification
- Kaggle ranking: approximately top 11% (800 / 7,000)

## Core stack

`Python` · `SQL` · `RAG` · `LangGraph` · `MCP` · `Temporal` · `Langfuse` · `LLM evaluation` · `pgvector` · `PySpark` · `TensorFlow` · `PyTorch` · `FastAPI` · `Vertex AI` · `BigQuery` · `Cloud Run` · `AWS Bedrock` · `Kubernetes` · `Docker` · `CI/CD`

---

Currently open to senior AI/ML, GenAI, and ML platform engineering opportunities.
