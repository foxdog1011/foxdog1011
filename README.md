<h1 align="center">Hi, I'm Eason Lin 👋</h1>

<p align="center">
  Full-Stack Engineer · AI Systems · M.S. Information Management, NCU
</p>

<p align="center">
  <a href="mailto:eason4522@gmail.com"><img src="https://img.shields.io/badge/Email-eason4522%40gmail.com-blue?style=flat-square&logo=gmail" /></a>
  <a href="https://github.com/foxdog1011"><img src="https://img.shields.io/badge/GitHub-foxdog1011-181717?style=flat-square&logo=github" /></a>
</p>

---

I build end-to-end systems where **AI is a first-class citizen** — not a wrapper, but woven into the product: agentic tool loops, dual-engine ML scoring, vector search pipelines. Everything ships with tests, CI/CD, and infrastructure-as-code.

---

## Agent & Automation Systems

Beyond single-model integrations, I design and operate **multi-agent pipelines**:

- **Claude Code × Discord orchestration** — automated task routing and work distribution via a persistent Claude Code agent connected to Discord; agents receive commands, spawn sub-agents for parallel workstreams, and report results back to the channel
- **NanoClaw (OpenClaw) self-hosted agent harness** — custom Claude Code agent harness with persistent memory, skill libraries, hook-based automation (pre/post tool-use), cron-scheduled remote agents, and session continuity across conversations
- **MCP server authoring** — built and deployed MCP servers exposing portfolio data, knowledge bases, and automation tools to any MCP-compatible AI client
- **Parallel sub-agent workflows** — orchestrating planner / code-reviewer / security-reviewer / tdd-guide agents in parallel for structured feature development

---

## Projects

### [Stock Ledger](https://github.com/foxdog1011/stock_ledger) — Portfolio Tracker & Investment Research Platform

> Python · FastAPI · Next.js 15 · TypeScript · SQLite · Docker · AWS EC2 · Terraform · Claude API

A full-stack investment platform built from a pure-Python core library up through a REST API, an interactive dashboard, and an AI analyst.

- **J.A.R.V.I.S.** — agentic portfolio analyst powered by Claude claude-opus-4-6 with 12 tool-use functions; autonomously queries positions, risk metrics, P&L, and company research before answering; SSE token-by-token streaming
- **Market Anomaly Detection** — PCA linear autoencoder on 6-feature multivariate time-series; data-driven threshold (μ + 2.5σ reconstruction error); scans all active positions simultaneously
- **Taiwan Stock Research DB** — 1,735 TWSE + OTC companies with supply chain mapping, upstream/downstream links, and 20 investment themes (AI server, EV, HBM, NVIDIA ecosystem, …)
- **Quantitative Analytics** — Sharpe ratio, max drawdown, VaR, benchmark comparison (0050 / SPY / QQQ / TAIEX) with tracking error and information ratio
- **Tax-aware P&L** — FIFO / LIFO / HIFO lot breakdown, commission flow into cost basis, loss-offsetting simulation
- **336 unit tests** · 40+ REST endpoints · CI/CD: GitHub Actions → AWS ECR → EC2 (zero-touch deploy on every push)

**Live demo:** http://35.76.187.226

---

### [IELTS AI Platform](https://github.com/foxdog1011/ielts-ai-platform) — AI Coaching for Writing & Speaking

> Next.js 16 · TypeScript · Python · XGBoost · OpenAI o3 · Vercel · Upstash Redis

A full-stack IELTS coaching platform with a dual-engine scoring architecture that combines language model judgement with a local ML baseline.

- **Dual-engine scoring** — OpenAI o3 and XGBoost run in parallel; confidence-weighted fusion reduces MAE by **19% over baseline**
- **Multi-agent orchestration** — sequential agents for diagnosis, planning, and review with cross-agent consistency validation
- **Quantile calibration** — maps raw model output to official IELTS band distribution
- **Learning analytics** — 7-week activity calendar, streak counter, weekly goals, cross-session weakness detection
- **Error notebook** — save and track improvement suggestions across sessions
- **Exam simulation** — 40-minute writing countdown + 1-minute speaking prep timer
- Full CI/CD: GitHub Actions → Vercel auto-deploy on every push

**Live demo:** https://ielts-ai-platform-web.vercel.app

---

### [personal_db_assistant](https://github.com/foxdog1011/personal_db_assistant) — Local-First AI Knowledge Base

> Electron 28 · React 19 · TypeScript · SQLite · OpenAI · MCP · Vite · Tailwind CSS

A local desktop app that turns raw notes into a queryable, AI-enriched knowledge base — built solo end-to-end.

- **Vector search pipeline** — custom embedding implementation with text-embedding-3-small
- **Knowledge graph** — multi-hop concept traversal across linked notes
- **Background AI job queue** — non-blocking enrichment with GPT-4o-mini; zero-downtime schema migrations
- **MCP server** — exposes the knowledge base to any MCP-compatible AI client (Claude Desktop, agents)
- **Knowledge Tasks** — synthesis layer with Brief, Writing, and Review modes
- **Deterministic mock mode** for offline development; full test suite with Vitest + React Testing Library

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & AI**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude%20API-orange?style=flat-square)
![OpenAI o3](https://img.shields.io/badge/OpenAI%20o3-412991?style=flat-square&logo=openai&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=foxdog1011&theme=dark&hide_border=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=foxdog1011&layout=compact&theme=dark&hide_border=true&langs_count=8" height="150" />
</p>
