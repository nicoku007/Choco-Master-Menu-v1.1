# Changelog - Choco-Master-Menu v1.1
This updated version of Choco-Master-Menu features several new characteristics.

---

## [1.1] - Official Release
### Added
1. **Advanced Color Customization:** Added a dedicated "Color" layout tab featuring 2 independent 16-color MS-DOS CGA/EGA/VGA style selection ListBoxes to adjust backgrounds and fonts natively. *(Note: MS-DOS colors were too bright for modern screens, so the colors were softened to avoid eye strain).*
2. **Anti-Fatigue Control:** A brightness selector for both background and font colors was added as an extra measure to prevent eye strain.
3. **UI Engine Uniformity:** Hardcoded a multi-channel `FlatAppearance` routine to synchronize Checked, MouseOver, and MouseDown states dynamically to achieve strict visual layout uniformity.
4. **Dynamic Local Port Scanner:** The UDP port number was implemented alongside the "Local-search" button; this way, if a friend decides to change the default port number to another one, for example (5023), you can find the local server using that same number. This option was implemented simply as an additional local search measure.
5. **Configuration Parsing:** Player name: The launcher can detect the `chocolate-doom.cfg` file, allowing you to change the player name from the menu without needing to use `chocolate-doom.setup`.
6. **Input Sanitization:** The need to use quotation marks has been eliminated. Quotation marks (" ") are configured within the launcher's code, so there is no longer any need to use them when entering the server or player name.
7. **Automated Campaign Streaming:** Campaign mode for Master Levels: Integrated an automated virtual campaign data streamer for the Master Levels that generates temporary engine scripts natively in Windows Temp. This completely insulates and safeguards original game files against modifications, deploying an automated garbage collector to erase all temporary virtual files instantly on process exit. The second part of the campaign features a new sky with dark blue clouds to match the launcher's default color (navy blue).
8. **Extended CLI Compatibility:** Extra parameters option: a text box allows you to enter and use parameters that are not found in the launcher.
