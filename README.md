# Support and privacy pages

This directory is a standalone static site. It needs no build step, JavaScript, cookies, analytics or external fonts. The support address is beat.root.dev@icloud.com. App and web privacy are described separately. Content reflects the app source on 20 October 2026.

Files to publish: `index.html`, `privacy.html`, `style.css`, `.nojekyll` and the `ru` directory. This README is deployment documentation, not a required public page.

For a project Pages site in `beatroot-dev/mtptransfer`, the expected URLs after deployment are:

- Support EN: https://beatroot-dev.github.io/mtptransfer/
- Privacy EN: https://beatroot-dev.github.io/mtptransfer/privacy.html
- Support RU: https://beatroot-dev.github.io/mtptransfer/ru/
- Privacy RU: https://beatroot-dev.github.io/mtptransfer/ru/privacy.html

These are planned URLs, not a claim that the site is published or reachable. If the site uses another repository or domain, update the App Store Connect URLs accordingly. Verify all four pages over HTTPS after deployment.

## Publishing later

The local repository remote is `beatroot-dev/mtptransfer`. Its current GitHub visibility and Pages settings have not been verified. GitHub Pages availability depends on repository visibility and account plan. Do not make the application source public merely to host these pages: a separate public support-site repository can contain only this directory's public files.

After publication is approved, use a Pages deployment that uploads only this directory's public site files. Alternatively copy them to the root of a separate Pages repository. Never deploy the project root: it contains application sources, release documents and unrelated files. Do not add provisioning profiles, certificates or private support correspondence.

No workflow is added or run by this change. No push, visibility change, Pages activation or deployment has been performed. Support and privacy URLs should be entered into App Store Connect only after they have been checked publicly.

Before publishing, the owner should approve the public privacy commitments, including support-email handling and retention. No response-time promise is included.
