# AbilityFlags Enumeration

Defines movement abilities and traversal capabilities for pathfinding. Used as flags in Detour query filters to determine valid navigation paths.

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum AbilityFlags
```

The AbilityFlags type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [AbilityFlags](AbilityFlags/Constructors/Constructor_1F80931E34FF.md) | Initializes a new instance of the AbilityFlags enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [All](AbilityFlags/Fields/All_0E814894A32A.md) | All abilities combined - full traversal capabilities. |
| Public field | [Alliance](AbilityFlags/Fields/Alliance_EC54A2F2DDE4.md) | Alliance faction access - can traverse Alliance-only areas. |
| Public field | [Horde](AbilityFlags/Fields/Horde_99501D6A95A8.md) | Horde faction access - can traverse Horde-only areas. |
| Public field | [Jump](AbilityFlags/Fields/Jump_CEC84EA417F5.md) | Can jump over obstacles or gaps. |
| Public field | [None](AbilityFlags/Fields/None_3D56E5838D39.md) | No abilities specified. |
| Public field | [Run](AbilityFlags/Fields/Run_C59F4B1115C6.md) | Can walk/run on ground surfaces. |
| Public field | [RunSafe](AbilityFlags/Fields/RunSafe_1A6AE243CDF6.md) | Can run safely - areas verified as safe traversal (HB 3.3.5). |
| Public field | [Swim](AbilityFlags/Fields/Swim_9497F4F2FE08.md) | Can swim through water. |
| Public field | [Teleport](AbilityFlags/Fields/Teleport_492A1683D81C.md) | Can use teleport/portal mechanics. |
| Public field | [Transport](AbilityFlags/Fields/Transport_30C1AB9BF845.md) | Can use transport vehicles (boats, zeppelins, elevators). |
| Public field | [Unwalkable](AbilityFlags/Fields/Unwalkable_6A182BD53D83.md) | Area is unwalkable - should be avoided. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | CompareTo(object) | Compares the current instance with another object. (Inherited from Enum.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides ValueType.Equals().). (Inherited from Enum.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides ValueType.GetHashCode().). (Inherited from Enum.) |
| Public method | GetTypeCode | Gets the type code. (Inherited from Enum.) |
| Public method | HasFlag(Enum) | Determines whether has flag. (Inherited from Enum.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides ValueType.ToString().). (Inherited from Enum.) |
| Public method | ToString(string) | Converts the current value to its string representation. (Inherited from Enum.) |
| Public method | ToString(IFormatProvider) | Converts the current value to its string representation. (Inherited from Enum.) |
| Public method | ToString(string, IFormatProvider) | Converts the current value to its string representation. (Inherited from Enum.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Tripper.Navigation Namespace](../../../namespaces/Tripper/Navigation.md)
