# Funnelea Releases

Public, checksum-verified release artifacts for self-hosted Funnelea installations.

The application source is maintained separately. This repository exists so VPS installers and lifecycle updates can download release binaries without requiring GitHub credentials.

## Install

```sh
curl --proto '=https' --tlsv1.2 -fsSL \
  https://github.com/artemus/funnelea-releases/releases/latest/download/install.sh \
  | sudo sh
```

See each GitHub Release for Linux `amd64` and `arm64` archives, checksums, and the lifecycle manager.
