# Lil' King

Static site for Lil' King — Springfield, Illinois. Precision. Performance. Capital. One page: intro video, hero, and photo gallery.

Live: https://lil-king.lilkingspringfield.workers.dev

## Deploy

```bash
npx wrangler deploy
```

This publishes `public/` as the Cloudflare Worker `lil-king` (Workers Static Assets). No Worker script is required.

Cloudflare Workers Builds can be connected to this repo for auto-deploy on push.
