# VortSpec — Downloads

An **agentic development environment** for design-to-code, running on your own local Claude Code.

There are two releases. Pick one — both install as **VortSpec IDE**, so they replace each other rather than sitting side by side.

## Stable

**[Download the latest stable release →](https://github.com/royvillasana/vortspec-releases/releases/latest)**

| Build | For |
|---|---|
| [`VortSpec-IDE-mac-arm64.dmg`](https://github.com/royvillasana/vortspec-releases/releases/latest/download/VortSpec-IDE-mac-arm64.dmg) | Apple Silicon — M1 / M2 / M3 and newer |
| [`VortSpec-IDE-mac-intel.dmg`](https://github.com/royvillasana/vortspec-releases/releases/latest/download/VortSpec-IDE-mac-intel.dmg) | Intel-based Macs |

## With the live design canvas (2.0 alpha)

Start a project with no design yet, create your screens on a live canvas with the AI, and choose the framework when you export. This is an alpha: expect rough edges.

Current alpha: **2.0.0-alpha.2** — fixes canvas documents not opening in alpha.1, and shows tokens used and an estimated cost for Enterprise Claude accounts.

**[Download the canvas alpha →](https://github.com/royvillasana/vortspec-releases/releases/tag/v2.0.0-alpha.2)**

| Build | For |
|---|---|
| [`VortSpec-IDE-mac-arm64.dmg`](https://github.com/royvillasana/vortspec-releases/releases/download/v2.0.0-alpha.2/VortSpec-IDE-mac-arm64.dmg) | Apple Silicon — M1 / M2 / M3 and newer |
| [`VortSpec-IDE-mac-intel.dmg`](https://github.com/royvillasana/vortspec-releases/releases/download/v2.0.0-alpha.2/VortSpec-IDE-mac-intel.dmg) | Intel-based Macs |

The alpha updates itself from its own channel, so later alphas arrive without a new download. The `channel-alpha` release is that update feed; there is nothing to download from it by hand.

## Installing

Open the DMG and drag **VortSpec IDE** to Applications. The builds are signed with a
Developer ID certificate and notarized by Apple, so there is no security warning and
nothing to right-click.

VortSpec needs your own [Claude Code](https://claude.com/claude-code) install. It stores
no API keys and proxies no model traffic.

This repository holds **releases only** — the source lives elsewhere.

Learn more at **[royvillasana.github.io/VortSpec](https://royvillasana.github.io/VortSpec/)**.
