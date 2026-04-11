# anjadhe-releases

Public distribution point for [Anjadhe](https://anjadhe.com), a privacy-first personal assistant for macOS.

This repository exists **only to host release binaries** as GitHub Release assets and to serve update manifests for `electron-updater`. No application source code lives here.

## Download

Latest release: https://github.com/ram-bakthavachalam-754/anjadhe-releases/releases/latest

Direct download (always points to the newest build):

```
https://github.com/ram-bakthavachalam-754/anjadhe-releases/releases/latest/download/Anjadhe.dmg
```

Universal binary — runs natively on both Apple Silicon and Intel Macs. Signed with a Developer ID Application certificate and notarized by Apple, so it opens cleanly with no Gatekeeper warnings on modern macOS.

## About the auto-attached "Source code" archives

GitHub automatically attaches "Source code (zip)" and "Source code (tar.gz)" links to every release — there's no way to disable them. On this repository, those archives contain **only this repo's `.gitignore` file** (around 530 bytes). They do **not** contain the Anjadhe application source, which lives in a separate private repository and is never published here.

In short: those links exist, but they're empty placeholders, not a source leak.

## Reporting issues

Found a bug, crash, or something surprising? Open an issue on the [issues tab](https://github.com/ram-bakthavachalam-754/anjadhe-releases/issues) of this repository.

For product questions and general information, see [anjadhe.com](https://anjadhe.com).

## License

The Anjadhe desktop app is distributed as a compiled binary. Source code is not publicly available.
