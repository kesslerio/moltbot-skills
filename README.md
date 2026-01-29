# Moltbot Skills by kesslerio

> A curated collection of skills for [Moltbot](https://github.com/moltbot/moltbot) — the extensible AI assistant platform.

## Overview

This repository serves as an index of Moltbot skills authored by [kesslerio](https://github.com/kesslerio). Each skill extends Moltbot's capabilities through specialized tools, integrations, and workflows.

---

## 📊 Business & Sales

| Skill | Description | Repo |
|-------|-------------|------|
| **activecampaign** | ActiveCampaign CRM integration for lead management, deal tracking, and email automation | [kesslerio/activecampaign-moltbot-skill-public](https://github.com/kesslerio/activecampaign-moltbot-skill-public) |
| **attio** | Attio CRM integration — search, create, update companies, people, deals, tasks, and notes | [kesslerio/attio-moltbot-skill](https://github.com/kesslerio/attio-moltbot-skill) |
| **stripe-cli** | Stripe CLI integration for managing payments, customers, and subscriptions | [kesslerio/stripe-cli-moltbot-skill](https://github.com/kesslerio/stripe-cli-moltbot-skill) |

---

## 💰 Finance & Investing

| Skill | Description | Repo |
|-------|-------------|------|
| **equity-research** | Comprehensive equity analysis with MSS (SaaS/growth) and UQF (conservative) frameworks | [kesslerio/equity-research](https://github.com/kesslerio/equity-research) |
| **finance-news** | Market news briefings with AI summaries, portfolio tracking, and multi-market coverage | [kesslerio/finance-news-moltbot-skill](https://github.com/kesslerio/finance-news-moltbot-skill) |
| **openbb** | OpenBB financial data integration for stocks, ETFs, and market analysis | [kesslerio/openbb-moltbot-skill](https://github.com/kesslerio/openbb-moltbot-skill) |

---

## 🏥 Health & Wellness

| Skill | Description | Repo |
|-------|-------------|------|
| **fitbit-analytics** | Fitbit health and fitness data integration — steps, heart rate, sleep, and trends | [kesslerio/fitbit-analytics-moltbot-skill](https://github.com/kesslerio/fitbit-analytics-moltbot-skill) |
| **oura-analytics** | Oura Ring data integration — sleep scores, readiness, HRV, and activity analytics | [kesslerio/oura-analytics-moltbot-skill](https://github.com/kesslerio/oura-analytics-moltbot-skill) |

---

## 💻 Development & Productivity

| Skill | Description | Repo |
|-------|-------------|------|
| **coding-agent** | Coding assistant with Codex MCP for reviews, refactoring, and implementation | [kesslerio/coding-agent-moltbot-skill](https://github.com/kesslerio/coding-agent-moltbot-skill) |
| **lobster-jobs** | Transform Moltbot cron jobs into Lobster workflows | [kesslerio/lobster-moltbot-skill](https://github.com/kesslerio/lobster-moltbot-skill) |
| **task-tracker** | Personal task management with daily standups and weekly reviews | [kesslerio/task-tracker-moltbot-skill](https://github.com/kesslerio/task-tracker-moltbot-skill) |

---

## 🔧 Utilities

| Skill | Description | Repo |
|-------|-------------|------|
| **shorten** | Shorten URLs using is.gd (no auth required) | [kesslerio/url-shortener-moltbot-skill](https://github.com/kesslerio/url-shortener-moltbot-skill) |

---

## 🌐 Community Skills

Looking for more skills? Check out the [ClawdHub Skill Registry](https://clawdhub.com) for community-contributed skills including:

- **alltrails** — Search hiking trails near any location
- **babyconnect-browser** — Log baby activities to Baby Connect
- **bird** — X/Twitter CLI for reading and posting
- **context7** — Intelligent documentation search
- **dex** — Personal CRM for contacts and relationships
- **elevenlabs** — Text-to-speech using ElevenLabs AI voices
- **github** — GitHub CLI integration
- **goplaces** — Google Places API integration
- **llm-council** — Multi-member planning council
- **personas** — 31 specialized AI personalities
- **qmd** — Local search/indexing with vectors
- **research** — Deep research via Gemini CLI
- **skillcraft** — Opinionated design guide for creating Moltbot skills
- **summarize** — Summarize URLs, PDFs, videos
- **therapy-mode** — AI-assisted therapeutic support
- **tmux** — Remote-control tmux sessions
- **weather** — Current weather and forecasts
- And more...

---

## Installation

Skills can be installed via the Moltbot CLI:

```bash
moltbot skills install kesslerio/<skill-name>
```

Or clone directly to your skills directory:

```bash
git clone https://github.com/kesslerio/<skill-name>.git ~/.moltbot/skills/<skill-name>
```

---

## Contributing

To add a new skill to this list:

1. Create your skill following the [Skillcraft guide](https://github.com/kesslerio/skillcraft-moltbot-skill)
2. Ensure it has a `SKILL.md` with proper metadata
3. Open a PR to update this README

---

## License

Each skill is licensed individually. See the respective repository for license details.

---

<p align="center">
  <i>Built for <a href="https://github.com/moltbot/moltbot">Moltbot</a></i>
</p>
