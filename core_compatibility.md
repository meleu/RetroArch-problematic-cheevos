# libretro cores compatibility with RetroAchievements

This is an attempt to make a compatibility list of libretro cores and RetroAchievements. If you want to contribute, please, updated your RetroArch to get the latest (2016/November/05) fixes on the RetroAchievements feature.

- [NES](#nes)
  - [QuickNES](#quicknes)
  - [FCEUmm](#fceumm)
  - [Nestopia](#nestopia)
- [MegaDrive / Genesis](#megadrivegenesis)
  - [picodrive](#picodrive)
  - [Genesis Plus GX](#genesis-plus-gx)
- [SNES](#snes)
  - [Snes9x 2010](#snes9x-2010)
  - [Snes9x 2005](#snes9x-2005)
  - [Snes9x 2002](#snes9x-2002)
  - [Snes9x](#snes9x)  
- [Game Boy / Game Boy Color](#game-boygame-boy-color)
  - [gambatte](#gambatte)
  - [mGBA](#mgba)
- [Game Boy Advance](#game-boy-advance)
  - [mGBA](#mgba-1)
  - [VBA Next](#vba-next)
  - [VBA-M](#vba-m)
- [PC Engine](#pc-engine)
  - [Beetle PCE Fast](#beetle-pce-fast)


## NES

### QuickNES

The QuickNES seems to be the NES core with the best compatibility. No problems related to RetroAchievements were found in this core after the 05-Nov-2016 fixes.


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

### Snes9x 2010
*(previously called SNES9x Next)*

Seems to be working fine, but needs more tests after the 05-Nov-2016 fixes.


### Snes9x 2005
*(previously called CAT SFC)*

Untested.


### Snes9x 2002
*(previously called PocketSNES)*

Untested.


### Snes9x
*(from [this repository](https://github.com/libretro/snes9x))*

Untested.


## Game Boy/Game Boy Color

### gambatte

Received a fix on 12-November-2016 and then seems to be working fine.


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

### Beetle PCE Fast
*(from [this repository](https://github.com/libretro/beetle-pce-fast-libretro))*

Working fine.
