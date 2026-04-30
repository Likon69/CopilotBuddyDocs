# PoiSelector Class

Represents a point-of-interest selector.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    TreeSharp.GroupComposite
      TreeSharp.Selector
        TreeSharp.PrioritySelector
          CommonBehaviors.PoiSelector

## Namespace
[CommonBehaviors](../../namespaces/CommonBehaviors.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class PoiSelector : PrioritySelector
```

The PoiSelector type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PoiSelector(Composite[])](PoiSelector/Constructors/Constructor_AF30C9D559D5.md) | Initializes a new instance of the PoiSelector class. |

## Properties

| | Name | Description |
| --- | --- | --- |
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
| Public method | [Tick(object)](PoiSelector/Methods/Tick_E6445A0A6697.md) | Processes one tick. (Overrides Composite.Tick().) |
| Protected method | Execute(object) | Executes the composite. (Overrides Selector.Execute().). (Inherited from PrioritySelector.) |
| Public method | AddChild(Composite) | Adds a child composite. (Inherited from GroupComposite.) |
| Public method | InsertChild(int, Composite) | Inserts a child composite. (Inherited from GroupComposite.) |
| Public method | Start(object) | Starts the bot. (Overrides Composite.Start().). (Inherited from GroupComposite.) |
| Protected method | Cleanup | Cleans up the current state. (Inherited from Composite.) |
| Public method | Equals(Composite) | Determines whether the specified object is equal to the current object. (Inherited from Composite.) |
| Public method | Run(object) | Runs the action. (Inherited from Composite.) |
| Public method | Stop(object) | Stops the bot. (Inherited from Composite.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[CommonBehaviors Namespace](../../namespaces/CommonBehaviors.md)
