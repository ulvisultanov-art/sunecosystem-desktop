# SUNECOSYSTEM modifications

This repository is a modified copy of [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk),
licensed under AGPL-3.0 (see `LICENCE`). Modified by SUN Corporation starting 2026-10-04.
Upstream base: commit e5bc204.

Changes on the `sunecosystem` branch:

- `.gitmodules` / `libs/hbb_common`: point to the modified
  [sunecosystem-hbb-common](https://github.com/ulvisultanov-art/sunecosystem-hbb-common) (app name, default server, server key).
- `Cargo.toml`: Windows product name and file description.
- `src/common.rs`: removed the fallback to the upstream public API server.

Not yet changed: executable/service file names, icons, installer metadata, About dialog attribution.
No binaries have been released from this branch yet.

"RustDesk" is a name of its respective owners; this fork is not affiliated with or endorsed by them.
