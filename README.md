# Website Share Kit

This folder is copied into `TenureEvidenceApp/dist/web/site` by:

```sh
TenureEvidenceApp/script/package_for_web.sh
```

The generated site includes:

- `index.html` - static landing page.
- `install.html` - styled install notes for public sharing.
- `docs.html` - guided usage documentation with screenshots.
- `privacy.html` - styled privacy notes for public sharing.
- `assets/screenshot-*.svg` - share-safe walkthrough screenshots.
- `downloads/Proofessor-macOS.zip` - zipped standalone macOS app.
- `downloads/Proofessor-source.zip` - clean source package with the empty workspace template.
- `downloads/checksums.txt` - SHA-256 checksums.
- `assets/app-icon.png` - copied from the app icon set.

Before public website distribution, sign and notarize the app with an Apple Developer ID. The app project includes `TenureEvidenceApp/DISTRIBUTION.md` and `TenureEvidenceApp/script/sign_and_notarize.sh` for that workflow.
