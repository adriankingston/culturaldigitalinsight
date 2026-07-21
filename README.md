# culturaldigitalinsight.nz

Holding page for culturaldigitalinsight.nz (and culturaldigitalinsight.co.nz).

One static page: the wordmark **cultural/digital/insight** in white on black,
sized by script to span 90% of the viewport width, cycling once per second
through four self-hosted display faces — Silkscreen, Bitcount Single,
Atomic Age, Tourney — plus a mailto link to info@culturaldigitalinsight.nz.

- No build step; deploy the folder as-is (Vercel config included).
- Fonts are latin-subset woff2 files from Google Fonts, served from `/fonts`
  with immutable cache headers.
- Respects `prefers-reduced-motion` (the cycle stops on the first face).

Local preview: `python3 -m http.server 4600` in this folder.
