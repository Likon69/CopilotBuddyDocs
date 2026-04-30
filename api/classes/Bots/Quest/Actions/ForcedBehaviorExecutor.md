# ForcedBehaviorExecutor Class

Coordinates forced quest order behaviors for the questing bot.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    Bots.Quest.Actions.ForcedBehaviorExecutor

## Namespace
[Bots.Quest.Actions](../../../../namespaces/Bots/Quest/Actions.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ForcedBehaviorExecutor : Composite
```

The ForcedBehaviorExecutor type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ForcedBehaviorExecutor(QuestOrder)](ForcedBehaviorExecutor/Constructors/Constructor_14EC590DAC1C.md) | Initializes a new instance of the ForcedBehaviorExecutor class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Order](ForcedBehaviorExecutor/Properties/Order_28A879B91F32.md) | Gets the current quest order. |
| Public property | Children | Gets the children. (Inherited from Composite.) |
| Protected property | CleanupHandlers | Gets or sets the cleanup handlers. (Inherited from Composite.) |
| Protected property | ContextChanger | Gets or sets the context changer. (Inherited from Composite.) |
| Public property | Guid | Gets the guid. (Inherited from Composite.) |
| Public property | IsRunning | HonorBuddy-compatible property: whether this composite is currently running. Many third-party bots reference `IsRunning` as a property. (Inherited from Composite.) |
| Public property | LastStatus | Gets or sets the last status. (Inherited from Composite.) |
| Public property | Parent | Gets or sets the parent. (Inherited from Composite.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [Execute(object)](ForcedBehaviorExecutor/Methods/Execute_F84716F7338C.md) | Executes the composite. (Overrides Composite.Execute().) |
| Protected method | Cleanup | Cleans up the current state. (Inherited from Composite.) |
| Public method | Equals(Composite) | Determines whether the specified object is equal to the current object. (Inherited from Composite.) |
| Public method | Run(object) | Runs the action. (Inherited from Composite.) |
| Public method | Start(object) | Starts the bot. (Inherited from Composite.) |
| Public method | Stop(object) | Stops the bot. (Inherited from Composite.) |
| Public method | Tick(object) | Processes one tick. (Inherited from Composite.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.Quest.Actions Namespace](../../../../namespaces/Bots/Quest/Actions.md)
