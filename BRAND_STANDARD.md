# D2CE4I — Brand Color Standard (v1.2)

**Decision:** Approved as the planned D2CE4I visual brand standard on 18 November 2026.  
**Brand character:** Calm, high-quality, modern, open, human. Minimal and precise rather than playful.

## Brand positioning

D2CE4I maintains the clear typographic and editorial design attitude of Minds4Motion, but is deliberately distinct from its black/white/red palette. D2CE4I uses **charcoal + white + deep teal**, in two equally valid display modes.

## Color tokens

| Token | Light mode | Dark mode | Meaning |
| --- | --- | --- | --- |
| Background | `#F7F9F8` | `#20262A` | Main page background |
| Surface | `#FFFFFF` | `#293137` | Hero, cards and contact panel |
| Secondary surface | `#EFF4F2` | `#313C41` | Optional secondary UI |
| Main text | `#252B30` | `#F9FAFB` | Headlines and content |
| Secondary text | `#58666A` | `#C1CDCE` | Support copy |
| Accent (Deep Teal) | `#087D73` | `#48C5B3` | The numerals 2 and 4, small highlights, interactive accents |
| Border | `#D7E1DE` | `#4B5A5E` | Quiet separators |

Use accents deliberately; preserve strong white space and legibility. No high-saturation yellow, stock icon colors, loud gradients or additional competing accent colors.

## Theme behavior and icons

- Both **light and dark** are first-class brand experiences.
- Default to the user's operating-system color preference.
- Provide a visible manual toggle, and retain its selection locally across page loads.
- Toggle symbols are **monochrome SVG** with a CSS `currentColor` stroke mapped to `--accent`—therefore teal in both modes, never platform-dependent yellow emoji.
- Sun represents the **switch to light mode** while dark is active; moon represents **switch to dark mode** while light is active.
- Keep the control accessible with text and an explicit action-oriented `aria-label`.

## Identity constants

- D2CE4I logotype; numerals **2** and **4** emphasized in the active theme's teal
- **Discover · Connect · Create · Experience**
- **From Inspiration to Impact.**
- **Human potential. Shared possibilities.**

## Governance

This document is the agreed **brand color baseline** for subsequent website and product iterations, not a claim of a registered/trademarked brand. Future visual changes should cite and explicitly revise this standard. The historical initial launch remains recorded as v1.1 in `VERSION.md`.
