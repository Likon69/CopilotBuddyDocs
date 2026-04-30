# QuestLogEntry Struct

Quest log entry structure (20 bytes). Layout: Id(4) + State(4) + ObjectiveRequiredCounts(8) + Time(4) = 20 bytes. Read from address 12728252 (0xC23F3C). WoW 3.3.5a build 12340.

## Namespace
[Styx.Logic.Questing](../../../../namespaces/Styx/Logic/Questing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct QuestLogEntry
```

The QuestLogEntry type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [QuestLogEntry.StateFlag](QuestLogEntry/StateFlag.md) | Represents values for State Flag. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [QuestLogEntry](QuestLogEntry/Constructors/Constructor_0EEEFB40B5FA.md) | Initializes a new instance of the QuestLogEntry struct. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [Id](QuestLogEntry/Fields/Id_80B6DE63BC7B.md) | Stores the id. |
| Public field | [ObjectiveRequiredCounts](QuestLogEntry/Fields/ObjectiveRequiredCounts_FBD03363DF78.md) | Stores the objective required counts. |
| Public field | [State](QuestLogEntry/Fields/State_6583D3AFF105.md) | Stores the state. |
| Public field | [Time](QuestLogEntry/Fields/Time_58B61FE72684.md) | Stores the time. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [ToString](QuestLogEntry/Methods/ToString_29C67B305F18.md) | Returns a string that represents the current object. (Overrides ValueType.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from ValueType.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from ValueType.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Questing Namespace](../../../../namespaces/Styx/Logic/Questing.md)
