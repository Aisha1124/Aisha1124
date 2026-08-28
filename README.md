<h1 align="center">Hi, I'm Aisha Siddiqua 👋</h1>
<h3 align="center">Agentic AI Engineer | Multi-Agent Systems | MCP | OpenAI SDK</h3>

<p align="center">
  <a href="https://linkedin.com/in/aisha-siddiqua-1b01a9268">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:aishasiddiqua1124@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

### 👩‍💻 About Me
- 🤖 Building **production-grade multi-agent systems** using OpenAI SDK & MCP
- 📚 Currently working on an **AI Native Book** & **AI Employee System**
- 🎓 Trained **2,000+ students** in AI engineering at GIAIC, Karachi
- 🏆 Certified in **Anthropic MCP** (Basic & Advanced) + **Agentic AI Development**
- 🌍 Seeking AI Engineering roles in **UAE · KSA · Qatar**
- ⚡ Fun fact: I build AI agents that actually work in production!

---

### 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_SDK-412991?style=for-the-badge&logo=openai&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

---

### 🏆 Featured Project: ResolveAI

**AI complaint-service agent for retail digital banking** — built solo for a national banking innovation hackathon (Team H15, AI in Banking theme).

Takes voice and text intake in Roman Urdu and English, asks one clarifying question, classifies the complaint, routes it deterministically to a department, and issues a case number. In a later session, it recalls the case and reports status straight from the database — no case number needed from the customer.

> ⚠️ *Independent prototype built against a mock banking core. Not affiliated with, endorsed by, or connected to any bank; touches no production system or real customer data.*

**Key design decisions:**
- 🧭 **LLM classifies, a lookup table routes** — classification is the model's job, but category → department mapping is a dictionary, so routing stays deterministic and auditable
- 🔒 **One mutator for status** — every status change writes the case update and its event-log row in the same transaction, so a case can never have a status without a matching timeline entry
- 🚫 **Zero money-movement tools by design** — the agent can only state facts returned by its tools; it cannot transfer, refund, reverse, or block anything
- 🔁 **Cross-session recall via pgvector** — returning customers are matched against stored case embeddings in the database, not chat history, so recall works even in a brand-new session

**Tech:** Python 3.11 · FastAPI · OpenAI Agents SDK (GPT-4o) · Whisper STT + OpenAI TTS · text-embedding-3-small + pgvector · PostgreSQL (Neon) · Vanilla JS + Tailwind

🔗 [View Repository](https://github.com/Aisha1124/ResolveAI)

---

### 🚀 Other Projects

| Project | Description | Tech |
|---|---|---|
| [AI Employee System](https://github.com/Aisha1124/Ai-employe-Bronze-tier) | Autonomous AI employee for task automation | Python |
| [Shopping Agent](https://github.com/Aisha1124/Shopping_Agent) | Intelligent shopping assistant with CrewAI | CrewAI, Python |
| [Orchestration System](https://github.com/Aisha1124/Orchestration_Management_System) | Multi-agent orchestration management | Python |

---
