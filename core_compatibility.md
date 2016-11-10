# libretro cores compatibility with RetroAchievements

This is an attempt to make a compatibility list of libretro cores and RetroAchievements. If you want to contribute, please, updated your RetroArch to get the latest (2016/November/05) fixes on the RetroAchievements feature.

- [NES](#nes)
- [MegaDrive / Genesis](#megadrivegenesis)
- [SNES](#snes)
- [Game Boy/Game Boy Color](#game-boygame-boy-color)
- [Game Boy Advance](#game-boy-advance)
- [PC Engine](#pc-engine)

## NES

### QuickNES

The QuickNES seems to be the NES core with the best compatibility. No problems related to RetroAchievements were found in this core after the fixes.


### FCEUmm

There are some know achievements that aren't working with FCEUmm and are working fine with QuickNES. Here is a short list:

**Metroid** (all of them are item pickup cheevos)
- http://retroachievements.org/Achievement/3515
- http://retroachievements.org/Achievement/3518
- http://retroachievements.org/Achievement/3511
- http://retroachievements.org/Achievement/3507
- http://retroachievements.org/Achievement/3509

**Super Mario Bros 3**
- http://retroachievements.org/Achievement/4622


### Nestopia

Untested.


## MegaDrive/Genesis

### picodrive

No problems at all.


### Genesis Plus GX

Untested.


## SNES

### Snes9x 2010 (previously called SNES9x Next)

Seems to be working fine, but needs more tests after the fixes.


### Snes9x 2002 (previously called PocketSNES)

Untested.


### Snes9x 2005 (previously called CAT SFC)

Untested.


### Snes9x (from [this repository](https://github.com/libretro/snes9x))

Untested.


## Game Boy/Game Boy Color

### gambatte

Working, but has issues.


### mGBA

Although mGBA can play Game Boy/Game Boy Color ROMs, it does **NOT** suport cheevos for these systems (only for Game Boy Advance).


## Game Boy Advance

### mGBA

Seems to be working fine, but need more tests.


### VBA next

Doesn't work OK.
"vba-next doesn't support the memory map interface, so achievements won't work ok with it." - @leiradel


### VBA-M

Seems to be working fine, but need more tests.


## PC Engine

### Beetle PCE Fast (from [this repository](https://github.com/libretro/beetle-pce-fast-libretro))

Working fine.
