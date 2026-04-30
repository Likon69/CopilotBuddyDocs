# PolyNav.FindPath Method

Find a 2D path from to . Returns an empty array if either point is outside the navigable area. Returns {start, end} if a straight line is clear. Otherwise returns visibility-graph waypoints via A*.

## Namespace
[Styx.Logic.Pathing.FlightorNavigation](../../../../../../../namespaces/Styx/Logic/Pathing/FlightorNavigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public Vector2[] FindPath(Vector2 start, Vector2 end)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| start | [Vector2](../../../../../../Tripper/XNAMath/Vector2.md) | The start. |
| end | [Vector2](../../../../../../Tripper/XNAMath/Vector2.md) | The end. |

## Return Value

Type: [Vector2](../../../../../../Tripper/XNAMath/Vector2.md)[]
The result of the operation.

## See Also
[PolyNav Class](../../PolyNav.md)
[Styx.Logic.Pathing.FlightorNavigation Namespace](../../../../../../../namespaces/Styx/Logic/Pathing/FlightorNavigation.md)
