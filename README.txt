# My Week — Calendar Planner

## What changed
- Every date has its own plan and completion history.
- The first time a date is opened, it receives a copy of that weekday's starter schedule. Its tasks and checkmarks are then saved under that exact date.
- Moving to the next Monday does not reuse the previous Monday's checkmarks.
- Tasks can be added, edited, deleted and checked off. Changes save automatically.
- Calendar navigation, JSON backup/restore and a pure-tone Web Audio player are included.

## Important storage note
The planner stores data in the browser's local storage on the current device and website address. It survives closing/reopening the app, but it is not cloud-synced between devices. Export a JSON backup regularly. To copy data to another device, open the same hosted app there and use Import backup.

## Host it free with GitHub Pages
1. Extract this ZIP.
2. Sign in to GitHub and create a new repository (for example, `my-week-planner`).
3. Upload **the five files** from this folder into the repository's top/root level: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, and `icon-512.png`. Do not upload the ZIP as the only file.
4. In the repository, open **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**, select branch `main` and folder `/ (root)`, then Save.
5. Wait for GitHub Pages to publish and open the website URL shown on that Pages screen. Use that exact URL on every device.
6. On Android Chrome: open the site → browser menu ⋮ → **Install app** or **Add to Home screen**.
7. On Mac: open the same URL in a supported browser and use its install/add-to-dock option, or bookmark it.

## Local preview
You can open `index.html` directly to preview the planner, but install/offline caching requires a secure hosted address (HTTPS), such as GitHub Pages.

## Before relying on it
Tick a few test tasks, move to tomorrow and back, close/reopen the app, and verify they remain checked. Export a backup once you have entered important real data.
