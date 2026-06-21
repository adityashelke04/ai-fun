---
version: alpha
name: realfunai-design
description: Real Fun AI design language — a dark-first interactive AI experiences site. Built on Vercel's stark design system but flipped to a near-black canvas with electric green accent, Geist typography, and the same multi-color mesh gradient at hero scale. Every surface signals AI-native without losing the clean, engineered feel.

colors:
  primary: "#ffffff"
  on-primary: "#0a0a0a"
  ink: "#ffffff"
  body: "#a1a1a1"
  mute: "#555555"
  hairline: "#222222"
  hairline-strong: "#333333"
  canvas: "#0a0a0a"
  canvas-soft: "#111111"
  canvas-soft-2: "#1a1a1a"
  canvas-card: "#141414"
  canvas-raised: "#1f1f1f"
  accent: "#00ff88"
  accent-soft: "#00ff8815"
  accent-deep: "#00cc66"
  link: "#00ff88"
  link-deep: "#00cc66"
  link-bg-soft: "#00ff8815"
  success: "#00ff88"
  error: "#ee0000"
  error-soft: "#ee000020"
  error-deep: "#c50000"
  warning: "#f5a623"
  warning-soft: "#f5a62320"
  warning-deep: "#ab570a"
  violet: "#7928ca"
  cyan: "#00dfd8"
  highlight-pink: "#ff0080"
  gradient-neural-start: "#007cf0"
  gradient-neural-end: "#00dfd8"
  gradient-model-start: "#7928ca"
  gradient-model-end: "#ff0080"
  gradient-data-start: "#ff4d4d"
  gradient-data-end: "#f9cb28"
  game-surface: "#0f0f0f"
  game-border: "#2a2a2a"
  game-success: "#00ff88"
  game-fail: "#ee0000"
  game-highlight: "#f9cb28"
  selection-bg: "#00ff88"
  selection-fg: "#0a0a0a"

typography:
  display-xl:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 48px
    fontWeight: 600
    lineHeight: 48px
    letterSpacing: -2.4px
  display-lg:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 32px
    fontWeight: 600
    lineHeight: 40px
    letterSpacing: -1.28px
  display-md:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 24px
    fontWeight: 600
    lineHeight: 32px
    letterSpacing: -0.96px
  display-sm:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 20px
    fontWeight: 600
    lineHeight: 28px
    letterSpacing: -0.6px
  body-lg:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 18px
    fontWeight: 400
    lineHeight: 28px
    letterSpacing: 0px
  body-md:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
  body-md-strong:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 16px
    fontWeight: 500
    lineHeight: 24px
  body-sm:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: -0.28px
  body-sm-strong:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 14px
    fontWeight: 500
    lineHeight: 20px
    letterSpacing: -0.28px
  caption:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 12px
    fontWeight: 400
    lineHeight: 16px
  caption-mono:
    fontFamily: Geist Mono, JetBrains Mono, ui-monospace, monospace
    fontSize: 12px
    fontWeight: 400
    lineHeight: 16px
  code:
    fontFamily: Geist Mono, JetBrains Mono, ui-monospace, monospace
    fontSize: 13px
    fontWeight: 400
    lineHeight: 20px
  counter:
    fontFamily: Geist Mono, JetBrains Mono, ui-monospace, monospace
    fontSize: 32px
    fontWeight: 400
    lineHeight: 40px
    letterSpacing: -1px
  button-md:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 14px
    fontWeight: 500
    lineHeight: 20px
  button-lg:
    fontFamily: Geist, Inter, system-ui, -apple-system, sans-serif
    fontSize: 16px
    fontWeight: 500
    lineHeight: 24px

rounded:
  none: 0px
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  pill-sm: 64px
  pill: 100px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 40px
  3xl: 48px
  4xl: 64px
  5xl: 96px
  6xl: 128px
  section: 192px

components:
  nav-bar:
    backgroundColor: "{colors.canvas}"
    borderColor: "{colors.hairline}"
    textColor: "{colors.ink}"
    height: 64px
    padding: "{spacing.sm} {spacing.lg}"
    backdropBlur: 12px
  nav-link:
    textColor: "{colors.body}"
    hoverTextColor: "{colors.ink}"
    rounded: "{rounded.full}"
    padding: "{spacing.xs} {spacing.sm}"
  nav-cta-primary:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
    padding: "0px {spacing.xs}"
    height: 28px
  nav-cta-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    borderColor: "{colors.hairline}"
    rounded: "{rounded.sm}"
    padding: "0px {spacing.xs}"
    height: 28px
  button-primary:
    backgroundColor: "{colors.accent}"
    textColor: "#0a0a0a"
    rounded: "{rounded.pill}"
    padding: "0px {spacing.sm}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    borderColor: "{colors.hairline}"
    rounded: "{rounded.pill}"
    padding: "0px {spacing.sm}"
  button-primary-sm:
    backgroundColor: "{colors.accent}"
    textColor: "#0a0a0a"
    rounded: "{rounded.pill}"
    padding: "0px {spacing.xs}"
  card-experience:
    backgroundColor: "{colors.canvas-card}"
    textColor: "{colors.ink}"
    borderColor: "{colors.hairline}"
    hoverBorderColor: "{colors.accent}"
    rounded: "{rounded.lg}"
    padding: "{spacing.xl}"
  card-stat:
    backgroundColor: "{colors.canvas-soft-2}"
    textColor: "{colors.ink}"
    borderColor: "{colors.hairline}"
    rounded: "{rounded.md}"
    padding: "{spacing.lg}"
  card-game:
    backgroundColor: "{colors.game-surface}"
    textColor: "{colors.ink}"
    borderColor: "{colors.game-border}"
    rounded: "{rounded.lg}"
    padding: "{spacing.xl}"
  badge-accent:
    backgroundColor: "{colors.accent-soft}"
    textColor: "{colors.accent}"
    rounded: "{rounded.full}"
    padding: "0px {spacing.xs}"
  badge-secondary:
    backgroundColor: "{colors.canvas-soft-2}"
    textColor: "{colors.body}"
    rounded: "{rounded.full}"
    padding: "0px {spacing.xs}"
  live-counter:
    fontFamily: "{typography.counter}"
    textColor: "{colors.accent}"
    backgroundColor: "{colors.canvas-card}"
    borderColor: "{colors.hairline}"
    rounded: "{rounded.md}"
    padding: "{spacing.lg}"
  form-input:
    backgroundColor: "{colors.canvas-soft}"
    textColor: "{colors.ink}"
    borderColor: "{colors.hairline}"
    rounded: "{rounded.sm}"
    padding: "0px {spacing.sm}"
    height: 40px
  hero-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    padding: "{spacing.section} {spacing.lg}"
  footer:
    backgroundColor: "{colors.canvas}"
    borderColor: "{colors.hairline}"
    textColor: "{colors.body}"
    padding: "{spacing.4xl} {spacing.lg}"

---

## Overview

Real Fun AI is a dark-first interactive AI experiences website. The design is
built on Vercel's stark system but polarity-flipped: near-black canvas surfaces,
white ink text, and an electric green accent (#00ff88) that acts as the single
conversion and highlight color. The multi-stop mesh gradient (neural blue →
model violet/pink → data coral/amber) is the only hero decoration — used at
full bleed scale only, never miniaturised.

Every counter, score, and live stat uses the monospace counter token to signal
real-time data. Cards are dark (#141414) with hairline borders that glow green
on hover. The overall feel: an AI control room, not a marketing brochure.

## Colors

### Core Surfaces (dark-first)
- **Canvas** (#0a0a0a): The deepest background. Page body, full-bleed hero bands.
- **Canvas Soft** (#111111): Default section background. Sits one step above canvas.
- **Canvas Soft 2** (#1a1a1a): Inset regions, code block backgrounds, table headers.
- **Canvas Card** (#141414): Experience cards, game surfaces, stat panels.
- **Canvas Raised** (#1f1f1f): Elevated cards, modals, dropdowns.

### Accent
- **Accent** (#00ff88): The single primary CTA and highlight color. Used for primary
  buttons, hover borders on cards, live counter values, active nav links, and
  selection highlights. Never used as a background at large scale.
- **Accent Soft** (#00ff8815): Subtle tinted backgrounds for badges and info panels.
- **Accent Deep** (#00cc66): Pressed/hover state for accent elements.

### Text
- **Ink** (#ffffff): All primary headings and body on dark surfaces.
- **Body** (#a1a1a1): Secondary text, nav links, card subtitles, footer body.
- **Mute** (#555555): Lowest priority — placeholders, fine print, disabled states.

### Brand Gradient
Three gradient pairs collapse into the hero mesh:
- **Neural**: #007cf0 → #00dfd8 (blue to teal — the AI data flow pair)
- **Model**: #7928ca → #ff0080 (violet to pink — the model intelligence pair)
- **Data**: #ff4d4d → #f9cb28 (coral to amber — the output/result pair)

Use the gradient as one unified atmospheric object at hero scale only. Never
reduce to a single color, never miniaturise to an icon or badge.

### Game Tokens
- **Game Surface** (#0f0f0f): The darkest surface, used inside game iframes/panels.
- **Game Border** (#2a2a2a): Structural dividers inside game UIs.
- **Game Success** (#00ff88): Correct answers, win states, positive outcomes.
- **Game Fail** (#ee0000): Wrong answers, fail states, error outcomes.
- **Game Highlight** (#f9cb28): Timer warnings, score milestones, attention pulls.

## Typography

### Font Families
- **Display + Body**: Geist (Inter as fallback). Weights 400/500/600 only. Never 700+.
- **Mono + Counters**: Geist Mono (JetBrains Mono as fallback). All live counters,
  stats, scores, code blocks, and technical labels use this face.

### Key Rules
- Sentence-case headlines, period-terminated. Aggressive negative tracking is the voice.
- Mono is for counters, stats, code, and technical eyebrows ONLY.
- Weight 600 is the display ceiling. Never 700 or heavier.
- The counter token (32px / Geist Mono) is used for all live number displays.

## Layout

Same spacing system and grid as Vercel base. Max width 1400px, 24px gutters desktop,
16px mobile. Experience grid: 2x2 at desktop, 1-up at mobile.

## Elevation

Same stacked shadow system as Vercel base, but on dark surfaces:
- Level 0: No shadow. Full-bleed hero and section bands.
- Level 1: 1px inset hairline (#222222). Default card chrome.
- Level 2: Subtle drop + inset hairline. Experience cards at rest.
- Level 3: Soft stack. Experience cards on hover (add accent border glow).
- Level 4: Float stack. Modals, dropdowns, elevated panels.

## Components

### Experience Cards
Dark (#141414) surface, hairline (#222222) border at rest. On hover: border
color transitions to accent (#00ff88) with a subtle glow. Rounded lg (12px).
Each card hosts: a mono eyebrow label (caption-mono), a display-md headline,
a body-sm description, and a pill CTA button.

### Live Counters
Monospace counter token (32px Geist Mono) in accent green on canvas-card surface.
Always include a caption-mono label above and a body-sm description below.
Animate value changes with a brief number-roll transition.

### Game Surfaces
Full-page game experiences use game-surface (#0f0f0f) as the base. Game UI
elements (score panels, timers, input areas) use canvas-card with game-border
dividers. Win/fail states use game-success/game-fail with a full-surface flash.

## Do's and Don'ts

### Do
- Use accent (#00ff88) for ALL primary CTAs, active states, and live data values.
- Set every counter and stat in Geist Mono counter token — mono signals live data.
- Keep the hero mesh gradient at full bleed scale only — it is the entire decoration system.
- Use hairline borders (#222222) on all cards; transition to accent on hover.
- Layer stacked shadows on dark surfaces — same multi-offset approach as Vercel base.
- Keep headlines sentence-case with aggressive negative tracking.
- Use canvas-card (#141414) for experience cards, NOT canvas-soft.

### Don't
- Don't use accent green as a large background fill — it is an accent, not a surface.
- Don't introduce new accent colors. The palette is: ink + grays + accent green + mesh gradient.
- Don't render headlines in all-caps. Sentence-case + negative tracking is the voice.
- Don't use the geometric sans for counters or stats — mono only for live numbers.
- Don't miniaturise the mesh gradient. Hero scale only.
- Don't promote Geist to weight 700. Display ceiling is 600.
- Don't use white/light canvas surfaces — this is a dark-first site throughout.
