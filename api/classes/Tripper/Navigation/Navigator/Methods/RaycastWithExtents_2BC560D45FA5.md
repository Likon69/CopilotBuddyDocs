# Navigator.RaycastWithExtents Method

GAP 3: Raycast with custom extents for FindNearestPoly. HB 6.2.3 method_26 uses tight extents (0.5, 3, 0.5) for push-ahead to avoid snapping to the wrong nav-mesh layer in multi-floor areas.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public Status RaycastWithExtents(uint mapId, Vector3 start, Vector3 end, Vector3 customExtents, out float hitT, out Vector3 hitNormal, out ulong[] visitedPolys, out int visitedCount)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | The map id. |
| start | Vector3 | The start. |
| end | Vector3 | The end. |
| customExtents | Vector3 | The custom extents. |
| hitT | float | The hit t. |
| hitNormal | Vector3 | The hit normal. |
| visitedPolys | ulong[] | The visited polys. |
| visitedCount | int | The visited count. |

## Return Value

Type: [Status](../../Status.md)
The result of the operation.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
