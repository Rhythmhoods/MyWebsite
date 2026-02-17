# PulseNest Media Website

A complete multi-page marketing website for a social media management and marketing startup.

## Pages
- Home (`index.html`)
- Services (`services.html`)
- Case Studies (`case-studies.html`)
- About (`about.html`)
- Pricing (`pricing.html`)
- Contact / Book a Call (`contact.html`)

## Features
- Conversion-focused messaging and structure
- Premium dark visual style with accent gradients
- Mobile responsive layout
- Lead capture contact form
- Calendly CTA placeholder link
- Floating WhatsApp quick-contact button

## Run locally
Use either command:

```bash
python3 -m http.server 8000
```

or

```bash
npm start
```

Then open `http://localhost:8000`.

## If preview says "Not Found"
- Make sure the server is running (`npm start` or `python3 -m http.server 8000`).
- Open the root URL (`/`) or `/index.html`.
- A `404.html` redirect is included to route unknown URLs back to the homepage on static hosts.

## Customize quickly
- Brand name: update in headers/footers across HTML files
- Colors and typography: `styles.css`
- WhatsApp number: update link in `index.html`
- Calendly link: update `contact.html`
