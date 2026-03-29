# KIParla Visual Kit

A collection of SVG assets and design tokens for the [KIParla](https://kiparla.it) research project — a corpus of spoken Italian. The kit provides visual building blocks for presentations, publications, and interfaces related to the project.

## Assets

All assets are in `assets/`, organized by category. Most icons come in two color variants: **red** (brand color, `#E52424`) and **white** (for use on dark backgrounds).

### `assets/speakers/`

Human figure illustrations representing corpus participants and spoken contributions.

- `adult-speaker.svg`, `young-speaker.svg`, `old-speaker.svg` — silhouettes by age group
- `generic-contribution.svg` — abstract representation of a spoken contribution
- `question.svg` — question mark illustration

### `assets/conversation/`

Icons representing conversation contexts and registers.

- `dinner` — informal dinner setting
- `exam` — exam or evaluation context
- `formal` / `informal` — register markers
- `interview` — interview context
- `lecture` — academic lecture

### `assets/places/`

Geographic and spatial icons.

- `italy.svg`, `italy-question.svg` — Italian territory outline
- `inside` / `outside` — private vs public setting markers

### `assets/layouts/`

Reusable layout and background components.

- `background.svg` — decorative background pattern
- `layout-1.svg`, `layout-2.svg`, `layout-3.svg` — card layout templates

## Design Tokens

The `style/` folder contains a design system for consistent visual styling across all KIParla materials.

| File | Description |
| --- | --- |
| `style/tokens.json` | Design tokens in JSON (colors, typography, spacing) |
| `style/tokens.css` | Same tokens as CSS custom properties, ready to import |
| `style/colors.md` | Color palette documentation with usage notes |
| `style/palette.html` | Visual preview of the color palette |

The primary brand color is **red `#E52424`**. Typography is based on [Lato](https://fonts.google.com/specimen/Lato) (SIL Open Font License).

## Usage

Import `style/tokens.css` into your project to use the design tokens:

```css
@import url('path/to/style/tokens.css');

.my-element {
  color: var(--color-primary-500);
  font-family: var(--font-family-base);
  padding: var(--spacing-md);
}
```

SVG assets can be used inline or as `<img>` tags. For color customization, inline SVGs support CSS targeting via class names.

## License

Released under [CC BY-NC-SA 4.0](LICENSE) — free for personal and research use, with attribution. Commercial use is not permitted. Derivatives must use the same license.

## About

Developed as part of the [KIParla](https://kiparla.it) research initiative by [@iacovfn-cpu](https://github.com/iacovfn-cpu). Contributions via issues and pull requests are welcome.
