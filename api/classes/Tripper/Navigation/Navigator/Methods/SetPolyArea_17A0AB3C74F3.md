# Navigator.SetPolyArea Method

Sets the area type for a polygon. Like HB WoD NavMesh.SetPolyArea - used for blackspot marking.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public uint SetPolyArea(uint mapId, PolygonReference polyRef, byte area)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| polyRef | [PolygonReference](../../PolygonReference.md) | Polygon reference. |
| area | byte | Area type ID (0-63). |

## Return Value

Type: uint
Detour status (success if high bit set).

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
