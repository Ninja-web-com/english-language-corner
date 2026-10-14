# Accessibility notes

- Sticky nav uses `scroll-margin-top` so anchors land correctly
- Active nav links set `aria-current="page"`
- Theme toggle and hamburger have clear `aria-label` values
- Focus rings use a consistent cyan outline (`:focus-visible`)
- Animations respect `prefers-reduced-motion`
- Light mode muted text uses higher contrast (`#334155`)
- Mobile menu closes on link click and on Escape
