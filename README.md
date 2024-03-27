[![RimWorld 1.5](https://img.shields.io/badge/RimWorld-1.5-brightgreen.svg?style=plastic&logo=steam)](https://rimworldgame.com/)
...
[![RimWorld 1.3](https://img.shields.io/badge/RimWorld-1.3-brightgreen.svg?style=plastic&logo=steam)](https://rimworldgame.com/)

# Advanced Transport Pods v2 for RimWorld

A complete redesign of the original mod. Now using [XML Extensions](https://steamcommunity.com/sharedfiles/filedetails/?id=2574315206) to incorporate mod settings, for allowing the customization of attributes of both pod launchers and added transport pods.

All the new transport pods, as well as both pod launchers, are added into their own respective drop down lists in the Architect menu's Misc category, where they can be accessed via a single icon for the pod launchers and another for transport pods. All the added transport pods will also appear in the linkable facilities on both pod launchers, where it's more convenient to just click on the pod launcher when building a new pod instead of browsing through the Architect menu.

## What is added by this mod

Below is a list of all the new things this mod adds to the game.

- The `required research` lists the needed research projects, which may change depending on how the mod settings are customized.
- The `default resource requirements` lists the materials needed for construction. The percentage in parenthesis for pods indicates a relative material cost to a vanilla transport pod. All the resource requirements can be customized in the mod settings.

### Pod Launcher MKII

This is a more advanced version of the Pod launcher, doubling the vanilla pod launcher's range. The maximum fuel capacity is customizable in the mod settings, and can be set to cover the entire planet if so wanted.

```none
Required research: Transport pod, Large transport pods, Microelectronics, Advanced transport pods
Default maximum fuel capacity: 300
Construction skill needed: 8

Default resource requirements:
- 65  Steel
- 10  Uranium
-  1  Advanced Component
```

### Small Transport Pod 50

Not suitable for transporting pawns, but is cheaper for sending out smaller amount of goods than using a full-sized pod. The amount of steel required by three small pods is 25% more than it costs to build a single vanilla transport pod, but this also requires no components.

```none
Required research: Transport pod (vanilla)
Construction skill needed: 6

Default resource requirements:
- 25  Steel     ( 125 % )
```

### Large Transport Pod 200

Has a mass capacity one third larger than the vanilla pod. Uses 93% of the total amount of steel and 75% of components than what 1.33 vanilla pods would cost to build.

Is unlocked by researching the Large transport pods project.

```none
Required research: Transport pod, Large transport pods
Construction skill needed: 7

Default resource requirements:
- 85  Steel      ( 93 % )
-  1  Component  ( 75 % )
```

### Large Transport Pod 250

Has two thirds larger mass capacity than that of the vanilla pod. Construction costs 95% of the total amount of steel and 60% of components required to build 1.66 vanilla pods.

Is unlocked by researching the Large transport pods project.

```none
Required research: Transport pod, Large transport pods
Construction skill needed: 7

Default resource requirements:
- 95  Steel      ( 95 % )
-  1  Component  ( 60 % )
```

### Advanced Transport Pod 300

The first of the advanced transport pods, which offers double the capacity of the vanilla pod. Construction costs 17% less steel and 50% less components than using two vanilla pods, which is somewhat offset by the extra requirement of plasteel.

Is unlocked by researching the Advanced transport pods project.

```none
Required research: Transport pod, Large transport pods, Microelectronics, Advanced transport pods
Construction skill needed: 8

Default resource requirements:
- 100  Steel      ( 83 % )
-  10  Plasteel
-   1  Component  ( 50 % )
```

### Advanced Transport Pod 400

**Note! This pod is disabled by default, and must be manually enabled in the mod settings.** The reason for this is to avoid wandering too far off from the original vision of the base game.

The second iteration of the advanced transport pods, over two and a half times the capacity of the vanilla pod. Construction costs over 20% less steel and 25% fewer components than same amount of mass capacity with vanilla pods, but is compensated by the requirement of a significant amount of plasteel.

Is unlocked by researching the Advanced transport pods project.

```none
Required research: Transport pod, Large transport pods, Microelectronics, Advanced transport pods
Construction skill needed: 8

Default resource requirements:
- 125  Steel       ( 78 % )
-  15  Plasteel
-   2  Components  ( 75 % )
```

### Super Transport Pod

**Note! This pod is disabled by default, and must be enabled in the mod settings.**

This pod is completely overpowered and should not be used by anyone, ever. Nevertheless... if the lure of the dark side is too strong for you to resist, the mass capacity of this pod can be adjusted to insane levels in the mod settings.

Requires the research of a special spacer level technology to unlock. No significant material cost discounts.

```none
Required research: Transport pod, Large transport pods, Microelectronics, Advanced transport pods, Super advanced transport pod
Construction skill needed: 9

Default resource requirements:
- 225  Steel
-  15  Uranium
-   1  Advanced Component
```

---

## Updates

`v2.0.0`

- Complete redesign for RimWorld versions 1.3+.
- Rewritten with XML Extensions for incorporating mod settings.
- Dropped support for earlier versions of RimWorld.

## Known issues

Other mods that make changes to pod launchers and/or transport pods may cause issues.

Any anomalies related to transport pods or pod launchers are likely caused by conflicts with other mods. If you encounter any issues, try to start a new game with only this mod, the XML Extensions and Harmony loaded in addition to the base game and possible DLCs. If the issues go away, you may have a mod conflict or an incompatible save to blame.

Adding or removing the mod mid-save should be relatively safe, but removal will of course throw one-time errors when RimWorld can no longer find the researchDefs and thingDefs from this mod. These can be ignored and should go away after the game has been saved, and is reloaded again.
