# Portfolio — Starter (HTML & CSS only)

This is a minimal, responsive portfolio starter built with HTML and CSS only. It's ready to customize with your name, projects, and colors.

Files created:
- `index.html` — main page with sections: hero, about, projects, skills, contact
- `assets/css/styles.css` — responsive styles and theme variables
- `assets/images/avatar.svg` — placeholder illustration

How to use:
1. Open `index.html` in your browser.
2. Replace `Your Name`, `you@example.com`, and project details with your own content.
3. Swap images in `assets/images/` with your own.

Deployment:
- Push this folder to a GitHub repository and enable GitHub Pages (deploy from `main` branch, root). Alternatively upload to any static host.

Customization tips:
- Edit colors in `:root` in `assets/css/styles.css`.
- Change fonts by adding a Google Fonts link in `index.html` head.

If you'd like, I can:
- Add a dark/light theme toggle (CSS only)
- Convert this into a Jekyll/Eleventy template or a React site
- Help craft better copy for each section

Customization & deployment
--------------------------

- To change theme colors edit the `:root` variables at the top of `assets/css/styles.css`.
- To change the font, add a `<link>` to Google Fonts in the `<head>` of `index.html` and update the `font-family` in `body`.
- Replace the placeholder SVG in `assets/images/avatar.svg` with your photo (use `jpg`/`png` and update the `img` `src` in `index.html`).

Deploy to GitHub Pages:

1. Create a GitHub repo and push this project.
2. In the repo settings -> Pages, choose branch `main` (or `gh-pages`) and folder `/ (root)`.
3. Wait a minute and your site will be available at `https://<your-username>.github.io/<repo>`.

Or upload the contents to Netlify, Vercel, or any static host.
