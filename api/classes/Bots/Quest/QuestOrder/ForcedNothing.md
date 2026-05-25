# ForcedNothing Class

A forced behavior that does nothing and immediately completes. Used for checkpoint nodes and other pass-through nodes.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior
    Bots.Quest.QuestOrder.ForcedNothing

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedNothing : ForcedBehavior
```

The ForcedNothing type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedNothing](ForcedNothing/Constructors/Constructor_F98AA434E373.md) | Initializes a new instance of the ForcedNothing class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsDone](ForcedNothing/Properties/IsDone_83804EFB6B2C.md) | Gets a value indicating whether is done. (Overrides ForcedBehavior.IsDone.) |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. (Inherited from ForcedBehavior.) |
| Public property | [NavType](ForcedBehavior/Properties/NavType_41A3D52F0288.md) | NavType for this behavior. null = auto-detect (Flightor.CanFly). Legion: ForcedBehavior.NavType (nullable). (Inherited from ForcedBehavior.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedNothing/Methods/CreateBehavior_CFF58A2BB20B.md) | Creates the behavior. (Overrides ForcedBehavior.CreateBehavior().) |
| Public method | [Dispose](ForcedBehavior/Methods/Dispose_999011160F69.md) | Disposes resources used by this behavior. (Inherited from ForcedBehavior.) |
| Public method | [OnStart](ForcedBehavior/Methods/OnStart_2DCBC74E7F4F.md) | Called when this behavior starts executing. (Inherited from ForcedBehavior.) |
| Public method | [OnTick](ForcedBehavior/Methods/OnTick_B78D26CF1B1A.md) | Called each tick while this behavior is active. (Inherited from ForcedBehavior.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
