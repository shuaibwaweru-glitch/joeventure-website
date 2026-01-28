# Joeventure Tours & Travel - Project Structure

## 📁 Folder Architecture

```
joeventure-website/
├── public/                      # Static assets
│   ├── images/
│   │   ├── logo/               # Logo files
│   │   ├── destinations/       # Kenya destinations photos
│   │   ├── wildlife/           # Safari animal photos
│   │   ├── testimonials/       # Guest photos
│   │   └── gallery/            # General gallery images
│   ├── videos/                 # Hero videos
│   └── favicon.ico
│
├── src/
│   ├── css/
│   │   ├── main.css           # Global styles
│   │   ├── components.css     # Reusable components
│   │   └── pages.css          # Page-specific styles
│   │
│   ├── js/
│   │   ├── main.js            # Core functionality
│   │   ├── navigation.js      # Menu & routing
│   │   ├── forms.js           # Form handling
│   │   ├── gallery.js         # Image gallery
│   │   └── chat.js            # Live chat integration
│   │
│   └── components/            # Reusable HTML partials
│       ├── header.html
│       ├── footer.html
│       ├── contact-form.html
│       └── package-card.html
│
├── pages/
│   ├── index.html             # Homepage
│   ├── about.html             # About Us
│   ├── packages.html          # Safari Packages
│   ├── destinations.html      # Destinations
│   ├── support.html           # Client Support Portal
│   ├── gallery.html           # Photo Gallery
│   ├── testimonials.html      # Reviews
│   ├── blog.html              # Blog listing
│   └── contact.html           # Contact page
│
├── api/                       # Serverless functions (Vercel)
│   ├── contact.js            # Contact form handler
│   └── inquiry.js            # Booking inquiry handler
│
├── .gitignore
├── vercel.json               # Vercel configuration
├── package.json              # Dependencies
└── README.md                 # Project documentation
```

## 🚀 Tech Stack
- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Hosting**: Vercel (with serverless functions)
- **Version Control**: GitHub
- **Form Handling**: Vercel Serverless + Free email service (FormSpree/EmailJS)
- **Chat Widget**: Tawk.to (free)
- **Analytics**: Google Analytics (free)

## 📋 Free Integrations
- **Forms**: FormSpree or Web3Forms
- **Chat**: Tawk.to or Crisp
- **Booking Calendar**: Calendly embed
- **Maps**: Google Maps Embed API
- **Payments**: PayPal or Flutterwave (Kenya-friendly)
- **Email**: EmailJS for automated responses

## 🎨 Design System
- **Colors**: Safari Green (#4A7C59), Sunset Orange (#E67E22), Clay Brown (#8B4513)
- **Fonts**: Inter (body), Playfair Display (headings)
- **Mobile-first**: Responsive breakpoints at 768px, 1024px, 1440px
