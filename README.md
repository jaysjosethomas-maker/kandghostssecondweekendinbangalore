# KandGhostsweekendsinBangalore.com 👻✨

> **Weekend 02 // Classified Dossier Experience**  
> An interactive cinematic dossier created for K and Ghost's Weekend in Bangalore.

---

## 🚀 How to Deploy on GitHub Pages (Free Hosting)

1. **Create a new GitHub Repository:**
   - Go to [github.com/new](https://github.com/new).
   - Repository name: `KandGhostsweekendsinBangalore` (or any name you prefer).
   - Visibility: **Public** (required for free GitHub Pages) or **Private** (if you have GitHub Pro).
   - Do **NOT** initialize with README, .gitignore, or license (we already have them).

2. **Upload & Push:**
   - **Option A (Via Git Terminal):**
     ```bash
     cd KandGhostsweekendsinBangalore
     git init
     git add .
     git commit -m "Initial commit: Weekend 02 Dossier"
     git branch -M main
     git remote add origin https://github.com/<YOUR-USERNAME>/<REPO-NAME>.git
     git push -u origin main
     ```
   - **Option B (Via GitHub Web Upload):**
     - On your newly created repo page, click **"uploading an existing file"**.
     - Drag and drop all files from this folder and click **Commit changes**.

3. **Enable GitHub Pages:**
   - In your repo, go to **Settings** → **Pages** (in the left sidebar).
   - Under **Build and deployment** → **Branch**, select `main` branch and `/ (root)`.
   - Click **Save**.
   - In 1–2 minutes, your site will be live at:  
     `https://<YOUR-USERNAME>.github.io/<REPO-NAME>/`

---

## 📁 Repository Structure
- `index.html` — The complete interactive single-page app (Tailwind, Lucide icons, sound engine, HUD, canvas animations, and Web3Forms email notifications).
- `Barney/` — Barnabas Barney cat photos.
- `Giphs/` — Topic animations and situational GIFs.
- `KALYANI - ARJN x KDS x FIFTY4 x RONN  What We Cookin - What We Cookin.mp3` — Background soundtrack.
- `.nojekyll` — Ensures GitHub Pages serves all assets and subfolders directly without Jekyll filtering.
- `.gitignore` — Ignores OS junk files (.DS_Store).
