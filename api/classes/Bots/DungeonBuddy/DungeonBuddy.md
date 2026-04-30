# DungeonBuddy Class

DungeonBuddy - BotBase pour Dungeon Finder automatique WotLK 3.3.5a (patch 3.3 — Dungeon Finder ajouté) State machine: NotInLfg → SetRole + Queue → InQueue → Proposal → Accept → InDungeon InDungeon → Combat/Follow → DungeonComplete → TeleportOut → Requeue LFG state détecté via GetLFGMode() (API canonique WotLK 3.3). Events LFG via Lua.Events.AttachEvent (confirmé dans CopilotBuddy).

## Inheritance Hierarchy
System.Object
  Styx.BotBase
    Bots.DungeonBuddy.DungeonBuddy

## Namespace
[Bots.DungeonBuddy](../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class DungeonBuddy : BotBase
```

The DungeonBuddy type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [DungeonBuddy](DungeonBuddy/Constructors/Constructor_E534C6273AFE.md) | Initializes a new instance of the DungeonBuddy class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ConfigurationForm](DungeonBuddy/Properties/ConfigurationForm_FA0F4C564D40.md) | Return the configuration window used by DungeonBuddy. This allows the main UI's "Bot Config" button to work when DungeonBuddy is selected (previously ConfigurationForm was null). (Overrides BotBase.ConfigurationForm.) |
| Public property | [IsPrimaryType](DungeonBuddy/Properties/IsPrimaryType_1E82EB369B4F.md) | Gets a value indicating whether is primary type. (Overrides BotBase.IsPrimaryType.) |
| Public property | [Name](DungeonBuddy/Properties/Name_7ADC50EA2CC2.md) | Gets the name. (Overrides BotBase.Name.) |
| Public property | [PulseFlags](DungeonBuddy/Properties/PulseFlags_6DF505273E80.md) | Gets the pulse flags. (Overrides BotBase.PulseFlags.) |
| Public property | [RequirementsMet](DungeonBuddy/Properties/RequirementsMet_B1B82DC9C137.md) | Gets a value indicating whether requirements met. (Overrides BotBase.RequirementsMet.) |
| Public property | [RequiresProfile](DungeonBuddy/Properties/RequiresProfile_9CF3A13B865A.md) | Gets a value indicating whether requires profile. (Overrides BotBase.RequiresProfile.) |
| Public property | [Root](DungeonBuddy/Properties/Root_D71E80ECD53E.md) | Gets the root. (Overrides BotBase.Root.) |
| Public property | Initialized | Gets a value indicating whether initialized. (Inherited from BotBase.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Pulse](DungeonBuddy/Methods/Pulse_30947684535A.md) | Executes one bot pulse. (Overrides BotBase.Pulse().) |
| Public method | [Start](DungeonBuddy/Methods/Start_C95662C9E981.md) | Starts the bot. (Overrides BotBase.Start().) |
| Public method | [Stop](DungeonBuddy/Methods/Stop_7FEE8E459A9F.md) | Stops the bot. (Overrides BotBase.Stop().) |
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
[Bots.DungeonBuddy Namespace](../../../namespaces/Bots/DungeonBuddy.md)
