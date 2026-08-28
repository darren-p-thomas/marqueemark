# Changelog

This fork is based on MarqueeMark v1.3.4 by beastech. Version suffixes
identify the Electrocoin / Digital Marquee work in this repository.

## v1.3.4-electrocoin.3 — Custom-editor drag fix

- Kept the custom background visible while dragging or resizing a slot.
  The editor now moves only the slot overlay during a drag rather than
  rebuilding the canvas and reloading its background image every frame.

## v1.3.4-electrocoin.2 — Flexible Digital Marquee editor

- Renamed the configuration area to **Digital Marquee (1366 × 360)**.
- Added friendly game-title labels to the card-art selectors, with the PNG
  filename retained only when no title mapping is available.
- Simplified each card to one selector, with the live **NeoSD Pro** option
  clearly separated as a special option.
- Added selectable base-template pills.
- Added the **Custom** layout editor: upload a PNG/JPEG background, crop to
  fill or fit it to the marquee canvas, and position mini-marquee objects.
- Custom layouts support the real Neo Geo MVS slot counts: **1, 2, 4, or 6**.
  Slots can be moved and resized while retaining the correct proportions.
- Card assignments now adapt to the saved slot count.

## v1.3.4-electrocoin.1 — Electrocoin four-slot edition

- Added the wide 1366 × 360 Electrocoin display mode.
- Recreated the four-card Electrocoin presentation with a base image and
  overlaid mini-marquee windows.
- Added three fixed cartridge-art positions plus a highlighted live NeoSD Pro
  position, configurable from the Admin page.
- Added an installer path for this personal fork while preserving the
  Electrocoin service option across updates.
