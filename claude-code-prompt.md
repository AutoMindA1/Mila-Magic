# Prompt: Build Magic Mountain Family Trip Planner

Create a single-file interactive HTML trip planner (`index.html`) for the Swainston family road trip from Highlands Ranch, CO to Six Flags Magic Mountain in Valencia, CA — Summer 2026. Also create a `README.md`. Commit both, push to main, and enable GitHub Pages. Return the live URL.

## Family
Caleb, Wife, Mila, Lane, Wyatt, Chloe (6 people total, 2 hotel rooms per night required)

## Trip Data — 5 Scenarios

All scenarios assume: SUV @ 22 mpg, blended gas ~$3.70/gal, hotel $160/room/night near Valencia, season passes (admission = $0), SFMM parking $35/day, food ~$100/day for 6, spending money $150 total, tolls ~$50 RT. Relatives in Moreno Valley = free lodging + home-cooked meals.

### 1. Best Compromise (Recommended) — 5 Days
2 Nights Relatives (Moreno Valley) + 3 Nights Hotel (Valencia)
*"Arrive at Family. Finish at the Park."*

| Line Item | Cost | Range |
|---|---|---|
| Gas (RT via Moreno Valley) | $425 | $380–$480 |
| Relatives — 2 nights | $0 | $0 |
| Hotel near park — 3 nights × 2 rooms | $960 | $840–$1,080 |
| Food — 5 days (2 home + 3 out) | $450 | $360–$540 |
| SFMM Parking — 2 days | $70 | $70 |
| Tolls / Transport | $50 | $40–$65 |
| Spending Money — 6 ppl | $150 | $100–$200 |
| **TOTAL** | **$2,105** | **$1,790–$2,435** |

Pros: 2 full park days from hotel 5 min from SFMM, wake up and walk to park, hotel pool, 2 free nights at relatives, $459 saved vs Best Experience, home-cooked meals first 2 days
Cons: Mid-trip transition day, two lodging check-ins, 3 hotel nights still costly
Itinerary: Day 1 Drive to Moreno Valley (15-16 hrs) → Day 2 Family Day → Day 3 Transition 60 mi to Valencia, hotel check-in → Day 4 Park Day 1 → Day 5 Park Day 2

### 2. Best Experience — 4–6 Days
Full Hotel (Valencia), No Relatives Stop

| Line Item | Cost | Range |
|---|---|---|
| Gas (RT ~2,100 mi) | $354 | $310–$400 |
| Hotel — 4–5 nights × 2 rooms | $1,440 | $1,280–$1,600 |
| Food — 5 days | $500 | $400–$600 |
| SFMM Parking — 2 days | $70 | $70 |
| Tolls / Transport | $50 | $40–$65 |
| Spending Money — 6 ppl | $150 | $100–$200 |
| **TOTAL** | **$2,564** | **$2,150–$2,915** |

Pros: 5 min from park, full schedule control, hotel pool, no transitions
Cons: Most expensive, no home meals, no family visit
Itinerary: Day 1 Drive to Valencia → Day 2 Rest/pool → Day 3 Park Day 1 → Day 4 Park Day 2 → Day 5 Flex/return

### 3. Best Value — 4–6 Days
2 Nights Hotel (Valencia) + 3+ Nights Relatives

| Line Item | Cost | Range |
|---|---|---|
| Gas (RT ~2,260 mi + park days) | $425 | $380–$480 |
| Relatives — 3+ nights | $0 | $0 |
| Hotel near park — 2 nights × 2 rooms | $640 | $560–$720 |
| Food — 5 days (home meals help) | $375 | $300–$450 |
| SFMM Parking — 2 days | $70 | $70 |
| Tolls / Transport | $50 | $40–$65 |
| Spending Money — 6 ppl | $150 | $100–$200 |
| **TOTAL** | **$1,710** | **$1,480–$1,955** |

Pros: Saves ~$854 vs full hotel, real family connection, 2 park days, home meals
Cons: 60 mi each way to park on non-hotel days, schedule coordination with relatives
Itinerary: Day 1 Drive to Moreno Valley → Day 2 Family Day → Day 3 Family + drive to Valencia → Day 4 Park Day 1 → Day 5 Park Day 2 → Day 6 Return via relatives

### 4. Quick + Relatives — 3–4 Days
1 Night Relatives + 2 Nights Hotel

| Line Item | Cost | Range |
|---|---|---|
| Gas (RT ~2,260 mi + park day) | $400 | $360–$455 |
| Relatives — 1–2 nights | $0 | $0 |
| Hotel near park — 2 nights × 2 rooms | $640 | $560–$720 |
| Food — 3.5 days | $250 | $200–$320 |
| SFMM Parking — 1 day | $35 | $35 |
| Tolls / Transport | $50 | $40–$65 |
| Spending Money — 6 ppl | $150 | $100–$200 |
| **TOTAL** | **$1,525** | **$1,325–$1,765** |

Pros: Lowest cost with hotel, less PTO, family visit included
Cons: Long drive for 1 park day, tight timeline, most coordination
Itinerary: Day 1 Drive to Moreno Valley → Day 2 Drive to Valencia, hotel → Day 3 Park Day → Day 4 Drive home

### 5. Quick + Hotel — 3 Days
Hotel Only (Valencia)

| Line Item | Cost | Range |
|---|---|---|
| Gas (RT ~2,100 mi) | $354 | $310–$400 |
| Hotel — 2–3 nights × 2 rooms | $960 | $640–$960 |
| Food — 3.5 days | $350 | $280–$420 |
| SFMM Parking — 1 day | $35 | $35 |
| Tolls / Transport | $50 | $40–$65 |
| Spending Money — 6 ppl | $150 | $100–$200 |
| **TOTAL** | **$1,899** | **$1,355–$2,130** |

Pros: Shortest time, $665 less than full hotel, schedule control
Cons: Long drive for 1 park day, hotel still expensive, rushed
Itinerary: Day 1 Drive to Valencia → Day 2 Park Day → Day 3 Drive home

## Design Requirements

### Visual Design — "Desert Cartography"
Earth-tone palette inspired by the CO→CA desert drive with Six Flags coaster energy:

| Token | Hex | Use |
|---|---|---|
| earth-deep | #1E120B | Primary text, hero bg |
| earth-mid | #3D2519 | Secondary text |
| earth-warm | #5C3A2E | Borders, subtle accents |
| ochre | #B8860B | Highlight, recommended badge |
| amber | #D4A04A | Best Compromise accent |
| sand | #E8D5B7 | Card borders, dividers |
| sand-light | #F5EDE0 | Subtle backgrounds |
| cream | #FAF6F0 | Page background |
| sky | #7BA7C2 | Info accents |
| sky-deep | #3E7A9E | Best Experience accent |
| coaster-red | #C44536 | CTA buttons, SFMM energy |
| coaster-red-light | #E8675A | Hover states |
| green | #4A7C5C | Best Value accent |
| green-light | #EAF2EC | Success backgrounds |

### Typography
- Google Fonts: Work Sans (body), Outfit (headings), DM Mono (labels/monospace)
- No Inter font. No purple gradients. No generic centered hero layouts.

### Layout
- Max-width 1100px centered container
- Numbered sections: 01 Scenarios, 02 Itinerary, 03 Key Decision Factors, 04 Family Vote, 05 Family Notes
- Hero section: dark bg (earth-deep), SFMM coaster silhouette as subtle SVG background art, title "Swainston Family · Magic Mountain 2026", tagline "Highlands Ranch → Valencia · Summer 2026 · Family of 6"

## Interactive Features

### 1. Scenario Cards
- Horizontal scrollable cards or tab-style navigation
- Each card shows: emoji + name, tagline, days, total cost, cost range
- "Recommended" badge on Best Compromise
- Each scenario has its own accent color

### 2. Interactive Cost Adjustment
- For each cost line item, parse the range (e.g., "$380–$480") into min/max values
- Display 3 tappable chip buttons per item: Low (min), Mid (midpoint), High (max) — showing exact dollar amounts
- Chips must be minimum 34px tall for iOS tap targets
- Selected chip gets highlighted in the scenario's accent color
- Total updates in real time as chips are tapped
- "Reset" button to return all items to midpoint defaults
- NO range sliders (they're bad on iOS Safari)

### 3. Family Voting
- 6 family member buttons: Caleb, Wife, Mila, Lane, Wyatt, Chloe
- Click a member → click a scenario to cast their vote
- Votes persist in localStorage (key: `sfmm-trip-votes`)
- Show vote tally per scenario

### 4. Vote Sharing via Text Codes (for iMessage group text)
Since this is a static site with no backend, votes sync between family members via copy/paste text codes:

- Scenario aliases: `BC` = Best Compromise, `BE` = Best Experience, `BV` = Best Value, `QR` = Quick + Relatives, `QH` = Quick + Hotel
- "Copy Vote Code" button generates: `🎢 SFMM Trip Votes: Mila=BC, Lane=BV`
- "Import Votes" button: textarea + import button. Paste a code from iMessage, it parses and merges votes into local storage
- Show feedback on successful import

### 5. Family Notes
- Textarea with placeholder: "Anything — questions, ideas, must-dos, food spots, things to pack, ride wish lists..."
- Persists to localStorage (key: `sfmm-trip-notes`)

### 6. Key Decision Factors Section
Display as info cards with icons:
- 🚗 The 60-Mile Variable: Moreno Valley → Valencia = 1 hr without traffic, 1.5–2 hrs with LA traffic
- 🎢 Season Passes: $0 admission, but budget $100–150 for park food
- ⚖️ The Compromise Structure: Hotel is base for park days, family visit front-loaded
- 🏨 2 Rooms Minimum: Family of 6 = 2 rooms every night at ~$160/room = $320/night
- 👨‍👩‍👧‍👦 Family Visit: Moreno Valley relatives = $0 lodging + home-cooked meals

## iOS Safari Optimization (Critical)
- All inputs and textareas: `font-size: 16px` minimum (prevents iOS auto-zoom)
- All tap targets: minimum 34px height
- `touch-action: manipulation` on interactive elements
- Responsive breakpoints at 768px and 420px
- No hover-dependent interactions

## Technical Constraints
- Single `index.html` file — all HTML, CSS, and JS inline
- No frameworks, no build step, no npm
- Google Fonts loaded via @import
- localStorage only (no cookies, no server)
- Footer: "All estimates are midpoints · Actual costs vary by gas prices, hotel availability, and California appetites" + "Swainston Family · Magic Mountain 2026"

## README.md
Include: project description, scenario comparison table, feature list, how-to-use instructions, vote code format explanation, tech stack summary, family member list. Link to the live GitHub Pages URL.

## Deployment
Commit `index.html` and `README.md` to main. Enable GitHub Pages on main branch via `gh api` or `gh` CLI. Return the live URL.
