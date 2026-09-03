# Repository Rules

- Use two spaces for indentation and English for code comments.
- `runtime-index-v1.json` is always the complete installable runtime index.
- Every published `fabdev-runtime-v2.json` is a complete catalog.
- Never replace or delete an asset from a published `catalog-vN` release.
- Publish a same-version corrected package under the next `catalog-vN` tag.
- Verify source metadata, file size, and SHA-256 before publication.
- Do not commit runtime archives to Git; attach them only to GitHub Releases.
