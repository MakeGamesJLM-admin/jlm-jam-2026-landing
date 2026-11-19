# JLM JAM 2026 — landing page

Bilingual (English / Hebrew) landing page for the MakeGamesJLM Hanukkah Game Jam, Dec 8–10 2026 at Hansen House.

Live: https://makegamesjlm-admin.github.io/jlm-jam-2026-landing/ (intended to be reached via `makegamesjlm.com/jam`)

- Plain static site: `index.html`, `style.css`, `assets/` — no build step. Pushing to `main` redeploys via GitHub Pages.
- Language: toggle in the top bar; also `?lang=he` / `?lang=en`. Defaults to the visitor's browser language, and remembers the choice.
- Text: every string appears twice in `index.html`, as `<span class="en">` and `<span class="he">`.
- Artwork: layers extracted from the JLM JAM 2026 poster (`jlm-jam-2026-graphics/assets/layers`). The hero title is reassembled from those layers using the positions in the layer manifest.
- Registration form: https://forms.gle/fbEMRiPKKkjxS4aTA

Local preview: `python -m http.server 8765` in this folder, then open http://localhost:8765.
