# Neptora Inc — Website

> Premium futuristic website for Neptora Inc. Built as a single-file multi-page application with animated starfield, SVG icons, and smooth page transitions.

---

## 🚀 Deploy to Vercel (Recommended)

### Option A — One-Click via Vercel Dashboard (Easiest)

1. Push this repo to GitHub (instructions below)
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repository
4. Vercel auto-detects the config — just click **Deploy**
5. Your site is live in ~30 seconds ✦

---

### Option B — Vercel CLI

```bash
# Install Vercel CLI globally
npm install -g vercel

# Login
vercel login

# Deploy from project root
vercel

# Deploy to production
vercel --prod
```

---

## 📁 Project Structure

```
neptora-inc/
├── public/
│   └── index.html        # Full website (all 5 pages)
├── vercel.json           # Vercel deployment config
├── .gitignore
└── README.md
```

---

## 🐙 Push to GitHub

```bash
# 1. Initialize git repo
git init

# 2. Add all files
git add .

# 3. First commit
git commit -m "feat: initial Neptora Inc website"

# 4. Create repo on GitHub at github.com/new
#    Name it: neptora-inc  (keep it Public or Private)

# 5. Link and push
git remote add origin https://github.com/YOUR_USERNAME/neptora-inc.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

---

## 🔄 Update & Redeploy

Every push to `main` will **auto-deploy** to Vercel once connected:

```bash
# Make changes to public/index.html, then:
git add .
git commit -m "update: your change description"
git push
```

Vercel picks up the push and redeploys automatically — usually under 20 seconds.

---

## 🌐 Custom Domain (Optional)

1. In Vercel Dashboard → your project → **Settings → Domains**
2. Add your domain e.g. `neptorainc.com`
3. Follow DNS instructions (add A record or CNAME to your registrar)
4. Vercel provisions SSL automatically — free

---

## ⚡ What's Inside

| Feature | Detail |
|---|---|
| Pages | Home, About, Services, Projects, Contact |
| Background | Canvas starfield — shooting stars, aurora, parallax nebulae |
| Icons | Inline SVG (no external icon lib needed) |
| Fonts | Syne + DM Sans + Space Mono (Google Fonts) |
| Animations | CSS scroll-reveal, page transitions, orbital rings |
| Responsive | Mobile, tablet, desktop |
| Logo | Embedded base64 (no external image files needed) |
| Forms | Contact form with success state |
| Performance | Single HTML file, no build step, no dependencies |
