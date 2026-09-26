# MasterDe'Genius Academy - Landing Page

Professional, clean, premium landing page built strictly from the supplied PDF source of truth.

## Brand
- Primary: Deep Navy #0A2342
- Accent: Golden Yellow #FFC300
- White backgrounds extensively, navy sections strategically

## Structure
- Header / Navigation (sticky, WhatsApp CTA)
- Hero (Premium preparation for JAMB, WAEC, NECO, GCE)
- About MasterDe'Genius
- Premium Tutorial Classes (₦5,000 Monthly) with Science/Arts/Commercial subjects
- Value Benefits (4 feature blocks)
- 200 Pre Recorded Teaching Audios (₦15,000 Non Negotiable) with Government, Literature, CRS topic accordions
- Private One on One Tutorial Sessions (Google Meet, fees vary)
- Handbooks (English ₦2,000, Literature ₦3,000)
- MasterDeGenius Edu App (https://www.masterdegenius.com.ng/)
- Contact / WhatsApp CTA
- Footer

## WhatsApp Integration
All purchase buttons use prefilled WhatsApp messages to 08168454014 via https://wa.me/2348168454014

- Premium: Hello MasterDe’Genius, I am interested in the Premium Tutorial Class.
- Audios: Hello MasterDe’Genius, I would like to purchase the 200 Pre Recorded Teaching Audios for ₦15,000.
- English Handbook: Hello MasterDe’Genius, I would like to purchase The Genius Use of English Handbook for ₦2,000.
- Literature Handbook: Hello MasterDe’Genius, I would like to purchase The Genius Literature in English Handbook for ₦3,000.
- Private: Hello MasterDe’Genius, I am interested in booking a private tutorial session.

No checkout, no payment gateway, no backend required.

## Assets
All images are from the PDF:
- assets/logo.png - Official logo
- assets/premium-tutorial.* - Premium class promo (subjects)
- assets/audio-promo.* - 200 audios promo with topic lists and tutor photo
- assets/private-tutor.* - Private tutorial tutor photograph
- assets/english-handbook.* - The Genius Use of English Handbook cover
- assets/literature-handbook.* - The Genius Literature Handbook cover

Optimized to WebP with JPG fallback.

## Deployment
Static site. Upload entire folder to any static hosting:
- Supabase Hosting
- Vercel
- Netlify
- GitHub Pages

No build step required. Just serve index.html.

If using Vite/React, production build is not needed - this is pure HTML/CSS/JS.

## Quality Checks
✓ No fake testimonials, stats, awards
✓ No excessive gradients or rainbow colors
✓ No unnecessary dashes
✓ All PDF text, prices, topics preserved
✓ Mobile responsive, no horizontal overflow
✓ Images not distorted (object-fit)
✓ WhatsApp links correct
✓ SEO title and meta description included
✓ Alt text for all images

## Local Preview
python3 -m http.server 8000
Open http://localhost:8000
