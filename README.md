# Edd's Samurai Pack

A custom Minecraft resource pack by **Edd** that adds samurai-inspired swords and shields with unique models, textures, and name styling.

## What’s Included

- Custom diamond swords:
  - **Algid Gleam**
  - **Bloody Grief**
  - **Brass Legacy**
  - **Evergreen**
  - **Faint Quasar**
  - **Nightborn Sorrow**
- Matching custom shields / sheaths:
  - **Algid Sheath**
  - **Bloody Sheath**
  - **Brass Legacy Sheath**
  - **Evergreen Sheath**
  - **Faint Sheath**
  - **Nightborn Sheath**

## Features

- Custom item models in `assets/minecraft/models/item`
- Custom item textures in `assets/minecraft/textures/item`
- Dynamic lighting support for custom shields in `assets/minecraft/dynamiclights/item/shield.json`
- Command templates for giving the custom items in game are stored in `names.txt`

## Installation

1. Copy this folder into your Minecraft `resourcepacks` directory.
2. Open Minecraft and enable the pack from the Resource Packs menu.
3. Make sure your Minecraft version supports the pack format and custom item behavior used by this pack.

## Usage

Open `names.txt` for the full list of `/give` command templates. Use these commands in-game to receive the custom swords and shields with their proper names and custom data.

Example:

```mcfunction
/give @s diamond_sword[custom_data={algidgleam:1b},item_name=[{"text":"Algid Gleam","color":"blue"}]]
```

## Notes

- This pack is intended to be used as a resource pack with custom item visuals and command-based item generation.
- Keep `names.txt` handy for easy command reference.

## Author

- Created by **Edd**

