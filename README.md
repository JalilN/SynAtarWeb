# SynAtar Web

Static website for SynAtar, a UK-based geoscience and subsurface consultancy. The site is built with plain HTML and CSS and is deployed with GitHub Pages.

## Pages

- `index.html` - homepage with hero messaging and primary calls to action
- `about.html` - company overview
- `services.html` - geophysics, reservoir studies, and expertise content
- `contact.html` - contact details and company information

## Assets

- `logo.png` - SynAtar logo used in the site header
- `poster.jpg` - homepage and service imagery referenced by `styles.css`
- `styles.css` - shared layout, typography, colors, and responsive styling

Keep image filenames lowercase as referenced in the HTML and CSS. GitHub Pages is case-sensitive, so `poster.jpg` and `Poster.jpg` are treated as different files after deployment.

## Local Preview

Because this is a static site, you can open `index.html` directly in a browser. For a closer GitHub Pages-style preview, serve the folder locally:

```powershell
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

This repository includes:

- `CNAME` configured for `synatar.co.uk`
- `.nojekyll` so GitHub Pages publishes the static files directly
- `.github/workflows/pages.yml` to deploy the repository root on pushes to `main`

To deploy updates:

```powershell
git add .
git commit -m "Update SynAtar website"
git push origin main
```

After the push, GitHub Actions publishes the site to GitHub Pages.

## Domain

The custom domain is:

```text
synatar.co.uk
```

Make sure the DNS records for the domain point to GitHub Pages and that the repository Pages settings use the same custom domain.

## Company Details

- Email: `info@synatar.co.uk`
- Phone: `+44 7712 885371`
- Location: London, UK
- Company Registration No: `17200144`
