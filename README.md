# Benouaer Technology Consulting website

Built with [Astro](https://astro.build). Deployed to GitHub Pages by `.github/workflows/deploy.yml` on every push to `master`.

## Development
```
npm install
npm run dev      # http://localhost:4321
npm run build    # outputs to dist/
```

## Editing content
- Page sections: `src/components/*.astro`
- Site name, email, LinkedIn URL, navigation: `src/config.ts`
- Styles and colours: `src/styles/global.css`
- Images: `public/img/`

## Publishing a blog post
Add a Markdown file to `src/content/blog/`, for example `my-post.md`:
```
---
title: My first post
description: One-line summary.
date: 2026-10-08
---
Post content here.
```
Set `draft: true` in the front matter to hide a post.

## Deployment setup
In the repository settings, go to Pages and set Source to **GitHub Actions** (one-time).

Released under the [MIT](LICENSE) licence.
