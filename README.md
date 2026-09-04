<img src="banner.png" alt="foxdog1011 — AI systems and market research" width="100%">

# Hi, I'm Eason 林煜霖

I build and **operate** production AI and data systems end-to-end, then use them for real work: a Taiwan-equity research platform that publishes market briefings every trading day, and an IELTS assessment product with real learners. M.S. in Information Management, National Central University (2025).

The same discipline runs through both: measure the noise before claiming a gain, surface silent failures, and keep the system honest when nobody is watching.

Currently looking at roles where systems thinking meets communication — equity research, solutions engineering, and technical consulting.

---

## Featured Projects

### Stock Ledger — Taiwan-equity decision system

Independently built and operated. Point-in-time market data, chip-flow (籌碼) and institutional analytics, supply-chain research, rule-based entry/exit checks, and an autonomous research-to-video pipeline that publishes to YouTube unattended.

**[Engineering case study](https://foxdog1011.github.io/stock-ledger-showcase/)** ·
**[Production app](https://covenest.systems)** *(login required)* ·
**[YouTube output](https://www.youtube.com/channel/UC-TJSNbjSGP4c447hPjYLow)**

- 77 scheduled jobs running at 90.9% success over 1,400 executions, each audited with rate-limited Discord alerts and an external dead-man switch.
- Video pipeline: market data → LLM script with grounding checks → quality gates → word-level captions → Remotion render → upload. Over 900 videos published without manual steps.
- Lifted median video views 11.4× (non-overlapping ranges) through measured A/B title experiments and a Thompson Sampling upload scheduler.
- Found Docker's iptables rules exposing 7 services while the firewall reported 3 open ports. Rebound everything behind a single Caddy ingress and added a guard test that caught 3 more live holes the day it was written.

### Lumi — AI IELTS assessment and coaching

A longitudinal IELTS learning system rather than a one-shot band-score generator. Writing and Speaking assessment with rubric-level evidence, deterministic coaching, and a verified learning loop where mastery only updates after repeated evidence on new prompts.

**[Live product](https://lumi.integratewise.com)** ·
**[Engineering case study](https://github.com/foxdog1011/ielts-ai-platform-demo)**

- 180 registered learners and 640+ scored submissions at roughly $0.01 average AI cost per score.
- Writing scorer benchmarked against 26 official IELTS examiner-scored samples: Spearman 0.78–0.83, approaching certified-examiner inter-rater agreement. The earlier eval set turned out to be synthetic, so it was rebuilt from official sources and the old accuracy claim was retracted.
- Cut Speaking scoring MAE from 0.80 to 0.50 bands by fusing ASR word timing, a self-hosted acoustic service (faster-whisper + Praat), and an audio-LLM judge, with fail-open degradation.
- Measured the eval harness's own noise floor (±0.011 Spearman across identical runs) and reject any prompt change whose gain falls inside it.

*Also running: a private multi-persona agent framework that handles the daily operations around both products.*

---

## Verified Snapshot

| | Stock Ledger | Lumi |
|---|---:|---:|
| API operations | 551 | 92 |
| Automated tests | 2,969 test functions | 1,289 test cases |
| Scheduled jobs | 77 (90.9% success) | — |
| Reach | 924 videos · 263K views | 180 users · 642 submissions |

*Repository and YouTube Data API snapshot, 2026-08-31. Public counts change after publication.*

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=foxdog1011&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=foxdog1011&layout=compact&theme=default&hide_border=true" alt="Top Languages" height="165" />
</p>

---

## Contact

- **LinkedIn:** [linkedin.com/in/easonlin10](https://www.linkedin.com/in/easonlin10)
- **Email:** eason4522@gmail.com
- **GitHub:** [github.com/foxdog1011](https://github.com/foxdog1011)
