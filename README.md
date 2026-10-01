# Devhabor Releases

Official Devhabor desktop installers and automatic update manifests.

Source code is maintained separately. This public repository contains only distribution documentation and GitHub Release assets.

## Distribution

Download published installers from [Releases](https://github.com/angrypandahu/devhabor-releases/releases).

No desktop release has been published yet.

## Maintainer notes

- Upload installers and electron-builder-generated update manifests as Release assets, not Git source files.
- Upload complete artifacts to a draft Release, validate them, then publish a stable Release.
- macOS automatic updates need the generated ZIP and latest-mac.yml in addition to the DMG installer. Windows uses NSIS and latest.yml.
- Include generated blockmaps and all files referenced by the manifests. Do not edit generated checksums.
- Keep published versions immutable; use a new version for fixes.
- Never upload credentials, environment files, build debug configuration or private source files.
- Publishing credentials stay in the release environment. Public desktop clients do not need a GitHub token.
