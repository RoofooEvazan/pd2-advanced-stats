# PD2 Advanced Stats

Every advanced stat of a **Project Diablo 2** character, from a PD2 Armory export or a single-player save. Every number comes from the game's own code and PD2's data files, not from community formulas.

**Live site:** https://roofooevazan.github.io/pd2-advanced-stats/

Companion site: [PD2 IAS Calculator](https://roofooevazan.github.io/pd2-ias-calc/)

## Using it

- **Armory:** enter a character name. The page links to that character's Armory JSON (`api.projectdiablo2.com/game/character/NAME`); save it and load the file, or paste its text into the page.
- **Single player:** load a `.d2s` save file.

Everything runs in your browser. Files you load are not uploaded anywhere. The whole site is one file (`index.html`) with no server, build step or tracking.

## How the numbers were established

The rules were recovered from the Diablo II 1.13c DLLs that PD2 uses (`D2Common.dll`, `D2Game.dll`, `D2Client.dll`), PD2's changes in `ProjectDiablo.dll`, and PD2's Advanced Stats window in `BH.dll`. Rules marked **VERIFIED** on the page were checked by running the game's own machine code on random inputs; **READ** means read from the code but not run. The research log is in [`FINDINGS.md`](FINDINGS.md).

## Updating the site

Replace `index.html` with a new version, then commit. GitHub Pages republishes automatically within a minute or two.

## Disclaimer

This is a fan-made tool. It is not affiliated with or endorsed by Blizzard Entertainment or the Project Diablo 2 team. Diablo is a trademark of Blizzard Entertainment. No game assets are included.
