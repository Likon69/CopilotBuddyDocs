# Status Struct

Represents a navigation status value.

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct Status : IEquatable<Status>
```

The Status type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Status](Status/Constructors/Constructor_A8F23068B843.md) | Initializes a new instance of the Status struct. |
| Public constructor | [Status(uint)](Status/Constructors/Constructor_E4D51AF08647.md) | Initializes a new instance of the Status struct. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Failed](Status/Properties/Failed_4A392E934C1A.md) | Gets a value indicating whether the operation failed. |
| Public property Static member | [Failure](Status/Properties/Failure_0E264825B46A.md) | Gets the failure. |
| Public property | [InProgress](Status/Properties/InProgress_F4B373B08330.md) | Gets a value indicating whether the operation is still in progress. |
| Public property | [IsPartialResult](Status/Properties/IsPartialResult_BCC895FD92F0.md) | Gets a value indicating whether the result is a partial path (goal polygon was not reached, closest reachable point was used). |
| Public property | [Succeeded](Status/Properties/Succeeded_F98124B39A66.md) | Gets a value indicating whether the operation succeeded. |
| Public property Static member | [Success](Status/Properties/Success_76B60899D170.md) | Gets the success. |
| Public property | [Value](Status/Properties/Value_3B43157CB4D7.md) | Gets the raw status value. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Equals(Status)](Status/Methods/Equals_F2E909E9E9AC.md) | Determines whether the specified object is equal to the current object. |
| Public method | [Equals(object)](Status/Methods/Equals_2065B7E94D26.md) | Determines whether the specified object is equal to the current object. (Overrides ValueType.Equals().) |
| Public method | [GetHashCode](Status/Methods/GetHashCode_CC32B2CCC5F6.md) | Serves as a hash function for a particular type. (Overrides ValueType.GetHashCode().) |
| Public method | [ToString](Status/Methods/ToString_7C4039DB4D70.md) | Returns a string that represents the current object. (Overrides ValueType.ToString().) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Tripper.Navigation Namespace](../../../namespaces/Tripper/Navigation.md)
