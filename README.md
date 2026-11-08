# TaskLoom releases

This repository contains **compiled release artifacts only** for the TaskLoom
Obsidian plugin. The source code is private.

- `manifest.json` — plugin manifest
- `main.js` — compiled plugin bundle
- `styles.css` — plugin styles

## Install manually

1. Download the three files from the latest release.
2. Put them in `<your-vault>/.obsidian/plugins/taskloom/`.
3. Restart Obsidian, then enable **TaskLoom** under Settings → Community plugins.

## Install with BRAT

Add `ADE150/taskloom-releases` in BRAT and choose TaskLoom. BRAT reads the
latest GitHub release.

## Versioning

The release tag, release title and `manifest.json` version are the same
`x.y.z` value. This plugin does not self-update; use BRAT or install a new
release manually.

## License

Proprietary; see `LICENSE`. The compiled artifacts may be installed for
personal use. Redistribution or reverse engineering is not permitted.
