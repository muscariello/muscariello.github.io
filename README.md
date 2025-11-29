# Personal Website

My personal website built with [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## 🌐 Live Site

Visit: [muscariello.github.io](https://muscariello.github.io)

## 📁 Structure

```
├── mkdocs.yml          # MkDocs configuration
├── docs/
│   ├── index.md        # Home page / Bio
│   ├── projects.md     # Ongoing projects
│   ├── students.md     # PhD students
│   ├── publications.md # Publications list
│   └── patents.md      # Patents
├── requirements.txt    # Python dependencies
└── .github/workflows/  # GitHub Actions for deployment
```

## 🚀 Setup Instructions

### Local Development

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run local server:
   ```bash
   mkdocs serve
   ```

3. Open http://127.0.0.1:8000 in your browser

### Deploy to GitHub Pages

1. **Rename this repository** to `muscariello.github.io` on GitHub:
   - Go to repository Settings → General
   - Change repository name to `muscariello.github.io`

2. **Enable GitHub Pages with Actions**:
   - Go to repository Settings → Pages
   - Under "Build and deployment", select `GitHub Actions` as the source

3. **Push your changes**:
   ```bash
   git add -A
   git commit -m "Setup MkDocs site"
   git push
   ```

The GitHub Action will automatically build and deploy your site!

## ✏️ Editing Content

All content is in Markdown files under the `docs/` folder. Simply edit the `.md` files and push to deploy.