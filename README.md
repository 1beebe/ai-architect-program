# AI Architect Program

**A 6-week cohort that took participants from AI fundamentals to building real systems — with zero paid marketing and zero cancellations.**

---

## What It Was

The AI Architect Program was a community-run workshop series (December 2025–February 2026) designed to bridge the gap between AI curiosity and AI competence. Seven sessions, 91 registrants, and a participant base that spanned Fortune 500 companies, biotech, manufacturing, academia, and independent founders — all organic, all word-of-mouth.

Sessions were opt-in and structured based on content participants surfaced during the Orientation Session "Session 0": LLM fundamentals → prompt engineering → AI workflows → vibe coding → AI agents → multimodal AI → a final Show & Tell showcase where participants demoed what they built.

---

## The Numbers

| Metric | Result |
|---|---|
| Registrants | 91 (zero paid marketing) |
| Satisfaction rate | 96% |
| Avg helpfulness rating | 4.47 / 5.0 |
| Post-program overall rating | 4.8 / 5.0 |
| Season 2 continuation intent | 100% |

---

## How Data Was Collected

Each session generated three data streams:
- **Attendance CSVs** — unique attendees per session, tracked against registration list
- **Post-session polls** — helpfulness ratings and open-ended feedback after each session
- **End-of-program survey** — overall satisfaction, NPS-style continuation intent, expansion topic requests

All data was collected manually, anonymized, and stored as flat CSV files.

---

## How Claude Code Powered the Reporting

Raw CSVs → structured insight, fast.

Rather than manually aggregating and formatting metrics, I used Claude Code to:
- Analyze attendance patterns and calculate retention rates across 7 sessions
- Aggregate satisfaction scores and surface qualitative themes from open-ended responses
- Generate `generate_reports.py` — a Python script that reads the raw data and renders the full HTML report with all charts and metrics

The result: a polished, stakeholder-ready data story produced from raw CSVs in a single session. The report is live at [`AI-Architect-Program-Report.html`](https://1beebe.github.io/ai-architect-program/AI-Architect-Program-Report.html).

**This repo is itself a demonstration of the program's core thesis:** AI tools are most powerful when you understand how to direct them with intention.

---

## Related Work

- [`1beebe/claude`](https://github.com/1beebe/claude) — A live artifact from Session 6 (Show & Tell). Demonstrates the LLM + tools + skills architecture taught throughout the program: the same model and tools produce measurably better outputs when guided by domain-specific knowledge.

- [`1beebe/ai-agent-portfolio`](https://github.com/1beebe/ai-agent-portfolio) — AI Agents & Enablement Portfolio. Production-ready agents and workflows in customer education, content automation, and applied AI for learning design.

---

## Interested in Season 2?

[Get notified →](https://share-na2.hsforms.com/2aKbtf1MCT8qeMoBgjXDPXA41tw3d) &nbsp;·&nbsp; [Book a chat](https://calendly.com/ligaya-b/chat)
