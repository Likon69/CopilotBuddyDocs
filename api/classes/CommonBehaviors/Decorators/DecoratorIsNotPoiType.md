# DecoratorIsNotPoiType Class

Represents an is not point of interest type decorator.

## Inheritance Hierarchy
System.Object
  TreeSharp.Composite
    TreeSharp.GroupComposite
      TreeSharp.Decorator
        CommonBehaviors.Decorators.DecoratorIsPoiType
          CommonBehaviors.Decorators.DecoratorIsNotPoiType

## Namespace
[CommonBehaviors.Decorators](../../../namespaces/CommonBehaviors/Decorators.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class DecoratorIsNotPoiType : DecoratorIsPoiType
```

The DecoratorIsNotPoiType type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [DecoratorIsNotPoiType(PoiType, Composite)](DecoratorIsNotPoiType/Constructors/Constructor_47ACB7FEAD38.md) | Initializes a new instance of the DecoratorIsNotPoiType class. |
| Public constructor | [DecoratorIsNotPoiType(IEnumerable<PoiType>, Composite)](DecoratorIsNotPoiType/Constructors/Constructor_C5ABA230DACE.md) | Initializes a new instance of the DecoratorIsNotPoiType class. |

## Properties

| | Name | Description |
| --- | --- | --- |
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
| Protected method | [CanRun(object)](DecoratorIsNotPoiType/Methods/CanRun_C98D80E4BCE8.md) | Determines whether can run. (Overrides DecoratorIsPoiType.CanRun().) |
| Protected method | Execute(object) | Executes the composite. (Overrides Composite.Execute().). (Inherited from Decorator.) |
| Public method | Start(object) | Starts the bot. (Overrides GroupComposite.Start().). (Inherited from Decorator.) |
| Public method | AddChild(Composite) | Adds a child composite. (Inherited from GroupComposite.) |
| Public method | InsertChild(int, Composite) | Inserts a child composite. (Inherited from GroupComposite.) |
| Protected method | Cleanup | Cleans up the current state. (Inherited from Composite.) |
| Public method | Equals(Composite) | Determines whether the specified object is equal to the current object. (Inherited from Composite.) |
| Public method | Run(object) | Runs the action. (Inherited from Composite.) |
| Public method | Stop(object) | Stops the bot. (Inherited from Composite.) |
| Public method | Tick(object) | Processes one tick. (Inherited from Composite.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[CommonBehaviors.Decorators Namespace](../../../namespaces/CommonBehaviors/Decorators.md)
