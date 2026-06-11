# 🏆 FIFA World Cup 2026 Predictor

> A fully self-contained, offline-ready bracket predictor for the 2026 FIFA World Cup — 48 teams, 12 groups, complete knockout rounds through to the Final.

---

A single HTML file. No installation, no server, no internet required. Just open it in any modern browser.

---

## 🌍 What's Inside

- **48 nations** across 12 groups, each with their country flag
- **Official 2026 group draw** (Groups A–L)
- **Complete bracket logic** following FIFA's Round of 32 matchup structure
- **Embedded FIFA World Cup 2026 logo** — no external assets
- **Dark gold aesthetic** — Bebas Neue display font, radial gold glow, phase progress bar

---

## 🕹️ How to Play

The predictor walks you through **7 phases** in order:

### Phase 1 — Group Stage
- Click any team to assign it a position (1st, 2nd, or 3rd)
- First click = 1st place, second click = 2nd, third click = 3rd
- Click a ranked team again to remove its ranking
- Complete all **12 groups** before moving on

### Phase 2 — Best 3rd-Place Teams
- Each group produces a 3rd-place team (12 total)
- Only **8 of them** advance to the Round of 32
- Select exactly 8 teams you believe deserve to go through

### Phase 3 — Round of 32
- 32 teams, 16 matches
- Click the team you think wins each match
- The bracket builds automatically from your group-stage picks

### Phase 4 — Round of 16
- Winners from the Round of 32 face off
- Click your winner in each match

### Phase 5 — Quarterfinals
- 8 teams remain — pick 4 semifinalists

### Phase 6 — Semifinals
- 4 teams, 2 matches — pick your 2 finalists

### Phase 7 — The Final
- Two nations, one trophy
- Click your **World Cup Champion**

---

## 🗂️ Groups

| Group | Teams |
|-------|-------|
| A | Mexico, South Africa, South Korea, Czechia |
| B | Canada, Switzerland, Qatar, Bosnia and Herzegovina |
| C | Brazil, Morocco, Scotland, Haiti |
| D | United States, Paraguay, Australia, Türkiye |
| E | Germany, Ecuador, Ivory Coast, Curaçao |
| F | Netherlands, Sweden, Japan, Tunisia |
| G | Belgium, Egypt, Iran, New Zealand |
| H | Spain, Uruguay, Saudi Arabia, Cape Verde |
| I | France, Senegal, Norway, Iraq |
| J | Argentina, Austria, Algeria, Jordan |
| K | Portugal, Colombia, Uzbekistan, DR Congo |
| L | England, Croatia, Ghana, Panama |

---

## 🔢 Bracket Structure (Round of 32)

| Match | Fixture |
|-------|---------|
| M73 | A2 vs B2 |
| M74 | E1 vs Best 3rd |
| M75 | F1 vs C2 |
| M76 | C1 vs F2 |
| M77 | I1 vs Best 3rd |
| M78 | E2 vs I2 |
| M79 | A1 vs Best 3rd |
| M80 | L1 vs Best 3rd |
| M81 | D1 vs Best 3rd |
| M82 | G1 vs Best 3rd |
| M83 | H1 vs J2 |
| M84 | J1 vs H2 |
| M85 | B1 vs Best 3rd |
| M86 | D2 vs G2 |
| M87 | K1 vs Best 3rd |
| M88 | K2 vs L2 |

> **Note:** The exact assignment of the 8 qualifying 3rd-place teams to their specific matches follows FIFA's 495-scenario allocation table. In this predictor, the 8 teams you select in Phase 2 fill the "Best 3rd" slots in order (M74, M77, M79, M80, M81, M82, M85, M87).

---

## ⚙️ Technical Notes

- **Zero dependencies** — no frameworks, no CDN links, no build step
- **Logo embedded** as a base64 data URI inside the HTML
- **All state is in-memory** — refreshing the page resets your predictions
- **Fully responsive** — works on desktop and mobile browsers
- Tested in Chrome, Firefox, Edge, and Safari

---

## 🔄 Starting Over

At any point you can go **← Back** to revisit previous phases. After crowning a champion, a **Start Over** button resets everything to the Group Stage.

---

## 📌 Tournament Details

| Detail | Value |
|--------|-------|
| Host nations | United States, Canada, Mexico |
| Total teams | 48 |
| Total groups | 12 |
| Teams advancing per group | Top 2 (24 teams) + Best 8 third-place = 32 total |
| Knockout rounds | Round of 32 → R16 → QF → SF → Final |
| Dates | June 11 – July 19, 2026 |

---

*Built with HTML, CSS, and vanilla JavaScript. No external dependencies.*
