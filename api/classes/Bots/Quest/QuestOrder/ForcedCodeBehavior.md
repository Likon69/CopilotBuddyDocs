# ForcedCodeBehavior Class

Represents a forced code behavior step.

## Inheritance Hierarchy
System.Object
  Bots.Quest.QuestOrder.ForcedBehavior
    Bots.Quest.QuestOrder.ForcedCodeBehavior

## Namespace
[Bots.Quest.QuestOrder](../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedCodeBehavior : ForcedBehavior
```

The ForcedCodeBehavior type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedCodeBehavior(CodeNode)](ForcedCodeBehavior/Constructors/Constructor_BCB1F746C9FB.md) | Initializes a new instance of the ForcedCodeBehavior class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsDone](ForcedCodeBehavior/Properties/IsDone_4972309C7F89.md) | Gets a value indicating whether is done. (Overrides ForcedBehavior.IsDone.) |
| Public property | [Branch](ForcedBehavior/Properties/Branch_D9EDC1D2DD45.md) | The behavior tree branch for this forced behavior. Created lazily on first access. (Inherited from ForcedBehavior.) |
| Public property | [NavType](ForcedBehavior/Properties/NavType_41A3D52F0288.md) | NavType for this behavior. null = auto-detect (Flightor.CanFly). Legion: ForcedBehavior.NavType (nullable). (Inherited from ForcedBehavior.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [CreateBehavior](ForcedCodeBehavior/Methods/CreateBehavior_8887F6734A20.md) | Creates the behavior. (Overrides ForcedBehavior.CreateBehavior().) |
| Public method | [Dispose](ForcedCodeBehavior/Methods/Dispose_F362B6FBDAC9.md) | Releases the resources used by the instance. (Overrides ForcedBehavior.Dispose().) |
| Public method | [OnStart](ForcedCodeBehavior/Methods/OnStart_EA1ADD06524E.md) | Handles the on start operation. (Overrides ForcedBehavior.OnStart().) |
| Public method | [OnTick](ForcedCodeBehavior/Methods/OnTick_504AFEF860FC.md) | Handles the on tick operation. (Overrides ForcedBehavior.OnTick().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Quest.QuestOrder Namespace](../../../../namespaces/Bots/Quest/QuestOrder.md)
