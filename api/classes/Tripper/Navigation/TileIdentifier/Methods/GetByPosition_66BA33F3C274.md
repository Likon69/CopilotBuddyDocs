# TileIdentifier.GetByPosition Method

Gets the tile identifier for a given world position. Coordinates: TileX = 32 - Floor(worldY / 533.3333), TileY = 32 - Floor(worldX / 533.3333)

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static TileIdentifier GetByPosition(float x, float y)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | World X position. |
| y | float | World Y position. |

## Return Value

Type: [TileIdentifier](../../TileIdentifier.md)
TileIdentifier for the position.

## See Also
[TileIdentifier Struct](../../TileIdentifier.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
