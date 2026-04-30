# Action Class

Represents an action node.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    TreeSharp.Action

## Namespace
[TreeSharp](../../namespaces/TreeSharp.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class Action : Composite
```

The Action type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Action](Action/Constructors/Constructor_CE83EEC33760.md) | Initializes a new instance of the Action class. |
| Public constructor | [Action(ActionDelegate)](Action/Constructors/Constructor_F6DE010A6AC4.md) | Initializes a new instance of the Action class. |
| Public constructor | [Action(ActionSucceedDelegate)](Action/Constructors/Constructor_900E7B47E0E3.md) | Initializes a new instance of the Action class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Runner](Action/Properties/Runner_09E97C3B8939.md) | Gets the runner. |
| Public property | [SucceedRunner](Action/Properties/SucceedRunner_A78BCB391EC6.md) | Gets the succeed runner. |
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
| Protected method | [Execute(object)](Action/Methods/Execute_4843FEEB7653.md) | Executes the composite. (Overrides Composite.Execute().) |
| Protected method | [Run(object)](Action/Methods/Run_A400713632B5.md) | Runs the action. |
| Protected method | [RunAction(object)](Action/Methods/RunAction_E851F48540C1.md) | Runs the action. |
| Protected method | Cleanup | Cleans up the current state. (Inherited from Composite.) |
| Public method | Equals(Composite) | Determines whether the specified object is equal to the current object. (Inherited from Composite.) |
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
[TreeSharp Namespace](../../namespaces/TreeSharp.md)
