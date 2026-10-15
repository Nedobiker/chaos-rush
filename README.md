# CHAOS RUSH

> **Survive the chaos. Outlast the disaster.**

CHAOS RUSH is a multiplayer survival game concept for Roblox where players try to survive a sequence of increasingly dangerous disasters in a shared city arena. Every round brings unpredictable chaos, and only players who make it through all three rounds qualify as winners.

**Project status:** Pre-production / concept development  
**Platform:** Roblox  
**Genre:** Multiplayer survival · Disaster survival  
**Repository:** [Nedobiker/chaos-rush](https://github.com/Nedobiker/chaos-rush)

---

## Overview

In CHAOS RUSH, players enter a large city arena and face random disasters. The danger increases from round to round, so players must adapt quickly, use the environment, and stay alive until the stage is complete.

The first release is planned around three signature disasters:

- 🌪️ **Tornado** — a destructive force moving through the arena.
- ☄️ **Meteor Shower** — falling meteors threaten areas across the city.
- ⛈️ **Thunderstorm** — dangerous lightning makes survival harder.

Disaster behaviour, balancing, and detailed effects will be defined during implementation.

## Core match loop

1. Players gather in the lobby.
2. When enough players are present, a short countdown begins.
3. The match starts in the city arena.
4. Players survive **three rounds**, with danger increasing each round.
5. Each round features **one or two random disasters**. Two disasters may occur simultaneously.
6. A short break separates rounds.
7. Players who survive all three rounds are declared winners.

## Planned rules

| Feature | Current decision |
| --- | --- |
| Players per server | Up to 12 |
| Arena | One large city |
| Stage length | 3 rounds |
| Round duration | 4–6 minutes |
| Disasters per round | 1–2 |
| Disaster selection | Random; danger increases each round |
| Respawns | One respawn per round |
| Between-round break | 20–30 seconds |
| Camera | Switch between first-person and third-person |
| Winners | All players who survive all 3 rounds |
| Match start | Automatic short countdown when enough players are present |

Some details—such as the minimum player count, exact respawn/elimination flow, and precise disaster timing—are still being discussed. See [DECISIONS.md](DECISIONS.md) for the decision log and open questions.

## User interface and atmosphere

CHAOS RUSH aims for a bright, energetic **CHAOS-style** interface.

The planned HUD includes:
- Current round timer.
- Timer until the next disaster.
- Short messages for important events only.

Sound effects, lobby music, visual effects, and additional presentation features will be evaluated as the first playable version takes shape.

## First-release scope

The initial playable version is being planned around the essentials:

- Three-round match flow.
- City arena.
- Tornado, Meteor Shower, and Thunderstorm.
- Respawn and elimination rules.
- Timers and core HUD.
- Results and winner determination.
- Spectating, subject to finalizing the elimination flow.

The MVP feature list is **not yet finalized**. Features such as currency, a shop, cosmetic rewards, and persistent statistics remain undecided and are not promised for the first release.

## Development status

This repository is currently used to document the concept and record agreed design decisions before implementation begins.

- [x] Establish the core game concept.
- [x] Agree on the three initial disasters.
- [ ] Finalize the MVP feature list.
- [ ] Resolve remaining match-flow questions.
- [ ] Prepare the Game Design Document.
- [ ] Begin Roblox Studio implementation.

## Project documentation

- **[Decision log](DECISIONS.md)** — agreed choices and questions still to resolve.
- **Game Design Document** — planned after the concept is sufficiently finalized.

## Design principle

**Easy to understand, unpredictable to play, and more dangerous with every round.**

---

*CHAOS RUSH is a work in progress. Features and rules may change as the concept is tested and refined.*
