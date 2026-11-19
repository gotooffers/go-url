# GitHub Pages Traffic Masker

This repository hosts a static referrer-stripping gateway built with strict `no-referrer` policies so destination websites cannot read the originating traffic source (`Referer` header or `document.referrer`).

## Configuration Summary
- **Masking Mode**: `double-hop`
- **Default Destination**: `https://example.com/landing`
- **Strip Tracking Params**: Enabled (`utm_*`, `fbclid`, `gclid`, `ref`, etc.)
- **Allowed Domains**: Any valid http/https domain

## Deploy to GitHub Pages (2 Minutes)
1. Create a new public GitHub repository (e.g. `go`).
2. Upload `index.html` and `404.html` to the root of the `main` branch.
3. Open **Settings -> Pages** in your GitHub repository.
4. Under **Build and deployment**, select **Deploy from a branch**, pick `main` and `/ (root)`, then click **Save**.
5. Share your GitHub Pages URL (`https://gotooffers.github.io/go-url/`) instead of direct links to the destination website.
