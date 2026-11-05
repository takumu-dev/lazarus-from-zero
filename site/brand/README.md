# Lazarus from Zero — logo files

Logo: "Ember from zero". A red-orange ember rises from a slashed zero.
Colors: ink `#141720`, ember `#e8452c`, white `#ffffff`.
License: CC BY-SA 4.0, like the text of the tutorial.

## Files

| File | Use |
|---|---|
| `logo.svg` | Main logo with the dark square. Use it at 48 px and bigger. |
| `logo-small.svg` | Simple version for 16 px to 32 px: bigger ember, thicker zero, no slash. |
| `logo-glyph-on-dark.svg` | Ember and white zero, no square. Use it on dark backgrounds. |
| `logo-glyph-on-light.svg` | Ember and ink zero, no square. Use it on light backgrounds. |
| `favicon.svg` | Browser tab icon (from `logo-small.svg`). |
| `favicon.ico` | Browser tab icon for old browsers: 16, 32 and 48 px. |
| `favicon-16.png`, `favicon-32.png` | PNG browser tab icons. |
| `apple-touch-icon.png` | 180 px icon for iPhone and iPad. Full square: iOS rounds the corners. |
| `icon-192.png`, `icon-512.png` | Icons for the web app manifest. |
| `icon-maskable-512.png` | Full-square icon for Android. The logo stays inside the safe zone. |
| `site.webmanifest` | Web app manifest that uses the icons. |
| `og-image.png` (and `og-image.svg`) | Share image, 1200 × 630 px, for search engines, chats and social media. |
| `lockup-on-light.png`, `lockup-on-dark.png` | Logo with name and subtitle, transparent background, 1840 × 480 px. For the README and slides. |

## HTML for the `<head>` of each page

```html
<link rel="icon" href="/favicon.ico" sizes="48x48">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
<link rel="manifest" href="/site.webmanifest">
<meta name="theme-color" content="#141720">
<meta property="og:image" content="https://<domain>/og-image.png">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
<meta property="og:image:alt" content="Lazarus from Zero: Modern Free Pascal for Beginners">
```

## Rules

- Do not change the colors, the shapes or the positions.
- Keep a free space around the logo of 1/4 of its width minimum.
- Use `logo-small.svg` (or `favicon.svg`) below 48 px. Use `logo.svg` from 48 px.
- Do not put the logo on a red-orange background or on a busy photo.
- Do not add effects (shadows, gradients, outlines).
- The share image and the lockups use the font Atkinson Hyperlegible Next. The PNG files already contain the text.
