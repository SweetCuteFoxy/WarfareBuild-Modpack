# WarfareBuild Modpack

A custom Minecraft 1.20.1 Forge modpack with a military and tactical theme featuring ~180 hand-picked mods.

Includes weapon systems (TaCZ, Superb Warfare, Point Blank), vehicles (Valkyrien Skies, Immersive Aircraft), magic (Goety), building tools (Create + addons), and a ton of quality-of-life and optimization mods.

## How to Download

1. Head over to the [Releases](../../releases) page
2. Download **all 3 parts** (`.part01`, `.part02`, `.part03`)
3. Merge them into a single ZIP — see below

### Merging the Parts

**Windows (Command Prompt):**
```
copy /b WarfareBuild2.zip.part01+WarfareBuild2.zip.part02+WarfareBuild2.zip.part03 WarfareBuild2.zip
```

**Windows (PowerShell):**
```powershell
Get-Content WarfareBuild2.zip.part01, WarfareBuild2.zip.part02, WarfareBuild2.zip.part03 -Encoding Byte -ReadCount 512 | Set-Content WarfareBuild2.zip -Encoding Byte
```

**Linux / macOS:**
```bash
cat WarfareBuild2.zip.part01 WarfareBuild2.zip.part02 WarfareBuild2.zip.part03 > WarfareBuild2.zip
```

## Installation

1. Open **Prism Launcher** (or MultiMC)
2. Click **Add Instance** → **Import from zip**
3. Select the merged `WarfareBuild2.zip`
4. Wait for the import to finish
5. Launch and enjoy

## Key Mods

| Category | Mods |
|----------|------|
| Weapons | TaCZ, Superb Warfare, Point Blank, Musket Mod |
| Vehicles & Flight | Valkyrien Skies, Immersive Aircraft, Warsteel |
| Magic | Goety (+ addons), Enigmatic Legacy, Cataclysm |
| Building | Create (+ addons), Immersive Engineering |
| Optimization | Embeddium, ModernFix, FerriteCore, Starlight |
| QoL | EMI, Xaero's Minimap, BetterF3, ParCool |

## Requirements

- Minecraft **1.20.1**
- Forge **47.4.0** (bundled)
- ~8 GB RAM recommended (allocate in launcher settings)
- Java 17+

## Notes

- Keybinds are pre-configured but you might want to tweak them to your liking
- Shader support via Oculus/Iris is included — drop your favorite shaderpack into the `shaderpacks` folder
