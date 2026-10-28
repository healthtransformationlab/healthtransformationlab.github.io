# healthtransformationlab.org

The website for Health Transformation Lab: open benchmarks for accurate health information, in the AI millions of
people ask and in dental records. Served by GitHub Pages at https://healthtransformationlab.org.

- `index.html`: the landing page, from the
  [project README](https://github.com/healthtransformationlab/health-transformation-lab-nlp).
- `perio-bench/`, `oral-health-bench/`: the two pitch decks, copied from `docs/edr/deck.html` and
  `docs/pitch/deck.html` in that repo. Edit the slides there, rebuild with `python docs/build_decks.py`, and copy the
  built `deck.html` here.
- `CNAME`: the custom domain. DNS is on Cloudflare (four A records for `@` to GitHub Pages, `www` CNAME to
  `healthtransformationlab.github.io`, all DNS only).

Personal learning project, not affiliated with or endorsed by any employer, institution or vendor. Synthetic data
only.
