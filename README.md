# fabDev Runtimes

This public repository stores the independent runtime catalog and runtime package releases used by [fabDev](https://github.com/JimmyWon1028/fabdev).

## Files

- `runtime-index-v1.json`: the version-controlled full runtime index.
- `docs/RUNTIME_CATALOG_V2_SPEC.md`: the catalog, package, migration, and publication contract.
- `catalog-vN` releases: immutable-by-process runtime package snapshots and a complete `fabdev-runtime-v2.json` catalog.

The stable catalog endpoint is:

```text
https://github.com/JimmyWon1028/fabdev-runtimes/releases/latest/download/fabdev-runtime-v2.json
```

Published assets are never replaced in place. A corrected package keeps its upstream version and file name, but is published under the next `catalog-vN` release with a new URL, size, and SHA-256 entry.
