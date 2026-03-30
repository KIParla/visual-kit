# Typography

---

## Fonts

| Role | Family | License | Source |
| --- | --- | --- | --- |
| Base (UI & body) | Lato | SIL OFL | [Google Fonts](https://fonts.google.com/specimen/Lato) |
| Display (SVG assets & layouts) | Caveat | SIL OFL | [Google Fonts](https://fonts.google.com/specimen/Caveat) |

Both fonts are free and open-source. Caveat is used for the "k parla" wordmark inside layout SVGs; Lato is used for all other text.

---

## Weights (Lato)

| Token | Value | Usage |
| --- | --- | --- |
| `regular` | 400 | Body text |
| `medium` | 500 | UI elements, captions |
| `semibold` | 600 | Subheadings, labels |
| `bold` | 700 | Headings, emphasis |

---

## Type Scale

| Token | rem | px | Usage |
| --- | --- | --- | --- |
| `xs` | 0.75rem | 12px | Captions, metadata |
| `sm` | 0.875rem | 14px | Secondary text, labels |
| `md` | 1rem | 16px | Body (base size) |
| `lg` | 1.125rem | 18px | Lead text |
| `xl` | 1.25rem | 20px | Subheadings (h4–h5) |
| `2xl` | 1.5rem | 24px | Headings (h3) |
| `3xl` | 2rem | 32px | Display headings (h1–h2) |

---

## Line Heights

| Token | Value | Usage |
| --- | --- | --- |
| `tight` | 1.2 | Headings |
| `base` | 1.5 | Body text |
| `relaxed` | 1.7 | Long-form reading |

---

## CSS Variables

```css
font-family: var(--font-family-base);      /* Lato */
font-family: var(--font-family-heading);   /* Lato */

font-weight: var(--font-weight-regular);   /* 400 */
font-weight: var(--font-weight-medium);    /* 500 */
font-weight: var(--font-weight-semibold);  /* 600 */
font-weight: var(--font-weight-bold);      /* 700 */

font-size: var(--font-size-md);            /* 1rem / 16px */
line-height: var(--line-height-base);      /* 1.5 */
```
