# Back on Court

A home-screen app for ankle rehab, training and food planning on the way back to squash.
All data stays on the phone. Nothing is sent anywhere.

## Put it online with GitHub Pages

1. Sign in at github.com (a free account is enough).
2. Go to github.com/new. Name the repository `back-on-court`, set it to **Public**, and click **Create repository**.
3. On the next page click **uploading an existing file**. Drag in everything from this folder: `index.html`, `manifest.json`, `sw.js`, `README.md` and the `icons` folder. Click **Commit changes**.
4. Open **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and click **Save**.
5. Wait one or two minutes. The app is at `https://YOUR-USERNAME.github.io/back-on-court/`.

## Install on iPhone

Open that link in **Safari**, tap **Share**, then **Add to Home Screen**.

## Updating the app

Upload the changed files to the repository again. In `sw.js`, change `VERSION` (for example `boc-v2`) so phones pick up the new version. Close the app fully and reopen it, sometimes twice.
