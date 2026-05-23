# HSB Marble | Granite | Stones — Website

A complete, lead-generation website for a stone surface installation business in England.

## 📁 What's Included

```
hsb-website/
├── index.html          → Homepage
├── kitchens.html       → Kitchen worktops & islands
├── stairs.html         → Stone staircases
├── bathrooms.html      → Bathroom surfaces & vanities
├── commercial.html     → Bar counters, retail, hospitality
├── gallery.html        → Filterable portfolio
├── about.html          → Company story & values
├── contact.html        → Contact details + quote form
├── styles.css          → All styling (luxury editorial aesthetic)
├── main.js             → Navigation, gallery filter, FAQ, forms
└── images/             → 17 project photos + logo
```

## 🚀 How to Use

**To preview locally:** double-click `index.html` and it opens in your browser.

**To publish online:** upload the entire folder to any web host. The site is pure static HTML/CSS/JS — no build step, no server required.

Free hosting options that work straight away:
- **Netlify** (netlify.com) — drag & drop the folder, done
- **Vercel** (vercel.com) — same, drag & drop
- **GitHub Pages** — push to a repo and enable Pages
- **Cloudflare Pages** — similar to Netlify, totally free

## ✏️ Things to Customize Before Going Live

Search the project for `[Insert ...]` placeholders and replace them with your friend's real details. There are 4 things to swap in every HTML file:

1. **Phone number** — replace `[Insert Phone Number]` (Contact page, footer CTA, etc.)
2. **Email address** — replace `[Insert Email Address]` / `[Insert Email]`
3. **WhatsApp number** — replace `[InsertNumber]` in the `https://wa.me/[InsertNumber]` link (use country code without `+`, e.g. `447XXX...` for UK)
4. **Workshop address** — replace `[Insert Workshop Address]` on the contact page

Quick way: open the whole folder in VS Code or any editor, use "Find & Replace in Files", and swap each placeholder once across all 8 HTML files.

## 📧 Connecting the Quote Forms

Currently forms show a "Thank you" message on submit but **don't actually email anyone**. To receive real leads:

**Easiest option — Formspree (free for 50 submissions/month):**
1. Sign up at formspree.io
2. Create a new form, copy your form endpoint (looks like `https://formspree.io/f/abcd1234`)
3. In each HTML file, find `<form>` and change it to `<form action="https://formspree.io/f/abcd1234" method="POST">`
4. In `main.js`, replace the placeholder form handler with a real fetch (instructions commented in the file)

**Alternative — EmailJS** (similar setup, also free tier).

## 🎨 Design Notes

- **Typography:** Cormorant Garamond (headings) + Inter (body) — loaded from Google Fonts
- **Palette:** Charcoal #1a1a1a, Cream #f9f7f4, Gold #c9a96e
- **Mobile-first:** Fully responsive with breakpoints at 768px and 1024px
- **Hamburger menu** on mobile, sticky nav with smooth scroll behavior throughout
- **Scroll-reveal animations** trigger on intersection (subtle fade-up on each section)
- **WhatsApp float button** sits bottom-right on every page

## 📸 Replacing Photos

All photos live in `/images/`. To swap any image, just replace the file while keeping the same filename — the HTML references won't need to change.

Photos used:
- `kitchen-island-calacatta.jpg` — hero image
- `stairs-curved-white.jpg` — stairs hero  
- `bath-vanity-marble.jpg` — bathroom hero
- `bar-counter-white.jpg` — commercial hero
- ... and 13 more in the gallery

## ✅ What This Site Does for Lead Generation

- **Sticky "Free Quote" CTA** in the top nav on every page
- **WhatsApp float button** — one tap from any page
- **Quote forms** on home, kitchens, stairs, bathrooms, commercial, and contact pages — each pre-filtered by project type
- **Click-to-call** phone links in the footer and contact page
- **Trust signals** front-and-center: 500+ projects, 10+ years, fully insured, free measurements
- **Social proof** — 3 testimonials on the homepage
- **Service-specific landing pages** with their own FAQs to convert browsers into enquiries

---

Built with care. Good luck with the launch! 🪨
