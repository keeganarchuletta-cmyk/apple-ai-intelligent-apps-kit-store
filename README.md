# Apple AI Intelligent Apps Kit — Storefront Demo

Live demo product page for the **Apple AI Intelligent Apps Kit**.

## Features
- Modern dark Shopify-style product landing page
- 5-step guide from the original Apple developer infographic
- Working cart (demo)
- **ChatGPT-style product assistant** with knowledge of the kit (price, steps, App Intents, Foundation Models, TestFlight, monetization, Shopify connection)
- Ready to connect real payments (Shopify Buy Button / Stripe / Gumroad)

## Deploy
Already pushed to GitHub. Deploy via Vercel, Netlify, or GitHub Pages.

## Connect real Shopify / ChatGPT
1. Create product in Shopify admin → generate Buy Button embed code → replace `addToCart()` in index.html
2. For real ChatGPT: add OpenAI API key as env var on Vercel, create a `/api/chat` serverless function, and point the chat widget to it.

## Product
Digital developer kit based on:
- Get Ready (Foundation Models + SDKs)
- Implement App Intents
- Build & Integrate (Xcode)
- Test & Refine (Labs + TestFlight)
- Submit & Monetize (App Store)

Price demo: $47 (launch)
