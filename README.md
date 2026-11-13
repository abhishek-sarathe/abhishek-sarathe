# Hi, I'm Abhishek 👋

**AI Engineer · Agentic AI & LLM Systems · Bengaluru, India**

I build production AI systems end-to-end: multi-agent pipelines, RAG and LLM evaluation, plus the backend, payments and infrastructure around them.

Currently an AI Engineer at **nu10**, building GenAI fraud-detection engines for a motor-insurance claims platform. B.Tech from IIT Guwahati (2019).

---

## 💼 Current work: GenAI claims quality control at nu10

- **Contradiction Analysis Engine:** groups related document chunks, detects contradictions across documents (dates, names, narratives) and flags them against known fraud patterns
- **Entity Graph Engine:** end-to-end entity extraction, entity resolution against existing data, Neo4j graph construction and fraud-ring detection
- **Evaluation:** LLM-as-judge frameworks for both engines, which reliably exceed 80% accuracy on complex cases
- **Cost:** introduced prompt caching and drove team-wide adoption, cutting the average per-claim processing cost by 60%
- **Observability:** 5 Grafana dashboards (70+ panels) for claim-run metrics and system health
- Both engines are now in UAT ahead of production

*This is client work, so the code isn't public.*

## 🚀 Projects

### [Under These Stars](https://underthesestars.in): live, 50+ paying customers
An e-commerce product that generates astronomically accurate star-map posters. It has 50+ paying customers with zero marketing. A customer picks a date and place, and the backend computes the exact night sky from NASA's DE440 ephemeris and the Hipparcos catalogue, then renders it at 300 DPI with Matplotlib. Built and run solo.

- **Backend:** FastAPI on Railway with Razorpay webhook verification, async fulfilment, Supabase storage, Resend email, and Groq LLM title generation with validation and retry logic
- **Frontend:** Next.js on Vercel with a 3-step wizard, IP-based multi-currency pricing, PostHog AARRR funnel analytics and automated 30-day PII anonymisation

`FastAPI` `Next.js` `Skyfield` `Matplotlib` `Supabase` `Razorpay` `Groq` `PostHog` `Railway` `Vercel`

➡️ [Website](https://underthesestars.in) · [Frontend repo](https://github.com/abhishek-sarathe/under-these-stars) · [Star-map engine](https://github.com/abhishek-sarathe/star-map-poster) · [Streamlit demo](https://star-map-generator.streamlit.app/)

### [NOCA: Not Only Calorie App](https://github.com/abhishek-sarathe/noca) (in development)
A learning-first calorie app for Indian food, built around a **Guess → Learn → Graduate** loop. It runs as a 4-agent LangGraph pipeline (Food Identifier, Nutrition Analyst, Quiz Generator, Learning Coach), with RAG over a curated 82-item Indian food knowledge base in ChromaDB.
The LLM (Llama 3.3 on Groq) only identifies the food. Nutrition is computed deterministically with the Atwater system, which keeps hallucinated numbers out.

`Python` `LangGraph` `LangChain` `RAG` `ChromaDB` `FastAPI` `Groq` `React`

### Freshworks CRM migration to Salesforce (Jade Global)
Sole engineer on a **30M+ record** CRM migration to Salesforce for Freshworks, across 9 object types using Bulk API V2.

- **Pipeline:** resumable batches of 60K records, with cursor-based Databricks pagination and PostgreSQL checkpointing, so nothing is reprocessed after a failure
- **Job control:** a FastAPI layer with ID mapping across 9 ordered passes; 256K attachments migrated

*This is client work, so the code isn't public.*

`Python` `FastAPI` `Salesforce Bulk API V2` `Databricks` `PostgreSQL`

---

## 🛠️ Tech stack

- **Agentic AI & GenAI:** LangGraph · LangChain · Multi-agent orchestration · RAG · MCP · Prompt engineering · Prompt caching · LLM-as-judge evals · Entity resolution
- **LLMs & platforms:** AWS Bedrock · Claude API · Groq (Llama 3.3)
- **Languages:** Python · SQL · Java · JavaScript
- **Databases:** Neo4j · PostgreSQL · Snowflake · Supabase · SQLite · ChromaDB
- **Backend & frontend:** FastAPI · Pydantic · async/await · REST APIs · Webhooks · React · Next.js · Tailwind CSS
- **Cloud, DevOps & monitoring:** AWS (Bedrock, S3) · Docker · Railway · Vercel · GitHub Actions · Grafana · PostHog
- **Data & integration:** MuleSoft · Salesforce Bulk API V2 · Databricks · Batch/ETL pipelines · Pandas

## 📋 Experience

| When | Role | Company |
|---|---|---|
| Jun 2026 – Present | AI Engineer | nu10 · Bengaluru |
| Oct 2025 – Jun 2026 | Full Stack AI Developer (Under These Stars) | Self-employed · Bengaluru |
| Mar 2025 – Sep 2025 | Senior Associate Consultant, Data Migration & Integration | Jade Global · Pune |
| Jun 2019 – Jun 2021 | Project Engineer, Enterprise Integration (Eddie Bauer on Oracle Retail) | Wipro · Bengaluru |

## 🎓 Education

**IIT Guwahati:** B.Tech in Mechanical Engineering (2015–2019)

**Courses:** Agentic AI (DeepLearning.AI, Andrew Ng) · Machine Learning Crash Course (Google)

## 📫 Get in touch

[Portfolio](https://my-portfolio-nu-three-18.vercel.app) · [LinkedIn](https://linkedin.com/in/abhishek-sarathe) · [Email](mailto:official.abhishek.sarathe@gmail.com)
