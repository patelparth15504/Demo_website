# Artisan Plumbing Co. — Demo Website

A premium boutique plumber demo site for the Australian market (Sydney Eastern Suburbs). Built with plain HTML, CSS, and vanilla JavaScript — no build step required.

## Quick Start

Open `index.html` in a browser, or serve locally:

```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080`.

## Pages

| Page | File | Purpose |
|------|------|---------|
| Home | `index.html` | Hero, services preview, reviews, emergency CTA |
| Services | `services.html` | Full service details with pricing |
| About | `about.html` | Story, process, licences |
| Service Areas | `areas.html` | Suburb list + map embed |
| Reviews | `reviews.html` | 8 fictional 5-star testimonials |
| FAQ | `faq.html` | Accordion FAQ |
| Book Appointment | `book.html` | Booking form with date/time picker |
| Contact | `contact.html` | Quote form + business details |

## Features

- **Premium design** — Navy/charcoal palette, copper accents, Playfair Display + Source Sans 3
- **Mobile-first** — Sticky header, click-to-call, emergency banner, bottom CTA bar
- **Australian touches** — NSW licence, ABN, GST-inclusive pricing, real Eastern Suburbs
- **Client-side forms** — Validation + success states (no backend)
- **SEO ready** — Meta descriptions, LocalBusiness JSON-LD on home page
- **Accessible** — Semantic HTML, ARIA labels, keyboard-friendly FAQ accordion

## Deploy

Host on any static platform:

- **GitHub Pages** — Push repo, enable Pages on `main` branch
- **Netlify** — Drag-and-drop the folder or connect repo
- **Any web host** — Upload files via FTP

## Demo vs. Real

| Fake (demo) | Real (functional) |
|-------------|-------------------|
| Testimonials, licence numbers, ABN | Layout, navigation, responsive design |
| Form submission to server | Client-side validation + success UI |
| Live booking calendar sync | Date/time picker appearance |
| Map pin exact office | Google Maps embed of service region |

## Customisation

Edit CSS variables in `css/styles.css` (`:root`) to change colours. Update copy, phone numbers, and suburbs in the HTML files. Replace Unsplash image URLs with your own assets in `images/`.

## Licence

Demo template — free to use and modify for client presentations.
