# Navigator Class

Represents a navigator.

## Namespace
[Styx.Logic.Pathing](../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class Navigator
```

The Navigator type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [CurrentPath](Navigator/Properties/CurrentPath_9CA28F676291.md) | Gets the current path. |
| Public property Static member | [CurrentProvider](Navigator/Properties/CurrentProvider_CCEDB2A82B5B.md) | Convenience alias used by older HB code. |
| Public property Static member | [Destination](Navigator/Properties/Destination_FD2F30723D1D.md) | Gets the destination. |
| Public property Static member | [FlyingMountHeight](Navigator/Properties/FlyingMountHeight_1DFB02655522.md) | Gets or sets the flying mount height. |
| Public property Static member | [HasActivePath](Navigator/Properties/HasActivePath_5EBB44194B1E.md) | true when there are unvisited waypoints in the current navmesh path. |
| Public property Static member | [HeightProvider](Navigator/Properties/HeightProvider_FE2A902BEFF5.md) | Gets or sets the height provider. |
| Public property Static member | [IsInNoFlyZone](Navigator/Properties/IsInNoFlyZone_42930D9DF754.md) | Checks if the current zone is a no-fly zone (P6.10 — Dalaran etc.). |
| Public property Static member | [IsNavigatorLoaded](Navigator/Properties/IsNavigatorLoaded_F44CE97F845A.md) | Whether the underlying Tripper navigator instance has finished loading its meshes. Mirrors HB's Navigator.IsNavigatorLoaded property. |
| Public property Static member | [IsRidingElevator](Navigator/Properties/IsRidingElevator_916E2CF8DC55.md) | true if currently riding an elevator (blocks mount-up). |
| Public property Static member | [LoadTilesAroundRadius](Navigator/Properties/LoadTilesAroundRadius_40BD94F7FA25.md) | Gets or sets the load tiles around radius. |
| Public property Static member | [NavAvoidWaypointProvider](Navigator/Properties/NavAvoidWaypointProvider_86DEA9E19083.md) | Returns the geometric detour path (WoWPoint[]) the bot should follow to route around registered obstacles for the given destination. Null = no avoidance needed. Set by Bots.DungeonBuddy.Avoidance.WorldObstacleManager.Initialize(). HB 6.2.3 equivalent: AvoidanceNavigationProvider.MovePath() → Helpers.GetAvoidPath(). |
| Public property Static member | [NavAvoidanceUpdater](Navigator/Properties/NavAvoidanceUpdater_A72F55C70563.md) | Called every WoWPulsator tick to scan ObjectManager and refresh avoidance zones. Set by Bots.DungeonBuddy.Avoidance.WorldObstacleManager.Initialize(). |
| Public property Static member | [NavigationProvider](Navigator/Properties/NavigationProvider_F49F377A8492.md) | The active navigation provider. Setting this property raises the event if the value differs. |
| Public property Static member | [PathPrecision](Navigator/Properties/PathPrecision_AE469996E5E8.md) | Gets or sets the path precision. |
| Public property Static member | [PlayerMover](Navigator/Properties/PlayerMover_27EFA7C8F4A5.md) | Gets or sets the player mover used for movement control. |
| Public property Static member | [StuckHandler](Navigator/Properties/StuckHandler_7CBD26F04AC9.md) | Gets or sets the stuck handler used for stuck detection and recovery. |
| Public property Static member | [TripperNavigator](Navigator/Properties/TripperNavigator_434CC577D7F1.md) | Gets or creates the Tripper navigator instance. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event Static member | [OnHeightProviderChanged](Navigator/Events/OnHeightProviderChanged_613383639F0F.md) | Occurs when height provider changes. |
| Public event Static member | [OnNavigationProviderChanged](Navigator/Events/OnNavigationProviderChanged_8544D27EEB3B.md) | Fired when is replaced. Consumers such as can (re)wire tile events. |
| Public event Static member | [OnPlayerMoverChanged](Navigator/Events/OnPlayerMoverChanged_3683C0E8F728.md) | Occurs when player mover changes. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [AtLocation(WoWPoint)](Navigator/Methods/AtLocation_ECB771D295AD.md) | true if the player is at the given point (HB 6.2.3 Navigator.AtLocation(WoWPoint)). |
| Public method Static member | [AtLocation(WoWPoint, WoWPoint)](Navigator/Methods/AtLocation_932E04138F96.md) | HB 6.2.3 Navigator.AtLocation — delegates to NavigationProvider.AtLocation. |
| Public method Static member | [CanNavigateFully(WoWPoint)](Navigator/Methods/CanNavigateFully_FA2E72234274.md) | Determines whether can navigate fully. |
| Public method Static member | [CanNavigateFully(WoWPoint, WoWPoint)](Navigator/Methods/CanNavigateFully_6F276E85F7B0.md) | Determines whether can navigate fully. |
| Public method Static member | [CanNavigateWithin(WoWPoint, WoWPoint, float)](Navigator/Methods/CanNavigateWithin_00BD8BE4D0BA.md) | Determines whether can navigate within. |
| Public method Static member | [CanNavigateWithinDistance(WoWPoint, WoWPoint, float)](Navigator/Methods/CanNavigateWithinDistance_28F2E5BEB7C4.md) | Mirrors HB 4.3.4 Class81.method_10: returns true only if the actual nav path from to is complete (not partial) and its total length in yards is ≤ . Used by DungeonTargeting to reject through-wall mobs whose straight-line distance is within range but whose nav path winds far around the dungeon geometry. |
| Public method Static member | [Clear](Navigator/Methods/Clear_9889366B499C.md) | Clears the current contents. |
| Public method Static member | [ComputeRawPath(WoWPoint, WoWPoint)](Navigator/Methods/ComputeRawPath_93E9C1C883B6.md) | Pathfinds from → to via TripperNavigator and returns the waypoints as WoWPoint[]. Lightweight wrapper: no tile pre-load, no blackspot sync. For avoidance use only. |
| Public method Static member | [Dispose](Navigator/Methods/Dispose_F42222DA98D4.md) | Disposes the navigator and releases resources. |
| Public method Static member | [FindDistanceToWall(WoWPoint, float)](Navigator/Methods/FindDistanceToWall_E64D9061D2BF.md) | HB 6.2.3 MeshNavigator.DistToWall — finds the nearest navmesh wall/boundary distance. Used by GetBestLocationOutsideCluster to reject candidates that are too close to walls (distance < 1 yard). A candidate right next to a wall means the character would immediately re-enter the avoid zone the next time it bumps into geometry. Thin wrapper over TripperNavigator.FindDistanceToWall → Navigation.dll FindDistanceToWall. |
| Public method Static member | [FindHeight(Vector3)](Navigator/Methods/FindHeight_797ACE3C9B7E.md) | HB 6.2.3 Navigator.FindHeight(ref Vector3) — modifies Z in place. |
| Public method Static member | [FindHeight(float, float, float)](Navigator/Methods/FindHeight_BB8967353C66.md) | HB 6.2.3 Navigator.FindHeight(x,y,out z) — takes first height from FindHeights. |
| Public method Static member | [FindHeights(float, float)](Navigator/Methods/FindHeights_129A2A8499B4.md) | HB 6.2.3 Navigator.FindHeights — delegates to HeightProvider.FindHeights. |
| Public method Static member | [FindMeshHeight(Vector3)](Navigator/Methods/FindMeshHeight_590D6F7BFE83.md) | Finds the mesh height at a given position. |
| Public method Static member | [FindMeshHeight(float, float, float)](Navigator/Methods/FindMeshHeight_DDB9B9D2DFCF.md) | Finds the mesh height at a given XY position. |
| Public method Static member | [FindNearestPoint(WoWPoint)](Navigator/Methods/FindNearestPoint_856D5A3AC3CF.md) | Finds the nearest navigable point to a given position. |
| Public method Static member | [FindRandomPoint(WoWPoint, float)](Navigator/Methods/FindRandomPoint_9ADF40765E11.md) | Finds a random navigable point within radius of center position. |
| Public method Static member | [GeneratePath(WoWPoint, WoWPoint)](Navigator/Methods/GeneratePath_40F635C5C850.md) | Generates a path. |
| Public method Static member | [GetNavigationProviderAs](Navigator/Methods/GetNavigationProviderAs_5A6176A9C085.md) | HB 6.2.3 Navigator.GetNavigationProviderAs — convenience cast helper. |
| Public method Static member | [GetRemainingNavPath](Navigator/Methods/GetRemainingNavPath_EE816230959C.md) | Returns the remaining unvisited navmesh waypoints from the current path index. Used internally by Bots.DungeonBuddy.Avoidance.Helpers.GetAvoidPath(). |
| Public method Static member | [GetRunStatusFromMoveResult(MoveResult)](Navigator/Methods/GetRunStatusFromMoveResult_306C24F2594E.md) | Converts a MoveResult to a TreeSharp RunStatus. Direct port of HB 6.2.3 Navigator.GetRunStatusFromMoveResult. |
| Public method Static member | [IsPathSafe(IList<WoWPoint>)](Navigator/Methods/IsPathSafe_952069E83D4C.md) | Determines whether is path safe. |
| Public method Static member | [MoveTo(WoWPoint)](Navigator/Methods/MoveTo_7B22B4359F45.md) | Moves to to. |
| Public method Static member | [MoveTo(WoWPoint, string)](Navigator/Methods/MoveTo_494D1FC9C5F6.md) | Moves to to. |
| Public method Static member | [MoveTo(WoWPoint, float)](Navigator/Methods/MoveTo_6D6931B10115.md) | Moves to to. |
| Public method Static member | [MoveTo(WoWPoint, float, string)](Navigator/Methods/MoveTo_6FBC07624DFD.md) | Moves to to. |
| Public method Static member | [OverrideCurrentPath(WoWPoint[])](Navigator/Methods/OverrideCurrentPath_DB20361C5D3F.md) | Replaces the active navmesh path. Called by Helpers.GetAvoidPath() when the obstacle set changes and a fresh path from current position is needed. Equivalent to HB 6.2.3: CurrentMovePath.Path = FindPath(from, to); Index = 0. |
| Public method Static member | [PathDistance(WoWPoint, WoWPoint, float)](Navigator/Methods/PathDistance_5B066B809A17.md) | HB 6.2.3 Navigator.PathDistance — delegates to NavigationProvider.PathDistance. Falls back to raw Tripper path calculation when no provider is set. |
| Public method Static member | [Raycast(WoWPoint, WoWPoint, WoWPoint)](Navigator/Methods/Raycast_433631170323.md) | Performs a raycast from start to end position on the navmesh. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing Namespace](../../../../namespaces/Styx/Logic/Pathing.md)
