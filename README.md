# Immersive Free Camera

**English** · [简体中文](README.zh-CN.md)

A camera customization plugin for **Where Winds Meet**, by **Bryce**. Adjust your framing, save your favorite views, and switch between them in game.

[Download](https://github.com/ZeBryce/FreeCamera-for-WWM/releases/latest) · [Changelog](CHANGELOG.md) · [YouTube](https://www.youtube.com/watch?v=tMVm-ALSlO4) · [Bilibili](https://www.bilibili.com/video/BV1xzxK6cEBJ/) · [Report an issue](https://github.com/ZeBryce/FreeCamera-for-WWM/issues)

## Features

- Adjust camera distance, horizontal offset, target height and depth offset with sliders or exact values.
- Save named presets and cycle through your preset collection.
- Edit with the mouse wheel and rebind shortcuts.
- Chinese and English interfaces, with system input method support for preset names.
- Fullscreen in-game panel and a manager for installation, updates and uninstalling.
- PC support for the Chinese and global clients; after a game update the plugin needs an update.

This adjusts the character camera; in portrait (F5) and photo (F7) modes the camera can move freely. There is no full first-person mode.

## Install

1. Download the latest **FreeCamera-for-WWM-&lt;version&gt;.zip** from [Releases](https://github.com/ZeBryce/FreeCamera-for-WWM/releases/latest) and extract it completely. Choose the release ZIP, not GitHub's source code archives.
2. Exit the game and open **FreeCamera-Manager.exe**.
3. Read and accept the usage notice, choose your language, select the game installation folder, then click **Install**.
4. Start the game. Press **F10** for the panel and **−** to enable the custom camera.

To update or uninstall, exit the game and use the manager. Updates preserve your presets and shortcuts. Detailed Chinese and English guides are included in the ZIP.

## Default controls

- **F10** — open or close the panel; **Esc** — close it.
- **−** — enable or disable the custom camera.
- **← / →** — cycle through the preset collection while the custom camera is enabled.
- **=** — enter or lock quick editing.
- **PgUp / PgDn** — select a parameter in quick editing; **mouse wheel** — adjust it.

Shortcuts can be rebound in the panel. For distance, scroll forward to move closer and backward to move farther.

## Before you use it

This is an unofficial plugin. Third-party plugins can cause crashes or account penalties; there is no ban-free guarantee. After a game update the camera features turn off; use **Check for updates** in the manager to get the new version.

After the first successful install, the manager automatically sends one install count. Connection failures do not affect installation. **Check for updates** connects to GitHub.

Free to use and share with credit to **Bryce**. No paid resale. See [LICENSE.txt](LICENSE.txt) for the full terms; third-party licenses are included in the release.

If you enjoy the plugin, a **Star** helps support continued updates.

## Changelog

### v1.1.0
- Renamed Immersive Free Camera.
- The panel is now a Chinese hanging scroll, with Camera, Lighting and Picture pages that each have their own shortcuts.
- New Picture page: a cinematic letterbox with adjustable height, toggled with ]. The scroll rustles like parchment when it opens and closes; turn it off on the Picture page.
- The custom camera carries into indoor, combat, lock-on, crouch, dialogue and quest cameras; lock-on keeps the custom view.
- Drawing the bow returns to the game's own shoulder view, so the character no longer leaves the screen when drawing over the shoulder.
- Portrait (F5) and photo (F7) free camera: W/S, A/D, the wheel and Q/E move and roll; hold the right button to turn.
- New Follow inertia and Follow the body (beta).
- The Camera page is off in multiplayer and co-op worlds and on activity and PvP maps, and comes back in a single-player world or on the open-world map.
- Also: click a preset's name to apply it; a larger, draggable panel; a smoother cursor with frame generation; Alt-Tab no longer closes the panel.
- Lighting still needs testing on more maps and is not open yet.
- After future game updates the camera features turn off and ask for a plugin update; download the new version from the project page.

### v1.0.1
- Fixed the missing panel cursor, and the panel not showing or misplaced under some display settings.

### v1.0.0
- First stable release.
