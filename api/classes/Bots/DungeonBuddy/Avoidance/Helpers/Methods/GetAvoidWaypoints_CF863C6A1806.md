# Helpers.GetAvoidWaypoints Method

Wrapper consumed by Navigator.NavAvoidWaypointProvider. Returns the current avoidance detour as WoWPoint[] (remaining waypoints from Index), or null when no avoidance is needed. HB 6.2.3 AvoidanceNavigationProvider.MovePath() pattern.

## Namespace
[Bots.DungeonBuddy.Avoidance](../../../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static WoWPoint[] GetAvoidWaypoints(WoWPoint destination)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| destination | [WoWPoint](../../../../../Styx/Logic/Pathing/WoWPoint.md) | The destination. |

## Return Value

Type: [WoWPoint](../../../../../Styx/Logic/Pathing/WoWPoint.md)[]
The result of the operation.

## See Also
[Helpers Class](../../Helpers.md)
[Bots.DungeonBuddy.Avoidance Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)
