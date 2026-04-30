# ForcedQuestObjective Class

Represents a forced quest objective step.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior
    Bots.Quest.QuestOrder.ForcedQuestObjective

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedQuestObjective : ForcedBehavior
```

The ForcedQuestObjective type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedQuestObjective(QuestObjective)](ForcedQuestObjective/Constructors/Constructor_53FD56134C54.md) | Initializes a new instance of the ForcedQuestObjective class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsDone](ForcedQuestObjective/Properties/IsDone_9E069E4927C0.md) | Gets a value indicating whether is done. (Overrides ForcedBehavior.IsDone.) |
| Public property | [Objective](ForcedQuestObjective/Properties/Objective_2C677FF6AF01.md) | Gets the objective. |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. (Inherited from ForcedBehavior.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedQuestObjective/Methods/CreateBehavior_F7FBF2C5FFCD.md) | Creates the behavior. (Overrides ForcedBehavior.CreateBehavior().) |
| Public method | [Dispose](ForcedQuestObjective/Methods/Dispose_8CC94F7F833B.md) | Releases the resources used by the instance. (Overrides ForcedBehavior.Dispose().) |
| Protected method | [Finalize](ForcedQuestObjective/Methods/Finalize_D806419A0530.md) | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. |
| Public method | [OnStart](ForcedQuestObjective/Methods/OnStart_638A21602EFC.md) | Handles the on start operation. (Overrides ForcedBehavior.OnStart().) |
| Public method | [ToString](ForcedQuestObjective/Methods/ToString_8402404DF2A2.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | [OnTick](ForcedBehavior/Methods/OnTick_B78D26CF1B1A.md) | Called each tick while this behavior is active. (Inherited from ForcedBehavior.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
