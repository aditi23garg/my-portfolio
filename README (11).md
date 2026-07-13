# Aditi Garg — Portfolio

Live portfolio site — AI Engineer specializing in RAG, Agentic AI, and Applied ML.

## Files
- `index.html` — the entire site (structure + styling + interactivity, no build step needed)
- `Aditi-Garg-Resume.pdf` — downloadable résumé, linked from the nav and hero buttons

## Deploy this repo on Vercel

1. Push this repo to GitHub (see steps below if you haven't yet)
2. Go to [vercel.com](https://vercel.com) → **Add New → Project → Import Git Repository**
3. Select this repo
4. Framework preset: **Other** (it's a static site — no build command needed)
5. Click **Deploy**

You'll get a live URL like `your-project-name.vercel.app` within a minute.

## Making updates later

1. Ask Claude for the change → get the updated `index.html`
2. Replace the old `index.html` in this repo (GitHub web UI: click the file → edit/upload → commit)
3. Vercel auto-detects the push and redeploys automatically — no manual redeploy step needed

## First-time GitHub setup (if this repo doesn't exist yet)

**Via GitHub web UI (no terminal needed):**
1. Go to github.com → **New repository** → name it (e.g. `portfolio`) → Create
2. Click **uploading an existing file** → drag in `index.html` and `Aditi-Garg-Resume.pdf` → Commit

**Via terminal:**
```bash
git init
git add index.html Aditi-Garg-Resume.pdf README.md
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/aditi23garg/portfolio.git
git push -u origin main
```

Then connect the repo to Vercel as described above.

## Optional: custom domain

Once deployed, you can attach a custom domain (if you own one) under
**Vercel Project → Settings → Domains**. The free `*.vercel.app` subdomain works fine without one.
