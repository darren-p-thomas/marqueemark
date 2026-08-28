# Changelog

This fork is based on MarqueeMark v1.3.4 by beastech. Version suffixes
identify the Electrocoin / Digital Marquee work in this repository.

## v1.3.4-electrocoin.5 — Layout preview and editing

- Moved custom-layout naming into a Save dialog instead of showing a name
  field in the editor.
- Added compact Preview and Edit controls next to saved layout pills.
- Preview opens a modal with the background and non-interactive slot guides;
  it closes with the X button or a click outside the modal.
- Edit reopens a saved custom layout with its background and slot positions,
  and supports renaming it on save.

## v1.3.4-electrocoin.4 — Saved layout library

- Made the layout builder independent from card-marquee assignments.
- Custom layouts now require a name and save permanently as reusable layout
  pills containing only their background and slot positions.
- Added selection and deletion of saved custom layouts; deletion never removes
  game artwork.
- Preserved an existing pre-library Custom layout by importing it on upgrade.
- Stored card assignments separately for each layout, so changing layouts does
  not overwrite another layout's selections.
- Reduced inactive pill size and contrast so only the selected layout is
  visually highlighted.
- The installer now prints the exact installed MarqueeMark version.

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
