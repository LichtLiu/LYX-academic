---
title: "Generative-AI English Teaching SaaS Platform"
excerpt: "Solo project: Django + React + Claude API SaaS for Taiwan's 108-curriculum English teachers. Live on Azure."
collection: portfolio
permalink: /portfolio/learning-platform
---

[**Live Demo**](https://learningplatform-frontend-dev.bravefield-45f8f415.westus2.azurecontainerapps.io/) · *Solo Project, 2024 – Present*

A SaaS platform for English teachers in Taiwan that uses Anthropic's Claude API to generate lesson explanations, vocabulary breakdowns, grammar analysis, exercises, and oral-practice feedback. Built end-to-end as a solo project — from product discovery through architecture, development, testing, deployment, and ongoing operations.

## Architecture

- **Backend**: Django 4.2 + DRF + PostgreSQL, organized into 13+ app modules (`lessons`, `vocabulary`, `grammar`, `exercises`, `writing`, `ai_engine`, `billing`, `exams`, etc.), with 70+ pytest tests covering business-critical paths.
- **Frontend**: React 18 + TypeScript + Vite + TanStack Query + React Router 7, with Axios interceptors handling JWT refresh automatically.
- **AI Integration**: Anthropic Claude API with **SSE streaming** for real-time generation of lesson content; three-tier caching reduces API cost.
- **Billing & Auth**: TapPay subscription billing, Google OAuth via django-allauth, JWT (15min access / 7d refresh).
- **DevOps**: Docker multi-stage builds, Azure Container Registry, Azure Container Apps, Azure DevOps Pipelines (Test → Build → Deploy with auto-block on failure).
- **Cloud**: Deployed in **westus2** to bypass Anthropic's Asia IP restriction; Azure PostgreSQL Flexible Server, Azure Blob Storage for media, Google Cloud TTS for audio.

## Notable Engineering Decisions

- **Three-layer feature gate** (`GlobalToggle` → per-user `Override` → `PlanFeature`) — single entry point `can_use_feature()` so business logic stays clean.
- **SM-2 spaced repetition** algorithm for vocabulary review scheduling.
- **Server-Sent Events** for streaming long Claude responses to the UI instead of blocking on full completion.
- **Region selection** — chose westus2 specifically because Anthropic's API blocks Asia IPs (including Taiwan).

## Tech Stack

`Django` · `DRF` · `PostgreSQL` · `React 18` · `TypeScript` · `Vite` · `TanStack Query` · `Claude API` · `SSE` · `Docker` · `Azure Container Apps` · `Azure DevOps Pipelines` · `pytest` · `Vitest` · `OAuth2` · `JWT` · `TapPay`
