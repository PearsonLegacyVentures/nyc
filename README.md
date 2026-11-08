# Tranquilitas — New York City

Dedicated enquiry-first destination website for New York City.

## Canonical
https://nyc.tranquilitasspa.com/

## Cloudflare Pages
Framework: none. Build command: none. Output directory: repository root. Production branch: main.

## Booking policy
WhatsApp and telephone are prominent. Enquiries require a selected treatment, guests, exact property, date and time. At least 6 hours in America/New_York; request hours 10 AM–7 PM local time. Prices and therapist credentials must be confirmed before any booking. No verified local walk-in storefront is asserted.

## Email channel
Set **BOOKING_FROM_EMAIL** to `bookings@bahamasmassages.com` as a non-secret text variable on the Cloudflare Pages project. Add `RESEND_API_KEY` as a secret after verifying sender domain with Resend. The email endpoint returns a clear error until configured. Recipients are fixed in the server handler and are not environment variables.

## Pricing policy
For future US/UK international price proposals, the user's requested internal benchmark is **current verified Nassau service base × 1.15**, rounded appropriately in local currency after current FX, staffing, licensing, tax, travel, and margin checks. **Do not publish unverified international rates.** This build is inquiry-only.

## Authenticity
Only genuine Tranquilitas massage images are used to depict massage. The destination image is from https://unsplash.com/photos/new-york-city-skyline-at-night-with-tall-buildings-hGiIm9_993Y (Unsplash) and is credited. It does not purport to show a Tranquilitas appointment in New York City.

## Routes
/
/services/
/areas/
/about/
/contact/
/faq/
/request/
/privacy/
/swedish-massage/
/deep-tissue-massage/
/couples-massage/
/hotel-massage/
/villa-massage/
/group-wellness/
/areas/midtown-manhattan/
/areas/upper-east-side/
/areas/tribeca/
/areas/williamsburg/
/areas/long-island-city/
/journal/
/journal/hotel-and-villa-massage-guide/
/journal/couples-wellness-planning-guide/
/journal/private-massage-guest-checklist/

## Independent Cloudflare Pages deployment

Cloudflare Pages project: `nyc` (`https://nyc-3ci.pages.dev/`). The `main` branch automatically deploys to this website's own Pages project. The public domain will be transferred after independent deployment and DNS verification; the original shared Grenada Pages project remains available until migration completes.
