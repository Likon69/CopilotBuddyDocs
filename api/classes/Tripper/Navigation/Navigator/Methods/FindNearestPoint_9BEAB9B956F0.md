# Navigator.FindNearestPoint Method

Finds the nearest valid navmesh point to a given position.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool FindNearestPoint(uint mapId, Vector3 position, out Vector3 nearestPoint)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| position | Vector3 | Position to search from. |
| nearestPoint | Vector3 | Output nearest valid point. |

## Return Value

Type: bool
True if a valid point was found.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
