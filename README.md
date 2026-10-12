# gdprEnforcer releases

This repository distributes **signed gdprEnforcer release binaries** only: update packages (ZIP), Windows installers, signed channel manifests (`latest.json`) and `SHA256SUMS.txt` integrity files, published as GitHub Releases.

It contains no application source, tests, build scripts, keys, credentials or client data. Release authenticity does not depend on this repository being hidden: an installed gdprEnforcer accepts a release only when its channel manifest verifies against the trust store it already holds and the artefact matches the signed size, SHA-256 and package identity.

Channels: `channel-uat` and `channel-stable` each hold the current `latest.json`; the releases they point at (`rel-<version>-<commit>`) are immutable.