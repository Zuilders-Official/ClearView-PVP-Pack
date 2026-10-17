# ClearView PvP & Clarity

A lightweight Minecraft Java Edition resource pack that clears your screen so you can see more and fight better.

## Features

- **Short swords:** every sword (wooden, stone, copper, iron, golden, diamond, netherite) is drawn smaller in first person, so it blocks less of your view.
- **Clean crosshair:** a thin white crosshair with a dark outline and a gap in the middle, visible on any background.
- **No pumpkin blur:** removes the dark overlay when you wear a carved pumpkin.

## Compatibility

- Minecraft Java Edition 1.21.9 and newer.
- Works alongside most other resource packs. Place it above or below them in the list depending on which one should win a conflict (packs higher in the list take priority).
- Not for Bedrock Edition.

## Installation

1. Download `ClearView_PvP_Pack.zip`. Do not unzip it.
2. In Minecraft, go to **Options > Resource Packs > Open Pack Folder**.
3. Move the zip into the folder that opens.
4. Back in the game, select **ClearView PvP & Clarity** and click **Done**.

## What's inside

```
ClearView_PvP_Pack/
  pack.mcmeta                      pack info and version range
  pack.png                         pack icon
  assets/minecraft/
    models/item/*_sword.json       shortened first-person sword models
    textures/gui/sprites/hud/
      crosshair.png                custom crosshair
    textures/misc/
      pumpkinblur.png              transparent overlay (blur removed)
```

## Customizing

- **Sword size:** open any `models/item/*_sword.json` and change the `scale` values under `firstperson_righthand` and `firstperson_lefthand`. Smaller numbers make a smaller sword.
- **Crosshair:** edit `crosshair.png` (15x15 pixels) in any image editor.

## Troubleshooting

- **Pack doesn't show up:** make sure the file is a `.zip` and still zipped. Minecraft does not list `.jar` files in the resource pack folder.
- **"Made for a different version" warning:** the pack declares support for 1.21.9 and newer. On older versions, the warning is expected and the pack may not work correctly.

## Notes

This pack contains only original files and does not copy any of Minecraft's own textures. It is not affiliated with Mojang or Microsoft.
