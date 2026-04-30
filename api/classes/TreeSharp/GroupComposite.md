# GroupComposite Class

Represents a composite node that manages child composites.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    TreeSharp.GroupComposite

## Namespace
[TreeSharp](../../namespaces/TreeSharp.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class GroupComposite : Composite
```

The GroupComposite type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [GroupComposite(Composite[])](GroupComposite/Constructors/Constructor_93F77C8CE1C0.md) | Initializes a new instance of the GroupComposite class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Children](GroupComposite/Properties/Children_5E9DED586574.md) | Gets or sets the children. |
| Public property | [Selection](GroupComposite/Properties/Selection_227482EC359F.md) | Gets or sets the selection. |
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
| Public method | [AddChild(Composite)](GroupComposite/Methods/AddChild_87A01BB762E9.md) | Adds a child composite. |
| Public method | [InsertChild(int, Composite)](GroupComposite/Methods/InsertChild_1C8EA4105668.md) | Inserts a child composite. |
| Public method | [Start(object)](GroupComposite/Methods/Start_E59240189960.md) | Starts the bot. (Overrides Composite.Start().) |
| Protected method | [Cleanup](Composite/Methods/Cleanup_3F719FA40CFF.md) | Cleans up the current state. (Inherited from Composite.) |
| Public method | [Equals(Composite)](Composite/Methods/Equals_CBF6BA29E389.md) | Determines whether the specified object is equal to the current object. (Inherited from Composite.) |
| Protected method | [Execute(object)](Composite/Methods/Execute_151B119C72DB.md) | Executes the composite. (Inherited from Composite.) |
| Public method | [Run(object)](Composite/Methods/Run_BC9E13587AE6.md) | Runs the action. (Inherited from Composite.) |
| Public method | [Stop(object)](Composite/Methods/Stop_5E714027604F.md) | Stops the bot. (Inherited from Composite.) |
| Public method | [Tick(object)](Composite/Methods/Tick_C3134FF5E290.md) | Processes one tick. (Inherited from Composite.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[TreeSharp Namespace](../../namespaces/TreeSharp.md)
