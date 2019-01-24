[![RimWorld 1.0](https://img.shields.io/badge/Rimworld-1.0-brightgreen.svg?style=plastic&logo=steam)](https://rimworldgame.com/)

# Advanced Transport Pods for RimWorld

Adds new larger versions of the original transport pod to the game.

The maximum load capacity has been increased to 275 kg for the large transport pod, and 400/525 kg for the more advanced versions. These pods also require small amounts of plasteel for construction. All new pods can be found from a convenient drop-down list under one icon in the Misc items category. Two new research options have been added for unlocking the secrets of the manufacturing processes.

Transport pod 275

Research needed: "Large transport pod"  
Construction skill needed: 7  
Construction requirements:
- 90 Steel
- 5 Plasteel
- 1 Component

Transport pod 400 / 525

Research needed: "Advanced transport pods"  
Construction skill needed: 8  
Construction requirements:
- 130 / 160 Steel
- 10 / 20 Plasteel
- 2 Components

# Known Issues

Should be mostly compatible with existing savegames, and other mods. Though there have been reports of the new pods disappearing as soon as one has been constructed, but the cause is unknown.

Due to some refactoring of the XMLs, games saved using the initial v1.0 of the mod will produce some errors in the debug log (see examples below), but these can be safely ignored. Though you will lose the earlier Advanced Transport Pods research, and all already constructed pods. Similar error messages will appear when loading a save game that included this mod, after the mod has been uninstalled.

```
"Could not load reference to Verse.ResearchProjectDef named AdvancedTransportPod"
"Could not load reference to Verse.ThingDef named AdvancedTransportPod"
```
