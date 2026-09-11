# Ready Research website

Source for [readyresearch.org](https://www.readyresearch.org), the website of Ready Research, a research, training and communication organisation founded in 2019 by Michael Noetel, Alexander Saeri and Peter Slattery, with Emily Grundy joining the leadership team in 2020.

Ready Research has been on indefinite pause since September 2026. The site stays up as an archive of its research outputs and resources.

## What's here

A small static site with four pages plus a 404. Content is written directly into the page files; there is no CMS or markdown collection.

- `src/pages/index.astro` — home: pause notice, research projects, testimonials
- `src/pages/about.astro` — history, leadership team, volunteers, impact
- `src/pages/research.astro` — research areas and links to published papers
- `src/pages/resources.astro` — tools and guides
- `src/settings.ts` — site name, social links, SEO description
- `public/images/` — team photos, testimonials, research covers, logo
- `public/files/` — downloadable files (AMSTAR 2 checklist, charitable donations summary)

Built with [Astro](https://astro.build), Tailwind CSS and DaisyUI, starting from the [Astro Academia](https://github.com/maiobarbero/astro_academia) template.

## Running locally

Requires Node 22 (see `.nvmrc`).

```bash
npm install
npm run dev       # dev server at http://localhost:4321
npm run build     # production build into dist/
npm run preview   # serve the built site
```

## Deployment

Hosted on Vercel, which deploys automatically on every push to `main`. The domain is registered at Dynadot and its DNS is managed in Cloudflare.
