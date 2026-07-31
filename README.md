# Alterra Animated Email Signature

A self-hosted, table-based HTML email signature for Ryan Hofmann / Alterra Studio.

## Live installer

Open:

`https://cdn.jsdelivr.net/gh/theryanhofmann/email-signature@main/index.html`

Click **Copy signature**, then paste into Gmail under **Settings → See all settings → General → Signature**.

## How it works

- `index.html` is the copy/install page.
- `signature.html` is the clean email-safe markup.
- `assets/ryan-profile.gif` is the animated portrait.
- The remaining files in `assets/` are the wordmark, badge, and animated social icons.
- `.github/workflows/import-assets.yml` copied the current assets into this repository so the signature no longer depends on a monthly service.

The email itself uses no JavaScript. Animation is provided by normal GIF images.

## Links currently configured

- Website: `https://alterra.studio`
- Instagram: `https://www.instagram.com/theryanhofmann/`
- LinkedIn: `https://www.linkedin.com/in/theryanhofmann`
- YouTube: `https://youtube.com/alterrastudio`
- Facebook currently points to the Facebook homepage; replace it in `signature.html` and `index.html` when a specific page URL is available.
