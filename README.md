# jamaladen1.github.io

Personal site for Jamal Aden. Plain HTML + CSS, no build step.

## Publish on GitHub Pages

```bash
gh repo create Jamaladen1.github.io --public --source . --push
```

GitHub serves a repo named `<username>.github.io` at https://jamaladen1.github.io automatically
(Settings → Pages → deploy from the `main` branch if it doesn't start on its own).

## Edit

- `index.html`: all content. Each section is marked with a `<!-- ===== ... ===== -->` comment.
- `style.css`: colors are at the top (`--go`, `--java`, `--cpp`, `--kotlin`, `--accent`).
- Headshot: add `images/headshot.jpg` and follow the comment in the hero section.
- Project screenshots in `images/` come from each repo's `docs/screenshots`.
