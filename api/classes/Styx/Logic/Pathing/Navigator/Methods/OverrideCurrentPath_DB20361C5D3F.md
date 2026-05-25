# Navigator.OverrideCurrentPath Method

Replaces the active navmesh path. Called by Helpers.GetAvoidPath() when the obstacle set changes and a fresh path from current position is needed. Equivalent to HB 6.2.3: CurrentMovePath.Path = FindPath(from, to); Index = 0.

## Namespace
[Styx.Logic.Pathing](../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static void OverrideCurrentPath(WoWPoint[] points)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| points | [WoWPoint](../../WoWPoint.md)[] | The points. |

## See Also
[Navigator Class](../../Navigator.md)
[Styx.Logic.Pathing Namespace](../../../../../../namespaces/Styx/Logic/Pathing.md)
