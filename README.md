# Yashitaa Arya — Portfolio

A single-page portfolio site. Plain HTML/CSS/JS — no build step, no dependencies.

## Files

- `index.html` — page content and structure
- `style.css` — design system and styling
- `script.js` — mobile nav, scroll reveal animation, constellation canvas
- `resume.pdf` — **you need to add this yourself** (see below)

## Before deploying

1. Drop your actual résumé PDF into this folder and name it exactly `resume.pdf` — the "Download Résumé" buttons already link to it.
2. Add project screenshots into the `images/` folder using these **exact filenames** — the cards are already wired to them and will pick them up automatically, no code changes needed:
   - `images/talentflow-dashboard.png`
   - `images/rbac-admin-panel.png`
   - `images/mantis-rviz.png`
   - `images/intellicardiac-prediction-ui.png`
   Until an image exists at that path, the card shows a placeholder box with the filename it's expecting — that's expected behavior, not a bug.
3. Open `index.html` directly in your browser to preview locally before pushing anything.

## Deploying to Vercel

1. Push this folder as a new GitHub repository (e.g. `yashitaa-portfolio`).
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub.
3. Click **Add New → Project**, select your new repo.
4. Framework preset: choose **Other** (this is a static site, no build step needed).
5. Leave build settings blank and click **Deploy**.
6. Vercel will give you a live URL (e.g. `yashitaa-portfolio.vercel.app`) — you can add a custom domain later from the project settings if you want.

Any time you push a change to the repo, Vercel redeploys automatically.