# healthtransformationlab.org

The website for Health Transformation Lab: open benchmarks for accurate health information, in the AI millions of
people ask and in dental records. Served by GitHub Pages at https://healthtransformationlab.org.

- `index.html`: the landing page, from the
  [project README](https://github.com/healthtransformationlab/health-transformation-lab-nlp).
- `perio-bench/`, `oral-health-bench/`: the two pitch decks, copied from `docs/edr/deck.html` and
  `docs/pitch/deck.html` in that repo. Edit the slides there, rebuild with `python docs/build_decks.py`, and copy the
  built `deck.html` here.
- `scoring/`: how PerioBench scores work, the short form of
  [docs/scoring.md](https://github.com/healthtransformationlab/health-transformation-lab-nlp/blob/main/docs/scoring.md)
  in that repo (spec 030). Edit both together.
- `standards/`: the short form of
  [docs/standards.md](https://github.com/healthtransformationlab/health-transformation-lab-nlp/blob/main/docs/standards.md)
  (definitions, sources and reading orders side by side). Its numbers are copied from that page: update both together.
- `favicon.svg`, `favicon.ico`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `site.webmanifest`: the site
  icon, the nav bar's mark (a Libre Baskerville Bold "H", `#0F2A33` on `#F2A070`). The SVG draws the letter as a
  path, so it needs no font; the PNGs and the ICO are rendered from it.
- `CNAME`: the custom domain. DNS is on Cloudflare (four A records for `@` to GitHub Pages, `www` CNAME to
  `healthtransformationlab.github.io`, all DNS only).

Personal learning project, not affiliated with or endorsed by any employer, institution or vendor. The patients
are synthetic.
