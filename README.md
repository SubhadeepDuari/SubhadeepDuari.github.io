# Subhadeep Duari — personal website

Static site (HTML · CSS · JavaScript). No build step, no dependencies.

## Files
- `index.html` — the whole site (styles + scripts inline)
- `profile.jpg` / `profile.webp` — portrait
- `Subhadeep_Duari_CV.pdf` — linked from the CV buttons

## Host on GitHub Pages
1. Create a repo named `<your-username>.github.io` (this gives you `https://<your-username>.github.io`).
2. Upload every file in this folder to the repo root (keep the filenames identical).
3. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / root → Save.
4. Live in ~1 minute at your Pages URL.

## Before you publish — quick edits in `index.html`
- **GitHub link:** search `data-edit="github"` → replace `https://github.com/` with your profile.
- **LinkedIn link:** search `data-edit="linkedin"` → replace `https://www.linkedin.com/` with your profile.
- **Google Scholar:** the Contact button points to a name search. Replace with your Scholar profile URL if you have one.
- **Add/edit publications:** the `PUBS = [ ... ]` array near the bottom of the file. Copy an entry, keep the same fields (`type` is `"journal"` or `"preprint"`), wrap your name as `<b>S. Duari</b>` to bold it.
