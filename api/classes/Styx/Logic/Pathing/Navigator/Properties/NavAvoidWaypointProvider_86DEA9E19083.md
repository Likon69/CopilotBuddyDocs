# Navigator.NavAvoidWaypointProvider Property

Returns the geometric detour path (WoWPoint[]) the bot should follow to route around registered obstacles for the given destination. Null = no avoidance needed. Set by Bots.DungeonBuddy.Avoidance.WorldObstacleManager.Initialize(). HB 6.2.3 equivalent: AvoidanceNavigationProvider.MovePath() → Helpers.GetAvoidPath().

## Namespace
[Styx.Logic.Pathing](../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Func<WoWPoint, WoWPoint[]> NavAvoidWaypointProvider { get; set; }
```

## Property Value

Type: Func<WoWPoint, WoWPoint[]>
The nav avoid waypoint provider.

## See Also
[Navigator Class](../../Navigator.md)
[Styx.Logic.Pathing Namespace](../../../../../../namespaces/Styx/Logic/Pathing.md)
