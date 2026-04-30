# AuctionHouse Class

FEAT-34: Auction house manager. Provides search, browse, bid, buyout, and listing operations via Lua (WotLK AH API). Ported from HB 4.3.4 AuctionHouse.

## Namespace
[Styx.Logic.Inventory.Frames.AuctionHouse](../../../../../../namespaces/Styx/Logic/Inventory/Frames/AuctionHouse.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class AuctionHouse
```

The AuctionHouse type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [AuctionHouse.AuctionListType](AuctionHouse/AuctionListType.md) | Auction list types for query. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [Frame](AuctionHouse/Properties/Frame_680F2CC2979A.md) | The auction frame instance. |
| Public property Static member | [FullNumListAuctions](AuctionHouse/Properties/FullNumListAuctions_C71DD2D83DB5.md) | Gets the total number of list auctions matching last search. |
| Public property Static member | [IsOpen](AuctionHouse/Properties/IsOpen_16042A318A16.md) | Whether the AH frame is open and we can interact. |
| Public property Static member | [NumBidderAuctions](AuctionHouse/Properties/NumBidderAuctions_123E142085CD.md) | Number of auctions the player is bidding on. |
| Public property Static member | [NumListAuctions](AuctionHouse/Properties/NumListAuctions_2E9D4C9E6226.md) | Gets the number of list auctions (from last search). |
| Public property Static member | [NumOwnerAuctions](AuctionHouse/Properties/NumOwnerAuctions_40F7951A9017.md) | Number of auctions owned by the player. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Buyout(int, AuctionListType)](AuctionHouse/Methods/Buyout_7E038DE36272.md) | Buys out an auction at the given index (1-based). |
| Public method Static member | [CancelAuction(int)](AuctionHouse/Methods/CancelAuction_30DF9C2BF6C9.md) | Cancels an owned auction at the given index (1-based). |
| Public method Static member | [GetAuction(int, AuctionListType)](AuctionHouse/Methods/GetAuction_AB3227A5E17C.md) | Gets auction data at the specified index (1-based) for the given list type. Uses Lua GetAuctionItemInfo. |
| Public method Static member | [GetAuctionDeposit(int)](AuctionHouse/Methods/GetAuctionDeposit_4DCF41DC8BEC.md) | Gets the auction deposit cost for the currently selected sell item. |
| Public method Static member | [GetBidderAuctionItems](AuctionHouse/Methods/GetBidderAuctionItems_3D1B47E1D9F1.md) | Queries auctions the player has bid on. |
| Public method Static member | [GetBidderAuctions](AuctionHouse/Methods/GetBidderAuctions_F1197514EFC5.md) | Gets all auctions the player is bidding on. |
| Public method Static member | [GetListAuctions](AuctionHouse/Methods/GetListAuctions_A73058AECCDF.md) | Gets all auctions from the last search batch. |
| Public method Static member | [GetNumAuctionItems(AuctionListType)](AuctionHouse/Methods/GetNumAuctionItems_F964D1797931.md) | Gets the number of auction items returned by the last query. Returns (batchCount, totalCount). |
| Public method Static member | [GetOwnedAuctions](AuctionHouse/Methods/GetOwnedAuctions_E6847AD8F534.md) | Gets all auctions owned by the player. |
| Public method Static member | [GetOwnerAuctionItems](AuctionHouse/Methods/GetOwnerAuctionItems_F4F734F7815E.md) | Queries the player's own auctions. |
| Public method Static member | [PerformSearch(string, int, int, int, bool, int, bool)](AuctionHouse/Methods/PerformSearch_583900B7644F.md) | Performs an auction search query via Lua QueryAuctionItems. |
| Public method Static member | [PlaceBid(int, int, AuctionListType)](AuctionHouse/Methods/PlaceBid_50D707E66EED.md) | Places a bid on an auction at the given index. |
| Public method Static member | [PostAuction(int, int, int, int, int, int)](AuctionHouse/Methods/PostAuction_6DDB20D2DB3D.md) | Posts an item from bags to the AH. Uses ClickAuctionSellItemButton + StartAuction Lua. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Inventory.Frames.AuctionHouse Namespace](../../../../../../namespaces/Styx/Logic/Inventory/Frames/AuctionHouse.md)
