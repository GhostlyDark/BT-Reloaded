# BT Reloaded

Banjo-Tooie HD texture pack for GLideN64 and rt64.

> [!IMPORTANT]
> Release files can be found over at [evilgames.eu](https://evilgames.eu/texture-packs/bt-reloaded.htm) and [GitHub Releases](https://github.com/GhostlyDark/BT-Reloaded/releases/latest).

![](/bt-reloaded.jpg)



## Texture rescaling

The `bt.tdb` file contains information about the original texture sizes, which can be used by [Bighead's Custom Texture Tool](https://forums.dolphin-emu.org/Thread-custom-texture-tool-ps-v52-5) to rescale them to a new upscale ratio. This way, an HD replacement for a 32x32 texture can be rescaled to 8x the original resolution (256x256), down from however big the given HD texture might be.



## GLideN64

> [!NOTE]
> Latest [WIP build](https://github.com/gonetz/GLideN64/releases/github-actions) required. Use `PJ64Legacy-Qt-x86` if Project64 is your emulator of choice.

Pre-compiled `.hts` files are `cache` files and have to be located inside:

- Project64: `Project64/Plugin/GFX/cache`
- RMG: `RMG/Cache/cache`
- mupen64plus:
-- Windows: `%appdata%/mupen64plus/cache`
-- Linux: `~/.cache/mupen64plus/cache`
-- macOS: `~/Library/Application Support/Mupen64plus/cache`
- mupen64plus-nx (RetroArch): `RetroArch/system/Mupen64plus/cache`


**Only for advanced users:** HTS cache can be generated from the source PNG textures:

- Project64: `Project64/Plugin/GFX/hires_texture/BANJO TOOIE`
- RMG: `RMG/Data/hires_texture/BANJO TOOIE`
- mupen64plus:
-- Windows: `%appdata%/mupen64plus/hires_texture/BANJO TOOIE`
-- Linux: `~/.local/share/mupen64plus/hires_texture/BANJO TOOIE`
-- macOS: `~/Library/Application Support/Mupen64plus/hires_texture/BANJO TOOIE`
- mupen64plus-nx (RetroArch): `RetroArch/system/Mupen64plus/hires_texture/BANJO TOOIE`


Required graphics settings (named differently depending on emulator):

- Set texture pack usage: `Use texture pack` | `txHiresEnable` | `Use High-Res textures` to **On**
- Set use of full alpha: `Use full transparencies` | `txHiresFullAlphaChannel` | `Use High-Res Full Alpha Channel` to **On**
- Set use of HTS over HTC: `Use file storage instead of memory cache` | `txHiresTextureFileStorage` | `Use enhanced Hi-Res Storage` to **On**


Optional (but recommended) settings:

- Set cache compression: `Compress texture cache` | `txCacheCompression` | `Use High-Res Texture Cache Compression` to **Off**
- Fix black lines: `Fix black lines between 2D elements: For adjacent 2D elements` | `CorrectTexrectCoords: 1 (Auto)` | `Continuous texrect coords: Auto`
- Set mip-mapping: `Enable N64-style mip-mapping` | `EnableLOD` | `LOD Emulation` to **Off**



## Credits

Contributors:

- **GhostlyDark:** Main pack creator
- **brochacho:** Shock jump pad, Puzzle transition
- **James:** Control Stick animation
