# Bundled export dependencies

Created November 15, 2026. These pinned browser distributions were copied from packages already installed in the containing project. The website uses only these local files; it does not request a CDN.

| File | Package/version | License | Upstream source |
|---|---|---|---|
| `jszip.min.js` | JSZip 3.10.1 | MIT or GPLv3; used under MIT | https://github.com/Stuk/jszip/tree/v3.10.1 |
| `pdf-lib.min.js` | pdf-lib 1.17.1 | MIT | https://github.com/Hopding/pdf-lib/tree/v1.17.1 |

See `JSZip-LICENSE.md` and `pdf-lib-LICENSE.md`. JSZip’s browser bundle also includes third-party notices in its source/license comments (including pako). No dependency is loaded from the network at runtime. Main entry: these files are loaded by `../index.html`; no separate run command.
