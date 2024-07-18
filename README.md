# What is VirtuaNES?

## overview
This is a NES/Famicom emulator for Win32 created by Norix. Currently, it can run many Japanese software. The menus and readme.txt are all in Japanese, so even beginners can use it with confidence. ([About the dedicated help file](http://virtuanes.s1.xrea.com/vnes_help.php "VirtuaNES.chm.
about the VirtuaNES HELP is also available). To install, simply extract the archive to a suitable folder. To uninstall, simply delete the folder (the registry is not used). VirtuaNES is freeware. The author (Norix) takes no responsibility for any damage caused by this software. Use at your own risk.

The main features of VirtuaNES are as follows:

* Equipped with a TV mode that displays the screen in the same size as a real TV (4:3 ratio).
* Equipped with pseudo TV mode. Displays scan lines. You can also adjust the brightness of the scan line color.
* TV frame display is possible. Displays frames like those found on old TVs and arcade cabinets.
* Probably a complete MMC5. Equipped with SPLIT MODE/SPLIT SCROLL. Check out the Space Defense Force (SDF) demo.
* Language plugin support. Supports various languages ​​using language plugins (plugins are required).
* Lightweight operation. I think it's one of the lightest NES emulators out there.
* The sound reproduction is excellent. You can really feel Norix's attention to detail.

In the graphics settings, turn on "TV size correction", "Pseudo TV mode", "Show TV frame", and "Show all 240 lines" to reproduce an actual TV screen on your computer monitor. [Snapshot here.](http://virtuanes.s1.xrea.com/vnes_ss.php)

## Operating environment
<table>
<tr>
<td>OS</td>
<td>Windows95 (probably IE4.0 or higher required)/98/2000/Me/XP + DirectX7.0 or higher.</td>
</tr>
<tr>
<td>CPU</td>
<td>Pentium 200MHz or higher is recommended.</td>
</tr>
<tr>
<td>MEMORY</td>
<td>Probably more than 16MByte.</td>
</tr>
<tr>
<td>VIDEO</td>
<td>DirectDraw compatible video card. Probably 4MB or more of video memory (1MB is fine depending on the video mode).</td>
</tr>
<tr>
<td>SOUND</td>
<td>DirectSound compatible sound card (required).</td>
</tr>
<tr>
<td>JOYPAD</td>
<td>It's useful to have it.</td>
</tr>
</table>

Most games run at 60FPS with a Celeron 366MHz + Matrox Millennium G400. I wonder if a Celeron 300A or so would be able to run comfortably without FrameSkip?

## Implemented features
<table>
<tr>
<td>CPU</td>
<td>All unpublished commands are implemented.</td>
</tr>
<tr>
<td>Sound</td>
<td>Supports extended sound (FDS, MMC5, VRC6, VRC7, NAMCO106, FME7). Four types of sound filters are available.</td>
</tr>
<tr>
<td>Disk System (FDS)</td>
<td>BIOS is VirtuaNES.exe, please place it in the same directory.</td>
</tr>
<tr>
<td>Real-time save</td>
<td>It's a save anywhere thing. FDS is also OK.</td>
</tr>
<tr>
<td>Drag and Drop</td>
<td>You can open ROM images, state files, NSF files, and movie files by drag and drop.</td>
</tr>
<tr>
<td>Command line launch</td>
<td>You can open ROM images by file extension association.</td>
</tr>
<tr>
<td>Shortcut keys</td>
<td>You can assign one function to two shortcut keys.</td>
</tr>
<tr>
<td>Controller</td>
<td>Continuous shooting can be set. Up to 8 are recognized.</td>
</tr>
<tr>
<td>Extension Controller</td>
<td>Arkanoid Paddle, Hyper Shot, Ray Gun, Family Basic Keyboard, Crazy Climber, Top Rider, Space Shadow Gun, Family Trainer, Exciting Boxing, Ide Yosuke Practice Mahjong Controller, Oeka Kids Tablet, Turbo File, VS-Unisystem (Zapper).</td>
</tr>
<tr>
<td>Extended Devices</td>
<td>DATACH Barcode Butler, Family Basic Keyboard Tape I/O, VS-Unisystem DipSwitch.</td>
</tr>
<tr>
<td>Scanline Display</td>
<td>Brightness adjustable.</td>
</tr>
<tr>
<td>Fullscreen display</td>
<td>Option to make ROM image full screen at the same time.</td>
</tr>
<tr>
<td>TV frame display</td>
<td>You can display frames like those found on old TVs and arcade cabinets.</td>
</tr>
<tr>
<td>8DOT unit bank switching</td>
<td>Automatic detection. The Mother(J) screen will be normal.</td>
</tr>
<tr>
<td>Modify headers in database</td>
<td>You can use the database file of NesToy or NNNesterJ. Rename it to nesromdb.dat and use it.</td>
</tr>
<tr>
<td>NSF Player</td>
<td>When you open an NSF file, it will automatically enter NSF player mode.</td>
</tr>
<tr>
<td>Compressed file</td>
<td>LHA, ZIP, RAR, CAB. Requires various DLLs (ZIP can be extracted without DLLs).</td>
</tr>
<tr>
<td>Snapshot</td>
<td>256x240dot/256 color BMP or PNG file.</td>
</tr>
<tr>
<td>Built-in Launcher</td>
<td>Compressed files are supported.</td>
</tr>
<tr>
<td>Movie Function</td>
<td>Addition and re-shooting functions available. AVI conversion is also possible.</td>
</tr>
<tr>
<td>WAVE Recording</td>
<td>Only during emulation.</td>
</tr>
<tr>
<td>Network play</td>
<td>Peer-to-peer simultaneous play. Chat function available. Proprietary. Not compatible with Kaillra.</td>
</tr>
<tr>
<td>Cheat Codes</td>
<td>You can load, save, and edit the code. Cheat support function is available.</td>
</tr>
<tr>
<td>Game Genie</td>
<td>You can load code files.</td>
</tr>
<tr>
<td>Language Plugins</td>
<td>Multilingual support via plugins. One or more plugins are required to run the program.</td>
</tr>
<tr>
<td>Various viewers</td>
<td>Memory viewer, pattern viewer, palette viewer, name table viewer.</td>
</tr>
<tr>
<td>Game-specific options</td>
<td>If the game screen is blurred or garbage is generated, the user can adjust it. You can switch between rendering (5 types), video mode (NTSC and PAL), and IRQ (H-SYNC and CLOCK) methods.</td>
</tr>
<tr>
<td>VS-Unisystem</td>
<td>Colormap is not perfect. VS-Dualsystem is not supported.</td>
</tr>
<tr>
<td>Various screen filters</td>
<td>6 types in total. MMX is required.</td>
</tr>
<tr>
<td>AVI conversion</td>
<td>Convert the movie file to AVI.</td>
</tr>
</table>

The above is a part of the implemented features. For details, please refer to [VirtuaNES OnlineHelp](http://virtuanes.s1.xrea.com/vhelp/index.html "VirtuaNES Online Help") (the information may be out of date) or VirtuaNES Readme.txt.

## Supported Mappers
Currently supports 148 mappers.

000, 001, 002, 003, 004, 005, 006, 007, 008, 009, 010, 011, 012, 013, 015, 016, 017, 018, 019, 020, 021, 022, 023, 024, 025, 026, 027, 032, 033, 034, 040, 041, 042, 043, 044, 045, 046, 047, 048, 050, 051, 057, 058, 060, 061, 062, 064, 065, 066, 067, 068, 069, 070, 071, 072, 073, 074, 075, 076, 077, 078, 079, 080, 082, 083, 085, 086, 087, 088, 089, 090, 091, 092, 093, 094, 095, 096, 097, 099, 100, 101, 105, 107, 108, 109, 110, 112, 113, 114, 115, 116, 117, 118, 119, 122, 133, 134, 135, 140, 142, 151, 160, 164, 165, 167, 180, 181, 182, 183, 184, 185, 187, 188, 189, 190, 191, 193, 194, 198, 200, 201, 202, 222, 225, 226, 227, 228, 229, 230, 231, 232, 233, 234, 235, 236, 240, 241, 242, 243, 244, 245, 246, 248, 249, 251, 252, 254, 255
