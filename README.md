# Hyrule Evil 4

Download mirror for **Hyrule Evil 4**, a free fan mod that puts Link from *The Legend of Zelda: Twilight Princess* into *Resident Evil 4* UHD (Steam).

Main page and full description: https://www.nexusmods.com/residentevil4/mods/954

This repository only hosts release files. Get them from **[Releases](../../releases)**.

## Which files do I need?

You need your own copy of Resident Evil 4 UHD on Steam, with its original `bio4.exe`. If a tool offers the 4GB/LAA patch, answer **No**.

**New players** (full mod):
1. [3.2.0](../../releases/tag/v3.2.0): the full mod. `Main` is required (3 parts), `HD-Textures` is optional (4 parts). Download **every** part, then join them with 7-Zip (open the `.001` file) or with `copy /b`, as the release notes explain. Extract outside the game folder and run `LinkInRE4/Install-LinkInRE4.bat` (Main first, then HD-Textures).
2. [3.4.3](../../releases/tag/v3.4.3): run `LinkInRE4-3.4.3-Actualizador-desde-3.2.0.exe`. It takes 3.2.0 to 3.4.3.
3. [The latest release](../../releases/latest): run its updater EXE (`LinkInRE4-3.6.1-Actualizador-desde-3.4.0.exe` for 3.6.1).

**Already playing:**
- On 3.2.0, 3.2.1 or 3.3.0: the 3.4.3 updater, then the latest updater.
- On 3.4.0 or later: only the latest updater EXE. If you are on the version just before the latest one, its small patch ZIP also works.

To install any ZIP: close the game, extract it **outside** the game folder and run `LinkInRE4/Install-LinkInRE4.bat`. Each release lists the SHA-256 of its files.

**Do not copy the mod's files into the game by hand.** The installer also moves aside the game's compressed `.lfs` originals. Without that step the menu and many textures stay vanilla while the music changes, and the game can crash when gameplay starts. If that already happened: in Steam, right-click Resident Evil 4 > Properties > Installed Files > Verify integrity, then install again with the `.bat`.

**re4_tweaks or re4_fps:** they also use `Bin32\dinput8.dll`. Rename theirs to `winmm.dll` (and `dinput8.ini` to `winmm.ini`) before installing; the installer stops and tells you if it finds one.

## Disclaimer

Hyrule Evil 4 is a free, non-profit fan project. I do not own any of the characters, models, textures, animations, voices, music or sound effects it uses. The Legend of Zelda belongs to Nintendo; Hyrule Warriors content to Koei Tecmo and Nintendo; Resident Evil 4 to Capcom; Twilight Princess Definitive Edition+ HD textures to ValdarTP and GossipGeist. Not affiliated with or endorsed by Nintendo, Capcom or Koei Tecmo. The mod is never sold. If any rights holder wants this content removed, it will be taken down right away.
