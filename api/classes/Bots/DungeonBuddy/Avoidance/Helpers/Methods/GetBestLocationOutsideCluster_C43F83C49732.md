# Helpers.GetBestLocationOutsideCluster Method

HB 6.2.3 Helpers.GetBestLocationOutsideCluster — goal-directed cluster escape. Nudges the search origin toward 'goal' by up to 'goalPriority' units before scanning exit directions, so the bot exits on the side closest to its current target. CB uses the same Navigation.dll that HB's RecastManaged wraps, so all three checks are now exact ports: - FindNearestPolyRef → candidate is on the navmesh - Raycast hitT == FLT_MAX → no wall between searchOrigin and candidate - FindDistanceToWall > 1f → candidate is not right next to a wall AvoidInfo.Priority is now wired in; dungeon scripts can set priority=High on instant-kill avoids so they dominate the exit-score and are escaped first.

## Namespace
[Bots.DungeonBuddy.Avoidance](../../../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Vector3 GetBestLocationOutsideCluster(Vector3 from, Vector3 goal, int goalPriority, AvoidCluster cluster, float extendDistance)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| from | [Vector3](../../../../../Tripper/Tools/Math/Vector3.md) | The from. |
| goal | [Vector3](../../../../../Tripper/Tools/Math/Vector3.md) | The goal. |
| goalPriority | int | The goal priority. |
| cluster | [AvoidCluster](../../AvoidCluster.md) | The cluster. |
| extendDistance | float | The extend distance. |

## Return Value

Type: [Vector3](../../../../../Tripper/Tools/Math/Vector3.md)
The result of the operation.

## See Also
[Helpers Class](../../Helpers.md)
[Bots.DungeonBuddy.Avoidance Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)
