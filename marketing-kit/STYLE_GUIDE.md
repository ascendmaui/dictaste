# Dictaste style guide

Use this with the files in `marketing-kit/`. Color and type values below are taken from this repository’s only styled source, `docs/index.html`, unless a row says otherwise.

## Color

| Token | Value | Where it is used in `docs/index.html` |
| --- | --- | --- |
| Background | `#0A0A0B` | `body` background |
| Text | `#FFFFFF` | `body` color |
| Muted text | `#A1A1A6` | `p`, ghost button |
| Meta | `#6B6B70` | `.meta` |
| Lime | `#C8F542` | `.pill` text, `.btn` background, `.note a` |
| Lime pill fill | `rgba(200, 245, 66, 0.10)` | `.pill` background |
| Lime pill border | `rgba(200, 245, 66, 0.35)` | `.pill` border |
| Surface | `#141416` | `.card` background |
| Border | `#2A2A2E` | `.card` border, ghost button border |
| Ink on lime | `#0A0A0B` | `.btn` text |

Buttons in that file are lime `#C8F542` with `#0A0A0B` text, weight 650, radius 10px. Ghost buttons are transparent with a `#2A2A2E` border and `#A1A1A6` text.

The published app icon is a separate sampled palette. It is not declared as CSS variables in this repository:

| Part | Sampled value |
| --- | --- |
| Tile | `#0B141B` |
| Ring | `#85E42F` |
| Inner mark | `#FFFFFF` |

`logo/logo-mark.svg` uses those sampled colors. UI chrome in the banners (eyebrows, buttons, pills) uses `#C8F542` from `docs/index.html`.

The public Windows client in `johnmatveyev-lab/dictaste` (`windows/src/settings.html`) repeats `#0A0A0B`, `#FFFFFF`, `#A1A1A6`, `#C8F542`, `#2A2A2E`, and `#141416`, and also sets `--magenta: #FF2D95`. Magenta is not used in this repository and is not used in this kit.

## Type

From `docs/index.html`:

| Role | Stack |
| --- | --- |
| UI | `ui-sans-serif, system-ui, -apple-system, sans-serif` |
| Meta / code | `ui-monospace, SFMono-Regular, Menlo, monospace` |

| Setting | Value | Where |
| --- | --- | --- |
| Wordmark weight | 650 | `.logo span` |
| Wordmark tracking | `-0.02em` | `.logo span` |
| Heading tracking | `-0.03em` | `h1` |
| Pill weight | 600 | `.pill` |
| Button weight | 650 | `.btn` |
| Body line height | 1.55 | `p` |
| Heading size on the download page | 40px | `h1` |
| Pill size | 12px | `.pill` |
| Meta size | 12px | `.meta` |

Radii in that file: logo image 9px on a 32px icon, cards 16px, buttons 10px, pills 999px.

This repository does not declare a webfont. The public Windows client sets `font-family: Inter, system-ui, sans-serif`. The published site stylesheet also loads Space Grotesk and JetBrains Mono. Kit SVG text uses `Inter`, then the `docs/index.html` stack, so a machine without Inter still resolves to the system sans.

## Logo

- `logo/logo-mark.svg` is a trace of the icon published at `https://dictaste.vercel.app/brand/icon.png`: dark rounded tile, lime ring, white inner mark. Corners outside the tile are transparent.
- `logo/logo-mark.png` is 1024×1024, with the same transparent corners.
- `logo/logo-wordmark.svg` and `logo/logo-wordmark.png` place the mark beside the word **Dictaste** in white on `#0A0A0B`. The word uses weight 650 and `-0.02em` tracking.
- Do not recolor the ring to `#C8F542`. That lime is the UI accent. The ring color is the sampled icon green.
- Do not set the wordmark in a serif, and do not add a second tagline inside the wordmark file.

## Voice

Tagline, used as written: **Speak it. Ship it.**

Describe the product as system-wide AI dictation and highlight-to-speak for Mac and Windows. The live site is `https://dictaste.vercel.app`. `dictaste.com` is not live.

Say these distribution facts when downloads come up:

- Primary download: notarized Mac DMG v0.1.4 (Apple Silicon and Intel).
- Windows is a portable preview, unsigned. SmartScreen may warn.

Pricing, written this way:

- Free
- Pro $4/mo or $32/yr
- Pro Plus $8/mo or $64/yr
- Developer tier: free with a GitHub star on `johnmatveyev-lab/dictaste` and the developer’s own API key
- Affiliates: 30%

Support is GitHub Issues on `johnmatveyev-lab/dictaste` only. Do not publish a support email. Do not use `support@dictaste.com`.
