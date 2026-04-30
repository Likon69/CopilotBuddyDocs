# Navigator.FindPath Method

Calculates a path from start to end position. Uses CalculatePathEx for complete path information including flags and area types.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public PathFindResult FindPath(uint mapId, Vector3 start, Vector3 end, bool straightPath)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID to pathfind on. |
| start | Vector3 | Starting position. |
| end | Vector3 | Destination position. |
| straightPath | bool | If true, returns straight path; otherwise returns polygon corridor. |

## Return Value

Type: [PathFindResult](../../PathFindResult.md)
PathFindResult containing the calculated path.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
