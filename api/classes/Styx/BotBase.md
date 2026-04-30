# BotBase Class

Represents a bot base.

## Inheritance Hierarchy
System.Object
  Styx.BotBase

## Namespace
[Styx](../../namespaces/Styx.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class BotBase
```

The BotBase type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [BotBase](BotBase/Constructors/Constructor_407AE10E25C2.md) | Initializes a new instance of the BotBase class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ConfigurationForm](BotBase/Properties/ConfigurationForm_CBC7DC73D3AC.md) | Gets the configuration form. |
| Public property | [Initialized](BotBase/Properties/Initialized_674BAA41B396.md) | Gets a value indicating whether initialized. |
| Public property | [IsPrimaryType](BotBase/Properties/IsPrimaryType_C7445CE347C0.md) | Gets a value indicating whether is primary type. |
| Public property | [Name](BotBase/Properties/Name_4616FEA17B0E.md) | Gets the name. |
| Public property | [PulseFlags](BotBase/Properties/PulseFlags_C5D69EB0AF1C.md) | Gets the pulse flags. |
| Public property | [RequirementsMet](BotBase/Properties/RequirementsMet_227DB49FE8F4.md) | Gets a value indicating whether requirements met. |
| Public property | [RequiresProfile](BotBase/Properties/RequiresProfile_34391F84865C.md) | Gets a value indicating whether this bot requires a profile to be loaded. If false, the bot can run without a profile (like CombatBot, LazyRaider). |
| Public property | [Root](BotBase/Properties/Root_7DDC39F5E760.md) | Gets the root. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [DoInitialize](BotBase/Methods/DoInitialize_AF39DAC9E6F6.md) | Initializes the component. |
| Public method | [Initialize](BotBase/Methods/Initialize_44BE67A0624E.md) | Initializes the component. |
| Public method | [OnPaused](BotBase/Methods/OnPaused_7D853AC69F28.md) | HB 6.2.3 method_0: Called when bot is paused. |
| Public method | [OnResumed](BotBase/Methods/OnResumed_96599F0B6720.md) | HB 6.2.3 method_1: Called when bot is resumed. |
| Public method | [Pulse](BotBase/Methods/Pulse_759AA28A1CF7.md) | Executes one bot pulse. |
| Public method | [Start](BotBase/Methods/Start_18D2CF2F0D72.md) | Starts the bot. |
| Public method | [Stop](BotBase/Methods/Stop_5F7A6C04458E.md) | Stops the bot. |
| Public method | [ToString](BotBase/Methods/ToString_33AC0F08B9BB.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx Namespace](../../namespaces/Styx.md)
