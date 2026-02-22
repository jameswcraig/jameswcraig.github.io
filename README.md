# jameswcraig.github.io (Hugo source)

This repository contains the **Hugo source** for `jameswcraig.github.io`.

- **Source**: lives in this repo (Hugo content + layouts + assets)
- **Deployment**: handled by **GitHub Actions → GitHub Pages** (no built files committed)
- **Legacy**: the prior generated site output was moved to `legacy-output/` for reference

## Local development

Install Hugo:

```bash
brew install hugo
```

Run locally:

```bash
hugo server -D
```

Build:

```bash
hugo --minify
```

## GitHub Pages setup (one-time)

In GitHub:

- Go to **Settings → Pages**
- Under **Build and deployment**, set **Source** to **GitHub Actions**

After that, pushes to `master` will automatically deploy.


