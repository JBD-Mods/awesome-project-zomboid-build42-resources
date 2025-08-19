# Mod Configuration Parameters

This document describes each parameter used for configuring your Project Zomboid mod in the mod manager.

| Parameter        | Description |
|------------------|-------------|
| `name`           | Displayed name for your mod in the game's mod manager. |
| `id`             | Unique mod ID used to activate your mod. Ensure it is not shared with other mods. |
| `author`         | Name of the mod author(s). Use your username if it's your original mod. |
| `description`    | Description shown in the mod manager. Supports ISRichTextPanel tags. |
| `url`            | URL link displayed in the mod manager for users to visit (e.g., donation links). |
| `poster`         | Main mod image(s). The first image is the primary display. Multiple images supported. |
| `icon`           | Icon shown next to the mod name in the mod manager list. |
| `modversion`     | Version number of your mod. |
| `require`        | List of mod IDs required for this mod to run. Example: `require=\theNeededMod,\theOtherOne` |
| `incompatible`   | List of mod IDs that cannot be enabled with this mod. Example: `incompatible=\theUnwantedMod,\theOtherOne` |
| `loadModAfterUnused` | Loads this mod only after the specified unused mods. |
| `loadModAfter`   | Loads this mod after the listed mods. Example: `loadModAfter=\someMod,\anotherMod` |
| `loadModBefore`  | Loads this mod before the listed mods. Example: `loadModBefore=\someMod,\anotherMod` |
| `category`       | Mod category (e.g., Map, Library, etc.). |
| `pack`           | Name of packs to be loaded by the game. |
| `tiledef`        | Tile definition and ID added by the mod. Example: `tiledef=Excavation 2112` |
| `versionMin`     | Minimum game version required for the mod. |
| `versionMax`     | Maximum game version supported by the mod. |

Use these parameters to ensure your mod is properly configured and compatible with Project Zomboid Build 42.