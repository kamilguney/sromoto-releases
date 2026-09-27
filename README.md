# Sromoto Releases

This public repository contains only signed Windows distribution files. The
application source repository remains private.

Each GitHub Release provides `release.json`, `release.sig`, and a Windows ZIP.
The application verifies the pinned Ed25519 signature and ZIP checksum before
installing an update. Do not run files from an unsigned or modified release.
