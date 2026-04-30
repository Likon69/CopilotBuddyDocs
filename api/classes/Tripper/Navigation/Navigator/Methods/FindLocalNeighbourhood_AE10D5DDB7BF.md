# Navigator.FindLocalNeighbourhood Method

Finds local polygon neighbourhood around a starting polygon. Useful for local obstacle detection and area analysis.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public PolygonReference[] FindLocalNeighbourhood(uint mapId, PolygonReference startPoly, Vector3 center, float radius, int maxResults)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| startPoly | [PolygonReference](../../PolygonReference.md) | Starting polygon reference. |
| center | Vector3 | Center position. |
| radius | float | Search radius. |
| maxResults | int | Maximum results. |

## Return Value

Type: [PolygonReference](../../PolygonReference.md)[]
Array of polygon references in the neighbourhood.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
