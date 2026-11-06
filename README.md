# Portfolio

A static personal portfolio site (plain HTML + CSS, no build step), hosted on GitHub Pages.

## Customize

Search `index.html` for these placeholders and replace them:

- `Your Name`, `YN` (the logo initials), `Your City`
- `YOUR_USERNAME`, `YOUR_PROFILE`, `you@example.com`
- `TODO` comments: bio and project descriptions

Colors are CSS variables at the top of `style.css` (`--accent` changes the theme color).

## Preview locally

    python -m http.server 8000   # then open http://localhost:8000

## Publish on GitHub Pages

1. Create a public repo named `YOUR_USERNAME.github.io`.
2. Push these files to its `main` branch.
3. In the repo, open **Settings → Pages** and set the source to *Deploy from a branch*, `main`, `/ (root)`.
4. The site goes live at `https://YOUR_USERNAME.github.io` within a minute or two.
