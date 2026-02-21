# Storyboard — Political Satire Animation Project

Production storyboard system. Extends the character board into episode-level planning, shot-by-shot breakdowns, and sequence guides.

---

## Directory Structure

```
storyboard/
├── README.md                          ← this file
├── _templates/
│   ├── episode.md                     ← full episode storyboard template
│   ├── beat-sheet.md                  ← beat breakdown template
│   ├── shot-list.md                   ← shot list template
│   └── panel-notes.md                 ← panel annotation template
├── episodes/
│   └── ep-001/                        ← first episode
│       ├── beat-sheet.md
│       ├── shot-list.md
│       └── panels/
│           └── README.md
├── sequences/
│   ├── README.md                      ← sequence system overview
│   ├── cold-open/
│   │   └── README.md                  ← news desk sequence conventions
│   ├── pov-maga-cultist/
│   │   └── README.md
│   ├── pov-typical-leftist/
│   │   └── README.md
│   ├── pov-informed-person/
│   │   └── README.md
│   ├── pov-opportunist/
│   │   └── README.md
│   ├── pov-talking-head/
│   │   └── README.md
│   └── button/
│       └── README.md
├── shot-language/
│   ├── README.md                      ← shot notation system
│   ├── south-park-flat.md             ← shot conventions for flat style
│   └── boondocks-fluid.md             ← shot conventions for fluid style
└── animatic/
    └── README.md                      ← animatic workflow and export specs
```

---

## Episode Workflow

1. **Copy** `_templates/beat-sheet.md` into `episodes/ep-[N]/`
2. **Copy** `_templates/shot-list.md` into `episodes/ep-[N]/`
3. **Fill** the beat sheet first — establish the event and distortion arc per character
4. **Expand** each beat into shots in the shot list
5. **Annotate** panels in `episodes/ep-[N]/panels/` using `_templates/panel-notes.md`
6. **Reference** sequence guides in `sequences/` for per-character conventions
7. **Reference** shot language in `shot-language/` for style-specific framing rules

---

## Relationship to Character Board

This storyboard system is built on top of `character-board/`:

| Character Board | Storyboard
|---|---|
| Character specs | Drive casting per sequence |
| Color palettes | Drive panel fill annotation |
| SVG asset maps | Drive which rig parts are active per shot |
| Episode template | Drives beat sheet structure |
| POV distortion rules | Drive shot framing logic per sequence |

---

## Episode Naming Convention

```
ep-[NNN]-[slug].md
```

Examples:
- `ep-001/` — pilot episode
- `ep-002-the-vote/` — episode 2, slug: the-vote
- `ep-003-the-summit/` — episode 3, slug: the-summit

---

## Branch Convention

Each episode in production gets its own branch:

```
feature/ep-[NNN]-[slug]
```

Merged into `main` when the episode storyboard is locked.
