# QBO Client Data Extractor legal site

Static pages intended to satisfy the QuickBooks Developer portal fields shown by Remi:

- End-user license agreement URL
- Privacy policy URL

Both must be public HTTPS pages. Proposed GitHub Pages URLs after approval and publication:

- `https://remiloranger.github.io/qbo-client-data-extractor-legal/eula.html`
- `https://remiloranger.github.io/qbo-client-data-extractor-legal/privacy.html`

## Status

Publisher information and current operational practices were completed on September 29, 2026. This material should receive qualified legal review before any external commercial distribution.

## Publication plan

Publication steps:

1. Run an automated placeholder/link/accessibility scan.
2. Create public repository `remiloranger/qbo-client-data-extractor-legal`.
3. Commit only these public legal pages; no application source, secrets, or client data.
4. Enable GitHub Pages from `main` root.
5. Verify both URLs return HTTP 200 over HTTPS and are readable without authentication.
6. Enter the two verified URLs in the Intuit Developer portal.

This material is a software/product draft, not legal advice. Obtain qualified legal review before relying on it for external production distribution.
