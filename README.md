[README.md](https://github.com/user-attachments/files/26042288/README.md)
# Swainston Family · Magic Mountain 2026

Interactive trip planner for the Swainston family road trip from Highlands Ranch, CO to Six Flags Magic Mountain in Valencia, CA — Summer 2026.

**Live site:** [https://AutoMindA1.github.io/Mila-Magic/](https://AutoMindA1.github.io/Mila-Magic/)

## Family

Caleb, Wife, Mila, Lane, Wyatt, Chloe (6 people, 2 hotel rooms per night)

## Scenario Comparison

| Scenario | Days | Total (Mid) | Range |
|---|---|---|---|
| Best Compromise (Rec) | 5 | $2,105 | $1,790–$2,435 |
| Best Experience | 4–6 | $2,564 | $2,150–$2,915 |
| Best Value | 4–6 | $1,710 | $1,480–$1,955 |
| Quick + Relatives | 3–4 | $1,525 | $1,325–$1,765 |
| Quick + Hotel | 3 | $1,899 | $1,355–$2,130 |

## Features

- **5 Trip Scenarios** — tab-style navigation with per-scenario accent colors
- **Interactive Cost Adjustment** — tap Low / Mid / High chips per line item, total updates in real time
- **Family Voting** — tap a family member, then a scenario to cast their vote (persists in localStorage)
- **Vote Sharing** — copy a text code to paste in iMessage; import codes from other family members
- **Family Notes** — shared textarea persisted locally
- **Key Decision Factors** — info cards covering the 60-mile variable, season passes, hotel math, and more

## How to Use

1. **Browse scenarios** — tap tabs at the top of section 01
2. **Adjust costs** — tap Low / Mid / High chips to see how the total changes
3. **Vote** — tap your name under Family Vote, then tap your preferred scenario
4. **Share votes** — tap "Copy Vote Code" and paste into the family group text
5. **Import votes** — paste a vote code from iMessage and tap "Import Votes"
6. **Notes** — jot anything in the notes section at the bottom

### Vote Code Format

```
🎢 SFMM Trip Votes: Mila=BC, Lane=BV
```

Aliases: `BC` = Best Compromise, `BE` = Best Experience, `BV` = Best Value, `QR` = Quick + Relatives, `QH` = Quick + Hotel

## Tech Stack

- Single `index.html` — all HTML, CSS, and JS inline
- No frameworks, no build step, no npm
- Google Fonts: Work Sans, Outfit, DM Mono
- localStorage for votes and notes
- Optimized for iOS Safari (16px inputs, 34px+ tap targets, no hover-dependent interactions)

## Assumptions

- SUV at 22 mpg, blended gas ~$3.70/gal
- Hotel $160/room/night near Valencia
- Season passes (admission = $0)
- SFMM parking $35/day
- Food ~$100/day for 6
- Spending money $150 total
- Tolls ~$50 RT
