# Styx.Logic.Pathing Namespace

Contains pathfinding and movement types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [AvoidanceManager](../../../classes/Styx/Logic/Pathing/AvoidanceManager.md) | Manages dynamic avoidance of hostile mobs by creating temporary blackspots. Mobs can be added to avoid by Entry ID, and the system will automatically create and update blackspots as mobs move. |
| Public class | [BlackspotManager](../../../classes/Styx/Logic/Pathing/BlackspotManager.md) | Manages blackspots - areas to avoid during navigation. Blackspots can be added from profiles or dynamically at runtime. Like HB 4.3.4, this marks navmesh polygons with AreaType.Misc7 (26) and sets a high path cost (60f) to make the pathfinder avoid them. |
| Public class | [BlackspotManager.GlobalBlackspot](../../../classes/Styx/Logic/Pathing/BlackspotManager/GlobalBlackspot.md) | Represents a global blackspot that is saved across sessions. |
| Public class | [Flightor](../../../classes/Styx/Logic/Pathing/Flightor.md) | Flightor - Flying movement and pathfinding Ported from HB 4.3.4, adapted for WotLK with Trinity mmap support |
| Public class | [Flightor.MountHelper](../../../classes/Styx/Logic/Pathing/Flightor/MountHelper.md) | Flying mount helper - manages mounting/dismounting |
| Public class | [Flightor.MountHelper.DisMount](../../../classes/Styx/Logic/Pathing/Flightor/MountHelper/DisMount.md) | TreeSharp action for dismounting |
| Public class | [MeshHeightHelper](../../../classes/Styx/Logic/Pathing/MeshHeightHelper.md) | Helper class to find the navigation mesh height at a given position. Used by quest objectives to find valid Z coordinates for navigation. |
| Public class | [NavigationProviderChangedEventArgs<T>](../../../classes/Styx/Logic/Pathing/NavigationProviderChangedEventArgs_1.md) | Represents a navigation provider changed event args. |
| Public class | [Navigator](../../../classes/Styx/Logic/Pathing/Navigator.md) | Represents a navigator. |
| Public class | [StuckDetector](../../../classes/Styx/Logic/Pathing/StuckDetector.md) | Detects when the player is stuck and unable to move. |

## Structures

| | Name | Description |
| --- | --- | --- |
| Public struct | [WoWPoint](../../../classes/Styx/Logic/Pathing/WoWPoint.md) | Represents a wow point value. |

## Interfaces

| | Name | Description |
| --- | --- | --- |
| Public interface | [INavigationProvider](../../../classes/Styx/Logic/Pathing/INavigationProvider.md) | Defines the contract for I Navigation Provider. |
| Public interface | [IStuckHandler](../../../classes/Styx/Logic/Pathing/IStuckHandler.md) | Interface for handling stuck detection and recovery. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [MoveResult](../../../classes/Styx/Logic/Pathing/MoveResult.md) | Represents values for Move Result. |
| Public enumeration | [PathGenerationFailStep](../../../classes/Styx/Logic/Pathing/PathGenerationFailStep.md) | Represents values for Path Generation Fail Step. |
| Public enumeration | [PointLocationType](../../../classes/Styx/Logic/Pathing/PointLocationType.md) | Indicates the type of location where a point is situated. |

## See Also
[Namespace Index](../../../index.md)
