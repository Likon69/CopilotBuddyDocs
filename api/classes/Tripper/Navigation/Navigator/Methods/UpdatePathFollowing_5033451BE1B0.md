# Navigator.UpdatePathFollowing Method

Updates path following with raycast shortcuts. Returns the new waypoint index to skip to if a shortcut is found.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public int UpdatePathFollowing(uint mapId, Vector3 currentPos, Vector3[] path, int currentWaypointIndex, int agentId)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| currentPos | Vector3 | Current position. |
| path | Vector3[] | Path points array. |
| currentWaypointIndex | int | Current waypoint index. |
| agentId | int | Agent ID for multi-agent support. |

## Return Value

Type: int
New waypoint index (may be ahead if shortcut found).

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
