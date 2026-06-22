# The Audit Trifecta — Vercel Ready

This is a static HTML landing page prepared for Vercel deployment.

## Files

- `index.html` — the full landing page.
- `vercel.json` — Vercel deployment configuration.
- `package.json` — project metadata and optional deploy script.
- `.gitignore` — ignores Vercel, environment, and local system files.

## Deploy on Vercel

### Option 1: Upload through Vercel

1. Go to Vercel.
2. Create a new project.
3. Upload or import this folder.
4. Framework preset: **Other**.
5. Build command: leave blank.
6. Output directory: leave blank.
7. Deploy.

### Option 2: Deploy from GitHub

1. Push this folder to a GitHub repository.
2. In Vercel, click **Add New Project**.
3. Import the repository.
4. Framework preset: **Other**.
5. Build command: leave blank.
6. Output directory: leave blank.
7. Deploy.

### Option 3: Deploy with Vercel CLI

```bash
npm i -g vercel
vercel login
vercel --prod
```

## Notes

The page uses inline CSS, inline JavaScript, Google Fonts, external Jotform links, WhatsApp links, and embedded base64 images. No build step is required.
