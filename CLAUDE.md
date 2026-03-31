# Cinematic Sites Framework

A library of 31 cinematic website modules + a Claude Code skill that picks and combines them into single-file websites.

## Quick Start

```
/webcraft dark SaaS landing page with scroll animation and feature section
```

## What's Here

- `*.html` — 31 standalone cinematic module demos (no build step, just open in browser)
- `index.html` — Visual hub page with animated mini-demos for each module
- `.claude/skills/webcraft/SKILL.md` — The skill file that powers `/webcraft`

## How It Works

1. Describe what you want (business type, mood, theme)
2. Webcraft picks 2-3 cinematic modules from the library
3. Generates a single `index.html` combining them into a complete site

## Module Categories

- **Scroll-Driven** (9) — Text mask, sticky stack, zoom parallax, horizontal scroll, sticky cards, SVG draw, curtain reveal, split screen, color shift
- **Cursor & Hover** (9) — Cursor-reactive, accordion, cursor reveal, image trail, flip cards, magnetic grid, spotlight borders, drag-to-pan
- **Click & Tap** (7) — View transitions, particle button, odometer, coverflow, dynamic island, dock nav
- **Ambient & Auto** (6) — Text scramble, marquee, mesh gradient, circular text, glitch, typewriter, gradient stroke

## Requirements

- Claude Code with slash command support
- A browser (for previewing)
- That's it. No npm, no build, no frameworks.
