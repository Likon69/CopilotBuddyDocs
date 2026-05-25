# GatherbuddySettings Class

Persistent settings for GatherBuddy. Saved to Settings/GatherBuddySettings_{Name}.xml Pattern from HB 3.3.5a.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.Settings
    Bots.Gatherbuddy.GatherbuddySettings

## Namespace
[Bots.Gatherbuddy](../../../namespaces/Bots/Gatherbuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class GatherbuddySettings : Settings
```

The GatherbuddySettings type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [GatherbuddySettings](GatherbuddySettings/Constructors/Constructor_212C5DAEE975.md) | Initializes a new instance of the GatherbuddySettings class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](GatherbuddySettings/Fields/Instance_338D35626836.md) | Represents the instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [BlacklistTimer](GatherbuddySettings/Properties/BlacklistTimer_512BC1424A45.md) | Blacklist duration for failed nodes (seconds) |
| Public property | [BlacklistedEntries](GatherbuddySettings/Properties/BlacklistedEntries_B55F30B37327.md) | Parsed set of blacklisted Entry IDs. Not persisted directly — read/write through . |
| Public property | [BlacklistedEntriesRaw](GatherbuddySettings/Properties/BlacklistedEntriesRaw_5E5B2330A179.md) | Comma-separated list of Entry IDs that should NOT be gathered. Unchecked nodes in the Node Selection tab are stored here. |
| Public property | [BottingHours](GatherbuddySettings/Properties/BottingHours_6570FF509A24.md) | Auto-stop after X hours (0 = infinite/no limit). |
| Public property | [FaceNodes](GatherbuddySettings/Properties/FaceNodes_A343A2A60DF9.md) | Face nodes before interacting |
| Public property | [FindVendorsAutomatically](GatherbuddySettings/Properties/FindVendorsAutomatically_C1D8192D79FE.md) | Use FindVendorsAutomatically when profile has no vendors. Falls back to NpcDatabase queries. |
| Public property | [GatherChests](GatherbuddySettings/Properties/GatherChests_63E54D5256C8.md) | Gather treasure chests along the route. |
| Public property | [GatherHerbs](GatherbuddySettings/Properties/GatherHerbs_7812C08495B5.md) | Gets or sets a value indicating whether gather herbs. |
| Public property | [GatherMinerals](GatherbuddySettings/Properties/GatherMinerals_7C5DFE3D5A15.md) | Gets or sets a value indicating whether gather minerals. |
| Public property | [HearthAndExit](GatherbuddySettings/Properties/HearthAndExit_D5A20BBFDFF5.md) | Use Hearthstone and exit when BottingHours expires. |
| Public property | [HeightModifier](GatherbuddySettings/Properties/HeightModifier_B779921080D2.md) | Height modifier for flying (yards above ground) |
| Public property | [IgnoreElites](GatherbuddySettings/Properties/IgnoreElites_BC4BF89EEF8E.md) | Ignore Elite mobs (do not pull them) |
| Public property | [LootMobs](GatherbuddySettings/Properties/LootMobs_24056A7A56E6.md) | Loot killed mobs during gathering |
| Public property | [LootRadius](GatherbuddySettings/Properties/LootRadius_5912DD80B416.md) | Loot radius in yards. |
| Public property | [MailBlue](GatherbuddySettings/Properties/MailBlue_4A92C4B19549.md) | Gets or sets a value indicating whether mail blue. |
| Public property | [MailGreen](GatherbuddySettings/Properties/MailGreen_DD53838FFF00.md) | Gets or sets a value indicating whether mail green. |
| Public property | [MailGrey](GatherbuddySettings/Properties/MailGrey_9D391A84ECFC.md) | Gets or sets a value indicating whether mail grey. |
| Public property | [MailPurple](GatherbuddySettings/Properties/MailPurple_80D69D630A4E.md) | Gets or sets a value indicating whether mail purple. |
| Public property | [MailRecipient](GatherbuddySettings/Properties/MailRecipient_B7BA5894A449.md) | Mail recipient character name |
| Public property | [MailToAlt](GatherbuddySettings/Properties/MailToAlt_2A27186B5330.md) | Gets or sets a value indicating whether mail to alt. |
| Public property | [MailWhite](GatherbuddySettings/Properties/MailWhite_8CA000CB78FC.md) | Gets or sets a value indicating whether mail white. |
| Public property | [MinFreeBagSlots](GatherbuddySettings/Properties/MinFreeBagSlots_DBFC72352D21.md) | Number of free bag slots below which the bot goes to vendor. |
| Public property | [NoNinja](GatherbuddySettings/Properties/NoNinja_B4ECD4E67824.md) | Do not steal nodes from other players |
| Public property | [NodeDetectionRange](GatherbuddySettings/Properties/NodeDetectionRange_E617B31A59CC.md) | Maximum detection range for nodes (yards) |
| Public property | [PathingType](GatherbuddySettings/Properties/PathingType_FA65FB6EB657.md) | Gets or sets the pathing type. |
| Public property | [RandomizeHotspots](GatherbuddySettings/Properties/RandomizeHotspots_9745FC98A358.md) | Randomize hotspot visit order on start. |
| Public property | [RepairAtVendor](GatherbuddySettings/Properties/RepairAtVendor_890AF4518A79.md) | Repair gear at vendor when durability is low. |
| Public property | [RepairDurabilityPercent](GatherbuddySettings/Properties/RepairDurabilityPercent_5087007EF772.md) | Durability percentage threshold to trigger repair. |
| Public property | [SellBlue](GatherbuddySettings/Properties/SellBlue_350CE6E13A75.md) | Gets or sets a value indicating whether sell blue. |
| Public property | [SellGreen](GatherbuddySettings/Properties/SellGreen_5D00FA412541.md) | Gets or sets a value indicating whether sell green. |
| Public property | [SellGrey](GatherbuddySettings/Properties/SellGrey_DA913A54C7A1.md) | Gets or sets a value indicating whether sell grey. |
| Public property | [SellPurple](GatherbuddySettings/Properties/SellPurple_DE88FBA996A3.md) | Gets or sets a value indicating whether sell purple. |
| Public property | [SellWhite](GatherbuddySettings/Properties/SellWhite_6412885217B8.md) | Gets or sets a value indicating whether sell white. |
| Public property | [SkinMobs](GatherbuddySettings/Properties/SkinMobs_CC8ECCE8DD76.md) | Skin killed mobs (requires Skinning profession). |
| Public property | [UseSpiritHealer](GatherbuddySettings/Properties/UseSpiritHealer_E37C7CAD1245.md) | Use spirit healer instead of corpse running (accepts rez sickness). |
| Public property | [VendorWhenFull](GatherbuddySettings/Properties/VendorWhenFull_06971043F039.md) | Gets or sets a value indicating whether vendor when full. |
| Public property | [WaitRezSickness](GatherbuddySettings/Properties/WaitRezSickness_EF1ED4BCC58B.md) | Wait out resurrection sickness debuff before continuing. |
| Public property | SettingsPath | Gets the settings path. (Inherited from Settings.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [SetBlacklistedEntries(HashSet<uint>)](GatherbuddySettings/Methods/SetBlacklistedEntries_C34E8B3A9D4F.md) | Update the blacklist from a set of Entry IDs. Persists to the raw string setting. |
| Public method | GetSettings | Gets the settings. (Inherited from Settings.) |
| Public method | GetXML | Gets the xml. (Inherited from Settings.) |
| Public method | InitializeDefaultValues | Initializes the default values. (Inherited from Settings.) |
| Public method | Load | Loads settings from the current settings file. Pattern from HB 5.4.8: checks File.Exists and uses StreamReader. (Inherited from Settings.) |
| Public method | LoadFromXML(XElement) | Loads from xml. (Inherited from Settings.) |
| Public method | Save | Saves the current state. (Inherited from Settings.) |
| Public method | SaveToFile(string) | Saves to file. (Inherited from Settings.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Gatherbuddy Namespace](../../../namespaces/Bots/Gatherbuddy.md)
