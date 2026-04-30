# WoWPoint Struct

Represents a wow point value.

## Namespace
[Styx.Logic.Pathing](../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct WoWPoint : IEquatable<WoWPoint>, IRangeAble
```

The WoWPoint type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWPoint](WoWPoint/Constructors/Constructor_A67DE16B017C.md) | Initializes a new instance of the WoWPoint struct. |
| Public constructor | [WoWPoint(float)](WoWPoint/Constructors/Constructor_BA20E656EB2E.md) | Initializes a new instance of the WoWPoint struct. |
| Public constructor | [WoWPoint(float, float, float)](WoWPoint/Constructors/Constructor_FBCA4E74DDD0.md) | Initializes a new instance of the WoWPoint struct. |
| Public constructor | [WoWPoint(double, double, double)](WoWPoint/Constructors/Constructor_06564FEB8B15.md) | Initializes a new instance of the WoWPoint struct. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [Center](WoWPoint/Fields/Center_B327F27E4AD2.md) | Represents the center. |
| Public field Static member | [Empty](WoWPoint/Fields/Empty_7ED0F63EDFCD.md) | Represents an empty value. |
| Public field Static member | [MaxValue](WoWPoint/Fields/MaxValue_67FAFCD4C92E.md) | Represents the maximum value. |
| Public field Static member | [MinValue](WoWPoint/Fields/MinValue_6C5AD739C928.md) | Represents the minimum value. |
| Public field | [X](WoWPoint/Fields/X_8250DB985212.md) | Stores the x. |
| Public field Static member | [XUnit](WoWPoint/Fields/XUnit_09C195DCCFAD.md) | Represents the x unit. |
| Public field | [Y](WoWPoint/Fields/Y_3224A9B3F280.md) | Stores the y. |
| Public field Static member | [YUnit](WoWPoint/Fields/YUnit_F78EF5E49750.md) | Represents the y unit. |
| Public field | [Z](WoWPoint/Fields/Z_60137010A42D.md) | Stores the z. |
| Public field Static member | [ZUnit](WoWPoint/Fields/ZUnit_027FD0C810C0.md) | Represents the z unit. |
| Public field Static member | [Zero](WoWPoint/Fields/Zero_08162B634E56.md) | Represents the zero value. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ComponentSum](WoWPoint/Properties/ComponentSum_149340BDFC88.md) | Gets the component sum. |
| Public property | [IsValid](WoWPoint/Properties/IsValid_81152DED14E5.md) | Gets a value indicating whether is valid. |
| Public property | [Length](WoWPoint/Properties/Length_F4B36B308D28.md) | Gets the length. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Add(float, float, float)](WoWPoint/Methods/Add_00F0E5BFE829.md) | Adds values. |
| Public method | [Distance(WoWPoint)](WoWPoint/Methods/Distance_0E1EF5C08586.md) | Computes the distance. |
| Public method | [Distance2D(WoWPoint)](WoWPoint/Methods/Distance2D_4E623A762D99.md) | Computes the 2D distance. |
| Public method | [Distance2DSqr(WoWPoint)](WoWPoint/Methods/Distance2DSqr_4CB7DC3455CB.md) | Computes the squared 2D distance. |
| Public method | [DistanceSqr(WoWPoint)](WoWPoint/Methods/DistanceSqr_338D92020838.md) | Computes the squared distance. |
| Public method | [Equals(WoWPoint)](WoWPoint/Methods/Equals_8C160B0EE345.md) | Determines whether the specified object is equal to the current object. |
| Public method | [Equals(object)](WoWPoint/Methods/Equals_609A09A11DA8.md) | Determines whether the specified object is equal to the current object. (Overrides ValueType.Equals().) |
| Public method Static member | [GetDirection(WoWPoint, WoWPoint)](WoWPoint/Methods/GetDirection_FD85AFBED19F.md) | Gets the direction. |
| Public method | [GetDirectionTo(WoWPoint)](WoWPoint/Methods/GetDirectionTo_A91C7107A300.md) | Gets the direction to. |
| Public method | [GetHashCode](WoWPoint/Methods/GetHashCode_2AFF092583EA.md) | Serves as a hash function for a particular type. (Overrides ValueType.GetHashCode().) |
| Public method | [GetRange](WoWPoint/Methods/GetRange_240BD79F8490.md) | Gets the range. |
| Public method | [MakeNegative](WoWPoint/Methods/MakeNegative_D538E608852D.md) | Makes the value negative. |
| Public method | [MakePositive](WoWPoint/Methods/MakePositive_7C6DEFF5817F.md) | Makes the value positive. |
| Public method | [Negate](WoWPoint/Methods/Negate_00470AA3D44F.md) | Negates the value. |
| Public method | [Normalize](WoWPoint/Methods/Normalize_9BEBF5FBBE0A.md) | Normalizes the value. |
| Public method | [RayCast(float, float)](WoWPoint/Methods/RayCast_2BC24986E412.md) | Performs a ray cast. |
| Public method Static member | [RayCast(WoWPoint, float, float)](WoWPoint/Methods/RayCast_C59CB94F323C.md) | Performs a ray cast. |
| Public method | [ToString](WoWPoint/Methods/ToString_69E9E087AB19.md) | Returns a string that represents the current object. (Overrides ValueType.ToString().) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing Namespace](../../../../namespaces/Styx/Logic/Pathing.md)
