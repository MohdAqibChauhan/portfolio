# Backend Portfolio - Deployment Guide

## Quick Deploy to Vercel

### Step 1: Initialize Git Repository

```bash
cd C:\Users\arifc\portfolio
git init
git add .
git commit -m "Initial commit: Backend-first portfolio"
```

### Step 2: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `portfolio` (or any name you prefer)
3. Keep it public
4. **Do NOT** initialize with README (we already have one)
5. Click "Create repository"

### Step 3: Push to GitHub

```bash
git remote add origin https://github.com/MohdAqibChauhan/portfolio.git
git branch -M main
git push -u origin main
```

### Step 4: Deploy to Vercel

1. Go to https://vercel.com
2. Sign in with GitHub
3. Click "Add New..." → "Project"
4. Import your `portfolio` repository
5. Vercel will auto-detect it as a static site
6. Click "Deploy"
7. Wait 30-60 seconds
8. Your portfolio is live! 🎉

### Step 5: Custom Domain (Optional)

1. In Vercel dashboard, go to your project
2. Click "Settings" → "Domains"
3. Add your custom domain
4. Follow DNS configuration instructions

## Alternative: Deploy to GitHub Pages

```bash
# Enable GitHub Pages in repository settings
# Settings → Pages → Source: main branch → Save
# Your site will be at: https://mohdaqibchauhan.github.io/portfolio/
```

## Local Testing

```bash
# Option 1: Direct open
start index.html

# Option 2: Python server
python -m http.server 8000
# Visit: http://localhost:8000

# Option 3: Node.js server
npx http-server
```

## Updating Your Portfolio

```bash
# Make changes to HTML/CSS files
git add .
git commit -m "Update project details"
git push

# Vercel will automatically redeploy
```

## Troubleshooting

**Issue: Vercel shows 404**
- Ensure `index.html` is in root directory
- Check `vercel.json` configuration

**Issue: Styles not loading**
- Verify `assets/styles.css` path is correct
- Check browser console for errors

**Issue: Links broken**
- Use relative paths (e.g., `../assets/styles.css`)
- Avoid absolute paths with `C:\`

## Next Steps

1. ✅ Deploy to Vercel
2. ✅ Share portfolio link on LinkedIn
3. ✅ Add GitHub repo link to resume
4. ✅ Update Apidog documentation links (if public)
5. ✅ Consider adding architecture diagrams (draw.io, Mermaid)

---

**Your portfolio URL will be:** `https://portfolio-<random>.vercel.app`

You can customize this in Vercel settings.
