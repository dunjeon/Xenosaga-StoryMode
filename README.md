# Xenosaga — Story Mode

A free, open-source cheat for the USA PlayStation 2 games **Xenosaga Episode I**, **Episode II**, and **Episode III**.

This is a fan project. It is not made by or affiliated with Monolith Soft, Namco, or Bandai Namco.

Made with Grok by xAI.

The project is [MIT licensed](LICENSE). Use it, share it, and change it.

**[Download the latest release](https://github.com/dunjeon/Xenosaga-StoryMode/releases/latest)**

## Install

Close PCSX2. Copy the `.pnach` files from `cheats/` into the PCSX2 cheats folder. Copy the one that matches the game, or copy them all.

| System | Cheats folder |
| --- | --- |
| Linux, and the AppImage | `~/.config/PCSX2/cheats/` |
| Windows | `Documents/PCSX2/cheats/` |
| Flatpak | `~/.var/app/net.pcsx2.PCSX2/config/PCSX2/cheats/` |

Right-click the game, open Properties, then Cheats. Turn on Enable Cheats for this game, and tick Story Mode or Easy Mode. Tick one.

| | Damage you deal | Damage you take |
| --- | --- | --- |
| Story Mode | 3× | ¼ |
| Easy Mode | 2× | ½ |

Healing and EP costs stay the same. A hit still does at least 1. The floating damage number can still show the original value. The HP bar is the scaled one.

## Which game

PCSX2 names the cheat from the serial and the CRC it prints in the log when the game boots.

| Game | Disc | Serial | CRC | Cheat file |
| --- | --- | --- | --- | --- |
| Episode I | — | `SLUS-20469` | `6D1276AB` | `cheats/SLUS-20469_6D1276AB.pnach` |
| Episode II | 1 | `SLUS-20892` | `EB39ABEC` | `cheats/SLUS-20892_EB39ABEC.pnach` |
| Episode II | 2 | `SLUS-21133` | `EB39ABEC` | `cheats/SLUS-21133_EB39ABEC.pnach` |
| Episode III | 1 | `SLUS-21389` | `2088950A` | `cheats/SLUS-21389_2088950A.pnach` |
| Episode III | 2 | `SLUS-21417` | `2088950A` | `cheats/SLUS-21417_2088950A.pnach` |

Episode II has two discs, and so does Episode III. Both discs of a game carry the same battle code, so the cheat inside the two files is the same. PCSX2 loads the file for the disc you boot. A disc swap during the game keeps that cheat running, because the game does not reload its code. Booting disc 2 from the menu uses the disc 2 file.

USA discs only.
