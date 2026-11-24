# Agent Sentinel

A macOS menu bar app that keeps your Mac awake while coding agents work, can protect tasks with the lid closed and can switch to a backup hotspot when Wi-Fi fails.

[Website](https://agent-sentinel-app.pages.dev/en/) · [Latest release](https://github.com/BrunoBacelar/agent-sentinel-releases/releases/latest) · [Installation guide](https://agent-sentinel-app.pages.dev/en/installation/)

## What it does

* Detects Codex, Claude Code and Cursor and configures their hooks, keeping your existing settings and making backups.
* Keeps the Mac awake only while agent tasks or tracked commands are active, and allows sleep after the last one ends.
* Optional closed-lid protection through an authorized system service, with battery and temperature limits.
* Optional switch to a backup hotspot you choose, with the password kept in the Keychain.
* Does not read conversation content. Interface in Portuguese (Portugal), English and Spanish.

## Pricing

* Seven-day trial started in the app, with no card and no automatic charge.
* Lifetime license for €15 or annual license for €5 per year, each for up to two Macs, sold through Polar.
* Basic manual sleep control stays free.

See the [terms and conditions](https://agent-sentinel-app.pages.dev/en/terms/) and the [privacy policy](https://agent-sentinel-app.pages.dev/en/privacy/).

## Requirements and known limits

* macOS 14 or later on Apple Silicon.
* The app is signed locally and is not notarized by Apple. macOS may ask you to confirm before opening it; follow the installation guide and do not disable system protections.
* Closed-lid protection was tested with an external display and charger. It is not validated on battery or without an external display.
* Joining the hotspot was tested; full Internet recovery is still being validated. The phone must share its network and have working mobile data.
* Cursor support is available but has not yet been field-tested.

## About this repository

This repository only hosts the customer installers and release notes. The application source code is not published here.

Each release includes a `SHA256SUMS` file. To check a download:

```sh
shasum -a 256 Agent-Sentinel-*-macos-arm64.zip
```

Support: bruno_bacelar@outlook.com
