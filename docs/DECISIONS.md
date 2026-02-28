## Decision: npm vs pnpm

`pnpm` is a faster, more disk-efficient alternative to `npm` that uses a content-addressable storage system and symlinks to manage dependencies. It saves significant disk space by storing packages in a global, shared directory rather than copying them for every project. `pnpm` also enforces stricter dependency resolution, ensuring projects cannot access unlisted packages, improving reliability compared to `npm`'s flat `node_modules` structure.

**Decision**: pnpm

---
