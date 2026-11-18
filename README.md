# Liye Wang

The homepage uses plain HTML and CSS. The GitHub Pages ZIP has the publishable files at its root. In the original source checkout, those files are in `dist/`.

## Edit the site

- Update the biography, research, teaching, and contact text in `index.html`.
- Adjust the typography and layout in `styles.css`.
- Replace `assets/portrait.jpg` with a square JPEG and set the portrait's `alt` attribute in `index.html` to `Liye Wang`.
- Replace `assets/cv.pdf` when your updated public CV is ready.

Open `index.html` locally to review the page.

To typeset new formulas, write the research summary in Markdown with TeX
math (for example, `$\sqrt{d}$`). Run
`pandoc --from=markdown --to=html --mathml` and replace the content of
`<p class="paper-summary">` with the generated paragraph's contents. MathML
is included in the HTML served by GitHub Pages.

## Publish on GitHub Pages

Put `index.html`, `styles.css`, and the `assets/` folder directly in the root of
the `Prince-Polo.github.io` repository. In **Settings → Pages**, select
**Deploy from a branch**, choose `main` and `/(root)`, and click **Save**.
Open [prince-polo.github.io](https://prince-polo.github.io/) after GitHub publishes
the site. If you own a custom domain, verify it with GitHub and configure its
DNS records before enabling **Enforce HTTPS**.

- [Create a GitHub Pages site](https://docs.github.com/en/pages/quickstart)
- [Verify a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/verifying-your-custom-domain-for-github-pages)
- [Configure a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)
