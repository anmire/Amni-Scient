# Changelog — amni-scient.com

## v1.3.0 — 2026-03-06 — Ko-fi Support Integration

### All Pages (11 files)
- Added Ko-fi "SUPPORT" link (https://ko-fi.com/amnibro) to footer-links on every page
- Footer link styled with `.kofi-link` class (coral #ff5e5b accent)

### index.html
- Added Ko-fi "SUPPORT" button to hero CTA row alongside AMNI-CRYPT and VIEW PROJECTS
- Button styled with `.btn-kofi` class (coral outline, fills on hover)

### css/style.css
- Added `.btn-kofi` button style (coral border/text, coral fill on hover)
- Added `.kofi-link` footer accent style

### Backups
- Pre-change backups stored at backups/v_kofi/

## v1.2.0 — 2026-03-05 — App Screenshots & Graphics

### New Assets
- `assets/haven/` — 14 files: Screenshot_32-37 (phone), 10in_38-43 (tablet), FfNHy.jpg, 6Mxdg.jpg (promo)
- `assets/crypt/` — 3 files: feature_graphic.png, icon-512.jpg, amni-scient-header.jpg

### amni-haven.html
- Added `<div class="screenshots">` section before SPECIFICATIONS with horizontal-scroll phone strip (6 screenshots) and tablet strip (6 screenshots) plus dual promo images

### amni-crypt.html
- Added `<div class="screenshots">` section before SPECIFICATIONS with full-width feature graphic and icon/header promo pair

### css/style.css
- Added `.screenshots`, `.screenshot-strip`, `.screenshot-phone`, `.screenshot-tablet`, `.feature-graphic-wrap`, `.promo-pair`, `.promo-img` component styles with hover glow and mobile responsive sizing



### Verbiage Fixes (Fact-Check)
- Homepage tagline changed from "No cloud. No compromise." to "Honest disclosures per product." — both Amni-Crypt and Haven use AdMob, Play Billing, and/or FCM (all cloud services)
- Amni-Crypt hero text: removed "No cloud" claim, replaced with transparent disclosure that encryption runs locally and free tier is ad-supported
- Amni-Crypt meta description: removed "military-grade" (unaudited cipher, no certification)
- Amni-Crypt OG description: added "(ad-supported)" qualifier
- Amni-Crypt GET section: clarified "all encryption features included at every tier"
- Amni-Haven description: replaced "No third-party cloud. No message scanning." with transparent FCM/AdMob disclosure
- Amni-Haven GET section: added "(ad-supported)" qualifier
- Homepage project card for Haven: removed "Private" qualifier from description (FCM uses Google Cloud)
- Terms page title: changed from "Amni-Crypt" scoped to "AMNI-SCIENT" site-wide scope
- Privacy hub Crypt card: updated description to explicitly mention AdMob data collection

### Coloration Fixes
- Haven theme changed from #64b5f6 (light blue) to #7c5cfc (purple) — matches Haven app's actual default accent and distinguishes from Crypt's blue
- Haven SVG icon colors updated to match new purple theme
- Haven inline link colors updated from light blue to purple
- Homepage project cards now show per-app accent colors (Crypt=blue, Haven=purple, AI=amber, Core=red)
- Privacy hub Crypt card fixed from #00ff9d (default green) to #4da6ff (Crypt blue)
- Privacy hub Haven card updated to #7c5cfc (new Haven purple)

### Documentation
- README updated with full page listing and theme color table
- Backups stored at backups/v1.0.0

## v1.0.0 — 2026-03-03 — Initial Site
- Site launched with pages for Crypt, Haven, AI, Core
- Per-product privacy policies
- GitHub Pages deployment via CNAME
