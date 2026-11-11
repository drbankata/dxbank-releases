# Dxbank releases

Signed update files for Dxbank, read by **Dxbank Setup** ("Check for updates") at the labs.

- `index.json`: the list of the newest update for each edition, signed in `index.sig` with the seller's key.
- `files/*.bankupdate`: the update files, each signed on its own.

Dxbank Setup uses a file only when both signatures check out. This repository holds no code, no keys and no lab data.
Published with `release.ps1` from the Dxbank source.
