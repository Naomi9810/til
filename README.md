# Sijia's pixelboba teahouse

Static project and notes homepage for thoughts on AI, infrastructure, and
digital experiences. Published with GitHub Pages.

The site is intentionally lightweight: no Node build step, no generated content,
and no copied starter posts. Everything needed to render the page is committed
directly in this repository.

## Contents

- `index.html` - main project page
- `assets/style.css` - sky-blue visual theme and responsive layout
- `assets/logo.svg` - small pixelboba mark used in the header
- `.github/workflows/publish.yml` - publishes the static files to GitHub Pages

## Local Preview

```sh
python3 -m http.server 5173
```

Then open:

```text
http://localhost:5173/
```

## Publish

Push changes to `main`. The GitHub Actions workflow publishes the repository
root to the `gh-pages` branch.
