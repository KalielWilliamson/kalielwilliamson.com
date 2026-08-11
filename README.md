# Kaliel Williamson — ML Systems Engineer & Independent Researcher

Source for [Kaliel Williamson's portfolio](https://kalielwilliamson.github.io/kalielwilliamson.com/), deployed through GitHub Pages.

The site includes a detailed public research page for [*Causal Observability for Active Reinforcement Learning*](https://zenodo.org/records/21889140), with links to its artifact and DOI.

## Local development

```sh
npm install
npm run dev
```

Run `npm run build` before publishing. GitHub Actions deploys each push to `main`.

## Custom domain

The site currently uses a GitHub Pages project URL. Once the Squarespace-managed domain is available, add and verify it in the GitHub Pages settings, point its DNS records to GitHub Pages, then update `astro.config.mjs` with the custom `site` URL and remove the project `base` path.

GitHub's current DNS guidance is in [Managing a custom domain for your GitHub Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).
