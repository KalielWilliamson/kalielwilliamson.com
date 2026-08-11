# Kaliel Williamson — Research Engineer

The source for the personal research-engineering portfolio at the future custom domain.

## Local development

```sh
npm install
npm run dev
```

Use `npm run build` to make a production build. GitHub Actions deploys the site to GitHub Pages after each push to `main`.

## Content to personalize

Update the `links` object at the top of `src/pages/index.astro` with the published Zenodo record, LinkedIn profile, ORCID, and CV path. Put the CV PDF in `public/`.

## Connecting the custom domain

1. In GitHub repository settings, enable Pages with **GitHub Actions** as the source.
2. Add and verify the selected custom domain in the Pages settings before changing DNS.
3. In Squarespace Domains, point the apex and `www` records to GitHub Pages, then enable HTTPS in GitHub.
4. Update `astro.config.mjs` to use `site: 'https://your-domain.example'` and remove `base`.

GitHub's current DNS guidance is available in [Managing a custom domain for your GitHub Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).
