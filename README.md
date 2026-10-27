# Tarkov Tool

A customized Windows companion for Escape from Tarkov, based on [Tarkov MoA](https://github.com/mopocop/Tarkov-moa).

[Download Tarkov Tool](https://github.com/FindAWayFitness/Tarkov-Tool/releases/latest)

Tarkov Tool includes Flea and Ammo Scanners, automatic extract-list recognition with clickable highlights, a map with named pins, zoom favorites that preserve your player’s screen placement, customizable navigation and panels, and a keybind reminder that can import your game controls. Floating utility windows support resizing, collapse, snapping, and linked movement.

The desktop app reads local game logs for task changes and raid maps. In-game location screenshots update your position. Optional cleanup deletes newly processed location screenshots after the app acknowledges them. Item data refreshes from Tarkov.dev; armor-effectiveness and reference-distance data refresh from EFT-AMMO, with saved data available during outages.

## Install and transfer your settings

Run the Windows installer and choose your installation folder. To keep the app on E:, use `E:\Apps\TarkovTool`. App data will then live separately at `E:\Apps\TarkovToolData`, including browser storage, scanner calibration, caches, and preferences.

In the browser preview, open **Settings → Settings backup → Export settings**. In the desktop app, use **Import settings** to restore that file. This preserves your layouts, minimum window sizes, zoom favorites, pins, keybinds, and scanner calibration.

Task recovery is limited to notifications available in your saved game logs. Extract highlights identify recognized entries in the visible list; conditional exits still have their normal requirements. OCR works with English tooltips and may occasionally need a second scan.

Squad sharing requires a separate configured relay server; hosting that server is not part of this installer.

## Updates

The app uses its own signed update channel under `FindAWayFitness/Tarkov-Tool`. It does not install releases from the original MoA project. Application source is kept private; the public repository contains downloads and documentation only.

Install newer releases into the same folder to keep your saved preferences. The app checks this repository for signed updates.

## Credits

Original Tarkov MoA application by Moacir (mopocop), MIT licensed. FleaTooltip calibration utility by sammereye, MIT licensed. OCR uses Tesseract and Leptonica. Map and item data come from Tarkov.dev and their credited contributors; ammunition reference data comes from EFT-AMMO. Original license and attribution notices are retained.

This is a community application, not an official Battlestate Games product.
