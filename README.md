# Infinite — Desktop Releases

Public release feed for the **Infinite** desktop app for macOS.

This repository holds only signed desktop binary artifacts and updater metadata:
`.dmg`, `.zip`, and `latest-mac.yml` files produced by the desktop release
pipeline. It contains **no source code** and is not the desktop source
repository.

## Install

Use the canonical tracked download:

[Download Infinite for Mac](https://infinite.fast/download)

That endpoint routes normal installs to the current stable `.dmg` and preserves
the product's compatibility and download-tracking boundary. After the first
install, the app updates itself silently in the background; later versions are
delivered automatically on the next launch.

## Release history

Use [GitHub Releases](../../releases) when you need release history, a specific
version, or updater diagnostics. Release history is secondary to
`https://infinite.fast/download` for normal installation.

## Distribution boundary

This repository is a binary release bucket, not a source distribution. Do not
treat the release feed as the desktop source repository or attach the Infinite OS
source license to these desktop binaries.
