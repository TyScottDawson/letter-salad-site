# Letter Salad — public pages

**Moved.** The Letter Salad privacy policy now lives at
https://tylerscottdawson.com/apps/letter-salad/privacy/ (source: `src/pages/apps/letter-salad/privacy.astro`
in the tylerscottdawson-site repo). `index.html` here only redirects old links there.

Once App Store Connect points at the new address, this repository can be deleted.

This repository is public only because GitHub Pages will not serve a public site from
a private repository on a free plan. The app's own source stays private in
`TyScottDawson/letter-salad`; nothing here reveals anything about it.

## Keep it true

The policy describes what the code actually does, not what is convenient to claim:

- Solo, Computer and Timed run wholly on device and open no socket at all
- Friends games send the chef name, tile positions and room code to the game server
- The server holds rooms in memory and drops them when the last player leaves
- There are no analytics, advertising or third-party SDKs in the app

If any of that stops being true, this page has to change in the same commit.
