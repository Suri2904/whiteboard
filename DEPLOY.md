# Deploy Whiteboard to GitHub Pages

## Files in this folder
- index.html   — the full app
- manifest.json — makes it installable on iPad
- sw.js         — offline support
- icon-192.png  — app icon
- icon-512.png  — app icon

---

## Step 1: Create GitHub repo

1. Go to https://github.com/new
2. Name it: whiteboard  (or anything you like)
3. Set to Public
4. Click "Create repository"

---

## Step 2: Upload files

On the new repo page, click "uploading an existing file"
Drag ALL files from this folder → click "Commit changes"

---

## Step 3: Enable GitHub Pages

1. Go to repo Settings → Pages (left sidebar)
2. Source: "Deploy from a branch"
3. Branch: main → / (root) → Save
4. Wait ~60 seconds

Your URL will be:
  https://YOUR-USERNAME.github.io/whiteboard

---

## Step 4: Install on iPad

1. Open Safari on iPad
2. Go to your GitHub Pages URL
3. Tap Share button (box with arrow)
4. Tap "Add to Home Screen"
5. Tap "Add"

Done! It opens full screen like a native app, works offline,
and saves all your notes automatically.

---

## Storage
Notes are saved in IndexedDB on your iPad.
Up to ~60% of your iPad's free disk space.
Data stays on your device — completely private.
