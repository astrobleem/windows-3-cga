# Front-door verification

Checked on **2026-10-27** against canonical `main` at
[`c40e380e13b6e7cc6201b1958c580fd287cf4374`](https://github.com/astrobleem/oemdisplay-tandy/commit/c40e380e13b6e7cc6201b1958c580fd287cf4374),
which merges the unified panning integration in PR #205.

## The actual public download

- Release: [windows-xt](https://github.com/astrobleem/oemdisplay-tandy/releases/tag/windows-xt), public rather than a draft.
- Asset: [CGA.ZIP](https://github.com/astrobleem/oemdisplay-tandy/releases/download/windows-xt/CGA.ZIP).
- Size when checked: **414,463 bytes**.
- SHA-256 when checked: `f66bca3c0708923e2ecd9e56fddee5d092149831d68d535e866be212d30dafe9`.
- [Catalog manifest](https://github.com/astrobleem/oemdisplay-tandy/releases/download/windows-xt/CURRENT.JSN)
  identifies source commit `c40e380e13b6e7cc6201b1958c580fd287cf4374`.
- [Catalog checksums](https://github.com/astrobleem/oemdisplay-tandy/releases/download/windows-xt/CURRENT.SHA).

The downloaded ZIP's hash matches its release identity and catalog checksum.
Inspection found root `SETUP.EXE`, `README.TXT` and the expanded `CGA/` folder.
It contains `CGA100.DRV`, `CGAPAN.DRV`, `CGA320.DRV`, `CGA640.DRV`, fonts,
grabber, artwork and the current panning helpers, including `PANCFG.EXE`.
Its included README documents all four install choices and native DOS setup.
No emulator was launched for this front-door work.

This confirms that the README's panning instructions refer to a shipped public
asset, rather than a source-only or unpublished feature. Fixed-mode window
movement and CGAPAN's larger framebuffer are described separately.

## Keeping this page honest

Installation links intentionally follow the canonical current `windows-xt`
release. The hash above is a dated verification record, not a promise that a
moving current asset will keep the same bytes. For current identities, use
the release's current manifest and checksum file.

When updating this page, check the public asset's own README and members,
the current CGA guide, and the capture provenance. Keep software changes,
release management and issue reports in the canonical project. Describe
emulator evidence as emulator evidence and preserve each reused capture's
scope. The canonical component notices remain authoritative for the software.
