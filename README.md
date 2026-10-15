# malgriot.github.io

Root of the `malgriot.github.io` domain. It exists so the domain root can serve
`/.well-known/assetlinks.json`, which proves the EBBLESS Android app
(`io.github.malgriot.ebbless`) owns https://malgriot.github.io/EBBLESS/ and lets
it open full screen with no browser bar.

`.nojekyll` is required: without it GitHub Pages skips dot-folders like `.well-known`.

After the first upload to Play Console, add the **App signing key** SHA-256 from
Play Console > Test and release > App integrity to the fingerprint list. Keep
the upload key's fingerprint too.
