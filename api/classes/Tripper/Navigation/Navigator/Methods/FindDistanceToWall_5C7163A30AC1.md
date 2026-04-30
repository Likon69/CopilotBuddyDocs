# Navigator.FindDistanceToWall Method

Finds distance to the nearest wall/boundary from a position.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public float FindDistanceToWall(uint mapId, Vector3 position, float maxRadius, out Vector3 hitPoint)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| position | Vector3 | Position to check. |
| maxRadius | float | Maximum search radius. |
| hitPoint | Vector3 | Output hit point on wall. |

## Return Value

Type: float
Distance to wall, or -1 if failed.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
