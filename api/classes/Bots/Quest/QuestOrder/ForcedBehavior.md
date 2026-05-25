# ForcedBehavior Class

Base class for all forced quest behaviors. Forced behaviors are executed in order from the quest profile.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class ForcedBehavior : IDisposable
```

The ForcedBehavior type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [ForcedBehavior](ForcedBehavior/Constructors/Constructor_BAB12F1EF227.md) | Initializes a new instance of the ForcedBehavior class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. |
| Public property | [IsDone](ForcedBehavior/Properties/IsDone_FBF416E56F41.md) | Returns true when this behavior has completed its task. |
| Public property | [NavType](ForcedBehavior/Properties/NavType_41A3D52F0288.md) | NavType for this behavior. null = auto-detect (Flightor.CanFly). Legion: ForcedBehavior.NavType (nullable). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedBehavior/Methods/CreateBehavior_C8CBD202936F.md) | Creates the behavior tree for this forced behavior. |
| Public method | [Dispose](ForcedBehavior/Methods/Dispose_999011160F69.md) | Disposes resources used by this behavior. |
| Public method | [OnStart](ForcedBehavior/Methods/OnStart_2DCBC74E7F4F.md) | Called when this behavior starts executing. |
| Public method | [OnTick](ForcedBehavior/Methods/OnTick_B78D26CF1B1A.md) | Called each tick while this behavior is active. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
