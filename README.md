# Hi, I'm Eason Lin 👋

M.S. in Information Management @ National Central University · Building AI-powered full-stack systems

[![GitHub](https://img.shields.io/badge/Portfolio-foxdog1011-181717?style=flat&logo=github)](https://github.com/foxdog1011)
[![Email](https://img.shields.io/badge/Email-eason4522@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:eason4522@gmail.com)

---

## What I Build

I design and ship full-stack systems that put AI at the core — not as a wrapper, but as a measured, testable component with real eval metrics.

### [Stock Ledger](https://github.com/foxdog1011/stock_ledger) — Portfolio Tracker & Investment Research Platform
> Python · FastAPI · Next.js · TypeScript · SQLite · Docker · Terraform · AWS · Claude API

- 40+ REST endpoints · 24-page frontend · 18-tool MCP server for AI agent access
- **J.A.R.V.I.S.** — context-aware AI portfolio analyst powered by Claude via MCP tool orchestration + SSE streaming
- PCA autoencoder for portfolio-wide anomaly detection across multiple positions
- AWS EC2 deployment via Terraform IaC + GitHub Actions CI/CD pipeline
- 336 automated tests across domain logic and API contracts

### [IELTS AI Platform](https://github.com/foxdog1011/ielts-ai-platform) — AI Coaching for Writing & Speaking · [Live Demo ↗](https://ielts-ai-platform-web.vercel.app)
> Next.js · TypeScript · Python · XGBoost · OpenAI API · Vercel KV

- Dual-engine scoring: LLM (GPT-4o-mini / o3-mini) + local XGBoost, fused by confidence-weighted averaging
- Quantified bias correction: reduced scoring MAE by **19%** over baseline GPT-4o
- Multi-agent pipeline: DiagnosisAgent → PlannerAgent → ReviewerAgent with 8 consistency rules
- Quantile calibration maps raw 0–1 scores to official IELTS 4.0–9.0 half-band increments
- Full audit trace per submission: weights, timings, model attribution, debug flags

### [Personal DB Assistant](https://github.com/foxdog1011/personal_db_assistant)
> TypeScript · Claude API

- Natural-language interface over personal databases using Claude tool-use

---

## Tech Stack

**Languages** · Python · TypeScript · JavaScript · SQL · Go
**Frontend** · Next.js · React · Tailwind CSS
**Backend** · FastAPI · Node.js · REST API
**AI / ML** · Claude API · OpenAI API · XGBoost · scikit-learn · LLM application design
**Infra** · Docker · AWS (EC2 · ECR · IAM) · Terraform · GitHub Actions · Vercel
**Databases** · SQLite · Redis (Vercel KV) · PostgreSQL

---

## Currently

- Finishing M.S. @ National Central University (2023–2025)
- Open to full-time roles in **backend / AI engineering** — Taiwan or remote

<!-- stats -->
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=foxdog1011&layout=compact&hide=css,html&theme=default)
