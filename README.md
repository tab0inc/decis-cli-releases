# Decis CLI Releases

This repository is the public binary distribution channel for Decis CLI. The
source repository is private. All distributed software remains proprietary to
Tab0 Inc.

## Install

Install the latest signed and notarized macOS release with Homebrew:

```bash
brew install tab0inc/tap/decis-cli
```

macOS and Linux can use the standalone installer:

```bash
curl -fsSL https://github.com/tab0inc/decis-cli-releases/releases/latest/download/install.sh | sh
```

Each release includes SHA-256 checksums and an SPDX SBOM. The installer verifies
the selected archive against the published checksum before installing it.

## Security

Report vulnerabilities privately by following [`SECURITY.md`](SECURITY.md).
Do not publish credentials, access tokens, or private health data.

## License

Copyright (c) 2026 Tab0 Inc. All rights reserved. Official binary releases may
be used only under the limited terms in [`LICENSE`](LICENSE). No open-source
license is granted.
