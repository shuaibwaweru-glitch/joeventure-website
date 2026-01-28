# 🦁 Joeventure Tours & Travel - Official Website

> Premium Kenya safari experiences for international travelers

![Joeventure Logo](public/images/logo/joeventure-logo.png)

## 🌍 About

Joeventure Tours and Travel specializes in curated safari experiences across Kenya, including Maasai Mara wildlife expeditions, mountain treks (Kilimanjaro, Mount Kenya), beach getaways, and authentic cultural tours.

## 🚀 Quick Start

### Prerequisites
- Git installed
- Node.js (optional, for Vercel CLI)
- GitHub account
- Vercel account (free)

### Local Development

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/joeventure-website.git
cd joeventure-website
```

2. **Open in browser**
Simply open `pages/index.html` in your browser, or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

3. **View the site**
Navigate to `http://localhost:8000/pages/`

### Deploy to Vercel

1. **Install Vercel CLI** (optional)
```bash
npm install -g vercel
```

2. **Deploy**
```bash
vercel
```

Or connect your GitHub repo directly to Vercel for automatic deployments!

## 📁 Project Structure

```
joeventure-website/
├── public/              # Static assets
│   ├── images/         # All images organized by type
│   └── videos/         # Hero videos
├── src/
│   ├── css/           # Stylesheets
│   ├── js/            # JavaScript files
│   └── components/    # Reusable HTML components
├── pages/             # All HTML pages
├── api/               # Serverless functions (contact forms)
└── vercel.json        # Vercel configuration
```

## 🎨 Design System

### Colors
- **Safari Green**: `#4A7C59`
- **Sunset Orange**: `#E67E22`
- **Clay Brown**: `#8B4513`
- **White**: `#FFFFFF`
- **Dark Text**: `#2C3E50`

### Typography
- **Headings**: Playfair Display
- **Body**: Inter

## ✨ Features

- ✅ Mobile-responsive design
- ✅ Fast-loading optimized images
- ✅ SEO-ready meta tags
- ✅ Client support portal
- ✅ Interactive booking forms
- ✅ Live chat integration (Tawk.to)
- ✅ Gallery with lightbox
- ✅ Testimonials section
- ✅ Blog for SEO content
- ✅ Google Maps integration

## 🔧 Free Integrations

| Service | Purpose | Setup |
|---------|---------|-------|
| **Web3Forms** | Contact forms | Add API key in `api/contact.js` |
| **Tawk.to** | Live chat | Add widget code in footer |
| **Calendly** | Booking consultations | Embed link in pages |
| **Google Maps** | Destination maps | Embed API in destinations page |
| **EmailJS** | Automated emails | Configure in `src/js/forms.js` |

## 📝 Configuration

1. **Update Contact Form**
   - Get free API key from [Web3Forms](https://web3forms.com)
   - Add to `api/contact.js`

2. **Add Live Chat**
   - Sign up at [Tawk.to](https://www.tawk.to)
   - Copy widget code to `src/components/footer.html`

3. **Setup Calendly**
   - Create account at [Calendly](https://calendly.com)
   - Embed link in support and contact pages

## 🌐 Deployment

### GitHub Setup
```bash
git init
git add .
git commit -m "Initial commit - Joeventure website"
git branch -M main
git remote add origin https://github.com/yourusername/joeventure-website.git
git push -u origin main
```

### Vercel Deployment
1. Go to [Vercel](https://vercel.com)
2. Click "Import Project"
3. Connect your GitHub repo
4. Deploy! 🚀

Your site will be live at: `https://joeventure-tours.vercel.app`

## 📧 Contact

**Joeventure Tours & Travel**
- Email: info@joeventuretours.com
- Phone: +254 XXX XXX XXX
- Website: [Coming Soon]

## 📄 License

MIT License - Feel free to customize for your needs!

---

**Built with ❤️ for authentic Kenya experiences**
