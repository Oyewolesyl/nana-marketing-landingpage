# Nana Marketing Page — Real App Assets Version

This package replaces the earlier placeholder marketing page.

It uses assets from the actual Nana frontend app:

- `logo.svg`
- `topnavlogo.svg`
- `child1.svg`
- `child2.svg`
- `inactivechildpicture.svg`
- Nana navigation icons
- Nana hamburger menu
- Nana add-child button
- Nana animation SVGs

## What was built

A one-page marketing website for the Nana product using the actual app branding and visual language.

Sections included:

1. Header with real Nana logo
2. Hero section explaining the product
3. Real-app inspired phone screen previews
4. Problem section
5. How it works section
6. Features section
7. App screens/gallery section
8. Tester feedback/reviews section
9. CTA section
10. Footer

## How this matches the app

The page uses the same core Nana palette:

- Blue: `#a8d7ff`
- Yellow: `#ffe98a`
- Neutral: `#f2e6d8`
- Red: `#ff6f61`
- Button red: `#ff776b`
- Teal: `#4fb4a6`

The page also uses the same main typography direction:

- Sora for big product/brand headings
- Nunito for app-style text and content

## How to run

Open:

```text
index.html
```

directly in the browser.

Or serve locally:

```bash
npx serve .
```

## Files

```text
nana-marketing-page/
├── index.html
├── styles.css
├── README.md
└── assets/
    ├── logo.svg
    ├── topnavlogo.svg
    ├── child1.svg
    ├── child2.svg
    ├── inactivechildpicture.svg
    ├── caregiver.svg
    ├── doctor.svg
    ├── home-active.svg
    ├── history-active.svg
    ├── history-inactive.svg
    ├── settings-active.svg
    ├── settings-inactive.svg
    ├── hamburgermenu.svg
    ├── addchildbutton.svg
    ├── ani1.svg
    ├── ani2.svg
    └── ani3.svg
```

## Deployment

You can deploy this folder separately to Vercel, Netlify, or GitHub Pages.

For Vercel:

```bash
cd nana-marketing-page
vercel
```

## Figma marketing assignment use

Use this page as the structure/content reference for the Figma marketing page.

Recommended Figma sections:

1. Hero/header
2. Product preview
3. Problem
4. How it works
5. Features
6. App screens/gallery
7. Testimonials
8. CTA
9. Footer


## Actual Live Links Implemented

The marketing page CTAs now open the real Nana deployments:

```text
Production app:
https://nana-app-frontend.vercel.app

Staging app:
https://nana-app-frontend-i28e.vercel.app

Backend health:
https://nanaappbackend.onrender.com/health
```

Updated CTA behavior:

- Header `Open Nana App` opens production.
- Header `Staging` opens staging.
- Hero primary button opens production.
- Hero secondary button opens staging.
- Final CTA opens production.
- Footer backend health link opens the backend health endpoint.
