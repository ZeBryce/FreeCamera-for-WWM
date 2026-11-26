# Immersive Free Camera

**English** · [简体中文](README.zh-CN.md)

A camera customization plugin for **Where Winds Meet**, by **Bryce**. Adjust your framing, save your favorite views, and switch between them in game.

**This plugin is completely free. It is released only on GitHub and my Bilibili; any paid copy is a resale.**

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
4. Start the game. The custom camera switches itself on once you are in the game world (turn this off on the Options page); press **F10** for the panel and **−** to switch it on or off.

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

### v1.2.0
- The Lighting page is open: fog & atmosphere, clouds, exposure & bloom, character lighting, sun, moon & stars and colour, 45 values for every weather and region. Save a look under My lighting presets; [ turns all lighting adjustments on or off.
- Two built-in lighting presets: clear skies and realistic.
- New colour rows that act on one range of brightness: shadow gain, midtone gain, shadow gamma and midtone gamma; plus sun disk and film shoulder.
- Lighting was tested on a few maps only; please report maps or weather where it looks wrong.
- Lighting is off in multiplayer and co-op worlds and on activity and PvP maps, where the game uses its own; it comes back in a single-player world or on the open-world map.
- The scroll has no shadow round it any more; its edge is a gilt hairline.
- With the panel open, hold the right button on the game and drag to turn the view (also in the game's own photo mode), without closing the panel.
- The portrait and photo free camera has its own switch (Preferences page): it no longer follows the custom camera switch and works everywhere, multiplayer worlds and activity and PvP maps included.
- In portrait and photo modes WASD, QE, the wheel and a right-drag move the camera with the panel open, to frame a shot while setting the lighting.
- In multiplayer worlds the custom camera switch is greyed out, as on the Lighting page.
- Fixed: after Enter froze time in portrait or photo mode, the panel did not open and WASD and the wheel did not move the camera.
- Fixed: with the panel open, Alt+Z (NVIDIA's recording overlay) showed two cursors.
- Supports the global update of 2026-11-25 and the CN update of 2026-11-25 (DX12).
- After a game update, once the author has added the new build, exit the game and click Check for updates in the manager; no reinstall needed.

### v1.1.3
- DX11 support: with DX12 off in the launcher, the panel opens and the camera works.
- Supports the DX11 executable of the CN update of 2026-11-19.
- Supports the global update of 2026-11-02 (r64785).
- New Options page (after Picture): Game view indoors and Game view while locked on hand the view back to the game in houses or while locked on, and your camera returns outdoors or when lock-on ends. Both are off by default, so the custom camera stays on as before. The parchment-sound checkbox moved to this page.
- The custom camera switches itself on when you enter the game, once every check has passed and the camera is steady (uncheck it on the Options page).

### v1.1.2
- The custom camera works on horseback: mounting keeps the current view, and it can be adjusted or switched on while riding.
- Dragging a camera slider no longer stutters, and dragging the distance in a shoulder view no longer sways sideways.
- Fixed: in 1.1.1, with ReShade/033 installed, the panel lost its scroll artwork and did not respond to the mouse.

### v1.1.1
- Fixed: the game crashed when frame generation (FSR) was turned off.
- Fixed: on some PCs the manager did not open and showed "Cannot set unknown member ... RichTextBox.IsReadOnly".
- The plugin log records details each time the panel opens, to help with reports of the panel not showing.

### v1.1.0
- Renamed Immersive Free Camera.
- The panel is now a Chinese hanging scroll, with Camera, Lighting and Picture pages that each have their own shortcuts.
- New Picture page: a cinematic letterbox with adjustable height, toggled with ]. The scroll rustles like parchment when it opens and closes; turn it off on the Picture page.
- The custom camera carries into indoor, combat, lock-on, crouch, dialogue and quest cameras; lock-on keeps the custom view.
- Drawing the bow returns to the game's own shoulder view, so the character no longer leaves the screen when drawing over the shoulder.
- Portrait (F5) and photo (F7) free camera: W/S, A/D, the wheel and Q/E move and roll; hold the right button to turn.
- New Follow inertia and Follow the body (beta), switched with ' and ; by default (rebindable on the panel).
- The Camera page is off in multiplayer and co-op worlds and on activity and PvP maps, and comes back in a single-player world or on the open-world map.
- Also: click a preset's name to apply it; a larger, draggable panel; a smoother cursor with frame generation; Alt-Tab no longer closes the panel.
- Lighting still needs testing on more maps and is not open yet.
- After future game updates the camera features turn off and ask for a plugin update; download the new version from the project page.

### v1.0.1
- Fixed the missing panel cursor, and the panel not showing or misplaced under some display settings.

### v1.0.0
- First stable release.
