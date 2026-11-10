# UEIsBad-DigitalEuro

> **This repository is frozen.** The site is complete and will not receive
> further modifications. Facts were last verified in November 2026.

A single self-contained HTML page — the **Digital Euro Dossier** — a civic
and technical awareness dossier on the EU's proposed digital euro / retail
CBDC. Available in English, French, German, Italian and Spanish via an
in-page language switcher. Everything is in one file, with no build step.

## What's inside

- **Overview** — the November 2026 status update, the European Parliament
  vote scoreboard, and eight "did you know" fact cards.
- **Legal status** — the three clocks of the file (legislation, ECB
  preparation, monetary-policy decision), the adopted-vs-open breakdown,
  promises vs criticisms, and a full 2021–2029 timeline.
- **Technical dossier** — how wallets, holding limits, offline mode,
  waterfall accounts and central infrastructure would work, with the main
  privacy and financial-stability failure modes.
- **Privacy & resilience manual** — three tiers of cash-first protection,
  practical alternatives to single-rail dependence, and categorized
  "use / avoid" guidance.
- **Take action** — a ready-made message for decision-makers, petitions,
  related projects and primary sources.

## Usage

This is a static, single-file site: open `index.html` directly in a browser,
or host it on any static file host (GitHub Pages, Netlify, a plain web
server). There is no server-side component and no build process. Append
`?lang=fr` (or `de`, `it`, `es`) to the URL to force a language; the choice
is also remembered via `localStorage`.

The site works fully offline except for the optional web-font import and
external links. All interactive widgets are rendered client-side with no
external dependencies.

## Data & accuracy

Vote counts, dates, holding-limit discussions, pilot details and Council or
Parliament positions are editorial and were accurate as of November 2026,
the date noted in the page itself. The trilogue is still moving — always
check the linked primary sources for anything time-sensitive. This is a
civic-awareness dossier, not legal, financial or monetary-policy advice.

## License

MIT — see [LICENSE.md](LICENSE.md).
