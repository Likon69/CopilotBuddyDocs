# SequenceManager Class

Manages bot action sequences with override support

## Namespace
[Styx.Logic](../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class SequenceManager
```

The SequenceManager type exposes the following members.

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [AddDefaultSequenceExecutor(BotSequence, Action)](SequenceManager/Methods/AddDefaultSequenceExecutor_BE7D02B9C760.md) | Adds a default sequence executor (warns if duplicate) |
| Public method Static member | [AddSequenceExecutorOverride(BotSequence, Action)](SequenceManager/Methods/AddSequenceExecutorOverride_D9F6B2A62E65.md) | Adds or updates an override executor for a sequence |
| Public method Static member | [CallDefaultSequenceExecutor(BotSequence)](SequenceManager/Methods/CallDefaultSequenceExecutor_6574D1D90A13.md) | Calls only the default sequence executor (ignores overrides) |
| Public method Static member | [CallSequenceExecutor(BotSequence)](SequenceManager/Methods/CallSequenceExecutor_E82D0332E3F7.md) | Calls the sequence executor (override if present, otherwise default) |
| Public method Static member | [GetSequenceExecutorOverride(BotSequence)](SequenceManager/Methods/GetSequenceExecutorOverride_5A32FB30DCED.md) | Gets the override executor for a sequence (null if none) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic Namespace](../../../namespaces/Styx/Logic.md)
