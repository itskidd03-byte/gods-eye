# God's Eye

https://itskidd03-byte.github.io/gods-eye/

The living world of Johan, as an installable web app. The game is built in the
`Lost` repository under `gods-eye/` and published to `docs/gods-eye/`; this
repository copies that build and deploys it here, so this URL always serves the
latest published world (checked every 30 minutes, and on every push).

## Accounts

The game runs on static hosting only. Sign-in talks to a hosted auth API from
the browser, configured in `gods-eye/src/auth-config.js` in the Lost repository.
Without that configuration the game plays without accounts and keeps the world
on the device.
