# Closifi Landing Page — Standalone Repository

This is the official marketing landing page for Closifi (`closifi.app`), decoupled from the main web application (`app.closifi.app`).

## Development

```bash
# Install dependencies
npm install

# Start local dev server (http://localhost:3000)
npm run dev

# Build production bundle (output in dist/)
npm run build

# Preview production build locally
npm run preview
```

## Deployment Options for Root Domain (`closifi.app`)

### 1. Vercel (Recommended)
1. Push this folder to a dedicated Git repository (e.g. `github.com/your-org/closifi-landing`).
2. Import project in Vercel.
3. Framework Preset: **Vite** or **Other**.
4. Build Command: `npm run build`
5. Output Directory: `dist`
6. Add custom domain: `closifi.app` and `www.closifi.app`.

### 2. Netlify
1. Connect Git repository to Netlify.
2. Build command: `npm run build`
3. Publish directory: `dist`
4. Set domain to `closifi.app`.

### 3. Cloudflare Pages
1. Connect repo to Cloudflare Pages.
2. Build command: `npm run build`
3. Build output directory: `dist`
4. Assign custom domain: `closifi.app`.
