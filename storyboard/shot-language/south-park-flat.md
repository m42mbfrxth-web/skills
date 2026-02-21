# Shot Language — South Park Flat

**Applies to:** The Anchor, The MAGA Cultist, The Typical Leftist, The Talking Head

---

## Core Principles

1. **The camera is locked.** No movement. No pans. No dolly. No zoom. Every shot is a fixed frame — the character moves within it, or the edit moves between them.
2. **Expressions are discrete swaps.** There is no interpolation between expressions. The face changes state, not value. Cut to a new expression, or swap in place.
3. **Flat fills only.** No gradients within character elements. Backgrounds may use 2–3 banded zones to suggest depth — no smooth transitions.
4. **The body rotates as a unit.** Characters do not turn their heads independently. The full torso rotates.

---

## Camera

| Rule | Detail |
|---|---|
| Movement | None — all shots locked off |
| Angle | Eye level in most shots — authority angle (slight high) for Anchor desk only |
| Lens | Flat — no perspective distortion within shots |
| Transitions | Hard cuts only — no dissolves between scenes |

---

## Framing Conventions by Character

### The Anchor
- MCU is the default framing — head and shoulders, desk edge visible at bottom
- WS only for establishing and pulls
- ECU reserved for earpiece beat only

### The MAGA Cultist
- MS is the default — phone in frame at all times where possible
- CU for expression beats — the jaw
- INSERT for phone screen — 2–3 per sequence, 2–3 sec

### The Typical Leftist
- MS is the default — cup in frame at all times
- MCU for outrage escalation
- ECU for cup insert — the irony beat
- MS or INSERT for phone posting moment

### The Talking Head
- MCU is the default — eyebrows readable
- CU for urgency escalation
- ECU for eyebrow hold
- INSERT for tablet glance — 2 sec, twice per sequence

---

## Expression System

Expressions are discrete states. Each character has a defined range:

| Character | Expression states |
|---|---|
| The Anchor | Neutral → mildly concerned → neutral |
| The MAGA Cultist | Certainty at rest → certainty sharpening → satisfaction → unchanged |
| The Typical Leftist | Mild indignation → escalating → full outrage → reset to mild indignation |
| The Talking Head | Controlled urgency → escalating → peak urgency → reset |

**There is no "between" state.** The character is in one of these states. Transitions between states are hard swaps, not continuous animation.

---

## Prop Animation

| Prop | Animation rule |
|---|---|
| Phone (MAGA Cultist) | Continuous downward scroll — single aggressive tap at share moment |
| Coffee cup (Typical Leftist) | Held — slight movement when character gestures, otherwise static |
| Tablet (Talking Head) | In hand — glance animation: head dips, returns, 2 sec |
| Papers (The Anchor) | Never move |
| Earpiece (The Anchor) | Cord micro-animation: occasional subtle movement — implying incoming signal |

---

## Cut Rate by Sequence

| Sequence | Cut rate | Notes |
|---|---|---|
| Cold open | Slow — 4 shots, 22–24 sec | Authority pacing |
| MAGA Cultist | Medium — 10–14 shots per 90 sec | Deliberate certainty |
| Typical Leftist | Medium-fast — 12–16 shots per 90 sec | Indignation has energy |
| Talking Head | Fast — 16–20 shots per 90 sec | Urgency has velocity |
| Button | 1 shot, 5–8 sec | The reset |

---

## Outline Spec

- All character outlines: `stroke-width="3"`, color `#1A1A1A`
- Background elements: `stroke-width="1.5"` or no stroke
- Prop outlines: `stroke-width="2"`

---

## Background Depth Convention

South Park flat backgrounds use 2–3 discrete color bands to imply depth:

```
[FAR BACKGROUND — darkest value]
[MID BACKGROUND — mid value]
[FOREGROUND PLANE — lightest or most saturated]
```

No gradients. No textures. Color zones only.
