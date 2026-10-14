# English Language Corner

A collaborative space to improve reading, listening, vocabulary, and speaking through practical activities.

**Live site:** open `index.html` locally or deploy the single file to any static host.

## Overview

Premium, modern single-page website built with **HTML5**, **CSS3**, and **vanilla JavaScript**. No frameworks, no build step.

## Features

- Sticky navigation with active section highlighting
- Light / dark mode toggle (persists in localStorage)
- Mobile hamburger menu
- Hero with gradient background and soft motion
- Five activity cards (responsive 3+2 grid)
- Six learning goals with numbered layout
- Four-step horizontal / vertical timeline
- Scroll progress bar and reveal animations
- Accessible focus states and `aria-current` on nav
- `prefers-reduced-motion` support

## Sections

| ID | Section |
|----|--------|
| `#home` | Hero |
| `#activities` | Our Activities |
| `#learning-goals` | Learning Goals |
| `#how-it-works` | How It Works |
| `#join-us` | Call to action |
| `#contact` | Footer / contact |

## Getting Started

```bash
git clone https://github.com/Ninja-web-com/english-language-corner.git
cd english-language-corner
open index.html
```

## Browser support

Works in current Chrome, Firefox, Safari, and Edge. Uses modern CSS (`color-mix`, backdrop-filter) with graceful fallbacks where needed.

## Docs

- [Activities](docs/activities.md)
- [Learning goals](docs/learning-goals.md)
- [How it works](docs/how-it-works.md)
- [Design system](docs/design.md)
- [Accessibility](docs/accessibility.md)
- [Deployment](docs/deployment.md)
- [Changelog](docs/changelog.md)

## Tech

- Semantic HTML5
- CSS custom properties (theming)
- DM Sans + Sora (Google Fonts)
- Intersection Observer for reveals
- Zero runtime dependencies

## License

MIT — see [LICENSE](LICENSE).
