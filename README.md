# indo-websit
SUMERIA furniture concept store, built with React, TypeScript and Vite for GitHub Pages.

## Features
- English and Bahasa Indonesia
- Four visual styles: Natural, Boutique, Vibrant and Luxe
- Catalogue product details, shopping bag and demo checkout
- Browser-local demo order storage and simulated payment

Product photography and dimensions come from the supplied SUMERIA catalogue. Display names, prices and delivery fees are illustrative. Demo orders remain in the current browser; no payment is collected and no order is sent to a merchant.

## Development
Node.js 24 or later.

```
npm ci
npm run dev
npm run build
```

Pushes to main build and deploy through GitHub Actions. The Vite base path is `/indo-websit/`.

## Future payments
Real payments require a separate secure backend. A future Midtrans Snap integration should create transactions server-side, recalculate totals from trusted product data, verify notifications and handle pending, expired and failed transactions. Never place server keys in frontend code or this repository.
