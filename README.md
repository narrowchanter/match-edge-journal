# Match Edge — journals + learnings

Ash’s EPL / La Liga / MLS prediction-market desk log. **One repo** for both:

- `journals/` — per-match (or paper) tickets with **what happened** first
- `learnings/STANDING.md` — standing rules only, each citing dated journal tickets

Not a generic betting blog. No webhook keys, no Gina secrets, no sizes unless Ash put them in the journal.

## Entry bar (non-negotiable)

Every `journals/YYYY-MM/YYYY-MM-DD-<slug>.md` must include:

1. **What happened (cause of the learning)** — score, goals, reds, VAR, HT/FT, live xG/tape that drove the decision
2. **Price path** — Polymarket (and books if used) through the decision points
3. **What we did / didn’t do** — fills or explicit sit
4. **Rule tweak** — one concrete standing lesson, not vibes

Update `learnings/STANDING.md` when a ticket adds or hardens a rule. Never invent stats.

## Layout

```
journals/YYYY-MM/YYYY-MM-DD-<slug>.md
learnings/STANDING.md
README.md
```
