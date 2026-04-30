# Navigator.GetPolyArea Method

Gets the area type for a polygon. Like HB WoD NavMesh.GetPolyArea.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public uint GetPolyArea(uint mapId, PolygonReference polyRef, out byte area)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| polyRef | [PolygonReference](../../PolygonReference.md) | Polygon reference. |
| area | byte | Output area type. |

## Return Value

Type: uint
Detour status (success if high bit set).

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
