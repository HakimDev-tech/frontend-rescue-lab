# Frontend Rescue Lab

A hands-on frontend quality teardown. The page compares a deliberately rough interface with a refined version and exposes a small interactive review checklist.

## Art direction

A technical field-notes aesthetic: warm paper, blueprint grid, precise cobalt accents, Space Grotesk display type and mono metadata. It is intentionally different from generic agency landing pages. The hero illustration is built from CSS geometry and typographic annotations, not an AI-generated abstract background.

## What the demo shows

- Before/after state switch for a small project dashboard.
- Functional navigation selection inside the demo.
- Interactive quality checklist with a live completion meter.
- Responsive behavior for narrow screens.
- Semantic controls, visible focus styles and reduced-motion support.

## Stack

Next.js App Router, React, TypeScript and custom CSS.

## Run locally

```bash
npm install
npm run dev
```

## Scope note

This is a demonstration of frontend review patterns, not a claim of measured client outcomes or an audit of a real production product.

## Deploy on Netlify

1. In Netlify, choose **Add new project → Import an existing project** and select this GitHub repository.
2. Keep the production branch as `main`.
3. The repository includes `netlify.toml`; use Node.js 22 and the Next.js runtime plugin declared there.
4. Trigger the first production deploy, then use the generated `.netlify.app` URL as the canonical site URL before adding sitemap and canonical metadata.

Every push to `main` should trigger a production deploy after the repository is connected. The repository is prepared for Netlify; this README does not imply that a Netlify site has already been created or deployed.
