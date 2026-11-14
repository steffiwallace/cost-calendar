# Cost Calendar

A calendar and cost tracker that runs in Safari and installs on your iPhone home screen. Everything is saved on the device and it works offline.

## Put it on GitHub Pages

1. On github.com, click **New repository**, name it `cost-calendar`, set it to **Public** and create it.
2. On the empty repository page, click **uploading an existing file**. Drag in **everything inside this folder**: `index.html`, `app.js`, `sw.js`, `manifest.webmanifest`, `.nojekyll`, `README.md` and the `icons` folder. Then click **Commit changes**.
   - On a Mac, `.nojekyll` is hidden. Press Cmd+Shift+. in Finder to show it. The site still works without it.
3. Go to **Settings › Pages**. Under *Build and deployment*, choose **Deploy from a branch**, pick **main** and **/ (root)**, then click **Save**.
4. After a minute or two, the site is live at `https://YOUR-USERNAME.github.io/cost-calendar/`.

## Add it to your iPhone

1. Open the link in **Safari**.
2. Tap **Share › Add to Home Screen**. If you see an **Open as Web App** switch, leave it on. Then tap **Add**.
3. Always open it from the home-screen icon. The home-screen app keeps its own storage, separate from Safari tabs.

## Your data

- Events and settings save automatically on the phone. Nothing goes to a server.
- Deleting the home-screen icon deletes its data. Use **Settings › Backup and restore › Export a backup** now and then, and choose **Save to Files** to keep the copy in iCloud Drive.
- To move to a new phone, or to recover, use **Restore from a backup** and pick that file.

## Updating the app

Upload the new files over the old ones in the repository. GitHub Pages republishes in a minute or two. The next time you open the app with a connection, it picks up the new version. Close the app and reopen it if you don't see the change.

## What's not live yet

- **Reminders** are saved with events, but they won't send notifications. A web app needs a push server for that.
- **Calendar sync**, **Shared itinerary** and **Send feedback** are still design mockups.
- Attachments store the file's name and size, not the file itself.
