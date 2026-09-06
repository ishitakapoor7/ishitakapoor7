# Hi, I'm Ishita 👋

**B.S. Computer Science & Data Science @ University of Wisconsin–Madison · May 2026**

I build AI systems — agents, RAG pipelines, recommenders — and then build the evaluation
harnesses that tell me whether they actually work. Most of my recent projects ship with a
scoring suite attached, because a demo that looks right and a system that *is* right are
different claims.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 💼 Experience

**Software Engineering Intern — Sony Interactive Entertainment (PlayStation)** · Sep–Dec 2025
- Built an AI QA assistant on **MCP architecture** connecting 7 dev tools (Jira, Jenkins, GitHub, Slack, Confluence, Postman, qTest) — real-time Slack alerts and automated failure diagnosis, **adopted by 30+ teams** after a company-wide QA forum presentation.
- Raised regression and functional coverage **40%** across core PlayStation Store services with Python/JavaScript/React API and UI suites, extending into edge-case and accessibility scenarios.
- Owned nightly regression runs across 5 cross-functional teams, triaging failures to keep daily builds unblocked.

**Full-Stack Development Intern — Interactive Brokers** · Jun–Aug 2025
- Shipped compliance tooling in **Python, Django, Vue.js** with pytest/Django TestCase coverage, letting **50+ compliance officers** self-serve account queries instead of queueing on engineering.
- Cut query turnaround **70%** and report generation **5×** by automating workflows that previously required developer intervention.
- Architected two backend microservices — query and report-generation — so ad hoc lookups and scheduled reports scale independently.

---

## 🚀 Featured Projects

### [311derful](https://github.com/ishitakapoor7/311derful) · *NYC Hackathon (NYPL) — main track + Best Use of NYC Open Data*
Reparses `resolution_description` across **22,145,244 NYC 311 records** to convert a complaint-*volume*
dataset into a service-*effectiveness* one. The finding: closing a complaint isn't fixing it — only
**24% of HPD plumbing complaints** end with the problem actually addressed. Classifier coverage is
reported per year (92.9–94.4%), never as a single average that could hide a collapse.
`Python` `FastAPI` `React` `Docker`

### [interview-prep-agent](https://github.com/ishitakapoor7/interview-prep-agent)
An agentic prep tool: parallel multi-source company research, one bounded reflect-and-refine round,
schema-enforced generation of a 7-module lesson plan, then RAG-grounded Q&A that never re-searches.
Ships with an offline eval using **deterministic scoring and three-way failure attribution**
(research / synthesis / extraction) — **no LLM-as-judge anywhere** in the scoring path.
`Python` `FastAPI` `Anthropic API` `React` `SQLite`

### [decimal-careers](https://github.com/ishitakapoor7/decimal-careers)
A career site where uploading a résumé re-ranks open roles: semantic retrieval over a shared
384-dim space plus a **calibrated, explainable fit layer** that applies downgrade-only penalties
and states its reasons in plain language. Every factor fails open — an unreadable signal costs nothing.
`Python` `FastAPI` `React` `FAISS` `Transformers`

### [NOMinate](https://github.com/ishitakapoor7/NOMinate-cheesehacks) · *CheeseHacks*
One dish a day, nominated for you. Hybrid collaborative-filtering + content-based recommender trained
on **42.8K real Food.com ratings** (3,781 users, 3,370 dishes, 24 cuisines), with embeddings
precomputed so the full catalog scores in **~25 ms**. Trained in PyTorch, served in NumPy.
[**Live demo →**](https://nominate-web.onrender.com)
`PyTorch` `Flask` `React` `PostgreSQL`

---

## 🧰 Tech

**Languages** · Java (Spring Boot, JUnit) · Python · TypeScript · JavaScript · SQL · R · C
**Frameworks** · React · Node.js · FastAPI · Flask · Django · Vue.js · LangChain · PyTorch · scikit-learn
**AI/ML** · MCP Servers · LangGraph · LlamaIndex · RAG · FAISS · Whisper · RAGAS
**Infrastructure** · AWS · GCP · Docker · PostgreSQL · DynamoDB · CI/CD · Microservices

---

## 🎓 Also

Dean's List ×3 · Secretary of **Girls Who Code** · AI Club · Google Developer Club · CheeseHacks
Undergraduate TA for MATH 221/222/234, and an academic mentor across DSA, linear algebra, and other STEM subjects.

---

## 📫 Reach me

[![Email](https://img.shields.io/badge/Email-ishita.kapoor0712@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ishita.kapoor0712@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ishita--kapoor1-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishita-kapoor1)
