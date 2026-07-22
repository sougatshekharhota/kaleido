# KALEIDO — Design System Generator

**One brief in. A whole design system out.**

KALEIDO turns a short brief — your industry, what you're building, the mood you want, and your platform — into a complete, coherent design system: a named style direction, a generated color palette, a type pairing, layout tokens, industry-specific UX guidance, a recommended stack, and a **live preview** you can export as design tokens.

🔗 **Live:** https://sougatshekharhota.github.io/kaleido/

## What it does

- **Style direction** — chosen from a catalog of named styles by matching your industry, mood and product against each style's affinity.
- **Color palette** — *generated*, not looked up: an HSL engine derives primary, accent, neutrals and semantic colors from a seed hue, then adaptively tunes lightness so every text/background and button pairing clears **WCAG AA (4.5:1)**.
- **Typography** — a curated heading + body pairing from Google Fonts, loaded live into the preview.
- **Layout tokens** — radius, density, shadow, spacing scale.
- **UX guidance** — do's and don'ts tuned to how each industry's audience actually behaves.
- **Recommended stack & components** — sensible defaults per platform and product type.
- **Live preview + export** — a rendered mini-UI using the full system, exportable as JSON tokens, CSS variables, or a Tailwind theme.

## How it works

Everything runs in the browser — no backend, no API keys, no data leaves your device.

1. Your inputs are turned into a bag of **affinity tags**.
2. Styles and font pairings are **scored** against those tags; the best match is selected (with a light shuffle so "Another take" surfaces alternatives).
3. A **seed hue** comes from the industry, nudged by mood; the palette engine builds a harmonious, accessibility-checked token set around it.
4. The system renders into a live preview and can be exported.

## Coverage

18 industries × 8 product types × 10 moods × 6 platforms — thousands of combinations, each producing a distinct, coherent system.

## Tech

Single self-contained `index.html`. Vanilla JS, no dependencies. Google Fonts loaded on demand for previews. Hosted free on GitHub Pages.

---

Built by [Sougat Shekhar Hota](https://sougatshekharhota.github.io/portfolio/). Design intelligence, generated — recommendations are a strong starting point, not a substitute for design judgement.
