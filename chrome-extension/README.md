# LukeTools Chrome Extension

This folder contains the unpacked Chrome extension version of LukeTools.

## Install

1. Download or clone this repository.
2. Open Chrome and go to `chrome://extensions`.
3. Turn on **Developer mode**.
4. Click **Load unpacked**.
5. Select this `chrome-extension` folder.
6. Open Wick Editor at `https://www.wickeditor.com/editor/`.
7. LukeTools should load automatically.

## Architecture

Chrome Extension -> LukeTools Bridge -> WickTools Config.json -> individual LukeTools scripts -> Wick Editor

The extension packages the current Luke Tools Local Panel Bridge locally. The bridge continues to use the existing WickTools repository for `Config.json`, icons, and individual tool files, so the working modular LukeTools system is preserved.

## Development

After changing extension files:

1. Open `chrome://extensions`.
2. Click **Reload** on LukeTools.
3. Refresh Wick Editor.
