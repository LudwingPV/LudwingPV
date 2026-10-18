# Hey, I'm Ludwing

Technology Engineer at Patient Engine and independent developer from El Salvador.

I build the automation layer companies run on: AI classification, integrations, and workflows built on top of the tools teams already use, so they don't spend months adapting to something new. On my own time I design and ship web apps, mobile apps, and AI workers for clients.

## What I do now

### Patient Engine · Technology Engineer

I work as the company's technology wizard: I find the technology that best fits each team and make it run inside the tools they already use. I sit with the team, learn the process they have, and build the automation on top of it. Nobody has to learn new software, so adoption takes days, not months.

```mermaid
flowchart LR
    subgraph TOOLS[Tools the team already used]
        direction TB
        T1[Slack]
        T2[ClickUp]
        T3[GoHighLevel and Twilio]
        T4[Gmail and Google Sheets]
    end
    L{{Automation layer<br/>Zapier, Claude AI,<br/>custom Slack app, APIs}}
    subgraph SYSTEMS[Systems I built]
        direction TB
        S1[01 Tech Request Intake]
        S2[02 Marketing Ops Sync]
        S3[03 Operations Dashboard]
        S4[04 Telecom and A2P Compliance]
        S5[05 Funnel Remediation]
    end
    TOOLS --> L --> SYSTEMS
    classDef tool fill:#0c2d6b,stroke:#58a6ff,color:#e6edf3
    classDef layer fill:#2a1f47,stroke:#a371f7,color:#e6edf3
    classDef sys fill:#0f2e1c,stroke:#3fb950,color:#e6edf3
    class T1,T2,T3,T4 tool
    class L layer
    class S1,S2,S3,S4,S5 sys
```

| # | System | What it solved |
|---|---|---|
| 01 | [Tech Request Intake](https://github.com/LudwingPV/business-process-automation/tree/main/01-tech-request-intake-system) | Five fragile request channels replaced by one custom Slack app. Claude classifies each request against the SLA rulebook, creates the routed ClickUp task, and confirms back. Four legacy automations retired. |
| 02 | [Marketing Ops Sync](https://github.com/LudwingPV/business-process-automation/tree/main/02-marketing-ops-sync) | Geo-targeting updates that were copied by hand now sync from ClickUp to the reporting sheet, flagging missing data instead of overwriting good data. |
| 03 | [Operations Dashboard](https://github.com/LudwingPV/business-process-automation/tree/main/03-live-operations-dashboard) | Leadership went from no visibility to live completion rates, workload by assignee, and monthly KPIs. |
| 04 | [Telecom and A2P Compliance](https://github.com/LudwingPV/business-process-automation/tree/main/04-telecom-provisioning) | Caller ID conflicts fixed without service loss, local numbers provisioned, and A2P 10DLC status triaged into tasks and alerts. |
| 05 | [Funnel Remediation](https://github.com/LudwingPV/business-process-automation/tree/main/05-funnel-remediation) | Live campaign defects fixed at the root cause, and brand updates pushed account-wide from one templating variable. |

All flowcharts in one place: **[WORKFLOWS.md](https://github.com/LudwingPV/business-process-automation/blob/main/WORKFLOWS.md)**

**Before that, at Thoughtful AI (Smarter Technologies)**, I designed, deployed, and optimized AI workers that automated healthcare revenue cycle operations end to end: eligibility verification, claims processing, denial management, payment posting, and prior authorization across Medicare, Medicaid, and commercial payers, resolving up to 70% of RCM tasks.

## Where I've been

**Patient Engine** (2026 - Present): Technology Engineer. Business automation, AI classification pipelines, custom Slack apps, ClickUp, GoHighLevel, Twilio, Zapier, Claude.

**Thoughtful AI** (2024 - 2026): Customer Success Engineer bridging customers and engineering. End-to-end delivery and optimization of AI/RPA automation for US healthcare revenue cycles. Python, Robocorp, Selenium, OpenAI and Anthropic SDKs, OCR, API integrations, Jira.

**Dataprise, National Spine and Center** (2023 - 2024): IT Engineer II. Azure cloud security (Private Link, NSGs, Defender for Cloud), vulnerability management (Nessus, Splunk), Active Directory, Microsoft 365, Mimecast, endpoint management.

**Blackhawk Network** (2019 - 2023): Risk Analytics Analyst. Fraud pattern detection, Power BI dashboards for regulatory compliance and business performance.

**Telus El Salvador / Google** (2017 - 2019): Sales Development Technology. Enterprise retail client relationships, C-level presentations, Salesforce, Google Console sys-admin.

## Tech

**AI & Automation:** Claude (Anthropic), OpenAI / GPT, Gemini, Claude Code, Cursor, MCP servers, prompt engineering, AI workers, agentic workflows, RPA, OCR, Zapier, n8n

**Business Systems:** ClickUp, Slack apps (slash commands, shortcuts, Events API), GoHighLevel, Twilio, HubSpot, Salesforce, Google Sheets

**Mobile & Frontend:** React Native, Expo, TypeScript, Expo Router, EAS Build/Submit, HTML, CSS, JavaScript

**Backend & Data:** Supabase (Auth, Database, Edge Functions, Realtime), PostgreSQL, Python, Node.js, Deno, REST APIs

**Cloud & Infra:** Microsoft Azure, Vercel, Railway, Modal, Active Directory, Microsoft 365, Okta SSO, VMware, Hyper-V, PowerShell

**Security:** Nessus, Splunk, IBM QRadar, ELK/SIEM, Microsoft Defender, Kali Linux, Metasploit, Nmap, Wireshark, Snort, Fortinet

**Dev Tools:** Git, GitHub Actions, Vitest, VS Code, Power BI, Jira, ServiceNow, Figma

## Certifications

Google Project Management Professional (2025) | CISSP (ISC)2 (In Progress) | Digital Forensics DFMC+ (2024) | Ethical Hacking Zero to Hero (2024) | Mastering Windows Security (2024) | Google Data Analytics Professional (2024) | Microsoft Cybersecurity Analyst Professional (2024) | IBM Cybersecurity Fundamentals (2024) | Google Cybersecurity Professional (2023-2024) | Google IT Support Professional (2023)

## Projects

### ChordSight: Chord Analysis for Musicians

Web app that detects the chords of a song, plays them in sync with guitar diagrams, and separates the audio into stems so musicians can practice each part. Built for a music team that reviews and corrects chords; their corrections feed the training data for automatic detection.

- Synced chord player with guitar diagrams, transposition, and capo
- Stem separation with a per-track mixer (volume, solo, mute)
- Chord editor with root and quality selector, including add2 and add9 voicings
- Admin review workflow: suggestions, full-song review, and a correction log

**Tech:** TypeScript, Supabase (PostgreSQL), Railway (API and worker), Modal, Vercel

**Status:** In production, live at **[chordsight.vercel.app](https://chordsight.vercel.app)**

<p align="center">
  <img src="chordsight-showcase.png" width="800" alt="ChordSight screens" />
</p>

### CashFlow: Mobile Finance App

Built for salaried workers in El Salvador to manage money between paydays. Solo build, end to end: product, frontend, backend, and logic automation.

**Tech:** React Native, Expo, TypeScript, Supabase

<p align="center">
  <img src="cashflow-showcase.png" width="800" alt="CashFlow screens" />
</p>

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ludwing-pacas-55886b230/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:ludwing_pv@hotmail.com)
[![Credly](https://img.shields.io/badge/Credly-FF6B00?style=flat&logo=credly&logoColor=white)](https://www.credly.com/users/ludwing-pacas)
