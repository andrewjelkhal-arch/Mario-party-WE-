# Market Analysis: "Capitalist Party Game"

*Prepared November 2026. Sales figures for Steam games are third-party estimates (Raijin, SteamData.AI, Gamalytic, GameDiscoverCo, AppMagic) unless a developer announced them. Valve doesn't publish sales, and the trackers often disagree by 2x or more. Read them as order-of-magnitude numbers.*

**The concept:** a fast, chaotic online board game. Players roll and move, buy property and stock, and settle fights with short arena minigames (*Pummel Party*). The economy is the core (*Fortune Street*), and bluffing and betrayal set the tension (*Liar's Bar*).

**The earlier verdict being tested:** "Yes, 100%. It is a massive blind spot on Steam, infinitely streamable, and much more achievable to scope than an open-world or shooter game."

---

## 1. Bottom line

**Verdict: worth pursuing, as a staged bet with kill criteria. The "Yes, 100%" verdict doesn't hold up.**

| Claim | What the data says | Rating |
|---|---|---|
| "Massive blind spot on Steam" | **Partly true.** There's no strong *economy-first* party board game on Steam. Monopoly-likes there are weak or dead. But the "money + friends + chaos" idea is not unclaimed. *Gamble With Your Friends* sold **1M copies in its first week** (May 2026) with a money theme. *Pummel Party* still owns the "Mario Party on PC" slot. | ⚠️ Overstated |
| "Infinitely streamable" | **True for the right design.** *Liar's Bar* went from ~2K to **100K+ concurrent players in 3 weeks**, driven by streamers. But the hits that streamers carry are cheap, short-session, voice-chat games. A 60-minute board game is a harder fit. | ✅ True, with a design condition |
| "Achievable for a small team" | **Easier than a shooter or open world, but not small.** Online multiplayer for 4–8 players (netcode, reconnects, lobbies), plus the 20–40 minigames needed for replay value, is real work. | ⚠️ Underestimated |
| "We can make money" | **Possible, but the base rate is brutal.** The median Steam game released in 2025 grossed **$249**. 66% grossed under $1K, and only ~10% passed $50K. | ❌ Not guaranteed by the genre |

The opportunity is real. It needs to be a **short-session, bluff-first, cheap, streamer-friendly** game, not a full digital Fortune Street. Validate it cheaply before committing a year.

---

## 2. Market landscape

### 2.1 Demand signals (strong)

| Title | What it proves | Key numbers |
|---|---|---|
| **Super Mario Party Jamboree** (Switch, 2024) | Mass demand for digital party board games | 6.17M units in ~10 weeks, fastest-selling Mario Party; 7.48M by Mar 2025 ([VGC](https://videogameschronicle.com/news/super-mario-party-jamboree-marked-the-series-biggest-launch-with-6m-shipped), [GamingBolt](https://gamingbolt.com/super-mario-party-jamboree-has-sold-6-17-million-units)) |
| **Pummel Party** (PC 2018, consoles 2024) | Mario Party demand on PC is real and has a long tail | Est. 0.85M–2.1M Steam copies, $8M–$19M gross; all-time peak ~16–21K CCU; still ~1.5–2K avg players in mid-2026, with spikes to ~15K ([Raijin](https://raijin.gg/app/880940/Pummel_Party), [SteamData.AI](https://steamdata.ai/game/880940), [Steambase](https://steambase.io/games/pummel-party)). No sequel announced. |
| **Liar's Bar** (Oct 2024) | Bluffing and tension plus streamers can make a viral hit | 2K CCU at launch → **100K+ CCU within 3 weeks**; est. ~2.2M copies ([Game World Observer](https://gameworldobserver.com/2024/10/21/liars-bar-100k-ccu-steam-curve-animation-turkey-success), [Raijin](https://raijin.gg/app/3097560/Liars_Bar)) |
| **Buckshot Roulette** (2023–24) | High-stakes gambling tension sells | **8M copies on PC** (developer milestone, Dec 2025) at $2.99 ([KitGuru](https://www.kitguru.net/gaming/joao-silva/buckshot-roulette-hits-8-million-sales-console-port-gets-delayed/)) |
| **Gamble With Your Friends** (May 2026) | **Money-themed friend chaos is the closest live comparable** | 1M copies in first week, ~37–43K peak CCU, $7.99. Co-op (shared wallet versus a loan shark), not competitive ([GameReactor](https://www.gamereactor.eu/the-latest-friendslop-hit-is-here-as-gamble-with-your-friends-sells-a-million-copies-in-less-than-two-weeks-1716843/), [Automaton](https://automaton-media.com/articles/newsjp/20260504-441051/)) |
| **"Friendslop" wave** (2025) | Cheap social multiplayer dominated Steam's top sellers | R.E.P.O. (~18.5M) and Peak (~15.4M) were #1 and #2 Steam sellers of 2025; 4 friendslop titles in the top 10 ([Kotaku](https://kotaku.com/steam-top-selling-2025-friendslop-rpgs-sales-2000654157), [AppMagic](https://appmagic.rocks/blog/friendslop-steam-games-2025)) |

### 2.2 Warning signals (just as important)

| Title | What it warns about | Key numbers |
|---|---|---|
| **Monopoly Madness** (Ubisoft, Steam 2023) | A big brand plus a property board doesn't sell on its own | ~94 Steam reviews, **~43% positive (Mixed)**; peak 29 CCU; discounted 75% ([Datahumble](https://datahumble.com/monopoly-madness-2383760), [GG.deals](https://gg.deals/ca/game/monopoly-madness/)) |
| **Fortune Avenue** (indie, EA Apr 2025) | **The closest concept on Steam (Monopoly + stocks + minigames) is barely noticed** | ~70 reviews (82% positive), **~3 average CCU**, $6.99 ([Datahumble](https://datahumble.com/fortune-avenue-1810050), [GamingOnLinux](https://gamingonlinux.com/2025/02/fortune-avenue-is-a-hyped-up-fast-paced-chaotic-spin-on-monopoly)) |
| **Business Tour** (free-to-play Monopoly clone) | The audience exists but treats it as a commodity | ~197K owners, 80K reviews at only 60% positive, ~500 CCU ([Raijin](https://raijin.gg/app/397900/Business_Tour__Board_Game_with_Online_Multiplayer)) |
| **LEGO Party** (Sept 2025, multi-platform) | Even a licensed Mario Party clone can stall on Steam | Est. 13–33K Steam copies; peak ~780–850 CCU, falling fast despite 84–88% positive reviews ([Raijin](https://raijin.gg/app/1969370/LEGO_Party), [Sensor Tower](https://app.sensortower.com/vgi/game/lego-party)) |
| **Friendslop retention** | Viral party games spike and fade | Average **D30 retention ≈ 3%** for the genre ([AppMagic via GameDev Reports](https://gamedevreports.substack.com/p/appmagic-friendslop-games-in-2025)) |

**Why the warnings matter:** the "Fortune Street on PC" idea has already been tried several times (Fortune Avenue, Monopoly Madness, Business Tour, Rento Fortune), and none broke out. The "blind spot" exists because **slow, rules-heavy property games don't fit how PC players buy social games now**. The hits (*Liar's Bar*, *Buckshot*, *Gamble With Your Friends*, *R.E.P.O.*) share four traits:

1. **Cheap:** $3–$10. Friend groups buy 4 copies at once.
2. **Short rounds:** 5–20 minutes. They're clippable and streamable.
3. **Voice-chat drama is the content:** lying, betrayal, screaming.
4. **Rules learned in under 60 seconds.**

A traditional 45–90-minute board game breaks traits 2 and 4. **The design has to fit these four traits, or it will end up in the Fortune Avenue column.**

### 2.3 Competitive positioning

```
                    COMPETITIVE / BETRAYAL
                            ▲
              Liar's Bar    │    ★ YOUR GAME (target)
           Buckshot Roulette│    bluff + economy + minigames
                            │
   SHORT / CHEAP ───────────┼─────────── LONG / BOARD
                            │      Pummel Party
     Gamble With Your Friends   Mario Party, LEGO Party
          R.E.P.O., Peak    │   Fortune Avenue, Monopoly Madness
                            ▼   Business Tour
                       CO-OP / CASUAL
```

The empty corner is: **competitive, betrayal-driven, economy-centric, short sessions**. No strong title holds it. *Gamble With Your Friends* is the nearest threat, because a competitive mode or sequel from that studio would move straight into this space.

---

## 3. Steam economics (the base rate)

From 2025 Steam release data (~15–20K new games) ([Gamalytic via 80.lv](https://80.lv/articles/analysts-report-drop-in-game-revenue-on-steam-despite-growing-number-of-releases), [PC Gamer](https://www.pcgamer.com/games/with-over-13-000-new-games-on-steam-this-year-so-far-over-a-third-of-them-havent-even-made-enough-to-break-even-on-valves-submission-fee), [Game World Observer](https://gameworldobserver.com/2025/12/22/indie-projects-generated-a-quarter-of-the-total-game-revenue-on-steam-by-the-end-of-2025-analytics)):

- **Median gross revenue: $249**
- 40% didn't earn back the $100 Steam fee
- 66% grossed under $1,000
- ~10% grossed $50,000+
- Indie games as a group earned ~$4.4B, so the money is there, but it's extremely concentrated.

**Wishlist inflation:** First-month sales per wishlist fell from ~0.45 (2020–22) to **~0.22 (2023–25)**. You need roughly twice the wishlists you did a few years ago for the same launch ([Chris Zukowski analysis via WN Hub](https://wnhub.io/news/analytics/item-52409), [GameDiscoverCo](https://gamedevreports.substack.com/p/gamediscoverco-the-state-of-steam)).

### Revenue scenarios ($7.99 launch price)

Net to the developer is roughly **50–55% of gross** after Steam's 30%, refunds, VAT and regional pricing.

| Scenario | Rough odds for a well-made, well-marketed game in this niche | Copies (yr 1) | Gross | **Net to you** |
|---|---|---|---|---|
| Miss | Most likely | < 5K | < $40K | **< $20K** |
| Solid niche | Plausible | 20–50K | $160–400K | **$80–220K** |
| Hit (Pummel Party-tier, year one) | Unlikely | 200–500K | $1.6–4M | **$0.8–2.2M** |
| Breakout (Liar's Bar / GWYF-tier) | Lottery | 1–2M+ | $8–16M | **$4–8M** |

The genre's ceiling is very high. The floor is near zero. **Marketing traction before launch (wishlists, streamer interest) decides which row you land in far more than the genre does.**

---

## 4. Build feasibility

**Easier than a shooter or open world:**
- Turn-based board movement is easy to sync over the network.
- Minigames are small, separate scenes that can be built and tested one at a time.
- Stylized low-poly art is accepted, even preferred, in this genre.

**Underestimated by the earlier verdict:**
- **Online multiplayer is most of the risk.** You need lobbies, invites, host migration or dedicated relay, reconnect after disconnect, and anti-stall timers. Steam's networking (Steamworks / Steam Datagram Relay) plus an off-the-shelf layer (e.g., Netcode for GameObjects, Mirror, FishNet, or Godot's high-level multiplayer) gets you most of the way.
- **Minigame count drives replay value.** Pummel Party's long tail comes from variety. Plan for ~15 minigames at launch and 30+ within a year.
- **Balancing a bluff economy is hard.** You must stop runaway leaders and make betrayal feel fair, not just random.
- **Matchmaking with strangers rarely works** for party games. The game must be fully playable with 2–4 friends, plus bots to fill seats.

**Rough scope (small team of 2–3, or a dedicated solo dev):**

| Phase | Duration | Output |
|---|---|---|
| Paper/grey-box prototype | 4–8 weeks | Core loop playable online with 4 people, 3 minigames |
| Vertical slice + Steam page | +2–3 months | 1 board, 8–10 minigames, trailer, demo |
| Early Access launch | +4–6 months | 2 boards, 15+ minigames, bots, polish |
| **Total to EA** | **~9–12 months** | |

---

## 5. Risks

| Risk | Severity | Mitigation |
|---|---|---|
| **Discoverability:** the median game makes $249 | 🔴 High | Steam page live by month 3; Next Fest demo; streamer outreach as a core task, not an afterthought |
| **Fast-follow / incumbents:** a GWYF competitive mode, Pummel Party 2, a Liar's Bar update | 🟠 Medium | Ship fast; own a specific hook ("lie about your portfolio") that a mode update can't copy |
| **"Too board-gamey":** turns are slow, downtime kills streams | 🟠 Medium | Simultaneous turns; 15–25 min matches; a cap on turn time; something to do while waiting (betting, sabotage) |
| **Low retention** (genre D30 ≈ 3%) | 🟠 Medium | Plan finances around the launch spike; Workshop and mod support for a long tail (worked for Pummel Party) |
| **Rating / platform: simulated gambling** | 🟡 Low on Steam, Medium on consoles | PEGI rates simulated gambling **PEGI 18** (since 2020); paid loot boxes default to PEGI 16 from mid-2026 ([Osborne Clarke](https://www.osborneclarke.com/insights/games-loot-boxes-get-16-plus-age-rating-europe-under-pegi-overhaul)). Keep the theme as **stocks, bribes, takeovers**, not casino slots or roulette, and **never sell randomized items for real money** |
| **Online multiplayer complexity** | 🟠 Medium | Use Steam Datagram Relay and an existing netcode library; lock netcode early; build every minigame on one shared networking template |

---

## 6. Recommended product direction

To land in the empty quadrant instead of the Fortune Avenue column:

1. **The hook is the lie, not the board.** Each turn, players make a hidden or bluffed economic move: declare a stock pick, accuse someone of insider trading, offer a bribe, call a bluff. A caught liar is punished on screen. That moment is the clip streamers post.
2. **15–25 minute matches.** Short enough to replay; long enough for grudges to form.
3. **Minigames are confrontations, not interludes.** Hostile takeover = 1v1 arena duel. Market crash = free-for-all scramble. Minigames should move money, not only award stars.
4. **4 players first, 8 later.** Launch at $7.99 with a possible 4-pack discount.
5. **Built for streams:** a big readable UI, dramatic reveals, an optional chat/audience vote ("Crowd Sabotage"), and a "Streamer mode" hiding lobby codes.
6. **Theme:** cutthroat Wall Street satire (fits "Capitalist Party"). Stays out of casino imagery and its PEGI 18 risk, and differs visually from Liar's Bar and Buckshot.

---

## 7. Go / No-Go plan with kill criteria

Make one small bet at a time, and let the market decide each next step.

| Gate | When | Pass criteria | If it fails |
|---|---|---|---|
| **G1: Fun test** | Week 6–8 | 4-player online prototype. Testers ask to play again *without prompting* in ≥ 3 of 5 sessions. At least one "clip-worthy" moment per match. | Rework the core loop once; kill if still flat |
| **G2: Market signal** | Steam page + 60–90 days | **≥ 5–7K wishlists** before Next Fest. Trailer CTR / page conversion in line with genre (use GameDiscoverCo / How To Market A Game benchmarks). | Re-pitch hook/art; kill if < 2K after rework |
| **G3: Creator signal** | Next Fest demo | ≥ 10–20 mid-size creators (10K–200K subs) play the demo unpaid; at least one clip with views well above the creator's average | Hold launch; iterate demo |
| **G4: Launch readiness** | Pre-EA | **≥ 20–30K wishlists** (inflation-adjusted target for a meaningful launch) | Delay launch rather than launch quietly |

**Budget guidance:** cap spending before G2 at what you're comfortable losing completely. Most of the cost is time. Treat G2 wishlists as the real investment decision.

---

## 8. Final verdict

- **Is there a market?** Yes. Party board games and "money + friends + chaos" games are proven, multi-million-unit categories, and the competitive bluff-economy space has no strong owner.
- **Is it a guaranteed blind spot?** No. The Monopoly-on-Steam approach has failed repeatedly, and *Gamble With Your Friends* shows others are already circling the money-themed party space.
- **Can it make money?** Yes, if it's built as a short, cheap, bluff-driven, streamer-first game and gets past the wishlist gates. Expect a lottery-shaped outcome: most likely modest, with a real chance of a hit.
- **Recommendation:** **build the 6–8 week prototype now** and decide on the full build at G2 based on wishlist data, not conviction.

---

### Sources

- Pummel Party: [Raijin](https://raijin.gg/app/880940/Pummel_Party) · [SteamData.AI](https://steamdata.ai/game/880940) · [Steambase](https://steambase.io/games/pummel-party) · [Tracker.gg](https://tracker.gg/population/steam/880940?page=1)
- Liar's Bar: [Game World Observer](https://gameworldobserver.com/2024/10/21/liars-bar-100k-ccu-steam-curve-animation-turkey-success) · [Raijin](https://raijin.gg/app/3097560/Liars_Bar) · [Wikipedia](https://en.wikipedia.org/wiki/Liar%27s_Bar)
- Buckshot Roulette: [KitGuru](https://www.kitguru.net/gaming/joao-silva/buckshot-roulette-hits-8-million-sales-console-port-gets-delayed/) · [Raijin](https://raijin.gg/app/2835570/Buckshot_Roulette)
- Gamble With Your Friends: [GameReactor](https://www.gamereactor.eu/the-latest-friendslop-hit-is-here-as-gamble-with-your-friends-sells-a-million-copies-in-less-than-two-weeks-1716843/) · [Automaton](https://automaton-media.com/articles/newsjp/20260504-441051/) · [SteamPulse](https://steampulse.org/game/3892270)
- Mario Party Jamboree: [VGC](https://videogameschronicle.com/news/super-mario-party-jamboree-marked-the-series-biggest-launch-with-6m-shipped) · [GamingBolt](https://gamingbolt.com/super-mario-party-jamboree-has-sold-6-17-million-units)
- Friendslop: [Kotaku](https://kotaku.com/steam-top-selling-2025-friendslop-rpgs-sales-2000654157) · [AppMagic](https://appmagic.rocks/blog/friendslop-steam-games-2025) · [AppMagic retention](https://gamedevreports.substack.com/p/appmagic-friendslop-games-in-2025) · [GamesRadar](https://www.gamesradar.com/games/co-op/we-proudly-wear-the-friendslop-badge-peak-studio-unpacks-one-of-the-biggest-trends-on-steam-and-beyond-after-studying-games-like-repo-to-find-out-what-makes-them-fun/)
- Monopoly-likes: [Fortune Avenue – Datahumble](https://datahumble.com/fortune-avenue-1810050) · [GamingOnLinux](https://gamingonlinux.com/2025/02/fortune-avenue-is-a-hyped-up-fast-paced-chaotic-spin-on-monopoly) · [Monopoly Madness – Datahumble](https://datahumble.com/monopoly-madness-2383760) · [Business Tour – Raijin](https://raijin.gg/app/397900/Business_Tour__Board_Game_with_Online_Multiplayer)
- LEGO Party: [Raijin](https://raijin.gg/app/1969370/LEGO_Party) · [Sensor Tower](https://app.sensortower.com/vgi/game/lego-party)
- Steam economics: [80.lv / Gamalytic](https://80.lv/articles/analysts-report-drop-in-game-revenue-on-steam-despite-growing-number-of-releases) · [PC Gamer](https://www.pcgamer.com/games/with-over-13-000-new-games-on-steam-this-year-so-far-over-a-third-of-them-havent-even-made-enough-to-break-even-on-valves-submission-fee) · [Game World Observer](https://gameworldobserver.com/2025/12/22/indie-projects-generated-a-quarter-of-the-total-game-revenue-on-steam-by-the-end-of-2025-analytics)
- Wishlists: [WN Hub – wishlist inflation](https://wnhub.io/news/analytics/item-52409) · [GameDiscoverCo](https://gamedevreports.substack.com/p/gamediscoverco-the-state-of-steam) · [How To Market A Game survey](https://howtomarketagame.com/salesSurvey/)
- Ratings: [Osborne Clarke – PEGI overhaul](https://www.osborneclarke.com/insights/games-loot-boxes-get-16-plus-age-rating-europe-under-pegi-overhaul)
