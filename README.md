# Rangr website

Public website for Rangr, an EV range calculator for iPhone. The app source is maintained separately in a private repository. This repository contains only static website files and approved public-facing media.

## Publishing

GitHub Pages serves `main` from `/` at:

https://deework.github.io/rangr-site/

There is no build step, package manager, third-party script, font request or analytics integration. Changes to `index.html`, `styles.css` and `assets/` are deployed by GitHub Pages after a push to `main`.

## Documents

The landing page reserves a section for support and privacy information. Those documents are intentionally not published yet. Before the App Store release:

1. Add `support/index.html` with support details and actual contact information.
2. Add `privacy/index.html` with the reviewed privacy policy.
3. Replace the “not published yet” message with links to those pages.
4. Use the resulting `/rangr-site/support/` and `/rangr-site/privacy/` URLs in App Store Connect and add policy access within the app.

Do not use this landing page's temporary document section as a completed App Store support page or privacy policy.

## Media

The screenshots and 28-second preview show the actual app. Example vehicle consumption figures are user-entered inputs, not measured specifications for a particular vehicle. The website and app are currently in preparation for the first App Store release.

To preview locally, open `index.html` in a browser. All asset references are relative, so the site also works under GitHub Pages' project path.
