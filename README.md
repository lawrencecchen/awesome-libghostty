# Awesome libghostty [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of projects and resources built with `libghostty` and `libghostty-vt`.

Most project sections below are clone-verified, code-level integrations.
Entries under `Claimed / In-Progress Integrations` are explicitly marked as claims or partial implementations.

Last audited: 2026-02-21

## Contents

- [Core Resources](#core-resources)
- [Terminal Apps](#terminal-apps)
- [Multiplexers and Session Tools](#multiplexers-and-session-tools)
- [Web, Editor, and Embedding Integrations](#web-editor-and-embedding-integrations)
- [Agent-Focused Workspaces](#agent-focused-workspaces)
- [Forks and Variants](#forks-and-variants)
- [Claimed / In-Progress Integrations](#claimed--in-progress-integrations)
- [Research Audit](#research-audit)
- [Contributing](#contributing)

## Core Resources

- [ghostty-org/ghostty](https://github.com/ghostty-org/ghostty) - Upstream Ghostty project and home of `libghostty`.
- [libghostty API Reference](https://libghostty.tip.ghostty.org/index.html) - Generated API docs for embedding and integration.
- [libghostty is coming](https://mitchellh.com/writing/libghostty-is-coming) - Original announcement and ecosystem context.

## Terminal Apps

- [manaflow-ai/cmux](https://github.com/manaflow-ai/cmux) - Ghostty-based macOS terminal with vertical tabs and notifications for AI coding agents.
- [blaine/fantastty](https://github.com/blaine/fantastty) - macOS terminal built on `libghostty` with workspaces, notes, and tmux-backed persistence.
- [eriklangille/clauntty](https://github.com/eriklangille/clauntty) - iOS SSH terminal using GhosttyKit with persistent sessions.
- [vivy-company/vvterm](https://github.com/vivy-company/vvterm) - Ghostty-powered SSH client for iOS/iPadOS/macOS.
- [codymullins/dotty](https://github.com/codymullins/dotty) - `.NET` terminal emulator using `libghostty`.
- [maximgorbatyuk/slothy-terminal](https://github.com/maximgorbatyuk/slothy-terminal) - Native macOS terminal for AI coding assistants powered by `libghostty`.
- [arya-s/phantty](https://github.com/arya-s/phantty) - Windows terminal renderer using `libghostty-vt`.
- [tapthaker/ghostty-android](https://github.com/tapthaker/ghostty-android) - Android terminal project using `libghostty-vt` and Jetpack Compose (early-stage).
- [sidequery/ghostree](https://github.com/sidequery/ghostree) - Agent/worktree-focused Ghostty fork.

## Multiplexers and Session Tools

- [neurosnap/zmx](https://github.com/neurosnap/zmx) - Session persistence tool that restores state via `libghostty-vt`.
- [monotykamary/openmux](https://github.com/monotykamary/openmux) - Terminal multiplexer using `libghostty-vt` for terminal state.
- [psyclyx/vanish](https://github.com/psyclyx/vanish) - Lightweight multiplexer with state preservation on top of `libghostty-vt`.
- [seruman/hauntty](https://github.com/seruman/hauntty) - Go daemon for persistent sessions backed by Ghostty VT parsing in WASM.
- [seruman/bootty](https://github.com/seruman/bootty) - Zig CLI/daemon for terminal automation with ghostty-vt.

## Web, Editor, and Embedding Integrations

- [coder/ghostty-web](https://github.com/coder/ghostty-web) - Ghostty terminal emulation for the web with xterm.js-compatible API.
- [wiedymi/restty](https://github.com/wiedymi/restty) - Web terminal library powered by `libghostty-vt`, WebGPU/WebGL2, and `text-shaper`.
- [0xBigBoss/vscode-bootty](https://github.com/0xBigBoss/vscode-bootty) - VS Code terminal extension backed by `libghostty-vt` via WASM.
- [kingwill101/dart_terminal](https://github.com/kingwill101/dart_terminal) - Dart/Flutter terminal stack with Ghostty VT bindings.
- [philipp-spiess/electron-libghostty](https://github.com/philipp-spiess/electron-libghostty) - Electron integration for embedding native `libghostty` surfaces.
- [Xuanwo/gpui-ghostty](https://github.com/Xuanwo/gpui-ghostty) - Embedded terminal stack combining GPUI with Ghostty VT core.
- [PhilipLudington/libkoda-terminal](https://github.com/PhilipLudington/libkoda-terminal) - Zig terminal library combining `libghostty-vt` with GPU text rendering.
- [arach/TermBridgeKit](https://github.com/arach/TermBridgeKit) - SwiftUI bridge for embedding GhosttyKit terminal surfaces in macOS apps.
- [Snoupix/browstty](https://github.com/Snoupix/browstty) - Zig/WASM experiment to run Ghostty terminal emulation in browsers.

## Agent-Focused Workspaces

- [loocor/codmate](https://github.com/loocor/codmate) - macOS app for managing Codex/Claude/Gemini CLI sessions with embedded Ghostty-based terminal support.
- [supabitapp/supacode](https://github.com/supabitapp/supacode) - Native macOS coding-agent command center built with `libghostty`.
- [coder/mux](https://github.com/coder/mux) - Agent multiplexer with browser and desktop UX using `ghostty-web`.
- [yangzichao/JustSessions](https://github.com/yangzichao/JustSessions) - Native macOS coding-agent session workspace with an optional libghostty renderer through libghostty-spm.

## Forks and Variants

- [parkers0405/ghostty-pixel-scroll](https://github.com/parkers0405/ghostty-pixel-scroll) - Ghostty fork focused on pixel scrolling, smooth cursor animation, and Neovim GUI rendering.
- [areai51/grip](https://github.com/areai51/grip) - Ghostty fork focused on local AI-assisted terminal workflows.
- [GhostKellz/ghostshell](https://github.com/GhostKellz/ghostshell) - Experimental Ghostty fork targeting Arch Linux + NVIDIA optimization.

## Claimed / In-Progress Integrations

- [mvfti/jupyterlab-ghostty-terminal](https://github.com/mvfti/jupyterlab-ghostty-terminal) - Claims libghostty-powered terminal support in docs/metadata; code-level Ghostty dependency is not clearly wired yet.
- [ocnc/spectty](https://github.com/ocnc/spectty) - Ghostty-inspired iOS terminal with planned/swappable `libghostty-vt` integration; current build script indicates placeholder wiring.

## Research Audit

- [2026-02-21 ecosystem audit](research/2026-02-21-audit.md) - Discovery queries, repositories reviewed, and inclusion decisions.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting additions.

## License

[MIT](LICENSE)
