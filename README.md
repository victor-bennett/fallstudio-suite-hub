# FallStudio v1.0.0 - creative suite hub 2026

> **FallStudio is a browser-first creative suite hub for web users, combining a single-file HTML launcher with offline, local-first routing and the current 1.0.0 release.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/victor-bennett/fallstudio-suite-hub?style=flat-square)](https://github.com/victor-bennett/fallstudio-suite-hub)

---

<p align="center">
  <a href="https://victor-bennett.github.io/fallstudio-suite-hub/">
    <img src="https://img.shields.io/badge/Download-FallStudio%20Latest-brightgreen?style=for-the-badge" alt="Download FallStudio">
  </a>
</p>

> **[Direct Download - FallStudio v1.0.0](https://victor-bennett.github.io/fallstudio-suite-hub/)**

---

[Download Latest Build](https://victor-bennett.github.io/fallstudio-suite-hub/)

---

## What FallStudio Is

FallStudio is a lean creative suite hub built to move users from an idea to the right tool without the overhead of a full desktop app collection. It is made for browser-centric use and can also run from local files, giving you a self-contained interface that stays simple to set up.

The core idea is intent-based routing for creative work. Instead of making you browse through separate applications, FallStudio relies on keyword navigation, a command palette, and built-in shortcuts to steer you toward the most relevant workflow. It suits users who want a local-first, sovereign setup with optional PWA installation.

---

## Key Capabilities

- Keyword-driven navigation that sends creative intent to the appropriate tool
- 8 single-HTML tools grouped inside one hub
- Ctrl+K command palette support
- Direct file:// execution with no installation required
- Optional PWA install for a more app-like experience
- No dependencies and no build step
- Offline keyword routing
- Local LLM and BYOK routing flows

---

## Getting Started

1. Download or clone the repository.
2. Open the primary HTML file in your browser, or serve the folder locally if that fits your setup better.
3. If you want a local launch, run a simple static server and load the app in the browser.

Example:

    git clone https://github.com/victor-bennett/fallstudio-suite-hub.git
    cd REPO
    python -m http.server 8000

Then visit:

    http://localhost:8000

If you are using the packaged single-file version, you can also open it directly from your file system.

---

## How to Use It

Begin by typing a creative task or by opening the command palette with Ctrl+K. FallStudio will map your input to the most relevant included tool so you can go from intent to action without friction.

Typical workflow:

1. Open FallStudio in a browser.
2. Enter a keyword, task, or creative goal.
3. Use the routed tool that matches the intent.
4. Install it as a PWA if you want faster repeat access.

For offline sessions, keep the local HTML file available in your browser or stored in your workspace. If you use local LLM or BYOK routing, connect your preferred local or user-supplied model settings before starting a session.

---

## Configuration Notes

FallStudio stays lightweight by keeping most behavior inside the HTML app itself rather than relying on a separate configuration layer.

If you are customizing it, look for:
- routing keywords in the main HTML file
- local LLM or BYOK connection settings
- PWA-related metadata and install prompts
- tool definitions for the included single-file apps

There is no build-time configuration required.

---

## Requirements

- A modern web browser
- HTML file access for file:// usage, or a basic static server
- Enough local storage for browser caching if you install it as a PWA
- Optional: access to a local LLM or BYOK setup if you want those routing features

No dependency installation or compile step is needed.

---

## FAQ

**How do I update FallStudio?**  
Swap in the latest release or pull the newest files from the repository, then reopen the main HTML file.

**Can I use it offline?**  
Yes. The project supports offline keyword-based routing and can run from local files.

**Does it require installation?**  
No. You can launch it directly in a browser. PWA installation is optional.

**Where are settings kept?**  
Settings live inside the app or in browser storage, depending on how you use it.

**What if a tool does not open as expected?**  
Make sure you are using a modern browser and that the HTML file or local server path is loading properly. If you changed routing keywords, confirm the keyword mappings in the app source.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
