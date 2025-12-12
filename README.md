# My Bot Site

This repository hosts a simple static website for **My Bot**:

- Homepage: `index.html`
- Terms of Service: `terms.html`
- Privacy Policy: `privacy.html`

These pages are intended to be used as public HTTPS URLs for bot registration (e.g., Azure Bot Service) and for user transparency.

## How to update

1. Edit `index.html`, `terms.html`, and/or `privacy.html` in the `main` branch.
2. Commit and push to `main`.
3. GitHub Actions will deploy the site using `peaceiris/actions-gh-pages`.

## Enable GitHub Pages

After the first workflow run completes:

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select branch **`gh-pages`** and folder **`/ (root)`**.

GitHub will then publish the site over HTTPS.

## Expected URLs

Once GitHub Pages is enabled, the URLs will be:

- Homepage: `https://<your-github-username>.github.io/my-bot-site/`
- Terms: `https://<your-github-username>.github.io/my-bot-site/terms.html`
- Privacy: `https://<your-github-username>.github.io/my-bot-site/privacy.html`

## Notes

- Replace `contact@example.com` in the HTML files with your real support/contact email.
- Update the “Last updated” / “Effective date” fields when you change policies.
