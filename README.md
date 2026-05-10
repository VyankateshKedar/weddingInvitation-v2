# 💍 Wedding Invitation — Kawalpreet & Avneesh

A beautiful wedding invitation website with curtain-reveal animation and autoplay video.

## Project Structure

```
wedding-invite/
├── public/
│   ├── index.html      ← Main page
│   └── wedding.mp4     ← Invitation video
└── vercel.json         ← Vercel config
```

## Deploy to Vercel (3 steps)

### Option A — Vercel Dashboard (easiest, no CLI needed)

1. Go to [vercel.com](https://vercel.com) → Log in → **Add New Project**
2. Click **"Deploy without a Git repository"** → drag & drop this entire `wedding-invite` folder
3. Click **Deploy** — done! ✅

### Option B — GitHub + Vercel (recommended for updates)

1. Create a new GitHub repository
2. Push this folder:
   ```bash
   cd wedding-invite
   git init
   git add .
   git commit -m "Wedding invitation site"
   git remote add origin https://github.com/YOUR_USERNAME/wedding-invite.git
   git push -u origin main
   ```
3. Go to [vercel.com](https://vercel.com) → **Add New Project** → Import from GitHub
4. Select your repo → Click **Deploy** ✅

### Option C — Vercel CLI

```bash
npm i -g vercel
cd wedding-invite
vercel --prod
```

## Local Preview

Just open `public/index.html` in any browser — no server needed.
