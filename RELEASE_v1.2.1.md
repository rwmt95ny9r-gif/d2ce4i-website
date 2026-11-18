# Landingpage navigation polish — v1.2.1

Date: 18 November 2026

This is a small usability iteration on the approved v1.2 Deep Teal brand standard. It introduces no new colors or external dependencies.

## Changes

- Floating circular **Back to top** control (bottom-right) appears only after meaningful scrolling
- Minimal teal up-arrow SVG instead of a platform-dependent emoji; works in both theme modes
- Tap/click smoothly returns to top; respects **prefers-reduced-motion**
- Safe-area positioning for phones with home indicators
- A quiet **Explore the vision** action in the hero links to the four D2CE4I dimensions below
- **Skip to content** keyboard navigation link and visible keyboard focus styles
- Removed the redundant bottom-of-page Back to top link

## Unchanged

- Deep Teal light and dark brand palette
- Theme toggle, system detection and persisted preference
- D2CE4I content and four dimensions
- Obfuscated click-to-email contact at `md@minds4motion.com`
- No tracking, cookies, forms, external assets, or backend

## Deployment

After merging this change, manually run `Publish D2CE4I Website` on the `main` branch. Verify mobile and desktop, both theme modes, keyboard operation and the floating button after scrolling.

## Validation

Code read-back and both inline JavaScript blocks were syntax-checked. Live browser testing is pending publication.
