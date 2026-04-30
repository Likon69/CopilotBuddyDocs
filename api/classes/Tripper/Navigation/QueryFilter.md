# QueryFilter Class

Defines query filtering rules for pathfinding operations. Controls which polygon types are traversable and their costs.

## Inheritance Hierarchy
System.Object
  Tripper.Navigation.QueryFilter

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class QueryFilter
```

The QueryFilter type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [QueryFilter](QueryFilter/Constructors/Constructor_268FE8B269B9.md) | Initializes a new instance of the QueryFilter class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AreaCosts](QueryFilter/Properties/AreaCosts_A1A40D6C2DDE.md) | Cost multipliers for different area types. Higher cost = less preferred path. |
| Public property | [ExcludeFlags](QueryFilter/Properties/ExcludeFlags_0F7A0115A5B7.md) | Flags that prevent a polygon from being traversable. |
| Public property | [IncludeFlags](QueryFilter/Properties/IncludeFlags_BE17B862C5CC.md) | Flags that must be present on a polygon for it to be traversable. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Clone](QueryFilter/Methods/Clone_8FAFFE2E14F6.md) | Creates a copy of this query filter. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Tripper.Navigation Namespace](../../../namespaces/Tripper/Navigation.md)
