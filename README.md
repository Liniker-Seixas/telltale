# Telltale: public pages

The privacy policy and support pages for Telltale, an iPhone and Apple
Watch app, served by GitHub Pages at
https://liniker-seixas.github.io/telltale/.

This repository holds only these pages; the app lives elsewhere. App Store
Connect links to:

- Privacy policy: https://liniker-seixas.github.io/telltale/privacy/
- Support: https://liniker-seixas.github.io/telltale/support/

`privacy.md` is generated from the app's `PRIVACY_POLICY.md`, which the app
also shows in its Settings, so never edit it here. After changing the
policy, run `telltale/scripts/publish_policy.sh <this checkout>` in the app
repository, then commit and push; Pages rebuilds in about a minute.
