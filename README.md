# Quote Genius

Instant quote generator for service businesses. No signup required.

## Live URL
https://tcby04.github.io/quote-genius/

## Features

### Free Version
- Business name & contact info
- Up to 5 line items
- Auto-calculated total
- Generate shareable quote URL
- Copy quote as formatted text

### Pro ($5/month)
- Unlimited line items
- Custom logo on quotes
- PDF export
- Remove "Created with Quote Genius" branding
- Save business info (auto-loads)

## Payment Links
- Venmo, CashApp, PayPal supported
- Stripe checkout for Pro subscriptions

## Tech Stack
- Single HTML file
- Vanilla JavaScript
- GitHub Pages hosting
- Render.com backend for code validation

## Stripe Integration

### Get Keys from Stripe Dashboard
- Developers → API Keys
- Use live keys for production

### Live Payment Link
https://buy.stripe.com/28E9AT7qB7RT4UX8mc8EM01

### Webhook
https://quote-genius-server.onrender.com/webhook

## Backend Server
https://quote-genius-server.onrender.com

### API Endpoints
- POST /validate - Validate Pro unlock code
- GET /get-code?session=xxx - Get code by Stripe session
- POST /webhook - Stripe webhook handler
- GET /admin/codes - List all codes

## To Do
- Add AdSense (need to sign up)
- Email delivery for unlock codes
- PDF improvements
