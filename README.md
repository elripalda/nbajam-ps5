# NBA Jam: On Fire Edition for PS5

**NBA Jam: On Fire Edition (Xbox 360) running natively on a jailbroken PS5.** The game is statically recompiled with [ReXGlue](https://github.com/rexglue/rexglue-sdk) and runs on its runtime's PS5 platform layer, with a hub made for the DualSense.

## What's in it
- Up to 4K, with sharpening (AMD CAS) and anti-aliasing settings
- A hub made for the DualSense: start the game, pick a mod, change settings
- PlayStation buttons in the game
- johnz1's mods (the 1990s, 2020s and Legends On Fire Editions, from [nba-jam.com](https://nba-jam.com)), installed from the hub's MODS page, each with its own saves

## What you need
- A jailbroken PS5 that runs homebrew apps from `/data/homebrew/`
- Your **own** copy of NBA Jam: On Fire Edition for Xbox 360: its `default.xex` and `data` folder. No game files are included.

## Install
**From Recomp Store:** install NBA Jam: On Fire Edition from [Recomp Store](https://recompstore.com), then copy your game's files into `/data/homebrew/PPSA91010/Assets/`.

**By hand:** download `PPSA91010.zip` from [Releases](https://github.com/elripalda/nbajam-ps5/releases), copy the `PPSA91010` folder to `/data/homebrew/` on your PS5, then copy your game's files into its `Assets` folder:

```
/data/homebrew/PPSA91010/Assets/default.xex
/data/homebrew/PPSA91010/Assets/data/...
```

Launch it from your homebrew launcher. The hub opens first: press START GAME.

## Mods
Get johnz1's mods at [nba-jam.com](https://nba-jam.com). Copy a mod's folder (the one with `Installation Files` in it) into `/data/homebrew/PPSA91010/Mods/`, then install it from the hub's MODS page.

## Credits
- **elripalda**: the PS5 port and the hub
- **GTTeancum**: OpenJam, the PC port, and how the PS3 mods play on the Xbox 360 game
- **johnz1**: the mods ([nba-jam.com](https://nba-jam.com))
- **ReXGlue**: the static recompiler and runtime; **Xenia**: the emulator its code comes from

*An unofficial fan project, not affiliated with or endorsed by EA, the NBA, Microsoft or Sony. No game files are included.*
