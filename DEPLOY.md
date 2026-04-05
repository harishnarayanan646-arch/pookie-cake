# 🚀 How to Push to GitHub

Follow these steps exactly to push Pookie Cakes to GitHub.

---

## Step 1 — Install Git
Download from: https://git-scm.com/downloads
Install with default settings.

---

## Step 2 — Create GitHub repo
1. Go to https://github.com/new
2. Repository name: `pookie-cakes`
3. Set to: **Public**
4. Do NOT tick "Add README" (we already have one)
5. Click **"Create repository"**
6. Copy the repo URL — looks like:
   `https://github.com/YOUR-USERNAME/pookie-cakes.git`

---

## Step 3 — Open Terminal / CMD
- Windows: Press `Win + R` → type `cmd` → Enter
- Mac: Press `Cmd + Space` → type `terminal` → Enter

---

## Step 4 — Navigate to your project folder
```bash
cd path/to/pookie-cakes
```

Example (Windows):
```bash
cd C:\Users\YourName\Downloads\pookie-cakes
```

Example (Mac):
```bash
cd ~/Downloads/pookie-cakes
```

---

## Step 5 — Run these commands ONE BY ONE

```bash
git init
```
```bash
git add .
```
```bash
git commit -m "🎂 Initial commit — Pookie Cakes v2.0"
```
```bash
git branch -M main
```
```bash
git remote add origin https://github.com/YOUR-USERNAME/pookie-cakes.git
```
```bash
git push -u origin main
```

> When asked for password — use your **Personal Access Token**, NOT your GitHub password!

---

## Step 6 — Get Personal Access Token (if needed)
1. GitHub → click your profile photo → Settings
2. Scroll to bottom → Developer Settings
3. Personal Access Tokens → Tokens (classic)
4. Generate new token → tick `repo`
5. Copy the token → paste it as your password

---

## Step 7 — Enable GitHub Pages (free hosting!)
1. Go to your repo on GitHub
2. Click **Settings** tab
3. Left sidebar → **Pages**
4. Under Branch → select `main` → folder `/ (root)`
5. Click **Save**
6. Wait 2 minutes → your site is live at:

```
https://YOUR-USERNAME.github.io/pookie-cakes/
```

---

## Updating your site later

Every time you make changes, run:
```bash
git add .
git commit -m "Updated something"
git push
```

That's it! 🎂
