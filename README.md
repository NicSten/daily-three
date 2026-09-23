# Daily Three — setup on Android

Everything saves on your phone. No account, no server, works offline after the first open.

## 1. Put it on GitHub Pages (free, ~10 min)
1. Sign in at github.com and click **New repository**. Name it `daily-three`, set it to **Public**, check **Add a README**, create.
2. Click **Add file → Upload files**. Drag in every file from this folder (index.html, manifest.json, sw.js, and the four icon PNGs). Click **Commit changes**.
3. Go to **Settings → Pages**. Under *Branch*, pick `main` and `/ (root)`, then **Save**.
4. Wait a minute or two. The page shows your link: `https://YOUR-USERNAME.github.io/daily-three/`

## 2. Install on your phone
1. Open that link in **Chrome** on your Android.
2. Tap **⋮ → Install app** (or **Add to Home screen**).
3. Open it from the new ⚡ icon. It runs full-screen and works with no signal.

## Using it
- **Edit task lists** at the bottom: switch between Morning / Evening small / Evening big, rename or reorder categories, add or delete tasks. Changes save as you go.
- **Backup:** tap *Save backup* every week or two. It downloads a .json file you can restore on a new phone.

## Updating later
Edit `index.html`, upload it to the repo again, and change `daily-three-v1` to `daily-three-v2` in `sw.js` (upload that too). Close and reopen the app twice to pick up the new version. Your data isn't touched.

Note: uninstalling the app or clearing Chrome's site data erases your history, so keep a backup.
