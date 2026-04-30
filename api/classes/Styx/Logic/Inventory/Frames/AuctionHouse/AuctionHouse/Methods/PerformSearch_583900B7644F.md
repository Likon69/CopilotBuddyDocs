# AuctionHouse.PerformSearch Method

Performs an auction search query via Lua QueryAuctionItems.

## Namespace
[Styx.Logic.Inventory.Frames.AuctionHouse](../../../../../../../../namespaces/Styx/Logic/Inventory/Frames/AuctionHouse.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static void PerformSearch(string searchText, int page, int minLevel, int maxLevel, bool usable, int quality, bool isExact)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| searchText | string | Item name to search for (empty = all) |
| page | int | Page number (0-based) |
| minLevel | int | Minimum item level filter (0 = no filter) |
| maxLevel | int | Maximum item level filter (0 = no filter) |
| usable | bool | Only show usable items |
| quality | int | Minimum quality filter (-1 = no filter) |
| isExact | bool | Exact name match |

## See Also
[AuctionHouse Class](../../AuctionHouse.md)
[Styx.Logic.Inventory.Frames.AuctionHouse Namespace](../../../../../../../../namespaces/Styx/Logic/Inventory/Frames/AuctionHouse.md)
