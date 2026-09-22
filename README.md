# MaceRoyale

A Paper plugin built around a single legendary mace that continuously rotates between players.

## Overview

MaceRoyale creates a unique server-wide event where players compete for ownership of one powerful enchanted mace.

The mace never drops, never remains on the ground, and is constantly passed between players through automated game events.

## Features

### Legendary Mace

The event revolves around a unique enchanted mace featuring:

- Density V
- Unbreaking III
- Mending
- Wind Burst I

### Automatic Rotation

The mace rerolls when:

- The holder dies
- The holder enters the spawn zone
- The 10-minute ownership timer expires

### Fair Player Selection

- Equal chance for all eligible players
- Spawn-zone exclusion support
- Low-player-count handling
- Solo-player edge-case handling

### Spawn Detection

Supports:

- WorldGuard regions
- Built-in spawn protection fallback
- No hard WorldGuard dependency

### Event Presentation

- MACE ROLLING title animation
- Live player selection display
- Broadcast winner announcements
- Sound effects

### Administration

Commands:

- `/mr start`
- `/mr stop`
- `/mr reroll`
- `/mr status`
- `/rig <player>`

## Technologies

- Java
- Paper API
- WorldGuard API

## Status

Commercial project. Source code is not publicly available.

## Author

Liam
Minecraft: liam__mc
Discord: liam_bluelock
