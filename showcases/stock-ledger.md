# Stock Ledger

> An independently built and operated production system for Taiwan-equity
> decision intelligence.

Stock Ledger combines point-in-time market data, private portfolio analytics,
sourced research, scheduled automation, and a public publishing pipeline. The
production source and personal data remain private; the public case study makes
the architecture, engineering decisions, and verified evidence inspectable.

## Explore

- **[Production engineering case study](https://foxdog1011.github.io/stock-ledger-showcase/)** — architecture, trust boundaries, incident response, data correctness, and screenshots
- **[Authenticated production application](https://covenest.systems)** — login required; no shared demo credentials
- **[JARVIS 選股 on YouTube](https://www.youtube.com/channel/UC-TJSNbjSGP4c447hPjYLow)** — public output from the research-to-media pipeline
- **[Showcase source](https://github.com/foxdog1011/stock-ledger-showcase)** — static public site; production source remains private

## Verified snapshot

| Evidence | Result |
|---|---:|
| OpenAPI operations | 551 |
| Public YouTube videos | 924 |
| Channel views | 263,079 |
| Python test modules | 238 |

*Repository and YouTube Data API snapshot verified 2026-08-31. Public channel
counts may change after publication.*

The full case study deliberately leads with three engineering decisions rather
than code volume: containing a Docker networking exposure, enforcing
point-in-time financial data, and turning silent automation failures into
observable, testable outcomes.
