# Sequences — Overview

Each directory contains the standing conventions for that sequence type. These apply across all episodes — they define the default framing, environment, shot rhythm, and animation behavior for each character's segment.

Episode-specific variations are documented in the episode's shot list, not here.

---

## Sequence Index

| Sequence | Directory | Character | Style |
|---|---|---|---|
| Cold open / button | `cold-open/` | The Anchor | South Park flat |
| POV: MAGA Cultist | `pov-maga-cultist/` | The MAGA Cultist | South Park flat |
| POV: Typical Leftist | `pov-typical-leftist/` | The Typical Leftist | South Park flat |
| POV: Informed Person | `pov-informed-person/` | The Informed Person | Boondocks fluid |
| POV: Opportunist | `pov-opportunist/` | The Opportunist | Boondocks fluid |
| POV: Talking Head | `pov-talking-head/` | The Talking Head | South Park flat |
| Button | `button/` | The Anchor | South Park flat |

---

## What Sequence Files Define

Each sequence README covers:

- **Environment** — default setting, colors, props in frame
- **Default framing** — standard shot types for this character
- **Shot rhythm** — cut rate and pacing conventions
- **Animation behavior** — what moves, what stays still
- **Prop rules** — when and how signature props appear
- **Transition in / out** — how the sequence begins and ends

---

## The Invariants

Two shots must be identical across every episode:

| Shot ID | Description | Rule |
|---|---|---|
| `ANCHOR-COLD-OPEN` | Anchor MCU, opening | Framing, color, expression — locked |
| `ANCHOR-BUTTON` | Anchor MCU, button | Must match cold open exactly |

The match is the joke. Do not vary these shots between episodes.
