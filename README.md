# Catppuccin for Standard Notes

[Catppuccin](https://github.com/catppuccin/catppuccin) theming for [Standard Notes](https://standardnotes.com/).

All 4 Catppuccin flavors are included:

| Flavor | Type | Directory |
|---|---|---|
| 🌻 Latte | Light | `com.catppuccin.latte-theme` |
| 🪴 Frappé | Dark | `com.catppuccin.frappe-theme` |
| 🌺 Macchiato | Dark | `com.catppuccin.macchiato-theme` |
| 🌿 Mocha | Dark | `com.catppuccin.mocha-theme` |

## Installation

Use the published GitHub Pages CSS URLs in Standard Notes:

- Latte: `https://joec-dev.github.io/catpuccin_StandardNotes/com.catppuccin.latte-theme/src/theme.css`
- Frappé: `https://joec-dev.github.io/catpuccin_StandardNotes/com.catppuccin.frappe-theme/src/theme.css`
- Macchiato: `https://joec-dev.github.io/catpuccin_StandardNotes/com.catppuccin.macchiato-theme/src/theme.css`
- Mocha: `https://joec-dev.github.io/catpuccin_StandardNotes/com.catppuccin.mocha-theme/src/theme.css`

## Building

Each theme directory contains a `package.json` with a build script that copies the CSS into a `dist/` folder alongside the `plugin.json`:

```bash
cd com.catppuccin.mocha-theme
npm install
npm run build
```

## Color Palettes

The full Catppuccin color palette for each flavor is available at [catppuccin/catppuccin](https://github.com/catppuccin/catppuccin#-palette).
