# Sugar & Cloud
A responsive sweet-selling website built with vanilla TypeScript, HTML, and CSS.

## Quick preview (no installation)
Open `dist/index.html` in your browser. Compiled JavaScript and all SVG illustrations are included, so the site works offline.

## Develop
Install Node.js and Python 3, then run:

```bash
npm install
npm run dev
```
Visit http://localhost:5173. After editing TypeScript, run `npm run build` and refresh the browser. `npm run typecheck` checks types without writing files.

## Included
- Six illustrated treats and a gift assortment
- Category filters, product search, and price sorting
- Persistent shopping bag with quantity controls and removal
- Delivery calculation ($4.50; free for orders of $35 or more)
- Accessible native dialogs and mobile/desktop layouts
- Form validation and a clearly labeled demo checkout

## Customize
Edit the product catalog in `src/app.ts`, styles in `dist/styles.css`, and page copy in `dist/index.html`. Prices are illustrative USD prices. All product art is original inline-style SVG in `dist/assets/`.

This is a frontend portfolio demo. No real orders, payments, emails, inventory reservations, or deliveries occur. Checkout details are not sent to a server or stored persistently. A production store needs a backend, payment provider, inventory controls, shipping/tax rules, and verified product/allergen information. No third-party tracking or runtime dependencies are used.
