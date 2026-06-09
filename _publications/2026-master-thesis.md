---
title: "Implementation of an AI Routing System for Military Academy Tasks"
collection: publications
permalink: /publication/2026-ai-routing-system
excerpt: 'An offline-deployed LLM system integrating RAG, function calling, and intelligent routing for high-security environments.'
date: 2026-06-01
venue: 'M.S. Thesis, National Yang Ming Chiao Tung University'
paperurl: ''
citation: 'Liu, Yun-Hsin. (2026). &quot;Implementation of an AI Routing System for Military Academy Tasks.&quot; <i>M.S. Thesis</i>, National Yang Ming Chiao Tung University, College of Computer Science. Advisor: Prof. Yu-Sung Wu.'
---

## Abstract

Cloud-based LLM services such as ChatGPT and Claude offer powerful capabilities but raise three blocking issues for high-security organizations: (1) static training knowledge that grows stale, (2) limited domain expertise, and (3) data exfiltration risk that disqualifies them from sensitive deployments.

This thesis proposes and implements an **offline-deployed LLM routing system** that combines three capabilities to address those gaps:

1. **Retrieval-Augmented Generation (RAG)** — injects domain knowledge from a curated corpus into the LLM context window.
2. **Function Calling** — lets the LLM invoke external tools when retrieval alone cannot answer.
3. **Intelligent Routing** — classifies incoming queries and dispatches them to the appropriate capability (RAG, tools, or hybrid).

The entire pipeline runs on local GPU infrastructure using **TAIDE-LX-8B** and **Ministral-8B**, with no dependency on cloud LLM APIs.

## Application Domain

The system is validated on **military academy admission and operational tasks**, including admission information lookup (RAG), student record queries (function calling), and hybrid scenarios that need both.

## Evaluation

A test suite of **260 cases** was constructed across three task types:

- Overall routing accuracy: **81.74%**
- Tool-calling task quality vs baseline: **+40%+**
- Hybrid task quality vs baseline: **+40%+**

## Why This Matters

For organizations that cannot send data to OpenAI, Anthropic, or Google — including national defense, regulated industries, and high-security manufacturing environments — this kind of self-hosted LLM stack is the only path to using generative AI safely.

The thesis contributes:

- A reference architecture for offline LLM systems with RAG + tools + routing.
- An evaluation methodology with quantitative routing accuracy and per-task-type quality metrics.
- A working implementation on commodity Taiwan-developed LLMs (TAIDE).

## Advisor

[Prof. Yu-Sung Wu](https://people.cs.nycu.edu.tw/~ysw/), National Yang Ming Chiao Tung University, College of Computer Science.
