# Manish Verma — Personal Portfolio

A single-page, static personal website for Manish Verma (Senior Product Manager, R&D — AI Platforms). No build step, no dependencies — just an `index.html` plus an `assets/` folder.

## 📁 Structure

```
manish-portfolio/
├── index.html      # the whole site (HTML + CSS + a little JS, self-contained)
├── render.yaml     # optional: Render Blueprint config for one-click deploy
├── .gitignore
└── assets/         # <-- put your photo, resume, and PDFs here
    ├── profile.jpg
    ├── Manish_Verma_Resume.pdf
    ├── Tech_Insights.pdf
    ├── Tech Forecast.pdf
    ├── Slime Mold.pdf
    ├── Injector.pdf
    └── Harvard Certificate.pdf
```

## ✅ Step 1 — Add your files

Copy your photo and PDFs into the `assets/` folder using these **exact names** (see `assets/_PUT_YOUR_FILES_HERE.txt`):

- `profile.jpg` — your headshot (rename the photo you uploaded to this)
- `Manish_Verma_Resume.pdf`
- `Tech_Insights.pdf`, `Tech Forecast.pdf`, `Slime Mold.pdf`, `Injector.pdf`, `Harvard Certificate.pdf`

> If `profile.jpg` is missing, the page shows an "MV" monogram automatically — it never looks broken.

## ✅ Step 2 — Push to GitHub

```bash
cd manish-portfolio
git init
git add .
git commit -m "Initial commit: personal portfolio"
git branch -M main
git remote add origin https://github.com/Manish-Verma-sys/portfolio.git   # create this repo on GitHub first
git push -u origin main
```

## ✅ Step 3 — Deploy on Render (free static site)

**Option A — Dashboard (simplest):**
1. Go to <https://dashboard.render.com> → **New +** → **Static Site**.
2. Connect your GitHub account and pick the `portfolio` repo.
3. Settings:
   - **Build Command:** *(leave empty)*
   - **Publish Directory:** `.`
4. Click **Create Static Site**. Render gives you a live URL like
   `https://portfolio-xxxx.onrender.com` — share that link with anyone.

**Option B — Blueprint (uses `render.yaml`):**
1. **New +** → **Blueprint** → select the repo. Render reads `render.yaml` and configures everything automatically.

Every `git push` to `main` auto-redeploys the site.

## 🌐 Custom domain (optional)
In the Render service → **Settings → Custom Domains**, add e.g. `manishverma.com` and follow the DNS instructions.

## ✏️ Editing content
Everything lives in `index.html`. Search for the section you want (e.g. `<!-- PATENTS -->`, `<!-- RESEARCH -->`) and edit the text directly. Colors are CSS variables at the top of the `<style>` block (`--navy`, `--blue`, etc.).
