# Social Automation Plugin for Claude Cowork

**Multilingual social content at scale. EN/PT/ES posts from a Google Sheets CMS — no manual repetition.**

Built by [Artur Ferreira](https://thegeolab.net) | The GEO Lab

---

## Commands

| Command | What It Does |
|---------|-------------|
| `/social:generate [url/topic]` | Generate LinkedIn + X posts with data hook and CTA |
| `/social:translate` | Adapt EN post to PT and ES (native adaptation, not translation) |
| `/social:calendar` | Review queue, identify gaps, fill from pending sources |
| `/social:report` | Weekly performance report with patterns and recommendations |

## Agent

`weekly-social-batch` — Autonomous weekly batch: reads calendar gaps → generates 7 days of EN/PT/ES posts → quality checks → writes back to Sheets.

## Posting Schedule

| Time UTC | Language |
|---------|---------|
| 09:00 | English |
| 13:00 | Portuguese |
| 17:00 | Spanish |

## Connectors

Google Drive/Sheets · LinkedIn · Notion · Firecrawl

---

MIT License · [thegeolab.net](https://thegeolab.net)
