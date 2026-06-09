---
layout: archive
title: "CV"
permalink: /cv-en/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Joy Liu (YUN-HSIN, LIU)
*Software Engineer | Applied AI | Azure | Django + ASP.NET*

📧 joy9517538246@gmail.com | 🔗 [LinkedIn](https://www.linkedin.com/in/yun-hsin-liu/?locale=en_US) | 🌐 [Blog](https://lovedrinkcafe.com)

---

## Professional Summary

Software engineer with a B.S. in Information Management and an M.S. in National Defense Cybersecurity Management. Spent three years as a software engineering officer in the ROC Air Force's communications branch, leading the design and delivery of 20+ enterprise MIS systems serving 30,000+ users at **99.9% availability**, and currently serve as a Senior Software Engineering Officer at the Ministry of National Defense, building geospatial data-visualization tooling.

Strong in backend development (C#/ASP.NET, Python/Django), full-stack architecture, and Azure cloud deployment with CI/CD. Independently built and operates a generative-AI SaaS platform (Django + React + Claude API). Master's thesis bridges academic research with production engineering through an offline-deployed LLM routing system.

Looking for software engineer roles — particularly interested in **enterprise software** and **applied AI**.

---

## Professional Experience

### Senior Software Engineering Officer
**Office of the Deputy Chief of the General Staff for Communications, Electronics and Information (ODCGS/CEI), General Staff Headquarters, Ministry of National Defense** | *Jan 2026 – Present*

- Develop internal **geospatial data-visualization tooling**, including a **Power BI custom visual** built in TypeScript + Leaflet.js — interactive maps with layered filtering, marker clustering, coverage-range rendering, fuzzy search (Fuse.js), and polygon/lasso region selection, packaged via the pbiviz toolchain.
- Engineer **Android (Java/Gradle)** plugins extending a geospatial situational-awareness platform (ATAK), working across AGP 8.13 / compileSdk 36 / JDK 17.
- Build a real-time **operational command-display** web application.
- Advise on software architecture and secure development practices across the office.

### Software Engineering Officer
**ROC Air Force (ROCAF) – Communications Information Wing, Technical Training Center** | *Jan 2022 – Dec 2025*

- Led the design and delivery of **20+ enterprise MIS systems** (ASP.NET MVC + MSSQL/Oracle) serving **30,000+ daily users** at **99.9% availability**.
- Independently developed core web applications (approval workflow, intranet portal, AD authentication module) end-to-end from front-end (Razor/JavaScript) to back-end (C#/SQL).
- Owned architecture review and tech-stack selection for new requirements; produced API specs, database schemas, security strategies, and technical feasibility reports for leadership.
- Integrated enterprise security (NetApp, Checkpoint, F5, VMware) at the application layer; performed **OWASP Top 10** code reviews and vulnerability remediation.
- Led an internal AI innovation initiative: evaluated LLM + RAG for an internal knowledge-management use case, delivered a working POC and an integration proposal.
- Planned and delivered cross-team training on ASP.NET, Web Forms, Oracle, MSSQL, PyTorch, CI/CD, Docker, and Git.

### Infrastructure Design Officer
**Republic of China Air Force (ROCAF) – Communications Technical Training Center** | *Jul 2021 – Dec 2021*

- Helped plan enterprise network infrastructure supporting 30,000+ users (NetApp StorageGRID, Checkpoint firewalls, F5 LB, VMware vCenter).
- Evaluated and integrated security products (ArcSight SIEM, Cisco IPS, PaloAlto WAF) into the network architecture, contributing to system availability improvement to **99.5%**.
- Produced system operating documentation and architecture assessment reports used by development teams for application-layer integration.

---

## Education

### M.S. in National Defense Cybersecurity Management
**National Yang Ming Chiao Tung University, [College of Computer Science](https://www.ccs.nycu.edu.tw/department/dpcm)** | *2023 – 2026*

- **Thesis**: Implementation of an AI Routing System for Military Academy Tasks ([details](/publication/2026-ai-routing-system))
- **Advisor**: Prof. Yu-Sung Wu

### B.S. in Information Management
**National Defense University, College of Management** | *2017 – 2021*

- **Class Rank**: Graduated 1st in class (Valedictorian), Score 87.55/100
- **Silver Medal** — [Military Academy Cybersecurity Competition](https://tw.news.yahoo.com/%E8%BB%8D%E6%A0%A1%E7%9B%83%E7%B6%B2%E8%B7%AF%E5%AE%89%E5%85%A8%E7%AB%B6%E8%B3%BD-%E7%AE%A1%E7%90%86%E5%AD%B8%E9%99%A2%E7%8D%B2%E4%BD%B3%E7%B8%BE-160000203.html), 2020

---

## Master's Thesis

### Implementation of an AI Routing System for Military Academy Tasks
*Advisor: Prof. Yu-Sung Wu, National Yang Ming Chiao Tung University*

- Integrated **RAG, Function Calling, and intelligent routing** on a fully offline LLM stack (**TAIDE-LX-8B / Ministral-8B**).
- Validated with **260 test cases** across pure-RAG, pure-tool, and hybrid scenarios.
- Achieved **81.74% overall routing accuracy** and **40%+ quality lift** on tool-calling and hybrid tasks vs baseline.
- Designed for high-security environments where cloud LLM APIs are not permitted.

[Full details →](/publication/2026-ai-routing-system)

---

## Personal Project

### Generative-AI English Teaching SaaS Platform
*Solo Project, 2024 – Present*

[**Live demo**](https://learningplatform-frontend-dev.bravefield-45f8f415.westus2.azurecontainerapps.io/) (westus2 Azure Container Apps)

- Independently designed, built, and operates a SaaS platform for English teachers under Taiwan's 108 curriculum — from product discovery through architecture, development, testing, deployment, and ongoing operations.
- **Backend**: Django 4.2 + DRF + PostgreSQL across 13+ app modules with 70+ pytest tests.
- **Frontend**: React 18 + TypeScript + Vite + TanStack Query + React Router 7.
- **AI integration**: Anthropic Claude API with **SSE streaming** for real-time generation of lesson content; three-tier caching reduces API cost.
- **Billing & Auth**: TapPay subscription billing, Google OAuth, JWT (15min access / 7d refresh).
- **DevOps**: Docker multi-stage builds, Azure Container Registry, Azure Container Apps, Azure DevOps Pipelines (Test → Build → Deploy).
- **Cloud architecture**: deployed in **westus2** to bypass Anthropic API's Asia IP restriction; Azure PostgreSQL Flexible Server, Azure Blob Storage, Google Cloud TTS.

[Full details →](/portfolio/learning-platform)

---

## Technical Skills

| Category | Skills |
|:---|:---|
| **Languages** | Python, C#, TypeScript, JavaScript, Java, SQL |
| **Backend** | Django (DRF), ASP.NET MVC, ASP.NET Web Forms |
| **Frontend** | React 18, Vite, TanStack Query, React Router |
| **Data Viz & Geospatial** | Power BI Custom Visuals (pbiviz), Leaflet.js, Android plugin (Gradle) |
| **Database** | PostgreSQL, MSSQL, Oracle, SQLite |
| **Cloud & DevOps** | Azure (Container Apps, ACR, Blob, PostgreSQL Flexible), Azure DevOps Pipelines, Docker, Git |
| **AI / ML** | Claude API, LLM, RAG, Function Calling, PyTorch, TAIDE-LX-8B, Vector Database, Computer Vision |
| **Testing & Quality** | pytest (70+ tests), Vitest, ESLint, TypeScript strict mode |
| **Other** | OAuth2, JWT, SSE Streaming, SM-2 algorithm, OWASP Top 10, SQL performance tuning |

---

## Certifications

- **AZ-104** — Microsoft Certified: Azure Administrator Associate, Microsoft, 2025 ([cert](https://learn.microsoft.com/en-us/users/yunhsinliu-2381/credentials/eabb2b9beae2ea4b?ref=https%3A%2F%2Fwww.linkedin.com%2F))
- **CompTIA PenTest+** — CompTIA, 2025 ([cert](https://t3764800.p.clickup-attachments.com/t3764800/0db3a5b3-926d-47a0-86d5-20082a87e2dc/image.png?view=open))
- **ECIH** — EC-Council Certified Incident Handler, EC-Council, 2022 ([cert](https://t3764800.p.clickup-attachments.com/t3764800/be8e2684-23e7-4f51-8c45-09a50610c4b2/ECC-ECIH-ANSI-Certificate.jpg?view=open))
- **CCNA** — Cisco Certified Network Associate, Cisco, 2021 ([cert](https://t3764800.p.clickup-attachments.com/t3764800/e9c4a176-cf25-458a-9508-340c289b63bc/Cisco%20Certifications.jpeg?view=open))

---

## Selected Training & Courses

**AI & Machine Learning**

- [Neural Networks and Deep Learning](https://www.coursera.org/account/accomplishments/verify/IL6YVLQ7VK6U), Coursera, 2025
- [Generative AI with Large Language Models](https://coursera.org/share/32a3342640ea17246b2a96aa6a3ff9b3), Coursera, 2024
- [Learn Hugging Face BootCamp](https://www.udemy.com/certificate/UC-673eadde-0a6b-4883-8c46-03d9804670a0/), Udemy, 2024
- [Introduction to AI](https://coursera.org/share/f1a5c3b6f7af9e53039f5b05e20f6bdb), Coursera, 2024
- [PNLP — Python Chinese NLP Expert Course](https://t3764800.p.clickup-attachments.com/t3764800/bd14c453-b3c2-44ec-82e8-d3d20909200a/image.png?view=open), 2024

**Software & Data**

- [ASP.NET MVC 5 Web Application Design (MVC522)](https://t3764800.p.clickup-attachments.com/t3764800/db5dd9fe-407c-4b1b-8ff7-4e4a322a6cde/ASP.NET%20MVC%205.jpg?view=open), SYSTEX, 2023
- [Oracle Database 19c SQL Workshop](https://t3764800.p.clickup-attachments.com/t3764800/5b141f1b-a0d5-46ea-9440-3bb29fb1b8a9/oracle-certificate.jpg?view=open), Oracle, 2023
- [BDPY — Python Data Processing](https://t3764800.p.clickup-attachments.com/t3764800/6607a159-1640-495d-9b54-f923d66cee97/BDPY.jpg?view=open), 2024
- [Django 2.2 & Python Web Development Bootcamp](https://www.udemy.com/certificate/UC-DK32X8UO/), Udemy, 2019
- Docker Containers & Kubernetes System Administration, SYSTEX, 2025

**Project Management**

- [Project Management Assistant (PMA)](https://t3764800.p.clickup-attachments.com/t3764800/44a2f1e1-6b0e-4d39-aded-fdb486d04dc8/Screen%20Shot%202024-07-14%20at%203.11.07%20PM.png?view=open), NPMA, 2019
- [Government Procurement Certification](https://t3764800.p.clickup-attachments.com/t3764800/95e6babd-de9c-4cce-9aa5-7f0e2016cf09/%E6%8E%A1%E8%B3%BC%E8%AD%89%E7%85%A7.jpg?view=open), Public Construction Commission, 2021

---

## Languages

- **Chinese** — Native
- **English** — Professional working proficiency ([TOEIC 800, 2022](https://t3764800.p.clickup-attachments.com/t3764800/64128f81-6a59-48a8-9947-c5a280a5efa2/image.png?view=open))
- **Japanese** — Basic proficiency ([JLPT N4, 2021](https://t3764800.p.clickup-attachments.com/t3764800/96d7469a-0b10-4d85-8d1a-159cb983f33c/image.png?view=open))

---

## Awards & Activities

- **Silver Medal** — [Military Academy Cybersecurity Competition](https://tw.news.yahoo.com/%E8%BB%8D%E6%A0%A1%E7%9B%83%E7%B6%B2%E8%B7%AF%E5%AE%89%E5%85%A8%E7%AB%B6%E8%B3%BD-%E7%AE%A1%E7%90%86%E5%AD%B8%E9%99%A2%E7%8D%B2%E4%BD%B3%E7%B8%BE-160000203.html) (representing College of Management), 2020
- **Valedictorian** — National Defense University, College of Management, Class of 2021

📄 [中文版履歷](/cv-zh-tw/)
