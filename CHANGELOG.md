# Changelog

All notable changes to Choco-Master-Menu will be documented in this file.

## [1.2] - 2026-08-05

### Added
- **Direct Setup Access**: Added a new button in the IWADs / Custom WADs section to launch `chocolate-doom.setup` directly without closing the launcher.
- **Master MIDI Pack Support**: Enabled full compatibility for the Master MIDI pack alongside the Campaign Mode for Master Levels.
- **Border Customization**: Added a third color ListBox allowing players to choose from 16 different border colors.

### Changed
- **Visual Interface (Tribute to Chocolate Doom)**: Set the default theme colors to Deep Charcoal Blue and Cyan borders as an intentional visual homage to the original `chocolate-doom.setup` text interface.
- **Eye Strain Improvements**: 
  - Replaced the harsh Navy Blue color with a more subdued Deep Charcoal Blue.
  - Replaced pure white backgrounds in list boxes and text boxes with a softer, subdued white tone.

---

## [1.1] - Previous Release (idgames)

### Added
- **Advanced Color Layout**: Added a dedicated "Color" layout tab featuring 2 independent 16-color MS-DOS CGA/EGA/VGA style selection ListBoxes to adjust backgrounds and fonts natively.
- **Brightness Selector**: Added a brightness adjuster for both background and font colors as an extra measure to prevent eye strain.
- **UI Uniformity**: Hardcoded a multi-channel `FlatAppearance` routine to synchronize Checked, MouseOver, and MouseDown button states dynamically.
- **Custom UDP Ports**: Implemented a UDP port configuration field alongside the "Local-search" button to scan local servers using custom ports (e.g., 5023).
- **Profile Integration**: Added native detection of the `chocolate-doom.cfg` file, allowing players to change their username directly from the menu.
- **Auto-Quotation Marks**: Eliminated the need to manually type quotation marks (`" "`) when entering server or player names; the launcher handles them internally.
- **Master Levels Campaign Mode**: Integrated an automated virtual campaign data streamer for Master Levels that generates temporary engine scripts natively in Windows Temp.
- **Garbage Collector**: Implemented an automated process cleanup that instantly erases all temporary virtual campaign files on exit to keep original game files safe.
- **Custom Campaign Sky**: Added a brand new sky texture featuring dark blue clouds during the second part of the Master Levels campaign.
- **Extra Parameters**: Added a dedicated text box to enter and use custom command-line parameters not present in the main UI checkboxes.
