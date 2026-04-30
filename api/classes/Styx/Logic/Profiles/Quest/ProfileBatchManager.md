# ProfileBatchManager Class

Manages the per-profile CompileBatch for quest behaviors that use [CompileString] / [CompileExpression] (e.g. RunCode). Flow (mirrors HB WoD Class1208 semantics): 1. QuestBot.Start() → ProfileBatchManager.Reset() 2. ForcedCodeBehavior ctor → ProfileBatchManager.Register(qbInstance) 3. ForcedCodeBehavior.OnStart() → ProfileBatchManager.EnsureCompiled() Because CB executes nodes sequentially, Definition QBs are registered before any Statement QB tries to compile, so cross-node variable sharing works.

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class ProfileBatchManager
```

The ProfileBatchManager type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [CurrentBatch](ProfileBatchManager/Properties/CurrentBatch_3C24783E2056.md) | The active batch for the current profile session. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [EnsureCompiled](ProfileBatchManager/Methods/EnsureCompiled_D6EA6904467E.md) | Compiles the current batch if not already compiled. Returns true if compiled successfully (or nothing to compile). |
| Public method Static member | [Register(CustomForcedBehavior)](ProfileBatchManager/Methods/Register_FC1768048EDA.md) | Scans the QB instance for [CompileString] and [CompileExpression] properties and registers them with the current batch. |
| Public method Static member | [Reset](ProfileBatchManager/Methods/Reset_8F782AFD2E1A.md) | Resets the batch. Call when a new profile is loaded. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles.Quest Namespace](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
