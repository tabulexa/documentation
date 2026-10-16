# Tabulexa Board Documentation

Ready-to-deploy Jekyll **Just the Docs** site for:

- Repository: https://github.com/tabulexa/documentation
- Website: https://tabulexa.github.io/documentation/
- Privacy policy: https://tabulexa.github.io/documentation/privacy/

## Publish

1. Create a **public** GitHub repository named `documentation` under `tabulexa` (or open your existing repository).
2. Upload the **contents** of this ZIP to the repository root (do not upload just the ZIP or an enclosing folder). Include the `.github/workflows/pages.yml` workflow.
3. Commit the files to the `main` branch.
4. Go to **Settings → Pages → Build and deployment → Source → GitHub Actions**.
5. Open the **Actions** tab and allow the `Deploy documentation to GitHub Pages` workflow to finish.
6. Open https://tabulexa.github.io/documentation/ and verify each page and image.

If the GitHub account/org or repo name differs, edit `url`, `baseurl` and `aux_links` in `_config.yml` before publishing.

## Editing

- Change site title and colour scheme: `_config.yml` and `_sass/color_schemes/tabulexa.scss`.
- Change page text: `*.md` files.
- Change illustrations: `assets/images/`.
- Sidebar navigation follows the `nav_order` metadata in each page.

## Local preview (optional)

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000/documentation/`.

## Disclaimer

Screenshots in `assets/images` are promotional illustrations, not guaranteed identical to the running application. Review the privacy statement and support contact against the final published build.
