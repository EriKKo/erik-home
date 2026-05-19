# erik-home

Personal site. Static HTML/CSS, no build step.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy with GitHub Pages

1. Push to `main`.
2. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Branch: `main`, folder: `/ (root)`. Save.
4. Site will be live at `https://erikko.github.io/erik-home/` after a minute.

## Editing

- Update name, tagline, and About copy in `index.html`.
- Add real projects by editing the `<ul class="projects">` list — each `<li class="project">` is a card.
- Tweak colors in the `:root` block at the top of `styles.css` (light and dark themes both defined there).
