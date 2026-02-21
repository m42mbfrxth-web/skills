# Animatic — Workflow and Export Specs

Pre-animation stage. Static panels in sequence with timing and scratch audio.

---

## Purpose

The animatic locks:
- Shot order and duration before full animation begins
- Timing for dialogue and sound cues
- Register shifts (flat ↔ fluid) and their positions in the cut
- The button match — verified before any animation is finalized

An approved animatic is the gate before full production on each episode.

---

## Workflow

```
Beat sheet (locked)
    ↓
Shot list (locked)
    ↓
Panels annotated (_templates/panel-notes.md)
    ↓
Animatic assembled (panels + timing)
    ↓
Scratch audio added (temp VO + ambient)
    ↓
Animatic review
    ↓
Approved → full animation
```

---

## Animatic Assembly

Panels are placed in shot order with durations matching the shot list. No animation — static images held for the specified duration.

| Element | Source |
|---|---|
| Panels | `episodes/ep-[NNN]/panels/` |
| Timing | `episodes/ep-[NNN]/shot-list.md` |
| Scratch VO | Temp read — no final voice direction at this stage |
| Music placeholder | Temp track or silence — note intended tone |
| SFX placeholder | Text overlay or tone — note intended effect |

---

## Export Specs

| Spec | Value |
|---|---|
| Format | MP4 (H.264) or MOV |
| Resolution | 1920 × 1080 |
| Frame rate | 24fps |
| Audio | Scratch only — 48kHz stereo |
| Naming | `ep-[NNN]-animatic-v[N].mp4` |

**File location:** `animatic/ep-[NNN]-animatic-v[N].mp4`

Version number increments with each review pass.

---

## Review Checklist

Before approving an animatic for full animation:

- [ ] Cold open framing matches `ANCHOR-COLD-OPEN` spec
- [ ] Button framing is identical to cold open — no variation
- [ ] Register shifts (flat ↔ fluid) occur at correct cuts
- [ ] Each POV sequence contains all 5 beats
- [ ] Signature prop appears in beat 3 for each character
- [ ] Sigh animation beat (Informed Person) has sufficient hold duration
- [ ] Calculation CU (Opportunist) has sufficient hold duration
- [ ] Tablet glance (Talking Head) is 2 sec — not longer
- [ ] Book set-down (Informed Person) has its own uncut shot
- [ ] Total runtime within range for episode type
- [ ] Button is the last image before end card

---

## Timing Reference

| Segment | Target |
|---|---|
| Cold open | 30–45 sec |
| Title card | 3–5 sec |
| POV sequence (single) | 90–180 sec |
| Button | 5–10 sec |
| Single-character episode | ~3–4 min |
| Three-character episode | ~8–10 min |

---

## Per-Episode Animatic Index

| Episode | Version | Status | File |
|---|---|---|---|
| ep-001 | v1 | Pending | `ep-001-animatic-v1.mp4` |
