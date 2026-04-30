# PerFrameCachedValue<T> Class

Exact port of HB 5.4.8/6.2.3 PerFrameCachedValue. Caches a value per EndScene frame using Executor.FrameCount. Multiple accesses in the same frame return the cached value (0 RPM).

## Inheritance Hierarchy
System.Object
  Styx.Helpers.PerFrameCachedValue<T>

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class PerFrameCachedValue<T>
```

The PerFrameCachedValue<T> type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PerFrameCachedValue(Func<T>)](PerFrameCachedValue_1/Constructors/Constructor_0FE18D7B79EE.md) | Initializes a new instance of the PerFrameCachedValue<T> class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Value](PerFrameCachedValue_1/Properties/Value_CF07897077FF.md) | Gets the value. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Invalidate](PerFrameCachedValue_1/Methods/Invalidate_CAE867C29F0C.md) | Forces a cache refresh on the next access. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
