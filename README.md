<p align="center">
  <a href="https://n0rt0nthec4t.dev/trailbridge/"><img src="https://n0rt0nthec4t.dev/assets/trailbridge/trailbridge-art.png" alt="TrailBridge — a route across topographic contours, from a green start to a red finish" width="420"></a>
</p>

<h1 align="center">TrailBridge</h1>

<p align="center">
  <b>Your Garmin. In Finder.</b>
</p>

<p align="center">
  <a href="https://github.com/n0rt0nthec4t/TrailBridge/releases"><img src="https://img.shields.io/github/v/release/n0rt0nthec4t/TrailBridge?include_prereleases&amp;label=release&amp;color=FF9800" alt="Latest release, including betas"></a>
  <img src="https://img.shields.io/badge/macOS-15%2B-64748b?logo=apple&amp;logoColor=white" alt="Requires macOS 15 or later">
  <a href="LICENSE"><img src="https://img.shields.io/github/license/n0rt0nthec4t/TrailBridge?color=4CAF50" alt="MIT License"></a>
</p>

<p align="center">
  <a href="https://www.buymeacoffee.com/n0rt0nthec4t"><img src="https://img.shields.io/badge/Buy_Me_a_Coffee-FFDD00?logo=buymeacoffee&amp;logoColor=black" alt="Buy Me a Coffee"></a>
</p>

<p align="center">
  <a href="https://github.com/n0rt0nthec4t/TrailBridge/releases"><b>Download TrailBridge</b></a> ·
  <a href="https://n0rt0nthec4t.dev/trailbridge/">Website</a> ·
  <a href="#support">Support</a>
</p>

Browse your Garmin in Finder, copy activities to your Mac, send courses to your device, and preview routes with Quick Look. TrailBridge is a native macOS menu bar app for supported Garmin USB/MTP devices.

## Getting Started

Downloads are Developer ID-signed and notarized by Apple. Each release includes a SHA-256 checksum.

1. Download `TrailBridge-<version>.dmg` from [Releases](https://github.com/n0rt0nthec4t/TrailBridge/releases).
2. Open the disk image and drag **TrailBridge** into **Applications**.
3. Open TrailBridge. Its icon appears in the menu bar. Allow its extensions in System Settings if prompted.
4. Connect your Garmin using a USB data cable and select file-transfer mode if the device prompts you.
5. In Finder, select **TrailBridge** under **Locations** and open your Garmin's folder.

Keep TrailBridge open while browsing or transferring files. Right-click or Option-click its menu bar icon for connection details and Finder refresh actions.

### Requirements

- **macOS 15 or later**, on Apple silicon or Intel.
- A supported Garmin device that exposes a **USB MTP interface**.
- A **USB data cable**.
- Internet access for Quick Look map backgrounds. Route outlines and thumbnails can be drawn offline.

[Features](#features) · [Everyday Use](#everyday-use) · [Troubleshooting](#troubleshooting) · [Support](#support)

## Features

### Browse in Finder

Your Garmin files, alongside your Mac files. Browse folders, drag activities onto your Mac, and copy courses to your device. Create folders, rename files, and delete items where the device permits it.

<p align="center">
  <img src="https://n0rt0nthec4t.dev/assets/trailbridge/finder.png" alt="Finder showing the connected Garmin Edge 1040 and its Activities and Courses folders" width="840">
</p>

### Preview with Quick Look

Select a supported **FIT, GPX, or TCX** file and press **Space** to preview its route. FIT activities can also show distance, duration, ascent, heart rate, and power when those metrics are present. Finder thumbnails make routes recognizable without opening another app.

<p align="center">
  <img src="https://n0rt0nthec4t.dev/assets/trailbridge/quick-look.png" alt="Quick Look displaying a cycling route map and activity statistics" width="640">
</p>

### See Connection Status

The menu bar shows whether your Garmin is connected and ready for Finder, with connection details one click away.

<p align="center">
  <img src="https://n0rt0nthec4t.dev/assets/trailbridge/connection-status.png" alt="TrailBridge menu showing a green connection indicator for Garmin Edge 1040" width="400">
</p>

## Everyday Use

To save an activity, browse to `Garmin/Activities` in Finder and drag its file to a local folder. To send a course, copy a compatible file into the destination your Garmin expects, commonly `Garmin/NewFiles`.

The device determines which files and folders are writable. **Deleting an item permanently removes it from the Garmin.** There is no recoverable trash, and deleting a folder also deletes its contents.

Use the device folder's **Eject** action when finished. Reconnect USB to make it available again. Quit TrailBridge before using another app that needs the Garmin's USB connection.

## Troubleshooting

If your Garmin does not appear:

- Check that the cable supports data and the device is in its USB file-transfer mode.
- Close Garmin Express and other apps using the Garmin, then reconnect it.
- Check the menu bar status and keep TrailBridge running. USB detection can happen before the MTP session is ready.
- Allow TrailBridge's extensions in System Settings if macOS requests it.

Map backgrounds depend on internet access and map-service availability. If a background map cannot load, route outlines and thumbnails can still be drawn.

## Support

For bugs and device compatibility reports, [open an issue](https://github.com/n0rt0nthec4t/TrailBridge/issues). Include your **TrailBridge version, macOS version, Garmin model and firmware**, the steps to reproduce the problem, and what you expected to happen.

Remove personal paths, device serial numbers, and location or health data before sharing logs or screenshots. Use a synthetic example rather than attaching a personal activity file.

## About This Repository

This repository hosts TrailBridge downloads, release notes, and public support. The application's source is maintained privately. Artwork and screenshots are hosted by the [TrailBridge website](https://n0rt0nthec4t.dev/trailbridge/).

TrailBridge is not affiliated with Garmin or Apple.

Copyright © 2026 Mark Hulskamp. Licensed under the [MIT License](LICENSE).
