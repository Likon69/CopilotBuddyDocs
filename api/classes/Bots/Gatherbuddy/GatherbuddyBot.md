# GatherbuddyBot Class

GatherBuddy - Full-featured gathering bot for WoW 3.3.5a (WotLK). Harvests herbs, minerals, chests, skins mobs along a waypoint route. Supports profile vendors, mailboxes, blackspots, sell/mail quality filters, full combat behaviors, death handling with spirit healer, and session timers.

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

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ConfigurationForm](GatherbuddyBot/Properties/ConfigurationForm_FE877FC49D76.md) | Returns the settings window shown when "Bot Config" is clicked. (Overrides BotBase.ConfigurationForm.) |
| Public property | [HerbsGathered](GatherbuddyBot/Properties/HerbsGathered_134EF5585493.md) | Gets the herbs gathered. |
| Public property | [IsPrimaryType](GatherbuddyBot/Properties/IsPrimaryType_86D62A4ACAA3.md) | Gets a value indicating whether is primary type. (Overrides BotBase.IsPrimaryType.) |
| Public property | [MineralsGathered](GatherbuddyBot/Properties/MineralsGathered_E68601AB876C.md) | Gets the minerals gathered. |
| Public property | [Name](GatherbuddyBot/Properties/Name_FCB40C88FEB9.md) | Gets the name. (Overrides BotBase.Name.) |
| Public property | [NodesGathered](GatherbuddyBot/Properties/NodesGathered_2CCCDA7D1C14.md) | Session statistics. |
| Public property | [PulseFlags](GatherbuddyBot/Properties/PulseFlags_2ACF33EC8405.md) | Gets the pulse flags. (Overrides BotBase.PulseFlags.) |
| Public property | [RequirementsMet](GatherbuddyBot/Properties/RequirementsMet_B46B7E8DEC9E.md) | Gets a value indicating whether requirements met. (Overrides BotBase.RequirementsMet.) |
| Public property | [RequiresProfile](GatherbuddyBot/Properties/RequiresProfile_9E5E7EC45D21.md) | Gets a value indicating whether requires profile. (Overrides BotBase.RequiresProfile.) |
| Public property | [Root](GatherbuddyBot/Properties/Root_C3497671FC4A.md) | Gets the root. (Overrides BotBase.Root.) |
| Public property | [SessionTime](GatherbuddyBot/Properties/SessionTime_869062C83183.md) | Gets the session time. |
| Public property | Initialized | Gets a value indicating whether initialized. (Inherited from BotBase.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Initialize](GatherbuddyBot/Methods/Initialize_8278EBB5E306.md) | Initializes the component. (Overrides BotBase.Initialize().) |
| Public method | [Pulse](GatherbuddyBot/Methods/Pulse_1F976D48D0FA.md) | Executes one bot pulse. (Overrides BotBase.Pulse().) |
| Public method | [Start](GatherbuddyBot/Methods/Start_9E11621FAC97.md) | Starts the bot. (Overrides BotBase.Start().) |
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
