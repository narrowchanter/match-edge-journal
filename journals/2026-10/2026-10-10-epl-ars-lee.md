# Trade journal — Arsenal vs Leeds United — 2026-10-10 (Gina fill — won, TP banked)

Slug: `epl-ars-lee-2026-10-10` · Emirates Stadium · KO **12:30 London** · Market `epl-ars-lee-2026-10-10-total-3pt5` (Under 3.5 goals)

---

## What happened (cause of the learning)

### Pre-match / live thesis
- Ash asked for a live deep dig (past meetings, what changed, conviction per outcome) — research only.
- 0–0 at HT and at 53'. Draw ~32¢; Arsenal Yes 55–56¢ (over the ≤45¢ cap → PASS). No O/U board surfaced by the desk at that point.
- Over 2.5 was flagged at ~67¢ during the dig (over cap, no ask → not bought). It would have won.

### Match narrative
Sources: desk live notes, Polymarket CLOB price history, Gina fills.

| Min | Event |
|---|---|
| HT | **0–0** |
| **55'** | **Justin** — Leeds **0–1** |
| ~60s' | **Calafiori** equalises after a **Trafford** error — **1–1** |
| **68'** | **Guimarães** — Arsenal **2–1**. Under 2.5 dies (~0.05¢). Arsenal Yes 88–89¢ by 74' |
| ~77' | Ash: explicit **buy $10 Under 3.5** (one more goal kills it) |
| ~85' | Resting **80¢ TP** fills |
| FT | **Arsenal 2–1 Leeds United** — no further goals; Under 3.5 resolves **Yes** |

Why these events drove the lesson: the 68' goal pushed the total to 3, so Under 3.5 became a pure "no more goals" clock ticket. Its price then rose almost linearly with the minute. The cheapest print was **right after the goal** (in-cap), and the TP at 80 sold into the steepest part of the time-decay curve with ~8–10 minutes plus stoppage left.

### Polymarket ¢ path — Under 3.5 (CLOB history, London time)
| Stamp | Under 3.5 | Note |
|---|---:|---|
| 13:00 | ~84.5 | 0–0 first half |
| 13:44 | ~95.5 | 0–0 early 2nd half peak |
| 13:48–13:56 | ~86 → ~71 | Justin 55' / Calafiori equaliser |
| **14:00** | **~42.5** | Post-Guimarães 2–1 low (**≤45¢ cap**) |
| 14:04 / 14:08 | ~46.5 / ~56.5 | Time decay begins |
| **Gina BUY 14:09:40** | **59.0¢** | 16.949153 sh / **$10.205** (explicit buy overrides cap) |
| 14:12 / 14:16 | ~63.5 / ~71.5 | |
| **Gina SELL 14:18:33** | **80.0¢** | 16.94 sh / **$13.552** — resting TP filled |
| 14:20 / 14:24 | ~84.5 / ~97.5 | |
| FT ~14:28 | ~99.95 → resolves 1 | |

---

## Ticket path

| Phase | Lean | Price | Action |
|---|---|---|---|
| Live dig 0–0 | Draw ~32 / ARS 55–56 | ARS over cap | PASS |
| 2–1 at 68' | Under 3.5 | low ~42.5 | Not on desk yet |
| **Gina BUY** | Under 3.5 | **59¢** | Ash explicit $10 |
| TP rest | Under 3.5 | **80¢** | Ash "TP at 80" (16.94 of 16.95 sh) |
| **Gina SELL** | Under 3.5 | **80¢** | Filled ~85' |
| FT 2–1 | — | 1.00 | Dust 0.009 sh left |

**Gina PnL (authoritative):** BUY $10.205 → SELL $13.552 = **+$3.35**. Ignore closedPositions `exitPrice=1 / realizedPnl 3.3561` — the live SELL @80 is the real exit. Hold-to-FT would have paid ~$16.95 (≈ **+$6.74**), so **≈ $3.40 left on the table**.

---

## Plan vs actual / Ash reasoning / desk read

- **Ash reasoning:** with Arsenal 2–1 and the match slowing, back "no more goals" and lock a clean +~35% at 80 rather than sweat stoppage time.
- **Actual:** correct direction; clean bank. The 80¢ level was roughly at late-game fair when it filled (~85', one goal needed to kill), so it was not a bad price — but it was a **fixed price on a clock-driven ticket**, and the clock kept paying for the next 10 minutes.
- **Desk read:** two misses on the desk side, not Ash's — (1) we didn't surface the Under 3.5 board the moment Guimarães scored, when it printed ~42–46¢ (inside the cap, would have been a standing-rule probe candidate on its own); (2) when Ash said "TP at 80" we placed exactly that, which is right, but didn't show the minute-by-minute fair curve so Ash could choose full vs ladder.

---

## Lessons

1. **Late "no more goals" totals are time-decay tickets.** Their fair rises with the clock; a single fixed TP sells the best minutes. Sister pattern to the Leones Draw TP on 2026-10-07 ([col2-leo-bar](2026-10-07-col2-leo-bar.md)) — two-for-two this week, ≈ $7.25 left vs ≈ $7.17 banked.
2. **The in-cap print is right after the goal.** The goal that makes a total "one more kills it" also dumps that Under to its lowest price. That is the moment to surface it.
3. Explicit TP from Ash stays exactly as named — the fix is in what we show before placing it.

## Standing rule tweak

**Time-decay TP (clock tickets):** On a held ticket whose value comes mainly from the clock running out (late Under, Draw at level score late), when proposing a TP, show Ash the minute-aware fair (e.g. ~75' / 85' / 90'+) and offer a **ladder: 50% at the named TP, 50% at ≥90¢ after ~85'** or hold. If Ash names a single level, place exactly that. Desk-set TPs default to the ladder.

*(Also: when a goal moves a total to "one more kills it", surface that Under at its post-goal low if ≤45¢.)*

## Lesson one-liner
Emirates: Guimarães 68' → 2–1, Under 3.5 low ~42.5¢ → Ash bought 59¢ ($10.21) → TP 80¢ filled ~85' ($13.55, **+$3.35**) → FT 2–1, hold would have paid $16.95. Clean bank; fixed TP on a clock ticket left ~$3.40.
