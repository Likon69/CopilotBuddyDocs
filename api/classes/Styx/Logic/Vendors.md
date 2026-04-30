# Vendors Class

Provides functionality for interacting with vendors, trainers, and mailboxes.

## Namespace
[Styx.Logic](../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class Vendors
```

The Vendors type exposes the following members.

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [OnBuyItems](Vendors/Fields/OnBuyItems_E50B20AD96C8.md) | Stores the on buy items. |
| Public field Static member | [OnMailItems](Vendors/Fields/OnMailItems_691268C4A305.md) | Stores the on mail items. |
| Public field Static member | [OnRepairItems](Vendors/Fields/OnRepairItems_45E6F34C7269.md) | Stores the on repair items. |
| Public field Static member | [OnVendorItems](Vendors/Fields/OnVendorItems_EFACDC3094F4.md) | Stores the on vendor items. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [ForceBuy](Vendors/Properties/ForceBuy_1633B8179F52.md) | Gets or sets a value indicating whether force buy. |
| Public property Static member | [ForceMail](Vendors/Properties/ForceMail_916E8EE81694.md) | Gets or sets a value indicating whether force mail. |
| Public property Static member | [ForceRepair](Vendors/Properties/ForceRepair_87AB1FBE3B78.md) | Gets or sets a value indicating whether force repair. |
| Public property Static member | [ForceSell](Vendors/Properties/ForceSell_37564B8645E5.md) | Gets or sets a value indicating whether force sell. |
| Public property Static member | [ForceTrainer](Vendors/Properties/ForceTrainer_1EABAE226C2B.md) | Gets or sets a value indicating whether force trainer. |
| Public property Static member | [NearestFlightMerchant](Vendors/Properties/NearestFlightMerchant_792DBA7FF83C.md) | Gets the nearest flight master with taxi available. |
| Public property Static member | [NeedClassTraining](Vendors/Properties/NeedClassTraining_2FAC7D65C6AE.md) | Gets or sets a value indicating whether need class training. |
| Public property Static member | [RepairDisabled](Vendors/Properties/RepairDisabled_2372F8D8F8AF.md) | Gets or sets whether repair functionality is disabled. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [BuyItems](Vendors/Methods/BuyItems_96F6D82316D0.md) | Buys items from vendor based on OnBuyItems event handlers and food/drink settings. Ported from HB 4.3.4. |
| Public method Static member | [MailAllItems](Vendors/Methods/MailAllItems_B45F7187852A.md) | Mails all items that should be mailed. |
| Public method Static member | [RepairAllItems](Vendors/Methods/RepairAllItems_950855CB673C.md) | Repairs all items. |
| Public method Static member | [SellAllItems](Vendors/Methods/SellAllItems_C185F4CBBC71.md) | Sells all items according to profile settings. |
| Public method Static member | [TrainSkills](Vendors/Methods/TrainSkills_1BFF1BDC6D16.md) | Trains all available skills at the current trainer. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic Namespace](../../../namespaces/Styx/Logic.md)
