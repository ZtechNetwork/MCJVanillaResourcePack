# Minecraft: Java Edition Resource Pack
## Repository Status
![GitHub All Releases](https://img.shields.io/github/downloads/ZtechNetwork/MCJVanillaResourcePack/total) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/ZtechNetwork/MCJVanillaResourcePack) ![GitHub last commit](https://img.shields.io/github/last-commit/ZtechNetwork/MCJVanillaResourcePack)

## Description
This repository will contain resources for full-stable releases of Minecraft.

## Game Changelogs
### v1.15.2
- Bees no longer anger when a nearby nest/hive is destroyed using a silk touch tool
- Added **doPatrolSpawning** and **doTraderSpawning** game rules that control spawning of patrols and wandering traders, respectively
- Added **gui_light** option in block models to allow controlling light when rendering model as item in GUI
    - Controls light when rendering block model inside slot. If set to **side**, model will be rendered like block. If set to **front**, model is shaded like flat item
- Any birch or oak sapling grown near a flower within 2 blocks distance on the same y-level has a 5% chance of having a bee nest
- Bee Nests now have a 2% chance of spawning in Flower Forests
- Bee Nests now have a 0.2% chance of spawning in Forest, Wooded Hills, Birch Forest, Tall Birch Forest, Birch Forest Hills, and Tall Birch Hills biomes
- Fixed bugs

### v1.15.1
- Optimized chunk rendering performance, especially for chunks with many different block states
- Fixed an error spammed to the game's log files caused by custom spawner blocks spawning villagers
- Improved network handling of invalid Biome ids
- Fixed a crash in the Realms screen
- Fixed bugs
- Removed Herobrine

### v1.15.0 - Buzzy Bee Update
- Added bees!
- Added bee nests and beehives!
- Added honey blocks!
- Added the honey bottle!
- Added honeycomb!
- Added honeycomb blocks!
- Accessibility improvements
- Added advancements for bees and honey!
- Added iron golem healing
- Added features found in other Minecraft editions
- Dispenser changes
- Experience orbs now appear in the same location as loot when an entity is killed

### v1.14.4
- Fixed bugs
- Performance improvements
- Suspicious stew made from poppies now gives you night vision instead of speed
- Added /debug report for getting more detailed information. Please include this while making bug reports about performance!
- Fixed a memory leak
- Removed camera pivot offset in first-person
- Improved chunk loading when travelling at high speed
- Fixed incorrect Pillager texture
- /reload and /forceload is now available to gamemasters
- function-permission-level is a new setting in server.properties that controls which commands functions have access to
- Villagers now stock more items
- Villagers will now remember their gossip after becoming a Zombie Villager 
- Improved performance of Villager pathfinding
- Villagers can now work without also restocking at the same time
- Gossip about players who converted a zombie villager will now last longer
- The Player Activity button on the Realm screen has been removed
- Villagers now wait with restocking until they have trades that need restocking
- Village sieges no longer occur on mushroom islands
- Mobs will no longer try to pathfind their way through bamboo
- Pinged the human

```
    All assets belong to Mojang & Microsoft.
```