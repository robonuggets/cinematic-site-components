# Cinematic Sites Framework

31 cinematic website modules + a Claude Code skill that picks and combines them.

> Every module is a **single HTML file**. No frameworks. No build step. No npm. Just open it.

## Preview

Open `index.html` to browse all 31 modules with animated mini-demos, or open any individual module file directly in a browser.

## Install as a Claude Code Skill

```bash
claude --add-dir /path/to/cinematic-sites
```

Then invoke:

```
/webcraft dark agency portfolio with scroll animation
```

## The 31 Cinematic Modules

### Scroll-Driven
| # | Module | What It Does |
|---|---|---|
| 01 | Text Mask Reveal | Headline fills with colour as you scroll |
| 02 | Sticky Stack Narrative | Product pins, features scroll past it |
| 03 | Layered Zoom Parallax | Depth layers, foreground zooms past |
| 06 | Horizontal Scroll Hijack | Vertical scroll → horizontal gallery |
| 07 | Sticky Card Stack | Cards pin and stack on each other |
| 12 | Scroll SVG Draw | Lines draw themselves on scroll |
| 13 | Curtain Reveal | Hero splits open like curtains |
| 16 | Split Screen Scroll | Two halves scroll opposite directions |
| 20 | Scroll Color Shift | Background changes per section |

### Cursor & Hover
| # | Module | What It Does |
|---|---|---|
| 04 | Cursor-Reactive | Glow, 3D tilt, magnetic buttons, ripples |
| 09 | Accordion Slider | Strips expand on hover |
| 11 | Cursor Image Reveal | Before/after with wipe, spotlight, split |
| 14 | Hover Image Trail | Cursor leaves fading images behind |
| 18 | 3D Flip Cards | Cards rotate to reveal back |
| 22 | Magnetic Repel Grid | Tiles push away from cursor |
| 25 | Spotlight Border Cards | Borders illuminate under cursor |
| 29 | Drag-to-Pan Grid | Infinite draggable canvas |

### Click & Tap
| # | Module | What It Does |
|---|---|---|
| 05 | View Transition Morphing | Elements shape-shift between states |
| 21 | Odometer Counter | Digit wheels roll to target |
| 23 | Particle Explosion Button | CTAs burst on click |
| 27 | 3D Coverflow Carousel | Center focused, edges angled |
| 28 | Dynamic Island Nav | Pill morphs for notifications |
| 30 | macOS Dock Nav | Icons magnify on hover |

### Ambient & Auto
| # | Module | What It Does |
|---|---|---|
| 08 | Text Scramble Decode | Matrix-style character cycling |
| 10 | Kinetic Marquee | Infinite text bands, scroll-reactive |
| 15 | Mesh Gradient Background | Animated colour blobs |
| 17 | Circular Text Path | Text on spinning circle |
| 19 | Glitch Effect | RGB channel split |
| 24 | Typewriter Effect | Text types itself |
| 26 | Gradient Stroke Text | Animated gradient on outlined text |

## How Webcraft Works

1. You describe what you want (business type, mood, dark/light)
2. Webcraft recommends 2-3 cinematic modules that work well together
3. Generates a single `index.html` combining them into a complete site

It never picks more than 3 modules (cognitive overload) and follows strict combination rules to avoid conflicting effects.

## Tech Stack

- HTML + CSS + vanilla JS
- GSAP + ScrollTrigger (CDN)
- Google Fonts (CDN)
- That's it.

## License

MIT — see [LICENSE](LICENSE) for details.

## Attribution

© Created by Jay from RoboLabs. Learn more at [RoboNuggets](https://robonuggets.com)
