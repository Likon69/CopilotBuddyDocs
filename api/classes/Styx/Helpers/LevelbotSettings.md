# LevelbotSettings Class

LevelbotSettings delegates all UI-visible settings to CharacterSettings. Path: Settings/LevelbotSettings_{Name}.xml Pattern from HB 3.3.5a.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.Settings
    Styx.Helpers.LevelbotSettings

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class LevelbotSettings : Settings
```

The LevelbotSettings type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [LevelbotSettings](LevelbotSettings/Constructors/Constructor_0E9DF2BEFF90.md) | Initializes a new instance of the LevelbotSettings class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Instance](LevelbotSettings/Fields/Instance_5909F70EF6C0.md) | Represents the instance. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [DrinkName](LevelbotSettings/Properties/DrinkName_AB2C8AEB1BC6.md) | Gets or sets the drink name. |
| Public property | [FindVendorsAutomatically](LevelbotSettings/Properties/FindVendorsAutomatically_7A0074AAA371.md) | Gets or sets a value indicating whether find vendors automatically. |
| Public property | [FoodName](LevelbotSettings/Properties/FoodName_7642A678DFA2.md) | Gets or sets the food name. |
| Public property | [FreeLook](LevelbotSettings/Properties/FreeLook_7C1AC5599EF0.md) | Gets or sets the free look. |
| Public property | [GroundMountFarmingMode](LevelbotSettings/Properties/GroundMountFarmingMode_CA69A9EE5E3B.md) | Gets or sets a value indicating whether ground mount farming mode. |
| Public property | [HarvestHerbs](LevelbotSettings/Properties/HarvestHerbs_C785DB6FE031.md) | Gets or sets a value indicating whether harvest herbs. |
| Public property | [HarvestMinerals](LevelbotSettings/Properties/HarvestMinerals_2F90BA5C9780.md) | Gets or sets a value indicating whether harvest minerals. |
| Public property | [LastUsedPath](LevelbotSettings/Properties/LastUsedPath_1C1608F6155C.md) | Gets or sets the last used path. |
| Public property | [LearnFlightPaths](LevelbotSettings/Properties/LearnFlightPaths_432ADEABD9A7.md) | Gets or sets a value indicating whether learn flight paths. |
| Public property | [LootChests](LevelbotSettings/Properties/LootChests_1D6614A0BB1F.md) | Gets or sets a value indicating whether loot chests. |
| Public property | [LootMobs](LevelbotSettings/Properties/LootMobs_F28615FD2955.md) | Gets or sets a value indicating whether loot mobs. |
| Public property | [LootRadius](LevelbotSettings/Properties/LootRadius_F644C2EFAAF6.md) | Gets or sets the loot radius. |
| Public property | [MailRecipient](LevelbotSettings/Properties/MailRecipient_FC0C1AD43183.md) | Gets or sets the mail recipient. |
| Public property | [MountDistance](LevelbotSettings/Properties/MountDistance_D53B6AFD7C52.md) | Gets or sets the mount distance. |
| Public property | [MountName](LevelbotSettings/Properties/MountName_C75FB99589C8.md) | Gets or sets the mount name. |
| Public property | [NinjaSkin](LevelbotSettings/Properties/NinjaSkin_7C668AC52CA1.md) | Gets or sets a value indicating whether ninja skin. |
| Public property | [PullDistance](LevelbotSettings/Properties/PullDistance_96693DBADFE5.md) | Gets or sets the pull distance. |
| Public property | [RessAtSpiritHealers](LevelbotSettings/Properties/RessAtSpiritHealers_E65DBD402464.md) | Gets or sets a value indicating whether ress at spirit healers. |
| Public property | [SkinMobs](LevelbotSettings/Properties/SkinMobs_1A8616D697F9.md) | Gets or sets a value indicating whether skin mobs. |
| Public property | [TrainNewSkills](LevelbotSettings/Properties/TrainNewSkills_8E5F84CA95A2.md) | Gets or sets a value indicating whether train new skills. |
| Public property | [UseFlightPaths](LevelbotSettings/Properties/UseFlightPaths_D041D27FEBFF.md) | Gets or sets a value indicating whether use flight paths. |
| Public property | [UseFreeLook](LevelbotSettings/Properties/UseFreeLook_1558D01029AB.md) | Gets or sets a value indicating whether use free look. |
| Public property | [UseMount](LevelbotSettings/Properties/UseMount_663EE89527CF.md) | Gets or sets a value indicating whether use mount. |
| Public property | SettingsPath | Gets the settings path. (Inherited from Settings.) |

## Methods

| | Name | Description |
| --- | --- | --- |
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
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
