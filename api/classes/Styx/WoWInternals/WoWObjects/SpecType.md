# SpecType Enumeration

FEAT-16: Player specialization type for role detection. In WotLK, this is determined by analyzing talent point distribution. Matches HB 4.3.4 enum values: None=0, RangedDps=1, MeleeDps=2, Healer=3, Tank=4.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum SpecType
```

The SpecType type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [SpecType](SpecType/Constructors/Constructor_23CE7CE2BA5A.md) | Initializes a new instance of the SpecType enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [Healer](SpecType/Fields/Healer_0DEFBD596D85.md) | Represents the healer value. |
| Public field | [MeleeDps](SpecType/Fields/MeleeDps_D3A6A40A2382.md) | Represents the melee dps value. |
| Public field | [None](SpecType/Fields/None_EA24F943F335.md) | Represents the none value. |
| Public field | [RangedDps](SpecType/Fields/RangedDps_ED500DDD3C4D.md) | Represents the ranged dps value. |
| Public field | [Tank](SpecType/Fields/Tank_ED3ADAAB800C.md) | Represents the tank value. |

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
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
