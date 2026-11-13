# Board Reviewer

A review app for the Philippine engineering board exam (Math, ESAS, EE). It ships with no question bank: you add your own documents (Word, PDF, scanned pages) and it turns them into cards with spaced-repetition practice. Everything is stored on your own device.

## Put it online (about 5 minutes)

1. Create a free account at github.com, then a new repository (for example `board-reviewer`). Public is fine.
2. Upload everything in this folder, keeping the layout (`site/`, `.github/`, and these files). On GitHub, "Add file" then "Upload files" works, but make sure the hidden `.github` folder goes up too.
3. In the repository go to Settings, then Pages, and set Source to **GitHub Actions**.
4. Open the Actions tab and wait for "Deploy to GitHub Pages" to turn green.
5. Your app is at `https://YOUR-USERNAME.github.io/board-reviewer/`.

## Install it on a phone

- Android (Chrome): open the link, menu, **Install app**.
- iPhone (Safari): Share, **Add to Home Screen**.

After the first visit it also opens offline.

## Optional: Google sync between devices

Needs a one-time Google sign-in ID. Follow `HOW_TO_GOOGLE_SYNC.txt`, paste the ID into `site/config.js`, and commit.

## Updating

Edit `site/index.html` and commit. The site redeploys by itself. If phones keep an old copy, change `VERSION` in `site/sw.js`.

## Later: Android APK

The `site/` folder is already a complete installable web app, so it can be wrapped into an APK (Capacitor or Bubblewrap) and built by a GitHub Action without changing the app.

Before making the repository public, add a LICENSE file you are happy with.
