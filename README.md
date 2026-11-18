# Golf Yardage Book — Installable Web App

This folder contains your original Yardage Card & Gapping Matrix with the files needed to install it as a Progressive Web App (PWA).

## Publish it (free with GitHub Pages)

1. Sign in to GitHub and create a new **public** repository, for example `yardage-book`.
2. Upload **all contents of this folder** to the repository's root. Make sure `index.html`, `manifest.webmanifest`, `sw.js`, and the `icons` folder are at the top level.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site. The URL will look like `https://YOUR-USERNAME.github.io/yardage-book/`.

## Install on your Samsung phone

1. Open the published HTTPS URL in **Chrome** on your Galaxy Z Fold.
2. Open Chrome's ⋮ menu and choose **Install app** (or **Add to Home screen**, depending on Chrome's wording).
3. Confirm installation. Launch **Yardage Book** from your app drawer or home screen.

## Important notes

- The app's existing yardages, golfer profiles, course presets, CSV import/export, and print layout are retained.
- The app saves data in browser local storage. Use the same installed app/browser profile to keep seeing the same saved data. Clearing Chrome/site data can erase it.
- The first visit should be online so the app shell and external resources can load and be cached.
- Your original HTML loads Tailwind CSS and Google Fonts from their CDNs. The service worker makes a best effort to cache those resources after they load, but completely offline styling on a first-ever visit is not guaranteed.
- GitHub Pages is public by default. Do not put private information in the repository.
