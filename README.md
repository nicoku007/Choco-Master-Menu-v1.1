
# Choco-Master-Menu for Chocolate Doom (Iwads, custom wads, Master Levels, Maximum Doom). NOW ON IDGAMES! https://www.doomworld.com/idgames/utils/frontends/chocomenu

![choco 1.2-1.png](https://github.com/nicoku007/Choco-Master-Menu-v1.1/blob/main/choco-1.2/choco%201.2-1.png?raw=true )

![choco 1.2-2.png](https://github.com/nicoku007/Choco-Master-Menu-v1.1/blob/main/choco-1.2/choco%201.2-2.png?raw=true )

![choco 1.2-3.png](https://github.com/nicoku007/Choco-Master-Menu-v1.1/blob/main/choco-1.2/choco%201.2-3.png?raw=true )

![choco 1.2-4.png](https://github.com/nicoku007/Choco-Master-Menu-v1.1/blob/main/choco-1.2/choco%201.2-4.png?raw=true )

![choco 1.2-5.png](https://github.com/nicoku007/Choco-Master-Menu-v1.1/blob/main/choco-1.2/choco%201.2-5.png?raw=true )

![choco 1.2-6.png](https://github.com/nicoku007/Choco-Master-Menu-v1.1/blob/main/choco-1.2/choco%201.2-6.png?raw=true )

Description: Choco-Master-Menu is a launcher I created for Chocolate Doom. My main idea was to create a  menu for the Master Levels in Chocolate Doom, because there isn't anything like  Doom-it for this source port,  but as I progressed with the launcher, I decided to add some more features such as multiplayer, the possibility  of playing with custom wads, Maximum Doom,  recording demos, etc.  The launcher was created using the C#  programming language.                       
     
 Launcher features:

Iwads: the possibility of choosing the Iwad to play without the need to enter chocolate-doom.setup to configure a specific Iwad or to have 4 folders with their respective Iwad.

Custom wads: The possibility of playing with custom WADs from the community or your own (vanilla compatible of course), you can also combine different WADs if the game requires it, for example: Back to  SaturnX "btsx_e1a.wad + btsx_e1b.wad", mix MIDI or MUS files with a WAD if a WAD has it, Hell Revealed: "HR.WAD + HRMUS.WAD" or also you can use DEH files for a WAD that uses special textures, "1k3v1a.wad +   1k3v1a.deh".
 
Master Levels Menu: The launcher has a menu for playing the Master Levels for Doom 2, eliminating the need to enter cumbersome parameters in the command line to select each map. The menu also includes the Master MIDI Pack to add musical variety to the levels. (Thanks to Peter Lawrence for allowing me to use the MIDI Pack for the menu.).

Campaign mode for Master Levels: Integrated an automated virtual campaign data streamer for the Master Levels that generates temporary engine scripts natively in Windows Temp. This completely insulates and safeguards original game files against modifications, deploying an automated garbage collector to erase all temporary virtual files instantly on process exit. The second part of the campaign features a new sky with dark blue clouds to match the launcher's default color (Deep Charcoal Blue).

Maximum Doom: The launcher has a session for Maximum Doom, the wads are separated into "maximum Doom 1" and "Maximum Doom 2" and are programmed to work only with their own  Iwad "DOOM.WAD" or "DOOM2.WAD".

Multiplayer: The menu includes options for multiplayer, cooperative deathmatch, deathmatch 2.0, private server, setting your server name, UDP port, auto join, as well as using server address. Each menu session has multiplayer options that only work for that session to prevent errors.

Player name: The launcher can detect the chocolate-doom.cfg file, allowing you to change the player name from the menu without needing to use chocolate-doom.setup.
 
The need to use quotation marks has been eliminated: Quotation marks (" ") are configured within the launcher's code, so there is no longer any need to use them when entering the server or player name.

Parameters: Each menu session has parameters to modify the game if you wish. These include: No monsters, Fast monsters, Respawn monsters, and Turbo.

Extra parameters option: a text box allows you to enter and use parameters that are not found in the launcher.

Demo: Each session has the option to record and view demos of your games; the "Demo File" button is used to search for the lmp files you have created.

Master Server and Locar Search: the possibility of viewing the Chocolate Doom master server or searching for a server in the local area.

Direct Setup Access: Added a new button in the IWADs / Custom WADs section that lets you launch chocolate-doom.setup directly. Now you can configure your controls, change music formats, and tweak settings without needing to close the launcher.

Added a dedicated "Color" layout tab featuring 2 independent 16-color MS-DOS CGA/EGA/VGA style selection ListBoxes to adjust backgrounds and fonts natively.

Note: MS-DOS colors were too bright for modern screens, so the colors were softened to avoid eye strain

A brightness selector for both background and font colors was added as an extra measure to prevent eye strain.

- New features for Choco-Master-Menu v1.2:

Border Customization: Added a third color ListBox, allowing you to choose from 16 different colors to customize your launcher's borders

The Master MIDI pack now fully works alongside the Campaign Mode for Master Levels, bringing enhanced music tracking to your gameplay.

Replaced the old Navy Blue color with Deep Charcoal Blue. Together with the new default Cyan borders, this layout is an intentional visual tribute to the iconic MS-DOS style of chocolate-doom.setup. Of course, you can still fully customize and change these colors to your liking!

Replaced the harsh pure white backgrounds of the list boxes and text boxes with a more subdued white to prevent visual fatigue during long setups.

INSTRUCTIONS:                                                                 
  
 1: All you have to do is put Choco-Master-Menu.exe in the same directory where you have chocolate-doom.exe. 
 
 2: You need the Master Levels wads, Put the Master Levels wads inside the folder called "master-wads", the folder is included in the zip file.

 3: Put the maximum doom wads corresponding to DOOM 1 inside the folder called "maximum1" and the wads  corresponding to DOOM 2 inside "maximum2". The folders are included in the  zip file.
 
 4: Put the iwads in the same directory: "DOOM.WAD, DOOM2.WAD, TNT.WAD, and PLUTONIA.WAD". This way you can select them from the menu without having to go into chocolate- doom.setup and if you have plutmidi.wad in the same directory, the menu will detect it automatically.

 Choco-Master-Menu by Nicokugame007.
 
 Credit for the Master Midi pack goes to Peter Lawrence.

