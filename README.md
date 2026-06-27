# ⚡ FUSION SQUAD — Elemental Brute Hunt

A **first-person** co-op action game (pure-JavaScript **raycasting engine**, no game libraries).
A huge muscular **BRUTE** hunts you across many themed arenas. You start with **no power** — grab the
elements, **freeze** the Brute when it's close, and **FUSE** all your powers to destroy it. **20 levels**,
play **solo or online with up to 3 players**.

## 🎮 How to play
- You start each round with **NO power**. Grab the element orbs (🔥 Fire, 💧 Water, 🪨 Earth, 🌪️ Wind).
- Your **first orb unlocks FREEZE**. Collect them all, then press **F** to **FUSE** — a blast that destroys the Brute(s) and clears the level.
- **FREEZE** (Space) stops every Brute for **8 seconds** when one gets close.
  - **2 freeze charges** on levels 1–10, only **1** on levels 11–20.

## 🌐 Multiplayer (1–3 players, online co-op)
- **Multiplayer → Create Room** gives you a **4-letter code**. Share it with friends.
- Friends pick **Multiplayer → Join**, type the code, and you play together.
- Co-op-only features:
  - **Shared elements** — orbs anyone grabs count for the whole squad, so split up to gather faster.
  - **Revive** — stand next to a downed teammate to bring them back.
  - **More Brutes** — the enemy count scales up with more players.
- Networking is peer-to-peer (WebRTC via PeerJS) with STUN/TURN relays — no server needed.

## 🗺️ Arenas
8 themed maps + 🎲 *Surprise Me* (a new one each level): Stone Keep, Lava Forge 🌋, Frozen Cavern ❄️,
Crystal Mine, Toxic Swamp ☠️, Sky Temple, Void Arena, Desert Ruins — with hazards (lava/acid/ice),
torches, crystals, and 4 layout styles (open/pillars/rooms/cross).

## ⌨️ Controls
| Action | Keys |
|--------|------|
| Move / strafe | `W` `S` move · `A` `D` turn · `Q` `E` strafe · `Shift` sprint |
| Look | `←` `→` turn · `↑` `↓` up/down · or **mouse** (click to lock) |
| Freeze (8s) | `Space` |
| Fuse | `F` |
| Ping (mark your spot) | `G` |
| Map size | `M` |
| Pause / help | `P` |

**On phone:** drag the **left** side to move, the **right** side to look, and use the **Freeze / Fuse** buttons.

## 🚀 Run locally
Open `index.html` in any browser.

---
*Made for Gabe.* 💚
