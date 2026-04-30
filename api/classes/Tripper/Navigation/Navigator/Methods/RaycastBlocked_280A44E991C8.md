# Navigator.RaycastBlocked Method

GAP 7: Raycast with area type validation — matches HB 6.2.3 method_13. After raycast, iterates visited polygons and checks that ALL have allowed area types (Ground, Water, Road, and the player's faction area). Returns true if the path is BLOCKED (hit boundary or bad area type).

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool RaycastBlocked(uint mapId, Vector3 start, Vector3 end, out float hitT, AreaType factionArea)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| start | Vector3 | Ray start position. |
| end | Vector3 | Ray end position. |
| hitT | float | Output normalized hit distance. |
| factionArea | [AreaType](../../AreaType.md) | Player faction area type (Horde or Alliance) — HB 6.2.3 areaType_0. |

## Return Value

Type: bool
True if blocked (hit boundary OR traverses disallowed area type), false if clear.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
