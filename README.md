# Hi, I'm Mohammed Bello Ibrahim 👋

**AI Engineering · Data · Security & Governance**

Final-year Honours Computer Science student (Data Analytics) at Trent University, graduating April 2027 and open to 2027 new grad roles in Toronto. I build AI that is useful, measured, and secure.

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

- **[Customer Churn Prediction](https://github.com/Bellomk77/customer-churn-prediction):** end-to-end ML pipeline (EDA, Random Forest, XGBoost) on 7,000+ telecom records, 80.7% accuracy
- **[Sales Performance Dashboard](https://public.tableau.com/app/profile/mohammed.bello.ibrahim/viz/SalesPerformanceDashboardSuperstore2025/SalesPerformanceDashboard):** Tableau KPI dashboard from 10,000+ retail sales records
- **Coming next:** Python AI agent with tool calling and evals · data pipeline (Airflow + dbt) · LLM security tester

## 🛡️ Security & Governance

- **vCISO Cybersecurity Risk Assessment extern:** scoping, asset inventory, control-gap scoring, and risk ranking for a client
- **IoT Cyber Defense extern (Hydroficient):** STRIDE threat model, mutual TLS and HMAC message signing on a live sensor pipeline
- **CalGrid AI security audit:** auth, access control, secrets, and payment flows of a live SaaS

## 🧰 Toolkit

**AI:** LLM APIs · RAG · embeddings · pgvector · LLM evaluation · prompt engineering · Langfuse
**Data:** Python (Pandas, NumPy, Scikit-learn) · SQL · PostgreSQL · ETL · Tableau · Excel
**Web & Cloud:** Next.js · React · JavaScript · Vercel · Supabase · Clerk · Stripe
**Security:** threat modelling · risk assessment · access control · NIST CSF
**Currently learning:** AI agents · Power BI · CompTIA Security+ · Azure fundamentals

---

## 🌐 Connect

[LinkedIn](https://www.linkedin.com/in/mohammed-bello-ibrahim-7521b62a2/) · [Portfolio](https://mohammed-bello-ibrahim.vercel.app) · [CalGrid AI](https://calgridai.com)
