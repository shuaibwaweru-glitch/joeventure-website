# 🚀 Deployment Guide - Joeventure Website

## Step 1: Push to GitHub

1. **Initialize Git** (if not done):
```bash
cd joeventure-website
git init
git add .
git commit -m "Initial commit: Joeventure Tours website structure"
```

2. **Create GitHub Repository**:
   - Go to github.com
   - Click "New Repository"
   - Name: `joeventure-website`
   - Don't initialize with README (we already have one)
   - Click "Create Repository"

3. **Push to GitHub**:
```bash
git remote add origin https://github.com/YOUR_USERNAME/joeventure-website.git
git branch -M main
git push -u origin main
```

## Step 2: Deploy to Vercel

### Option A: Via Vercel Dashboard (Easiest)

1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Click "New Project"
4. Import your `joeventure-website` repository
5. Click "Deploy"
6. Done! Your site will be live at `https://joeventure-website.vercel.app`

### Option B: Via Vercel CLI

1. **Install Vercel CLI**:
```bash
npm install -g vercel
```

2. **Login**:
```bash
vercel login
```

3. **Deploy**:
```bash
vercel
```

4. **Deploy to Production**:
```bash
vercel --prod
```

## Step 3: Custom Domain (Optional)

1. In Vercel Dashboard, go to your project
2. Click "Settings" → "Domains"
3. Add your custom domain (e.g., `joeventuretours.com`)
4. Follow DNS configuration instructions
5. Vercel will auto-generate SSL certificate

## Step 4: Configure Integrations

### Web3Forms (Contact Form)
1. Go to [web3forms.com](https://web3forms.com)
2. Sign up and get your Access Key
3. Add to `api/contact.js`:
```javascript
const ACCESS_KEY = 'YOUR_ACCESS_KEY_HERE';
```

### Tawk.to (Live Chat)
1. Go to [tawk.to](https://www.tawk.to)
2. Sign up and create a widget
3. Copy the widget code
4. Paste in `src/components/footer.html` before `</body>`

### Calendly (Booking)
1. Create account at [calendly.com](https://calendly.com)
2. Set up your availability
3. Get your scheduling link
4. Embed in support.html and contact.html

### Google Maps
1. Get API key from [Google Cloud Console](https://console.cloud.google.com)
2. Enable Maps JavaScript API
3. Add to destinations.html:
```html
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY"></script>
```

## Step 5: Environment Variables

In Vercel Dashboard:
1. Go to Project Settings → Environment Variables
2. Add:
   - `WEB3FORMS_KEY` = your Web3Forms key
   - `GOOGLE_MAPS_KEY` = your Google Maps key

## Step 6: Testing

Test your live site:
- ✅ All pages load correctly
- ✅ Navigation works
- ✅ Contact form submits
- ✅ Images load properly
- ✅ Mobile responsive
- ✅ Chat widget appears

## Automatic Deployments

Every time you push to GitHub, Vercel will automatically:
1. Build your site
2. Deploy to a preview URL
3. If pushed to `main`, deploy to production

## Troubleshooting

**Images not loading?**
- Check file paths are relative
- Ensure images are in `/public/images/`

**Forms not working?**
- Verify Web3Forms API key
- Check browser console for errors

**Chat widget not showing?**
- Ensure Tawk.to script is before `</body>`
- Check for JavaScript errors

## Next Steps

1. Add your actual safari photos to `/public/images/`
2. Update contact information in footer
3. Customize package details
4. Add blog content for SEO
5. Set up Google Analytics
6. Submit sitemap to Google Search Console

---

**Need Help?**
- Vercel Docs: https://vercel.com/docs
- Web3Forms: https://docs.web3forms.com
- Tawk.to: https://help.tawk.to

Your website is now live! 🎉
