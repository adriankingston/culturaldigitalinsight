# culturaldigitalinsight.nz

Holding page for culturaldigitalinsight.nz (and culturaldigitalinsight.co.nz).

One static page: the wordmark **cultural/digital/insight** in white on black,
sized by script to span 90% of the viewport width, cycling once per second
through four self-hosted display faces — Silkscreen, Bitcount Single,
Atomic Age, Tourney — plus a mailto link to info@culturaldigitalinsight.nz.

Built with [Astro](https://astro.build) (static output, zero client JS beyond
the page's own inline script) so the site can grow past a holding page —
the homepage lives in `src/pages/index.astro`.

- Fonts are latin-subset woff2 files from Google Fonts, served from
  `public/fonts` with immutable cache headers.
- Respects `prefers-reduced-motion` (the cycle stops on the first face).

Local dev: `npm install && npm run dev`. Build: `npm run build` (outputs `dist/`).
