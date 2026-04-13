# Claude Memory — Julie On The Move Website

## About the Site
- **Site name:** Julie On The Move
- **Live URL:** https://itsjulieonthemove.com
- **Netlify subdomain:** julie-on-the-move.netlify.app
- **GitHub repo:** julietterabahi-bot/julie-on-the-move-website (branch: main)
- **Tagline:** Travel · Fitness · Ebooks

## About Jules
- Full name: Juliette Rabahi
- Email: julietterabahi@gmail.com
- She's a fitness-focused serial traveller and content creator
- Known for finding off-the-beaten-path destinations (especially Gaafaru Island, Maldives)
- Philosophy: authentic travel, eat local, stay local, no tourist traps, no sponsored fluff
- Has visited 20+ countries including Maldives, Morocco, Bali, Thailand, Portugal, and more

## Instagram Accounts
- @itsjulieonthego — main travel + fitness content
- @MyMaldivianEscape — dedicated Maldives brand + travel packages

## Pages
- **index.html** — Homepage (hero, marquee strip, about strip, featured products, destinations grid, Instagram CTA)
- **about.html** — About Jules (story, values, journey timeline, fitness section)
- **shop.html** — Shop (ebooks + travel packages, filter tabs, bundle banner)
- **blog.html** — Travel Diaries (featured post, posts grid, newsletter signup)
- **style.css** — Global stylesheet
- **script.js** — Global JS (hamburger menu etc.)

## Products / Shop
- **The Maldives Insider Guide** — Ebook, $24.99, bestseller, covers Gaafaru Island
- **The Maldivian Escape Package** — Travel package, from $899/person, includes ebook + accommodation curation + WhatsApp support
- **Bali Hidden Gems Guide** — Coming soon ebook
- **Bundle promo** — Free ebook with Maldives package booking
- All purchases/enquiries go to: julietterabahi@gmail.com

## Design System

### Colours (CSS variables)
- `--warm-white: #FAF7F2` — page background
- `--beige-light: #F0E8D8` — section backgrounds
- `--beige-mid: #E8DDD0` — borders, card backgrounds
- `--sand: #C4956A` — primary accent (CTAs, labels, dividers)
- `--sand-dark: #A87A52` — hover state for sand
- `--green: #5C7A52` — travel package accent
- `--green-dark: #3D5435` — hover state for green
- `--brown: #2C2416` — primary text, dark backgrounds
- `--brown-mid: #5C4A30` — body text
- `--text-muted: #8C7B6B` — secondary text

### Fonts
- **Serif:** Playfair Display (headings, prices, logo)
- **Sans:** Lato (body, labels, buttons)
- Imported from Google Fonts

### Buttons
- `.btn-primary` — sand background, white text (main CTAs)
- `.btn-secondary` — transparent, brown border (secondary CTAs)
- `.btn-green` — green background (package CTAs)
- All buttons: 50px border-radius, uppercase, small tracking

### Layout
- Max width: 1200px
- Nav height: 70px (fixed)
- Mobile breakpoints: 768px (nav), 900px (grids), 600px (single column)

## Current State / To-Dos
- Photo placeholders throughout the site still need real images (hero, about section, product cards, fitness section)
- Blog posts are placeholder/dummy content — real posts need to be written
- Newsletter form is UI only — not connected to an email service yet
- Blog filter buttons are not functional yet (no JS filter logic)
- Payment/checkout not set up — purchases are via email enquiry for now

## Change Log
| Date | Change | Notes |
|------|--------|-------|
| Apr 8, 2026 | Initial site built | All pages created, placeholder images throughout |
| Apr 8, 2026 | DNS configured | Namecheap A record + CNAME → Netlify, custom domain pending verification |
