<div align="center">
<img width="256" height="256" src="https://github.com/sinfulbobcat/ez-tree/blob/0fe939fc7f4a9b937baaac7cd2cf19a711194ae3/site/logo.png"/>

# ez-tree

Electron desktop wrapper of the [EZ-Tree web tool](https://eztree.dev) (by Dan Greenheck) — a simple native app for generating and copying tree-style directory listings.

[![Latest release](https://img.shields.io/github/v/release/sinfulbobcat/ez-tree)](https://github.com/sinfulbobcat/ez-tree/releases/latest) [![Actions](https://img.shields.io/badge/actions-build-blue)](https://github.com/sinfulbobcat/ez-tree/actions) [![License](https://img.shields.io/badge/license-MIT-green)](#license)
</div>
What this is
- A desktop application that packages the EZ-Tree web UI into an Electron app for local/offline use.
- Frontend is primarily HTML/CSS (see repo language breakdown). The app lets you generate a visual/text tree of a folder and copy or export the result.

Download
- Download the latest packaged builds from Releases: https://github.com/sinfulbobcat/ez-tree/releases/latest
- CI artifacts (if available) are on Actions: https://github.com/sinfulbobcat/ez-tree/actions

Features
- Familiar EZ-Tree web interface inside a native window
- Select or drag & drop folders to generate directory trees
- Copy results to clipboard (and export as text if included)
- Cross-platform packaged binaries provided via Releases/Actions (no local build instructions here)

Screenshot
- Add a screenshot to ./assets/screenshot.png to show here.
- <img width="1304" height="856" alt="image" src="https://github.com/user-attachments/assets/08c5fa64-54ac-4d89-b083-0dbe236fc110" />


Quick usage
1. Download the zip-file from [releases](https://github.com/sinfulbobcat/ez-tree/releases/latest).
2. Run `ez-tree`.
3. Use the app!

>[!TIP]
>Available in the [aur](https://aur.archlinux.org/packages/ez-tree).
>Can be installed by any aur helper, eg, paru -S ez-tree

>[!CAUTION]
>When getting it from the aur DO NOT download  `ez-tree-bin` it is an older appimage based option that is broken. Thus I made the newer `ez-tree` aur package so it works flawlessly on every arch system.

Attribution & Legal
- Original site / concept: EZ-Tree by Dan Greenheck.
- Original site URL (please confirm): https://eztree.dev
- Attribution text suggested for the About screen and README:
  - "This application is based on and includes work from EZ-Tree by Dan Greenheck (https://eztree.dev). All credit to the original author."


Contributing
- Found a bug or want a feature? Open an issue or submit a pull request.
- Keep PRs focused and include a description of the change and motivation.

License
- MIT

Support
- Issues and feature requests: https://github.com/sinfulbobcat/ez-tree/issues
- Repo: https://github.com/sinfulbobcat/ez-tree
- Author / maintainer: sinfulbobcat (GitHub)
