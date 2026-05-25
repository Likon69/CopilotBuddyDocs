# MeshNavigator Class

Concrete NavigationProvider that wraps Tripper.Navigator (Navigation.dll). Direct port of HB 6.2.3 MeshNavigator (Styx.Pathing.MeshNavigator). Responsibilities (matching HB WoD): - Navmesh path generation (FindPath + EnsureTiles + Blackspot sync) - Path following with push-ahead (method_25/26) - Start-index skip (method_14) - Off-mesh connection dispatch (elevator, portal, interact, jump) - Door detection and interaction (method_7/8) - Stuck detection and recovery (Class469) - Drift detection (method_15) - Alive/ghost query filter (method_28) - PathPrecision-based waypoint advance (method_24/27) Not here (stays in Navigator facade): - Flightor routing, mount/dismount, avoidance wiring, bot lifecycle

## Inheritance Hierarchy
System.Object
  Styx.Logic.Pathing.NavigationProvider
    Styx.Logic.Pathing.MeshNavigator

## Namespace
[Styx.Logic.Pathing](../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class MeshNavigator : NavigationProvider
```

The MeshNavigator type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [MeshNavigator](MeshNavigator/Constructors/Constructor_4CF84559CC76.md) | Initializes a new instance of the MeshNavigator class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CurrentPath](MeshNavigator/Properties/CurrentPath_AB7F0104A968.md) | Current path waypoints. |
| Public property | [CurrentPathIndex](MeshNavigator/Properties/CurrentPathIndex_5143EDCC71E4.md) | Current waypoint index in path. |
| Public property | [Destination](MeshNavigator/Properties/Destination_BE212453DDBB.md) | Current navmesh destination. |
| Public property | [HasActivePath](MeshNavigator/Properties/HasActivePath_AE7E602329C4.md) | true when there are unvisited waypoints. |
| Public property | [IsRidingElevator](MeshNavigator/Properties/IsRidingElevator_384BFD8EF4CF.md) | true while riding an elevator. |
| Public property | [PathPrecision](MeshNavigator/Properties/PathPrecision_D55933084461.md) | HB 6.2.3 MeshNavigator.PathPrecision — default 2.0 yards. (Overrides NavigationProvider.PathPrecision.) |
| Public property | [StuckHandler](MeshNavigator/Properties/StuckHandler_C5076DC2540F.md) | HB 6.2.3 MeshNavigator.StuckHandler — Class469 instance. Lifecycle (OnSetAsCurrent/OnRemoveAsCurrent) is handled by the base class setter which guards on IsCurrent per HB NavigationProvider pattern. MeshNavigator uses _stuckHandler directly for Reset() calls. (Overrides NavigationProvider.StuckHandler.) |
| Public property | IsCurrent | Gets a value indicating whether is current. (Inherited from NavigationProvider.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [AtLocation(WoWPoint, WoWPoint)](MeshNavigator/Methods/AtLocation_BC2B574C9DAB.md) | HB 6.2.3 MeshNavigator.AtLocation — checks if two points are within PathPrecision. (Overrides NavigationProvider.AtLocation().) |
| Public method | [CanNavigateFully(WoWPoint, WoWPoint)](MeshNavigator/Methods/CanNavigateFully_3FD166F66B9C.md) | HB 6.2.3 MeshNavigator.CanNavigateFully — partial paths are not fully navigable. (Overrides NavigationProvider.CanNavigateFully().) |
| Public method | [CanNavigateWithin(WoWPoint, WoWPoint, float)](MeshNavigator/Methods/CanNavigateWithin_772BAF66CD18.md) | HB 6.2.3 MeshNavigator.CanNavigateWithin — uses the full PathFindResult endpoint. (Overrides NavigationProvider.CanNavigateWithin().) |
| Public method | [Clear](MeshNavigator/Methods/Clear_9098E2A21C03.md) | Clears all navigation state. HB 6.2.3 MeshNavigator.Clear(). (Overrides NavigationProvider.Clear().) |
| Public method | [GeneratePath(WoWPoint, WoWPoint)](MeshNavigator/Methods/GeneratePath_25C1B292F7CF.md) | Generates a navmesh path from player position to destination. HB 6.2.3 MeshNavigator.GeneratePath. (Overrides NavigationProvider.GeneratePath().) |
| Public method | [GetRemainingNavPath](MeshNavigator/Methods/GetRemainingNavPath_E5C1B21BB481.md) | Returns the remaining unvisited navmesh waypoints. Used by Bots.DungeonBuddy.Avoidance.Helpers.GetAvoidPath(). |
| Public method | [MoveTo(WoWPoint)](MeshNavigator/Methods/MoveTo_A739043256A0.md) | HB 6.2.3 MeshNavigator.MoveTo — main navigation method. Generates path if needed, follows path with push-ahead, handles offmesh/doors/stuck. (Overrides NavigationProvider.MoveTo().) |
| Public method | [MoveTo(WoWPoint, string)](MeshNavigator/Methods/MoveTo_00A812E24E39.md) | Moves to to. |
| Public method | [MoveTo(WoWPoint, float)](MeshNavigator/Methods/MoveTo_1063D3FED68D.md) | Moves to to. |
| Public method | [MoveTo(WoWPoint, float, string)](MeshNavigator/Methods/MoveTo_EA0BA1AC9E0B.md) | Moves to to. |
| Public method | [OnRemoveAsCurrent](MeshNavigator/Methods/OnRemoveAsCurrent_F8CFCBEC98D7.md) | HB 6.2.3 MeshNavigator.OnRemoveAsCurrent — unhooks BotEvents.OnPulse. Guard mirrors HB 6.2.3 bool_0: throws if not currently registered. Source: .hb 6.2.3 MeshNavigator.OnRemoveAsCurrent. (Overrides NavigationProvider.OnRemoveAsCurrent().) |
| Public method | [OnSetAsCurrent](MeshNavigator/Methods/OnSetAsCurrent_F8C514D8B8A6.md) | HB 6.2.3 MeshNavigator.OnSetAsCurrent — hooks BotEvents.OnPulse for per-pulse faction update + tile streaming (Class1039.method_0 equivalent). Guard mirrors HB 6.2.3 bool_0: throws if already current. Source: .hb 6.2.3 MeshNavigator.OnSetAsCurrent. (Overrides NavigationProvider.OnSetAsCurrent().) |
| Public method | [OverrideCurrentPath(WoWPoint[])](MeshNavigator/Methods/OverrideCurrentPath_EF504803D9BC.md) | Replaces the active navmesh path. Called by Helpers.GetAvoidPath(). HB 6.2.3: CurrentMovePath.Path = FindPath(from, to); Index = 0. |
| Public method | [PathDistance(WoWPoint, WoWPoint, float)](MeshNavigator/Methods/PathDistance_190F72582F18.md) | HB 6.2.3 MeshNavigator.PathDistance — returns null for failed or partial paths. (Overrides NavigationProvider.PathDistance().) |
| Public method | [SetFactionAreaType(AreaType)](MeshNavigator/Methods/SetFactionAreaType_3C4797356373.md) | Sets faction area type. Called by Navigator on bot start. |
| Public method | [UpdateMaps](MeshNavigator/Methods/UpdateMaps_F29437AF7BEA.md) | HB 6.2.3 MeshNavigator.UpdateMaps(): Preloads navmesh tiles around player position each pulse (Class1039.method_0). |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing Namespace](../../../../namespaces/Styx/Logic/Pathing.md)
