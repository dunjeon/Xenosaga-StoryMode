# Xenosaga Episode I — Story Mode

A free, open-source difficulty change for **Xenosaga Episode I: Der Wille zur Macht** (USA).

This is a fan project. It is not made by or affiliated with Monolith Soft, Namco, or Bandai Namco.

Made with Grok by xAI.

The project is [MIT licensed](LICENSE). Use it, share it, and change it.

**[Download the latest release](https://github.com/dunjeon/XenosagaEpisodeI-StoryMode/releases/latest)**

## Install

Close PCSX2. Open the zip and drag the `patches` folder onto your PCSX2 folder, into the same place as the `patches` folder that is already there. Replace the file when asked.

That folder is the one **Settings → Folders** calls the Patches directory:

| System | PCSX2 folder |
| --- | --- |
| Linux, and the AppImage | `~/.config/PCSX2/` |
| Windows | `Documents/PCSX2/` |
| Flatpak | `~/.var/app/net.pcsx2.PCSX2/config/PCSX2/` |

Start the game. Nothing else needs to be installed.

## Always on

Story Mode has no cheat checkbox. PCSX2 applies an unlabelled patch on every launch while **Enable Patches** is on. That setting is already on by default, and the patch stays on after you quit.

The patch writes only while the battle code is in memory. Field movement, menus, and the other modes are left alone.

| | Damage you deal | Damage you take |
| --- | --- | --- |
| Story Mode, the file in `patches/` | 3× | ¼ |
| Easy Mode, `optional/easy-mode/` | 2× | ½ |

Healing and EP costs stay the same. A hit still does at least 1, so you can still lose. The floating damage number can still show the original value. The HP bar is the scaled one.

Use one file. Easy Mode is a replacement for the Story Mode file, not a second copy beside it.

## Remove it

Delete `SLUS-20469_6D1276AB.pnach` from the PCSX2 `patches` folder.

## Which disc

USA. Serial `SLUS-20469`. CRC `6D1276AB`. PCSX2 prints that CRC in the log when the game boots.
