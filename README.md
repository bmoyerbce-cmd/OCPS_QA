# QA Scorecard

A static, interactive HTML QA scorecard with YES/NO dropdowns, automatic scoring, autofail status, reviewer comments, and print/save-to-PDF support.

## Files

- `index.html` - Main scorecard page.
- `.github/workflows/pages.yml` - Optional GitHub Pages deployment workflow.
- `.gitignore` - Common files to exclude from Git.
- `LICENSE` - Basic license placeholder.

## Run locally

Open `index.html` in any modern web browser.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository.
3. In GitHub, go to **Settings > Pages**.
4. Under **Build and deployment**, choose **GitHub Actions**.
5. Push to the `main` branch. The included workflow will publish the site.

Your live site will usually be available at:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

## Notes

This project does not require Node.js, npm, React, or any build step. It is plain HTML, CSS, and JavaScript.
