# Toman public version policy

Static public endpoint for the Android app `com.tomanrates.app`.

Only signed public policy JSON and this small static page belong in this repository. The laptop signing key, operator state, app source, APKs, purchase receipts and credentials must never be uploaded here.

The initial policy is `off`: no version is being restricted. Signing a new file on the laptop does not publish it; replace `version-policy.json` in this repository and wait for the Pages deployment to finish. Cache and scheduled Android checks mean delivery is not instantaneous. Signed policies expire and clients verify authenticity themselves.

Enable GitHub Pages from `main` / root. Use the final HTTPS URL ending in `/version-policy.json` in the app, then rebuild and test before release.
