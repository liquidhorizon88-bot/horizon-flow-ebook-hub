# Horizon Flow Ebook Hub

Owned SEO/static landing hub for Andrew Burton's Horizon Flow ebooks.

- Built: 2026-05-24T17:45:13+00:00
- Intended public URL if deployed to GitHub Pages: https://liquidhorizon88-bot.github.io/horizon-flow-ebook-hub/
- Product links use `utm_source=github_pages&utm_medium=free&utm_campaign=ebook_marketing`.
- Assets reuse existing product marketing images from the product repos; no new image generation was required.

## Verification

Run:

```bash
python3 -m json.tool ../state/marketing-state.json >/dev/null
python3 -m http.server 8099 -d published/horizon-flow-ebook-hub
```
