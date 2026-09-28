# ozen site

Landing page for [ozen](https://ozenhq.com), the free private meeting copilot for macOS. Plain static HTML in `public/`,
no build step. Preview with `npx serve public`.

- Download links (in `download/`) point at the `ozen-latest` tarball in R2, uploaded by ozen's `release.yml` on every `v*` tag.
- Deploys to the `ozen-site` Cloudflare Worker (static assets, `wrangler.jsonc`) on every push to `main`; pull requests get a preview URL.
  See [.github/workflows/deploy.yml](.github/workflows/deploy.yml).
- `download/` owns the download and install steps, one section per platform; the docs install page links here.
- Product copy mirrors the [docs](https://github.com/ozenhq/docs) home page.
