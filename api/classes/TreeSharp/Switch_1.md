# Switch<T> Class

This composite will perform a 'switch' statement to execute a specific branch of logic. This is useful for selecting specific branches, for different types of agents. (e.g. rogue, mage, and warrior branches)

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    TreeSharp.GroupComposite
      TreeSharp.Switch<T>

## Namespace
[TreeSharp](../../namespaces/TreeSharp.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class Switch<T> : GroupComposite
```

The Switch<T> type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Switch(Func<T>, SwitchArgument<T>[])](Switch_1/Constructors/Constructor_868CC61D56D3.md) | Initializes a new instance of the Switch<T> class. |
| Public constructor | [Switch(RetrieveSwitchParameterDelegate<T>, SwitchArgument<T>[])](Switch_1/Constructors/Constructor_48ED68703F12.md) | Initializes a new instance of the Switch<T> class. |
| Public constructor | [Switch(Func<T>, Composite, SwitchArgument<T>[])](Switch_1/Constructors/Constructor_2B2B3B73F3EF.md) | Initializes a new instance of the Switch<T> class. |
| Public constructor | [Switch(RetrieveSwitchParameterDelegate<T>, Composite, SwitchArgument<T>[])](Switch_1/Constructors/Constructor_3994A8C340F5.md) | Initializes a new instance of the Switch<T> class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Protected property | [Arguments](Switch_1/Properties/Arguments_5B2A7B8CBD04.md) | The switch arguments. |
| Protected property | [Default](Switch_1/Properties/Default_9904133D3DAD.md) | The 'default' argument to be carried out if no other switch conditions are met. |
| Protected property | [Statement](Switch_1/Properties/Statement_91A6C51935A6.md) | The statement assigned to this Switch that will determine which logical branch to take. |
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
| Protected method | [Execute(object)](Switch_1/Methods/Execute_65F830401920.md) | Executes the composite. (Overrides Composite.Execute().) |
| Protected method | [RunSwitch](Switch_1/Methods/RunSwitch_7B0379CB16B0.md) | Runs the switch. |
| Public method | [AddChild(Composite)](GroupComposite/Methods/AddChild_87A01BB762E9.md) | Adds a child composite. (Inherited from GroupComposite.) |
| Public method | [InsertChild(int, Composite)](GroupComposite/Methods/InsertChild_1C8EA4105668.md) | Inserts a child composite. (Inherited from GroupComposite.) |
| Public method | [Start(object)](GroupComposite/Methods/Start_E59240189960.md) | Starts the bot. (Overrides Composite.Start().). (Inherited from GroupComposite.) |
| Protected method | [Cleanup](Composite/Methods/Cleanup_3F719FA40CFF.md) | Cleans up the current state. (Inherited from Composite.) |
| Public method | [Equals(Composite)](Composite/Methods/Equals_CBF6BA29E389.md) | Determines whether the specified object is equal to the current object. (Inherited from Composite.) |
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
