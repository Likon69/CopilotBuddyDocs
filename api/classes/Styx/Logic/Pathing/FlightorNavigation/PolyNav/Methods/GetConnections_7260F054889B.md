# PolyNav.GetConnections Method

Returns the neighbour positions of the graph node closest to . Sets to that node's exact position. (method GetConnections in WoD PolyNav source)

## Namespace
[Styx.Logic.Pathing.FlightorNavigation](../../../../../../../namespaces/Styx/Logic/Pathing/FlightorNavigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public IEnumerable<Vector2> GetConnections(Vector2 point, out Vector2 closestPoint)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| point | [Vector2](../../../../../../Tripper/XNAMath/Vector2.md) | The point. |
| closestPoint | [Vector2](../../../../../../Tripper/XNAMath/Vector2.md) | The closest point. |

## Return Value

Type: IEnumerable<Vector2>
The result of the operation.

## See Also
[PolyNav Class](../../PolyNav.md)
[Styx.Logic.Pathing.FlightorNavigation Namespace](../../../../../../../namespaces/Styx/Logic/Pathing/FlightorNavigation.md)
