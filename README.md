# SH Software official website

Static website for `https://suhsuh0425.github.io/`, designed to work directly with GitHub Pages.

## Local preview

Run a static HTTP server from this directory, then open the local URL in a browser.

```powershell
python -m http.server 4173
```

## Before publishing

- Confirm the public business wording and product descriptions.
- Do not add a home address, personal phone number, or a full business registration number without an explicit privacy review.
- Create a Search Console URL-prefix property for `https://suhsuh0425.github.io/`.
- Insert the exact `google-site-verification` meta tag in the `<head>` of `index.html`.
- Push to `main`, wait for GitHub Pages to complete, and verify every public URL.
- In Play Console, replace the incorrect website URL with `https://suhsuh0425.github.io/` and request website verification.

Existing app privacy-policy pages are intentionally preserved as independent HTML files.
