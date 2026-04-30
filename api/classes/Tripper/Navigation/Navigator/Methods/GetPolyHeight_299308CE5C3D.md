# Navigator.GetPolyHeight Method

Gets the height at a position on a specific polygon.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool GetPolyHeight(uint mapId, PolygonReference polyRef, Vector3 position, out float height)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| polyRef | [PolygonReference](../../PolygonReference.md) | Polygon reference. |
| position | Vector3 | Position to check. |
| height | float | Output height. |

## Return Value

Type: bool
True if height was found.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
