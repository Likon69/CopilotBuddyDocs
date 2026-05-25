# Helpers Class

Provides helper methods for avoid tracing and clustering.

## Namespace
[Bots.DungeonBuddy.Avoidance](../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class Helpers
```

The Helpers type exposes the following members.

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [AvoidClusterTraceline(List<AvoidCluster>, Vector3, Vector3)](Helpers/Methods/AvoidClusterTraceline_E3F66AC8C5CB.md) | Checks a traceline against avoid clusters. |
| Public method Static member | [AvoidTraceline(Avoid, Vector3, Vector3)](Helpers/Methods/AvoidTraceline_19751ACA05C1.md) | Checks a traceline against an avoid. |
| Public method Static member | [BuildClusters(List<Avoid>, List<AvoidCluster>)](Helpers/Methods/BuildClusters_CBA82DB428E0.md) | Builds avoid clusters. |
| Public method Static member | [CalculatePointFrom(Vector3, Vector3, float)](Helpers/Methods/CalculatePointFrom_1A8FFC6BB46C.md) | Calculates a point from the origin toward the destination. |
| Public method Static member | [ClearAvoidPath](Helpers/Methods/ClearAvoidPath_02960EA95D33.md) | Clears the avoid path. |
| Public method Static member | [GetAvoidPath(WoWPoint)](Helpers/Methods/GetAvoidPath_898EEAB0509F.md) | Gets the avoid path. |
| Public method Static member | [GetAvoidWaypoints(WoWPoint)](Helpers/Methods/GetAvoidWaypoints_CF863C6A1806.md) | Wrapper consumed by Navigator.NavAvoidWaypointProvider. Returns the current avoidance detour as WoWPoint[] (remaining waypoints from Index), or null when no avoidance is needed. HB 6.2.3 AvoidanceNavigationProvider.MovePath() pattern. |
| Public method Static member | [GetAvoidsHitByTraceline(IEnumerable<Avoid>, Vector3, Vector3)](Helpers/Methods/GetAvoidsHitByTraceline_E5BB3C360A70.md) | Gets the avoids hit by traceline. |
| Public method Static member | [GetBestLocationOutsideCluster(Vector3, Vector3, int, AvoidCluster, float)](Helpers/Methods/GetBestLocationOutsideCluster_C43F83C49732.md) | HB 6.2.3 Helpers.GetBestLocationOutsideCluster — goal-directed cluster escape. Nudges the search origin toward 'goal' by up to 'goalPriority' units before scanning exit directions, so the bot exits on the side closest to its current target. CB uses the same Navigation.dll that HB's RecastManaged wraps, so all three checks are now exact ports: - FindNearestPolyRef → candidate is on the navmesh - Raycast hitT == FLT_MAX → no wall between searchOrigin and candidate - FindDistanceToWall > 1f → candidate is not right next to a wall AvoidInfo.Priority is now wired in; dungeon scripts can set priority=High on instant-kill avoids so they dominate the exit-score and are escaped first. |
| Public method Static member | [GetLineCircleIntersections(Vector3, float, Vector3, Vector3, Vector3, Vector3)](Helpers/Methods/GetLineCircleIntersections_F074F65D5919.md) | Gets the line circle intersections. |
| Public method Static member | [GetLineCircleTangentPoints(Vector3, float, Vector3)](Helpers/Methods/GetLineCircleTangentPoints_5D6F9657EF1F.md) | Gets the line circle tangent points. |
| Public method Static member | [GetNearestLocationOutsideCluster(Vector3, AvoidCluster, float)](Helpers/Methods/GetNearestLocationOutsideCluster_473947336D57.md) | Gets the nearest location outside cluster. |
| Public method Static member | [GetPointAt(Vector3, float, float, float)](Helpers/Methods/GetPointAt_F97219F1F323.md) | Gets the point at. |
| Public method Static member | [LineAvoidCollision(Avoid, Vector3, Vector3)](Helpers/Methods/LineAvoidCollision_E4596A2DCF45.md) | Checks line collision against an avoid. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy.Avoidance Namespace](../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)
