# wearjd.pk — version 3

## Open locally
Extract the ZIP and open this folder in VS Code. In the terminal:

    python3 -m http.server 8000

Visit http://localhost:8000. No installation or build step needed.

For the recommended GitHub → Vercel workflow, read START-HERE.md.

## Alternative: Vercel CLI deployment
This folder is ready for a static Vercel deployment. From this folder with Node/npm installed:

    npx vercel login
    npx vercel --prod

Choose your account, create a project named wearjd, use the current directory, and select Other if prompted for a framework. No build command is required. The generated Vercel URL is usable before buying a domain.

To use wearjd.pk, first register the domain. Add it in the project's Settings > Domains and use the exact DNS records Vercel provides in your registrar's DNS settings. Branding does not establish domain ownership.

## Included
New wearjd.pk wordmark/favicon, forest-green and cream styling, responsive catalog, search/category filters, price sorting, persistent favourites, size selection, cart quantities and checkout preview. Product details and prices remain editable in products.js. All assets are local.

## Launch status
Frontend is functional. Ordering is a clearly labelled preview: no orders are transmitted, no payment is collected, and no customer contact details are saved. Live ordering needs your business contact or order backend, confirmed products, prices, measurements, delivery charges and exchange policy. Current imagery includes original SVG product concepts and a bundled Unsplash lifestyle placeholder; replace with actual stock photos before taking orders.

## Files
index.html: copy and layout. styles.css: design and responsive rules. app.js: interactions. products.js: catalog and example delivery rates. vercel.json: static hosting configuration. assets/: images and favicon.

## Verification
JavaScript syntax checked; desktop homepage visually checked; saving a product and filtering to saved products verified in browser. Cart/checkout derive from the tested first edition. Responsive rules are provided; physical mobile-device testing remains recommended.

## Image credit
Hero placeholder: https://images.unsplash.com/photo-1556821840-3a63f95609a7 (Unsplash). Not actual wearjd stock or an endorsement. No Breakout brand assets used.
