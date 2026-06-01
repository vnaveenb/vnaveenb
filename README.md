<h1 align="center">Venkata Naveen Busiraju</h1>

<p align="center">
<b>Gen AI Application Developer · 5.5 Years · GCP & AWS Certified</b><br>
LangChain · LangGraph · FastAPI · Python · Docker · GCP · AWS
</p>

<p align="center">
<a href="https://linkedin.com/in/naveenbusiraju/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
<a href="mailto:naveenbusiraju@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>&nbsp;
<a href="https://github.com/naveenbusiraju" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

## About Me

Gen AI Developer with **5.5 years of experience** building LLM systems that go to production — not just proof-of-concepts. Currently at **Atos**, where I've shipped enterprise RAG pipelines, multi-agent workflows, and document-AI systems with measurable business outcomes.

Full-stack background (Java, Spring Boot, Node.js, Angular) means I own end-to-end delivery, not just the AI layer. Cloud-native from day one: **Google Cloud Certified (2021)** and **AWS DevOps Professional (2025)**.

---

## Work Experience

### Atos — Gen AI Application Developer &nbsp; <small>`Dec 2023 – Present`</small>
> Enterprise AI: long-context RAG, multi-agent orchestration, document-AI pipelines on GCP & AWS

- **65% reduction** in document review time — Long-context RAG (Azure OpenAI GPT-4 + LangChain + LangGraph) analysing course materials (PDF, DOCX, PPTX, XLSX) against compliance checklists, auto-reporting to SharePoint
- **55% reduction** in AR resolution time — LLM-powered email agent classifying, extracting, and validating invoice data from unstructured emails and attachments
- **96% field-level accuracy** — invoice-understanding pipeline (pdfplumber + pytesseract + Llama-3 prompting + agent validation), producing ERP-ready JSON
- Multi-agent orchestration with **LangGraph + MCP**: retrieval agent, checklist agent, review agent, and orchestrator with schema enforcement and fault tolerance

**Stack:** `Azure OpenAI` `LangChain` `LangGraph` `MCP` `FastAPI` `Docker` `Kubernetes` `GitHub Actions` `GCP` `AWS`

### Atos — Associate Consultant &nbsp; <small>`Nov 2019 – Jan 2022`</small>
> Cloud-native development, CI/CD, microservices, and GCP infrastructure

- Led CI/CD implementation with GitHub Actions, Docker, and Kubernetes across GCP
- Migrated legacy projects to Angular and Node.js, integrating GCP services for performance gains
- Deployed and managed Dockerized microservices on GCP; contributed to the Decarbonization Project with Java Spring Boot

**Stack:** `Java` `Spring Boot` `Node.js` `Angular` `Docker` `Kubernetes` `GCP`

---

## GenAI Portfolio

Six production-pattern LLM systems — each solving a problem that actually breaks in real deployments.

<table>
<tr>
<td width="50%">

### 💬 [Multi-Provider Chat Core](https://github.com/naveenbusiraju/project-1-multi-provider-chat)
The provider is a **runtime env var, not a code dependency** — swap Gemini, GPT-4o, Claude, or Bedrock with zero code changes. Real-time SSE streaming, Redis-backed conversation memory, function calling, and automatic provider fallback.

`FastAPI` `LangChain` `Redis` `LangSmith` `Docker`

</td>
<td width="50%">

### 🔍 [RAG App with Evaluations](https://github.com/naveenbusiraju/rag-app-with-evaluations)
Most RAG demos stop at "it works." This one **measures how well it works** — RAGAS metrics (Faithfulness, Answer Relevancy, Context Precision, Context Recall) baked in. Local embeddings, LLMs hot-swappable via one config line.

`FastAPI` `ChromaDB` `LiteLLM` `RAGAS` `sentence-transformers`

</td>
</tr>
<tr>
<td width="50%">

### 🤖 [Agent with Tool Calls + Retries](https://github.com/naveenbusiraju/agent-tool-calls-retries)
Production agents need **audit trails**. ReAct loop with exponential backoff retries, errors fed back as context for LLM recovery, and a full JSON execution trace saved for every run. 31 tests passing.

`FastAPI` `LiteLLM` `function calling`

</td>
<td width="50%">

### 📊 [Token + Cost Budget Dashboard](https://github.com/naveenbusiraju/token-cost-budget-dashboard)
LLM apps **leak money silently**. Per-request token logging with exact costs, real-time dashboards by endpoint/model/user, hard 429 budget enforcement before limits are hit — not after. 40 tests passing.

`FastAPI` `SQLite` `LiteLLM` `live dashboard`

</td>
</tr>
<tr>
<td width="50%">

### ⚡ [Async Inference Queue](https://github.com/naveenbusiraju/async-inference-queue)
100 users, 10-second LLM calls — **you can't hold HTTP connections open that long**. Redis-backed priority job queue, Dead Letter Queue for failed jobs, bounded worker concurrency, real-time monitoring. 36 tests passing.

`FastAPI` `Redis` `Docker Compose` `LiteLLM`

</td>
<td width="50%">

### 🔀 [Model Fallback Router](https://github.com/naveenbusiraju/model-fallback-router)
Provider outages and rate limits shouldn't take your system down. **Circuit breaker** with auto-recovery, three routing strategies (priority / round-robin / latency-weighted), p50/p95/p99 SLA tracking. 36 tests passing.

`FastAPI` `LiteLLM` `Docker Compose` `SQLite`

</td>
</tr>
</table>

---

## Also Built

<table>
<tr>
<td width="50%">

### 🌱 [Carbon Calculator Platform](https://github.com/naveenbusiraju/carbon-calculator-platform)
Role-based web app for laptop lifecycle carbon analysis — vendors upload emission profiles, admins manage regional emission factors, users estimate and compare device impact. Dockerized with GitHub Actions CI.

`Node.js` `Express` `MySQL` `Docker` `GitHub Actions`

</td>
<td width="50%">

### 📋 [ClipboardHistory for macOS](https://github.com/naveenbusiraju/clipboard-history-macos)
Native macOS clipboard manager — like Windows Win+V, built with SwiftUI. Global hotkey (⌘⇧V), floating panel, instant search, pinned items, type detection. Persistent across restarts. No network access.

`SwiftUI` `macOS 13+` `Carbon APIs`

</td>
</tr>
</table>

---

## Tech Stack

#### AI / ML
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-6B21A8?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-DC2626?style=flat-square)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

#### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

#### Frameworks & APIs
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

#### Infrastructure & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

#### Cloud
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

## Certifications

| Certification | Issuer | Year |
|---|---|---|
| AWS Certified DevOps Engineer – Professional | Amazon Web Services | 2025 |
| Associate Cloud Engineer | Google Cloud | 2021 · ID: ZVW1QW |

---

## Education

| Degree | Institution | Year |
|---|---|---|
| MSc Computer Science | University of East London | 2022 – 2024 |
| BTech Computer Science & Engineering | Gudlavalleru Engineering College | 2015 – 2019 |

---

## GitHub Insights

<p align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=naveenbusiraju&theme=vue" alt="GitHub Profile Summary" />
</p>

<p align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=naveenbusiraju&theme=vue" width="320" alt="GitHub Stats" />&nbsp;
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=naveenbusiraju&theme=vue" width="320" alt="Top Languages" />
</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=naveenbusiraju&theme=vue&hide_border=true" alt="GitHub Streak" />
</p>

---

<p align="center">
<em>"Ship systems that measure themselves. Everything else is a demo."</em>
</p>
