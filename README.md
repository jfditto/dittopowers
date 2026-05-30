# Ditto & Powers — Website

Small static website scaffold for Ditto & Powers Planning and Investments.

## Quick start

```bash
npm run start
```

Then open `http://localhost:8080`.

If you don't want to use npm, you can run:

```bash
npx http-server -c-1 -p 8080
```

## GitHub Pages deployment

This project includes a GitHub Actions workflow at `.github/workflows/deploy.yml` that publishes the site to the `gh-pages` branch whenever `main` is pushed.

1. Create a GitHub repository for this project.
2. Set the `origin` remote to your new repo, for example:

```bash
git remote set-url origin https://github.com/<your-username>/<your-repo>.git
```

3. Push the site to GitHub:

```bash
git push -u origin main
```

4. The workflow will automatically publish the static site.

5. Visit your Pages site after the workflow completes:

- `https://<your-username>.github.io/<your-repo>/`

If you want to use a custom domain, configure it in GitHub Pages settings.

## Files

- `index.html` — home page
- `about.html`, `services.html`, `contact.html` — content pages
- `styles.css` — global styles
- `assets/` — static assets
