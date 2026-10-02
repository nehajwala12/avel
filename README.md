# Avel eCare — Phase 1 diagnostic preview (CreditSwan)

Static site. No build step, no dependencies.

## Deploy
- Drag-and-drop: vercel.com/new → upload this folder (or the zip, unzipped).
- CLI: `npx vercel --prod` from inside this folder. Framework preset: Other. Build command: none. Output directory: `.`

## Notes
- Single page: `index.html` (all CSS/JS inline). Fonts load from Google Fonts.
- Search engines blocked (robots.txt, X-Robots-Tag, meta robots) because the packet is confidential.
- The URL is public to anyone who has it. For access control, enable Vercel Deployment Protection (password or Vercel Authentication) in Project Settings.
- Deep links work: `/#resource`, `/#margins/mg-billing`, etc.
