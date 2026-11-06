<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=800&height=60&lines=Hey%2C+I'm+Akshay+Kaushik+%F0%9F%91%8B;Full-Stack+Developer+%7C+GenAI+in+Production;Python+%7C+Django+%7C+React+%7C+Next.js;Shipping+AI-powered+marketplace+features" alt="Typing SVG" />

### Full-Stack Developer | GenAI in Production | Problem Solver

*Turning ideas into scalable products - including AI search, agents, and real-time systems.*

<br/>

[![Twitter](https://img.shields.io/badge/Twitter-161B22?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/AkshaykKaushik)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-161B22?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/iamakshaykaushik/)
[![YouTube](https://img.shields.io/badge/YouTube-161B22?style=for-the-badge&logo=youtube&logoColor=FF0000)](https://www.youtube.com/channel/UCXgvEwogFnrduVGIMRs8Q8Q)
[![Facebook](https://img.shields.io/badge/Facebook-161B22?style=for-the-badge&logo=facebook&logoColor=1877F2)](https://www.facebook.com/IamAkshayKaushik/)
[![Portfolio](https://img.shields.io/badge/Portfolio-161B22?style=for-the-badge&logo=firefox&logoColor=58A6FF)](https://akshaykaushik.dev)

</div>

---

## `$ whoami`

I'm **Akshay Kaushik**, a Full-Stack Developer who ships end-to-end web products - from Backend APIs and async workers to React/Next.js UIs - and production GenAI features.

I work across the full lifecycle: architecture, APIs, data models, background jobs, and interactive frontends.

- **Interests:** Full-stack web, production GenAI, search & personalization, software engineering.
- **Currently shipping:** Gemini / Vertex AI agents, semantic search, and event-driven recommendation systems.
- **Backend:** Python, Django, FastAPI, Celery, Redis, PostgreSQL / MySQL.
- **Frontend:** JavaScript, React, Next.js, Tailwind CSS.
- **AI stack:** Google Gemini, Vertex AI embeddings, hybrid retrieval (dense + TF-IDF), LLM tool calling, prompt engineering.
- **Ask me about:** Django, Next.js, LLM function calling, Agents, and building AI features that stay fast & grounded.

📬 **Let's connect:** [akshaykaushik.dev](https://akshaykaushik.dev) · [Email](mailto:akshay.kaushik9@gmail.com)

---

## 🚀 Featured work - MrSolvo (marketplace GenAI)

Production AI features on a services marketplace (consultations, bookings, payments).

### 1. Agentic dashboard recommendations
Built a **Gemini 2.5 Flash** recommendation agent with **function/tool calling** that suggests real services a client is likely to book next.

- **Two-pass agent:** intent memory update → catalog tools (`search_offerings`, price tiers, provider offerings, ownership checks)
- **Incremental memory:** saved activity summary + structured intent + event cursor (deltas only - not full history every run)
- **Event-driven rebuilds:** orders, chat (EN/Hindi request gate), search, browse, bookmarks, ratings → debounced Celery jobs
- **Grounded output:** model may only return catalog IDs from tools; server validates, pins unpaid/failed bookings, strips PII(Personally Identifiable Information)
- **Fast UX:** dashboard **reads precomputed rows** - Gemini never runs on page load

### 2. Hybrid semantic category search
Shipped `search-categories` with **Vertex AI / Gemini embeddings** + **TF-IDF** + optional **LLM rerank**.

- Offline index build (persisted), Celery rebuild on catalog changes
- Query embedding cache + response LRU cache; retries for rate limits
- Cost control: disabled dynamic thinking after it dominated Vertex spend
- Dual auth: Vertex AI service account or Gemini Developer API

### 3. Full-stack marketplace systems
Beyond AI: payments & ledger, chat & video consultations, provider ranking, admin RBAC, dashboards, WhatsApp/email notifications - Django + Next.js + Celery.

<details>
<summary><b>Resume-style highlights</b></summary>

<br/>

- Production **tool-calling GenAI agent** for personalized service recommendations with Celery debounce and DB-backed memory  
- **Hybrid semantic search** (Gemini embeddings + TF-IDF + optional LLM rerank) for category discovery  
- Hardened LLM output with **grounding, validation, and PII scrubbing** so recommendations stay catalog-true and privacy-safe  
- Event pipeline for personalization telemetry → async rebuild → low-latency dashboard reads  

</details>

---

## ⚡ Tech Stack & Tools

*Technologies I use to build, deploy and maintain applications.*

<div align="center">

### Languages & Frameworks

<img src="https://skillicons.dev/icons?i=python,javascript,django,react,redux,nextjs,html,tailwindcss,wordpress" />

### Databases, Messaging & Infrastructure

<img src="https://skillicons.dev/icons?i=mysql,postgres,redis,rabbitmq,kafka,docker,cloudflare,workers" />

### Development & Testing Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode,postman,selenium" />

<br/>

**AI & async:** Gemini · Vertex AI · Embeddings · Hybrid Search · Celery · Prompt Engineering · Tool Calling

</div>

---

## 🌱 What I'm Exploring

| Area | Current Focus |
|---|---|
| Production GenAI | Gemini agents, tool calling, grounded recommendations, cost/latency tuning |
| Search & ranking | Dense + sparse hybrid retrieval, LLM reranking, marketplace relevance |
| Backend Engineering | Django APIs, Celery workers, Redis, reliable async pipelines |
| Frontend Development | React, Redux, modern Next.js |
| Databases | PostgreSQL / MySQL at product scale |

---

## 📊 GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=IamAkshayKaushik&show_icons=true&theme=github_dark&hide_border=true&count_private=true" />

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=IamAkshayKaushik&layout=compact&theme=github_dark&hide_border=true" />

<br/><br/>

<img width="75%" src="https://streak-stats.demolab.com?user=IamAkshayKaushik&theme=github-dark-blue&hide_border=true" />

</div>

---

<div align="center">

### 💡 Build. Learn. Improve. Repeat.

*Shipping full-stack products - and GenAI that holds up in production.*

[![Portfolio](https://img.shields.io/badge/Explore_My_Portfolio-Visit_Now-58A6FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://akshaykaushik.dev)

<sub>Thanks for visiting my GitHub profile!</sub>

</div>
