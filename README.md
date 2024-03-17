[![RimWorld 1.5](https://img.shields.io/badge/Rimworld-1.5-brightgreen.svg?style=plastic&logo=steam)](https://rimworldgame.com/) [![RimWorld 1.4](https://img.shields.io/badge/Rimworld-1.4-brightgreen.svg?style=plastic&logo=steam)](https://rimworldgame.com/) [![RimWorld 1.3](https://img.shields.io/badge/Rimworld-1.3-brightgreen.svg?style=plastic&logo=steam)](https://rimworldgame.com/) [![RimWorld 1.2](https://img.shields.io/badge/Rimworld-1.2-brightgreen.svg?style=plastic&logo=steam)](https://rimworldgame.com/) [![RimWorld 1.1](https://img.shields.io/badge/Rimworld-1.1-brightgreen.svg?style=plastic&logo=steam)](https://rimworldgame.com/) [![RimWorld 1.0](https://img.shields.io/badge/Rimworld-1.0-brightgreen.svg?style=plastic&logo=steam)](https://rimworldgame.com/)

# Advanced Transport Pods for RimWorld

Adds a new pod launcher, and several new versions of the sub-orbital transport pod to the game. Supports Rimworld versions 1.0 through 1.5.

In addition to the vanilla pod (with 150 kg capacity) there is a smaller variant that can carry 50 kg, a large transport pod with a carrying capacity of 275 kg, and two more advanced versions with 400 & 525 kg capacities. All larger pods also require small amounts of plasteel for construction. All pods can now be found from a convenient drop-down list under one icon in the Misc items category, and the vanilla pod has been renamed to "Transport pod 150" to match with the naming scheme. Two new research options have been added for unlocking the larger variants.

The Advanced transport pods research also unlocks a new pod launcher with more hitpoints (doubled to 400), and greater fuel capacity (666) than the vanilla one (150), significantly extending its maximum range. Both launchers can be found from a drop-down list under one icon in the Misc items category. In addition, the pod construction templates have been linked to both launchers allowing to quickly and easily build new pods directly from the launcher (no need to browse the Architect menu).

### Transport pod 50

```none
Research needed: "Transport pod"
Construction skill needed: 5
Construction requirements:

- 25 Steel
```

### Transport pod 275

```none
Research needed: "Large transport pod"
Construction skill needed: 7
Construction requirements:

- 90 Steel
- 5 Plasteel
- 1 Component
```

### Transport pod 400 / 525

```none
Research needed: "Advanced transport pods"
Construction skill needed: 8
Construction requirements:

- 130 / 160 Steel
- 10 / 20 Plasteel
- 2 Components
```

### Pod launcher MKII

```none
Research needed: "Advanced transport pods"
Construction skill needed: 7
Construction requirements:

- 65 Steel
- 10 Plasteel
- 1 Advanced Component
```

## Updates

`v1.5.3`

- Updated for RimWorld 1.5
- Added textures in DDS format

`v1.5.2`

- Updated for RimWorld 1.4

`v1.5.1`

- Updated for RimWorld 1.3

`v1.5.0 (RimWorld 1.1+ only)`

- Added Rimefeller automatic refuel support to the MKII pod launcher. You may have to adjust the target fuel level once after construction for it to work correctly.
- Prevented the "linked facility" visual indicators from appearing between pods and launchers.
- Adjusted construction requirements of the MKII pod launcher.

## Known Issues

Adding or removing the mod mid-save should be safe. If you have researched the techs or constructed the pod launcher or pods from this mod, reloading the save after removing the mod will likely throw one-time errors that can be ignored.

Should be mostly compatible with existing save games, and other mods that do not involve transport pods. There have been reports of the new pods disappearing as soon as one has been constructed, but the cause is unknown; though it is most likely a conflict with another mod.

Due to some refactoring of the XMLs in ATP v1.1, games saved using the initial v1.0 of the mod will produce some errors in the debug log when loaded using a later version (see examples below), but these can be safely ignored. Though you will lose the earlier Advanced Transport Pods research, and all already constructed pods. Similar error messages will appear when loading a save game that included this mod, after the mod has been uninstalled.

```none
"Could not load reference to Verse.ResearchProjectDef named AdvancedTransportPod"
"Could not load reference to Verse.ThingDef named AdvancedTransportPod"
```
