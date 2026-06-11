# Madhumitha M — Portfolio

A modern, single-page developer portfolio (dark theme, gradient accents, scroll
animations, typing effect) built with **plain HTML, CSS & vanilla JavaScript** —
no build step, no dependencies.

## 📂 Structure
```
Madhumitha-Portfolio/
├── index.html   # Markup & content
├── style.css    # Styling, layout, animations
├── script.js    # Typing effect, scroll reveal, counters, mobile nav
└── README.md
```

## ▶️ Run locally
Just open `index.html` in a browser, or serve it:
```bash
# any one of these
npx serve .
python -m http.server 5500
```
Then visit http://localhost:5500

## 🚀 Deploy (Firebase Hosting — same as the reference site)
```bash
npm install -g firebase-tools
firebase login
firebase init hosting      # set public directory to "." , single-page app: No
firebase deploy
```
You'll get a free `https://<project>.web.app` URL.

### Other free options
- **GitHub Pages** — push to a repo, enable Pages on the `main` branch root.
- **Netlify / Vercel** — drag-and-drop the folder or connect the repo.

## ✏️ Customize
- Update the GitHub link in `index.html` if your username changes (currently `mathimadhu`).
- Add a real profile photo by replacing the `.about__avatar` initials with an `<img>`.
- Tweak colors via the CSS variables at the top of `style.css` (`--accent`, `--accent-2`).
- Add a downloadable résumé: drop the PDF in the folder and link it from the hero CTA.
