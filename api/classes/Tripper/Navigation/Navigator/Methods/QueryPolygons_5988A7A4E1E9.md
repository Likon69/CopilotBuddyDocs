# Navigator.QueryPolygons Method

Queries polygons within a bounding box centered at position. Like HB's NavMesh.QueryPolygons.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public PolygonReference[] QueryPolygons(uint mapId, Vector3 center, Vector3 extents, int maxResults)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| center | Vector3 | Center of search area. |
| extents | Vector3 | Search extents (half-dimensions). |
| maxResults | int | Maximum polygons to return. |

## Return Value

Type: [PolygonReference](../../PolygonReference.md)[]
Array of polygon references found.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
