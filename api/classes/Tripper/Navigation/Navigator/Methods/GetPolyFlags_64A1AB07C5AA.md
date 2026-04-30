# Navigator.GetPolyFlags Method

Gets flags for a polygon. Like HB WoD NavMesh.GetPolyFlags.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public uint GetPolyFlags(uint mapId, PolygonReference polyRef, out ushort flags)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| polyRef | [PolygonReference](../../PolygonReference.md) | Polygon reference. |
| flags | ushort | Output polygon flags. |

## Return Value

Type: uint
Detour status (success if high bit set).

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
