# Navigator

> A learning companion for senior professionals entering AI — built as a side project for the **Senior Product Manager, Education Labs** role at Anthropic.

[**→ Open the portfolio**](./index.html) 

---

## What this is

Navigator is a product concept for Anthropic's Education Labs: a Claude-powered learning companion for the 73 million senior US professionals who need AI woven into their existing expertise — not taught to them like beginners.

The repo contains a **single-file portfolio site** that walks through the case study end-to-end:

- The problem (why current AI education fails experienced professionals)
- The user (a persona drawn from real lived experience)
- The product vision (Socratic onboarding → phased plan → portfolio artifacts)
- The PRD (features, success metrics, guardrails, risks, the moat)
- Strategic fit with Education Labs' charter
- A **working interactive prototype** of the diagnostic — 4 questions that generate a real, phased learning plan drawn from a 17-resource career roadmap
- About the author and how this maps to the JD

## How to view it

It's a single HTML file with no build step and no dependencies (just one Google Fonts link).

**Easiest:** open [`index.html`](./index.html) directly in any browser.

```bash
git clone <this-repo-url>
cd navigator
open index.html      # macOS
xdg-open index.html  # Linux
start index.html     # Windows
```

Or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## What's inside

```
navigator/
├── index.html    The portfolio site + interactive prototype (single file)
└── README.md     This file
```

## Why this exists

Three things I wanted to demonstrate, the most honest way I knew how:

1. **Zero-to-one shipping** — concept, PRD, working prototype in one week.
2. **Technical fluency with Claude** — the portfolio was built with Claude; the prototype is a Claude-shaped diagnostic.
3. **An actual point of view** — a specific bet on which underserved AI education market matters most, defended in the spec.

The prototype is anchored to a real 15-month career plan (17 resources, three phases, real notes) so the output isn't generic — it shows what *honest, ordered, ROI-tagged* recommendations actually look like.

## About

Built by Albion · April 2026

I'm applying for the Senior Product Manager, Education Labs role at Anthropic. If you're reading this as part of that application — thanks for clicking through. The "About" section in the portfolio has the full context, including how I'd map my background to the JD and the gaps I'm honestly working on closing.
