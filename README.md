# ShorokooWeb

Source for [shorokoo.com](https://shorokoo.com).

A static website hosted on Cloudflare Workers (static assets). Every push to `main` is built and deployed automatically by Cloudflare.

## Structure

- `public/` – everything that gets published (HTML, CSS, images)
- `wrangler.jsonc` – Cloudflare deployment settings

## Preview locally

```sh
npx wrangler dev
```

Then open http://localhost:8787.
