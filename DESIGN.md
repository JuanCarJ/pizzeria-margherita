# DESIGN.md — Margherita Pan & Pizza

## Brand
- **Name**: Margherita Pan & Pizza
- **Tagline**: Mas que una pizza, un momento inolvidable.
- **Voice**: warm, artisanal, Italian tradition, inviting, authentic

## Color Palette

| Token | Hex | Usage |
|-------|-----|-------|
| `--color-bg` | #1A1612 | Dark sections background |
| `--color-bg-light` | #FAF3EA | Light sections background |
| `--color-surface` | #2A2420 | Elevated dark surfaces |
| `--color-surface-light` | #F0E8DC | Light elevated surfaces |
| `--color-text` | #F5EFEA | Text on dark backgrounds |
| `--color-text-dark` | #2C2418 | Text on light backgrounds |
| `--color-accent` | #D4A054 | Gold/wheat — primary accent |
| `--color-accent-red` | #C8373D | Italian red — CTAs |
| `--color-accent-green` | #3D7A4A | Italian green — subtle accents |
| `--color-muted` | #8B7E72 | Secondary text, captions |
| `--color-border` | rgba(255,255,255,0.08) | Borders on dark |
| `--color-border-light` | rgba(44,36,24,0.1) | Borders on light |

## Typography

| Role | Font | Weight | Size (fluid) |
|------|------|--------|-------------|
| Display | Fraunces | 700–900 | clamp(2.5rem, 1.5rem + 4vw, 5rem) |
| Headline | Fraunces | 600 | clamp(1.5rem, 1rem + 2vw, 2.5rem) |
| Body | Outfit | 300–400 | clamp(0.95rem, 0.9rem + 0.25vw, 1.125rem) |
| Caption | Outfit | 400 | 0.8125rem (13px) |

### Font sources
- Google Fonts: Fraunces (variable, opsz), Outfit

## Logo
| Variant | Path | Notes |
|---------|------|-------|
| Primary | `fotos/logo.png` | Pizza peel with M, wheat laurels, crown |
| Banner | `fotos/Banner pizza 2.jpg` | Full brand banner with breads and pizza |
| Instagram | `fotos/Instagram profile picture.jpg` | Small profile picture |

## Images
| Purpose | Path / Description |
|---------|--------------------|
| Hero BG | `fotos/Banner pizza 2.jpg` — Dark wood with logo, breads, and pizza |
| Bufalina | `fotos/WhatsApp Image 2026-02-07 at 17.16.38.jpeg` — Beautiful margherita bufalina |
| Prosciutto | `fotos/WhatsApp Image 2026-02-28 at 17.23.45.jpeg` — Prosciutto e funghi |
| Loaded | `fotos/WhatsApp Image 2026-02-22 at 13.11.26.jpeg` — Close-up loaded pizza |
| Tocineta | `fotos/WhatsApp Image 2026-02-03 at 17.48.02.jpeg` — Bacon pizza |
| Hawaiana | `fotos/WhatsApp Image 2026-01-29 at 18.03.18.jpeg` — Hawaiana |
| Side cut | `fotos/WhatsApp Image 2026-01-25 at 17.04.09.jpeg` — Side view thick crust |
| Half/half | `fotos/WhatsApp Image 2025-12-10 at 17.51.26.jpeg` — Half pepperoni half hawaiana |
| Romana | `fotos/IMG-20210927-WA0029.jpg` — Romana al Taglio |
| Chicago | `fotos/IMG-20210927-WA0032.jpg` — Chicago deep dish |
| Berenjena | `fotos/IMG-20210927-WA0036.jpg` — Berenjena Parmesana |
| Lasagna | `fotos/Lasagna.jpg` — Homemade lasagna |
| Flan | `fotos/IMG-20210927-WA0038.jpg` — Flan de Caramelo |
| Bread | `fotos/P_20210930_114126.jpg` — Artisanal bread |

### Image guidelines
- Photography style: warm, rustic, overhead and close-up food shots
- Treatment: warm color grading, slightly dark/moody backgrounds

## Aesthetic Direction
- **Archetype**: organic-natural
- **Mood**: Warm Italian trattoria — artisanal, rustic, inviting. Dark wood textures meet golden wheat tones.
- **References**: Traditional Italian pizzerias, warm food photography, artisanal bakery branding

## Configuration Dials
| Dial | Value | Rationale |
|------|-------|-----------|
| DESIGN_VARIANCE | 6 | Warm and inviting with some asymmetric flair |
| MOTION_INTENSITY | 5 | Gentle entrance animations and scroll reveals |
| VISUAL_DENSITY | 3 | Restaurant landing — breathing room, hero-dominant |

## Technical Constraints
- **CSS stack**: Vanilla CSS with custom properties
- **Framework**: Vanilla HTML — single page
- **Animation library**: CSS only + IntersectionObserver
- **Browser support**: Last 2 versions

## Content Notes
- **Language**: Spanish (Colombia), informal
- **Tone**: Warm, inviting, proud of artisanal quality. Not corporate.
- **Social**: Instagram @margherita.rionegro
- **WhatsApp**: 304 4124917
- **Location**: Rionegro, Antioquia, Colombia
