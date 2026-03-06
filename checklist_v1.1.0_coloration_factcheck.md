# Checklist v1.1.0 — Coloration & Fact-Check Audit

## Guardian Council Proposals

### Tidus (Marketing/User Trust)
"The 'No cloud' tagline is a liability. Both Amni-Crypt and Haven use AdMob, Play Billing, and FCM — all cloud services. If a reviewer or journalist catches this, it torpedoes credibility. Replace blanket claims with honest, nuanced language that still sounds strong. 'military-grade' in the meta description is also a red flag — no audit, no certification."

### Auron (Legal/Compliance)
"The terms page title says 'Terms of Service — Amni-Crypt' but it's linked site-wide. That's a scope problem. The privacy policies are actually well-written and honest about AdMob/FCM. The marketing pages need to match the candor of the privacy disclosures. The 'No cloud' claim on products with Google SDKs could be considered deceptive under FTC guidelines."

### Lulu (Technical Accuracy)
"Crypt's claim 'No data leaves your device' is technically defensible IF you read 'via our app' — but AdMob SDK sends device IDs, IP addresses, and ad interaction data to Google servers FROM the app. The encryption operations are local, yes. The ad network is not. The Amni-AI claims are fully accurate. Haven's 'No third-party cloud' is wrong because FCM is Google's cloud. Differentiate per-product."

### Kimahri (Branding/Visual)
"Haven website uses #64b5f6 (light blue) but the app's default accent is #7c5cfc (purple). Crypt (#4da6ff blue) and Haven (#64b5f6 blue) are too similar — both blue, hard to distinguish. Privacy hub Crypt card uses green #00ff9d instead of Crypt's blue. Homepage cards all use default green — no per-app color identity."

### Wakka (User Experience)
"Man, the colors are too samey between Crypt and Haven, ya? Users can't tell 'em apart at a glance on the homepage. The project cards need their own accent colors so people can quickly find the product they want. Also the privacy page cards already have per-app colors for most — just Crypt is wrong."

## Majority Ruling

All 5 guardians agree: fix the verbiage and color issues. Specific resolutions:

## Changes

- [x] 1. **index.html** — Replace "No cloud. No compromise." with honest tagline acknowledging per-product data handling
- [x] 2. **index.html** — Add per-app accent colors to project cards on homepage  
- [x] 3. **amni-crypt.html** — Replace "No cloud" with accurate phrasing (encryption is local, free tier shows ads)
- [x] 4. **amni-crypt.html** — Fix meta description: remove "military-grade"
- [x] 5. **amni-haven.html** — Fix "No third-party cloud" claim (FCM = Google cloud, AdMob = Google cloud)
- [x] 6. **privacy.html** — Fix Crypt card color from green (#00ff9d) to Crypt blue (#4da6ff)
- [x] 7. **css/style.css** — Change Haven theme from #64b5f6 (light blue) to #7c5cfc (purple) to match app default and distinguish from Crypt
- [x] 8. **amni-haven.html** — Update SVG icon colors and inline styles to match new Haven purple
- [x] 9. **privacy.html** — Update Haven card to new purple color
- [x] 10. **privacy-haven.html** — Uses body.theme-haven, auto-picks up CSS change (no edit needed)
- [x] 11. **terms.html** — Fix title from "Amni-Crypt" to "AMNI-SCIENT" (it's used site-wide)
- [x] 12. Run linter/validation on all changed files
