# The Happy Batch - D2C Cookie Shop

This is a starter Next.js + Tailwind project configured for Stripe Checkout.

## Quick local run
1. `npm install`
2. create `.env.local` with the following keys:
   - STRIPE_SECRET_KEY=sk_test_xxx
   - STRIPE_WEBHOOK_SECRET=whsec_xxx
   - PUBLIC_BASE_URL=http://localhost:3000
3. `npm run dev`
4. Open http://localhost:3000

## To deploy
1. Push this repo to GitHub (upload the files)
2. Import the repo to Vercel and set environment variables
