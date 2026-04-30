# BlackspotManager Class

Manages blackspots - areas to avoid during navigation. Blackspots can be added from profiles or dynamically at runtime. Like HB 4.3.4, this marks navmesh polygons with AreaType.Misc7 (26) and sets a high path cost (60f) to make the pathfinder avoid them.

## Namespace
[Styx.Logic.Pathing](../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class BlackspotManager
```

The BlackspotManager type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public class | [BlackspotManager.GlobalBlackspot](BlackspotManager/GlobalBlackspot.md) | Represents a global blackspot that is saved across sessions. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [Blackspots](BlackspotManager/Properties/Blackspots_A68E6577326E.md) | Gets all current blackspots (profile + runtime added). |
| Public property Static member | [GlobalBlackspots](BlackspotManager/Properties/GlobalBlackspots_E02194166909.md) | Gets all global blackspots (persisted across sessions). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [AddBlackspot(WoWPoint, float, float)](BlackspotManager/Methods/AddBlackspot_70AF8359494B.md) | Adds a blackspot at the specified location. |
| Public method Static member | [AddBlackspots(IEnumerable<Blackspot>)](BlackspotManager/Methods/AddBlackspots_6B603EE31A0B.md) | Adds multiple blackspots and marks the corresponding navmesh polygons. Like HB 4.3.4: QueryPolygons + SetPolyArea(26) + SetAreaCost(60f) |
| Public method Static member | [AddGlobalBlackspot(GlobalBlackspot)](BlackspotManager/Methods/AddGlobalBlackspot_FDF2DF72690B.md) | Adds a global blackspot. |
| Public method Static member | [AddGlobalBlackspot(WoWPoint, float, float)](BlackspotManager/Methods/AddGlobalBlackspot_FD681D5C4BA1.md) | Adds a global blackspot that persists across sessions. |
| Public method Static member | [ClearBlackspots](BlackspotManager/Methods/ClearBlackspots_EC69F3009F19.md) | Clears all non-global blackspots. |
| Public method Static member | [EnsureBlackspotsMarked](BlackspotManager/Methods/EnsureBlackspotsMarked_343A0B6D90EA.md) | Ensures all blackspots are marked on the navmesh. Call this before pathfinding to ensure tiles are loaded and blackspots applied. This is the substitute for HB's OnTileLoaded callback. |
| Public method Static member | [IsBlackspotted(WoWPoint, float)](BlackspotManager/Methods/IsBlackspotted_1B6A6C5AC9CB.md) | Checks if a location is within any blackspot. |
| Public method Static member | [LoadGlobalBlackspots](BlackspotManager/Methods/LoadGlobalBlackspots_4954EC0F1B87.md) | Loads global blackspots from file. |
| Public method Static member | [RemoveBlackspot(Blackspot)](BlackspotManager/Methods/RemoveBlackspot_30D722AFF5F5.md) | Removes a blackspot. |
| Public method Static member | [RemoveBlackspots(IEnumerable<Blackspot>)](BlackspotManager/Methods/RemoveBlackspots_56A5D6B1D012.md) | Removes multiple blackspots. |
| Public method Static member | [RemoveGlobalBlackspot(GlobalBlackspot)](BlackspotManager/Methods/RemoveGlobalBlackspot_C815E75DE42B.md) | Removes a global blackspot. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing Namespace](../../../../namespaces/Styx/Logic/Pathing.md)
