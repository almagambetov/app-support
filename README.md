# App support — Akhan Almagambetov

Public support and app-specific privacy policies for apps published by Akhan Almagambetov. Contact: texnically@gmail.com. Support is available in English, Russian, Italian, Ukrainian, French, Kazakh, and Spanish.

The shared support page covers all apps; each app must have its own privacy policy. Airelay is the first documented app. A future app must not reuse Airelay's policy unless its practices actually match and the policy explicitly covers it.

## Publish with GitHub Pages

In Settings → Pages, choose **Deploy from a branch**, **main**, **/docs**, then Save. Use HTTPS.

- Support: https://nixie.tube/app-support/support/
- Airelay privacy: https://nixie.tube/app-support/privacy/airelay/
- Policy directory: https://nixie.tube/app-support/privacy/

The account’s existing user site uses nixie.tube, so GitHub Pages inherits that custom domain for project sites. These URLs work only after Pages is enabled and deployment succeeds. Confirm the live HTTPS links before use. The shared support URL may be used for all App Store listing languages. Language links open complete static translations; no JavaScript is required. Russian, Italian, Ukrainian, French, Kazakh, and Spanish paths start with /ru/, /it/, /uk/, /fr/, /kk/, and /es/ after /app-support/.

## Maintain

Run `python3 scripts/build.py` to rebuild the static pages. The content directory contains the original localized policy/support templates; the generator fills publisher/contact/date and replaces draft-only passages with final website and email disclosures. `docs/` is the complete published site. No dependencies, forms, external fonts, analytics, advertising, cookies, or client scripts are added. GitHub, as host, may process request data under its own privacy statement, which the site links and discloses.

Before adding an app, review its actual data practices and add its own policy. Update policies when practices change. Never add signing material, user files, credentials, or private app source here.
