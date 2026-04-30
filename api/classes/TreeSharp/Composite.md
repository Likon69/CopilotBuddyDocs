# Composite Class

Represents a composite.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite

## Namespace
[TreeSharp](../../namespaces/TreeSharp.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class Composite : IEquatable<Composite>
```

The Composite type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [Composite](Composite/Constructors/Constructor_12E614A2C19B.md) | Initializes a new instance of the Composite class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Protected field Static member | [Locker](Composite/Fields/Locker_2CDF766C2FFA.md) | Represents the locker. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Children](Composite/Properties/Children_2024AC72E9EE.md) | Gets the children. |
| Protected property | [CleanupHandlers](Composite/Properties/CleanupHandlers_A8A815C671D7.md) | Gets or sets the cleanup handlers. |
| Protected property | [ContextChanger](Composite/Properties/ContextChanger_1D1A517EF8A1.md) | Gets or sets the context changer. |
| Public property | [Guid](Composite/Properties/Guid_10BF9D25838E.md) | Gets the guid. |
| Public property | [IsRunning](Composite/Properties/IsRunning_83A2FA669B5B.md) | HonorBuddy-compatible property: whether this composite is currently running. Many third-party bots reference `IsRunning` as a property. |
| Public property | [LastStatus](Composite/Properties/LastStatus_946652612308.md) | Gets or sets the last status. |
| Public property | [Parent](Composite/Properties/Parent_AEDB73D24FA0.md) | Gets or sets the parent. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Protected method | [Cleanup](Composite/Methods/Cleanup_3F719FA40CFF.md) | Cleans up the current state. |
| Public method | [Equals(Composite)](Composite/Methods/Equals_CBF6BA29E389.md) | Determines whether the specified object is equal to the current object. |
| Protected method | [Execute(object)](Composite/Methods/Execute_151B119C72DB.md) | Executes the composite. |
| Public method | [Run(object)](Composite/Methods/Run_BC9E13587AE6.md) | Runs the action. |
| Public method | [Start(object)](Composite/Methods/Start_4A89E7CF173D.md) | Starts the bot. |
| Public method | [Stop(object)](Composite/Methods/Stop_5E714027604F.md) | Stops the bot. |
| Public method | [Tick(object)](Composite/Methods/Tick_C3134FF5E290.md) | Processes one tick. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[TreeSharp Namespace](../../namespaces/TreeSharp.md)
