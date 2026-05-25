# Navigator Class

Main navigation system for WoW pathfinding using Detour navmesh. Provides mesh loading, path calculation, and navigation queries. Adapted from Honorbuddy 5.4.8 WowNavigator for Trinity navmesh format.

## Inheritance Hierarchy
System.Object
  Tripper.Navigation.Navigator

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class Navigator : IDisposable
```

The Navigator type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Navigator](Navigator/Constructors/Constructor_EF093226A6EE.md) | Initializes a new instance of the Navigator class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CurrentMapId](Navigator/Properties/CurrentMapId_A77327451839.md) | Current map ID that the navigator is operating on. |
| Public property | [EdgeDistance](Navigator/Properties/EdgeDistance_A63C4B95FAAF.md) | Edge distance threshold for MoveAwayFromEdges post-processing. Points closer than this to a wall will be moved away. Default: 2.0 yards (like HB). |
| Public property | [Extents](Navigator/Properties/Extents_7B0CCA9E9E09.md) | Search extents passed raw to dtNavMeshQuery in Detour space [horizontal, vertical, horizontal]. Navigation.cpp applies WoWToDetour on center only — extents go direct to Detour. Must match HB 6.2.3 WowNavigator.Extents = (3,20,3): ±3 horizontal, ±20 vertical. |
| Public property | [GarbageCollectTime](Navigator/Properties/GarbageCollectTime_F2D71EBCB626.md) | Time interval for garbage collection of unused tiles. |
| Public property | [GarrisonMesh](Navigator/Properties/GarrisonMesh_62C3A36725A6.md) | HB-compatible garrison mesh manager facade. WotLK does not use garrisons. |
| Public property | [IsLoaded](Navigator/Properties/IsLoaded_97591F547359.md) | Indicates if the navigation system is initialized and ready. |
| Public property | [MapNames](Navigator/Properties/MapNames_F75F0BD04404.md) | Loaded map names. Kept for HB API surface parity. |
| Public property | [MeshLock](Navigator/Properties/MeshLock_B7722A4D2AFF.md) | Lock object for thread-safe mesh operations. |
| Public property | [PathPostProcessing](Navigator/Properties/PathPostProcessing_7F81539EEE76.md) | Path post-processing mode. Default is MoveAwayFromEdges to avoid stairs/wall issues. Matches Honorbuddy's PathPostProcessing behavior. |
| Public property | [PrimaryMapName](Navigator/Properties/PrimaryMapName_B884B0A00E9B.md) | Primary map identifier string. WotLK uses numeric map IDs, so this is informational. |
| Public property | [QueryFilter](Navigator/Properties/QueryFilter_9C28993DC5C3.md) | Current query filter used for pathfinding operations. |
| Public property | [WorldMesh](Navigator/Properties/WorldMesh_759394E2D8D4.md) | HB-compatible world mesh manager facade. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [LogMessage](Navigator/Events/LogMessage_136CECEBDA2E.md) | Raised when a navigation log message is generated. |
| Public event | [MapLoaded](Navigator/Events/MapLoaded_D12306F06278.md) | Raised when a map is fully loaded. |
| Public event | [OnMapLoaded](Navigator/Events/OnMapLoaded_ADEAD38D38E8.md) | HB-compatible alias for MapLoaded. |
| Public event | [OnNavigatorLogMessage](Navigator/Events/OnNavigatorLogMessage_9284ED1BE525.md) | HB-compatible navigator log event. |
| Public event | [OnPathFindProgress](Navigator/Events/OnPathFindProgress_FF4F004318AB.md) | HB-compatible alias for PathProgress. |
| Public event | [OnSubTileLoaded](Navigator/Events/OnSubTileLoaded_DB949CDF9D21.md) | HB-compatible sub-tile event alias. 1x1 MaNGOS tiles do not have sub-tiles, so this mirrors OnTileLoaded. |
| Public event | [OnTileLoaded](Navigator/Events/OnTileLoaded_FD78BF39C7A9.md) | HB-compatible alias for TileLoaded. |
| Public event | [PathProgress](Navigator/Events/PathProgress_FD0800FA1670.md) | Raised during pathfinding progress. |
| Public event | [TileLoaded](Navigator/Events/TileLoaded_BB20301C8489.md) | Raised when a tile is loaded into the navmesh. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [AddOffMeshConnection(uint, Vector3, Vector3, float, byte, byte, uint)](Navigator/Methods/AddOffMeshConnection_0FA65C2F2613.md) | Adds a custom offmesh connection at runtime. |
| Public method | [ChangeMap(ICollection<string>)](Navigator/Methods/ChangeMap_107C92C59301.md) | HB-compatible map change API. In WotLK integration, map name values are numeric map ids. |
| Public method | [ClosestPointOnPoly(uint, PolygonReference, Vector3, Vector3)](Navigator/Methods/ClosestPointOnPoly_35085FDA9431.md) | Finds the closest point on a polygon. |
| Public method | [ClosestPointOnPolyBoundary(uint, PolygonReference, Vector3, Vector3)](Navigator/Methods/ClosestPointOnPolyBoundary_466D2C52C92C.md) | Finds the closest point on polygon boundary. |
| Public method | [Dispose](Navigator/Methods/Dispose_3E6BCF0A8BAA.md) | Releases all resources used by the Navigator. |
| Public method | [EnsureTiles(uint, Vector3, int)](Navigator/Methods/EnsureTiles_17BF13DF68DC.md) | Ensures tiles within specified ring distance are loaded. |
| Public method | [EnsureTilesAroundPosition(uint, Vector3, int)](Navigator/Methods/EnsureTilesAroundPosition_3F36DA19D27E.md) | Ensures tiles around position are loaded (HB-style streaming). Use this before pathfinding to ensure navmesh coverage. |
| Public method | [EnsureTilesDirectional(uint, Vector3, Vector3, int)](Navigator/Methods/EnsureTilesDirectional_4635F92B7AE1.md) | Prefetches tiles in movement direction for smoother streaming. Call this regularly during movement for best performance. |
| Public method | [FinalizeSlicedFindPath(int)](Navigator/Methods/FinalizeSlicedFindPath_BD87DD00E957.md) | Finalizes sliced path search and returns the path. |
| Public method | [FindDistanceToWall(uint, Vector3, float, Vector3)](Navigator/Methods/FindDistanceToWall_5C7163A30AC1.md) | Finds distance to the nearest wall/boundary from a position. |
| Public method | [FindLocalNeighbourhood(uint, PolygonReference, Vector3, float, int)](Navigator/Methods/FindLocalNeighbourhood_AE10D5DDB7BF.md) | Finds local polygon neighbourhood around a starting polygon. Useful for local obstacle detection and area analysis. |
| Public method | [FindNearestPoint(uint, Vector3, Vector3)](Navigator/Methods/FindNearestPoint_9BEAB9B956F0.md) | Finds the nearest valid navmesh point to a given position. |
| Public method | [FindNearestPolyRef(uint, Vector3, PolygonReference, Vector3)](Navigator/Methods/FindNearestPolyRef_77138907FAF8.md) | Finds the nearest polygon reference to a position. |
| Public method | [FindPath(Vector3, Vector3)](Navigator/Methods/FindPath_D08A1554D7FC.md) | HB-compatible overload that uses the current map. |
| Public method | [FindPath(uint, Vector3, Vector3, bool)](Navigator/Methods/FindPath_57DAA02799BF.md) | Calculates a path from start to end position. Uses CalculatePathEx for complete path information including flags and area types. |
| Public method | [FindPolysAroundCircle(uint, Vector3, float, int)](Navigator/Methods/FindPolysAroundCircle_155CE827DF6E.md) | Finds polygons within a circle around a point. |
| Public method | [FindRandomPoint(uint, Vector3, float, Vector3)](Navigator/Methods/FindRandomPoint_492535524B31.md) | Finds a random navigable point within radius of center position. |
| Public method | [GetAreaCost(uint)](Navigator/Methods/GetAreaCost_43E1E48977B7.md) | Gets traversal cost for an area type. Like HB WoD QueryFilter.GetAreaCost. |
| Public method | [GetAreaCost(AreaType)](Navigator/Methods/GetAreaCost_EB085FE0537A.md) | Gets traversal cost for an area type using AreaType enum. |
| Public method | [GetDefaultFilterPtr](Navigator/Methods/GetDefaultFilterPtr_FC05E021A461.md) | Gets direct pointer to default dtQueryFilter for advanced use. WARNING: Use with caution - direct Detour access. |
| Public method | [GetExcludeFlags](Navigator/Methods/GetExcludeFlags_499E136BE80A.md) | Gets current polygon exclude flags. |
| Public method | [GetIncludeFlags](Navigator/Methods/GetIncludeFlags_40AE1F9F6EBF.md) | Gets current polygon include flags. |
| Public method | [GetLoadedTilesCount(uint)](Navigator/Methods/GetLoadedTilesCount_73832216ED11.md) | Gets count of loaded tiles for a map. |
| Public method | [GetManagerFromLocation(Vector3)](Navigator/Methods/GetManagerFromLocation_2D958CBD51B0.md) | Returns the active mesh manager for a location. |
| Public method | [GetNavMeshQueryPtr(uint)](Navigator/Methods/GetNavMeshQueryPtr_21F6400C2C8E.md) | Gets direct pointer to dtNavMeshQuery for advanced NavBridge use. WARNING: Use with caution - direct Detour access. |
| Public method Static member | [GetNewDefaultQueryFilter](Navigator/Methods/GetNewDefaultQueryFilter_C50D123E63E5.md) | HB-compatible static default filter factory. |
| Public method Static member | [GetNewFactionQueryFilter(bool)](Navigator/Methods/GetNewFactionQueryFilter_C957400D965F.md) | HB-compatible faction filter factory. |
| Public method | [GetPolyArea(uint, PolygonReference, byte)](Navigator/Methods/GetPolyArea_E5743B711CB3.md) | Gets the area type for a polygon. Like HB WoD NavMesh.GetPolyArea. |
| Public method | [GetPolyFlags(uint, PolygonReference, ushort)](Navigator/Methods/GetPolyFlags_64A1AB07C5AA.md) | Gets flags for a polygon. Like HB WoD NavMesh.GetPolyFlags. |
| Public method | [GetPolyHeight(uint, PolygonReference, Vector3, float)](Navigator/Methods/GetPolyHeight_299308CE5C3D.md) | Gets the height at a position on a specific polygon. |
| Public method | [GetPolyWallSegments(uint, PolygonReference, int)](Navigator/Methods/GetPolyWallSegments_087605AE38AD.md) | Gets wall segments for a polygon (edges that are boundaries). Useful for edge avoidance and MoveAwayFromEdges post-processing. |
| Public method | [GetStoredQueryFilter(string)](Navigator/Methods/GetStoredQueryFilter_8236F65EA08D.md) | Gets a stored HB-compatible query filter. |
| Public method | [GetTileByPosition(Vector3)](Navigator/Methods/GetTileByPosition_F65A8991DBEA.md) | Gets tile coordinates for a world position. |
| Public method | [HasLineOfSight(uint, Vector3, Vector3)](Navigator/Methods/HasLineOfSight_05063E430EA7.md) | Checks if there's line of sight between two points on the navmesh. |
| Public method | [HasQueryFilter(string)](Navigator/Methods/HasQueryFilter_E40D1535770C.md) | Checks if a stored query filter exists by name. |
| Public method | [InitSlicedFindPath(uint, Vector3, Vector3)](Navigator/Methods/InitSlicedFindPath_40FB4594E982.md) | Initializes a sliced (async) path search. Use UpdateSlicedFindPath() to incrementally compute the path. |
| Public method | [IsPointOnNavMesh(uint, Vector3, float)](Navigator/Methods/IsPointOnNavMesh_5AED7E1764F3.md) | Checks if a point is on the navmesh. |
| Public method | [IsTileLoaded(uint, int, int)](Navigator/Methods/IsTileLoaded_B5704AF82C13.md) | Checks if a specific tile is loaded. |
| Public method | [IsWithinGarrison(Vector3)](Navigator/Methods/IsWithinGarrison_47ECD6A7F883.md) | WotLK has no garrisons. |
| Public method | [IsWithinGarrison(Vector2)](Navigator/Methods/IsWithinGarrison_5C4D53F92895.md) | WotLK has no garrisons. |
| Public method | [IsWithinGarrison(float, float)](Navigator/Methods/IsWithinGarrison_CC844572D486.md) | WotLK has no garrisons. |
| Public method | [LoadMeshes](Navigator/Methods/LoadMeshes_0F366AB62C1A.md) | Loads navigation meshes from the mmaps directory. |
| Public method | [LoadTile(TileIdentifier)](Navigator/Methods/LoadTile_7AC2BD5CFCF9.md) | HB-compatible tile load helper. |
| Public method | [LoadTileOffMesh(uint, int, int)](Navigator/Methods/LoadTileOffMesh_22ABC6840196.md) | Loads offmesh connections for a specific tile from .offmesh file. |
| Public method | [QueryPolygons(uint, Vector3, Vector3, int)](Navigator/Methods/QueryPolygons_5988A7A4E1E9.md) | Queries polygons within a bounding box centered at position. Like HB's NavMesh.QueryPolygons. |
| Public method | [Raycast(uint, Vector3, Vector3, float, Vector3)](Navigator/Methods/Raycast_C70FDAA368CD.md) | Performs a raycast from start to end position. Returns detailed raycast information including hit position and visited polygons. |
| Public method | [RaycastBlocked(uint, Vector3, Vector3, float, AreaType)](Navigator/Methods/RaycastBlocked_280A44E991C8.md) | GAP 7: Raycast with area type validation — matches HB 6.2.3 method_13. After raycast, iterates visited polygons and checks that ALL have allowed area types (Ground, Water, Road, and the player's faction area). Returns true if the path is BLOCKED (hit boundary or bad area type). |
| Public method | [RaycastWithExtents(uint, Vector3, Vector3, Vector3, float, Vector3, ulong[], int)](Navigator/Methods/RaycastWithExtents_2BC560D45FA5.md) | GAP 3: Raycast with custom extents for FindNearestPoly. HB 6.2.3 method_26 uses tight extents (0.5, 3, 0.5) for push-ahead to avoid snapping to the wrong nav-mesh layer in multi-floor areas. |
| Public method | [ResetQueryFilter](Navigator/Methods/ResetQueryFilter_AA2454E60CF1.md) | Resets query filter to default settings. |
| Public method | [SetAreaCost(uint, float)](Navigator/Methods/SetAreaCost_FFA03D46C773.md) | Sets traversal cost for an area type. Like HB WoD QueryFilter.SetAreaCost. |
| Public method | [SetAreaCost(AreaType, float)](Navigator/Methods/SetAreaCost_E19C73E89F33.md) | Sets traversal cost for an area type using AreaType enum. Like HB WoD QueryFilter.SetAreaCost. |
| Public method Static member | [SetDefaultQueryFilterCosts(WowQueryFilter)](Navigator/Methods/SetDefaultQueryFilterCosts_6EFB7F767DD1.md) | HB-compatible helper for applying default area costs. |
| Public method | [SetExcludeFlags(ushort)](Navigator/Methods/SetExcludeFlags_5EEA728E08A3.md) | Sets polygon exclude flags for pathfinding. |
| Public method | [SetFactionQueryFilter(bool)](Navigator/Methods/SetFactionQueryFilter_E3679BACD191.md) | Sets faction-aware query filter based on player faction. Ported from HB 6.2.3 WowNavigator.SetFactionQueryFilter. Excludes the opposite faction's ability flag and applies a 50x cost penalty on the opposite faction's area type (prevents pathing through enemy-only areas). |
| Public method | [SetIncludeFlags(ushort)](Navigator/Methods/SetIncludeFlags_0452C5DC623A.md) | Sets polygon include flags for pathfinding. |
| Public method | [SetPolyArea(uint, PolygonReference, byte)](Navigator/Methods/SetPolyArea_17A0AB3C74F3.md) | Sets the area type for a polygon. Like HB WoD NavMesh.SetPolyArea - used for blackspot marking. |
| Public method | [SetPolyFlags(uint, PolygonReference, ushort)](Navigator/Methods/SetPolyFlags_218624EAF9FC.md) | Sets flags for a polygon. Like HB WoD NavMesh.SetPolyFlags. |
| Public method | [SetQueryFilterByStored(string)](Navigator/Methods/SetQueryFilterByStored_52558F82EC3F.md) | Sets the current query filter from a stored filter name. |
| Public method | [StoreQueryFilter(string, WowQueryFilter)](Navigator/Methods/StoreQueryFilter_EE36D4CE6F81.md) | Stores a HB-compatible query filter by name. |
| Public method | [UnloadAllTiles](Navigator/Methods/UnloadAllTiles_069D01430999.md) | HB-compatible tile unload API. Navigation.dll streams tiles and does not expose explicit unload-all. |
| Public method | [UnloadMeshes](Navigator/Methods/UnloadMeshes_2744101F7E52.md) | Unloads all navigation meshes and releases resources. |
| Public method | [UpdatePathFollowing(uint, Vector3, Vector3[], int, int)](Navigator/Methods/UpdatePathFollowing_5033451BE1B0.md) | Updates path following with raycast shortcuts. Returns the new waypoint index to skip to if a shortcut is found. |
| Public method | [UpdateSlicedFindPath(int)](Navigator/Methods/UpdateSlicedFindPath_9F00555CBBCD.md) | Updates sliced pathfinding with iteration limit. |
| Public method | [UpdateSlicedFindPathMs(float)](Navigator/Methods/UpdateSlicedFindPathMs_21FA0736B787.md) | Updates sliced pathfinding with time budget. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Tripper.Navigation Namespace](../../../namespaces/Tripper/Navigation.md)
