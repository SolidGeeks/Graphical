# Solid Geeks — Logo usage guide

## 1. The logo
**Idea:** a barbell whose plates are brackets `[ ]`. Code that lifts iron: *solid* and *geek* at a glance.

**Versions:**
- **Horizontal** (main): `sg-horizontal-*.svg`
- **Stacked**: `sg-stacked-*.svg`
- **Symbol only**: `sg-symbol-*.svg`
- **Name only**: `sg-wordmark-ink.svg`
- **Small sizes** (16–24 px): `sg-symbol-small.svg` and `sg-favicon-tile.svg`, drawn pixel by pixel.

The symbol is built on a 4-unit grid, symmetrical on both axes. Plates: 36 × 176. Bracket arms: 24 × 28. Bar: 16. Collars: 12 × 48.

## 2. Clear space
Around the logo, keep a free space equal to **the width of one plate** (one upright of a bracket). The space grows with the logo.

## 3. Minimum sizes
| Version | Screen | Print |
|---|---|---|
| Horizontal | 120 px wide | 30 mm |
| Symbol (master) | 32 px | 8 mm |
| Symbol (small size) | 16 px | 5 mm |

## 4. Colours
| Name | HEX | RGB | CMYK (approx.) | Use |
|---|---|---|---|---|
| **Volt** | `#C8FF2E` | 200 255 46 | 22 0 82 0 | The symbol on dark backgrounds. The signature. |
| **Ink** | `#0D0F0C` | 13 15 12 | 75 60 70 90 (rich black) | Backgrounds, text, logo on light backgrounds. |
| White | `#FFFFFF` | 255 255 255 | 0 0 0 0 | The name on dark backgrounds. |

Volt has no exact Pantone match. For print (stickers, T-shirts), check a fluorescent green such as 802 C against a swatch book.

**Allowed combinations:**
- Volt symbol and white name on Ink (avatars, dark README, T-shirt).
- All-Ink logo on white or light backgrounds.
- All-white logo on a dark photo.
- All-Ink logo on a Volt background.

**Not allowed:** Volt on white. The contrast is about 1.1:1, so it cannot be read.

## 5. Typography
- **Name:** DejaVu Sans Mono Bold, outlined, with the space between the words reduced to 60 %. Never type the name: always use the files.
- **Site and docs:** headings in DejaVu Sans Mono or JetBrains Mono, body text in Inter.
- **Licenses:** DejaVu (Bitstream Vera license), JetBrains Mono and Inter (SIL OFL). All are free, including for a logo.

## 6. Avatars and web
- **GitHub (organization) and Discord (server):** `png/sg-avatar-1024.png`. It is made to survive the round crop.
- **GitHub social preview** (Settings → Social preview): the cards in [SolidGeeks/.github `assets/social-preview/`](https://github.com/SolidGeeks/.github/tree/main/assets/social-preview), the crew for the organization's repositories and one card per project. `png/sg-social-preview-1280x640.png` is the logo-only alternative.
- **Website:** copy the contents of `web/` next to the page and paste `web/head-snippet.html` into the `<head>`. Paths are relative: this also works for a GitHub Pages site served from a subfolder (`/SolidGeeks/`, `/strata/`…).
- **GitHub README** (switches between light and dark automatically):

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="sg-readme-dark.svg">
  <img alt="Solid Geeks" src="sg-readme-light.svg" width="480">
</picture>
```

## 7. Don'ts
- Do not stretch, squash or rotate the logo.
- Do not recolour it outside the palette.
- Do not add shadows, outlines, gradients or neon effects.
- Do not separate, move or resize the parts of a version.
- Do not put the logo on a busy background without a solid area behind it.
- Do not use the master symbol below 32 px: use the small-size version.

## 8. Notes
- No trademark clearance search has been done. Before registering the mark, search the INPI, EUIPO and WIPO databases, and run a reverse image search.
- `presentation/board.html` is the presentation board, with README, terminal, sticker, T-shirt, social profile and browser tab mockups.
