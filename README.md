# Tabulexa Board documentation — Minimal Mistakes

Four-page documentation site for https://github.com/tabulexa/documentation.

## Local preview (Windows)

This site uses **Minimal Mistakes** and Jekyll. Ruby **3.3** is recommended for local development. Your existing Ruby 4.0 installation may have compatibility issues with older Jekyll plugins.

```powershell
bundle install
bundle exec jekyll serve --baseurl ""
```

Open http://localhost:4000/.

## Publishing

Upload the **contents** of this folder to the root of `tabulexa/documentation` on branch `main` (including `.github/workflows/pages.yml`). In repository **Settings → Pages**, choose **GitHub Actions**. The workflow builds Jekyll and publishes to https://tabulexa.github.io/documentation/.

## Editing

- `index.md` — Motivation
- `usage.md` — Usage
- `faq.md` — FAQ
- `privacy.md` — Privacy
- `_data/navigation.yml` — navigation menu
- `_config.yml` — theme and site settings

This project uses Minimal Mistakes remotely; copyright and licence remain with the respective theme authors. See https://github.com/mmistakes/minimal-mistakes/blob/master/LICENSE.

Review the privacy policy and product claims against the actual release before publishing.
