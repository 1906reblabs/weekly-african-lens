# The Daily African Lens — Intelligence Archive

> AI · Machine Learning · Data Science · Across 54 Nations

**Live Site:** `https://[username].github.io/daily-african-lens`  
**Subscribe:** [simphiwemlotshwa.substack.com](https://simphiwemlotshwa.substack.com/)

---

## What This Is

This repository hosts the permanent archive for **The Daily African Lens** — a daily AI intelligence briefing covering artificial intelligence, machine learning, and data science developments across all 54 African Union member states.

Published every morning at **6:00 AM SAST**.

---

## Repository Structure

```
/
├── index.html                    # Main archive hub
├── weekly/                       # AI Weekly Intelligence reports
│   ├── index.html
│   ├── aiw-026-05.html          # Week of 7 April 2026
│   └── ...
├── editions/                     # Daily edition archive
│   ├── dal-026-067.html         # 08 March 2026
│   ├── dal-026-068.html         # 09 March 2026
│   └── ...
├── assets/
│   ├── css/                     # Shared stylesheets
│   └── js/                      # Shared scripts
└── .github/
    └── workflows/
        └── deploy.yml           # Auto-deploy to GitHub Pages
```

---

## Publishing Series

### AI Weekly Intelligence (`/weekly/`)
- Format: `AIW-[YY]-[NN]` (e.g. `AIW-026-05`)
- Time window: Tuesday 06:00 SAST → Tuesday 05:59 SAST
- Structure: Executive Summary → Key Developments → Market Signals → Strategic Insights → Opportunities → Risks

### Daily African Lens Editions (`/editions/`)
- Format: `DAL-[YY]-[NNN]` (e.g. `DAL-026-067`)
- Coverage window: 24-hour SAST windows
- Max 20 ranked items per edition

---

## Adding New Content

### New Weekly Report
1. Create `weekly/aiw-026-NN.html` following the template
2. Add entry to `index.html` archive table
3. Update `weekly/index.html`
4. Push to `main` — GitHub Actions auto-deploys

### New Daily Edition
1. Add HTML file to `editions/` folder
2. Update archive table in `index.html`
3. Push to `main`

---

## Design System

| Token | Value | Use |
|-------|-------|-----|
| `--ink` | `#0e0e0e` | Primary text |
| `--cream` | `#faf7f2` | Background |
| `--gold` | `#c8922a` | Brand accent |
| `--rust` | `#b84c2a` | Breaking/alerts |
| `--teal` | `#1a6b5e` | Secondary accent |

Fonts: **Playfair Display** (headings) · **DM Sans** (body) · **DM Mono** (labels/meta)

---

## Coverage Scope

- **54 African Union member states**
- Primary focus: AI, machine learning, data science, digital policy
- Source tiers: Reuters/BBC (Tier 1) → TechCabal/ITWeb (Tier 2) → Institutional (Tier 3) → Academic (Tier 4)

---

## License

© 2026 The Daily African Lens. All editorial content is original. Non-commercial redistribution with attribution permitted.

---

*Built with the DAL Agentic Workflow v1.0 — 7 agents, continuous self-improvement.*
