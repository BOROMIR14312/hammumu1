# 🔨 HAMMUMU

**Bonk the noobs. Spare the pros. Survive.**

A zero-dependency whack-a-mole roguelite(-ish) built in one HTML file. No build step, no frameworks, no mercy.

## How to play

Open `index.html` in a browser. That's it. You get **3 lives** and **45 seconds**, spread across three escalating waves.

### The cast

| Who | What | Worth |
|-----|------|------:|
| 😵 Noob (orange) | the classic. bonk it | **+10** |
| 🥷 Ninja noob | pops for a fraction of a second | **+25** |
| 🪖 Tank noob | helmet — takes **two** hits | **+35** |
| 😏 Dodger | **jumps to another hole when you hover it** | **+20** |
| ✨ Golden noob | rare, basically a rumor | **+50** |
| ⏰ Clock | adds time | **+4 s** |
| 😎 Pro (green) | do NOT bonk | **−15 and −1 life** |
| 💣 Bomb | really do NOT bonk | **−30 and −1 life** |

### Mechanics

- **Waves** — Wave 2 at 15 s (the noobs drank coffee ☕), Wave 3 at 30 s (send help 💀). More enemies, faster pops, double and triple spawns.
- **Combo** — chain scoring hits for a bonus (up to +10 per hit). Missing, pros, and bombs reset it.
- **🔥 FEVER** — reach combo ×8 and everything doubles for 6 seconds. Everything also gets faster. Good luck.
- **Lives** — lose all 3 and you're KNOCKED OUT before the clock even runs out.

## 👥 Multiplayer

On the claude.ai-published version, the game has live multiplayer:

- **Rooms** — create a room, share the 4-letter code, friends join from the same page.
- **Live matches** — anyone hits START MATCH and everyone in the room gets a synchronized 3-2-1 countdown into the **same seeded run** (identical enemy sequence — a fair race). Opponents' scores update live above your board while you play.
- **Match standings** — podium with medals when everyone finishes. 👑 for the winner.
- **🏆 Hall of Bonk** — a persistent shared leaderboard (top 10 all-time) with real names.

This copy of the file degrades gracefully: opened from disk or GitHub Pages it's solo-only, since multiplayer rides on the claude.ai artifact runtime (`room`, `db`, and `user` capabilities — real-time presence for the racing, a shared document store for the leaderboard).

## Ranks

| Score | Rank |
|------:|------|
| 600+  | HAMMUMU GOD 🔱 |
| 450+  | Certified Bonker 🔨 |
| 300+  | Semi-Pro Smasher 💪 |
| 150+  | Apprentice of the Hammer 🪵 |
| less  | Official Noob (it's in the repo name) 🐣 |

Best score is saved in your browser.

---

*Built for fun by Claude, at the request of a human who said, verbatim, "just have fun." Then they said "make it harder, make it more complex," which is on them.*
