# Changelog

**English** · [简体中文](CHANGELOG.zh-CN.md)

## v1.1.3
- DX11 support: with DX12 off in the launcher, the panel opens and the camera works.
- Supports the DX11 executable of the CN update of 2026-11-19.
- Supports the global update of 2026-11-02 (r64785).
- New Options page (after Picture): Game view indoors and Game view while locked on hand the view back to the game in houses or while locked on, and your camera returns outdoors or when lock-on ends. Both are off by default, so the custom camera stays on as before. The parchment-sound checkbox moved to this page.
- The custom camera switches itself on when you enter the game, once every check has passed and the camera is steady (uncheck it on the Options page).

## v1.1.2
- The custom camera works on horseback: mounting keeps the current view, and it can be adjusted or switched on while riding.
- Dragging a camera slider no longer stutters, and dragging the distance in a shoulder view no longer sways sideways.
- Fixed: in 1.1.1, with ReShade/033 installed, the panel lost its scroll artwork and did not respond to the mouse.

## v1.1.1
- Fixed: the game crashed when frame generation (FSR) was turned off.
- Fixed: on some PCs the manager did not open and showed "Cannot set unknown member ... RichTextBox.IsReadOnly".
- The plugin log records details each time the panel opens, to help with reports of the panel not showing.

## v1.1.0
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

## v1.0.1
- Fixed the missing panel cursor, and the panel not showing or misplaced under some display settings.

## v1.0.0
- First stable release.
