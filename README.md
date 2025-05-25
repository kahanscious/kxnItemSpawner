# kxnItemSpawner

a graveyard keeper mod that allows you to spawn any item directly into your inventory through a simple search interface.

## features

- **search-based item spawning** - find and spawn items by searching for their name or id
- **smart filtering** - automatically excludes problematic quest items and system objects
- **multiple quantity options** - spawn 1, 10, or 25 items at once
- **real-time search** - items load instantly as you type
- **performance optimized** - only loads items that match your search
- **clean interface** - simple, easy-to-use gui

## installation

1. **install BepInEx**
2. **download the mod** - get the latest `kxnItemSpawner.dll` file
3. **install the mod** - place the dll file in your `BepInEx/plugins/` folder
4. **launch the game** - the mod will load automatically

## usage

### opening the item spawner
- press **F9** in-game to open/close the item spawner window

### searching for items
- type in the search box to find items
- search by item name (e.g., "wood plank") or item id (e.g., "plank")
- results appear instantly as you type

### spawning items
1. **search** for the item you want
2. **select quantity** - choose 1, 10, or 25 items
3. **click "spawn"** next to the item you want
4. items are added directly to your inventory

### example searches

| search term | what you'll find |
|-------------|------------------|
| `wood` | wood planks, logs, beams, sticks |
| `iron` | iron ore, iron ingots, iron tools |
| `seed` | all seed varieties |
| `fish` | all fish types |
| `stone` | stone blocks, marble, clay |
| `food` | bread, cake, cooked meals |
| `ore` | all ore types (iron, coal, etc.) |
| `gem` | diamonds, emeralds, rubies |
| `silk` | silk and other rare materials |

## compatibility

- **works with most mods** - should be compatible with other graveyard keeper mods
- **save-safe** - won't corrupt your save files
- **multiplayer** - untested, use at your own risk

## support

if you encounter issues:
1. check the BepInEx console for error messages
2. try with a clean save to rule out save corruption
3. make sure you're using the latest version of the mod

## version history

### v1.0.0
- initial release
- search-based item spawning
- quantity selection (1, 10, 25)
- smart filtering of problematic items
- performance optimizations
