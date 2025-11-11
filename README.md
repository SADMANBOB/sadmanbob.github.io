# C&G Inspections — Static Site (GitHub Pages Ready)

This is a static website for a California home inspector. It’s ready to deploy on GitHub Pages.

## How to Deploy
1. Create a new repo named `your-username.github.io` (for a user site) or any repo name (for a project site).
2. Upload these files to the root of the repo.
3. In GitHub: Settings → Pages → Build and deployment → Source = `Deploy from a branch`, Branch = `main` (or `master`) / `/ (root)`.
4. Wait 1–2 minutes, then open the Pages URL GitHub shows.
5. (Optional) Add a custom domain under Settings → Pages. Add a DNS CNAME record pointing your domain to `your-username.github.io`.

## Structure
- `index.html` — Home page
- `services.html`, `report.html`, `about.html`, `faq.html`, `contact.html`
- `styles/` — theme-light.css (default), theme-dark-gold.css (optional)
- `assets/images/` — hero + icons

## Notes
- Google Sites embed blocks aren’t used here; everything is standard HTML/CSS.
- The contact form is static; use a service like Formspree or FormSubmit, or swap it for a Google Form link/button.
- To switch to the dark/gold look, edit the `<link rel="stylesheet" href="./styles/theme-light.css">` line in each page to `theme-dark-gold.css`.
