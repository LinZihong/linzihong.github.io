# Personal Website

An Astro static site for Zihong Lin, designed for GitHub Pages and a files-and-folders editing workflow.

## Edit the Site

- Edit the homepage in `src/pages/index.astro`.
- Edit the travels page in `src/pages/travels.astro`.
- Put your CV in `public/assets/cv/`.
- Put images in `public/assets/images/`.

## Local Development

Install dependencies:

```bash
npm install
```

Run the local dev server:

```bash
npm run dev
```

Build the production site:

```bash
npm run build
```

## GitHub Pages

1. Create a GitHub repository named `username.github.io`, replacing `username` with your GitHub username.
2. Push this project to the repository's `main` branch.
3. In GitHub, open the repository settings and enable Pages with GitHub Actions as the source.
4. The included workflow at `.github/workflows/deploy.yml` will build and publish the site.

For a project repository instead of `username.github.io`, update the Astro `base` setting before publishing.
