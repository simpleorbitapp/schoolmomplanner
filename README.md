# School Mom Planner Privacy Policy — staging package

This folder contains the bilingual public Privacy Policy draft for School Mom Planner by SimpleOrbit. It is a review artifact only and has not been published.

## Contents

- `index.html` — one semantic, bilingual Bahasa Indonesia/English page
- `styles.css` — responsive styling using system fonts
- `README.md` — review and future hosting notes

There is no build step, framework, JavaScript, analytics, advertising, form, external font, or app-owned cookie.

## Source baseline

The policy was drafted against the Android release implementation at commit:

`65def77382ccdcca67458a69ceb5cd907d3d42fd`

It should be rechecked if data handling, advertising, consent, notifications, backup behavior, or deletion behavior changes.

## Local review

Open `index.html` directly in a browser, or serve this directory locally:

```sh
python3 -m http.server 8765 --bind 127.0.0.1 --directory /Users/angga/Documents/SimpleOrbit/SchoolMomPlannerAndroidRelease/privacy-policy-staging
```

Then visit `http://127.0.0.1:8765/`.

## Recommended hosting after approval

GitHub Pages is a suitable minimal option because these files are static and require no server-side processing. No repository or Pages site was created during Phase 34A.

URL structure templates only (they do not claim a live site exists):

- `https://<owner>.github.io/<privacy-site>/`
- `https://<owner>.github.io/<privacy-site>/school-mom-planner/`

Before using a URL in Google Play:

1. Complete product/legal review of both languages.
2. Choose the final public repository/site and stable path.
3. Publish the static files and enable/enforce HTTPS.
4. Verify the page is public, browser-readable, and requires no login.
5. Check all links and both language anchors from a signed-out browser.
6. Update the app's public-policy link and Google Play listing in a separately approved phase.

## Status

- Effective date in draft: October 19, 2026
- Published: no
- Committed: no
- Production AdMob credentials: not included
