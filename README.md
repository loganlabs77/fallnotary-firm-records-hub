# Fallnotary v1.0.0 - legal workflow 2026

> **Fallnotary v1.0.0 is a browser-first legal workflow utility that brings signing oversight, research, and firm records together in one offline, single-file HTML app.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/loganlabs77/fallnotary-firm-records-hub?style=flat-square)](https://github.com/loganlabs77/fallnotary-firm-records-hub)

---

<p align="center">
  <a href="https://loganlabs77.github.io/fallnotary-firm-records-hub/">
    <img src="https://img.shields.io/badge/Download-Fallnotary%20Latest-brightgreen?style=for-the-badge" alt="Download Fallnotary">
  </a>
</p>

> **[Direct Download - Fallnotary v1.0.0](https://loganlabs77.github.io/fallnotary-firm-records-hub/)**

---

[Download Latest Build](https://loganlabs77.github.io/fallnotary-firm-records-hub/)

---

## Overview

Fallnotary is built for legal teams that need signing coordination, conflict review, and research support without depending on a hosted service or backend server. Because it ships as a single HTML file, it is simple to open, transport, and keep available in offline or locally controlled environments.

The application stores clients, advisers, signings, and firm records on the device. IndexedDB is used as the main storage layer, with localStorage available as a fallback. For audit-conscious use, it includes hashed entries, JSON chain exports, and retention-oriented record handling, which suits firms that need orderly local tracking.

---

## Key Capabilities

- Single-file HTML app that opens directly in the browser
- Local handling for signings, clients, advisers, and firm records
- Conflict scanning to help identify possible issues early
- Broadcast-channel syncing for updates across open tabs
- Advice logging with hashed audit entries
- Legal research corpus with practice areas and strategic weaves
- IndexedDB storage with localStorage fallback for broader compatibility
- Offline operation with no server, telemetry, or signup flow

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/loganlabs77/fallnotary-firm-records-hub.git
2. Open the main HTML file in a modern browser.
3. If you are using the downloadable build, launch the single file directly in the browser.

No build step is required for the basic workflow.

---

## Usage

Open the HTML file in your browser to begin working with legal workflow data locally. From there, you can:

- Add and review clients, advisers, and signing records
- Run conflict checks before proceeding with matters
- Record advice entries and export audit chains as JSON
- Use the research corpus and practice-area content during case preparation
- Keep working offline when a network connection is unavailable

Typical flow:

1. Load the app in the browser.
2. Enter firm and matter data.
3. Review conflicts and issue advice as needed.
4. Export audit records when you need a retained chain of activity.

---

## Configuration

Most settings are managed through the browser storage used by the app. Data is written to IndexedDB first, with localStorage serving as the fallback path.

If you want to reset the workspace, clear the site data for the page in your browser and reopen the file. Any retention or export process should be handled through the app's own JSON export functions.

---

## Requirements

- A modern browser with HTML and JavaScript support
- Local browser storage enabled for IndexedDB and localStorage
- Enough disk space for stored signings, audit exports, and research data
- Optional offline use after the file has been opened locally

---

## FAQ

### Does Fallnotary need a server?
No. It is intended to run locally in the browser and does not rely on a backend.

### Can it be used offline?
Yes. Offline operation is part of the workflow.

### Where is the data stored?
Data is kept in the browser using IndexedDB, with localStorage as a fallback when needed.

### How are audit records handled?
The app supports hashed audit entries and JSON export for audit chains.

### What if something is not loading correctly?
Make sure you are using a current browser, then refresh the page or clear site storage if the local data needs to be reinitialized.

### How do I get updates?
Check the repository release or download link for the latest build.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
