### 📧 Autonomous AI Email Triage & Dispatch 
> *Intelligent async LLM pipeline designed to automate enterprise ticket triage, successfully cutting ticket turnaround time by **60%**.*

**🔄 Architecture Flow:**<br>
`FastAPI Webhook` ➔ `Groq (Llama-3) Classifier` ➔ `PII Sanitization` ➔ `OpenAI Draft Gen` ➔ `Human-in-the-Loop` ➔ `Slack / Queue Dispatch`

**⚙️ Core Mechanics & Security:**
*   🧠 **Classification & Routing:** Rapid intent classification, entity extraction, and dynamic P1–P4 priority scoring.
*   🚀 **Automated Dispatch:** Intelligent queue routing with automated Slack escalation for high-priority tickets.
*   🛡️ **Resilience & Safety:** Built-in Groq-to-OpenAI model failover, active PII sanitization, and strict JSON-schema structured outputs.<br><br>

**🛠️ Tech Stack:**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Groq_API-F55036?style=flat-square"/> <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/> <img src="https://img.shields.io/badge/Agentic_AI-121212?style=flat-square"/>
