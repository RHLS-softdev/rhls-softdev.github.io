# RHLS — Rex Hernández Language Services

Home hub for the RHLS software collection: language, kitchen, and
subtitle tools. Live at https://rhls-softdev.github.io/

## Products

| Product | Landing | Android APK |
|---|---|---|
| **Shikibu** — Japanese EPUB editor (furigana, vocabulary, grammar, linguistic search) | https://rhls-softdev.github.io/lingua-mundi-launch/ | [Shikibu APK](https://github.com/RHLS-softdev/lingua-mundi-launch/releases/latest) |
| **Lingua Mundi** — dictionary & linguistic data API (dashboard live; API pricing on roadmap) | https://rhls-softdev.github.io/lingua-mundi-launch/ | — |
| **Subtitle Toolkit** — SRT cleanup + Pro batch processing (in-browser, files never leave the device) | https://rhls-softdev.github.io/subtitle-toolkit-launch/ | [Subtitle Toolkit APK](https://github.com/RHLS-softdev/subtitle-toolkit-launch/releases/latest) |
| **KitchenOS** — offline-first restaurant kitchen management (free desktop + Premium) | https://rhls-softdev.github.io/kitchenos-launch/ | [KitchenOS Premium APK](https://github.com/RHLS-softdev/kitchenos-launch/releases/latest) |

## Repos

- **Sources**: `shikibu`, `lingua-mundi`, `subtitle-toolkit`, `kitchenos`
- **Launch sites (GitHub Pages)**: `lingua-mundi-launch`, `subtitle-toolkit-launch`, `kitchenos-launch`, `rhls-softdev.github.io`
- **Ops**: `lingua-mundi-ops` — deploy/audit/backup scripts + wiring guides

## Localization

The hub and all landings ship in 9 languages: English, Spanish,
Japanese, Simplified Chinese, Traditional Chinese, Cantonese, Hindi,
Arabic (RTL), and Korean. Use the language selector in the top bar.

## Commercial layer

The paid tiers (Subtitle Toolkit Pro, KitchenOS Premium, Lingua Mundi
API) run on a shared Clerk identity + per-product Convex deployments +
Stripe. The **Stripe webhook is the only path that grants paid access.**
See `lingua-mundi-ops/WIRING-GUIDE.md` for the full wiring instructions.
