# Portfolio 2026

A minimal, semantic portfolio site built with Astro and PicoCSS.

## Quick Start

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Structure

```
src/
├── layouts/
│   └── Layout.astro       # Main layout with PicoCSS
├── pages/
│   ├── index.astro        # Home
│   ├── about.astro        # About
│   └── work/
│       ├── index.astro    # Project listing
│       └── [slug].astro   # Individual projects
└── env.d.ts
```

## Stack

- **Astro** — Static site generation
- **PicoCSS** — Classless CSS framework
- **Semantic HTML** — Zero utility classes

## Development

The site uses semantic HTML with no utility classes. Styling is handled by PicoCSS defaults on standard HTML elements.

**To debug:**
- Check browser DevTools for rendered HTML
- All styling comes from PicoCSS CDN link in `Layout.astro`
- Edit component HTML directly — no class-based styling

## Deploy

```bash
npm run build
```

Output is in `dist/` — ready for any static host (Vercel, Netlify, etc.)
