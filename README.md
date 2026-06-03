# Portfolio

A personal portfolio site auto-generated from my GitHub repositories.

## Purpose

Built as a learning exercise with two goals:
1. Evaluate [Gitfolio](https://github.com/imfunniee/gitfolio) as a portfolio generator
2. Practice CI/CD by automating deployment with GitHub Actions

## Tech Stack

- **Gitfolio** — generates the site from GitHub repo data
- **GitHub Actions** — builds and deploys on every push
- **GitHub Pages** — hosts the live site

## Local Development

```bash
npm install
npm run build   # generates dist/
```

## Deployment

Pushing to `master` triggers the workflow automatically:
1. GitHub Actions builds the site
2. Deploys `dist/` to GitHub Pages

Live at: `https://aseelalomari.github.io/Gitfolio/`

## License

MIT
