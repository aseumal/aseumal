<h1 align="center">Anthony Seumal</h1>
<p align="center">
  <em>AI Engineer · Data Scientist · PhD Scholar in Data Science (AIM)</em>
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/anthonyseumal"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/aseumal"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

---

## About Me

AI engineer and data scientist building production-grade agentic systems and the governance infrastructure to run them responsibly. Currently a PhD Scholar in Data Science at the **Asian Institute of Management** (also MSDS graduate) and focused on multi-agent AI architecture, observability, and enterprise AI deployment.

I build across the full stack — from LangGraph supervisor pipelines and RAG retrieval systems to FastAPI backends and React dashboards — with a strong emphasis on code quality, testability, and enterprise patterns.

---

## 🤖 AI Portfolio Arc

A deliberate multi-framework series demonstrating production-grade agent engineering across different paradigms:

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>🛡️ <a href="https://github.com/aseumal/Aegis-AgentOps">Aegis AgentOps</a></h3>
      <p><strong>AI Governance & Observability Platform</strong></p>
      <p>Enterprise-grade platform that monitors, evaluates, and governs AI agents in production. Auto-scores every agent run across 8 quality dimensions, detects 10 guardrail violation patterns, and routes high-stakes decisions to a human approval queue.</p>
      <p>🔗 <strong>Live integration with CoreAssist AI</strong> — real LangGraph agent runs appear in Aegis in real time via a zero-overhead background bridge.</p>
      <p><strong>Stack:</strong> Python 3.11 · FastAPI · SQLAlchemy 2.0 · Pydantic v2 · React 18 · TypeScript · Tailwind CSS · Recharts</p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB"/>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>📚 <a href="https://github.com/aseumal/CoreAssist-v2">CoreAssist AI</a></h3>
      <p><strong>LangGraph Multi-Agent Customer Support System</strong></p>
      <p>Production customer support agent for Cambridge University Press & Assessment. Uses a supervisor-routed pipeline with three specialist agents: Knowledge (FAISS+BM25 hybrid RAG + Cohere Rerank), Account (Text-to-SQL), and Escalation (ticket management). Includes a 3-layer output guard.</p>
      <p>🔗 <strong>Monitored live by Aegis</strong> — every run is auto-scored and guardrail-checked.</p>
      <p><strong>Stack:</strong> Python · LangGraph · Claude (Bedrock / Anthropic API) · FAISS · BM25 · Cohere · SQLite · Streamlit</p>
      <p>
        <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white"/>
        <img src="https://img.shields.io/badge/Claude-D97706?style=flat&logo=anthropic&logoColor=white"/>
        <img src="https://img.shields.io/badge/RAG-6366F1?style=flat&logoColor=white"/>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>🔬 <a href="https://github.com/aseumal/qualityguard">QualityGuard AI</a></h3>
      <p><strong>CrewAI Hierarchical Crew for AI Test Prioritization</strong></p>
      <p>Multi-agent system using a hierarchical CrewAI crew to automate software test prioritization using the VRTQ (Value, Risk, Time, Quality) framework. A manager agent delegates to specialist sub-agents for risk scoring, coverage analysis, and prioritization decisions.</p>
      <p><strong>Stack:</strong> Python · CrewAI · Claude · VRTQ Framework · FastAPI</p>
      <p>
        <img src="https://img.shields.io/badge/CrewAI-F97316?style=flat&logoColor=white"/>
        <img src="https://img.shields.io/badge/Claude-D97706?style=flat&logo=anthropic&logoColor=white"/>
        <img src="https://img.shields.io/badge/Multi--Agent-8B5CF6?style=flat&logoColor=white"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="100%" valign="top">
      <h3>🧪 <a href="https://github.com/aseumal/vrtq-rl">VRTQ-RL</a></h3>
      <p><strong>Reinforcement Learning for Test Prioritization, with Genuine Multi-Agent Negotiation</strong></p>
      <p>Extends the VRTQ framework (the same one powering QualityGuard AI) with PPO reinforcement learning. First training run scored <em>worse than random</em> on fault detection — root-caused to four distinct issues (train/eval data leakage, reward-objective misalignment, missing action masking, undertraining), fixed each, and validated honestly across a 5-seed evaluation sweep rather than reporting one lucky run. Adds an opt-in AutoGen layer where a Supervisor agent and a Critic agent genuinely negotiate over real tool calls — the Critic can trigger an actual re-run with different parameters, not just generate more chat text.</p>
      <p>🔗 <strong>Extends QualityGuard AI's VRTQ framework</strong> — same heuristic, now with a learned RL policy and real multi-agent negotiation layered on top.</p>
      <p><strong>Stack:</strong> Python · Gymnasium · Stable-Baselines3 + sb3-contrib (MaskablePPO) · AutoGen · FastAPI · React · MLflow</p>
      <p>
        <img src="https://img.shields.io/badge/Reinforcement%20Learning-7C3AED?style=flat&logoColor=white"/>
        <img src="https://img.shields.io/badge/AutoGen-2563EB?style=flat&logoColor=white"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB"/>
      </p>
    </td>
  </tr>
</table>

---

## 🛠️ Other Projects

<table>
  <tr>
    <td width="50%">
      <h4>🏪 ShelfFlow</h4>
      <p>Full-stack inventory and shelf management app built with Next.js 16 + React 19. The capstone of my 100-Day Claude Code Challenge.</p>
      <p><strong>Stack:</strong> Next.js · TypeScript · Tailwind · Prisma · PostgreSQL</p>
    </td>
    <td width="50%">
      <h4>📈 California Housing ML Dashboard</h4>
      <p>End-to-end ML pipeline with XGBoost, SHAP explanations, and a six-model comparison — delivered as an interactive dashboard.</p>
      <p><strong>Stack:</strong> Python · XGBoost · SHAP · Scikit-learn · React</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4>🔍 Explainable AI — MSDS Analysis</h4>
      <p>ML analysis on student performance data using Gradient Boosting and DiCE counterfactual explanations with full XAI findings.</p>
      <p><strong>Stack:</strong> Python · DiCE · SHAP · Gradient Boosting</p>
    </td>
    <td width="50%">
      <h4>🎓 Student Risk Prediction</h4>
      <p>ML-driven student analytics identifying high-risk students for academic advisors with actionable per-student insights.</p>
      <p><strong>Stack:</strong> Python · Pandas · Scikit-learn · Gradient Boosting</p>
    </td>
  </tr>
</table>

---

## Tech Stack

<p align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**AI & Agent Frameworks**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-F97316?style=for-the-badge&logoColor=white)
![AutoGen](https://img.shields.io/badge/AutoGen-2563EB?style=for-the-badge&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude%20API-D97706?style=for-the-badge&logo=anthropic&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

**Backend & Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**ML & Data Science**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-7C3AED?style=for-the-badge&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0A7E8C?style=for-the-badge&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aseumal&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aseumal&layout=compact&theme=default&hide_border=true" alt="Top Languages" height="165"/>
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aseumal&theme=default&hide_border=true" alt="GitHub Streak"/>
</p>

---

## Currently

- 🧪 Shipped **VRTQ-RL** — RL + genuine multi-agent negotiation for test prioritization (targeting STVR / JSS / IST)
- 🛡️ Extending **Aegis** to support multi-agent governance across the full portfolio arc
- 🎓 PhD Scholar in Data Science · Asian Institute of Management (MSDS)
- 📝 Building in public on LinkedIn

---

<p align="center">
  <em>"Building AI systems that are not just powerful — but observable, governable, and trustworthy."</em>
</p>
