# Letter Salad — public pages

The privacy policy for the **Letter Salad** iOS app, served by GitHub Pages so it has
a stable public URL. App Store Connect requires one for external TestFlight testing
and for App Store review.

- Live page: https://tyscottdawson.github.io/letter-salad-site/
- Source: [`index.html`](index.html)

This repository is public only because GitHub Pages will not serve a public site from
a private repository on a free plan. The app's own source stays private in
`TyScottDawson/letter-salad`; nothing here reveals anything about it.

## Editing

Edit `index.html` and push to `main`. GitHub Pages redeploys in a minute or so.
Update the "Last updated" date at the top of the page whenever the substance changes —
the page says the edit history is public, and Git provides that.

## Keep it true

The policy describes what the code actually does, not what is convenient to claim:

- Solo, Computer and Timed run wholly on device and open no socket at all
- Friends games send the chef name, tile positions and room code to the game server
- The server holds rooms in memory and drops them when the last player leaves
- There are no analytics, advertising or third-party SDKs in the app

If any of that stops being true, this page has to change in the same commit.
