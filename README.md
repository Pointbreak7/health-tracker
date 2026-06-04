# Project Trinity — Health Tracker
### Deploy to GitHub Pages in 5 steps

---

## Files in this package
- `index.html` — The full app (PIN lock + tracker)
- `manifest.json` — Makes it installable as a PWA
- `icon-192.png` — App icon (home screen)
- `icon-512.png` — App icon (splash screen)
- `README.md` — This file

---

## Step-by-step deployment

### Step 1 — Create a GitHub account
Go to https://github.com and sign up (free). Pick any username.

### Step 2 — Create a new repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `health-tracker` (or anything you like)
3. Set it to **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

### Step 3 — Upload the files
1. Inside your new repo, click **Add file** → **Upload files**
2. Drag and drop ALL 4 files:
   - `index.html`
   - `manifest.json`
   - `icon-192.png`
   - `icon-512.png`
3. Scroll down, click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Click **Settings** (tab at the top of your repo)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**
6. Wait ~60 seconds, then your URL appears:
   `https://YOUR-USERNAME.github.io/health-tracker`

### Step 5 — Install on your phone
1. Open the URL in **Chrome** (Android) or **Safari** (iPhone)
2. Android: tap the 3-dot menu → **Add to Home screen**
3. iPhone: tap the Share button → **Add to Home Screen**
4. The app icon appears on your home screen like a native app!

---

## First time opening
- The app will ask you to **create a 4-digit PIN**
- Enter it twice to confirm
- From then on, the PIN is required every time

## Your data
- All data is stored **locally on your device only**
- Nobody else can see it (not even GitHub)
- Even if someone opens your URL, they see a blank app — your data never leaves your phone

---

## Changing your PIN
Settings tab → Change PIN

## If you forget your PIN
Open the app URL in browser → Open DevTools (F12) → Console → type:
`localStorage.removeItem('trinity_pin')` and press Enter → refresh

---

Built for the 100 → 95 kg mission. Good luck, boss.
