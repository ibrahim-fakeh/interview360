360-Day Interview Preparation - iPhone app (installable web app)

Files: index.html, manifest.webmanifest, sw.js, icons/. Keep them together.

PUBLISH (one time, free) - GitHub Pages:
 1. Sign in at github.com (free account) -> New repository -> name it e.g. interview360 -> Public -> Create.
 2. On the repo page click "uploading an existing file", drag in ALL files and the icons folder, Commit.
 3. Settings -> Pages -> Source: "Deploy from a branch" -> Branch: main, folder: / (root) -> Save.
 4. After ~1 minute your app is at https://<your-username>.github.io/interview360/

Alternative: Netlify Drop (app.netlify.com/drop) or Cloudflare Pages - drag this folder in.

INSTALL ON IPHONE:
 1. Open the https link in Safari (must be Safari).
 2. Tap Share -> "Add to Home Screen" -> Add.
 3. Open "Interview 360" from the home screen. It works offline after the first open.

YOUR DATA:
 Progress is stored on the phone only. Use More -> Backup & content -> Export progress
 (opens the iOS share sheet: choose "Save to Files"). Import the same file in the desktop
 workbook to continue there, or vice versa.

UPDATES:
 When new 14-day content batches arrive, either import the JSON in the app (Backup & content),
 or replace index.html in the repository; the app picks up the new version on next open.
