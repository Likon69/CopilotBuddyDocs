# ActionMoveToGrindArea Class

Represents a move to grind area action.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    TreeSharp.Action
      CommonBehaviors.Actions.NavigationAction
        Bots.Quest.Objectives.ActionMoveToGrindArea

## Namespace
[Bots.Quest.Objectives](../../../../namespaces/Bots/Quest/Objectives.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ActionMoveToGrindArea : NavigationAction
```

The ActionMoveToGrindArea type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ActionMoveToGrindArea(GrindArea)](ActionMoveToGrindArea/Constructors/Constructor_ADC1E050122D.md) | Initializes a new instance of the ActionMoveToGrindArea class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | Runner | Gets the runner. (Inherited from Action.) |
| Public property | SucceedRunner | Gets the succeed runner. (Inherited from Action.) |
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
| Protected method | [Run(object)](ActionMoveToGrindArea/Methods/Run_A59DF8F8A2B7.md) | Runs the action. (Overrides NavigationAction.Run().) |
| Protected method | Execute(object) | Executes the composite. (Overrides Composite.Execute().). (Inherited from Action.) |
| Protected method | RunAction(object) | Runs the action. (Inherited from Action.) |
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
[Bots.Quest.Objectives Namespace](../../../../namespaces/Bots/Quest/Objectives.md)
