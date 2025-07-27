# 🚀 Deployment Guide for Sahyog A Portfolio

## Option 1: GitHub Pages (Recommended)

### Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New repository"
3. Name it: `sahyog-portfolio` or `portfolio`
4. Make it **Public** (required for free GitHub Pages)
5. Don't initialize with README (we already have one)

### Step 2: Push to GitHub
```bash
# Add the remote repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/sahyog-portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"
7. Wait 2-5 minutes for deployment

**Your site will be available at:** `https://YOUR_USERNAME.github.io/sahyog-portfolio`

---

## Option 2: Netlify (Free & Fast)

### Step 1: Create Netlify Account
1. Go to [Netlify.com](https://netlify.com)
2. Sign up with GitHub

### Step 2: Deploy
1. Click "New site from Git"
2. Choose GitHub
3. Select your portfolio repository
4. Deploy settings:
   - Build command: (leave empty)
   - Publish directory: (leave empty - it's the root)
5. Click "Deploy site"

**Your site will be available at:** `https://random-name.netlify.app`

---

## Option 3: Vercel (Free & Fast)

### Step 1: Create Vercel Account
1. Go to [Vercel.com](https://vercel.com)
2. Sign up with GitHub

### Step 2: Deploy
1. Click "New Project"
2. Import your GitHub repository
3. Framework Preset: "Other"
4. Click "Deploy"

**Your site will be available at:** `https://sahyog-portfolio.vercel.app`

---

## Option 4: Local Testing

To test locally before deploying:
```bash
# Using Python (if installed)
python -m http.server 8000

# Using Node.js (if installed)
npx serve .

# Using PHP (if installed)
php -S localhost:8000
```

Then visit: `http://localhost:8000`

---

## Option 5: Surge.sh (Quick & Simple)

```bash
# Install Surge globally
npm install -g surge

# Deploy
surge

# Follow the prompts to create account and deploy
```

---

## 🎯 Recommended Deployment Steps

1. **Use GitHub Pages** (easiest for beginners)
2. **Backup with Netlify** (for redundancy)
3. **Custom domain** (optional - costs ~$10/year)

## 📝 Post-Deployment Checklist

- [ ] Test all links work correctly
- [ ] Verify contact information is accurate
- [ ] Check mobile responsiveness
- [ ] Test contact form (if added later)
- [ ] Update social media profiles with new URL
- [ ] Add to LinkedIn profile
- [ ] Share with potential employers

## 🔧 Custom Domain (Optional)

If you want a custom domain like `sahyog.dev`:

1. **Buy domain** from Namecheap, GoDaddy, or Google Domains
2. **Configure DNS** to point to your hosting provider
3. **Update hosting settings** to use custom domain

## 📊 Performance Monitoring

After deployment, check:
- [Google PageSpeed Insights](https://pagespeed.web.dev/)
- [GTmetrix](https://gtmetrix.com/)
- [WebPageTest](https://www.webpagetest.org/)

---

**🎉 Your portfolio will be live and professional-looking!** 