# Villain Beating Releases

This public repository is used only for downloadable installer releases.

No website source code, application source code, or deployment notes are stored here.

Release assets must include:

- `latest.json`
- `villain-beating-<version>-mac-arm64.dmg`
- `villain-beating-<version>-mac-x64.dmg`
- `villain-beating-<version>-win-x64.exe`

The app reads update metadata from:

- https://github.com/Mixumi/linutech-studio-site/releases/latest/download/latest.json

`latest.json` is uploaded as a GitHub Release asset. It is not committed to this repository. The `notes` field in `latest.json` must contain only the version string, such as `0.1.1`.

Do not commit website files such as `index.html`, `script.js`, `styles.css`, `villain-beating/`, Cloudflare files, Wrangler cache, local handoff notes, or app source code. GitHub auto-generated Source code packages should contain only this README.

Downloads:

- https://github.com/Mixumi/linutech-studio-site/releases/tag/v0.1.1

Product page:

- https://linutechstudio.com/villain-beating/
