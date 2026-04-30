# Navigator.EnsureTilesAroundPosition Method

Ensures tiles around position are loaded (HB-style streaming). Use this before pathfinding to ensure navmesh coverage.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public void EnsureTilesAroundPosition(uint mapId, Vector3 position, int ring)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| position | Vector3 | Center position. |
| ring | int | Tile ring radius (2 = 5x5 tiles). |

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
