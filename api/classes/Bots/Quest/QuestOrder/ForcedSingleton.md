# ForcedSingleton Class

A forced behavior that executes a single action and completes immediately. Used for simple one-shot actions like setting grind area, vendors, etc. HB 4.3.4: Action runs in OnStart(), IsDone is always true, Branch is ActionAlwaysSucceed. This lets the while(IsDone) loop in ForcedBehaviorExecutor process singletons instantly without consuming a full tick.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior
    Bots.Quest.QuestOrder.ForcedSingleton

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedSingleton : ForcedBehavior
```

The ForcedSingleton type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedSingleton(Action)](ForcedSingleton/Constructors/Constructor_4089B107DEBF.md) | Initializes a new instance of the ForcedSingleton class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsDone](ForcedSingleton/Properties/IsDone_DB23FF821C57.md) | Gets a value indicating whether is done. (Overrides ForcedBehavior.IsDone.) |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. (Inherited from ForcedBehavior.) |
| Public property | [NavType](ForcedBehavior/Properties/NavType_41A3D52F0288.md) | NavType for this behavior. null = auto-detect (Flightor.CanFly). Legion: ForcedBehavior.NavType (nullable). (Inherited from ForcedBehavior.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedSingleton/Methods/CreateBehavior_A0DF0DB8960F.md) | Creates the behavior. (Overrides ForcedBehavior.CreateBehavior().) |
| Public method | [OnStart](ForcedSingleton/Methods/OnStart_09CD783D221A.md) | Handles the on start operation. (Overrides ForcedBehavior.OnStart().) |
| Public method | [ToString](ForcedSingleton/Methods/ToString_71450DC0DFD6.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | [Dispose](ForcedBehavior/Methods/Dispose_999011160F69.md) | Disposes resources used by this behavior. (Inherited from ForcedBehavior.) |
| Public method | [OnTick](ForcedBehavior/Methods/OnTick_B78D26CF1B1A.md) | Called each tick while this behavior is active. (Inherited from ForcedBehavior.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
