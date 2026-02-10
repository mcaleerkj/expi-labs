# Expi Labs — Public Docs

Public-facing policy and support documents for Expi Labs apps. Hosted via GitHub Pages.

## Structure

```
config.json              — Source-of-truth for app names, slugs, and data practices
docs/
  index.html             — Expi Labs landing page
  assets/styles.css      — Shared stylesheet
  app/
    pr-gems/             — PR Gems app docs
      index.html         — App hub page
      privacy-policy     — .md + .html
      terms-of-service   — .md + .html
      support            — .md + .html
      data-deletion      — .md + .html
      child-safety       — .md + .html
      security           — .md + .html
      changelog.md       — Documentation changelog
```

## Publishing with GitHub Pages

1. Go to **Settings > Pages** in this repository.
2. Set **Source** to "Deploy from a branch".
3. Set **Branch** to `main` and **Folder** to `/docs`.
4. Save. GitHub will publish the site at `https://<username>.github.io/expi-labs/`.

## Public URLs (once Pages is enabled)

| Document        | URL                                                                |
| --------------- | ------------------------------------------------------------------ |
| Privacy Policy  | `https://<username>.github.io/expi-labs/app/pr-gems/privacy-policy.html` |
| Terms of Service| `https://<username>.github.io/expi-labs/app/pr-gems/terms-of-service.html` |
| Support         | `https://<username>.github.io/expi-labs/app/pr-gems/support.html`  |
| Data Deletion   | `https://<username>.github.io/expi-labs/app/pr-gems/data-deletion.html` |
| Child Safety    | `https://<username>.github.io/expi-labs/app/pr-gems/child-safety.html` |
| Security        | `https://<username>.github.io/expi-labs/app/pr-gems/security.html` |

## Adding a New App

1. Create a new folder under `docs/app/<new-slug>/`.
2. Copy the PR Gems pages as templates.
3. Update `config.json` with the new app entry.
4. Update `docs/index.html` and `docs/index.md` to link to the new app.
5. Replace all `[PLACEHOLDER]` values with the app's actual information.

## Current Configuration

| Field              | Value                          |
| ------------------ | ------------------------------ |
| Support Email      | expilabs7@gmail.com            |
| Package Name       | com.WraparoundGames.PRGems     |
| Effective Date     | February 9, 2026               |

All placeholders have been filled in. See `config.json` for the full configuration.
