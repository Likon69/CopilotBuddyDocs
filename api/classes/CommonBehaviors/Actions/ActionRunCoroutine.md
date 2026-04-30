# ActionRunCoroutine Class

Port of HB 6.2.3 CommonBehaviors.Actions.ActionRunCoroutine. Bridges async Task-based coroutines with TreeSharp's synchronous behavior tree. Each Tick() calls Coroutine.Resume() which advances the async method by one step.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    TreeSharp.Action
      CommonBehaviors.Actions.ActionRunCoroutine

## Namespace
[CommonBehaviors.Actions](../../../namespaces/CommonBehaviors/Actions.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ActionRunCoroutine : Action
```

The ActionRunCoroutine type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ActionRunCoroutine(Func<object, Coroutine>)](ActionRunCoroutine/Constructors/Constructor_E4274EB669C5.md) | Initializes a new instance of the ActionRunCoroutine class. |
| Public constructor | [ActionRunCoroutine(Func<object, Task<bool>>)](ActionRunCoroutine/Constructors/Constructor_8C8705A29756.md) | Initializes a new instance of the ActionRunCoroutine class. |
| Public constructor | [ActionRunCoroutine(Func<object, CoroutineTask<bool>>)](ActionRunCoroutine/Constructors/Constructor_084AA708DCB4.md) | Initializes a new instance of the ActionRunCoroutine class. |
| Public constructor | [ActionRunCoroutine(Func<object, Task>)](ActionRunCoroutine/Constructors/Constructor_09E508B0E86A.md) | Initializes a new instance of the ActionRunCoroutine class. |
| Public constructor | [ActionRunCoroutine(Func<object, CoroutineTask>)](ActionRunCoroutine/Constructors/Constructor_C714D898687A.md) | Initializes a new instance of the ActionRunCoroutine class. |

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
| Protected method | [Run(object)](ActionRunCoroutine/Methods/Run_D1AC492F5A5E.md) | Runs the action. (Overrides Action.Run().) |
| Public method | [Start(object)](ActionRunCoroutine/Methods/Start_5AFF84E3942B.md) | Starts the bot. (Overrides Composite.Start().) |
| Public method | [Stop(object)](ActionRunCoroutine/Methods/Stop_A6F52611A764.md) | Stops the bot. (Overrides Composite.Stop().) |
| Protected method | Execute(object) | Executes the composite. (Overrides Composite.Execute().). (Inherited from Action.) |
| Protected method | RunAction(object) | Runs the action. (Inherited from Action.) |
| Protected method | Cleanup | Cleans up the current state. (Inherited from Composite.) |
| Public method | Equals(Composite) | Determines whether the specified object is equal to the current object. (Inherited from Composite.) |
| Public method | Tick(object) | Processes one tick. (Inherited from Composite.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[CommonBehaviors.Actions Namespace](../../../namespaces/CommonBehaviors/Actions.md)
