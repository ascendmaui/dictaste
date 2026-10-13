# Dictaste marketing kit

Source files for logo, social images, store-screenshot templates, and copy. Artwork is SVG, with an HTML preview of the same SVG and a PNG export at the stated pixel size.

The live site is https://dictaste.vercel.app. `dictaste.com` is not live. Support is GitHub Issues on https://github.com/johnmatveyev-lab/dictaste/issues only. Do not publish `support@dictaste.com`.

## Index

| File | What it is |
| --- | --- |
| [STYLE_GUIDE.md](STYLE_GUIDE.md) | Colors and type from `docs/index.html`, plus the sampled icon colors |
| [SOCIAL_COPY.md](SOCIAL_COPY.md) | X and LinkedIn posts, with character counts |
| [LANDING_COPY.md](LANDING_COPY.md) | Hero, subhead, features, pricing, CTA, FAQ |
| [PRESS_BLURB.md](PRESS_BLURB.md) | Short blurb, longer blurb, boilerplate, fact sheet |
| [logo/logo-mark.svg](logo/logo-mark.svg) | Logo mark. Transparent outside the rounded tile |
| [logo/logo-mark.png](logo/logo-mark.png) | 1024×1024 PNG of the mark |
| [logo/logo-wordmark.svg](logo/logo-wordmark.svg) | Mark plus the word Dictaste, on `#0A0A0B` |
| [logo/logo-wordmark.png](logo/logo-wordmark.png) | 980×240 PNG of the wordmark |
| [social/x-header.svg](social/x-header.svg) | X header, 1500×500 |
| [social/x-header.html](social/x-header.html) | Browser preview of the X header |
| [social/x-header.png](social/x-header.png) | 1500×500 PNG |
| [social/linkedin-banner.svg](social/linkedin-banner.svg) | LinkedIn banner, 1584×396 |
| [social/linkedin-banner.html](social/linkedin-banner.html) | Browser preview of the LinkedIn banner |
| [social/linkedin-banner.png](social/linkedin-banner.png) | 1584×396 PNG |
| [social/og-image.svg](social/og-image.svg) | Open Graph image, 1200×630 |
| [social/og-image.html](social/og-image.html) | Browser preview of the Open Graph image |
| [social/og-image.png](social/og-image.png) | 1200×630 PNG |
| [screenshots/iphone-1290x2796.svg](screenshots/iphone-1290x2796.svg) | Vertical store template, 1290×2796 |
| [screenshots/iphone-1290x2796.html](screenshots/iphone-1290x2796.html) | Browser preview of the vertical template |
| [screenshots/iphone-1290x2796.png](screenshots/iphone-1290x2796.png) | 1290×2796 PNG |
| [screenshots/mac-2880x1800.svg](screenshots/mac-2880x1800.svg) | Mac store template, 2880×1800 |
| [screenshots/mac-2880x1800.html](screenshots/mac-2880x1800.html) | Browser preview of the Mac template |
| [screenshots/mac-2880x1800.png](screenshots/mac-2880x1800.png) | 2880×1800 PNG |

`logo/logo-mark.html` and `logo/logo-wordmark.html` are the same kind of browser preview for the logo files.

## Facts used in this kit

- Product: system-wide AI dictation and highlight-to-speak for Mac and Windows. Tagline: Speak it. Ship it.
- Site: https://dictaste.vercel.app. `dictaste.com` is not live.
- Primary download: notarized Mac DMG v0.1.4, Apple Silicon and Intel, macOS 13+.
- Windows: portable preview (`Dictaste-Setup-0.1.92.zip`), unsigned. SmartScreen may warn.
- Pricing: Free, Pro $4/mo or $32/yr, Pro Plus $8/mo or $64/yr.
- Developer tier: free with a GitHub star on `johnmatveyev-lab/dictaste` and your own API key. The key stays on the machine.
- Affiliates: 30% of the first attributed Pro or Pro Plus invoice. Payout at $25+.
- Support: https://github.com/johnmatveyev-lab/dictaste/issues only.

There is no iPhone app. Browser and mobile are later. `screenshots/iphone-1290x2796` is a vertical store-screenshot template at iPhone 14 Pro Max pixel size, not a capture of a phone app. `screenshots/mac-2880x1800` is a designed Mac-sized template, not a screenshot taken from the running app. The before/after lines in that Mac template are the product’s published polish example, shortened to fit the frame.

## Logo

The mark is traced from the icon at https://dictaste.vercel.app/brand/icon.png. UI colors and the wordmark’s weight and tracking come from `docs/index.html`. See [STYLE_GUIDE.md](STYLE_GUIDE.md).

## PNG export

PNGs were rendered from the SVG files with `rsvg-convert` at the width and height in the filename (the logo wordmark is 980×240). Inter is the first font in the SVG text, then the system stack from `docs/index.html`.
