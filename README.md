# personal-profiles · GitHub Pages

A bilingual (English/中文) academic profile powered by GitHub Pages and the official Minimal theme. No local build required.

## How to publish
1) Copy all files in this folder to your GitHub repository root (or use the web UI to upload files).
2) Go to Settings → Pages:
   - Source: Deploy from a branch
   - Branch: main, Folder: /(root)
3) Wait ~1–3 minutes. Your site will be available at:
   https://joseph-zheng.github.io/personal-profiles

## Customize
- Edit `index.md`, `zh/index.md`, `publications.md`, `zh/publications.md`
- Upload your CV as `/assets/cv.pdf`
- Replace the header logo by setting in `_config.yml`:
  
  logo: /assets/profile.svg
  
  then swap `assets/profile.svg` with your own image (SVG/PNG/JPG).
- If you later move this to a username site (`joseph-zheng.github.io`), set in `_config.yml`:
  
  baseurl: ""
  url: "https://joseph-zheng.github.io"

## Notes
- All links that use `{{ '/...' | relative_url }}` will prefix `baseurl` automatically, so internal links work for both project and user sites.
- You can further add pages like `/projects` or `/talks` by creating more Markdown files.

