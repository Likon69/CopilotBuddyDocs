# TimeCachedValue<T> Class

Simple wrapper that caches the result of a producer delegate for a fixed amount of time. Ported directly from HonorBuddy 3.3.5a.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.TimeCachedValue<T>

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class TimeCachedValue<T>
```

The TimeCachedValue<T> type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [TimeCachedValue(TimeSpan, Func<T>)](TimeCachedValue_1/Constructors/Constructor_99BA0F4C0C60.md) | Initializes a new instance of the TimeCachedValue<T> class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Value](TimeCachedValue_1/Properties/Value_E8EACCAE0CC2.md) | Gets the cached value, regenerating it if the interval has elapsed. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Reset](TimeCachedValue_1/Methods/Reset_537D8BB6E4CF.md) | Clears the cached data so that the next access will call the producer again. HonorBuddy recreated its cache objects on updates; we provide Reset for convenience. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
