# Concept Deep Dive: Property Board + Minigames + Betting

*November 2026. Follows [MARKET_ANALYSIS.md](MARKET_ANALYSIS.md). Steam sales figures are third-party estimates unless a developer announced them.*

## The concept as pitched

- **Board:** a Monopoly-style loop. Roll, land, buy or pay. Invest in property to raise its income.
- **Events:** landing triggers quirky random events or Mario Party-style minigames.
- **Betting layer:**
  - Wager on who wins each minigame.
  - Prop bets on dice ("who rolls the higher combo over the next 3 rolls").
  - The **property owner earns from the action on their block**: either a cut of the betting pool, or an advantage in the minigame.
- **Players:** 2–8, with a **Duo mode**. Some minigames are automatically 2v2.
- **Minigames:** ~30 solo and ~10 duo, each **inspired by a famous game or mode from the last 15 years** (a 360-no-scope duel, a Griffball/Infection-style mode, a "mine a diamond from nothing" race). Clumsy, chaotic, fun.

---

## 1. Short answer: is this already a thing?

**No one has this exact combination. But every piece of it already exists in some form, and two games sit very close:**

1. **WE'RE ALL IN!** *(launching Nov 20, 2026, 12 days from now)*: "Bet on your friends" in fast minigames.
2. **Fortune Avenue** *(2025, Early Access)*: Monopoly-style board with stocks and minigames. It flopped.

The part that's original: **owning property makes you "the house" for the minigames played there.** Landlords choose between taking a cut of the bets or rigging the game in their favor. Nothing I found does that. **That mechanic, not "Monopoly + minigames," should be the pitch.**

---

## 2. Overlap map

### 2.1 Direct overlap: watch these closely

| Game | Overlap with your concept | Status / numbers | What it tells you |
|---|---|---|---|
| **WE'RE ALL IN!** (Blast Furnace Games / Black Lantern Collective) | **Betting on friends in minigames.** 1–8 players online, fictional chips and stars, 1v1, team modes and free-for-alls. Demo has 20 minigames. Formerly titled "DOPAMINE". | Full release **Nov 20, 2026**; demo out since Oct 15, 2026 ([Steam](https://store.steampowered.com/app/4183130/WERE_ALL_IN/), [Gamerscore](https://www.gamerscore.com.br/were-all-in-mini-games-com-apostas-chega-ao-steam-com-demo-gratis/), [PopTopic](https://poptopic.com.au/entertainment/games/were-all-lets-you-bet-which-friend/)) | **This is your closest competitor, and its launch is free market research.** As far as I could find, it has no property board. If it hits, betting on friends is proven but taken, and you must win on the landlord/board layer. If it flops, look at why. |
| **Fortune Avenue** (Binogure Studio) | **Monopoly-style board + stocks + minigames**, voting on rule changes, up to 6 online | EA since Apr 2025, $6.99, ~70 reviews (82% positive), **~3 average concurrent players** ([GamingOnLinux](https://gamingonlinux.com/2025/02/fortune-avenue-is-a-hyped-up-fast-paced-chaotic-spin-on-monopoly), [Datahumble](https://datahumble.com/fortune-avenue-1810050)) | **"Monopoly + minigames" alone isn't a hook.** Positive reviews, almost no audience. It never got streamer pull. |
| **Mario Party wager mechanics** | Duels where players stake coins or Stars; Game Guy all-in gambles (MP3); Mic bet spaces (MP7) ([Super Mario Wiki](https://www.mariowiki.com/Mario_Party_(series))) | Long-standing | Betting on *yourself* is a known mechanic. Betting on *others* while *owning the venue* isn't. |

### 2.2 Adjacent proof: the pieces sell

| Game | Which piece it proves | Numbers |
|---|---|---|
| **Machine Party** (Buckshot Roulette dev, Jul 2026) | Mario Party-style minigames with stakes sell **right now** | **1M copies in ~2 weeks**, ~22.6K peak CCU, 87–92% positive ([Game Developer](https://www.gamedeveloper.com/press-release/machine-party-sells-over-500-000-copies-in-its-first-week-reaching-20-000-concurrent-players), [WN Hub](https://wnhub.io/news/investment/item-51757)) |
| **Gamble With Your Friends** (May 2026) | Money and gambling chaos with friends | **1M copies in week one**, ~37–43K peak CCU ([GameReactor](https://www.gamereactor.eu/the-latest-friendslop-hit-is-here-as-gamble-with-your-friends-sells-a-million-copies-in-less-than-two-weeks-1716843/)) |
| **Momotaro Dentetsu** (Konami, Switch) | **Property board games can be huge.** Buy properties in cities, collect income, random events | **3.5M+** (2020 game); the 2025 sequel passed 1M. Japan only, never localized ([Nintendo Life](https://www.nintendolife.com/news/2021/05/momotaro_dentetsu_surpasses_three_million_sales_on_switch_yet_its_still_exclusive_to_japan), [Gematsu](https://www.gematsu.com/2026/03/momotaro-dentetsu-2-anata-no-machi-mo-kitto-aru-higashi-nihon-hen-nishi-nihon-hen-shipments-and-digital-sales-top-one-million)) |
| **Pummel Party** | Board + minigames on PC has a long tail | Est. 0.85–2.1M Steam copies since 2018 |
| **Dokapon Kingdom: Connect** | Friendship-ruining board game with betrayal | Est. ~24K Steam copies at $49.99, 87% positive ([Raijin](https://raijin.gg/app/2338140/Dokapon_Kingdom_Connect)) |
| **Business Tour / Rento Fortune** | Plain online Monopoly clones | Business Tour: ~197K owners (free), 60% positive. Commodity tier. |

### 2.3 Overlap on "minigames that riff on famous games"

| Example | Notes |
|---|---|
| **Game Soup** (Steam, 2019) | 46 microgames, "including parodies of famous games." Small, not a hit. |
| **Roblox / Fortnite UEFN** | *Epic Minigames* (Roblox) is effectively Mario Party with 130+ challenges, many riffing on popular modes. Fortnite Creative has board-plus-minigame islands. **Your target audience already gets "a minigame of every popular game" for free.** |
| **Garry's Mod modes** | Prop Hunt, TTT, Murder: the original "familiar game mode as a party game" format. |

**Takeaway:** "a minigame version of popular games" helps players understand a minigame instantly. It isn't a unique selling point by itself, because Roblox already does it at a huge scale.

---

## 3. What's strong (keep and push)

### ✅ 3.1 Betting fixes the 8-player downtime problem
This is the best idea in the concept. Mario Party caps at 4 because waiting is boring. With 8 players, most people are watching most of the time. **Betting turns watching into playing.** Everyone not in a minigame has money riding on it, so they shout at the screen, and that's the stream content. It's the main reason 8 players can work.

### ✅ 3.2 The landlord choice is new
> "Do I take the house cut, or do I play with an advantage?"

That's a real decision with risk on both sides, it's easy to understand on stream, and it ties the board to the minigames. (In Fortune Avenue and most Mario Party clones, the board and the minigames barely interact.) **Build the whole pitch around this.**

### ✅ 3.3 Duos are a real feature
Duos give 8 players a structure (4 teams of 2) and give friend pairs a reason to buy together. Shared wallets, carrying a teammate, and blaming your partner all make good clips. Mario Party's Partner Party and Superstars team modes show the appeal. Your twist is **betting against your own partner**.

### ✅ 3.4 Recognizable references are instantly readable on stream
A viewer who sees a "360 no-scope only" round understands it in one second. That's very valuable for clips and thumbnails.

---

## 4. What's risky (fix before building)

### ⚠️ 4.1 "The same Monopoly board" carries two risks

**Legal:**
- Hasbro protects **Monopoly's name, street names, Chance and Community Chest, Go to Jail, the mascot, and the board's look**. Commentators describe the board layout as protected trade dress. Hasbro sued a lookalike (*Ghettopoly*) over mimicked packaging and logos ([ABA](https://www.americanbar.org/groups/intellectual_property_law/resources/landslide/archive/not-playing-around-board-games-intellectual-property-law/), [Wikipedia: Ghettopoly](https://en.wikipedia.org/wiki/Ghettopoly)).
- Game *mechanics* (roll, buy, rent) are not protected, and hundreds of clones exist.
- **Safe path:** a loop board with your own names, layout, art, corners and card decks.

**Design:** Monopoly is a *slow* game. If you copy its pacing, you copy these problems:

| Monopoly problem | Fix |
|---|---|
| Bankruptcy knocks players out, so they sit and watch | **No elimination.** Broke players become "debt collectors" or bet with a loan. |
| Games run 90+ minutes | **Hard round cap**: 10–15 rounds, 30–45 minute target. |
| One leader snowballs | Catch-up mechanics: market crashes, tax events, bounties on the leader. |
| Trading negotiations drag | 20-second timed offers, or drop trading. |
| 8 players taking turns one at a time is slow | Fast auto-move, 10-second buy timer, and bets placed during other players' turns. |

### ⚠️ 4.2 40 minigames at launch is too many
Machine Party sold 1M copies with **15 minigames**. Pummel Party launched with far fewer than it has now. Each good minigame takes about **2–6 weeks** to build, network, balance and polish. 40 of them is years of work for a small team.

**Launch with 12–15** (about 10 free-for-all and 3–5 duo/2v2), each one polished and replayable. Add more in free updates; each update is a marketing beat. Get to 30–40 over the first year.

### ⚠️ 4.3 Homage minigames need guardrails
- **Legal:** a mode or idea (infection, a gun game, a mining race, a sports mode played with guns) **is fine**. Names (*Griffball*, *Minecraft*, *Halo*), characters, art style, sounds, UI and logos **are not**. Make it look like *your* game playing a joke on the *genre*.
- **Fit:** every homage has to work in **30–90 seconds with the same simple controls**. "Mine a diamond from nothing" is a 20-minute Minecraft activity. Cut it down: a small pre-built cave, 60 seconds, pickaxes only, first to the gem wins, and tunnels collapse on people.
- **Pick genres, not games.** "Battle royale circle in 60 seconds," "extraction run," "tower defense where your opponent is the creeps," "rhythm game while getting shoved," "no-scope only," "infection," "kart race with one lap." These age better and carry less legal risk than one specific franchise.

### ⚠️ 4.4 Watch the betting load
Three betting layers (minigame bets, dice prop bets, landlord cuts) can bury new players. **Keep one main bet per minigame**: pick a winner, choose an amount, done in 10 seconds. Dice prop bets should be an occasional "side market" event, not every turn. Dice-on-dice bets are pure luck, so keep them small.

### ⚠️ 4.5 Gambling framing
- On Steam, betting with in-game money is fine.
- On consoles, simulated **casino** gambling triggers **PEGI 18**.
- Keep the presentation as **sports betting / stock market / bookie** rather than slots or roulette.
- **Never sell randomized items for real money.** Since mid-2026, PEGI rates paid loot boxes 16+.

---

## 5. Suggested core loop, built around the house edge

```
┌──────────────────────────── ROUND (≈3 min with 8 players) ────────────────────────────┐
│ 1. ROLL & MOVE   (all turns quick; others place side bets while you move)              │
│ 2. LAND ON:                                                                            │
│    • Empty lot   → Buy it (10s timer)                                                   │
│    • Your lot    → Upgrade it (raise the house edge / rent)                             │
│    • Owned lot   → RENT DUEL: pay rent, or challenge the landlord: double or nothing    │
│                    1v1 minigame. Landlord picks:  🏦 TAKE THE HOUSE CUT (sit out,        │
│                    earn % of all bets)  or  🎯 PLAY RIGGED (fight with an advantage)    │
│                    Everyone else BETS on the outcome.                                   │
│    • Event space → quirky random event (market crash, tax audit, bribe, swap lots)      │
│ 3. END OF ROUND  → ALL-PLAYER MINIGAME (FFA or 2v2) in the district with the most       │
│                    upgrades. That district's owner takes the house cut.                 │
└────────────────────────────────────────────────────────────────────────────────────────┘
WIN: highest net worth after 12 rounds (cash + property + winnings). No elimination.
```

**Pitch line:** *"Own the block. Rig the game. Take the house cut."*

This keeps everything you described (buy, invest, events, minigames, betting, landlord payouts). The board and the minigames feed each other, and no one goes long without a decision.

---

## 6. Are you hitting a stride?

| Element | Original? | Proven demand? | Verdict |
|---|---|---|---|
| Property board | ❌ Common | ✅ Momotaro 3.5M+, but Monopoly clones flop on Steam | Keep as the *foundation*, not the hook |
| Mario Party-style minigames | ❌ Common | ✅ Machine Party 1M in 2 weeks | Must-have; quality beats quantity |
| Betting on friends in minigames | ⚠️ WE'RE ALL IN! launches Nov 20 | ✅ Money-and-friends chaos is selling | Strong, but you might not be first |
| **Landlord = the house (cut vs rigged advantage)** | ✅ **Not found anywhere** | — | **Your real hook. Lead with it.** |
| Duo mode with betting against your partner | ✅ Uncommon combination | ✅ Team modes are popular | Strong differentiator |
| Homage minigames | ❌ Roblox/UEFN/Game Soup do it | ✅ Instantly readable | Good for marketing, not an identity; keep it legally clean |
| 2–8 players | ✅ Rare for board party games (most cap at 4) | — | Only works *because* of betting |

**Verdict:** you're onto something, but not because the idea is unclaimed. Each piece exists. What's new is that **the board feeds the betting, and the betting feeds the board**, and that hasn't been done. A small team can win here with a **tight, fast, 12–15-minigame game that makes the house-edge moment feel huge on stream**. It doesn't win as "Monopoly + 40 minigames."

---

## 7. Next steps (in order)

1. **Now:** play the **WE'RE ALL IN!** demo and **Fortune Avenue**. Note what's fun, what drags, and what players complain about in reviews.
2. **Nov 20–Dec 20:** track WE'RE ALL IN!'s launch: peak players, review score, top complaints, and which streamers pick it up. That's your clearest demand signal for the betting layer.
3. **Paper prototype (1 week):** a printed board, dice, poker chips and phone-timer "minigames" (arm wrestling, rock-paper-scissors, a quick round of a real game). Test the **house cut vs rigged** decision and the 8-player betting flow. If that isn't fun on a table, no amount of polish will fix it.
4. **Digital grey-box (6–8 weeks):** board, Rent Duel, betting UI, and **3 minigames** (one shooter homage, one race, one 2v2), playable online.
5. **Then** follow the go/no-go gates in [MARKET_ANALYSIS.md](MARKET_ANALYSIS.md) (Steam page → wishlists → Next Fest).

---

### Sources
- WE'RE ALL IN!: [Steam](https://store.steampowered.com/app/4183130/WERE_ALL_IN/) · [Steam demo](https://store.steampowered.com/app/5285180/WERE_ALL_IN_Demo/) · [PopTopic](https://poptopic.com.au/entertainment/games/were-all-lets-you-bet-which-friend/) · [Gamerscore Brasil](https://www.gamerscore.com.br/were-all-in-mini-games-com-apostas-chega-ao-steam-com-demo-gratis/)
- Fortune Avenue: [GamingOnLinux](https://gamingonlinux.com/2025/02/fortune-avenue-is-a-hyped-up-fast-paced-chaotic-spin-on-monopoly) · [GamingOnLinux EA launch](https://www.gamingonlinux.com/2025/04/love-board-games-and-pure-chaos-fortune-avenue-is-a-new-spin-on-monopoly-out-in-early-access) · [Datahumble](https://datahumble.com/fortune-avenue-1810050)
- Machine Party: [Game Developer](https://www.gamedeveloper.com/press-release/machine-party-sells-over-500-000-copies-in-its-first-week-reaching-20-000-concurrent-players) · [WN Hub](https://wnhub.io/news/investment/item-51757) · [Raijin](https://raijin.gg/app/4108000/Machine_Party)
- Momotaro Dentetsu: [Nintendo Life](https://www.nintendolife.com/news/2021/05/momotaro_dentetsu_surpasses_three_million_sales_on_switch_yet_its_still_exclusive_to_japan) · [Gematsu](https://www.gematsu.com/2026/03/momotaro-dentetsu-2-anata-no-machi-mo-kitto-aru-higashi-nihon-hen-nishi-nihon-hen-shipments-and-digital-sales-top-one-million)
- Dokapon Kingdom: Connect: [Raijin](https://raijin.gg/app/2338140/Dokapon_Kingdom_Connect)
- Mario Party wagers: [Super Mario Wiki](https://www.mariowiki.com/Mario_Party_(series)) · [TV Tropes – Betting Mini-Game](https://tvtropes.org/pmwiki/pmwiki.php/Main/BettingMiniGame)
- Homage/minigame collections: [Steambase – Game Soup](https://steambase.io/games/game-soup/info) · [Fortnite.gg – party island](https://fortnite.gg/island/1298-8637-7262/info)
- Monopoly IP: [ABA Landslide](https://www.americanbar.org/groups/intellectual_property_law/resources/landslide/archive/not-playing-around-board-games-intellectual-property-law/) · [Wikipedia – Ghettopoly](https://en.wikipedia.org/wiki/Ghettopoly) · [Mondaq – board game trade dress](https://webiis08.mondaq.com/unitedstates/trademark/1433628/trademark-protection-for-board-games-unlock-the-potential-of-trade-dress-for-your-board-game)
- Gamble With Your Friends: [GameReactor](https://www.gamereactor.eu/the-latest-friendslop-hit-is-here-as-gamble-with-your-friends-sells-a-million-copies-in-less-than-two-weeks-1716843/)

*Not legal advice. Have an IP attorney review the board design and any homage minigames before launch.*
