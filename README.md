# DeerCityAI

Personal website for **deercityai.com**, designed for GitHub Pages.

## Quick start

1. Create a GitHub repository, for example:
   `deercityai`

2. Upload these files to the repository root:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `CNAME`

3. In GitHub:
   **Settings → Pages → Build and deployment → Deploy from a branch**

4. Select:
   - Branch: `main`
   - Folder: `/ (root)`

5. Point your custom domain DNS to GitHub Pages.

## Custom domain

The included `CNAME` file contains:

    deercityai.com

For the apex domain (`deercityai.com`), create these DNS A records:

    185.199.108.153
    185.199.109.153
    185.199.110.153
    185.199.111.153

For `www.deercityai.com`, create a CNAME record pointing to:

    YOUR_GITHUB_USERNAME.github.io

Then in GitHub Pages settings, enter:

    deercityai.com

and enable **Enforce HTTPS** once GitHub finishes issuing the certificate.

## Customize before publishing

Search and replace these placeholders in `index.html`:

- `https://github.com/`
- `https://www.linkedin.com/`
- `https://scholar.google.com/`
- `your.email@example.com`

You can also replace the selected projects/publications with exact URLs.

## Recommended repository name

Either:

- `YOUR_GITHUB_USERNAME.github.io` for a user-level site, or
- `deercityai` for a project repository using the custom domain.

With a custom domain, both work.
