# Board Reviewer

A review app for the Philippine engineering board exam (Math, ESAS, EE). It ships with no question bank: you add your own documents (Word, PDF, scanned pages) and it turns them into cards with spaced-repetition practice. Everything is stored on your own device.

## Hosting

GitHub Pages serves this repository directly: Settings, Pages, Source "Deploy from a branch", branch `main`, folder `/ (root)`. The app is then at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Install on a phone

- Android (Chrome): open the link, menu, **Install app**.
- iPhone (Safari): Share, **Add to Home Screen**.

After the first visit it also opens offline.

## Optional: Google sync between devices

Follow `HOW_TO_GOOGLE_SYNC.txt`, paste the ID into `config.js`, and commit.

## Updating

Upload a new `index.html` (Add file, Upload files). If phones keep an old copy, change `VERSION` in `sw.js`.

## Later: Android APK

This repository is already an installable web app, so it can be wrapped into an APK without changing the app.

Before sharing widely, add a LICENSE file you are happy with.
