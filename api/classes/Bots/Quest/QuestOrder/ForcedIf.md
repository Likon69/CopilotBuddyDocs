# ForcedIf Class

Represents a forced if step.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior
    Bots.Quest.QuestOrder.ForcedIf

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedIf : ForcedBehavior
```

The ForcedIf type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedIf(IfNode)](ForcedIf/Constructors/Constructor_182F6D24CDC7.md) | Initializes a new instance of the ForcedIf class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IfNode](ForcedIf/Properties/IfNode_8D8267775B2E.md) | Gets the if node. |
| Public property | [IsDone](ForcedIf/Properties/IsDone_A5DB8F9BFF29.md) | Gets a value indicating whether is done. (Overrides ForcedBehavior.IsDone.) |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. (Inherited from ForcedBehavior.) |
| Public property | [NavType](ForcedBehavior/Properties/NavType_41A3D52F0288.md) | NavType for this behavior. null = auto-detect (Flightor.CanFly). Legion: ForcedBehavior.NavType (nullable). (Inherited from ForcedBehavior.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedIf/Methods/CreateBehavior_02E5C7F3F9E5.md) | Creates the behavior. (Overrides ForcedBehavior.CreateBehavior().) |
| Public method | [OnStart](ForcedIf/Methods/OnStart_19A4E572DB1E.md) | Handles the on start operation. (Overrides ForcedBehavior.OnStart().) |
| Public method | [Dispose](ForcedBehavior/Methods/Dispose_999011160F69.md) | Disposes resources used by this behavior. (Inherited from ForcedBehavior.) |
| Public method | [OnTick](ForcedBehavior/Methods/OnTick_B78D26CF1B1A.md) | Called each tick while this behavior is active. (Inherited from ForcedBehavior.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
