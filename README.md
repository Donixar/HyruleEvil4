# Hyrule Evil 4

Download mirror for **Hyrule Evil 4**, a free fan mod that puts Link from *The Legend of Zelda: Twilight Princess* into *Resident Evil 4* UHD (Steam).

Main page and full description: https://www.nexusmods.com/residentevil4/mods/954

This repository only hosts release files. Get them from **[Releases](../../releases)**.

**Current version: 3.6.4.** Download the [offline updater](../../releases/tag/v3.6.4) to update an existing install in one run.

## Which files do I need?

You need your own copy of Resident Evil 4 UHD on Steam, with its original `bio4.exe`. If a tool offers the 4GB/LAA patch, answer **No**.

**New players** (full mod):

Download the [3.6.4 installer](https://github.com/Donixar/HyruleEvil4/releases/download/v3.6.4/HyruleEvil4-3.6.4-Installer.exe), close Resident Evil 4 and open the installer. It downloads and verifies the full package, then installs 3.6.4 directly on a clean Steam copy. The package includes standard textures. Set Texture Quality to Original in the game.

The updater opens a progress window at once (step, bar, elapsed time) and gives its final message in English and Spanish. An update can take several minutes, longer with the HD textures: let it finish and do not open the updater a second time.

**Already playing:**
- From any published version between 3.2.0 and 3.6.3, run the same [3.6.4 offline updater](../../releases/tag/v3.6.4) once. It detects your installed version and keeps your settings.
- The small manual ZIP is also available for players already on 3.6.3.

To install any ZIP: close the game, extract it **outside** the game folder and run `LinkInRE4/Install-LinkInRE4.bat`. Each release lists the SHA-256 of its files.

**Do not copy the mod's files into the game by hand.** The installer also moves aside the game's compressed `.lfs` originals. Without that step the menu and many textures stay vanilla while the music changes, and the game can crash when gameplay starts. If that already happened: in Steam, right-click Resident Evil 4 > Properties > Installed Files > Verify integrity, then install again with the `.bat`.

**re4_tweaks or re4_fps:** they also use `Bin32\dinput8.dll`. Rename theirs to `winmm.dll` (and `dinput8.ini` to `winmm.ini`) before installing; the installer stops and tells you if it finds one.

## Disclaimer

Hyrule Evil 4 is a free, non-profit fan project. I do not own any of the characters, models, textures, animations, voices, music or sound effects it uses. The Legend of Zelda belongs to Nintendo; Hyrule Warriors content to Koei Tecmo and Nintendo; Resident Evil 4 to Capcom; Twilight Princess Definitive Edition+ HD textures to ValdarTP and GossipGeist. Not affiliated with or endorsed by Nintendo, Capcom or Koei Tecmo. The mod is never sold. If any rights holder wants this content removed, it will be taken down right away.
