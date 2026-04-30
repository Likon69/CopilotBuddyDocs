# ForcedGrindTo Class

Represents a forced grind to step.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior
    Bots.Quest.QuestOrder.ForcedGrindTo

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedGrindTo : ForcedBehavior
```

The ForcedGrindTo type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedGrindTo(GrindToNode)](ForcedGrindTo/Constructors/Constructor_127B89819332.md) | Initializes a new instance of the ForcedGrindTo class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsDone](ForcedGrindTo/Properties/IsDone_375E7E989A93.md) | Gets a value indicating whether is done. (Overrides ForcedBehavior.IsDone.) |
| Public property | [Node](ForcedGrindTo/Properties/Node_73D0068CF906.md) | Gets the node. |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. (Inherited from ForcedBehavior.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedGrindTo/Methods/CreateBehavior_77C689D32FDB.md) | Creates the behavior. (Overrides ForcedBehavior.CreateBehavior().) |
| Public method | [Dispose](ForcedGrindTo/Methods/Dispose_4B07416710A7.md) | Releases the resources used by the instance. (Overrides ForcedBehavior.Dispose().) |
| Public method | [OnStart](ForcedGrindTo/Methods/OnStart_22806462FC1C.md) | Handles the on start operation. (Overrides ForcedBehavior.OnStart().) |
| Public method | [ToString](ForcedGrindTo/Methods/ToString_BE95DA05AE21.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | [OnTick](ForcedBehavior/Methods/OnTick_B78D26CF1B1A.md) | Called each tick while this behavior is active. (Inherited from ForcedBehavior.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
