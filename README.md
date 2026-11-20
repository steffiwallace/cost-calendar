# CostTracker – the cost tracking calendar

A working prototype that runs as a home-screen app on iPhone. It's hosted with GitHub Pages.

## What's in this folder

| File | What it is |
| --- | --- |
| `index.html` | The whole app |
| `support.js` | The engine that runs the app's screens |
| `manifest.webmanifest` | Tells phones the app's name, colours and icon |
| `icons/` | The app icon (`apple-touch-icon.png` is the one iPhone uses) |

## Updating the live app

1. Open the repository on github.com.
2. **Add file → Upload files**, then drag in everything from this folder, including the `icons` folder.
3. Commit the changes. GitHub replaces files that have the same name.
4. Wait a minute or two for GitHub Pages to update. The **Actions** tab shows a green tick when it's live.

First time only: **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**. The address appears at the top of that page.

## Putting it on an iPhone

1. Open the GitHub Pages address in **Safari**.
2. Tap **Share → Add to Home Screen → Add**.
3. Open it from the home screen icon.

To see a new icon after an update, delete the home screen icon (your data stays) and add it again.

## Good to know

- Each phone keeps its own data. You and your partner each have your own plans and spending; nothing is shared between you.
- Data is saved on the phone as you go. Clearing Safari's website data will erase it.
- Always open it from the home screen icon. A Safari tab keeps separate data from the home screen app.
