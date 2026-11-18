# Golf Yardage Book — Installable Web App

## Install on your phone

1. Open the published HTTPS URL in **Chrome** on your Galaxy Z Fold.
2. Open Chrome's ⋮ menu and choose **Install app** (or **Add to Home screen**, depending on Chrome's wording).
3. Confirm installation. Launch **Yardage Book** from your app drawer or home screen.

## Important notes

- The app's existing yardages, golfer profiles, course presets, CSV import/export, and print layout are retained.
- The app saves data in browser local storage. Use the same installed app/browser profile to keep seeing the same saved data. Clearing Chrome/site data can erase it.
- The first visit should be online so the app shell and external resources can load and be cached.
- Your original HTML loads Tailwind CSS and Google Fonts from their CDNs. The service worker makes a best effort to cache those resources after they load, but completely offline styling on a first-ever visit is not guaranteed.
