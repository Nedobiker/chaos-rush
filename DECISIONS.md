# CHAOS RUSH — Decision Log

This document records design choices agreed during concept development. The goal is to keep decisions visible, avoid losing context, and distinguish confirmed rules from ideas that are still under discussion.

**Status:** Concept development  
**Last updated:** 2026-10-15

## Confirmed decisions

### Game identity
- **Name:** CHAOS RUSH
- **Genre:** Multiplayer survival focused on random disasters.
- **Platform:** Roblox.

### Match structure
- A stage consists of **3 rounds**.
- Each round lasts approximately **4–6 minutes**.
- The danger increases with each round; Round 3 is the most dangerous.
- Each round contains **1–2 randomly selected disasters**.
- Two disasters may occur at the same time.
- A **20–30 second break** separates rounds.
- A match starts automatically after a short countdown once enough players are present.
- A server supports up to **12 players**.
- All players who survive all three rounds are winners.

### Arena and camera
- The first version uses **one large city arena** for all three rounds.
- Players can switch between **first-person and third-person** camera views.

### Respawn and spectating
- Players have **one respawn per round**.
- The agreed direction is that after the second death in a round, the player continues without further respawns for that round.
- Spectating remaining players after a player's final elimination is planned.

> The exact relationship between the second death, elimination, continued play, and spectating still needs clarification before implementation.

### Disasters
The initial disaster roster is:
1. **Tornado**
2. **Meteor Shower**
3. **Thunderstorm**

- Disasters are selected randomly.
- Their danger increases as the rounds progress.
- Disasters begin without a separate warning beforehand.

### HUD and presentation
- UI direction: bright, energetic **CHAOS style**.
- The HUD should show the current round timer and the timer until the next disaster.
- Only important event messages should be shown.

## Not decided yet

These topics must not be treated as finalized:
- The complete MVP feature list.
- Minimum number of players required to start a match.
- Exact disaster schedules, durations, damage, and balancing.
- The precise respawn, second-death, elimination, and spectating flow.
- How the “timer until the next disaster” works alongside the decision that disasters start without warning.
- Currency, rewards, cosmetics, shop, and persistent statistics.
- Final results-screen details.
- Detailed lobby design, music, and sound effects.

## Working rule for future decisions

When a design choice is explicitly approved, update this file in the same work session and commit the change to GitHub. Keep unresolved ideas in **Not decided yet** until they are approved. If an approved decision changes, update the log rather than silently treating the old and new rules as simultaneously valid.

## Change history

- **2026-10-15** — Recorded the confirmed concept decisions and open questions; created the initial project README and decision log.
