# QuestBot Class

The main questing bot implementation.

## Inheritance Hierarchy
System.Object
  Styx.BotBase
    Bots.Quest.QuestBot

## Namespace
[Bots.Quest](../../../namespaces/Bots/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class QuestBot : BotBase
```

The QuestBot type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [QuestBot](QuestBot/Constructors/Constructor_3C0854EE0EE8.md) | Initializes a new instance of the QuestBot class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ConfigurationForm](QuestBot/Properties/ConfigurationForm_4479C465961A.md) | Gets the quest bot configuration form. (Overrides BotBase.ConfigurationForm.) |
| Public property | [Name](QuestBot/Properties/Name_5AC012553D55.md) | Gets the bot name. (Overrides BotBase.Name.) |
| Public property | [PulseFlags](QuestBot/Properties/PulseFlags_C25D06CB2375.md) | Gets the bot pulse flags. (Overrides BotBase.PulseFlags.) |
| Public property | [RequiresProfile](QuestBot/Properties/RequiresProfile_452A6F291F62.md) | Gets a value indicating whether the bot requires a profile. (Overrides BotBase.RequiresProfile.) |
| Public property | [Root](QuestBot/Properties/Root_A219BADAE78B.md) | Gets the root behavior tree composite. (Overrides BotBase.Root.) |
| Public property | ConfigurationForm | Gets the configuration form. (Inherited from BotBase.) |
| Public property | Initialized | Gets a value indicating whether initialized. (Inherited from BotBase.) |
| Public property | IsPrimaryType | Gets a value indicating whether is primary type. (Inherited from BotBase.) |
| Public property | RequirementsMet | Gets a value indicating whether requirements met. (Inherited from BotBase.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [CreateRoot](QuestBot/Methods/CreateRoot_BB4B7C3F52A9.md) | Creates the root behavior tree composite. |
| Public method | [Pulse](QuestBot/Methods/Pulse_230051CB249E.md) | Executes one bot pulse. (Overrides BotBase.Pulse().) |
| Public method Static member | [QuestIncludeTargetsFilter(List<WoWObject>, HashSet<WoWObject>)](QuestBot/Methods/QuestIncludeTargetsFilter_45D6E4FDC6A2.md) | Filters the quest include targets. |
| Public method | [Start](QuestBot/Methods/Start_AE5BF8848DCB.md) | Starts the bot. (Overrides BotBase.Start().) |
| Public method | [Stop](QuestBot/Methods/Stop_F99F41817A79.md) | Stops the bot. (Overrides BotBase.Stop().) |
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
[Bots.Quest Namespace](../../../namespaces/Bots/Quest.md)
