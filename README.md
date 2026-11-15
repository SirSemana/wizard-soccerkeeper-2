# Wizard Scorekeeper 🪄

An English-language, mobile-friendly web score sheet for the classic Wizard card game.

## Features
- 3–6 players, with automatic 20/15/12/10-round tables
- Every round has a **Bid** and **Won** input per player
- Automatic points, totals, leaderboard and trick-count checks
- Automatic on-device browser persistence via `localStorage`
- JSON backup export/import
- No account, dependencies or backend required

## Scoring
- Correct prediction: **20 + 10 × tricks won** (including zero → +20)
- Incorrect prediction: **−10 × absolute difference**

## Run locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a **public** repository named `wizard-soccerkeeper-2` in your GitHub account.
2. Upload `index.html` and `README.md` to the root of the `main` branch.
3. Open **Settings → Pages → Build and deployment**, select **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Once deployed, visit `https://YOUR-USERNAME.github.io/wizard-soccerkeeper-2/`.

**Note:** Saved scores are per browser/device, not synchronized between devices. Export and import backups to transfer them.