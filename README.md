# SynAtar Web

This folder contains a static SynAtar website scaffold.

## Setup

- Copy the company logo image to `logo.png` in this folder.
- Copy the large homepage poster image to `poster.jpg` in this folder.

## Files

- `index.html` — main website page
- `styles.css` — styling for the page

## Notes

- The homepage hero and service cards use `poster.jpg` as the background image.
- The company contact details and registration number have been updated as requested.

## Domain Deployment

To deploy this site to `synatar.co.uk` with GitHub Pages:

- Create a GitHub repository and push the contents of this folder to the `main` branch.
- The repo already includes a `CNAME` file for `synatar.co.uk`.
- GitHub Actions is configured in `.github/workflows/pages.yml` to publish the site from the repository root.
- Add your domain DNS records as required by GitHub Pages for a custom domain.

### Deploying locally

1. Place `logo.png` and `poster.jpg` in this folder.
2. Initialize the repository and commit all files.
3. Create a GitHub repository and add it as the `origin` remote.
4. Push to the `main` branch.

Example commands:

```powershell
cd "c:\Users\jalil\OneDrive\Music\Documents\GitHub\SynAtar Web"
git init
git add .
git commit -m "Initial SynAtar website"
git remote add origin https://github.com/<your-username>/synatar-web.git
git branch -M main
git push -u origin main
```

After the first push, GitHub Pages should build the site automatically.
