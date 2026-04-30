# AuctionEntry Struct

Represents an auction entry from memory.

## Namespace
[Styx.Logic.Inventory.Frames.AuctionHouse](../../../../../../namespaces/Styx/Logic/Inventory/Frames/AuctionHouse.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct AuctionEntry
```

The AuctionEntry type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [AuctionEntry](AuctionEntry/Constructors/Constructor_4B62F4C9B54B.md) | Initializes a new instance of the AuctionEntry struct. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [AuctionId](AuctionEntry/Fields/AuctionId_BC1D7BEF6DD6.md) | Unique auction ID. |
| Public field | [BidderGuidA](AuctionEntry/Fields/BidderGuidA_9A8E937895DC.md) | Current bidder GUID (high part). |
| Public field | [BidderGuidB](AuctionEntry/Fields/BidderGuidB_B0E2611675A3.md) | Current bidder GUID (low part). |
| Public field | [BuyOut](AuctionEntry/Fields/BuyOut_501828D24C4D.md) | Buyout price. |
| Public field | [Count](AuctionEntry/Fields/Count_DC92062F1A87.md) | Stack count. |
| Public field | [CurrentBid](AuctionEntry/Fields/CurrentBid_68FF6EF585E8.md) | Current bid amount. |
| Public field | [EnchantInfo](AuctionEntry/Fields/EnchantInfo_E627348F05DA.md) | Enchant information (up to 7 enchants). |
| Public field | [ExpireTime](AuctionEntry/Fields/ExpireTime_ABA5259CFBEE.md) | Time until auction expires. |
| Public field | [ItemEntry](AuctionEntry/Fields/ItemEntry_A75BAEF72F2A.md) | Item entry ID. |
| Public field | [ItemSuffixFactor](AuctionEntry/Fields/ItemSuffixFactor_7F0F6458FBB7.md) | Item suffix factor. |
| Public field | [MinBidInc](AuctionEntry/Fields/MinBidInc_9E78D66568F3.md) | Minimum bid increment. |
| Public field | [RandomPropertyId](AuctionEntry/Fields/RandomPropertyId_999D23139F67.md) | Random property ID for random enchants. |
| Public field | [SaleStatus](AuctionEntry/Fields/SaleStatus_7BEF570B32E6.md) | Sale status. |
| Public field | [SellerGuid](AuctionEntry/Fields/SellerGuid_A0067C91854B.md) | GUID of the seller. |
| Public field | [SpellCharges](AuctionEntry/Fields/SpellCharges_A841424CDCD6.md) | Spell charges on the item. |
| Public field | [StartBid](AuctionEntry/Fields/StartBid_A040B9C2ADB6.md) | Starting bid amount. |
| Public field | [Unk00](AuctionEntry/Fields/Unk00_5BE663B30332.md) | Unknown field. |
| Public field | [Unk70](AuctionEntry/Fields/Unk70_DEC3E4702F90.md) | Unknown field. |
| Public field | [Unk74](AuctionEntry/Fields/Unk74_18503EE0DE65.md) | Unknown field. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from ValueType.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from ValueType.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from ValueType.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Inventory.Frames.AuctionHouse Namespace](../../../../../../namespaces/Styx/Logic/Inventory/Frames/AuctionHouse.md)
