# Navigator.GetPolyWallSegments Method

Gets wall segments for a polygon (edges that are boundaries). Useful for edge avoidance and MoveAwayFromEdges post-processing.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public (Vector3 start, Vector3 end)[] GetPolyWallSegments(uint mapId, PolygonReference polyRef, int maxSegments)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| polyRef | [PolygonReference](../../PolygonReference.md) | Polygon reference. |
| maxSegments | int | Maximum segments to return. |

## Return Value

Type: (Vector3 start, Vector3 end)[]
List of wall segments (start, end point pairs).

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
