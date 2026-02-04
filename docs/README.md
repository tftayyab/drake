# itel Explore – Mobile demo

Minimalist mobile-only demo for Shopify. Drake-inspired layout and animations.

## How to run

- Open `index.html` in a browser, or
- Serve the project root (so that `Images/` is available):  
  `npx serve ..` from inside `demo`, or open `index.html` from `c:\Tayyab\Drake-Itel\demo`.

## Features

- **Home**: Store image background, white product dots with ripple-on-load animation, pill buttons (Enter Studio style).
- **Three rooms**: Hot (blender) → itel Blender M1, Cold (underwater) → E1 Smart Watch, Floor (mobile) → S23. Each has one product dot; hover shows pill tooltip (pic 2 style), click opens the itel product link.
- **Navigation**: “Lets go hot / cold / on floor” open the room; back arrow returns to home.
- **Mobile-only**: Layout capped at 430px width, touch-friendly.

## Shopify use

- Copy the markup/CSS/JS into your theme (e.g. a section or snippet) or an app embed.
- Replace image paths with Shopify CDN or theme asset URLs (e.g. `{{ 'store.jpg' | asset_url }}`).
- Product dots and links can be driven by section settings or metafields.
