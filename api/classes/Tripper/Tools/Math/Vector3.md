# Vector3 Struct

Represents a 3D vector.

## Namespace
[Tripper.Tools.Math](../../../../namespaces/Tripper/Tools/Math.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct Vector3 : IEquatable<Vector3>
```

The Vector3 type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Vector3](Vector3/Constructors/Constructor_F38E9B9B3757.md) | Initializes a new instance of the Vector3 struct. |
| Public constructor | [Vector3(float)](Vector3/Constructors/Constructor_DD70C98FA42E.md) | Initializes a new instance of the Vector3 struct. |
| Public constructor | [Vector3(float, float, float)](Vector3/Constructors/Constructor_AD454CDEE665.md) | Initializes a new instance of the Vector3 struct. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [One](Vector3/Fields/One_37B88DFA17D9.md) | Represents the one value. |
| Public field | [X](Vector3/Fields/X_B852924F201F.md) | Stores the x. |
| Public field | [Y](Vector3/Fields/Y_CC1423C2DFBC.md) | Stores the y. |
| Public field | [Z](Vector3/Fields/Z_CAE96C8995E0.md) | Stores the z. |
| Public field Static member | [Zero](Vector3/Fields/Zero_0CD985860699.md) | Represents the zero value. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Magnitude](Vector3/Properties/Magnitude_B05ABE64D02F.md) | Gets the magnitude. |
| Public property | [MagnitudeSqr](Vector3/Properties/MagnitudeSqr_9A49DF2B823E.md) | Gets the magnitude sqr. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Cross(Vector3, Vector3)](Vector3/Methods/Cross_E0F22E7E6A79.md) | Computes the cross product. |
| Public method | [Distance(Vector3)](Vector3/Methods/Distance_64A0C005ADD0.md) | Computes the distance. |
| Public method | [DistanceSqr(Vector3)](Vector3/Methods/DistanceSqr_4FE85CFFCD71.md) | Computes the squared distance. |
| Public method Static member | [Dot(Vector3, Vector3)](Vector3/Methods/Dot_8E9DA7593D25.md) | Computes the dot product. |
| Public method | [Equals(Vector3)](Vector3/Methods/Equals_F1272EB8B612.md) | Determines whether the specified object is equal to the current object. |
| Public method | [Equals(object)](Vector3/Methods/Equals_8EE5835D29CE.md) | Determines whether the specified object is equal to the current object. (Overrides ValueType.Equals().) |
| Public method | [GetHashCode](Vector3/Methods/GetHashCode_C1635F6BBFCD.md) | Serves as a hash function for a particular type. (Overrides ValueType.GetHashCode().) |
| Public method | [Normalize](Vector3/Methods/Normalize_C9F1B4D5EFDC.md) | Normalizes the value. |
| Public method Static member | [NormalizedDirection(Vector3, Vector3)](Vector3/Methods/NormalizedDirection_64BB2B8AD6BE.md) | Computes the normalized direction. |
| Public method | [ToString](Vector3/Methods/ToString_4AA251893502.md) | Returns a string that represents the current object. (Overrides ValueType.ToString().) |
| Public method Static member | [Transform(Vector3, Matrix)](Vector3/Methods/Transform_AA1614E58AE4.md) | Transforms a vector by a matrix (position transform). Used by MyCTM.cs: Vector3.Transform(relLoc, transport.GetWorldMatrix()) |
| Public method Static member | [Transform(Vector3, Matrix, Vector3)](Vector3/Methods/Transform_661A9C90E7C1.md) | ref/out overload matching HB 4.3.4 signature. |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Tripper.Tools.Math Namespace](../../../../namespaces/Tripper/Tools/Math.md)
