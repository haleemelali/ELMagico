# ELMagico

A single self-contained static web page (`index.html`) that renders a full-screen HTML canvas animation of a basketball scene. All HTML, CSS, and JavaScript are inline in `index.html`; there are no external assets, dependencies, package manager, build step, or test/lint configuration.

## Cursor Cloud specific instructions

- This is a static site. There is nothing to install, build, or compile. Do not look for `package.json`, lockfiles, or a bundler — there are none.
- To run it, serve the repo root over HTTP and open `index.html` in a browser, e.g. `python3 -m http.server 8000` then visit `http://localhost:8000/`. Opening the file via `file://` also works for quick checks.
- There are no automated tests or linters. Verification is visual: confirm the canvas renders the basketball court/players/ball and that the scene animates (ball and player poses change over time).
