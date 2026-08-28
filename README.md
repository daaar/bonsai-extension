# bonsai-extension

Public homepage and privacy policy for the **Bonsai — JSON Tree Viewer** Chrome
extension, served via GitHub Pages.

This repository is intentionally documentation only. It contains no extension
source code; the extension itself is developed in a separate private repository.

| File | Purpose |
|---|---|
| `index.html` | Landing page — the listing's optional Homepage URL |
| `privacy.html` | Privacy policy — **required** by the Chrome Web Store listing |
| `style.css` | Shared styling; palette copied from the extension's dark theme |
| `favicon.svg` | The Bonsai brand mark, identical to the one shipped in the extension |

## Publishing

GitHub Pages serves the `main` branch from the repository root
(Settings → Pages → Source: `main` / `/ (root)`).

**The privacy policy URL must keep working for as long as the extension is
listed.** If it starts returning 404, the Web Store listing can be taken down.
Do not rename `privacy.html` or make this repository private.

## After the extension is published

`index.html` has a placeholder call-to-action marked with a `TODO` comment.
Replace its `href` with the real Chrome Web Store URL and remove the
`aria-disabled` attribute and the "coming soon" wording.
