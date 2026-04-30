# GatherBuddySettings Class

Represents persistent settings for GatherBuddy.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.Settings
    Bots.Gatherbuddy.GatherBuddySettings

## Namespace
[Bots.Gatherbuddy](../../../namespaces/Bots/Gatherbuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class GatherBuddySettings : Settings
```

The GatherBuddySettings type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [GatherBuddySettings](GatherBuddySettings/Constructors/Constructor_FBF4F5FC9087.md) | Initializes a new instance of the GatherBuddySettings class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](GatherBuddySettings/Fields/Instance_35D4B1181C26.md) | Represents the instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [BlacklistTimer](GatherBuddySettings/Properties/BlacklistTimer_6C2C95F35A11.md) | Blacklist duration for failed nodes (seconds) |
| Public property | [BlacklistedEntries](GatherBuddySettings/Properties/BlacklistedEntries_2E294CBA9C2D.md) | Parsed set of blacklisted Entry IDs. Not persisted directly — read/write through . |
| Public property | [BlacklistedEntriesRaw](GatherBuddySettings/Properties/BlacklistedEntriesRaw_876F8728F097.md) | Comma-separated list of Entry IDs that should NOT be gathered. Unchecked nodes in the Node Selection tab are stored here. |
| Public property | [BottingHours](GatherBuddySettings/Properties/BottingHours_5C0F9E1B33DF.md) | Auto-stop after X hours (0 = infinite/no limit). |
| Public property | [FaceNodes](GatherBuddySettings/Properties/FaceNodes_67923C95E649.md) | Face nodes before interacting |
| Public property | [FindVendorsAutomatically](GatherBuddySettings/Properties/FindVendorsAutomatically_DFCF0790875D.md) | Use FindVendorsAutomatically when profile has no vendors. Falls back to NpcDatabase queries. |
| Public property | [FlyingAltitude](GatherBuddySettings/Properties/FlyingAltitude_E46EFF139C1E.md) | Flying altitude above ground (yards). Used as HeightModifier for Flightor. |
| Public property | [FlyingDescentRange](GatherBuddySettings/Properties/FlyingDescentRange_E1598EBF906E.md) | Minimum distance to node before descending to gather (yards). |
| Public property | [GatherChests](GatherBuddySettings/Properties/GatherChests_035F10A82949.md) | Gather treasure chests along the route. |
| Public property | [GatherHerbs](GatherBuddySettings/Properties/GatherHerbs_84F2DD5FA161.md) | Gets or sets a value indicating whether gather herbs. |
| Public property | [GatherMinerals](GatherBuddySettings/Properties/GatherMinerals_EAC50695C10A.md) | Gets or sets a value indicating whether gather minerals. |
| Public property | [HearthAndExit](GatherBuddySettings/Properties/HearthAndExit_D0890B19BDE2.md) | Use Hearthstone and exit when BottingHours expires. |
| Public property | [HeightModifier](GatherBuddySettings/Properties/HeightModifier_13209FE40F85.md) | Height modifier for flying (yards above ground) |
| Public property | [IgnoreElites](GatherBuddySettings/Properties/IgnoreElites_96DDDFB3D4A2.md) | Ignore Elite mobs (do not pull them) |
| Public property | [LootMobs](GatherBuddySettings/Properties/LootMobs_F5DB736F299D.md) | Loot killed mobs during gathering |
| Public property | [LootRadius](GatherBuddySettings/Properties/LootRadius_DEAC64BC001C.md) | Loot radius in yards. |
| Public property | [MailBlue](GatherBuddySettings/Properties/MailBlue_96ED98665CC2.md) | Gets or sets a value indicating whether mail blue. |
| Public property | [MailGreen](GatherBuddySettings/Properties/MailGreen_AB3B0FEFB238.md) | Gets or sets a value indicating whether mail green. |
| Public property | [MailGrey](GatherBuddySettings/Properties/MailGrey_D20C8BFC486B.md) | Gets or sets a value indicating whether mail grey. |
| Public property | [MailPurple](GatherBuddySettings/Properties/MailPurple_01F344B5F373.md) | Gets or sets a value indicating whether mail purple. |
| Public property | [MailRecipient](GatherBuddySettings/Properties/MailRecipient_146EF5F29C43.md) | Mail recipient character name |
| Public property | [MailToAlt](GatherBuddySettings/Properties/MailToAlt_98987C09DC50.md) | Gets or sets a value indicating whether mail to alt. |
| Public property | [MailWhite](GatherBuddySettings/Properties/MailWhite_54EB37866959.md) | Gets or sets a value indicating whether mail white. |
| Public property | [MinFreeBagSlots](GatherBuddySettings/Properties/MinFreeBagSlots_3309D86E369A.md) | Number of free bag slots below which the bot goes to vendor. |
| Public property | [NoNinja](GatherBuddySettings/Properties/NoNinja_86AF355D88BB.md) | Do not steal nodes from other players |
| Public property | [NodeDetectionRange](GatherBuddySettings/Properties/NodeDetectionRange_86DEBA6CCCC4.md) | Maximum detection range for nodes (yards) |
| Public property | [PathingType](GatherBuddySettings/Properties/PathingType_DF1586FE637D.md) | Gets or sets the pathing type. |
| Public property | [RandomizeHotspots](GatherBuddySettings/Properties/RandomizeHotspots_88A6ABFD9C45.md) | Randomize hotspot visit order on start. |
| Public property | [RepairAtVendor](GatherBuddySettings/Properties/RepairAtVendor_2FF6BBB2DB37.md) | Repair gear at vendor when durability is low. |
| Public property | [RepairDurabilityPercent](GatherBuddySettings/Properties/RepairDurabilityPercent_F3B0B82ED398.md) | Durability percentage threshold to trigger repair. |
| Public property | [SellBlue](GatherBuddySettings/Properties/SellBlue_90C14F60942D.md) | Gets or sets a value indicating whether sell blue. |
| Public property | [SellGreen](GatherBuddySettings/Properties/SellGreen_CAA063B7B158.md) | Gets or sets a value indicating whether sell green. |
| Public property | [SellGrey](GatherBuddySettings/Properties/SellGrey_8D913F621F3D.md) | Gets or sets a value indicating whether sell grey. |
| Public property | [SellPurple](GatherBuddySettings/Properties/SellPurple_505C194BCECB.md) | Gets or sets a value indicating whether sell purple. |
| Public property | [SellWhite](GatherBuddySettings/Properties/SellWhite_751980917DBB.md) | Gets or sets a value indicating whether sell white. |
| Public property | [SkinMobs](GatherBuddySettings/Properties/SkinMobs_AB381C7DB3E9.md) | Skin killed mobs (requires Skinning profession). |
| Public property | [UseFlying](GatherBuddySettings/Properties/UseFlying_CDBCAC92BC32.md) | Use flying mount + Flightor for navigation when possible. Requires Cold Weather Flying in Northrend zones. |
| Public property | [UseSpiritHealer](GatherBuddySettings/Properties/UseSpiritHealer_ABEF1E7ADC12.md) | Use spirit healer instead of corpse running (accepts rez sickness). |
| Public property | [VendorWhenFull](GatherBuddySettings/Properties/VendorWhenFull_DFA82375E3F6.md) | Gets or sets a value indicating whether vendor when full. |
| Public property | [WaitRezSickness](GatherBuddySettings/Properties/WaitRezSickness_7861B2AE5642.md) | Wait out resurrection sickness debuff before continuing. |
| Public property | SettingsPath | Gets the settings path. (Inherited from Settings.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [SetBlacklistedEntries(HashSet<uint>)](GatherBuddySettings/Methods/SetBlacklistedEntries_251D6180C616.md) | Update the blacklist from a set of Entry IDs. Persists to the raw string setting. |
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
