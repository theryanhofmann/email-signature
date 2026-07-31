# Alterra Animated Email Signature

A self-hosted, table-based HTML email signature for Ryan Hofmann / Alterra Studio.

## Live installer

After GitHub Pages is enabled for this repository, open:

`https://theryanhofmann.github.io/email-signature/`

Click **Copy rendered signature**, then paste into Gmail under **Settings → See all settings → General → Signature**.

Do not paste the HTML source code into Gmail. Gmail's signature editor accepts the rendered rich signature, not raw HTML text.

## Enable GitHub Pages once

1. Open the repository's **Settings**.
2. Select **Pages** under **Code and automation**.
3. Under **Build and deployment → Source**, choose **GitHub Actions**.
4. Wait for the **Deploy signature installer to GitHub Pages** workflow to finish.

## How it works

- `index.html` is the copy/install page.
- `signature.html` is the clean email-safe markup.
- `assets/ryan-profile.gif` is the animated portrait.
- The remaining files in `assets/` are the wordmark, badge, and animated social icons.
- `.github/workflows/pages.yml` publishes the installer as a real webpage.
- `.github/workflows/import-assets.yml` copied and optimized the current assets into this repository so the signature no longer depends on a monthly service.

The email itself uses no JavaScript. Animation is provided by normal GIF images.

## Links currently configured

- Website: `https://alterra.studio`
- Instagram: `https://www.instagram.com/theryanhofmann/`
- LinkedIn: `https://www.linkedin.com/in/theryanhofmann`
- YouTube: `https://youtube.com/alterrastudio`
- Facebook currently points to the Facebook homepage; replace it in `signature.html` and `index.html` when a specific page URL is available.
