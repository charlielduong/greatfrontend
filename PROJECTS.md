Project Showcase — Notes

How it works

- Each project should live in its own folder at the repository root and must contain an `index.html`.
- That folder will be reachable at `https://<host>/<folder-name>/` (for local preview use `python -m http.server` or `npx http-server`).

Quick steps to add a project

1. Create a new folder at the root (e.g. `new-widget/`).
2. Add an `index.html` (and optional `css/`, `js/`, `img/`) inside that folder.
3. Optionally add a brief tile to `index.html` (root) to make the project visible on the home page.

Preview

- Run: `python -m http.server 8000` inside the repo root and open `http://localhost:8000/` in your browser.

Happy building! 🎉