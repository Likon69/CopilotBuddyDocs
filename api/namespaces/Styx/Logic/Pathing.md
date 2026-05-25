# Styx.Logic.Pathing Namespace

Contains pathfinding and movement types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [AvoidanceManager](../../../classes/Styx/Logic/Pathing/AvoidanceManager.md) | Manages dynamic avoidance of hostile mobs by creating temporary blackspots. Mobs can be added to avoid by Entry ID, and the system will automatically create and update blackspots as mobs move. |
| Public class | [BlackspotManager](../../../classes/Styx/Logic/Pathing/BlackspotManager.md) | Manages blackspots - areas to avoid during navigation. Blackspots can be added from profiles or dynamically at runtime. Like HB WoD, this marks navmesh polygons with AreaType.Blackspot (17) and sets a high path cost (60f) to make the pathfinder avoid them. |
| Public class | [BlackspotManager.GlobalBlackspot](../../../classes/Styx/Logic/Pathing/BlackspotManager/GlobalBlackspot.md) | Represents a global blackspot that is saved across sessions. |
| Public class | [ClickToMoveMover](../../../classes/Styx/Logic/Pathing/ClickToMoveMover.md) | Default WoD-style click-to-move mover. |
| Public class | [Flightor](../../../classes/Styx/Logic/Pathing/Flightor.md) | Flightor - Flying movement and pathfinding Ported from HB 4.3.4, adapted for WotLK with Trinity mmap support |
| Public class | [Flightor.MountHelper](../../../classes/Styx/Logic/Pathing/Flightor/MountHelper.md) | Flying mount helper - manages mounting/dismounting |
| Public class | [Flightor.MountHelper.DisMount](../../../classes/Styx/Logic/Pathing/Flightor/MountHelper/DisMount.md) | TreeSharp action for dismounting |
| Public class | [KeyboardMover](../../../classes/Styx/Logic/Pathing/KeyboardMover.md) | WoD-style keyboard mover — port of HB 6.2.3 Styx.Pathing.KeyboardMover. Steers by calling SetFacing in a tight loop rather than CTM. |
| Public class | [MeshHeightHelper](../../../classes/Styx/Logic/Pathing/MeshHeightHelper.md) | Helper class to find the navigation mesh height at a given position. Used by quest objectives to find valid Z coordinates for navigation. |
| Public class | [MeshMovePath](../../../classes/Styx/Logic/Pathing/MeshMovePath.md) | WoD-style move path wrapper (PathFindResult + current index). |
| Public class | [MeshNavigator](../../../classes/Styx/Logic/Pathing/MeshNavigator.md) | Concrete NavigationProvider that wraps Tripper.Navigator (Navigation.dll). Direct port of HB 6.2.3 MeshNavigator (Styx.Pathing.MeshNavigator). Responsibilities (matching HB WoD): - Navmesh path generation (FindPath + EnsureTiles + Blackspot sync) - Path following with push-ahead (method_25/26) - Start-index skip (method_14) - Off-mesh connection dispatch (elevator, portal, interact, jump) - Door detection and interaction (method_7/8) - Stuck detection and recovery (Class469) - Drift detection (method_15) - Alive/ghost query filter (method_28) - PathPrecision-based waypoint advance (method_24/27) Not here (stays in Navigator facade): - Flightor routing, mount/dismount, avoidance wiring, bot lifecycle |
| Public class | [MoveResultExtensions](../../../classes/Styx/Logic/Pathing/MoveResultExtensions.md) | Represents a move result extensions. |
| Public class | [NavigationProvider](../../../classes/Styx/Logic/Pathing/NavigationProvider.md) | WoD-style navigation provider contract used by Navigator. Direct port of HB 6.2.3 Styx.Pathing.NavigationProvider. |
| Public class | [NavigationProviderChangedEventArgs<T>](../../../classes/Styx/Logic/Pathing/NavigationProviderChangedEventArgs_1.md) | Represents a navigation provider changed event args. |
| Public class | [Navigator](../../../classes/Styx/Logic/Pathing/Navigator.md) | Represents a navigator. |
| Public class | [StuckDetector](../../../classes/Styx/Logic/Pathing/StuckDetector.md) | Detects when the player is stuck and unable to move. |
| Public class | [StuckHandler](../../../classes/Styx/Logic/Pathing/StuckHandler.md) | Represents a stuck handler. |

## Structures

| | Name | Description |
| --- | --- | --- |
| Public struct | [WoWPoint](../../../classes/Styx/Logic/Pathing/WoWPoint.md) | Represents a wow point value. |

## Interfaces

| | Name | Description |
| --- | --- | --- |
| Public interface | [INavigationProvider](../../../classes/Styx/Logic/Pathing/INavigationProvider.md) | Defines the contract for I Navigation Provider. |
| Public interface | [IPlayerMover](../../../classes/Styx/Logic/Pathing/IPlayerMover.md) | Defines the contract for I Player Mover. |
| Public interface | [ITerrainHeightProvider](../../../classes/Styx/Logic/Pathing/ITerrainHeightProvider.md) | Defines the contract for I Terrain Height Provider. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [BlackspotQueryFlags](../../../classes/Styx/Logic/Pathing/BlackspotQueryFlags.md) | Flags that control which categories of blackspot are queried. Port of HB 6.2.3 Styx.Pathing.BlackspotQueryFlags. |
| Public enumeration | [MoveResult](../../../classes/Styx/Logic/Pathing/MoveResult.md) | Represents values for Move Result. |
| Public enumeration | [PathGenerationFailStep](../../../classes/Styx/Logic/Pathing/PathGenerationFailStep.md) | Represents values for Path Generation Fail Step. |
| Public enumeration | [PointLocationType](../../../classes/Styx/Logic/Pathing/PointLocationType.md) | Indicates the type of location where a point is situated. |

## See Also
[Namespace Index](../../../index.md)
