# GatherBuddySettingsViewModel Class

ViewModel wrapping GatherBuddySettings for WPF binding. Slider values need double binding (WPF Slider uses double), while Settings uses int — this bridges the gap.

## Inheritance Hierarchy
System.Object
  Bots.Gatherbuddy.GatherBuddySettingsViewModel

## Namespace
[Bots.Gatherbuddy](../../../namespaces/Bots/Gatherbuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class GatherBuddySettingsViewModel : INotifyPropertyChanged
```

The GatherBuddySettingsViewModel type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [GatherBuddySettingsViewModel](GatherBuddySettingsViewModel/Constructors/Constructor_17B7957ADB39.md) | Initializes a new instance of the GatherBuddySettingsViewModel class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [BlacklistTimerValue](GatherBuddySettingsViewModel/Properties/BlacklistTimerValue_0FAD9AF6D085.md) | Gets or sets the blacklist timer value. |
| Public property | [BottingHours](GatherBuddySettingsViewModel/Properties/BottingHours_2AA67F8A814C.md) | Gets or sets the botting hours. |
| Public property | [FaceNodes](GatherBuddySettingsViewModel/Properties/FaceNodes_F18A7C59A719.md) | Gets or sets a value indicating whether face nodes. |
| Public property | [FindVendorsAutomatically](GatherBuddySettingsViewModel/Properties/FindVendorsAutomatically_CC8B0A47E142.md) | Gets or sets a value indicating whether find vendors automatically. |
| Public property | [FlyingAltitude](GatherBuddySettingsViewModel/Properties/FlyingAltitude_FC64044E7F5E.md) | Gets or sets the flying altitude. |
| Public property | [FlyingDescentRange](GatherBuddySettingsViewModel/Properties/FlyingDescentRange_7C0EC9C4B318.md) | Gets or sets the flying descent range. |
| Public property | [GatherChests](GatherBuddySettingsViewModel/Properties/GatherChests_0297F09BAEB5.md) | Gets or sets a value indicating whether gather chests. |
| Public property | [GatherHerbs](GatherBuddySettingsViewModel/Properties/GatherHerbs_7EDCE476F4BD.md) | Gets or sets a value indicating whether gather herbs. |
| Public property | [GatherMinerals](GatherBuddySettingsViewModel/Properties/GatherMinerals_15A01CC1DA3A.md) | Gets or sets a value indicating whether gather minerals. |
| Public property | [HearthAndExit](GatherBuddySettingsViewModel/Properties/HearthAndExit_9C411449A9D6.md) | Gets or sets a value indicating whether hearth and exit. |
| Public property | [HeightModifier](GatherBuddySettingsViewModel/Properties/HeightModifier_563773F3459D.md) | Gets or sets the height modifier. |
| Public property | [HerbItems](GatherBuddySettingsViewModel/Properties/HerbItems_BE46935B88DC.md) | Gets the herb items. |
| Public property | [IgnoreElites](GatherBuddySettingsViewModel/Properties/IgnoreElites_3939BD5B2E5A.md) | Gets or sets a value indicating whether ignore elites. |
| Public property | [LootMobs](GatherBuddySettingsViewModel/Properties/LootMobs_C66D6263D5E7.md) | Gets or sets a value indicating whether loot mobs. |
| Public property | [LootRadius](GatherBuddySettingsViewModel/Properties/LootRadius_7809803EB8F1.md) | Gets or sets the loot radius. |
| Public property | [MailBlue](GatherBuddySettingsViewModel/Properties/MailBlue_D3AD6BAD05AF.md) | Gets or sets a value indicating whether mail blue. |
| Public property | [MailGreen](GatherBuddySettingsViewModel/Properties/MailGreen_B2C2F4D9BF8E.md) | Gets or sets a value indicating whether mail green. |
| Public property | [MailGrey](GatherBuddySettingsViewModel/Properties/MailGrey_CB0F9F1F09F8.md) | Gets or sets a value indicating whether mail grey. |
| Public property | [MailPurple](GatherBuddySettingsViewModel/Properties/MailPurple_8B15589BFE3D.md) | Gets or sets a value indicating whether mail purple. |
| Public property | [MailRecipient](GatherBuddySettingsViewModel/Properties/MailRecipient_AB9F3962B01F.md) | Gets or sets the mail recipient. |
| Public property | [MailToAlt](GatherBuddySettingsViewModel/Properties/MailToAlt_73AFC034BCDF.md) | Gets or sets a value indicating whether mail to alt. |
| Public property | [MailWhite](GatherBuddySettingsViewModel/Properties/MailWhite_384452AA812B.md) | Gets or sets a value indicating whether mail white. |
| Public property | [MinFreeBagSlotsValue](GatherBuddySettingsViewModel/Properties/MinFreeBagSlotsValue_9D221B93A320.md) | Gets or sets the min free bag slots value. |
| Public property | [MineralItems](GatherBuddySettingsViewModel/Properties/MineralItems_ECABD576DA1C.md) | Gets the mineral items. |
| Public property | [NoNinja](GatherBuddySettingsViewModel/Properties/NoNinja_16EC8E855C05.md) | Gets or sets a value indicating whether no ninja. |
| Public property | [NodeDetectionRange](GatherBuddySettingsViewModel/Properties/NodeDetectionRange_9C8EC1DA024E.md) | Gets or sets the node detection range. |
| Public property | [PathingTypeIndex](GatherBuddySettingsViewModel/Properties/PathingTypeIndex_EEF47976A2B4.md) | Gets or sets the pathing type index. |
| Public property | [RandomizeHotspots](GatherBuddySettingsViewModel/Properties/RandomizeHotspots_D8AF7721C4B1.md) | Gets or sets a value indicating whether randomize hotspots. |
| Public property | [RepairAtVendor](GatherBuddySettingsViewModel/Properties/RepairAtVendor_B9DAE87E84D9.md) | Gets or sets a value indicating whether repair at vendor. |
| Public property | [RepairDurabilityPercentValue](GatherBuddySettingsViewModel/Properties/RepairDurabilityPercentValue_AB9E17DE4862.md) | Gets or sets the repair durability percent value. |
| Public property | [SellBlue](GatherBuddySettingsViewModel/Properties/SellBlue_22EA973971AE.md) | Gets or sets a value indicating whether sell blue. |
| Public property | [SellGreen](GatherBuddySettingsViewModel/Properties/SellGreen_4E5BC770D1FC.md) | Gets or sets a value indicating whether sell green. |
| Public property | [SellGrey](GatherBuddySettingsViewModel/Properties/SellGrey_5A0037E385A0.md) | Gets or sets a value indicating whether sell grey. |
| Public property | [SellPurple](GatherBuddySettingsViewModel/Properties/SellPurple_619F4AF8AC6F.md) | Gets or sets a value indicating whether sell purple. |
| Public property | [SellWhite](GatherBuddySettingsViewModel/Properties/SellWhite_C2FEF73158B2.md) | Gets or sets a value indicating whether sell white. |
| Public property | [SkinMobs](GatherBuddySettingsViewModel/Properties/SkinMobs_D10DB91AF4FA.md) | Gets or sets a value indicating whether skin mobs. |
| Public property | [UseFlying](GatherBuddySettingsViewModel/Properties/UseFlying_1DCC9B9A4C6C.md) | Gets or sets a value indicating whether use flying. |
| Public property | [UseSpiritHealer](GatherBuddySettingsViewModel/Properties/UseSpiritHealer_07205A96A9F0.md) | Gets or sets a value indicating whether use spirit healer. |
| Public property | [VendorWhenFull](GatherBuddySettingsViewModel/Properties/VendorWhenFull_3DD321F2789F.md) | Gets or sets a value indicating whether vendor when full. |
| Public property | [WaitRezSickness](GatherBuddySettingsViewModel/Properties/WaitRezSickness_BE704120E6B9.md) | Gets or sets a value indicating whether wait rez sickness. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [PropertyChanged](GatherBuddySettingsViewModel/Events/PropertyChanged_E2D1C0DD9EC4.md) | Occurs when property changes. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [SaveNodeSelection](GatherBuddySettingsViewModel/Methods/SaveNodeSelection_B40CFBE783E2.md) | Collect unchecked entries from both lists and save to settings. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Gatherbuddy Namespace](../../../namespaces/Bots/Gatherbuddy.md)
