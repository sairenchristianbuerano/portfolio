# Portfolio — Sairen Christian Buerano

Personal portfolio site for a Full Stack Engineer. Built with plain HTML, CSS, and vanilla JavaScript — no frameworks, no build step.

**Live site:** https://sairenchristianbuerano.github.io/portfolio/

## Preview locally

Open `index.html` directly in a browser, or serve it:

```sh
npx serve .
# or
python -m http.server 8000
```

## Deploy (GitHub Pages)

1. Push to `main`
2. Repo **Settings → Pages → Source: Deploy from a branch → `main` / root**
3. Site goes live at the URL above

## Customize

- **Projects** — edit the `<article class="project">` cards in `index.html` (section `03. Projects`); replace placeholder descriptions and links with real repos
- **Experience** — edit the timeline items in section `04. Experience`
- **Colors / theme** — CSS custom properties at the top of `css/style.css` (`:root`)
- **Socials** — footer links in `index.html`

## Structure

```
├── index.html      # single-page site
├── css/style.css   # dark theme, responsive layout, animations
└── js/main.js      # mobile nav, scroll-reveal, nav shadow
```
