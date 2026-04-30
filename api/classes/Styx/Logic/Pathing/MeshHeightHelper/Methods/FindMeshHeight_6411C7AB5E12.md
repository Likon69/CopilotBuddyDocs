# MeshHeightHelper.FindMeshHeight Method

Finds the mesh height at the given position, searching nearby if not found directly.

## Namespace
[Styx.Logic.Pathing](../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool FindMeshHeight(ref Vector3 position)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| position | Vector3 | The position to find height for. Z will be modified if found. |

## Return Value

Type: bool
True if a valid height was found, false otherwise.

## See Also
[MeshHeightHelper Class](../../MeshHeightHelper.md)
[Styx.Logic.Pathing Namespace](../../../../../../namespaces/Styx/Logic/Pathing.md)
