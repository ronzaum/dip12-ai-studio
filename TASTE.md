# TASTE.md

How every visual output in this repo looks. `/artifact` reads this file before it makes anything.

This is Ron's base, taken from the AI Sessions setup guide (`outputs/_reference-setup-guide.html`). **It is yours to change.** Swap the font, the colour, the grid. A page that looks like everyone else's is a page nobody thought about.

## Principles
- One idea per page. Cut until it hurts.
- Black on white. Hierarchy from size, weight and space, not colour.
- Everything sits on the grid. Nothing floats.
- Labels in small capitals. Content in plain sentences.
- Real content only. No placeholder text, no stock imagery, no decorative icons.
- Every image, figure and quote carries its source.

## Type
| Role | Spec |
|---|---|
| Font | Arial, Helvetica, sans-serif |
| Body | 13px, line height 20px, regular |
| Lead | 13px / 20px, bold |
| Title | 52px / 60px, bold, uppercase, letter-spacing -0.04em |
| Label | 10px / 20px, bold, uppercase, letter-spacing 0.06em |
| Section number | 32px / 26px, bold, letter-spacing -0.03em (`01`, `02`) |
| Small print | 10px / 20px |

## Colour
| Role | Value |
|---|---|
| Text | `#000` |
| Background | `#fff` |
| Rules | 1px `#bbb` |
| Accent | none by default. If you add one, use it for one thing only. |

## Grid
- Baseline: 20px. Every line of text lands on it.
- Two columns: a 136px label column, 24px gap, content column.
- Page: A4 portrait, margins 13mm top, 14mm sides, 11mm bottom. On screen, max width 210mm, centred.
- Sections: label on the left, thin rule above, content on the right.
- Lists: numbered steps hang their number in the margin (`1.`); bullets use an en dash (`–`).

## Page structure
1. Top line: project label left, your name or contact right (labels).
2. Title, then one bold lead sentence that says what the page is for.
3. Two to five labelled sections.
4. Final section **ACCOUNT**: what AI compiled, what you decided (from `DECISIONS.md`), and sources.

## Output rules
- One self-contained `.html` file in `outputs/`, named `YYYY-MM-DD-<slug>.html`. Styles inline, no external dependencies except images in `outputs/assets/`.
- Prints cleanly to one A4 page where possible.
- Works on a phone: below 640px the two columns stack.
