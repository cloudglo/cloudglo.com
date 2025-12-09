# CloudGlo.com

Professional consulting services website, deployed on Cloudflare Pages.

## Development

```bash
# Install dependencies
npm install

# Start local dev server
npm run dev
```

## Deployment

```bash
# Deploy to Cloudflare Pages
npm run deploy
```

## Structure

```
cloudglo.com/
├── public/           # Static assets served by Cloudflare Pages
│   ├── index.html    # Main landing page
│   ├── css/          # Stylesheets
│   └── assets/       # Images, logos, etc.
├── wrangler.toml     # Cloudflare configuration
└── package.json      # Project scripts
```
