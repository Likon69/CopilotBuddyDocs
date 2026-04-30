# Matrix Struct

Tripper.Tools.Math.Matrix — thin wrapper around . Matches HB 4.3.4's Matrix type with XNA-style M11–M44 field names. QBs use this via Vector3.Transform(pos, transport.GetWorldMatrix()).

## Namespace
[Tripper.Tools.Math](../../../../namespaces/Tripper/Tools/Math.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct Matrix
```

The Matrix type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Matrix](Matrix/Constructors/Constructor_9ABF73E6D53C.md) | Initializes a new instance of the Matrix struct. |
| Public constructor | [Matrix(float, float, float, float, float, float, float, float, float, float, float, float, float, float, float, float)](Matrix/Constructors/Constructor_DAFE51B8850C.md) | Initializes a new instance of the Matrix struct. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Identity](Matrix/Fields/Identity_E9004EE7D3E7.md) | Represents the identity value. |
| Public field | [M11](Matrix/Fields/M11_444DAD42C90A.md) | Stores the m11. |
| Public field | [M12](Matrix/Fields/M12_7417102B1307.md) | Stores the m12. |
| Public field | [M13](Matrix/Fields/M13_5ED04DFC28A6.md) | Stores the m13. |
| Public field | [M14](Matrix/Fields/M14_71E954C173D3.md) | Stores the m14. |
| Public field | [M21](Matrix/Fields/M21_DFC3698CEFA5.md) | Stores the m21. |
| Public field | [M22](Matrix/Fields/M22_3ABF6E337CEB.md) | Stores the m22. |
| Public field | [M23](Matrix/Fields/M23_B9BA8E1EC40F.md) | Stores the m23. |
| Public field | [M24](Matrix/Fields/M24_6BE029F15EE4.md) | Stores the m24. |
| Public field | [M31](Matrix/Fields/M31_B3FBB2DF625C.md) | Stores the m31. |
| Public field | [M32](Matrix/Fields/M32_82B80A463590.md) | Stores the m32. |
| Public field | [M33](Matrix/Fields/M33_A2C83C60B96C.md) | Stores the m33. |
| Public field | [M34](Matrix/Fields/M34_9AEAAF9B31C4.md) | Stores the m34. |
| Public field | [M41](Matrix/Fields/M41_E1FA05CD0BA1.md) | Stores the m41. |
| Public field | [M42](Matrix/Fields/M42_F0EFB17B2F6B.md) | Stores the m42. |
| Public field | [M43](Matrix/Fields/M43_DAC42FFEC8DF.md) | Stores the m43. |
| Public field | [M44](Matrix/Fields/M44_33C4B7B2DA35.md) | Stores the m44. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [CreateLookAt(Vector3, Vector3, Vector3)](Matrix/Methods/CreateLookAt_83233B637F09.md) | Creates the look at. |
| Public method Static member | [CreatePerspectiveFieldOfView(float, float, float, float)](Matrix/Methods/CreatePerspectiveFieldOfView_124C666EFA77.md) | Creates the perspective field of view. |
| Public method Static member | [Invert(Matrix, Matrix)](Matrix/Methods/Invert_C36D882504AC.md) | Inverts the value. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from ValueType.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from ValueType.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from ValueType.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Tripper.Tools.Math Namespace](../../../../namespaces/Tripper/Tools/Math.md)
