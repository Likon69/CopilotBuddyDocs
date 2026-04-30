# Wait Class

Represents a wait.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    TreeSharp.GroupComposite
      TreeSharp.Decorator
        TreeSharp.Wait

## Namespace
[TreeSharp](../../namespaces/TreeSharp.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class Wait : Decorator
```

The Wait type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Wait(int, Composite)](Wait/Constructors/Constructor_678AA01BB095.md) | Initializes a new instance of the Wait class. |
| Public constructor | [Wait(TimeSpan, Composite)](Wait/Constructors/Constructor_7889B361B2CA.md) | Initializes a new instance of the Wait class. |
| Public constructor | [Wait(WaitGetTimeoutDelegate, Composite)](Wait/Constructors/Constructor_E7D30067C2C0.md) | Initializes a new instance of the Wait class. |
| Public constructor | [Wait(TimeSpan, CanRunDecoratorDelegate, Composite)](Wait/Constructors/Constructor_FDC3A4F5F24A.md) | Initializes a new instance of the Wait class. |
| Public constructor | [Wait(int, CanRunDecoratorDelegate, Composite)](Wait/Constructors/Constructor_204E3326E14C.md) | Initializes a new instance of the Wait class. |
| Public constructor | [Wait(WaitGetTimeoutDelegate, CanRunDecoratorDelegate, Composite)](Wait/Constructors/Constructor_B1C4997B2CCE.md) | Initializes a new instance of the Wait class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Protected field | [End](Wait/Fields/End_C581D1163FC2.md) | Stores the end. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Timeout](Wait/Properties/Timeout_AACF9E42967D.md) | Gets or sets the timeout. |
| Public property | [DecoratedChild](Decorator/Properties/DecoratedChild_1DAC3C270A5E.md) | Gets the decorated child. (Inherited from Decorator.) |
| Protected property | [Runner](Decorator/Properties/Runner_916B3860B080.md) | Gets the runner. (Inherited from Decorator.) |
| Public property | [Children](GroupComposite/Properties/Children_5E9DED586574.md) | Gets or sets the children. (Inherited from GroupComposite.) |
| Public property | [Selection](GroupComposite/Properties/Selection_227482EC359F.md) | Gets or sets the selection. (Inherited from GroupComposite.) |
| Public property | [Children](Composite/Properties/Children_2024AC72E9EE.md) | Gets the children. (Inherited from Composite.) |
| Protected property | [CleanupHandlers](Composite/Properties/CleanupHandlers_A8A815C671D7.md) | Gets or sets the cleanup handlers. (Inherited from Composite.) |
| Protected property | [ContextChanger](Composite/Properties/ContextChanger_1D1A517EF8A1.md) | Gets or sets the context changer. (Inherited from Composite.) |
| Public property | [Guid](Composite/Properties/Guid_10BF9D25838E.md) | Gets the guid. (Inherited from Composite.) |
| Public property | [IsRunning](Composite/Properties/IsRunning_83A2FA669B5B.md) | HonorBuddy-compatible property: whether this composite is currently running. Many third-party bots reference `IsRunning` as a property. (Inherited from Composite.) |
| Public property | [LastStatus](Composite/Properties/LastStatus_946652612308.md) | Gets or sets the last status. (Inherited from Composite.) |
| Public property | [Parent](Composite/Properties/Parent_AEDB73D24FA0.md) | Gets or sets the parent. (Inherited from Composite.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [Execute(object)](Wait/Methods/Execute_A1B6F88D9E74.md) | Executes the composite. (Overrides Decorator.Execute().) |
| Public method | [Start(object)](Wait/Methods/Start_0D6C37B96959.md) | Starts the bot. (Overrides Decorator.Start().) |
| Public method | [Stop(object)](Wait/Methods/Stop_D13A13A26049.md) | Stops the bot. (Overrides Composite.Stop().) |
| Protected method | [CanRun(object)](Decorator/Methods/CanRun_0FE614F1F2A1.md) | Determines whether can run. (Inherited from Decorator.) |
| Public method | [AddChild(Composite)](GroupComposite/Methods/AddChild_87A01BB762E9.md) | Adds a child composite. (Inherited from GroupComposite.) |
| Public method | [InsertChild(int, Composite)](GroupComposite/Methods/InsertChild_1C8EA4105668.md) | Inserts a child composite. (Inherited from GroupComposite.) |
| Protected method | [Cleanup](Composite/Methods/Cleanup_3F719FA40CFF.md) | Cleans up the current state. (Inherited from Composite.) |
| Public method | [Equals(Composite)](Composite/Methods/Equals_CBF6BA29E389.md) | Determines whether the specified object is equal to the current object. (Inherited from Composite.) |
| Public method | [Run(object)](Composite/Methods/Run_BC9E13587AE6.md) | Runs the action. (Inherited from Composite.) |
| Public method | [Tick(object)](Composite/Methods/Tick_C3134FF5E290.md) | Processes one tick. (Inherited from Composite.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[TreeSharp Namespace](../../namespaces/TreeSharp.md)
