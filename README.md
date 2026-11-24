# healthtransformationlab.org

The website for Health Transformation Lab: open benchmarks for accurate health information, in the AI millions of
people ask and in dental records. Served by GitHub Pages at https://healthtransformationlab.org.

- `index.html`: the landing page, from the
  [project README](https://github.com/healthtransformationlab/health-transformation-lab-nlp).
- `perio-bench/`, `oral-health-bench/`, `access-bench/`: the three pitch decks, copied from `docs/edr/deck.html`,
  `docs/pitch/deck.html` and `docs/access/deck.html` in that repo by its copy-decks-to-site workflow. Edit the slides
  there and rebuild with `python docs/build_decks.py`; the workflow copies the built `deck.html` here on merge.
- `img/`: the deck covers. `edr_deck_cover.png` and `pitch_deck_cover.png` are copied from that repo;
  `access_deck_cover.png` is the AccessBench deck's first slide, rendered at 960 x 540.
- `scoring/`: how PerioBench scores work, the short form of
  [docs/scoring.md](https://github.com/healthtransformationlab/health-transformation-lab-nlp/blob/main/docs/scoring.md)
  in that repo (spec 030). Edit both together.
- `standards/`: the short form of
  [docs/standards.md](https://github.com/healthtransformationlab/health-transformation-lab-nlp/blob/main/docs/standards.md)
  (definitions, sources and reading orders side by side). Its numbers are copied from that page: update both together.
- `data-quality/`: a static data-quality page. It reads `docs/site/data-quality.json` straight from the project repo's
  `main` (raw.githubusercontent.com, cached 5 minutes), made there by `python scripts/50_dq_site.py`. No copy, no
  server, no API: it updates when that file does.
- `favicon.svg`, `favicon.ico`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `site.webmanifest`: the site
  icon, the nav bar's mark (a Libre Baskerville Bold "H", `#0F2A33` on `#F2A070`). The SVG draws the letter as a
  path, so it needs no font; the PNGs and the ICO are rendered from it.
- `CNAME`: the custom domain. DNS is on Cloudflare (four A records for `@` to GitHub Pages, `www` CNAME to
  `healthtransformationlab.github.io`, all DNS only).

Personal learning project, not affiliated with or endorsed by any employer, institution or vendor. The patients
are synthetic.
