# Rangr website

Public website for Rangr, an EV range calculator for iPhone. The app source is maintained separately in a private repository. This repository contains only static website files and approved public-facing media.

## Publishing

GitHub Pages serves `main` from `/` at:

https://deework.github.io/rangr-site/

There is no build step, package manager, third-party script, font request or analytics integration. Changes to `index.html`, `styles.css` and `assets/` are deployed by GitHub Pages after a push to `main`.

## Documents

- `support/index.html`: calculator and profile help, troubleshooting and the public support contact.
- `privacy/index.html`: privacy policy covering on-device app data, support correspondence and GitHub Pages hosting.

The pages are linked from the home page and shared footers. They are used for these App Store Connect fields:

- Support URL: `https://deework.github.io/rangr-site/support/`
- Privacy Policy URL: `https://deework.github.io/rangr-site/privacy/`

The public support and privacy contact address is `support@dee.work`, as approved by the owner. The privacy policy describes the actual current app rather than a policy for data collection the app does not perform. Keep it up to date if SDKs, analytics, cloud storage or support practices change.

App Store submission also needs privacy-policy access within the app. Publishing this website does not add that app link automatically.

## Media

The screenshots and 28-second preview show the actual app. The preview starts with a calculation and slider adjustment, then adds a second car and changes its consumption, capacity, trip distance and charge levels. Footage plays at its original speed. Example vehicle consumption figures are user-entered inputs, not measured specifications for a particular vehicle. Rangr is available on the App Store at https://apps.apple.com/app/id6829699733. The home page links to the app using Apple’s official, unmodified English download badge, stored locally in `assets/app-store-badge.svg` from https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg. Badge use follows https://developer.apple.com/app-store/marketing/guidelines/.

To preview locally, open `index.html` in a browser. All asset references are relative, so the site also works under GitHub Pages' project path.
