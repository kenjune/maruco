# maruco

A simple static website automatically deployed via GitHub Actions.

## 🚀 Live Demo

Visit the live site at: `https://kenjune.github.io/maruco/`

## 📦 Automatic Deployment

This site is automatically deployed to GitHub Pages whenever changes are pushed to the `main` or `master` branch.

### Setup Instructions

To enable GitHub Pages for this repository:

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Build and deployment", select:
   - **Source**: GitHub Actions

That's it! The GitHub Actions workflow (`.github/workflows/deploy.yml`) will automatically deploy your site on every push.

## 📂 Content

- **index.html**: Landing page with auto-redirect to the skill UI
- **skill_ui.html**: Interactive Japanese skill configuration interface (スキル設定UI)

## 🛠️ Local Development

Simply open `index.html` or `skill_ui.html` in your web browser to view the site locally.

## 📝 Making Changes

1. Edit `index.html` or `skill_ui.html` to customize the content
2. Commit and push your changes
3. GitHub Actions will automatically deploy the updated site

## 🌟 Features

- ✅ Automatic deployment with GitHub Actions
- ✅ Interactive skill configuration UI (スキル設定UI)
- ✅ Static HTML pages with modern design
- ✅ Responsive layout
- ✅ Fast and lightweight
- ✅ Bilingual support (English/Japanese)