# RDE Suite Updates

Signed Windows x64 app updates for GTA V Legacy. Single-player story mode only.

## Scope

This repository hosts the RDE Suite application and its signed update metadata. It does not host GTA game files, third-party mod bundles, private signing keys, personal settings, or logs. Third-party mod redistribution has not been approved.

## Updating

In an existing RDE Suite installation, open the installer/update view, enter `skqkwjsjsywhbd77282-arch/rde-suite-updates` as the GitHub repository, save, and check for updates. Stage the app update and reopen the app. GTA and the installed mods do not need to be reinstalled for an app-only update.

Version 1.3.2 connects previously empty update settings automatically. Custom repositories and automatic download/install preferences are preserved. The app checks while it is running; it does not install a background Windows updater service.

## Verification and Known Issues

The updater verifies release metadata with its pinned ECDSA publisher key and verifies downloaded files with SHA-256. This is separate from Windows Authenticode signing. Do not disable Windows security protections.

**The reported crash when an AH-64E Apache is hit remains under investigation. App version 1.3.2 is not an Apache damage-crash fix.** Automated and file-level checks do not prove gameplay stability. No AI population, accuracy, reaction, or weapon-strength reduction is included in this app-only release.

Read each release note before updating.
