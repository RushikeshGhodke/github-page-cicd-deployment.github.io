# 🚀 GitHub Pages CI/CD Deployment

A minimal static website with automated deployment using GitHub Actions and GitHub Pages.

## ✨ Features

- **Static HTML Website** - Simple, fast-loading static content
- **Automated Deployment** - CI/CD pipeline with GitHub Actions
- **GitHub Pages Hosting** - Free hosting with custom domain support

## 🛠️ How it works

1. **Push to main** → GitHub Actions automatically deploys to GitHub Pages
2. **Manual deployment** → Use the "Actions" tab for manual triggers
3. **Live updates** → Changes reflect instantly on your live site

## 🚀 Quick Start

1. Fork this repository
2. Enable GitHub Pages in Settings → Pages → Source: GitHub Actions
3. Edit `index.html` and push changes
4. Your site is live at `https://yourusername.github.io/repository-name`

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions workflow
└── README.md           # You are here
```

## 🔧 Customization

- Edit `index.html` for content changes
- Modify `.github/workflows/deploy.yml` for deployment settings
- Add CSS, JS, or additional HTML files as needed

## 📝 License

MIT License - see [LICENSE](LICENSE) for details

---

Made with ❤️ by [rushikeshghodke](https://github.com/rushikeshghodke)