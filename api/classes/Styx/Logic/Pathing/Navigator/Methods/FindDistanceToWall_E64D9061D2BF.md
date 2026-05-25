# Navigator.FindDistanceToWall Method

HB 6.2.3 MeshNavigator.DistToWall — finds the nearest navmesh wall/boundary distance. Used by GetBestLocationOutsideCluster to reject candidates that are too close to walls (distance < 1 yard). A candidate right next to a wall means the character would immediately re-enter the avoid zone the next time it bumps into geometry. Thin wrapper over TripperNavigator.FindDistanceToWall → Navigation.dll FindDistanceToWall.

## Namespace
[Styx.Logic.Pathing](../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static float FindDistanceToWall(WoWPoint position, float maxRadius)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| position | [WoWPoint](../../WoWPoint.md) | Point to measure from. |
| maxRadius | float | Maximum search radius (use 5f to match HB 6.2.3 Helpers.smethod_4). |

## Return Value

Type: float
Distance to the nearest wall, or 0f if the navigator is not loaded.

## See Also
[Navigator Class](../../Navigator.md)
[Styx.Logic.Pathing Namespace](../../../../../../namespaces/Styx/Logic/Pathing.md)
