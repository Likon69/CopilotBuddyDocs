# PolygonReference Struct

Represents a polygon reference.

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct PolygonReference : IEquatable<PolygonReference>
```

The PolygonReference type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PolygonReference](PolygonReference/Constructors/Constructor_64E55F9D4165.md) | Initializes a new instance of the PolygonReference struct. |
| Public constructor | [PolygonReference(ulong)](PolygonReference/Constructors/Constructor_2BDB4050441E.md) | Initializes a new polygon reference with the specified ID. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [Id](PolygonReference/Fields/Id_D9E4FB4B1786.md) | The unique identifier for this polygon. Note: Detour uses 64-bit poly refs with DT_POLYREF64 defined. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [Invalid](PolygonReference/Properties/Invalid_11122140994C.md) | Gets an invalid polygon reference (ID = 0). |
| Public property | [IsValid](PolygonReference/Properties/IsValid_2635E58567E2.md) | Gets a value indicating whether this polygon reference is valid. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Equals(PolygonReference)](PolygonReference/Methods/Equals_2459EEDAF0A9.md) | Determines whether the specified object is equal to the current object. |
| Public method | [Equals(object)](PolygonReference/Methods/Equals_D7A120450517.md) | Determines whether the specified object is equal to the current object. (Overrides ValueType.Equals().) |
| Public method | [GetHashCode](PolygonReference/Methods/GetHashCode_AEADA00EEF64.md) | Serves as a hash function for a particular type. (Overrides ValueType.GetHashCode().) |
| Public method | [ToString](PolygonReference/Methods/ToString_DCB6D480B84E.md) | Returns a string that represents the current object. (Overrides ValueType.ToString().) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Tripper.Navigation Namespace](../../../namespaces/Tripper/Navigation.md)
