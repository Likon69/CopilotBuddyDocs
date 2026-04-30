# MerchantFrame Class

Merchant frame wrapper for WoW.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Inventory.Frames.Frame
    Styx.Logic.Inventory.Frames.Merchant.MerchantFrame

## Namespace
[Styx.Logic.Inventory.Frames.Merchant](../../../../../../namespaces/Styx/Logic/Inventory/Frames/Merchant.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class MerchantFrame : Frame
```

The MerchantFrame type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [MerchantFrame](MerchantFrame/Constructors/Constructor_95FC06DA1C4A.md) | Initializes a new instance of the MerchantFrame class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](MerchantFrame/Fields/Instance_BB1D2F195733.md) | Represents the instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Merchant](MerchantFrame/Properties/Merchant_5101091B011C.md) | The merchant NPC. Address: 12559336U (0xBF9BE8) |
| Public property | [MerchantItems](MerchantFrame/Properties/MerchantItems_C242B21DCD05.md) | Gets all items the merchant sells. |
| Public property | [MerchantNumItems](MerchantFrame/Properties/MerchantNumItems_522D5D9CAFC3.md) | Number of items the merchant sells. Address: 12559344U (0xBF9BF0) |
| Public property | [NumBuybackItems](MerchantFrame/Properties/NumBuybackItems_91479AA570B6.md) | Number of buyback items. Address: 12559348U (0xBF9BF4) |
| Public property | [FrameName](../Frame/Properties/FrameName_395BA5AE7FD3.md) | The name of the frame in the WoW UI. (Inherited from Frame.) |
| Public property | [IsVisible](../Frame/Properties/IsVisible_9F5D19E4F04B.md) | Whether the frame is currently visible. (Inherited from Frame.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [BuyItem(WoWItem, int)](MerchantFrame/Methods/BuyItem_4B4659C31CB3.md) | Buys the item. |
| Public method | [BuyItem(uint, int)](MerchantFrame/Methods/BuyItem_E1E06B81C797.md) | Buys the item. |
| Public method | [BuyItem(int, int)](MerchantFrame/Methods/BuyItem_01AA2FEC9581.md) | Buys an item by merchant index and amount. Returns true if the purchase was made, false if not enough money. |
| Public method | [BuyItem(string, int)](MerchantFrame/Methods/BuyItem_0F29F173DF48.md) | FEAT-32: Buys an item by name from the merchant. Iterates through merchant items, finds by name, buys the requested amount. Returns true if the item was found and purchased. |
| Public method | [BuyItem(int, int, bool)](MerchantFrame/Methods/BuyItem_508E634E3DFA.md) | Returns true if the buy operation was successful. |
| Public method | [Close](MerchantFrame/Methods/Close_4DCABC5335C6.md) | Closes the . |
| Public method | [GetAllMerchantItems](MerchantFrame/Methods/GetAllMerchantItems_9B7710832881.md) | Gets all merchant items as an array. |
| Public method | [GetBestDrinkFromVendor](MerchantFrame/Methods/GetBestDrinkFromVendor_46833E902320.md) | Gets the best drink the merchant sells that the player can use. Returns -1 if none found. |
| Public method | [GetBestFoodFromVendor](MerchantFrame/Methods/GetBestFoodFromVendor_533E3D64A6A1.md) | Gets the best food the merchant sells that the player can use. Returns -1 if none found. |
| Public method | [GetBuybackItem(int)](MerchantFrame/Methods/GetBuybackItem_ECC08EA013C1.md) | Gets a buyback item by index. Address: 12554488U (0xBF8778) |
| Public method | [GetMerchantItemByIndex(int)](MerchantFrame/Methods/GetMerchantItemByIndex_51AE9C366736.md) | Gets a merchant item by its index. |
| Public method | [Hide](MerchantFrame/Methods/Hide_756CE43A761F.md) | Hides the frame. |
| Public method | [RepairAllItems](MerchantFrame/Methods/RepairAllItems_5920E92FD8D5.md) | Repairs all items. |
| Public method | [RepairAllItems(bool)](MerchantFrame/Methods/RepairAllItems_851BFFE04808.md) | Repairs all items. |
| Public method | [SellItem(WoWItem)](MerchantFrame/Methods/SellItem_43C2379BE208.md) | Sells the item. |
| Public method | [SellItemQualities(ItemQuality, IEnumerable<string>, IEnumerable<uint>)](MerchantFrame/Methods/SellItemQualities_24588D2FBBD6.md) | Sells all items matching the specified qualities. |
| Public method | [Show](../Frame/Methods/Show_24F916F5163E.md) | Shows the frame. (Inherited from Frame.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Inventory.Frames.Merchant Namespace](../../../../../../namespaces/Styx/Logic/Inventory/Frames/Merchant.md)
