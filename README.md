# Sprig — Clean Food Scanner

A web app that scores packaged food from 0–100 on how processed it is, explains every deduction, suggests cleaner alternatives from the same aisle, and warns about ingredients on your personal intolerance list.

**Live:** https://jellybeanjehmii.github.io/Sprig/

## Features
- Barcode scanning: live camera, barcode photo, or manual entry
- Product data from [Open Food Facts](https://world.openfoodfacts.org)
- Transparent scoring: NOVA processing level, additives (rated by concern), refined seed oils, added sugars, ultra-processing markers, ingredient count, category-level contaminant risks
- Cleaner alternatives from the same category, filterable by country
- Ingredients-label photo fallback (on-device OCR) or pasted ingredients
- Intolerance profile: 13 allergens plus FODMAP, histamine, caffeine, sweeteners, nightshades and corn, with "contains" / "may contain" warnings
- Scan history stored on the device

Everything is one self-contained `index.html` with no build step. Pushing to `main` redeploys via GitHub Actions.

*General information only, not medical advice. Always check the pack if you have a serious allergy.*
