# Seen It config

This `config.json` is read by the Seen It browser extension. It tells the extension where to find
posters, rows and buttons on streaming sites, so a site layout change can be fixed without an
extension update.

It contains selectors and patterns only: no code and no user data. Chrome Web Store policy forbids
remote code, and the extension rejects anything that fails its checks.

Don't edit this repository by hand. The master copy lives in the private Seen It project
(`config/config.json`), where every change is validated before it is published here with
`npm run publish-config`.

Served at https://guspecht.github.io/seen-it-config/config.json

`privacy.html` is the extension's privacy policy (https://guspecht.github.io/seen-it-config/privacy.html),
generated from `docs/PRIVACY.md` in the private project. `fonts/` holds the bundled typefaces (OFL).
