# ForcedMoveTo Class

Represents a forced move to step.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior
    Bots.Quest.QuestOrder.ForcedMoveTo

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedMoveTo : ForcedBehavior
```

The ForcedMoveTo type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedMoveTo(WoWPoint, uint)](ForcedMoveTo/Constructors/Constructor_10613E27139F.md) | Initializes a new instance of the ForcedMoveTo class. |
| Public constructor | [ForcedMoveTo(WoWPoint, string, float, uint)](ForcedMoveTo/Constructors/Constructor_20246FE3693F.md) | Initializes a new instance of the ForcedMoveTo class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsDone](ForcedMoveTo/Properties/IsDone_78EC303093CD.md) | Gets a value indicating whether is done. (Overrides ForcedBehavior.IsDone.) |
| Public property | [Location](ForcedMoveTo/Properties/Location_104E1240563B.md) | Gets the location. |
| Public property | [LocationName](ForcedMoveTo/Properties/LocationName_BD95186EE316.md) | Gets the location name. |
| Public property | [Precision](ForcedMoveTo/Properties/Precision_361BACBDB261.md) | Gets the precision. |
| Public property | [QuestId](ForcedMoveTo/Properties/QuestId_B9AED7653AA3.md) | Gets the quest id. |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. (Inherited from ForcedBehavior.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedMoveTo/Methods/CreateBehavior_AA3977159FE0.md) | Creates the behavior. (Overrides ForcedBehavior.CreateBehavior().) |
| Public method | [OnStart](ForcedMoveTo/Methods/OnStart_1B1E7986FD9F.md) | Handles the on start operation. (Overrides ForcedBehavior.OnStart().) |
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
