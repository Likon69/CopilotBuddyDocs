# Navigator.FindNearestPolyRef Method

Finds the nearest polygon reference to a position.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool FindNearestPolyRef(uint mapId, Vector3 position, out PolygonReference polyRef, out Vector3 nearestPoint)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| position | Vector3 | Position to search from. |
| polyRef | [PolygonReference](../../PolygonReference.md) | Output polygon reference. |
| nearestPoint | Vector3 | Output nearest point on polygon. |

## Return Value

Type: bool
True if a polygon was found.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
