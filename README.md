# Nibble 🍙: cute photo food diary (web app)

An installable web app. Once it's on your home screen it opens full screen with its own icon, works offline, and keeps your meals on your phone.

## 1. Put it online (free, once)

### Option A: GitHub Pages (works from your phone)
1. On github.com, tap **+ → New repository**, name it `nibble`, set it to **Public**, and create it.
2. Tap **Add file → Upload files** and choose every file from this folder: index.html, sw.js, manifest.webmanifest, the .png icons and this README. On iPhone, unzip first in the Files app.
3. Tap **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", pick **Deploy from a branch**, then branch **main** and folder **/ (root)**, and tap **Save**.
5. After about a minute your app is at `https://YOUR-USERNAME.github.io/nibble/`.

### Option B: Netlify Drop (from a computer)
Sign up free at netlify.com, open app.netlify.com/drop, and drag this folder onto the page. You get a link like `https://something.netlify.app`.

The site only holds the app's code. Your meal photos never leave your phone.

## 2. Install it on your iPhone
1. Open your app's link in **Safari**.
2. Tap **Share** (square with an arrow), then **Add to Home Screen**, then **Add**.
3. Always open Nibble from the home-screen icon. The installed app has its own storage, separate from Safari tabs.

## 3. Keep your meals safe
Meals are stored only on your phone. Tap ⚙️ → **Save a backup** now and then and save the file to iCloud Drive or Files. On a new phone, install Nibble and use ⚙️ → **Restore from a backup**.

Deleting the home-screen app also deletes its meals, so back up first.

## Updating the app later
If you change any file, also change `VERSION` at the top of `sw.js` (for example `nibble-v2`). Then upload again. Phones pick up the new version the next time Nibble is opened while online.

## Files
| File | What it is |
|---|---|
| index.html | the whole app (screens, styles, logic) |
| sw.js | service worker: offline support and fast start |
| manifest.webmanifest | app name, icon and full-screen setting |
| *.png | app icons |
