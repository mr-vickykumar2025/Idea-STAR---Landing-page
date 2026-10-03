# Ideastar Responsive Landing Page

A custom, responsive landing page concept for an independent creative studio. Built with semantic HTML5, modern CSS Grid/Flexbox, and vanilla JavaScript.

## Files

- `index.html` — page structure and content
- `styles.css` — theme, layout, responsive breakpoints, and reduced-motion support
- `script.js` — accessible mobile navigation toggle and dynamic footer year

## Run locally

1. Extract the ZIP.
2. Open `index.html` in a modern browser.

No build tools, package installation, or server are required. Google Fonts are loaded online; system fallbacks are included.

## Design / wireframe

```text
┌─────────────────────────────────────────────────────────┐
│ Brand                         Nav links      Contact CTA │
├─────────────────────────────────────────────────────────┤
│ Eyebrow              │ Abstract editorial hero artwork  │
│ Large headline       │ layered shapes + field-notes card │
│ Intro copy           │                                  │
│ CTA + secondary link│                                  │
│ Social proof         │                                  │
├─────────────────────────────────────────────────────────┤
│ Strategy with soul — Design with direction — Progress   │
├─────────────────────────────────────────────────────────┤
│ Eyebrow       Main statement              Supporting copy│
├─────────────────────────────────────────────────────────┤
│ Section heading and description                         │
│ ┌────────────────┐ ┌────────────────┐ ┌───────────────┐ │
│ │ Strategy card  │ │ Design card     │ │ Growth card   │ │
│ └────────────────┘ └────────────────┘ └───────────────┘ │
├─────────────────────────────────────────────────────────┤
│ Testimonial / quote                                      │
├─────────────────────────────────────────────────────────┤
│ Contact headline                       Email CTA         │
├─────────────────────────────────────────────────────────┤
│ Footer brand, note, back-to-top, links                   │
└─────────────────────────────────────────────────────────┘
```

On small screens, the hero and feature cards stack vertically, and the navigation becomes a keyboard-accessible menu toggle.

## Customization

- Replace the studio name, copy, email, and social links in `index.html`.
- Adjust the color tokens near the top of `styles.css` in `:root`.
- Change breakpoints in `styles.css` to suit your target devices.
- The hero artwork is made with CSS shapes, so no image assets are required.

## Accessibility notes

- Semantic landmarks and a skip link
- Mobile menu button exposes `aria-expanded` and an accessible label
- Visible keyboard focus states
- Reduced-motion preference support
