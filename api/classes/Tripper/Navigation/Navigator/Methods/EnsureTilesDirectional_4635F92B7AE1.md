# Navigator.EnsureTilesDirectional Method

Prefetches tiles in movement direction for smoother streaming. Call this regularly during movement for best performance.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public void EnsureTilesDirectional(uint mapId, Vector3 position, Vector3 velocity, int ring)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| position | Vector3 | Current position. |
| velocity | Vector3 | Current velocity/movement direction. |
| ring | int | Base tile ring radius. |

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
