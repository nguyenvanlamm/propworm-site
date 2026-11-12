# propworm-site

Landing page, support and privacy pages for **Propworm**, a toy-theatre puzzle game for iPhone
(game repo: nguyenvanlamm/propworm).

Live: https://nguyenvanlamm.github.io/propworm-site/ · [support](https://nguyenvanlamm.github.io/propworm-site/support.html) · [privacy](https://nguyenvanlamm.github.io/propworm-site/privacy.html)

Plain static HTML/CSS, no build step and no JavaScript. GitHub Pages serves the `main` branch root
directly (no GitHub Actions). Fonts are self-hosted (Josefin Slab, Jost — SIL OFL 1.1, licences in
`assets/fonts/`), so the site makes no third-party requests. Screenshots are rendered from the game.

Preview locally: `python3 -m http.server 8000` and open http://127.0.0.1:8000/.
