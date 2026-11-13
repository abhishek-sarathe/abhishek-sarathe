# Hi, I'm Abhishek 👋

**Agentic AI Developer · Bengaluru, India**

I build AI products end-to-end, from multi-agent pipelines and RAG to payments, deployment and DNS.
B.Tech from IIT Guwahati (2019). Six years across enterprise integration, large-scale CRM migration, and now shipping my own AI products.

🔍 Open to **Agentic AI Developer** roles at product companies.

---

## 🚀 Featured projects

### [NOCA: Not Only Calorie App](https://github.com/abhishek-sarathe/noca)
An AI calorie tutor for Indian food. A 4-agent LangGraph pipeline (food identifier, nutrition analyst, quiz generator, learning coach) takes users through a **Guess → Learn → Graduate** loop, backed by a curated 82-food RAG knowledge base and Atwater-system nutrition derivation.
Key design decision: the LLM only identifies the food. Nutrition numbers always come from validated data, never from the model.

`Python` `FastAPI` `LangGraph` `LangChain` `Groq` `ChromaDB` `Pydantic`

### [Under These Stars](https://underthesestars.in): live, revenue-generating
Astronomically accurate star-map posters, generated on demand. A customer picks a date and place, and the backend computes the exact night sky from NASA's DE440 ephemeris and the Hipparcos catalogue. Matplotlib renders it at 300 DPI, an LLM writes the title, Razorpay takes payment, and Resend delivers the poster. Built and run solo.

`FastAPI` `Next.js 15` `Skyfield` `Matplotlib` `Supabase` `Razorpay` `Groq` `Railway` `Vercel`

➡️ [Website](https://underthesestars.in) · [Frontend repo](https://github.com/abhishek-sarathe/under-these-stars) · [Star-map engine](https://github.com/abhishek-sarathe/star-map-poster) · [Streamlit demo](https://star-map-generator.streamlit.app/)

### Freshworks CRM Migration (client work at Jade Global)
I was the sole engineer migrating **30M+ CRM records** to Salesforce for a Fortune-500 SaaS client, across 9 dependency-ordered object types. I designed a resumable batch architecture (APScheduler, Databricks pagination and PostgreSQL checkpointing) that picks up from the exact point of failure. I also built a FastAPI control layer and migrated 256K binary attachments through the ContentVersion API.
*The code belongs to the client, so it isn't public.*

`Python` `FastAPI` `Salesforce Bulk API 2.0` `Databricks` `PostgreSQL` `APScheduler`

---

## 🛠️ Tech stack

- **AI & agents:** LangChain · LangGraph · RAG · ChromaDB · FAISS · Multi-agent orchestration · Prompt engineering
- **Backend:** Python · FastAPI · asyncio · PostgreSQL · Supabase · SQLite · SQL · Java
- **Frontend:** Next.js · React · Tailwind CSS · JavaScript · HTML/CSS
- **Infra & integrations:** Docker · Railway · Vercel · AWS S3 · Razorpay · Resend · Salesforce APIs

## 💼 Experience

| When | Role | Company |
|---|---|---|
| Oct 2025 – Present | Full Stack & AI Developer | Self-employed · Bengaluru |
| Mar 2025 – Sep 2025 | Senior Associate Consultant | Jade Global · Pune |
| Jun 2019 – Jun 2021 | Project Engineer | Wipro · Bengaluru |

## 📫 Get in touch

[Portfolio](https://my-portfolio-nu-three-18.vercel.app) · [LinkedIn](https://linkedin.com/in/abhishek-sarathe) · [Email](mailto:official.abhishek.sarathe@gmail.com)
