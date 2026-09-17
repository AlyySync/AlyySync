<div align="center">

# ALI JAVED

### AI & Automation Engineer

**AI agents · Business automation · API integrations · Data pipelines**

I build automation systems that connect business operations, live data, and AI—from the first customer interaction to the final payment.

**Bahawalpur, Pakistan** · **Currently at Algotix.ai**

[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alyyworkflow@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ali_Javed-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/ali-javed-0823873a4/)
[![GitHub](https://img.shields.io/badge/GitHub-AlyySync-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlyySync)

</div>

---

## ⚡ Engineering impact

| Production delivery | Data processing | Field operations |
| :---: | :---: | :---: |
| **12+ systems delivered** | **100K+ records per day** | **1,000–2,000 technicians** |
| Automation and AI systems across HVAC, e-commerce, marketing, and field service | Outbound email data processing with deduplication and verification | AI routing and photo-validation workflows for field operations |

## 👨‍💻 About me

I'm an AI & Automation Engineer who designs, deploys, and maintains production automation systems using **n8n, Python, Go, and JavaScript**. My work covers lead intake, CRM, invoicing, customer support, outbound email, and AI content production.

I connect **OpenAI GPT-4o, Google Gemini, Supabase, Twilio, WhatsApp, and REST APIs** into workflows that handle real business processes. I own the full delivery cycle: requirements, architecture, integrations, deployment, monitoring, and documentation.

- **AI systems:** Multi-agent pipelines, retrieval-augmented generation (RAG), intent classification, and human-in-the-loop support.
- **Business operations:** Lead-to-payment workflows, service scheduling, invoicing, and customer communication.
- **Data workflows:** Web scraping, AI extraction, ETL, deduplication, and email verification at scale.
- **Production reliability:** Retry logic, error alerts, confidence gates, race-condition checks, and deterministic escalation.

## 🧰 Technology stack

<div align="center">

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

| Area | Tools & capabilities |
| :--- | :--- |
| **Automation platforms** | n8n, Make.com, Zapier, GoHighLevel, workflow automation, business process automation |
| **Programming & APIs** | Python, Go (Golang), JavaScript, Node.js, React, SQL, JSON, REST APIs, webhooks |
| **AI & LLMs** | OpenAI GPT-4o, Google Gemini, AI agents, multi-agent systems, LangChain, RAG, prompt engineering |
| **Retrieval & media AI** | Supabase pgvector, vector databases, AWS Rekognition, text-to-speech, sentiment analysis |
| **Data & infrastructure** | Supabase, PostgreSQL, Google Sheets, Docker, Git, GitHub, data pipelines, ETL |
| **Scraping & extraction** | Bright Data, Apify, AI-assisted extraction, LangChain workflows |
| **Messaging & support** | Twilio, WhatsApp Business API, Telegram, Slack, Gmail, Gorgias |
| **Commerce & operations** | Shopify, Stripe, QuickBooks, FedEx, Floship, ClickUp |
| **Content & distribution** | Meta / Facebook Ads API, YouTube, TikTok, LinkedIn APIs, FFmpeg |
| **Engineering practices** | System architecture, API integration, error handling, monitoring, email deliverability, technical documentation, client communication |

## 🚀 Featured projects

### 01 · AI Customer Support Agent for E-commerce

**A multi-agent support pipeline grounded in company knowledge and live order data.**

Built a system that reads Gorgias tickets, classifies intent, plans the query, retrieves SOPs and knowledge-base facts, and drafts on-brand responses. The workflow handles order, delivery, return, and refund queries with human escalation where needed.

- Orchestrated an **intent classifier → query planner → retrieval → writer agent** pipeline.
- Used **Supabase vector search and RAG** to retrieve relevant support knowledge.
- Integrated **Shopify, FedEx, and Floship** to retrieve live order, shipment, and warehouse status.
- Handled return-to-shipper events, delivery exceptions, pre-orders, and multi-package orders.
- Added confidence-gated auto-replies, ClickUp escalation, auto-tagging, and internal notes.
- Checked for new customer messages before replying and used deterministic escalation for carrier exceptions.

**Stack:** `n8n` · `OpenAI GPT` · `LangChain Agents` · `Supabase / pgvector` · `Gorgias` · `Shopify` · `FedEx` · `Floship` · `ClickUp`

---

### 02 · Kept Cold — HVAC Business Automation

**An end-to-end service workflow from lead intake to payment.**

- Automated lead intake, job creation, and engineer assignment.
- Connected real-time job status updates with customer communication.
- Implemented automatic pricing and PDF invoice generation.
- Automated email and WhatsApp payment reminders with Stripe / QuickBooks integrations.

**Workflow:** Lead intake → Job creation → Engineer assignment → Status updates → Pricing → Invoice → Payment reminders

**Stack:** `n8n` · `Supabase` · `AI Call Assistant` · `Gmail` · `WhatsApp` · `Stripe` · `QuickBooks`

---

### 03 · Audience Lab — Scalable Outbound Email Automation

**An outbound email system processing 100K+ records per day.**

- Built data processing workflows with deduplication and email verification.
- Integrated NeverBounce and ZeroBounce into the verification process.
- Implemented progressive sending ramp-up to support deliverability and protect domain reputation.
- Connected Supabase and webhook-driven workflows to coordinate the outbound pipeline.

**Stack:** `n8n` · `Supabase` · `Webhooks` · `NeverBounce` · `ZeroBounce`

---

### 04 · Dr. Leo — AI-Powered HVAC Field Operations

**AI-assisted quality checks and job routing for operations involving 1,000–2,000 technicians.**

- Used AWS Rekognition to validate technician photos and flag incomplete work, damage, and safety risks.
- Implemented AI job routing based on proximity, skill, and workload.
- Connected operational workflows to a Slack management hub.

**Stack:** `n8n` · `AWS Rekognition` · `Slack`

## 🛠️ More systems I've built

| System | What it does |
| :--- | :--- |
| **AI content production** | Connects script, image, voice, and video generation with publishing through YouTube, Meta, TikTok, and LinkedIn APIs using GPT-4o, TTS, and FFmpeg. |
| **Newsletter automation** | Generates, schedules, and distributes content with approval and tracking steps. |
| **Web scraping & AI extraction** | Processes hundreds of websites per run using Bright Data, Apify, and LangChain, with retries and error alerts. |

## 💼 Professional experience

### AI & Automation Engineer · Algotix.ai

**May 2026 – Present**

- Design, build, and deploy AI-driven client workflows using n8n, Python, Go, and JavaScript, including complex JSON handling and third-party API integrations.
- Build and maintain a multi-agent e-commerce support system for order, delivery, return, and refund queries with human-in-the-loop escalation.
- Develop newsletter automation with content generation, scheduling, distribution, approvals, and tracking.
- Translate client requirements into workflow architectures with error handling, monitoring, alerting, and documentation.

### Freelance AI & Automation Engineer · Self-Employed

**May 2025 – April 2026**

- Delivered **12+ production-ready automation and AI systems** for HVAC, e-commerce, marketing, and field-service clients.
- Owned architecture, integrations, and deployment end to end.
- Built AI content pipelines covering scripts, images, voice, video, and multi-platform publishing.
- Developed web scraping and AI extraction workflows scalable to hundreds of websites per run, with retry and error-alert logic.

## 🧭 How I approach a build

1. **Map the business process.** Understand inputs, decisions, handoffs, and the result the team needs.
2. **Design the workflow.** Define the data model, API integrations, agent responsibilities, and escalation paths.
3. **Build for real conditions.** Account for missing data, failed requests, duplicate events, and changing customer context.
4. **Keep people in control.** Use approvals, confidence gates, and human escalation where judgment matters.
5. **Make it maintainable.** Add monitoring, alerts, and documentation so the system can be operated after deployment.

## 🎓 Education

**Intermediate in Computer Science (ICS)**  
Punjab Group of Colleges (PGC), Bahawalpur

## 🐍 My contributions in motion

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AlyySync/AlyySync/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AlyySync/AlyySync/output/github-snake.svg" />
  <img alt="Snake animation eating Ali Javed's GitHub contributions" src="https://raw.githubusercontent.com/AlyySync/AlyySync/output/github-snake.svg" width="100%" />
</picture>

*Refreshed daily with GitHub Actions.*

---

<div align="center">

## 🤝 Let's connect

**AI agents · Business workflow automation · API integrations · Data pipelines**

[alyyworkflow@gmail.com](mailto:alyyworkflow@gmail.com) · [LinkedIn](https://www.linkedin.com/in/ali-javed-0823873a4/)  
**Phone:** +92 300 0088758 · **Location:** Bahawalpur, Pakistan

</div>
