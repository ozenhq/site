# ozen site

Landing page for [ozen](https://ozenhq.com), the free private meeting copilot for macOS. Plain static HTML in `public/`,
no build step. Preview with `npx serve public`.

- Download links point at the `ozen-latest` tarball in R2, uploaded by ozen's `release.yml` on every `v*` tag.
- Deploys to Cloudflare Pages (`ozen-site`) on every push to `main`; pull requests get a preview URL.
  See [.github/workflows/deploy.yml](.github/workflows/deploy.yml).
- Product copy mirrors the [docs](https://github.com/ozenhq/docs) home page; install steps mirror its install guide.
