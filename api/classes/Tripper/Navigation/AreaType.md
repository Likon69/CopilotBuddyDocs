# AreaType Enumeration

Defines navigation area types for Detour navmesh polygons. These values correspond to Detour polygon area types and determine traversal rules.

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum AreaType
```

The AreaType type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [AreaType](AreaType/Constructors/Constructor_831DAD910600.md) | Initializes a new instance of the AreaType enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [Alliance](AreaType/Fields/Alliance_082A41522774.md) | Alliance-only area - restricted to Alliance faction. |
| Public field | [AlliancePortal](AreaType/Fields/AlliancePortal_0012413A6681.md) | Alliance portal - Alliance-specific portal. |
| Public field | [Blackspot](AreaType/Fields/Blackspot_9BA65941D63B.md) | Blackspot area - manually marked as unwalkable. |
| Public field | [Blocked](AreaType/Fields/Blocked_28157A709B6C.md) | Blocked area - permanently unwalkable. |
| Public field | [DefendersPortal](AreaType/Fields/DefendersPortal_4049041E6620.md) | Defenders portal - specific to battleground defenders. |
| Public field | [Elevator](AreaType/Fields/Elevator_F7212A52BF88.md) | Elevator platform - vertical transport mechanism. |
| Public field | [Fall](AreaType/Fields/Fall_C160B3B00533.md) | Falling area - used for jumps or drops. |
| Public field | [Gate](AreaType/Fields/Gate_AF54405A8038.md) | Gate area - battleground gates or similar barriers. |
| Public field | [Ground](AreaType/Fields/Ground_3F848A6178D9.md) | Ground surface - standard walkable terrain. |
| Public field | [Horde](AreaType/Fields/Horde_A60AE5FBC963.md) | Horde-only area - restricted to Horde faction. |
| Public field | [HordePortal](AreaType/Fields/HordePortal_A0CCC3A0AE07.md) | Horde portal - Horde-specific portal. |
| Public field | [InteractObject](AreaType/Fields/InteractObject_2A01DA887127.md) | Interactive object area - requires object interaction. |
| Public field | [InteractUnit](AreaType/Fields/InteractUnit_73A30214E0FC.md) | Interactive unit area - requires unit interaction. |
| Public field | [Lava](AreaType/Fields/Lava_6AAB3B6578E3.md) | Lava surface - typically avoided or requires special handling. |
| Public field | [Misc1](AreaType/Fields/Misc1_F0B0E74F4AF6.md) | Miscellaneous area type 1. |
| Public field | [Misc2](AreaType/Fields/Misc2_615EC97CDE71.md) | Miscellaneous area type 2. |
| Public field | [Misc3](AreaType/Fields/Misc3_E1E145DCB6A8.md) | Miscellaneous area type 3. |
| Public field | [Misc4](AreaType/Fields/Misc4_0BF47F619127.md) | Miscellaneous area type 4. |
| Public field | [Portal](AreaType/Fields/Portal_20D197F86F6A.md) | Portal area - teleportation or zone transition. |
| Public field | [Road](AreaType/Fields/Road_6FDCD80E0B1A.md) | Road surface - optimized for faster travel. |
| Public field | [Water](AreaType/Fields/Water_DDC65C38F815.md) | Water surface - requires swimming ability. |

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
