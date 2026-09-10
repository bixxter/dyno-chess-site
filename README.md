# Dyno Chess — landing page

The marketing site for [Dyno Chess](https://dynochess.bixxter.com/), a macOS app
that puts a chess game in the MacBook notch.

Three self-contained pages — `index.html`, `legal.html`, `thanks.html` — plus
favicons and the `og:image` a pasted link unfurls into. No build step, no
dependencies, and nothing a visitor's browser fetches from another host. The
playable board in the hero is a real (if small) chess engine in plain
JavaScript.

The app itself lives in a separate private repository, and so does the source of
truth for these files: they are copied here from its `Web/` directory. Editing
them in place means the next copy silently reverts you.
