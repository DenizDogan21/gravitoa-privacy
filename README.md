# Gravitoa Privacy Policy

Static privacy policy page for the Gravitoa Android app. It is a single `index.html` (inline CSS, no JavaScript, no external dependencies). The empty `.nojekyll` file tells GitHub Pages to serve the files as they are.

## Before you publish

Open `index.html` and replace every `[YOUR_CONTACT_EMAIL]` with your real contact email address (it appears in several places, including the `mailto:` links).

## Publish on GitHub Pages

1. **Create the repository** on GitHub: go to <https://github.com/new>, name it `gravitoa-privacy`, set it to **Public**, and do not add a README, .gitignore or license (this folder already has its own commit).
2. **Push this folder.** From inside this folder, replace `<github-username>` with yours:

   ```bash
   git remote add origin https://github.com/<github-username>/gravitoa-privacy.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable Pages:** in the repository go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then click **Save**.
4. **Wait a minute or two**, then open your site. The final URL format is:

   ```
   https://<github-username>.github.io/gravitoa-privacy/
   ```

## Useful links for Google Play

- Privacy policy URL: `https://<github-username>.github.io/gravitoa-privacy/`
- Account deletion URL (Play Console data safety form): `https://<github-username>.github.io/gravitoa-privacy/#delete-account`

## Updating the policy

Edit `index.html`, update the "Last updated" date (in the header and the footer), then:

```bash
git add index.html
git commit -m "Update privacy policy"
git push
```
