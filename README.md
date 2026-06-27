# 🔥 Streakline — your goals, broken down

A gamified goal app (Duolingo-style streaks + XP) that breaks big goals into **milestones**, then into small **tasks** (do once) and **habits** (repeat to build a streak). Optimised to look and feel great on **iPhone X**.

## Use it as an app on your iPhone X
Once it's live (see deployment below), open the link in **Safari** on your iPhone, then:
1. Tap the **Share** button (the square with an arrow).
2. Scroll down and tap **Add to Home Screen**.
3. Name it "Streakline" and tap **Add**.

It now lives on your home screen with its own icon and opens **full-screen, no browser bars** — just like a real app. Because you'll always use that one device, your streaks and progress stay in one place.

## Does it remember my progress?
Yes — on the **same browser/device**. Data is saved in local storage and persists between visits. It does not sync across devices, and clearing Safari's website data wipes it. (Ask if you want an export/backup button.)

## How to deploy it to your personal GitHub (step by step)

**Option A — easiest, all in the browser (no tools to install):**
1. Go to github.com and sign in (create a free account if needed).
2. Click the **+** top-right → **New repository**.
3. Name it `streakline`, keep it **Public**, click **Create repository**.
4. On the new repo page, click **uploading an existing file** (or **Add file → Upload files**).
5. Drag in `index.html` (and optionally this `README.md`). Click **Commit changes**.
6. Go to **Settings** (top tab) → **Pages** (left sidebar).
7. Under **Build and deployment → Source**, choose **Deploy from a branch**.
8. Set branch to **main** and folder to **/ (root)**, click **Save**.
9. Wait ~1 minute, refresh the Pages screen. You'll see:
   **"Your site is live at https://YOUR-USERNAME.github.io/streakline/"**
10. Open that link on your iPhone and Add to Home Screen (above).

**Option B — with Git on your computer:**
```bash
# in a folder containing index.html
git init
git add index.html README.md
git commit -m "Streakline goal tracker"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/streakline.git
git push -u origin main
# then enable Pages in Settings → Pages as in steps 6–9 above
```

**Updating later:** re-upload a new `index.html` (Option A) or `git commit` + `git push` (Option B). Pages redeploys automatically in about a minute. Your saved goals on the phone are untouched by updates.

## Your plan (3 active goals + a parked "Later" tier)

**1. Get healthier & stronger at 42** 💪 — ~12 weeks
Swim 2×/wk + 2 short strength sessions + daily walk · cut sugar/processed food · lights-out by 10:30 with a Calm wind-down · weekly weigh-in.

**2. Become an Azure Solutions Architect** ☁️ — AZ-104 first (~3 months), AZ-305 after
You can't earn the Architect credential without AZ-104 first, so it's sequenced inside one goal: Learn path + weekly labs → official practice exams from ~week 7 → 80%+ before booking → pass, then AZ-305.

**3. White paper: SDLC in an AI world** ✍️ — ~13 weeks
Landscape → thesis & outline → research + 250-words/day draft → revise & ship.

**Later tier (parked):** Learn AI + Claude Certified Architect · Quran (10 min/day) · Reading. Reminders are off; open one and switch its habit reminder on when you're ready to start.

## Reminders
Core daily habits remind you on **weekdays** at sensible times (change any of them by opening the habit). On iPhone, the first time a reminder is due you'll get a permission prompt — tap **Allow**. Reminders fire while the app is open.

## Tip
Don't start all habits at once. Pick the 2–3 that matter most this week, let them become automatic, then layer in the rest. Missing one day doesn't break a goal — just don't miss twice.
