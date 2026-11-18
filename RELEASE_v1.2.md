# D2CE4I Website v1.2 — Deep Teal

**Status:** Proposed for review / publish after merge.  
**Baseline:** v1.1 remains recorded in [VERSION.md](VERSION.md).

## Design
- Art direction: calm, premium, minimal, approachable
- Light: background `#F7F9F8`, surface `#FFFFFF`, text `#252B30`, accent `#087D73`
- Dark: background `#20262A`, surface `#293137`, text `#F9FAFB`, accent `#48C5B3`
- Black/red brand treatment replaced with charcoal/teal while preserving the wordmark, editorial typography and layout
- Numerals **2** and **4** remain visually emphasized in both modes
- Neutral panels, subtle borders, quiet interactions; no gradients, animation clutter or third-party assets

## Behavior
- Theme follows system preference on first visit
- A visible switch in the page header toggles dark/light
- Manual preference is stored locally and respected on later visits
- When no manual preference is set, system theme changes continue to apply
- The HTML contact button retains the correct address `md@minds4motion.com`, assembled on click
- Static website, no server or added analytics

## Review and publication
1. Review the Pull Request and merge into `main`.
2. Run the existing **Publish D2CE4I Website** GitHub Actions workflow manually on `main`.
3. Inspect `https://d2ce4i.com` on mobile and desktop: initial theme, switching, reload persistence, contrast, and the contact button.

The workflow remains manual; merging this PR does not publish v1.2 automatically.
