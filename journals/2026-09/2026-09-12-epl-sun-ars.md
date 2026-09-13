# Trade journal — epl-sun-ars — 2026-09-12

## Ticket
- Market: Arsenal Yes (`epl-sun-ars-2026-09-12`) · away at Stadium of Light
- Size: 44.642856 sh · buy $25.549989
- Entry: **56.0¢** · Gina fill `2026-09-12T19:15:40Z` (BUY)
- Exit: **full sell 80.0¢** · Gina fill `2026-09-12T20:19:51Z` (SELL 44.64 sh · $35.35488) after Guimarães 58' (~62' game clock)
- Realized (fills): **+$9.8049** (~+38.4%) · Gina day summary realizedPnl **+$9.8077**
- Open positions after exit: **none** (Gina `polymarket.positions` empty incl. closed)
- FT: **0–2 ARS** (Saka pen 90+7') — hold-to-$1 would have paid ~$44.64 proceeds (~+$9.29 vs sell); **process ≠ outcome**
- Note: Gina `closedPositions.exitPrice=1` / `closedAt` 21:33Z is resolution bookkeeping — authoritative exit is the **80¢ SELL fill**, not $1

## Game-state at exit (FotMob ~62')
- SUN 0–1 ARS · Guimarães 58' (Rice); Guimarães on at HT
- Le Fée missed pen 56'
- xG ~0.98–0.95 · shots 8–6 SUN · poss 36–64 · box 11–11
- Tape: heavy 0–0 chop dump on ARS Yes, then goal spike

## Verdict (Ash — authoritative)
**Selling / not holding was the correct approach.** Temptation to ride to FT/~95 is the trap; historical convert rates on thin away leads after a choppy script do not justify paying ~80–86¢ to stay long.

## Historical base rates (why sell)
Source: Brendan Sudol PL sample ~4.5k games since 2000 (score-by-minute → FT).
- **Away +1 goal:** win rate does **not** reach ~70% until ~**68'**. At ~62' you are still **below** that — i.e. a material draw/loss tail remains.
- **Home +1:** already >70% early, but even home doesn’t cross **80%** until ~**70'**, or **90%** until ~**85'**.
- So locking **80¢** on an **away** 1–0 at **62'** after even xG + missed-pen chaos is banking a price that sits **above** the unconditional historical convert, before strength adjustments.

Context flags that further cut hold EV vs raw favorite brand:
1. Venue = away (weaker protect rates)
2. Path = chop / dump then boom (not a control lead)
3. Live xG parity at exit (~1–1)
4. Home just missed a pen — pressure/variance still live

## Plan vs actual
| Rule | Plan | Actual |
|---|---|---|
| First ARS goal spike | Sell 50–100% into 67–75¢+ | Full flatten @80¢ — **on-plan, preferred** |
| Hold to FT / ~95 | Temptation / counterfactual | Correctly rejected |

## Lessons to carry
1. **Default on chop→first-goal spike for favorite Yes:** full or near-full flatten into 75–85¢ is the process win when mark ≥ historical minute/venue convert.
2. **Don’t rewrite sell with FT result.** 0–2 FT can still be a good sell if entry-to-exit EV was right.
3. **Away 1–0 before ~68'** is not an 80–90¢ hold by base rate alone — need clear control (xG gap, territorial, no pen/chaos) to justify trailing.
4. Journal frames Ash’s sell reasoning as the lesson, not “should’ve held.”
5. Reconcile Gina fills (BUY/SELL prices) over `closedPositions.exitPrice` when they disagree.

## Rule tweak (standing)
After first goal on a favorite Yes that dumped in a 0–0 chop: **prefer bank the spike (50–100%, lean full when away / xG flat / chaos)**. Only trail a runner if minute/venue base rate ≥ mark AND live control (xG lead, not parity).

## Nightly reconcile (23:00 London · 2026-09-12)
- Closed soccer tickets today: **ARS Yes only**
- Open soccer: **none**
- Slate notes still live: MLS overnight 00:30–03:30 London (`/workspace/match-slate-2026-09-12/mls-overnight.md`) — paper leans only, no Gina fills
- Day banked: **+$9.81** realized · left on table vs $1: ~**+$9.29** (ignored by process rule)
