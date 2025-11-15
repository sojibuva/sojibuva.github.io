# Personal Website — Md Sojib Hossain

This repository contains a simple, professional portfolio site suitable for GitHub Pages.

## Quick Start (GitHub Pages)

1. Create a GitHub repo named **sojibhossain.github.io**.
2. Upload these files (or push via git).
3. Go to **Settings → Pages → Build and deployment** and ensure Source is **Deploy from a branch**, Branch: **main** (or default).
4. The site will be live at: https://sojibhossain.github.io

## Customize

- Update text in `index.html`, `projects.html`, and `publications.html`.
- Replace `assets/Sojib_Hossain_Resume.pdf` with your latest resume.
- Add photos to `assets/` and link them in the HTML.
- Edit `style.css` to adjust theme colors and spacing.

## Optional — Custom Domain

1. Buy `sojibhossain.com` (or `.me`) from a registrar.
2. In your repo, add a file named `CNAME` containing just your domain, e.g.:

```
sojibhossain.com
```

3. At your registrar, add DNS records: **A** records pointing to GitHub Pages IPs (or use ALIAS/ANAME if supported).

## Local Preview

Open `index.html` in a browser, or use a simple server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

— Generated on 2025-11-14
