# Navigator.GetNavMeshQueryPtr Method

Gets direct pointer to dtNavMeshQuery for advanced NavBridge use. WARNING: Use with caution - direct Detour access.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public nint GetNavMeshQueryPtr(uint mapId)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |

## Return Value

Type: nint
Pointer to dtNavMeshQuery, or IntPtr.Zero if unavailable.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
