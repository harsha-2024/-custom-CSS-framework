# Aurora CSS

A scalable, utility‑first CSS framework with design tokens, responsive utilities, accessible components, theming (light/dark), classic layout primitives, and example templates. No build step required—just drop the compiled CSS—or customize via tokens.

## Highlights
- **Design tokens** (colors, spacing, typography, radii, shadows) using CSS variables
- **Base resets** and sensible defaults
- **Responsive utilities** with breakpoint prefixes (`sm:`, `md:`, `lg:`, `xl:`)
- **State variants** (`hover:`, `focus:`, `active:`, `disabled:`) via attribute selectors
- **Components**: buttons, forms, cards, alerts, badges, navbars, modals, tables, tabs, toasts, tooltips
- **Layout**: container, grid, flex helpers, stack/cluster/center/util patterns
- **Theming**: light/dark + example brand theme; easy to extend
- **Accessibility**: focus rings, reduced motion, high‑contrast opt‑in

## Quick start
Use `dist/aurora.css` or the minified `dist/aurora.min.css`:

```html
<link rel="stylesheet" href="./dist/aurora.min.css" />
```

See `examples/` for templates.

## Customize
Edit tokens in `src/tokens/` (CSS variables). Rebuild by concatenating `src/**` in order (tokens → base → layout → utilities → components → themes). For convenience we ship prebuilt files in `dist/`.
