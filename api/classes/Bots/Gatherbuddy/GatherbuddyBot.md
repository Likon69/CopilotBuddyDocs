# GatherbuddyBot Class

The main gatherbuddy bot implementation.

## Inheritance Hierarchy
System.Object
  Styx.BotBase
    Bots.Gatherbuddy.GatherbuddyBot

## Namespace
[Bots.Gatherbuddy](../../../namespaces/Bots/Gatherbuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class GatherbuddyBot : BotBase
```

The GatherbuddyBot type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [GatherbuddyBot](GatherbuddyBot/Constructors/Constructor_6B93A2C0D6DA.md) | Initializes a new instance of the GatherbuddyBot class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [BlacklistNodes](GatherbuddyBot/Fields/BlacklistNodes_41B834BBEA0F.md) | Represents the blacklist nodes. |
| Public field Static member | [NodeCollectionCount](GatherbuddyBot/Fields/NodeCollectionCount_377C6F009C13.md) | Represents the node collection count. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ConfigurationForm](GatherbuddyBot/Properties/ConfigurationForm_FE877FC49D76.md) | Gets the configuration form. (Overrides BotBase.ConfigurationForm.) |
| Public property | [IsPrimaryType](GatherbuddyBot/Properties/IsPrimaryType_86D62A4ACAA3.md) | Gets a value indicating whether is primary type. (Overrides BotBase.IsPrimaryType.) |
| Public property | [Name](GatherbuddyBot/Properties/Name_FCB40C88FEB9.md) | Gets the name. (Overrides BotBase.Name.) |
| Public property | [PulseFlags](GatherbuddyBot/Properties/PulseFlags_2ACF33EC8405.md) | Gets the pulse flags. (Overrides BotBase.PulseFlags.) |
| Public property | [RequiresProfile](GatherbuddyBot/Properties/RequiresProfile_9E5E7EC45D21.md) | Gets a value indicating whether requires profile. (Overrides BotBase.RequiresProfile.) |
| Public property | [Root](GatherbuddyBot/Properties/Root_C3497671FC4A.md) | Gets the root. (Overrides BotBase.Root.) |
| Public property Static member | [RunningTime](GatherbuddyBot/Properties/RunningTime_CCBFD22109C1.md) | Elapsed time since the last Start() call. |
| Public property | Initialized | Gets a value indicating whether initialized. (Inherited from BotBase.) |
| Public property | RequirementsMet | Gets a value indicating whether requirements met. (Inherited from BotBase.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [DiagnoseNodeDetection](GatherbuddyBot/Methods/DiagnoseNodeDetection_CAE418745E90.md) | Logs herb and mineral counts visible in the ObjectManager. Useful for diagnosing why no nodes are detected. |
| Public method | [Initialize](GatherbuddyBot/Methods/Initialize_8278EBB5E306.md) | Initializes the component. (Overrides BotBase.Initialize().) |
| Public method | [Pulse](GatherbuddyBot/Methods/Pulse_1F976D48D0FA.md) | Executes one bot pulse. (Overrides BotBase.Pulse().) |
| Public method | [Start](GatherbuddyBot/Methods/Start_9E11621FAC97.md) | Starts the bot. (Overrides BotBase.Start().) |
| Public method Static member | [StatusReport](GatherbuddyBot/Methods/StatusReport_2B49184004A4.md) | Prints a harvest summary to the log. Can be called at any time. |
| Public method | [Stop](GatherbuddyBot/Methods/Stop_949064CD09A1.md) | Stops the bot. (Overrides BotBase.Stop().) |
| Public method | DoInitialize | Initializes the component. (Inherited from BotBase.) |
| Public method | OnPaused | HB 6.2.3 method_0: Called when bot is paused. (Inherited from BotBase.) |
| Public method | OnResumed | HB 6.2.3 method_1: Called when bot is resumed. (Inherited from BotBase.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from BotBase.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Bots.Gatherbuddy Namespace](../../../namespaces/Bots/Gatherbuddy.md)
