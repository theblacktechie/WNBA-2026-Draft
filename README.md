# Who Develops Pros
### 2026 WNBA Draft · Coach Pipeline Viz
**Built by Kris E. Smith · The Black Techie**

---

## What This Is

An interactive data visualization tracking every coaching staff and player development professional who prepared the 2026 WNBA Draft class for the professional level. All 45 picks across three rounds. 15 WNBA teams. One question: who actually builds the players?

The editorial angle: the head coach gets the credit. This viz gives credit to everyone who earned it.

Live at **[theblacktechie.github.io/wnba-draft-coach-tree](https://theblacktechie.github.io/wnba-draft-coach-tree)**

---

## The Viz

**`wnba-draft-coach-tree.html`**

- All 45 confirmed picks organized by court position: Paint (Centers + Post Forwards), Wing (Forwards + Wings), Perimeter (Guards)
- Hover or tap any player card to reveal the coach pipeline behind them, the player-specific developer, and the defining stat that proves the coaching worked
- School filter: narrow the view to any of 20 programs or the international pipeline
- Position tabs: All, Guards, Forwards, Centers
- Faint basketball court SVG background scales behind all three zones
- Fully responsive across mobile, tablet, and desktop with position-specific layout adjustments

**Design system:** Inter font · WNBA orange (#FF6B35) · School hex colors · Athletic minimalist aesthetic · White background

**Responsive behavior:**

| Breakpoint | Behavior |
|------------|----------|
| Desktop (641px+) | Single-line deck text, full-size tabs (12px), standard zone padding |
| Mobile (max 640px) | Deck text wraps at 9px, eyebrow compressed to one line at 7.5px, tighter padding throughout, 3-column card grid |
| Small mobile (max 420px) | Cards narrow to 90px, pick numbers at 24px, footer compressed |

---

## The Tooltip: Player-Specific Developers

Every player's tooltip is unique. The staff block at the top is built from documented research into each program's coaching roles and player relationships — no two players from the same program necessarily get the same developer.

**Coach block (school color):**

| Line | What It Shows |
|------|---------------|
| **HC: [Coach Name]** | The head coach, in school color |
| **School: [Program]** | The program, in school color |
| **[Pipeline Context]** | The coaching stat that defines this pick, in school color |

**Staff block — player-specific (orange label, then 3 lines):**

| Label | When It Appears |
|-------|----------------|
| **Key Staff** | A named staff member had direct documented impact on this specific player |
| **Developer** | The head coach personally is the primary developer for this specific player |
| **Development Path** | International players, named by their specific club or national federation |

| Line | What It Shows |
|------|---------------|
| [Label] | Key Staff, Developer, or Development Path (orange) |
| [Name] | The specific person or club system, dark ink |
| [Role] | Title or position, muted gray caps |
| [Context note] | The documented reason this person matters to this player specifically, italic |

**Player block:**

| Line | What It Shows |
|------|---------------|
| [Player Name] | Large, dark ink |
| Pick # · Position | Muted caps |
| [Defining Stat] | The stat that proves the coaching worked |

---

## The Players (All 45 Picks)

### Round 1

| Pick | Player | School | Team |
|------|--------|--------|------|
| 1 | Azzi Fudd | UConn | Dallas Wings |
| 2 | Olivia Miles | TCU | Minnesota Lynx |
| 3 | Awa Fam Thiam | Spain | Seattle Storm |
| 4 | Lauren Betts | UCLA | Washington Mystics |
| 5 | Gabriela Jaquez | UCLA | Chicago Sky |
| 6 | Kiki Rice | UCLA | Toronto Tempo |
| 7 | Iyana Martin Carrion | Spain | Portland Fire |
| 8 | Flau'Jae Johnson | LSU | Seattle Storm |
| 9 | Angela Dugalić | UCLA | Washington Mystics |
| 10 | Raven Johnson | South Carolina | Indiana Fever |
| 11 | Cotie McMahon | Ole Miss | Washington Mystics |
| 12 | Nell Angloma | France | Connecticut Sun |
| 13 | Madina Okot | South Carolina | Atlanta Dream |
| 14 | Taina Mair | Duke | Seattle Storm |
| 15 | Gianna Kneepkens | UCLA | Connecticut Sun |

### Round 2

| Pick | Player | School | Team |
|------|--------|--------|------|
| 16 | Marta Suárez | TCU | Golden State Valkyries |
| 17 | Frieda Bühner | Germany | Portland Fire |
| 18 | Charlisse Leger-Walker | UCLA | Connecticut Sun |
| 19 | Cassandre Prosper | Notre Dame | Washington Mystics |
| 20 | Ta'Niya Latson | South Carolina | LA Sparks |
| 21 | Latasha Lattimore | Ole Miss | Chicago Sky |
| 22 | Teonni Key | Kentucky | Toronto Tempo |
| 23 | Ashlon Jackson | Duke | Golden State Valkyries |
| 24 | Chance Gray | Ohio State | LA Sparks |
| 25 | Justine Pissott | Vanderbilt | Indiana Fever |
| 26 | Saffron Shiels | Australia | Toronto Tempo |
| 27 | Ines Pitarch-Granel | France | Phoenix Mercury |
| 28 | Indya Nivar | UNC | Atlanta Dream |
| 29 | Janiah Barker | Tennessee | Las Vegas Aces |
| 30 | Darianna Littlepage-Buggs | Baylor | Washington Mystics |

### Round 3

| Pick | Player | School | Team |
|------|--------|--------|------|
| 31 | Zee Spearman | Tennessee | Dallas Wings |
| 32 | Tonie Morgan | Kentucky | Chicago Sky |
| 33 | Serah Williams | UConn | Portland Fire |
| 34 | Rori Harmon | Texas | Washington Mystics |
| 35 | Amelia Hassett | Kentucky | LA Sparks |
| 36 | Charlise Dunn | Davidson | Toronto Tempo |
| 37 | Taylor Bigby | TCU | Portland Fire |
| 38 | Kokoro Tanaka | Japan | Golden State Valkyries |
| 39 | Grace VanSlooten | Michigan State | Seattle Storm |
| 40 | Jessica Timmons | Alabama | Indiana Fever |
| 41 | Manuela Puoch | Australia | New York Liberty |
| 42 | Eszter Ratkai | Hungary | Phoenix Mercury |
| 43 | Kejia Ran | China | Atlanta Dream |
| 44 | Jordan Obi | Kentucky | Las Vegas Aces |
| 45 | Lani White | Utah | Minnesota Lynx |

---

## The Coach Pipeline Numbers

| Coach | Program | Pipeline Stat |
|-------|---------|---------------|
| Geno Auriemma | UConn | 52 WNBA draftees, 7 No. 1 overall picks, most in history |
| Dawn Staley | South Carolina | 21 WNBA picks, 11 first rounders, 2 No. 1 overalls |
| Cori Close | UCLA | 6 players drafted in one night, all-time single-draft record |
| Kim Mulkey | LSU | 26 career WNBA picks, 19 at Baylor, 7 at LSU, Hall of Fame |
| Mark Campbell | TCU | 15 career WNBA picks, 3 from TCU alone tonight |
| Yolett McPhee-McCuin | Ole Miss | 5 career WNBA picks, 2 from the same team on the same night |
| Kenny Brooks | Kentucky | 4 picks in year two, 2025 Sporting News National Coach of Year |
| Kara Lawson | Duke | First 2 WNBA picks of the Kara Era, USA Basketball HC |
| Vic Schaefer | Texas | 6 career WNBA picks across MSU and Texas |
| Kim Caldwell | Tennessee | First 2 WNBA picks of her Tennessee tenure |
| Nicki Collen | Baylor | 5th career WNBA pick, Former WNBA Coach of Year 2018 |
| Courtney Banghart | UNC | 7 seasons building this, Nivar is first Tar Heel to earn it |
| Robyn Fralick | Michigan State | VanSlooten is first WNBA pick of the Fralick era |
| Shea Ralph | Vanderbilt | Pissott is first WNBA pick of the Ralph era, 7x national champion |
| Niele Ivey | Notre Dame | Prosper is the 24th Notre Dame player ever drafted |
| Kevin McGuff | Ohio State | 4 straight years sending players to the WNBA |
| Gayle Fulks | Davidson | First WNBA pick in Davidson program history |
| Gavin Petersen | Utah | Utah Utes produced the last pick of the 2026 WNBA Draft |
| Kristy Curry | Alabama | Developed an NC State transfer into an All-SEC WNBA pick |
| International | No NCAA | No college system, built by global clubs and national federations |

---

## The Ole Miss Pipeline

Coach Yo (Yolett McPhee-McCuin) produced 5 total WNBA picks, including 2 in the same draft going to the same team on the same night:

| Player | Year | Pick | Team | Status |
|--------|------|------|------|--------|
| Shakira Austin | 2022 | No. 3 overall | Washington Mystics | Active, re-signed April 2026, 2025 AP Comeback POTY |
| Marquesha Davis | 2024 | No. 11 overall | New York Liberty | 2024 WNBA Champion, currently overseas (Botaş SK, Turkey) |
| Madison Scott | 2025 | No. 14 overall | Dallas Wings | Played 9 games for Mystics in 2025, currently overseas (Geas Basket, Italy) |
| Cotie McMahon | 2026 | No. 11 overall | Washington Mystics | Just drafted |
| Latasha Lattimore | 2026 | No. 21 overall | Chicago Sky | Just drafted |

---

## The Story

**Yolett McPhee-McCuin** recruited Cotie McMahon as the top forward in the transfer portal and developed her into a first-round pick in one season — 19.5 PPG, 703 points, SEC Newcomer of the Year. Coach Yo saw what Cotie could become before anyone else offered her that stage.

**Empress Davenport** served as associate coach at Ole Miss during the 2025-26 season, responsible for the guard group. On March 27, 2026, Davenport joined the Dallas Wings coaching staff — the same organization that held Pick No. 1 on draft night.

The coach tree doesn't end at graduation.

---

## Files in This Repository

| File | Description |
|------|-------------|
| `wnba-draft-coach-tree.html` | The live interactive viz, main deliverable |
| `README.md` | This file |

---

## Built With

- Vanilla HTML, CSS, JavaScript, no frameworks
- SVG basketball court drawn from scratch
- Inter font via Google Fonts
- School hex codes sourced from official athletics departments
- Staff data verified from program athletics sites, April 2026
- All 45 picks confirmed from official WNBA draft results, April 13, 2026

---

## About

**Kris E. Smith** is a sports data visualization creator and designer operating as **The Black Techie**, based in Atlanta, Georgia. Her work sits at the intersection of women's basketball, editorial storytelling, and interactive data design.

This viz is part of a larger dissertation research project on data visualization as a communication tool in women's basketball, with a companion series on Black female D1 head coaches.

**X/Twitter:** @TheBlackTechie  
**GitHub:** theblacktechie.github.io

---

*Completed post-draft. April 14, 2026.*
