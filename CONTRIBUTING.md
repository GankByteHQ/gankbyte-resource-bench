# Contributing to Resource Bench

Resource Bench is a GankByte developer tool. Contributions should keep the tool local, readable, dependency-light, and useful to Lua, FiveM, Python, Java, web, Minecraft, RuneLite, or data developers.

## Before opening an issue

- Use the bug form for a reproducible problem.
- Use the feature form for one focused improvement.
- Include your browser, operating system, template type, and exact steps when relevant.
- Do not include private source code, credentials, server addresses, or proprietary game assets.

## Pull requests

1. Keep the change focused.
2. Do not add analytics, uploads, token promotion, or hidden network requests.
3. Preserve keyboard access, labels, reduced-motion support, and clear error messages.
4. Test every affected starter preset and inspect the generated manifest and file list.
5. Run `node --check app.js`.
6. Update the README when behaviour, starter types, or privacy details change.

## Preset changes

When adding or changing a starter type:

- Keep generated paths predictable and readable.
- Do not add a network request, analytics, upload, framework dependency, or secret.
- Include a README and licence reminder unless the preset has a documented reason not to.
- Validate names before inserting them into Lua, JavaScript, HTML, CSS, or manifest output.
- Keep the public website copy and this repository in sync.

## Ownership and licences

Contributed source code is accepted under the MIT License unless a pull request states a different compatible arrangement before merge. GankByte branding remains separate and is not granted for reuse by contributing code.
