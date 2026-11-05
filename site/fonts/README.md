# Fonts

Both fonts use the SIL Open Font License 1.1. The license files are in this folder. Keep them with the font files.

| Font | Use | Source | Files |
|---|---|---|---|
| Atkinson Hyperlegible Next | Text | Fontsource package `@fontsource/atkinson-hyperlegible-next` 5.3.0, Latin subset | Regular, Bold, Italic, BoldItalic |
| JetBrains Mono NL | Code | Official JetBrains Mono release 2.304 (NL = no ligatures) | Regular, Bold, Italic, BoldItalic |

## Folders

- `web/`: WOFF2 files for the site. Preload only the two Regular files.
- `ttf/`: static TTF files for Asciidoctor PDF.

## CSS names

```css
font-family: "Atkinson Hyperlegible Next";   /* text */
font-family: "JetBrains Mono NL";            /* code */
```

The `@font-face` rules are in `design/reference/chapter-1-7.html`.

## Limits

- The Atkinson Hyperlegible Next files contain only Latin characters. This is sufficient for English. Before a translation, get the full font files from the official project (`github.com/googlefonts/atkinson-hyperlegible-next`).
- The TTF files of Atkinson Hyperlegible Next were made from the Latin WOFF files of the same package.
- The JetBrains Mono NL WOFF2 files contain the full character set (approximately 72 KB each). If the page weight is too high, make a Latin subset.
