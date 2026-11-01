# Hi, I'm Mohammed Bello Ibrahim 👋

**AI Engineering · Data · Security & Governance**

Final-year Honours Computer Science student (Data Analytics) at Trent University, graduating April 2027 and open to 2027 new grad roles in Ontario. I build AI that is useful, measured, and secure.

📍 Ontario, Canada · 🎓 Dean's Honour Roll 2024, 2025 and 2026

---

## 🚀 Flagship: CalGrid AI

**[calgridai.com](https://calgridai.com)**: an AI data analyst for small businesses. Upload a spreadsheet and get plain-English insights, forecasts, and shareable reports. I'm the founder and lead engineer.

**Latest: "Ask your data" (RAG).** Owners ask a question like *"Which month had my highest revenue?"* and get a cited answer drawn from every report they've saved.

| Metric (13-question eval) | Result |
|---|---|
| Answer accuracy | 13 / 13 |
| Retrieval recall | 100% |
| Groundedness (every number traced to a source) | 100% |
| Abstention (says "not in your reports" when it should) | 100% |
| Prompt-injection test | Passed |
| Median latency | ~5 s |

- **Retrieval:** pgvector (HNSW) in Postgres, Voyage embeddings, top-8 passages with a similarity floor
- **Grounding:** precomputed aggregates instead of raw rows, structured JSON answers with citations
- **Observability:** Langfuse tracing (OpenTelemetry) for latency, tokens, and cost per question
- **Security:** row-level security, per-user search filtering, rate limits, and a platform security audit

👉 [Live product](https://calgridai.com) · [Project overview](https://github.com/Bellomk77/calgrid-ai)

---

## 📊 Projects

▶ **[Try my projects live in your browser](https://mohammed-bello-ibrahim.vercel.app/demos/)**: interactive demos built on each project's real output.

### 🛠️ Data engineering & machine learning

| Project | What it does | Highlight | Stack |
|---|---|---|---|
| **[Retail Data Pipeline](https://github.com/Bellomk77/retail-data-pipeline)**<br>[▶ Live demo](https://mohammed-bello-ibrahim.vercel.app/demos/retail.html) | ELT pipeline: 59K messy rows → tested star schema → KPIs and cohort retention | Every injected data issue caught (6/6), revenue reconciles to the cent, 25 dbt tests | dbt · DuckDB · Airflow · SQL |
| **[Customer Churn Prediction](https://github.com/Bellomk77/customer-churn-prediction)** | Exploratory ML on 7,000+ telecom customers | Random Forest and XGBoost, 80.7% accuracy | Python · scikit-learn |
| **[Sales Performance Dashboard](https://public.tableau.com/app/profile/mohammed.bello.ibrahim/viz/SalesPerformanceDashboardSuperstore2025/SalesPerformanceDashboard)** | KPI dashboard from 10,000+ retail sales records | Regional and category performance | Tableau |

### 🏛️ Security & GRC

| Project | What it does | Highlight | Stack |
|---|---|---|---|
| **[GRC Risk Toolkit](https://github.com/Bellomk77/grc-risk-toolkit)**<br>[▶ Live demo](https://mohammed-bello-ibrahim.vercel.app/demos/grc.html) | Cyber risk assessment as code against NIST CSF 2.0 | Risk register, heat maps, and a roadmap that cuts high risks from 6 to 1 with 5 actions | Python · NIST CSF 2.0 · Excel |

## 🛡️ Security & Governance

- **vCISO Cybersecurity Risk Assessment extern:** scoping, asset inventory, control-gap scoring, and risk ranking for a client
- **IoT Cyber Defense extern (Hydroficient):** STRIDE threat model, mutual TLS and HMAC message signing on a live sensor pipeline
- **CalGrid AI security audit:** auth, access control, secrets, and payment flows of a live SaaS

## 🧰 Toolkit

**AI:** LLM APIs · tool calling · RAG · embeddings · pgvector · LLM evaluation · prompt engineering · Langfuse
**Data:** Python (Pandas, NumPy, Scikit-learn) · SQL · PostgreSQL · dbt · DuckDB · Airflow · Tableau · Excel
**Engineering:** FastAPI · Docker · GitHub Actions · Next.js · React · Vercel · Supabase · Clerk · Stripe
**Security:** OWASP Top 10 for LLMs · threat modelling · risk assessment · access control · NIST CSF 2.0
**Currently learning:** Power BI · CompTIA Security+ · Azure fundamentals

---

## 🌐 Connect

[LinkedIn](https://www.linkedin.com/in/mohammed-bello-ibrahim-7521b62a2/) · [Portfolio](https://mohammed-bello-ibrahim.vercel.app) · [CalGrid AI](https://calgridai.com)
