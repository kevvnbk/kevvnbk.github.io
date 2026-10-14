# kevvnbk.github.io

Personal portfolio website, hosted with GitHub Pages at https://kevvnbk.github.io

## Structure

```
.
├── index.html          # Main page (About, Projects, Experience, Contact)
├── 404.html            # Custom "not found" page
├── css/style.css       # Styles (light/dark theme, responsive)
├── js/main.js          # Theme toggle, mobile nav, footer year
└── assets/
    ├── images/         # favicon.svg, profile.jpg (add your own)
    └── docs/           # resume.pdf (add your own)
```

## Customize

1. Edit the placeholder text in `index.html` (tagline, about, projects, experience, LinkedIn link).
2. Add `assets/images/profile.jpg` (square photo works best) and `assets/docs/resume.pdf`.
3. Change colors in the `:root` block at the top of `css/style.css`.

## Preview locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

Push to the `main` branch. In the repo, go to Settings → Pages and set the source to "Deploy from a branch" → `main` / root.
