# Netlify Deployment Instructions

## Quick Deploy to Netlify (Recommended)

1. **Visit Netlify:** https://app.netlify.com/start/deploy?repository=https://github.com/divyanshu2616/loksandarbh-addhyan-samiti

2. **Or Manual Steps:**
   - Go to https://app.netlify.com
   - Click "New site from Git"
   - Select GitHub
   - Choose this repository
   - Click Deploy

Your site will be live in seconds!

## Alternative: Vercel

1. Go to https://vercel.com/new
2. Select "Import Git Repository"
3. Paste: https://github.com/divyanshu2616/loksandarbh-addhyan-samiti
4. Click Deploy

---

## Local Testing

To test locally:
```bash
# If you have Python 3
python -m http.server 8000

# If you have Node.js
npx serve .

# Then open: http://localhost:8000
```
