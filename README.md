# Scoop bucket for Postext

The [postext](https://postext.dev/docs/command-line) command line for Windows x64: PDF, HTML, EPUB, page images and Word files from a `.postext` book or loose Markdown, in one self-contained executable.

```powershell
scoop bucket add postext https://github.com/drnachio/scoop-postext
scoop install postext
```

`scoop update postext` follows the releases. The manifest installs the executable that every [release](https://github.com/drnachio/postext/releases/latest) of Postext publishes, checked against its SHA256.

`bucket/postext.json` is written by the release workflow of [drnachio/postext](https://github.com/drnachio/postext) (`.github/scripts/package-managers.mjs`): change it there, not here. Its `checkver` and `autoupdate` let Scoop's own tools follow the releases too. Issues go to [drnachio/postext](https://github.com/drnachio/postext/issues).
