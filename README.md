# Palette Co Website

Single-page Hugo static website for **Palette Co** — a lash, brows & beauty business in West End, Brisbane.

## Development

```bash
# Run local dev server
hugo server -D

# Build for production
hugo --minify
```

## Deployment

Deploys automatically to Cloudflare Pages on push to `main` via GitHub Actions.

### Required Secrets

- `CLOUDFLARE_API_TOKEN` — Cloudflare API token with Pages permissions
- `CLOUDFLARE_ACCOUNT_ID` — Cloudflare account ID

## Structure

- `layouts/_default/index.html` — Single-page template with all sections and inline CSS
- `content/_index.md` — Homepage content file
- `hugo.toml` — Hugo configuration
- `static/` — Static assets (favicon, etc.)
