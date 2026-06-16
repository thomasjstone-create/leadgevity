Leadgevity — Production-ready website bundle

Instructions

1. Replace the placeholder content in `index.html` with the contents of your original HTML file's `<body>...</body>` section.
2. Move any images or assets into the `assets/` folder (create it if needed) and update paths to be relative, e.g. `assets/logo.png`.
3. Commit and push to GitHub. To publish with GitHub Pages from the `main` branch (root):

```bash
git init
git add .
git commit -m "Initial site"
# create a repo on GitHub then:
git remote add origin git@github.com:YOUR_USERNAME/REPO_NAME.git
git branch -M main
git push -u origin main
```

4. Enable GitHub Pages in repository settings: publish from `main` branch, root folder.

Notes

- External CDNs (Tailwind, Google Fonts) are used for simplicity. If you need full offline hosting, install/build Tailwind locally.
- If you want me to paste and sanitize your original HTML into `index.html`, upload the file into the workspace or let me read it directly and I'll do it for you.
