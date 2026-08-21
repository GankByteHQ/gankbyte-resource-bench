# GankByte Resource Bench

Resource Bench is a browser-only developer tool for generating readable starter projects for Lua and FiveM resources.

It is intentionally different from GankByte's games: this is a practical project scaffold, not a score chase or a procedural experiment.

## Live tool

- [Try Resource Bench](https://gankbyte.com/resource-bench.html)
- [Visit GankByte Labs](https://gankbyte.com/developers.html)
- [Report a bug](https://github.com/GankByteHQ/gankbyte-resource-bench/issues/new/choose)

## Starter types

- FiveM resource - client, server, shared config, dependencies, commands, events, exports, README, tests, and manifest.
- FiveM NUI resource - a client-controlled HTML, CSS, and JavaScript interface with a close callback.
- FiveM command resource - a server command with optional restricted permission handling.
- FiveM map resource - map manifest settings and a safe stream-folder handoff note.
- Lua module - a small reusable module with optional tests.
- Lua configuration package - structured configuration with optional tests.
- Lua test harness - a dependency-free pass/fail test starter.

## What it does

- Generates FiveM resource starters with `fxmanifest.lua`.
- Adds optional commands, network events, exports, dependencies, tests, `.gitignore`, and changelog files.
- Generates NUI, map, command, module, configuration, and test starters.
- Lets users review, copy, and download individual files or a complete text bundle locally.
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

- `index.html` - accessible tool interface.
- `app.js` - validation, presets, file generation, clipboard, and download behaviour.
- `styles.css` and `bench-enhancements.css` - standalone presentation and responsive layout.
- `.github/ISSUE_TEMPLATE/` - bug and feature forms.

## Privacy
Resource Bench has no account, analytics, network request, or server-side storage. Browser local storage is used only to remember the last local builder settings. Generated files remain in the browser unless the user copies or downloads them.

## Licence

The source code is available under the MIT License. The GankByte name, logo, mascot, and other brand assets are not included under that licence. See [LICENSE](LICENSE).
