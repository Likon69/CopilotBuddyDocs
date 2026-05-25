# Tripper.Navigation Namespace

Contains navigation and mesh pathfinding types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [GarrisonMeshManager](../../classes/Tripper/Navigation/GarrisonMeshManager.md) | Provides garrison mesh management functionality. |
| Public class | [MapConsts](../../classes/Tripper/Navigation/MapConsts.md) | Navigation map constants. HB 6.2.3 uses 533.3333f and CopilotBuddy keeps the same world tile size. |
| Public class | [MapLoadedEventArgs](../../classes/Tripper/Navigation/MapLoadedEventArgs.md) | Represents a map loaded event args. |
| Public class | [Navigator](../../classes/Tripper/Navigation/Navigator.md) | Main navigation system for WoW pathfinding using Detour navmesh. Provides mesh loading, path calculation, and navigation queries. Adapted from Honorbuddy 5.4.8 WowNavigator for Trinity navmesh format. |
| Public class | [PathFindProgressEventArgs](../../classes/Tripper/Navigation/PathFindProgressEventArgs.md) | Represents a path find progress event args. |
| Public class | [PathFindResult](../../classes/Tripper/Navigation/PathFindResult.md) | Pathfinding result data, including points, polygons, flags, and status. |
| Public class | [PathProgressEventArgs](../../classes/Tripper/Navigation/PathProgressEventArgs.md) | Event arguments for path progress events. |
| Public class | [QueryFilter](../../classes/Tripper/Navigation/QueryFilter.md) | Defines query filtering rules for pathfinding operations. Controls which polygon types are traversable and their costs. |
| Public class | [TileLoadedEventArgs](../../classes/Tripper/Navigation/TileLoadedEventArgs.md) | Represents a tile loaded event args. |
| Public class | [WorldMeshManager](../../classes/Tripper/Navigation/WorldMeshManager.md) | Provides world mesh management functionality. |
| Public class | [WowQueryFilter](../../classes/Tripper/Navigation/WowQueryFilter.md) | Represents a wow query filter. |

## Structures

| | Name | Description |
| --- | --- | --- |
| Public struct | [PolygonReference](../../classes/Tripper/Navigation/PolygonReference.md) | Represents a polygon reference. |
| Public struct | [Status](../../classes/Tripper/Navigation/Status.md) | Represents a navigation status value. |
| Public struct | [TileIdentifier](../../classes/Tripper/Navigation/TileIdentifier.md) | Represents a navigation tile identifier. |

## Interfaces

| | Name | Description |
| --- | --- | --- |
| Public interface | [IMeshManager](../../classes/Tripper/Navigation/IMeshManager.md) | Compatibility interface matching HB 6.2.3 PathFindResult.Manager contract. CopilotBuddy uses a consolidated navigator, so these pointers are optional. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [AbilityFlags](../../classes/Tripper/Navigation/AbilityFlags.md) | Defines movement abilities and traversal capabilities for pathfinding. Used as flags in Detour query filters to determine valid navigation paths. |
| Public enumeration | [AreaType](../../classes/Tripper/Navigation/AreaType.md) | Defines navigation area types for Detour navmesh polygons. These values correspond to Detour polygon area types and determine traversal rules. |
| Public enumeration | [PathFindStep](../../classes/Tripper/Navigation/PathFindStep.md) | Pathfinding step values used to track progress and failures. |
| Public enumeration | [PathPostProcessing](../../classes/Tripper/Navigation/PathPostProcessing.md) | Path post-processing mode for pathfinding results. Matches Honorbuddy's PathPostProcessing enum. |
| Public enumeration | [StraightPathFlags](../../classes/Tripper/Navigation/StraightPathFlags.md) | Straight path flags returned by Detour findStraightPath. Matches Detour native dtStraightPathFlags (DetourNavMesh.h). Used to detect segment types and off-mesh connections in navigation paths. |

## Delegates

| | Name | Description |
| --- | --- | --- |
| Public delegate | [NavigatorLogMessage](../../classes/Tripper/Navigation/NavigatorLogMessage.md) | Represents a delegate for Navigator Log Message. |

## See Also
[Namespace Index](../../index.md)
