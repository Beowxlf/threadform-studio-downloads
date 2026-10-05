# Threadform Studio for Windows

[Download Threadform Studio 0.4.0-alpha.3](https://github.com/Beowxlf/threadform-studio-downloads/releases/tag/desktop-v0.4.0-alpha.3)

An offline knitting-design engineering preview for Windows x64. No GitHub account is required to download it.

Alpha.3 includes 41 editable wardrobe starters, smoother runway proportions, construction-derived openings and seams, a bounded gravity/contact preview, counted eyelets and old-shale scallops. Versioned components, independent sizes and frozen PDF/HTML/text/CSV editions carry the design through authoring and export.

Download `Threadform.Studio_0.4.0-alpha.3_x64-setup.exe` for per-user installation. The separate `threadform-studio.exe` supports direct review on a machine with Microsoft WebView2. The installer can require an internet connection if it needs to install WebView2. Export a `.tfstudio` backup before trying the preview.

The files have **no Windows Authenticode publisher signature**. Windows may show an unknown-publisher warning. Check `SHA256SUMS.txt` and the release's `BUILD-INFO.json` to identify the downloaded files.

## Updates

Alpha.3 is a manual-download prerelease. It does not replace the existing signature-verified automatic-update feed, which remains on [alpha.1](https://github.com/Beowxlf/threadform-studio-downloads/releases/tag/desktop-v0.4.0-alpha.1). The alpha.3 release supplies no `latest.json` or detached updater signature. Installation, upgrades, uninstallation and recovery of alpha.3 remain unaccepted.

Design work stays local and offline. Update checks happen only when requested; there are no project uploads or automatic installations. The source repository remains private and no public source-code license is granted. Production source maps are excluded from alpha.3.

## Review resources and limits

The release provides an actual-capture garment gallery, reviewer/test-knitter brief, textile validation protocol, wardrobe reference pack and lace studies. Human acceptance fields remain blank.

The wardrobe contains editable construction drafts. Trousers are relaxed panels, socks are heel-less tubes, gloves have no anatomical thumb gusset and shrugs currently use a panel preview. Runway anatomy, gravity/contact, lace dimensions and fabric appearance are illustrative and unmeasured. Limited collision handling and angular neckline/shoulder areas remain. This preview does not establish calibrated drape or physical fit.

Independent technical editing, complete physical test knitting, measured materials/fit, actual printing and freelancer beta acceptance remain open. These downloads support software evaluation and review; they are not a professionally accepted collection of garment patterns. Third-party asset, font and library notices remain bundled with the application.

## Verification for this release

All 28 local Windows verification stages passed, including 592 core and nine release Rust tests. The Windows package build completed successfully. Fresh acceptance tests of this rebuilt packaged executable were not run before publication, following the owner's request to publish immediately. The older six-stage, 57-check packaged result belongs to the retained historical checkpoint.
