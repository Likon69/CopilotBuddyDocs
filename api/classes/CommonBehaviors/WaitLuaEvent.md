# WaitLuaEvent Class

Represents a wait for a Lua event.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    TreeSharp.GroupComposite
      TreeSharp.Decorator
        TreeSharp.Wait
          TreeSharp.WaitContinue
            CommonBehaviors.WaitLuaEvent

## Namespace
[CommonBehaviors](../../namespaces/CommonBehaviors.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WaitLuaEvent : WaitContinue
```

The WaitLuaEvent type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WaitLuaEvent(string, int, Composite)](WaitLuaEvent/Constructors/Constructor_4A802F0A5FA6.md) | Initializes a new instance of the WaitLuaEvent class. |
| Public constructor | [WaitLuaEvent(string, WaitGetTimeoutDelegate, Composite)](WaitLuaEvent/Constructors/Constructor_036349B1840B.md) | Initializes a new instance of the WaitLuaEvent class. |
| Public constructor | [WaitLuaEvent(string, TimeSpan, Composite)](WaitLuaEvent/Constructors/Constructor_35656BECF49D.md) | Initializes a new instance of the WaitLuaEvent class. |
| Public constructor | [WaitLuaEvent(string, int, CanRunDecoratorDelegate, Composite)](WaitLuaEvent/Constructors/Constructor_878892B067C5.md) | Initializes a new instance of the WaitLuaEvent class. |
| Public constructor | [WaitLuaEvent(string, WaitGetTimeoutDelegate, CanRunDecoratorDelegate, Composite)](WaitLuaEvent/Constructors/Constructor_145DC1344421.md) | Initializes a new instance of the WaitLuaEvent class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | Timeout | Gets or sets the timeout. (Inherited from Wait.) |
| Public property | DecoratedChild | Gets the decorated child. (Inherited from Decorator.) |
| Protected property | Runner | Gets the runner. (Inherited from Decorator.) |
| Public property | Children | Gets or sets the children. (Inherited from GroupComposite.) |
| Public property | Selection | Gets or sets the selection. (Inherited from GroupComposite.) |
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
| Protected method | [CanRun(object)](WaitLuaEvent/Methods/CanRun_8696131FA30F.md) | Determines whether can run. (Overrides Decorator.CanRun().) |
| Public method | [Start(object)](WaitLuaEvent/Methods/Start_FE371FB135C8.md) | Starts the bot. (Overrides Wait.Start().) |
| Public method | [Stop(object)](WaitLuaEvent/Methods/Stop_BA90B5B3288B.md) | Stops the bot. (Overrides Wait.Stop().) |
| Protected method | Execute(object) | Executes the composite. (Overrides Wait.Execute().). (Inherited from WaitContinue.) |
| Public method | AddChild(Composite) | Adds a child composite. (Inherited from GroupComposite.) |
| Public method | InsertChild(int, Composite) | Inserts a child composite. (Inherited from GroupComposite.) |
| Protected method | Cleanup | Cleans up the current state. (Inherited from Composite.) |
| Public method | Equals(Composite) | Determines whether the specified object is equal to the current object. (Inherited from Composite.) |
| Public method | Run(object) | Runs the action. (Inherited from Composite.) |
| Public method | Tick(object) | Processes one tick. (Inherited from Composite.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[CommonBehaviors Namespace](../../namespaces/CommonBehaviors.md)
