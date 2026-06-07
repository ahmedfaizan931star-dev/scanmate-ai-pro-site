# ScanMate AI Pro Website + Policy Pages

This folder contains a complete static website for **ScanMate AI Pro**:

- `index.html` — landing page
- `privacy.html` — Privacy Policy for Google Play Console
- `terms.html` — Terms of Service
- `support.html` — support/contact page
- `data-safety.html` — plain-language Data Safety Summary
- `delete-data.html` — local data deletion instructions
- `robots.txt`, `sitemap.xml`, `.nojekyll` — GitHub Pages support files

## Important honesty note

The Privacy Policy is written for the app behavior currently described/inspected:

- offline-first document scanner
- no required login/account for core features
- no required cloud sync/backend for core features
- CameraX scanning
- ML Kit OCR/barcode
- local Room/DataStore/app files
- optional Gemini AI using a user-provided API key
- biometric/device protection features where supported

If you add ads, analytics, Firebase, crash reporting, cloud sync, login, payments, subscriptions, or developer-hosted accounts later, update the Privacy Policy, Data Safety page, and Google Play Console before publishing that version.

## Deploy on GitHub Pages

### Option A — New website repo

Recommended repo name:

```text
scanmate-ai-pro-site
```

1. Create a new **public** GitHub repository named `scanmate-ai-pro-site`.
2. Upload all files from this folder into the repository root.
3. Commit and push.
4. Go to **Settings → Pages**.
5. Set:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. Wait 1–10 minutes.
8. Open the generated GitHub Pages URL.

Expected URLs:

```text
https://ahmedfaizan931star-dev.github.io/scanmate-ai-pro-site/
https://ahmedfaizan931star-dev.github.io/scanmate-ai-pro-site/privacy.html
https://ahmedfaizan931star-dev.github.io/scanmate-ai-pro-site/terms.html
https://ahmedfaizan931star-dev.github.io/scanmate-ai-pro-site/support.html
https://ahmedfaizan931star-dev.github.io/scanmate-ai-pro-site/data-safety.html
https://ahmedfaizan931star-dev.github.io/scanmate-ai-pro-site/delete-data.html
```

### Option B — Push from Codespaces terminal

After creating/opening the `scanmate-ai-pro-site` repo in Codespaces, upload/extract this ZIP, then run:

```bash
git add -A
git commit -m "Add ScanMate AI Pro website and policy pages"
git push origin main
```

Then enable Pages from **Settings → Pages**.

## What to paste in Google Play Console

Use this as the Privacy Policy URL:

```text
https://ahmedfaizan931star-dev.github.io/scanmate-ai-pro-site/privacy.html
```

Use this as the website/support URL if asked:

```text
https://ahmedfaizan931star-dev.github.io/scanmate-ai-pro-site/support.html
```

## Before submitting to Play Console

Open these pages in an incognito/private tab:

- Home page loads
- Privacy Policy loads
- Terms load
- Support page loads
- Data Safety page loads
- Delete Local Data page loads

The Privacy Policy must be active, public, HTML-based, non-geofenced, and not a PDF.
