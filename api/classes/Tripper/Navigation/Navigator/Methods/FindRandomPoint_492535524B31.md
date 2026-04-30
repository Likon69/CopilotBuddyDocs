# Navigator.FindRandomPoint Method

Finds a random navigable point within radius of center position.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool FindRandomPoint(uint mapId, Vector3 center, float radius, out Vector3 randomPoint)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| center | Vector3 | Center position. |
| radius | float | Search radius in yards. |
| randomPoint | Vector3 | Output random valid point. |

## Return Value

Type: bool
True if a random point was found.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
