# Portfolio 2026

A fresh take on Pablo Anttila's portfolio site.

## Goals

- **Modern, minimal** — Let the work speak
- **One language** — English (wider reach, cleaner)
- **Direct voice** — First-person, present tense, human
- **Show don't tell** — Screenshots, links, code where possible
- **The story** — Designer → Developer → Senior → What's next?

## Stack (suggested)

- **Astro** — Static, fast, familiar
- **Tailwind** — Utility-first, quick to style
- **MDX** — Content with components
- **Vercel** — Deploy in seconds

## Structure

```
src/
├── pages/
│   ├── index.astro        # Landing — headline + brief + CTA
│   ├── about.astro        # The story, the human, the "why"
│   ├── work/
│   │   ├── index.astro    # Project grid
│   │   ├── [slug].astro   # Individual project pages
│   └── contact.astro      # Simple form or links
├── content/
│   └── projects/
│       ├── toca-boca.mdx
│       ├── dreamlake.mdx
│       ├── tobii.mdx
│       └── ...
├── components/
│   ├── Header.astro
│   ├── Footer.astro
│   ├── ProjectCard.astro
│   └── Timeline.astro
└── styles/
    └── global.css
```

## Content Strategy

### Landing page
Short. Punchy. No fluff.

> **Pablo Anttila**
> Frontend engineer & interface designer.
> I build web products people actually want to use.
> [See my work] [About me]

### About page
The story. Written like you're explaining to a friend at a bar:
- Started in design (Chile, branding)
- Fell into early mobile web
- Moved to Sweden, went deeper into code
- Big company work: Tobii, Dreamlake, Toca Boca
- Now: [current situation — consulting? looking? building?]
- The four languages, the cross-cultural thing
- What you care about (UX that matters, clean code, whatever is true)

### Projects
Each project needs:
- **One sentence** — What it is
- **Your role** — What you actually did
- **The interesting part** — One specific thing that was hard/cool/novel
- **Visuals** — Screenshots, video, links if live
- **Tech** — List, but not the focus

### Timeline filler (2021-2026)
Be honest. Options:
- Parental leave
- Freelance/consulting
- Sabbatical
- "Focused on family, now back and sharper"

Silence is worse than truth.

## Next Steps

1. [ ] Scaffold Astro project
2. [ ] Write landing page copy
3. [ ] Write about page (this is the hard one)
4. [ ] Port and rewrite 3-4 best projects
5. [ ] Deploy MVP
6. [ ] Add polish (animations, dark mode, etc.)

---

*Started: 2026-01-28*
