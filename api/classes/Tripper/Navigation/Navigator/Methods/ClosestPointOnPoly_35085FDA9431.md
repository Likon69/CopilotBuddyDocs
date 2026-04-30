# Navigator.ClosestPointOnPoly Method

Finds the closest point on a polygon.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool ClosestPointOnPoly(uint mapId, PolygonReference polyRef, Vector3 position, out Vector3 closestPoint)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| polyRef | [PolygonReference](../../PolygonReference.md) | Polygon reference. |
| position | Vector3 | Position to check. |
| closestPoint | Vector3 | Output closest point. |

## Return Value

Type: bool
True if closest point was found.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
