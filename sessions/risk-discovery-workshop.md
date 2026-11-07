# Risk discovery workshop

**Goal:** a shared product risk map that guides where quality effort goes in the next quarter.

**Participants:** 6 to 10 people mixing product, development, QA, support or customer success, and someone close to the business.

**Output:** a risk matrix with the top risks, an owner for each, and quick actions for the next sprint. It feeds the [risk-first matrix](https://github.com/ckachury/lean-quality-framework/blob/main/templates/risk-matrix.md) or the [AI risk register](https://github.com/ckachury/ai-quality-governance/blob/main/templates/risk-register.md).

| Minutes | Activity | Structure |
|---|---|---|
| 0–5 | Purpose, ground rules, check-in: "the last thing that broke and surprised me" | — |
| 5–20 | How to make our customers lose trust | TRIZ |
| 20–35 | Map the risks | 1-2-4-All on an impact × likelihood grid |
| 35–47 | Tensions we live with | Wicked Questions |
| 47–57 | What we can do now | 15% Solutions |
| 57–60 | Close | — |

## Activities

1. **TRIZ (15 min).** In groups of 3–4: "What would we have to do to make customers stop trusting our product as fast as possible?" Then: "What on this list do we already do, even a little?" Each group shares two items. These become candidate risks.
2. **Map the risks (15 min).** Individually, place each candidate on the grid (business impact vertical, likelihood horizontal). Pairs compare; fours agree positions for their group's risks; all review only the disagreements.
3. **Wicked questions (12 min).** "How is it that ___ and at the same time ___?" about risk. Example: "How is it that payments are our most critical flow and at the same time the least tested before release?"
4. **15% solutions (10 min).** For the top-right risks: "What can you do next sprint, within your own discretion, to reduce this risk?" Each top risk leaves with one action and one owner.

## Facilitation notes

- Support and customer success often know the real risks best. Make sure they speak in the first round.
- Keep impact in business terms: money, trust, data, legal exposure, blocked users.
- Likelihood needs a reason: recent changes, complexity, missing tests, incident history.
