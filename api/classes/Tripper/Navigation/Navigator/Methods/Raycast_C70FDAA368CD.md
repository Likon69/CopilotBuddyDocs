# Navigator.Raycast Method

Performs a raycast from start to end position. Returns detailed raycast information including hit position and visited polygons.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public Status Raycast(uint mapId, Vector3 start, Vector3 end, out float hitT, out Vector3 hitNormal)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| start | Vector3 | Ray start position. |
| end | Vector3 | Ray end position. |
| hitT | float | Output normalized hit distance (0-1, 1.0 = no hit). |
| hitNormal | Vector3 | Output hit normal vector. |

## Return Value

Type: [Status](../../Status.md)
Detour status code.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
