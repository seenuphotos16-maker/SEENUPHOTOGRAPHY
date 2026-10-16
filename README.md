# Seenu Photography — Champagne Elegance Website

Responsive static portfolio website in ivory, champagne, muted gold and charcoal.

## Included
- Homepage, portfolio, about and contact pages
- Individual wedding, pre-wedding, post-wedding, baby, maternity and traditional collection pages
- Responsive mobile navigation
- Floating Instagram and WhatsApp buttons
- Gallery lightbox with next/previous, Escape, arrow keys and touch swipe
- WhatsApp enquiry form, studio phone and address, Google Maps directions/embed
- Basic SEO metadata, robots.txt and sitemap template

## Before publishing
1. Replace the preview Unsplash photos with Seenu Photography's own photographs.
2. Replace the generic Instagram URL with the studio's actual Instagram profile.
3. Replace YOUR-DOMAIN.example in robots.txt and sitemap.xml.
4. Confirm the business details and review information.
5. Test all links and forms on mobile and desktop.

The enquiry form opens WhatsApp with a pre-filled message. This static site does not save submissions in a database and has no admin portal or upload API.

## Run / deploy
Open index.html or use VS Code Live Server. Upload this folder to a static host such as GitHub Pages, Netlify or Vercel. For Vercel, set the output directory to the project root.


## Homepage refresh
The homepage now has a full-screen three-image slideshow, portfolio rows for Wedding/Reception, Pre & Post-Wedding, Baby & Family, and Aesthetic/Traditional photography, a studio map, client-review cards, and a seven-card “Why choose us?” section. The existing ivory, champagne, and gold theme is preserved.

### Before publishing
- Replace the sample Unsplash image URLs in `index.html` with Seenu Photography's own images.
- Replace the clearly marked review-card placeholder copy and reviewer labels with real, permissioned customer reviews.
- Confirm the studio address and Google Maps pin are accurate.
- Replace the Instagram profile URL in the footer/social icon with the studio's real profile URL.


## Image assets
All external Unsplash sample photos have been removed from the website. The pages now use branded placeholders until your real images are added. See `assets/README.md` and `assets/image-manifest.json` for the organised folder structure and suggested filenames. The `assets/images/` subfolders are intentionally empty.


## Responsive rework (v2)
The latest stylesheet adds a full responsive pass for wide desktop, small laptop, tablet, and phone widths while preserving the Seenu ivory/champagne/gold look. Navigation collapses before it gets crowded, mobile menus can scroll, homepage hero buttons stack on narrow phones, portfolio cards resize without clipping, maps and forms become single-column on mobile, and the footer/social controls use tighter spacing.

Suggested manual browser checks:
- Desktop: 1440 × 900 and 1024 × 768
- Tablet: 768 × 1024
- Mobile: 390 × 844, 360 × 800 and 320 × 700
- Test the hamburger menu, hero previous/next controls, WhatsApp enquiry form, and Google Maps embed at each size.


### Homepage hero image locations
The three homepage slideshow image paths are now explicit in `index.html`:
- `assets/images/hero/hero-01.jpg`
- `assets/images/hero/hero-02.jpg`
- `assets/images/hero/hero-03.jpg`

Put your real photos in `SeenuPhotography/assets/images/hero/` and use these exact filenames. The same paths are documented in `assets/images/hero/README.txt`.


## Collection image slots

Wedding, pre-wedding, post-wedding, baby/family, maternity/Valikapu and traditional collection pages each include 15 numbered image slots. Copy images into the matching `assets/images/` folder using the filenames listed in `assets/IMAGE-GUIDE.md`. The first four images in each category are previewed on the homepage. Missing images remain placeholders instead of showing broken-image icons.
