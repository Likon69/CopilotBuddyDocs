# HookExecutor Class

Port of HB 6.2.3 Styx.Common.HookExecutor. A TreeSharp Action that reads TreeHooks at Start() time, rebuilds a PrioritySelector from registered operations, and ticks it. Uses a guard counter to detect when hooks change.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    TreeSharp.Action
      Styx.Common.HookExecutor

## Namespace
[Styx.Common](../../../namespaces/Styx/Common.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class HookExecutor : Action
```

The HookExecutor type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [HookExecutor(string, string, Composite)](HookExecutor/Constructors/Constructor_EEDD0117B1C2.md) | Initializes a new instance of the HookExecutor class. |

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
| Protected method | [Run(object)](HookExecutor/Methods/Run_898A092263DD.md) | Runs the action. (Overrides Action.Run().) |
| Public method | [Start(object)](HookExecutor/Methods/Start_5419983EBC28.md) | Starts the bot. (Overrides Composite.Start().) |
| Public method | [Stop(object)](HookExecutor/Methods/Stop_2EDC9AE6224C.md) | Stops the bot. (Overrides Composite.Stop().) |
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
[Styx.Common Namespace](../../../namespaces/Styx/Common.md)
