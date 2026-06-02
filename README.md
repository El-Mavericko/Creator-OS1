# Creator OS — Deploy Guide

## Files in this package
- `index.html` — the full app
- `manifest.json` — PWA config (makes it installable)
- `sw.js` — service worker (offline support)
- `vercel.json` — Vercel hosting config
- `icons/` — add your app icons here (192×192 and 512×512 PNG)

---

## Deploy to Vercel (free, ~5 minutes)

### Option A — Drag & drop (no coding required)
1. Go to **vercel.com** and sign up with GitHub or email
2. Click **Add New → Project**
3. Click **"Deploy from your computer"** or drag this folder into the upload area
4. Hit **Deploy**
5. Vercel gives you a live URL like `creator-os.vercel.app`

### Option B — Via GitHub (recommended for ongoing updates)
1. Create a free account at **github.com**
2. Create a new repository called `creator-os`
3. Upload all files from this folder into that repo
4. Go to **vercel.com**, click **Add New → Project**, connect your GitHub
5. Select the `creator-os` repo → Deploy
6. Every time you update files on GitHub, Vercel auto-redeploys

---

## Set a custom domain (optional but professional)
1. Buy a domain e.g. `creatoroshq.com` (~£10/yr on Namecheap)
2. In Vercel → your project → Settings → Domains → Add domain
3. Follow the DNS instructions — takes ~10 minutes

---

## How Billy installs it on his phone

### iPhone (Safari)
1. Open the URL in Safari
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **Add** — done, it's on his home screen

### Android (Chrome)
1. Open the URL in Chrome
2. Tap the **three dots** menu
3. Tap **"Add to Home Screen"** or **"Install app"**
4. Done

---

## Adding real app icons
Replace the placeholder icons with real ones:
- `icons/icon-192.png` — 192×192 pixels
- `icons/icon-512.png` — 512×512 pixels

Use Canva, Figma, or any image editor. A simple dark background (#0A0A0F) with the lime "OS" logo works great.

---

## Next steps after Billy tests it
- [ ] Collect feedback on what's missing or confusing
- [ ] Add user login (Supabase — free tier)
- [ ] Add Stripe billing for £50/month subscriptions
- [ ] Port to React Native / Expo for App Store listing
