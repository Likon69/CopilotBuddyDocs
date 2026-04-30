# LevelBot Class

The main grind bot implementation.

## Inheritance Hierarchy
System.Object
  Styx.BotBase
    Bots.Grind.LevelBot

## Namespace
[Bots.Grind](../../../namespaces/Bots/Grind.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class LevelBot : BotBase
```

The LevelBot type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [LevelBot](LevelBot/Constructors/Constructor_2CF0A745ADBA.md) | Initializes a new instance of the LevelBot class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsPrimaryType](LevelBot/Properties/IsPrimaryType_83DEEF353637.md) | Gets a value indicating whether this is a primary bot type. (Overrides BotBase.IsPrimaryType.) |
| Public property | [Name](LevelBot/Properties/Name_BA5CEDD81C0B.md) | Gets the bot name. (Overrides BotBase.Name.) |
| Public property | [PulseFlags](LevelBot/Properties/PulseFlags_B493AB92B76B.md) | Gets the bot pulse flags. (Overrides BotBase.PulseFlags.) |
| Public property | [RequirementsMet](LevelBot/Properties/RequirementsMet_7BA7242C53E7.md) | Gets a value indicating whether the bot requirements are met. (Overrides BotBase.RequirementsMet.) |
| Public property | [RequiresProfile](LevelBot/Properties/RequiresProfile_70EF6C976143.md) | Gets a value indicating whether the bot requires a profile. (Overrides BotBase.RequiresProfile.) |
| Public property | [Root](LevelBot/Properties/Root_7170797428EB.md) | Gets the root behavior tree composite. (Overrides BotBase.Root.) |
| Public property Static member | [ShouldUseSpiritHealer](LevelBot/Properties/ShouldUseSpiritHealer_61E7279501C8.md) | Gets or sets a value indicating whether the bot should use a spirit healer. |
| Public property | ConfigurationForm | Gets the configuration form. (Inherited from BotBase.) |
| Public property | Initialized | Gets a value indicating whether initialized. (Inherited from BotBase.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [CreateCombatBehavior](LevelBot/Methods/CreateCombatBehavior_E8CEEA074224.md) | HB 4.3.4 CreateCombatBehavior - handles dismount, target validation, rest, pull, combat |
| Public method Static member | [CreateDeathBehavior](LevelBot/Methods/CreateDeathBehavior_3B58CB5AF7F8.md) | HB 4.3.4 CreateDeathBehavior - handles release, ghost movement, corpse retrieval |
| Public method Static member | [CreateLootBehavior](LevelBot/Methods/CreateLootBehavior_CAFBAD55355D.md) | HB 4.3.4 CreateLootBehavior - handles looting, skinning, harvesting |
| Public method Static member | [CreateRoamBehavior](LevelBot/Methods/CreateRoamBehavior_928716F3D33F.md) | HB 4.3.4 CreateRoamBehavior - handles movement between hotspots |
| Public method Static member | [CreateVendorBehavior](LevelBot/Methods/CreateVendorBehavior_E0B5FD76C3B7.md) | HB 4.3.4 CreateVendorBehavior - handles selling, repairing, mailing, training |
| Public method Static member | [IsTooNearBlackspot(IEnumerable<Blackspot>, WoWPoint)](LevelBot/Methods/IsTooNearBlackspot_4B8AFCEAD8C7.md) | HB 4.3.4 IsTooNearBlackspot - checks if point is within any blackspot |
| Public method Static member | [LevelBotIncludeTargetsFilter(List<WoWObject>, HashSet<WoWObject>)](LevelBot/Methods/LevelBotIncludeTargetsFilter_BA33D7B78919.md) | HB 4.3.4 LevelBotIncludeTargetsFilter - filters combat targets by faction |
| Public method Static member | [LevelbotIncludeLootsFilter(List<WoWObject>, HashSet<WoWObject>)](LevelBot/Methods/LevelbotIncludeLootsFilter_488011FF7B4C.md) | HB 4.3.4 LevelbotIncludeLootsFilter - filters loot targets |
| Public method | [Pulse](LevelBot/Methods/Pulse_336DED85B6DB.md) | Executes one bot pulse. (Overrides BotBase.Pulse().) |
| Public method Static member | [SetDefaultQueryFilter](LevelBot/Methods/SetDefaultQueryFilter_3FF1F42AC2A4.md) | HB 4.3.4 SetDefaultQueryFilter — Resets the mesh navigator query filter. Called when navigation parameters need to be restored to defaults. |
| Public method | [Start](LevelBot/Methods/Start_EFA029375B88.md) | Starts the bot. (Overrides BotBase.Start().) |
| Public method | [Stop](LevelBot/Methods/Stop_792871AD9DA5.md) | Stops the bot. (Overrides BotBase.Stop().) |
| Public method | DoInitialize | Initializes the component. (Inherited from BotBase.) |
| Public method | Initialize | Initializes the component. (Inherited from BotBase.) |
| Public method | OnPaused | HB 6.2.3 method_0: Called when bot is paused. (Inherited from BotBase.) |
| Public method | OnResumed | HB 6.2.3 method_1: Called when bot is resumed. (Inherited from BotBase.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from BotBase.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Bots.Grind Namespace](../../../namespaces/Bots/Grind.md)
