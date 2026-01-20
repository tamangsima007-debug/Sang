# Portfolio Website (template)

This is a simple static portfolio template (HTML, CSS, JS) created for Sima Lama Bomjan and ready to deploy.

How to use
1. Files (index.html, styles.css, script.js, README.md) are placed in the repository root.
2. Edit `index.html`:
   - Replace bio and project entries with your content if you want further customization.
   - Replace the Formspree action URL with your form endpoint, or remove the form and link a mailto.
3. Add your images and update the project cards with links to live demos and source repos.
4. Commit and push to GitHub (already done by this commit).

Deploy to GitHub Pages
- Option A (recommended for simplicity): Use the `docs/` folder or the repository root on the `main` branch. In your repo Settings → Pages, set the source to `main` branch / `root` (or `/docs` if you prefer).
- Option B: Publish from the `gh-pages` branch. Use a deploy tool (gh-pages npm package) or create a gh-pages branch and push the static files there.
- After publishing, your site will be available at `https://<username>.github.io/<repo>/` (or at a custom domain if you configure one).

Customization ideas
- Convert to a React/Vite site if you prefer a component-based approach.
- Add animations, dark/light mode toggle, or a blog section.
- Add analytics, SEO meta tags, and social preview images.

Contact
- The contact email in the template is `simabomjan.official@gmail.com`. Replace the Formspree endpoint in `index.html` if you have a form id.
