# GankByte Resource Bench

Resource Bench is a browser-only developer tool for generating readable starter projects for Lua, FiveM, Python, JavaScript, TypeScript, Java, Minecraft, and SQL.

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
- Python utility - a `pyproject.toml` package with a CLI entry point and optional `unittest` starter.
- JavaScript tool - an ESM Node utility with an optional Node assertion test.
- TypeScript tool - a strict Node/TypeScript starter with build configuration and optional test.
- Java desktop/app starter - a Gradle application with a configurable package, class, and Java toolchain.
- Minecraft plugin starter - a Gradle Paper API plugin skeleton with `plugin.yml` and a JavaPlugin class.
- RuneLite plugin starter - a Gradle RuneLite client plugin skeleton with a configurable API version and plugin descriptor.
- SQL migration starter - PostgreSQL/Supabase, SQLite, or MySQL table migration with an optional development seed.

## What it does

- Generates FiveM resource starters with `fxmanifest.lua`.
- Adds optional commands, network events, exports, dependencies, tests, `.gitignore`, and changelog files.
- Generates NUI, map, command, module, configuration, and test starters.
- Generates language-specific build files, package metadata, migrations, plugin descriptors, and runtime entry points.
- Lets users filter files, review, copy, and download individual files, a complete text bundle, or a ZIP locally.
- Keeps all configuration and generated code in the browser.

## What it does not do

- It does not upload code or files.
- It does not install a resource on a server.
- It does not validate framework-specific APIs.
- It does not choose a licence for your work.
- It does not install language runtimes, Java/Gradle, Node packages, Minecraft servers, or database engines.
- It does not replace testing in a real project environment.

## Run locally

Serve the folder from a local web server:

```powershell
py -m http.server 8000
```

Open <http://localhost:8000>.

## Project structure

- `index.html` - accessible tool interface.
- `app.js` - validation, presets, file generation, filtering, clipboard, ZIP, and download behaviour.
- `styles.css` and `bench-enhancements.css` - standalone presentation and responsive layout.
- `.github/ISSUE_TEMPLATE/` - bug and feature forms.

## Privacy
Resource Bench has no account, analytics, network request, or server-side storage. Browser local storage is used only to remember the last local builder settings. Generated files remain in the browser unless the user copies or downloads them.

## Licence

The source code is available under the MIT License. The GankByte name, logo, mascot, and other brand assets are not included under that licence. See [LICENSE](LICENSE).
