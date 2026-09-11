# ShorokooWeb

Static website for shorokoo.com (shorokoo.org redirects to it).

- Hosting: Cloudflare Workers with static assets, configured in `wrangler.jsonc`.
- Deploys: Cloudflare's GitHub integration deploys every push to `main`. There is no build step.
- All published files live in `public/`. Keep the site plain HTML/CSS unless asked to add a framework or build step (if one is added, update `wrangler.jsonc` and the Cloudflare build settings to match).
- Preview locally with `npx wrangler dev`.
