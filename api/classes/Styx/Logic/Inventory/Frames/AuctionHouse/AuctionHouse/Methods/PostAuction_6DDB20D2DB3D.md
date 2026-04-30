# AuctionHouse.PostAuction Method

Posts an item from bags to the AH. Uses ClickAuctionSellItemButton + StartAuction Lua.

## Namespace
[Styx.Logic.Inventory.Frames.AuctionHouse](../../../../../../../../namespaces/Styx/Logic/Inventory/Frames/AuctionHouse.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static void PostAuction(int bag, int slot, int startingBid, int buyoutPrice, int duration, int stackSize)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| bag | int | Bag index (0-4) |
| slot | int | Slot in bag (1-based) |
| startingBid | int | Minimum bid in copper |
| buyoutPrice | int | Buyout price in copper (0 = no buyout) |
| duration | int | Duration index: 1=12h, 2=24h, 3=48h |
| stackSize | int | Number of items per stack |

## See Also
[AuctionHouse Class](../../AuctionHouse.md)
[Styx.Logic.Inventory.Frames.AuctionHouse Namespace](../../../../../../../../namespaces/Styx/Logic/Inventory/Frames/AuctionHouse.md)
