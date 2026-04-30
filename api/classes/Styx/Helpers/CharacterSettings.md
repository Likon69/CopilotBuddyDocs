# CharacterSettings Class

Character-specific settings. Ported from HB 3.3.5a CharacterSettings.cs. Settings stored in: Settings/CharacterSettings_{Name}.xml Instance is created via Initialize() after game attachment.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.Settings
    Styx.Helpers.CharacterSettings

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class CharacterSettings : Settings, INotifyPropertyChanged
```

The CharacterSettings type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [CharacterSettings](CharacterSettings/Constructors/Constructor_1D61837F4CFE.md) | Constructor. Path: Settings/CharacterSettings_{Name}.xml Exact pattern from HB 3.3.5a. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [DrinkAmount](CharacterSettings/Properties/DrinkAmount_38E1486CB37B.md) | Gets or sets the drink amount. |
| Public property | [DrinkName](CharacterSettings/Properties/DrinkName_1AEBF93CA67E.md) | Gets or sets the drink name. |
| Public property | [EnabledPlugins](CharacterSettings/Properties/EnabledPlugins_C22895C7A045.md) | Gets or sets the enabled plugins. |
| Public property | [FindMountAutomatically](CharacterSettings/Properties/FindMountAutomatically_AAE6DA86540B.md) | Gets or sets a value indicating whether find mount automatically. |
| Public property | [FindVendorsAutomatically](CharacterSettings/Properties/FindVendorsAutomatically_2609E7C0F155.md) | Gets or sets a value indicating whether find vendors automatically. |
| Public property | [FlyingMountName](CharacterSettings/Properties/FlyingMountName_B38206E415A2.md) | Gets or sets the flying mount name. |
| Public property | [FoodAmount](CharacterSettings/Properties/FoodAmount_E2BE12727FA0.md) | Gets or sets the food amount. |
| Public property | [FoodName](CharacterSettings/Properties/FoodName_689323EEAB75.md) | Gets or sets the food name. |
| Public property | [FreeLook](CharacterSettings/Properties/FreeLook_4B21BA18C274.md) | Gets or sets the free look. |
| Public property | [HarvestHerbs](CharacterSettings/Properties/HarvestHerbs_59FF53C3C0A7.md) | Gets or sets a value indicating whether harvest herbs. |
| Public property | [HarvestMinerals](CharacterSettings/Properties/HarvestMinerals_5A6A67F91AAF.md) | Gets or sets a value indicating whether harvest minerals. |
| Public property Static member | [Instance](CharacterSettings/Properties/Instance_65C090A90CBE.md) | Singleton instance. Set via Initialize() after game attachment. |
| Public property | [LastUsedPath](CharacterSettings/Properties/LastUsedPath_ADD67036E5F3.md) | Gets or sets the last used path. |
| Public property | [LearnFlightPaths](CharacterSettings/Properties/LearnFlightPaths_6FBD50739D52.md) | Gets or sets a value indicating whether learn flight paths. |
| Public property | [LootChests](CharacterSettings/Properties/LootChests_00A7464429C5.md) | Gets or sets a value indicating whether loot chests. |
| Public property | [LootMobs](CharacterSettings/Properties/LootMobs_9163300E8D91.md) | Gets or sets a value indicating whether loot mobs. |
| Public property | [LootRadius](CharacterSettings/Properties/LootRadius_2AB88E26D587.md) | Gets or sets the loot radius. |
| Public property | [MailRecipient](CharacterSettings/Properties/MailRecipient_4A14A6BC1189.md) | Gets or sets the mail recipient. |
| Public property | [MountDistance](CharacterSettings/Properties/MountDistance_3015107475D9.md) | Gets or sets the mount distance. |
| Public property | [MountName](CharacterSettings/Properties/MountName_92472EF2FC25.md) | Gets or sets the mount name. |
| Public property | [NinjaSkin](CharacterSettings/Properties/NinjaSkin_7EA2704C7DD0.md) | Gets or sets a value indicating whether ninja skin. |
| Public property | [PullDistance](CharacterSettings/Properties/PullDistance_12984776976A.md) | Gets or sets the pull distance. |
| Public property | [RessAtSpiritHealers](CharacterSettings/Properties/RessAtSpiritHealers_DF6FEF1E77EA.md) | Gets or sets a value indicating whether ress at spirit healers. |
| Public property | [SelectedBotIndex](CharacterSettings/Properties/SelectedBotIndex_A58CE43F06AE.md) | Gets or sets the selected bot index. |
| Public property | [SkinMobs](CharacterSettings/Properties/SkinMobs_5A632A16DFB2.md) | Gets or sets a value indicating whether skin mobs. |
| Public property | [TicksPerSecond](CharacterSettings/Properties/TicksPerSecond_E12480F44D95.md) | Gets or sets the ticks per second. |
| Public property | [TrainNewSkills](CharacterSettings/Properties/TrainNewSkills_313384AA85E4.md) | Gets or sets a value indicating whether train new skills. |
| Public property | [UseFlightPaths](CharacterSettings/Properties/UseFlightPaths_124E313FC9F5.md) | Gets or sets a value indicating whether use flight paths. |
| Public property | [UseFreeLook](CharacterSettings/Properties/UseFreeLook_9304BA87D566.md) | Gets or sets a value indicating whether use free look. |
| Public property | [UseMount](CharacterSettings/Properties/UseMount_C76F4DD2B7F6.md) | Gets or sets a value indicating whether use mount. |
| Public property | [UseRandomMount](CharacterSettings/Properties/UseRandomMount_CAACEF637413.md) | Gets or sets a value indicating whether use random mount. |
| Public property | SettingsPath | Gets the settings path. (Inherited from Settings.) |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [PropertyChanged](CharacterSettings/Events/PropertyChanged_2C856B22FE64.md) | Occurs when property changes. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Initialize](CharacterSettings/Methods/Initialize_FD7BCAF34CB3.md) | Creates the singleton instance. Must be called after game attachment when StyxWoW.Me is available. |
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
