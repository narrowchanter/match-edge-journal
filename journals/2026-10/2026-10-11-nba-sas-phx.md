# Trade journal — San Antonio Spurs vs Phoenix Suns — NBA preseason, 2026-10-10 ET (Gina fill — lost)

Slug: `nba-sas-phx-2026-10-10` · Mortgage Matchup Center, Phoenix · Tip **03:30 London Sun 11 Oct** (22:30 ET Sat 10 Oct) · Market: moneyline "Spurs vs. Suns", outcome **Spurs**

> Off-sport ticket: Match Edge is a soccer desk, but this was a Gina fill on Ash's explicit instruction, so it gets a journal.

---

## What happened (cause of the learning)

### Context
- **Preseason** game (NBA.com tags it PRESEASON). Starter minutes and rotations are unreliable in preseason, so the pre-tip price carries less information than in a regular-season game.
- Pre-tip the Spurs traded **~68–73¢** (favourites). The Polymarket event page still showed **71¢** when Ash asked to buy; the live book was **49¢ bid / 51¢ ask**. The page was stale, the book had already re-priced.

### Game narrative (ESPN / RealGM box score)
| Quarter | Spurs | Suns | Running |
|---|---:|---:|---|
| Q1 | 25 | 35 | **SAS 25–35** — Suns' fast start, Spurs ~70¢ → ~53¢ |
| Q2 | 26 | 23 | HT **SAS 51–58** |
| Q3 | 22 | 27 | **SAS 73–85** |
| Q4 | 25 | 17 | FT **Suns 102–98 Spurs** |

Why these events drove the lesson: the 10-point first quarter is what moved the Spurs from ~70¢ to ~51¢. Buying at 51¢ was not a discount to the 71¢ on the page; it was the fair re-price after the Suns' start. The Spurs got back to level-ish money twice (≈53¢ ~04:25, ≈51.5¢ ~05:05) but never above entry by enough to bank, then the Q3 gap pushed them under 15¢. The Q4 comeback (25–17) fell 4 points short.

### Polymarket ¢ path — Spurs (CLOB history, London time, Sun 11 Oct)
| Stamp | Spurs | Note |
|---|---:|---|
| 01:00–03:45 | ~68.5–73.5 | Pre-tip / opening minutes |
| **03:54:51** | **51.0¢** | **Gina BUY** 19.607844 sh / **$10.245** (Ash explicit; over 45¢ cap, explicit buy overrides) |
| 03:55 | ~53.5 | |
| 04:05–04:15 | ~46.5–47.5 | |
| 04:25 | ~53 | first scratch window (≈ entry) |
| 04:35–04:55 | ~46–47.5 | |
| 05:05 | ~51.5 | second scratch window (≈ entry) |
| 05:15 → 05:35 | ~40.5 → ~14 | Suns pull away (Q3) |
| 05:55 → 06:05 | ~0.75 → ~0.05 | FT, resolves Suns |

---

## Ticket path

| Phase | Lean | Price | Action |
|---|---|---|---|
| Live, ~Q1 | Spurs ML | 51¢ ask (page showed stale 71¢) | Ash explicit **buy $10** → filled |
| Post-fill | — | — | No TP / stop set; desk asked Ash for a level, none named |
| ~04:25 / ~05:05 | — | ~53 / ~51.5 | Scratch windows at entry — not taken |
| FT | Suns 102–98 | 0.00 | Position worthless (redeemable at $0) |

**Gina PnL (authoritative):** BUY **$10.245** → 0 = **−$10.25** (data-api `cashPnl` shows −$10.00 on initial value; the extra ~$0.25 is fees in the fill cost). Nothing to recover from redemption.

---

## Plan vs actual / Ash reasoning / desk read

- **Ash reasoning:** not recorded beyond the explicit "buy $10 Spurs". Desk inference only: the pre-tip favourite looked cheap at ~51 against the 71¢ still shown on the page.
- **Actual:** the drop was information (a 10-point Q1 hole in a preseason game where starters may sit), not a mispricing. Spurs lost by 4.
- **Desk read:** execution was right (explicit buy beats the cap, standing rule 2026-09-17). Two desk misses:
  1. We flagged the stale 71¢ but did not frame the 51¢ as "the board re-priced on a 10-point deficit" — the same reasoning as the soccer **"don't buy the dump as a better print"** rule (2026-09-15 Alavés–Valencia). That rule is written for soccer but applies here.
  2. We left the ticket with no exit plan. We asked for a level, but we did not propose one. A scratch-at-entry order would have cleared at ~51–53¢ twice before the Q3 collapse (≈ −$0.25 fees instead of −$10.25).

---

## Lessons

1. **A live drop from the pre-tip price is not a discount by itself.** Read the score first: if the drop is a scoreboard deficit, the new price is fair until shown otherwise. Same lesson as the soccer dump rule, now seen in basketball.
2. **Preseason is a lower-information market.** Starter minutes are capped and benches play late, so favourites are less reliable and swings are bigger.
3. **An explicit buy still needs an exit plan from the desk.** Asking "what level?" and hearing nothing left a full $10 riding on a ticket that offered two clean scratches.

## Standing rule tweak

**Explicit buys off-sport / preseason / live after a drop:** execute as instructed (explicit buy wins), but in the same fill message the desk must (a) say what moved the price (score/deficit, stale page vs live book) and label preseason games as such, and (b) **propose a concrete exit** — at minimum a scratch at entry if the ticket trades back there, plus a TP. Place it only if Ash says yes or names a level; never auto-place on a non-Gina-rule ticket. The soccer "don't buy the dump as a better print" rule applies across sports.

## Lesson one-liner
Phoenix (preseason): Suns 35–25 Q1 dropped Spurs ~70→51¢; Ash bought 51¢ ($10.25) on a stale 71¢ page; two scratch windows at ~51–53¢ untaken; Suns won 102–98 → **−$10.25**.
