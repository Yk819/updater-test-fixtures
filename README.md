# updater-test-fixtures

Public test fixture repository for GenshinRoutePlayer's file-level updater.

- manifest pointer: manifest.json
- signed fixed manifest: manifests/42.json
- object store: objects/<sha-prefix>/<sha256>
- config scripts: scripts/config/*.ps1

The manifest is signed with a test-only ECDSA P-256 key. The private key is not in this repository.
No product source, user data, cookies, or production keys belong here.
