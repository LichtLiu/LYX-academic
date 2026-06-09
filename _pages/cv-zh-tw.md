---
layout: archive
title: "履歷"
permalink: /cv-zh-tw/
author_profile: true
---

{% include base_path %}

## 劉昀昕 (Joy Liu)
*軟體工程師 | 應用 AI | Azure | Django + ASP.NET*

📧 joy9517538246@gmail.com | 🔗 [LinkedIn](https://www.linkedin.com/in/yun-hsin-liu/?locale=en_US) | 🌐 [部落格](https://lovedrinkcafe.com)

---

## 關於我
曾於空軍通信資訊單位擔任程式設計官三年，主導 20+ 套企業 MIS 系統設計與開發，支援 30,000+ 帳號、達成 **99.9% 系統可用性**；現於國防部擔任高級資訊程式官，負責地理空間資料視覺化工具開發。

專長後端開發（C#/ASP.NET、Python/Django）與全端架構，熟悉 Azure 雲端部署與 CI/CD 流程。獨立開發並維運生成式 AI 教學 SaaS 平台（Django + React + Claude API），碩士論文聚焦離線部署 LLM 路由系統，具備從**學術理論到產品實作**之雙軌經驗。

正在尋找**軟體工程師**職位，特別對**企業軟體**與**應用 AI** 領域感興趣。

---

## 工作經歷

### 高級資訊程式官
**國防部 通信電子資訊參謀次長室** | *2026 年 1 月 – 現今*

- 開發內部**地理空間資料視覺化工具**，包含以 TypeScript + Leaflet.js 打造的 **Power BI 自訂視覺效果**：互動地圖、分層篩選、標記叢集、範圍涵蓋繪製、模糊搜尋（Fuse.js）、框選 / 套索區域篩選，並透過 pbiviz 工具鏈封裝。
- 開發延伸地理空間態勢平台（ATAK）之 **Android（Java/Gradle）外掛**，環境為 AGP 8.13 / compileSdk 36 / JDK 17。
- 建置即時**指揮顯示**網頁應用程式。
- 提供軟體架構與安全開發實務之技術諮詢。

### 程式設計官
**空軍通信資訊聯隊技訓中心** | *2022 年 1 月 – 2025 年 12 月*

- 主導 **20+ 套企業 MIS 系統**的設計與開發，技術棧 ASP.NET MVC + MSSQL/Oracle，支援 **30,000+ 帳號**日常運作，達成 **99.9% 系統可用性**。
- 獨立設計並開發核心網頁系統（簽核管理、入口網站、AD 認證整合模組），涵蓋 front-end (Razor/JavaScript) 至 back-end (C#/SQL) 全鏈路。
- 負責新需求的系統架構評估與技術選型，制定 API 規範、資料庫 Schema、安全防護策略，並產出技術可行性報告。
- 將企業安全機制（NetApp、Checkpoint、F5、VMware）整合至應用層，依 **OWASP Top 10** 標準執行程式碼安全審查與漏洞修補。
- 主導內部 **AI 創新計畫**，評估 LLM + RAG 技術導入內部知識管理場景，完成 POC 並提出系統整合方案。
- 跨部門協作教育訓練：規劃並執行 ASP.NET、Web Forms、Oracle、MSSQL、PyTorch、CI/CD、Docker、Git 等技術培訓。

### 硬體設計官
**空軍通信資訊聯隊技訓中心** | *2021 年 7 月 – 2021 年 12 月*

- 協助規劃支援 30,000+ 使用者的企業網路基礎架構，包含 NetApp StorageGRID、Checkpoint 防火牆、F5 LB、VMware vCenter 等核心元件之架構設計與部署規劃。
- 評估並整合資訊安全產品（ArcSight SIEM、Cisco IPS、PaloAlto WAF）至企業網路架構，協助系統可用性提升至 **99.5%**。
- 產出系統運作原理文件與架構評估報告，提供開發團隊整合應用層所需之基礎設施規格。

---

## 學歷

### 國防資安管理碩士在職專班
**[國立陽明交通大學 資訊學院](https://www.ccs.nycu.edu.tw/department/dpcm)** | *2023 – 2026*

- **論文**：針對軍事院校體系任務之人工智慧路由系統實作（[詳細介紹](/publication/2026-ai-routing-system)）
- **指導教授**：吳育松 教授

### 資訊管理學系 學士
**國防大學管理學院** | *2017 – 2021*

- **班級排名**：班級第一名畢業（畢業生代表），學業成績 87.55/100
- **[2020 年軍校盃網路安全競賽](https://tw.news.yahoo.com/%E8%BB%8D%E6%A0%A1%E7%9B%83%E7%B6%B2%E8%B7%AF%E5%AE%89%E5%85%A8%E7%AB%B6%E8%B3%BD-%E7%AE%A1%E7%90%86%E5%AD%B8%E9%99%A2%E7%8D%B2%E4%BD%B3%E7%B8%BE-160000203.html)** 銀牌（代表管理學院）

---

## 碩士論文

### 針對軍事院校體系任務之人工智慧路由系統實作
*指導教授：吳育松 教授，國立陽明交通大學*

- 整合 **RAG、Function Calling、智能路由**三大模組，採 **TAIDE-LX-8B / Ministral-8B** 實作完全離線部署的 LLM 系統。
- 以 **260 個測試案例**驗證（純 RAG、純工具、混合場景）。
- 整體路由準確性達 **81.74%**，工具調用與混合任務品質較基準提升 **40%+**。
- 鎖定不允許使用雲端 LLM API 的高資安要求情境。

[完整介紹 →](/publication/2026-ai-routing-system)

---

## 個人專案

### 生成式 AI 英語教學 SaaS 平台
*獨立開發 (Solo Project)，2024 – 現今*

[**線上 Demo**](https://learningplatform-frontend-dev.bravefield-45f8f415.westus2.azurecontainerapps.io/) (westus2 Azure Container Apps)

- 獨立開發針對台灣 108 課綱英語教師之 SaaS 平台，從需求發想、架構設計、開發、測試、部署到維運皆為一人完成。
- **後端**：Django 4.2 + DRF + PostgreSQL，13+ 個 App 模組，70+ pytest 測試覆蓋核心邏輯。
- **前端**：React 18 + TypeScript + Vite + TanStack Query + React Router 7。
- **AI 整合**：透過 Anthropic Claude API 實作 SSE Streaming 即時串流教材生成，並設計三層快取機制降低 API 成本。
- **商業邏輯**：TapPay 金流訂閱、Google OAuth、JWT 雙 token (15min/7d)、SM-2 間隔重複演算法、三層 feature gate。
- **DevOps**：Docker 多階段建置 + Azure Container Registry + Azure Container Apps + Azure DevOps Pipelines 全自動 CI/CD。
- **雲端架構**：westus2 區域部署、Azure PostgreSQL Flexible Server、Azure Blob Storage、Google Cloud TTS。

[完整介紹 →](/portfolio/learning-platform)

---

## 技術專長

| 類別 | 內容 |
|:---|:---|
| **程式語言** | Python、C#、TypeScript、JavaScript、Java、SQL |
| **後端框架** | Django (DRF)、ASP.NET MVC、ASP.NET Web Forms |
| **前端框架** | React 18、Vite、TanStack Query、React Router |
| **資料視覺化與地理空間** | Power BI 自訂視覺效果 (pbiviz)、Leaflet.js、Android 外掛 (Gradle) |
| **資料庫** | PostgreSQL、MSSQL、Oracle、SQLite |
| **雲端與 DevOps** | Azure (Container Apps、ACR、Blob、PostgreSQL Flexible)、Azure DevOps Pipelines、Docker、Git |
| **AI / ML** | Claude API、LLM、RAG、Function Calling、PyTorch、TAIDE-LX-8B、向量資料庫、Computer Vision |
| **測試與品質** | pytest（70+ 測試）、Vitest、ESLint、TypeScript strict mode |
| **其他** | OAuth2、JWT、SSE Streaming、SM-2 演算法、OWASP Top 10、SQL 效能調校 |

---

## 專業證照

- **AZ-104** — Microsoft Certified: Azure Administrator Associate, Microsoft, 2025（[證書](https://learn.microsoft.com/en-us/users/yunhsinliu-2381/credentials/eabb2b9beae2ea4b?ref=https%3A%2F%2Fwww.linkedin.com%2F)）
- **CompTIA PenTest+** — CompTIA, 2025（[證書](https://t3764800.p.clickup-attachments.com/t3764800/0db3a5b3-926d-47a0-86d5-20082a87e2dc/image.png?view=open)）
- **ECIH** — EC-Council 認證事件處理員, EC-Council, 2022（[證書](https://t3764800.p.clickup-attachments.com/t3764800/5f36874b-8dde-4b33-8c7d-cfe2ea920735/ECC5037842691.jpeg?view=open)）
- **CCNA** — Cisco 認證網路助理, Cisco, 2021（[證書](https://t3764800.p.clickup-attachments.com/t3764800/e9c4a176-cf25-458a-9508-340c289b63bc/Cisco%20Certifications.jpeg?view=open)）

---

## 進修課程

**AI 與機器學習**

- [神經網路與深度學習](https://www.coursera.org/account/accomplishments/verify/IL6YVLQ7VK6U), Coursera, 2025
- [大型語言模型生成式 AI](https://coursera.org/share/32a3342640ea17246b2a96aa6a3ff9b3), Coursera, 2024
- [Learn Hugging Face BootCamp](https://www.udemy.com/certificate/UC-673eadde-0a6b-4883-8c46-03d9804670a0/), Udemy, 2024
- [人工智慧導論](https://coursera.org/share/f1a5c3b6f7af9e53039f5b05e20f6bdb), Coursera, 2024
- [PNLP Python 中文自然語言處理專家課程](https://t3764800.p.clickup-attachments.com/t3764800/bd14c453-b3c2-44ec-82e8-d3d20909200a/image.png?view=open), 2024

**軟體與資料**

- [MVC522 ASP.NET MVC 5 網頁應用程式設計](https://t3764800.p.clickup-attachments.com/t3764800/db5dd9fe-407c-4b1b-8ff7-4e4a322a6cde/ASP.NET%20MVC%205.jpg?view=open), SYSTEX, 2023
- [Oracle Database 19C：SQL Workshop](https://t3764800.p.clickup-attachments.com/t3764800/5b141f1b-a0d5-46ea-9440-3bb29fb1b8a9/oracle-certificate.jpg?view=open), Oracle, 2023
- [BDPY Python 資料處理實務演練](https://t3764800.p.clickup-attachments.com/t3764800/6607a159-1640-495d-9b54-f923d66cee97/BDPY.jpg?view=open), 2024
- [Django 2.2 & Python 網頁開發訓練營](https://www.udemy.com/certificate/UC-DK32X8UO/), Udemy, 2019
- Docker Containers 與 Kubernetes 系統管理, SYSTEX, 2025

**專案管理**

- [專案管理助理 (PMA)](https://t3764800.p.clickup-attachments.com/t3764800/44a2f1e1-6b0e-4d39-aded-fdb486d04dc8/Screen%20Shot%202024-07-14%20at%203.11.07%20PM.png?view=open), NPMA, 2019
- [政府採購證照](https://t3764800.p.clickup-attachments.com/t3764800/95e6babd-de9c-4cce-9aa5-7f0e2016cf09/%E6%8E%A1%E8%B3%BC%E8%AD%89%E7%85%A7.jpg?view=open), 行政院公共工程委員會, 2021

---

## 語言能力

- **中文** — 母語
- **英文** — 專業工作程度（[多益 800，2022](https://t3764800.p.clickup-attachments.com/t3764800/64128f81-6a59-48a8-9947-c5a280a5efa2/image.png?view=open)）
- **日文** — 基礎程度（[JLPT N4，2021](https://t3764800.p.clickup-attachments.com/t3764800/96d7469a-0b10-4d85-8d1a-159cb983f33c/image.png?view=open)）

---

## 競賽與榮譽

- **銀牌** — [軍校盃網路安全競賽](https://tw.news.yahoo.com/%E8%BB%8D%E6%A0%A1%E7%9B%83%E7%B6%B2%E8%B7%AF%E5%AE%89%E5%85%A8%E7%AB%B6%E8%B3%BD-%E7%AE%A1%E7%90%86%E5%AD%B8%E9%99%A2%E7%8D%B2%E4%BD%B3%E7%B8%BE-160000203.html)（代表管理學院），2020
- **畢業生代表** — 國防大學管理學院，2021 屆

📄 [English CV](/cv-en/)
