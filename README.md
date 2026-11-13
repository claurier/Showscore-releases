# Showscore — downloads

Builds of **Showscore** for macOS on Apple Silicon. Showscore updates itself from this page: at
start-up it downloads any newer version in the background and installs it the next time it
starts (or straight away with the green *restart to install* button).

## Install

1. Download the latest **Showscore-…-macos-arm64.zip** from
   [Releases](https://github.com/claurier/Showscore-releases/releases/latest).
2. Unzip it and move **Showscore.app** to your **Applications** folder.
3. Open it. The first time, macOS refuses because the app is not notarized: click *Done*, then
   go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.

Updates after that need nothing. To keep a machine on its current version (e.g. on a show day),
turn off *Check for updates at startup* in Showscore's Settings. *Help → Restore Previous
Version* goes back one update.

Requirements: macOS 13 or later, Apple Silicon (M1 or newer).

## Licences

Showscore includes FFmpeg (GPL v3) for video export and Qt/PyQt6; see
`Showscore.app/Contents/Resources/LICENSES/README.txt`.
