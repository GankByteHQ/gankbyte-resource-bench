# GankByte Resource Bench

Resource Bench is a small, browser-only developer tool for generating readable starter files for Lua and FiveM resources.

It is intentionally different from GankByte's games: this is a practical project scaffold, not a score chase or a procedural experiment.

## Live tool

- [Try Resource Bench](https://gankbyte.com/resource-bench.html)
- [Visit GankByte Labs](https://gankbyte.com/developers.html)
- [Report a bug](https://github.com/GankByteHQ/gankbyte-resource-bench/issues/new/choose)

## What it does

- Generates FiveM resource starters with `fxmanifest.lua`.
- Generates a small Lua module starter.
- Generates a dependency-free Lua test harness.
- Includes optional client, server, and shared files for FiveM resources.
- Lets users review, copy, and download generated text locally.
- Keeps all configuration and generated code in the browser.

## What it does not do

- It does not upload code or files.
- It does not install a resource on a server.
- It does not validate framework-specific APIs.
- It does not choose a licence for your work.
- It does not replace testing in a real Lua or FiveM environment.

## Run locally

Serve the folder from a local web server:

```powershell
py -m http.server 8000
```

Open <http://localhost:8000>.

## Project structure

- `index.html` — accessible tool interface.
- `app.js` — validation, templates, file generation, clipboard, and download behaviour.
- `styles.css` — standalone presentation and responsive layout.
- `.github/ISSUE_TEMPLATE/` — bug and feature forms.

## Privacy

Resource Bench has no account, analytics, network request, or server-side storage. Browser local storage is used only to remember the last local builder settings. Generated files remain in the browser unless the user copies or downloads them.

## Licence

The source code is available under the MIT License. The GankByte name, logo, mascot, and other brand assets are not included under that licence. See [LICENSE](LICENSE).
