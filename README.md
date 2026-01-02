# Skyview Hide & Seek

Skyview Hide & Seek is a casual Fortnite UEFN experience built around a central floating hub and multiple independent hide-and-seek maps. Players are scaled down to a miniature size while environments are oversized, creating playful, readable, and exploration-focused gameplay.

The experience is designed to be non-competitive, easy to understand, and highly replayable.

---

## Concept

- Players spawn in a **floating sky hub** positioned high above the map.
- From the hub, players can see **multiple hide-and-seek games running below**.
- The hub contains portals that send players into **separate map instances**.
- Each map runs independently with its own round, seeker, and hiders.
- Fortnite automatically scales the experience across unlimited instances.

---

## Core Features

- Floating central hub (“Skyview Plaza”)
- 7 unique hide-and-seek maps with different visual themes
- Tiny player scale + giant environments
- Casual hide-and-seek rules (no sweat mechanics)
- Automatic round handling using Round Manager
- Seeker tagging system
- Automatic return to hub after each round

---

## Gameplay Flow

1. Player joins the island
2. Player spawns in the sky hub at normal size
3. Player explores the hub and chooses a portal
4. Player is shrunk and teleported to a hide-and-seek map
5. One seeker is chosen, others become hiders
6. Round runs until:
   - All hiders are found, or
   - The round timer expires
7. All players return to the hub
8. Loop repeats

---

## Map Structure

Each hide-and-seek map:
- Supports up to 15 players
- Uses the same Verse logic
- Has a unique theme and layout
- Is scaled for miniature players

Example map themes:
- Giant Toy Room
- Overgrown Jungle
- Kitchen Chaos
- Library of Giants
- Beach Paradise
- Urban Playground
- Candy World

---

## Technical Overview

- Built using **UEFN** and **Verse**
- Game flow controlled via **Round Manager device**
- Player tagging handled through **Input Trigger devices**
- Player scaling and teleporting handled in Verse
- Designed for stability and clarity rather than experimental syntax

---

## Repository Structure


- Only source files and documentation are tracked
- Generated files, caches, and engine data are ignored

---

## Current Status

- Core hub and map logic implemented
- Round lifecycle working (start → play → end)
- Tagging and win conditions implemented
- Actively iterating on polish and edge cases

---

## License

This project is licensed under the MIT License.

---

## Notes

This project is a learning-driven, system-focused build intended to explore:
- Multi-instance game design
- Casual player flow
- Reliable Verse patterns in UEFN

Feedback and experimentation are welcome.
