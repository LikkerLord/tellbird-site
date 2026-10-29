# tellbird.org

The landing page for [Tellbird](https://github.com/LikkerLord/tellbird), served
by GitHub Pages at <https://tellbird.org>.

Plain static HTML, no build step: edit `index.html` and push. To preview
locally, run `python3 -m http.server` in this folder and open
<http://localhost:8000>.

- `assets/panel.webp` / `panel.png`: the app screenshot in the hero
- `assets/og-image.png`: preview image when the link is shared
- `assets/fonts/`: self-hosted Nunito and Inter (SIL Open Font License), so
  visitors' browsers never contact Google Fonts
- `CNAME`: tells GitHub Pages the custom domain

The download buttons look up the latest release through the GitHub API and
fall back to the release page if that fails.
