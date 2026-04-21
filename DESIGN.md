# CHRONOS-DEV Design System

## Brand Overview
**Name:** CHRONOS-DEV  
**Tagline:** Software Development & AI Integration  
**Location:** Guatemala City, Guatemala  
**Market:** Local GT businesses + remote LATAM/US clients  
**Personality:** Technological, futuristic, elegant, premium, trustworthy  
**Voice:** Direct, confident, results-oriented, bilingual (ES/EN)

---

## Color Tokens

### Primary
| Token | Value | Usage |
|---|---|---|
| `--color-primary` | `#7aff00` | Main brand color, "DEV" wordmark, CTAs, highlights |
| `--color-neon` | `#39ff14` | Glow effects, eye icon center, active states |
| `--color-primary-dark` | `#4aaa2a` | Hover states, pressed buttons |
| `--color-primary-ghost` | `#7aff0015` | Subtle backgrounds, badge fills |

### Background
| Token | Value | Usage |
|---|---|---|
| `--color-bg` | `#131a13` | Main page background |
| `--color-bg-deep` | `#0a100e` | Nav, cards, darkest surfaces |
| `--color-surface` | `#1a251a` | Card backgrounds, elevated surfaces |
| `--color-surface-2` | `#252f25` | Circuit pattern, borders, dividers |

### Text
| Token | Value | Usage |
|---|---|---|
| `--color-text` | `#f0f0e8` | Primary text, "CHRONOS" wordmark |
| `--color-text-muted` | `#888a80` | Secondary text, tagline, captions |
| `--color-text-dim` | `#4a5a4a` | Placeholder, disabled states |

### Semantic
| Token | Value | Usage |
|---|---|---|
| `--color-border` | `#2a3a2a` | Dividers, card borders |
| `--color-border-glow` | `#7aff0033` | Glowing borders, focus rings |
| `--color-success` | `#4aaa5a` | Positive states |

---

## Typography

### Display / UI Font
- **Family:** Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif
- **Usage:** All headings, buttons, nav, UI labels
- **Weights:** 400 (body), 500 (medium), 700 (bold/display)

### Accent / Decorative Font
- **Family:** Georgia, 'Times New Roman', serif  
- **Style:** Italic only
- **Usage:** Section labels only (e.g. "Complete Project", "Working Process")
- **Color:** Always `--color-primary` (#7aff00)

### Monospace Font
- **Family:** 'JetBrains Mono', 'Fira Code', monospace
- **Usage:** Numbered lists (01, 02...), code, hex values, technical labels

### Type Scale
| Name | Size | Weight | Usage |
|---|---|---|---|
| Display | 60–72px | 700 | Hero headlines |
| H1 | 48–56px | 700 | Page titles |
| H2 | 32–36px | 700 | Section titles |
| H3 | 22–24px | 500 | Card titles, service names |
| Body | 14–16px | 400 | Paragraphs, descriptions |
| Caption | 10–11px | 400 | Labels, dates, meta |
| Overline | 9–10px | 400–700 | Section labels (ALL CAPS, letter-spacing: 2–3px) |

---

## Logo

### Primary Logo
- **Icon:** Circular cyber/tech eye with concentric rings, binary data, neon green glow
- **Wordmark:** "CHRONOS" in white (#f0f0e8) bold + "DEV" in lime green (#7aff00) bold
- **Tagline:** "SOFTWARE DEVELOPMENT & AI INTEGRATION" in muted gray (#888a80), all caps, spaced
- **Background:** Dark charcoal-green (#131a13) with PCB circuit pattern

### Logo Variants
1. **Dark (primary):** On `#0a100e` background
2. **Surface:** On `#1a251a` background  
3. **Light:** On `#f0f0e8` background (icon inverted to dark)
4. **Icon only:** For favicon (16×16, 32×32), avatar (circular), app icon (rounded square)

### Clear Space
- Minimum clear space = 1× icon height on all sides
- Never place logo on busy backgrounds without sufficient contrast

---

## Brand Patterns & Textures

### PCB Circuit Pattern
- Thin lines (`#7aff0015` to `#7aff0022`) forming circuit board traces
- Used as background texture on hero and full-width sections
- Grid-based with node dots at intersections

### Concentric Circles
- Multiple rings emanating from center, decreasing opacity outward
- Stroke color: `#7aff00` at 15–70% opacity
- Used behind hero content, section headers

### Tech Grid
- Subtle grid lines (`#7aff0011`)  
- Node dots at key intersections (`#7aff0044`)
- Used on section backgrounds

---

## Components

### Buttons
```
Primary:   bg #7aff00, text #0a100e, font-weight 700, no border-radius, padding 11px 22px
Secondary: bg transparent, text #7aff00, border 1px solid #7aff00, same padding
Ghost:     bg transparent, text #888a80, border 1px solid #2a3a2a, same padding
```

### Badges / Tags
```
Filled:   bg #7aff00, text #0a100e, font-size 9px, font-weight 700, letter-spacing 1px, uppercase
Tinted:   bg #7aff0015, text #7aff00, border 1px solid #7aff0033
Outline:  bg transparent, text #7aff00, border 1px solid #7aff00
Dark:     bg #1a251a, text #888a80, border 1px solid #2a3a2a
```

### Cards
```
Background: #0a100e
Border: 1px solid #1a251a
Border-radius: 0px (sharp corners — tech aesthetic)
Hover border: 1px solid #7aff0033
```

### Navigation
```
Background: #0a100e
Height: 60px
Border-bottom: 1px solid #7aff0015
Logo left | Links center | CTA right
CTA button: Primary style (#7aff00)
```

### Dividers / Section Separators
- Horizontal line: `1px solid #1a251a`
- Decorative: Gold line + diamond + Georgia italic label
- Hierarchy lines: Decreasing opacity and width
- Star ornament: ✦ in `#7aff00`

---

## Spacing System (base 8px)

| Token | Value |
|---|---|
| xs | 4px |
| sm | 8px |
| md | 16px |
| lg | 32px |
| xl | 56px |
| 2xl | 80px |

---

## Iconography
- Style: Line/outline icons, 1.5px stroke
- Color: `#7aff00` for active, `#888a80` for inactive
- Size: 16px inline, 24px decorative max
- Preferred set: Lucide Icons or Heroicons

---

## Services Offered (for content generation)
1. **E-commerce completo** — Next.js 15, Neon DB, WhatsApp checkout, Stripe/Recurrente
2. **Landing pages** — alto impacto, carga rápida, optimizadas para conversión
3. **Chatbots con IA** — Claude API, atención 24/7, WhatsApp o web
4. **Automatización Python** — OCR, Google Sheets, flujos de trabajo
5. **Mantenimiento mensual** — actualizaciones, soporte, hosting

---

## Tech Stack (for code references)
- **Framework:** Next.js 15 (App Router)
- **Database:** Neon PostgreSQL (serverless)
- **Media:** Cloudinary
- **Auth:** NextAuth.js v5
- **Deploy:** Vercel
- **AI:** Claude API (Anthropic)
- **Language:** Python (automations), TypeScript (web)

---

## Social Media Presence
- **Platforms:** Instagram, LinkedIn, Facebook, WhatsApp Business
- **Content pillars:** Before/after projects, tech tips, behind the scenes, testimonials
- **Post format:** Dark bg + lime green accents, consistent brand frame
- **Tone:** Professional but approachable, bilingual

---

## Taglines
- **Primary:** "Soluciones digitales que no se quedan en el tiempo."
- **English:** "Where code meets intelligence."
- **Short:** "Software & AI · Guatemala"

---

## Ornamental Symbol
`✦` — used as bullet in marquees, list separators, decorative accents
