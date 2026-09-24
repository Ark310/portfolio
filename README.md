<h1 align="center">👋 Hi, I'm Abdul Raqeeb Khatri</h1>

<p align="center">
<strong>IT Support & Systems · Automation Builder · AI & Developer Tools</strong>
</p>

<p align="center">
  <a href="mailto:abdulraqeebkhatri310@gmail.com"><img src="https://img.shields.io/badge/Email-abdulraqeebkhatri310@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/abdulraqeebkhatri"><img src="https://img.shields.io/badge/LinkedIn-abdulraqeebkhatri-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/Ark310"><img src="https://img.shields.io/badge/GitHub-Ark310-181717?style=flat-square&logo=github&logoColor=white"></a>
  <a href="certifications/"><img src="https://img.shields.io/badge/Certifications-View-success?style=flat-square&logo=googlescholar&logoColor=white"></a>
</p>

---

## 👨‍💻 About Me

I'm an **IT support, systems, and automation professional** with experience across enterprise technology, SaaS platforms, Apple environments, business systems, technical support, and workflow automation.

My work spans **macOS and Windows support, endpoint troubleshooting, SaaS administration, user access, MDM, ITSM and ticketing, networking, asset management, technical documentation, automation, AI-enabled tools, and system deployments**.

I enjoy solving problems methodically, learning unfamiliar technologies, and finding practical ways to make systems and processes more reliable. A large part of my work has involved translating technical concepts into clear guidance for users with different levels of technical experience.

Outside traditional IT support, I build tools that automate repetitive work, improve reporting, simplify knowledge access, and reduce manual processes.

---

## 🛠️ IT & Technical Skills

### IT Support & Endpoint Management

`Tier 1/2 Support`, `macOS`, `Windows 11`, `iOS`, `iPadOS`, `Hardware Troubleshooting`, `Software Troubleshooting`, `Remote Support`, `Onsite Support`, `Device Setup`, `Device Deployment`, `Account Support`, `MFA`, `Printers`, `Peripherals`, `POS`, `A/V Systems`

### SaaS, Identity & Access

`Google Workspace`, `Microsoft 365`, `Slack`, `Salesforce`, `CRM Platforms`, `Microsoft Entra ID / Azure AD`, `User Provisioning`, `User Deprovisioning`, `Role-Based Access`, `Permissions Management`, `MFA`, `Authentication`, `Licence & SaaS Access Management`

### ITSM & Service Operations

`JIRA`, `ServiceNow`, `ITSM`, `SLA Management`, `Ticket Triage`, `Incident Management`, `Service Requests`, `Escalation Management`, `Root-Cause Investigation`, `Technical Documentation`, `Knowledge Bases`, `SOPs`, `How-To Guides`, `UAT`

### Networking & Infrastructure

`Wi-Fi`, `Ethernet`, `TCP/IP`, `VPN`, `DNS`, `DHCP`, `Local Network Troubleshooting`, `Network Devices`, `VoIP`, `IT Asset Management`, `Laptop & Desktop Deployment`, `A/V Infrastructure`

### Endpoint Security & Compliance

`MDM`, `Device Enrollment`, `Configuration Profiles`, `Disk Encryption`, `OS Security Settings`, `Device Restrictions`, `Endpoint Security`, `Access Controls`, `Security Awareness`, `Audit-Ready Documentation`, `Privacy & Compliance Support`

---

## 🚀 Featured Projects

### [Knowledge Base Assistant](https://github.com/Ark310/knowledge-base-assistant): *Scrape → Index → Chat, fully local*

A Confluence and support-ticket scraper feeding a **hybrid-RAG desktop assistant**: ChromaDB vector search + BM25 with reciprocal-rank fusion, CrossEncoder reranking, **verified clickable citations**, PII-redacted ticket context, and a choice of Claude, ChatGPT or an **on-prem Ollama model** running on a local GPU. It grew over 361 commits, from a scraper to v3 "KB Guru", including a measured retrieval overhaul (recall@8 0.816 → 0.920).

`Python` · `Playwright` · `ChromaDB` · `BM25/RRF` · `CrossEncoder` · `PySide6` · `Claude` · `Ollama` · `pytest (791 passing)`

### [BLNS: Sanctions Screening RAG](https://github.com/Ark310/blns-sanctions-screening-rag): *local-GPU compliance AI*

An offline assistant that adjudicates sanctions-screening alerts and recommends **FLAG / REVIEW / CLEAR** with deterministic evidence, cited analyst precedents and a confidence score. The analyst always decides. It began as a **QLoRA fine-tuning prototype** (Qwen 2.5 3B/7B → GGUF → Ollama); after evaluation it was **re-architected as RAG** over past decisions, with OFAC-style Jaro-Winkler name scoring done in code. The [journey](https://github.com/Ark310/blns-sanctions-screening-rag/blob/main/docs/JOURNEY.md) is documented step by step.

`Python` · `Ollama (qwen3:8b, bge-m3)` · `ChromaDB` · `FastAPI` · `.NET 8` · `RTX 5060 Ti 8 GB` · `pytest (368 passing)`

---

## 🤖 Shipping with AI

Every project below was built with **Claude Code** as a pair programmer (some with Codex; the earliest scripts from January–May 2026 were drafted with ChatGPT). I set direction, specs and review; the AI accelerates implementation and tests. Every commit carries a `Co-Authored-By: Claude` trailer, and each repo's README has a **Built with AI** section with real numbers.

| | |
|---|---|
| 📦 **29 repositories** | 1,035 commits · Jan → Sep 2026 |
| ✅ **3,300+ passing tests** | pytest suites across the desktop apps |
| 🧭 **Real history** | original commit dates and messages kept; pre-git work rebuilt from file timestamps |
| 🔒 **Sanitized** | employer, client and colleague names, internal hosts, credentials and data removed from every commit |

---

## 🗂️ Project Gallery

### 🤖 AI & Developer Tools

| Project | What it does | Stack |
|---------|-------------|-------|
| [**blns-sanctions-screening-rag**](https://github.com/Ark310/blns-sanctions-screening-rag) | Offline FLAG/REVIEW/CLEAR adjudicator for sanctions-screening alerts: deterministic OFAC-style scoring + RAG over past analyst decisions on an 8 GB GPU; started as a fine-tuning prototype | Ollama (qwen3:8b, bge-m3) · ChromaDB · FastAPI · .NET |
| [**knowledge-base-assistant**](https://github.com/Ark310/knowledge-base-assistant) | Scraper → markdown library → hybrid-RAG chatbot with verified citations and an on-prem LLM option | Playwright · ChromaDB · BM25/RRF · PySide6 · Claude · Ollama |
| [**local-llm-setup**](https://github.com/Ark310/local-llm-setup) | Two local LLM stacks (a KYC analyst and the KB chatbot) on one 8 GB GPU, with a reasoning gateway | Ollama · PowerShell · Caddy |
| [**enhancement-spec-generator**](https://github.com/Ark310/enhancement-spec-generator) | `/spec` Claude Code plugin: brain dump in, validated specification `.docx` out | Claude Code Skills · python-docx · pytest |
| [**claude-sessions-tracker**](https://github.com/Ark310/claude-sessions-tracker) | Desktop dashboard for local Claude Code sessions: tokens, models, subagents, session management | CustomTkinter · Matplotlib · watchdog · SQLite |
| [**claude-session-tracker**](https://github.com/Ark310/claude-session-tracker) | Next.js web dashboard to browse, control & audit Claude Code sessions | Next.js · TypeScript · Tailwind · Vitest |
| [**codex-session-manager**](https://github.com/Ark310/codex-session-manager) | Tkinter monitor for local Codex sessions: processes, tokens, context-window use | Python · Tkinter |
| [**codex-skills**](https://github.com/Ark310/codex-skills) | Five Claude-style agent skills ported to Codex (feature dev, PR review, browser testing, data eng.) | Agent Skills · Markdown |
| [**claude-config-transfer**](https://github.com/Ark310/claude-config-transfer) | Export/import a full Claude Code setup (settings, skills, plugins) to another Windows machine, no secrets | PowerShell |
| [**claude-account-switcher**](https://github.com/Ark310/claude-account-switcher) 🍴 | Fork of usage-monitor-for-claude adding DPAPI-encrypted multi-account switching with rollback | Python · DPAPI · pytest |
| [**codex-usage-tray**](https://github.com/Ark310/codex-usage-tray) 🍴 | Port of usage-monitor-for-claude to Codex: tray monitor for 5-hour and weekly limits | Python · JSON-RPC · pystray |
| [**observatory**](https://github.com/Ark310/observatory) 🍴 | Fork with additional session tracking, session management, and startup scanning | Bun · TypeScript · xterm.js · CodeMirror |

### ⚙️ Desktop & Browser Automation

| Project | What it does | Stack |
|---------|-------------|-------|
| [**report-downloader**](https://github.com/Ark310/report-downloader) | One-click month-end PDF/Excel dashboard exports for ~30 clients, plus an auto-built billing CSV | Playwright · Tkinter · openpyxl · PyInstaller |
| [**incident-report-scraper**](https://github.com/Ark310/incident-report-scraper) | Scrapes a support portal's incidents into a living Excel + offline HTML dashboard with sentiment | Playwright · PySide6 · openpyxl · VADER |
| [**portal-account-deactivator**](https://github.com/Ark310/portal-account-deactivator) | Safe batch offboarding of portal accounts: preview, confirm gate, verification, audit trail | PySide6 · Playwright · keyring |
| [**mailing-list-builder**](https://github.com/Ark310/mailing-list-builder) | Mailing lists from the portal roster as saved rules + exceptions, one-click Outlook export | PySide6 · Playwright · keyring |
| [**ticket-watchlist-updater**](https://github.com/Ark310/ticket-watchlist-updater) | One-click sync of a live ticket export into a multi-sheet Excel watchlist (117 real runs) | Playwright · openpyxl · Tkinter |
| [**enhancement-checks-automation**](https://github.com/Ark310/enhancement-checks-automation) | Five-phase Selenium clean-up of 147 enhancement tickets with dry runs and audit trails | Selenium · pandas · Tkinter |
| [**ticket-auto-updater**](https://github.com/Ark310/ticket-auto-updater) | Chrome extension for one-click ticket-field updates | Chrome MV3 · Vanilla JS |
| [**tickets-due-response-monitor**](https://github.com/Ark310/tickets-due-response-monitor) | Daily queue monitor with threshold alerts via Power Automate Desktop (79 logged runs) | Playwright · pandas · PAD |

### 📊 Reporting & Analytics

| Project | What it does | Stack |
|---------|-------------|-------|
| [**weekly-time-reports**](https://github.com/Ark310/weekly-time-reports) | Weekly per-person hours report rebuilt from a portal; matched the legacy workbook 48/48 (783 tests) | PySide6 · Playwright · openpyxl · Outlook |
| [**resource-matrix**](https://github.com/Ark310/resource-matrix) | Monthly capacity, utilisation and sprint-load matrix, reconciled to the hour (510 tests) | PySide6 · Playwright · T-SQL |
| [**support-portal-dashboard-widgets**](https://github.com/Ark310/support-portal-dashboard-widgets) | SQL dashboard widgets (misclassification checks, SLA, open tickets) and the bugs behind the numbers | T-SQL · SQL Server |
| [**weekly-ticket-status-reporter**](https://github.com/Ark310/weekly-ticket-status-reporter) | Weekly backlog status workbook with week-over-week trends from a ticket export | pandas · openpyxl · Tkinter |
| [**average-days-in-status**](https://github.com/Ark310/average-days-in-status) | Time-in-status analytics (SQL) plus a batch ticket-to-PDF exporter | T-SQL · Playwright · CDP |
| [**office-automation-scripts**](https://github.com/Ark310/office-automation-scripts) | Weekly ticket-aging workbook and a daily due-response Teams reminder flow | pandas · Tkinter · Power Automate |

### 📚 Documentation & Specs

| Project | What it does | Stack |
|---------|-------------|-------|
| [**confluence-to-guide-converter**](https://github.com/Ark310/confluence-to-guide-converter) | Offline pipeline turning a flat Confluence KB into a structured ReadMe guide site | Python · YAML · rdme |
| [**workflow-spec-docs**](https://github.com/Ark310/workflow-spec-docs) | Functional specs for configurable project/category/status workflows (GitHub Pages) | HTML · CSS |

### 🖥️ Systems & Infrastructure

| Project | What it does | Stack |
|---------|-------------|-------|
| [**gcc-server-2019-installer**](https://github.com/Ark310/gcc-server-2019-installer) | Reverse-engineered a consumer utility's installer and device DB to run it on Windows Server 2019 | PowerShell · Python · SQLite |

### 🔐 Security

| Project | What it does | Stack |
|---------|-------------|-------|
| [**web-app-security-assessment**](https://github.com/Ark310/web-app-security-assessment) | OWASP WSTG-aligned methodology and templates (RoE, checklist, severity model, report) from an authorized staging assessment. The assessment itself stays confidential | OWASP WSTG · CVSS · OWASP ZAP |

### 🧪 Experimental

| Project | What it does | Outcome |
|---------|-------------|---------|
| [**monthly-reports-automation**](https://github.com/Ark310/monthly-reports-automation) | API-first attempt at report automation | Superseded by report-downloader; failed attempts kept as engineering notes |

### 🌐 Web

| Project | What it does | Stack |
|---------|-------------|-------|
| [**HeartGuard**](https://github.com/Ark310/HeartGuard) | Apple-inspired single-page site with inline admin editing | PHP · Vanilla JS |

---

## 📜 Certifications

Professional certifications and training across **Apple Support, Microsoft Azure, Cloud, Networking, Security, Automation, and AI**.

### Key Certifications

- 🍎 **Apple Certified Support Technician** — Apple
- 🟦 **Microsoft Certified: Azure Fundamentals (AZ-900)** — Microsoft
- 🔐 **Network Support and Security** — Cisco
- 🖥️ **IT Customer Support Basics** — Cisco
- 🟨 **IT Automation with Python** — Google

### Additional Training

- ☁️ **AWS** — AWS SimuLearn: Cloud Practitioner, Technical Essentials, EC2, S3, VPC, IAM, Lambda, and additional cloud training
- 🤖 **Anthropic** — Claude 101, Claude Code 101, Introduction to Claude Cowork
- 🔐 **Cisco** — Introduction to Cybersecurity and networking/security coursework
- 🎯 **Udemy** — Learn Ethical Hacking From Scratch

➡️ **[Browse the full certification gallery](certifications/)**

---

## ⚙️ Automation, Development & Data

### Languages

`Python`, `Java`, `JavaScript`, `TypeScript`, `SQL / T-SQL`, `C`, `C++`, `Bash`, `PHP`, `HTML/CSS`

### AI & Automation

`RAG Pipelines`, `Hybrid Retrieval (BM25/RRF)`, `Claude`, `Claude Code`, `Codex`, `Ollama / Local LLMs`, `ChromaDB`, `sentence-transformers`, `CrossEncoder Reranking`, `Prompt Engineering`, `Microsoft Copilot`, `Agentic Workflows`, `Playwright`, `Selenium`, `Chrome Extensions`, `Power Automate`

### Microsoft & Business Systems

`Power Automate`, `Power Platform`, `Microsoft Teams`, `Excel`, `Power BI`, `Microsoft 365`, `Azure`, `Entra ID`, `CRM`, `Salesforce`

### Web & Desktop Development

`Next.js`, `React`, `Spring`, `FastAPI`, `REST APIs`, `Tailwind`, `Bootstrap`, `PySide6`, `Tkinter`, `CustomTkinter`

### Data & Reporting

`pandas`, `NumPy`, `openpyxl`, `Matplotlib`, `Power BI`, `Advanced Excel`, `Dashboard Development`, `SQLite`, `MongoDB`

### Cloud & Infrastructure

`Microsoft Azure`, `AWS EC2`, `AWS S3`, `AWS VPC`, `AWS IAM`, `AWS Lambda`, `Docker`, `Git`, `Windows`, `macOS`, `Linux`

### Security & Governance

`NIST CSF 2.0`, `ISO 27002`, `Role-Based Access`, `Endpoint Security`, `Security Awareness`, `Audit Documentation`, `Ethical Hacking Fundamentals`, `Windows DPAPI`

---

## 💼 Professional IT Experience

My professional experience spans **technical support, enterprise systems, SaaS administration, endpoint support, user enablement, automation, and technology implementation** across corporate, higher-education, fintech, and Apple environments.

### Technical Support & User Enablement

Supported users across **macOS, Windows, iOS, and iPadOS**, resolving hardware, software, connectivity, account-access, authentication, device, and application issues while communicating technical information clearly to users with different levels of experience.

### IT Service Management

Worked within structured **JIRA, ITSM, SLA, incident, and escalation workflows**, managing high-volume service queues, documenting technical issues, tracking resolutions, and coordinating system-level escalations.

### SaaS & Identity Administration

Supported and administered enterprise platforms including **Google Workspace, Microsoft 365, Slack, Salesforce, CRM systems, and Microsoft Entra ID**, with experience across user provisioning, deprovisioning, permissions, access management, MFA, and role-based access.

### Endpoint & Device Management

Configured, deployed, supported, and troubleshot **Mac, Windows, iPhone, and iPad devices**, including MDM-managed endpoints, configuration profiles, account enrollment, security settings, hardware, peripherals, and device lifecycle support.

### Systems & Infrastructure

Supported **enterprise systems, local networking, Wi-Fi, VoIP, A/V technology, printers, peripherals, laptops, desktops, and IT assets**, including deployment, troubleshooting, documentation, and escalation.

### Technology Deployments

Participated in and coordinated technology implementations involving **requirements gathering, configuration, deployment, UAT, documentation, stakeholder communication, user training, and ongoing process improvement**.

### Automation & Process Improvement

Built **Power Automate workflows, Slack integrations, reporting tools, ticket automations, dashboards, AI systems, and internal utilities** designed to reduce repetitive work, improve visibility, and make operational processes more efficient.

### Documentation & Training

Created **SOPs, knowledge-base articles, technical guides, presentations, training materials, and user documentation**, with a focus on making complex technologies accessible and easier to adopt.

### Security & Compliance

Worked within security-conscious environments involving **role-based access, MFA, MDM, endpoint security, privacy procedures, documentation requirements, and compliance-focused technology operations**.

---

## 🔧 Selected Professional Work

### 🤖 AI & Internal Knowledge Systems

Designed and deployed AI-assisted internal tools, including local AI infrastructure and RAG-based knowledge solutions intended to make organizational information easier to retrieve while supporting privacy-conscious use cases.

`AI` · `RAG` · `Python` · `Knowledge Management` · `Automation`

### ⚡ Workflow Automation

Designed workflow automations for data collection, reporting, ticket management, file processing, notifications, and operational processes.

`Power Automate` · `Python` · `Playwright` · `Selenium` · `Slack` · `Microsoft Teams`

### 📊 Reporting & Operational Visibility

Built dashboards and reporting tools that standardize recurring reporting, surface priorities, analyze service activity, and support decision-making.

`Excel` · `Power BI` · `Python` · `pandas` · `openpyxl`

### 🖥️ Enterprise User Support

Supported hundreds of users across Windows and macOS environments while working with enterprise SaaS platforms, access management, endpoint troubleshooting, technical documentation, and escalation processes.

`macOS` · `Windows` · `SaaS` · `ITSM` · `MDM` · `Networking`

### 🚀 Enterprise Technology Rollouts

Supported technology implementations from initial requirements and configuration through testing, documentation, training, deployment, and ongoing support.

`UAT` · `SaaS` · `CRM` · `Deployment` · `Training` · `Documentation`

---

## 🔬 Learning Through Building

Technology has always been something I learn best by experimenting with it.

Outside of my professional work, I've built and worked with:

`3D Printing`, `Cura`, `Bambu Studio`, `Chitubox`, `Tinkercad`, `Arduino`, `ESP32`, `RFID`, `Electronic Prototyping`, `Custom Circuits`, `Soldering`, `Hardware Troubleshooting`, `DIY Technology Projects`

That same mindset influences how I approach IT:

**Understand the system, isolate the problem, test methodically, document the solution, and keep learning.**

---

## 🌱 Currently Developing

I'm continuing to expand my knowledge across:

`Systems Administration`, `macOS Enterprise Support`, `Endpoint Management`, `MDM`, `Microsoft Azure`, `Identity & Access Management`, `Networking`, `Cybersecurity`, `Automation & Scripting`, `AI-Enabled IT Operations`, `Enterprise SaaS Administration`, `IT Service Management`

I'm especially interested in opportunities where I can combine **hands-on support, systems administration, automation, security, and user enablement** while continuing to grow technically.

---

## 🧭 How I Work

> **Troubleshoot methodically. Document clearly. Automate where it makes sense. Explain technology without overcomplicating it. Take ownership through resolution. Stay curious. Keep learning.**

---

## 📫 Connect With Me

- **LinkedIn:** [linkedin.com/in/abdulraqeebkhatri](https://linkedin.com/in/abdulraqeebkhatri)
- **GitHub:** [github.com/Ark310](https://github.com/Ark310)
- **Email:** [abdulraqeebkhatri310@gmail.com](mailto:abdulraqeebkhatri310@gmail.com)

---

<p align="center">
<em>Built around real problems, practical solutions, and continuous learning.</em> ✨
</p>
