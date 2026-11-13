# Aionin1

A free overlay for **Aion 2 Global** (NA & EU): a party damage meter, a compass to your next unfinished pet, event timers on your server's clock, and a plan for which gear lines to reroll.

**Website:** https://jordan-cyber-yep.github.io/aionin1/

## Download

Get **Aionin1-Setup.exe** from the [latest release](https://github.com/jordan-cyber-yep/aionin1/releases/latest) and run it. Aionin1 updates itself after that.

1. Run the installer. It installs for your Windows user, with no admin prompt. The installer isn't code-signed yet, so Windows may say "Windows protected your PC": click **More info**, then **Run anyway**.
2. Install [Npcap](https://npcap.com/#download) with the default options. The installer reminds you if it's missing.
3. Start Aionin1 before you enter the world. Press **Alt+Shift+F10** to lock the HUD so clicks go to the game.

Needs Windows 10 or 11.

## Bugs and ideas

Open an [issue](https://github.com/jordan-cyber-yep/aionin1/issues). What changed in each version is in the [release notes](https://github.com/jordan-cyber-yep/aionin1/releases).

## Privacy

Aionin1 reads the network traffic the game already sends to your PC. It looks up combat power and gear on the official Aion 2 armory and checks this repository for updates. If you choose to share boss kills, each dungeon boss kill is sent anonymously to build the DPS percentiles: the boss, each player's class, CP, DPS and the fight length, with no names. Nothing else leaves your PC.

Aionin1 doesn't change game files or inject anything into the client. NCSOFT hasn't approved any third-party meter, so it's used at your own risk.

## Credits and license

Aionin1 is distributed under the MIT license (see [LICENSE](LICENSE), also in the install folder). It began as an adaptation of [MartinLVila/aion2-pet-overlay](https://github.com/MartinLVila/aion2-pet-overlay), whose pet decoder came from [elkaida/AION2-pet-tracker](https://github.com/elkaida/AION2-pet-tracker). Pet descriptions, map tiles and portraits come from [MetaBot.GG](https://metabot.gg/en/aion-2/mounts). World spawn coordinates, NPC names and the dungeon boss list come from [SkeeveAN/Aion-DPS-Meter](https://github.com/SkeeveAN/Aion-DPS-Meter). Grind's wallet and loot layouts follow community protocol research by [dimkk/aion2-market-stack](https://github.com/dimkk/aion2-market-stack) and [krajetum/AION2](https://github.com/krajetum/AION2). Class emblems load from NCSOFT's own image server.

A free fan project, not affiliated with NCSOFT. AION is a trademark of NCSOFT Corporation; game data, names and class emblems belong to NCSOFT.
