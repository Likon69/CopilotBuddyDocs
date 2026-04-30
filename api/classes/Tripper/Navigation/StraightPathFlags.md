# StraightPathFlags Enumeration

Straight path flags returned by Detour findStraightPath. Matches Detour native dtStraightPathFlags (DetourNavMesh.h). Used to detect segment types and off-mesh connections in navigation paths.

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum StraightPathFlags
```

The StraightPathFlags type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [StraightPathFlags](StraightPathFlags/Constructors/Constructor_5B0322D8E18B.md) | Initializes a new instance of the StraightPathFlags enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [End](StraightPathFlags/Fields/End_5C87626164E3.md) | End of a path segment (DT_STRAIGHTPATH_END). |
| Public field | [None](StraightPathFlags/Fields/None_3A649F88BAD9.md) | No flags specified. |
| Public field | [OffMeshConnection](StraightPathFlags/Fields/OffMeshConnection_5A0CDEAAA4DB.md) | Off-mesh connection point (DT_STRAIGHTPATH_OFFMESH_CONNECTION). Indicates elevator, portal, or special navigation at this waypoint. Critical flag for detecting and handling offmesh traversal. |
| Public field | [Start](StraightPathFlags/Fields/Start_ED27725274EC.md) | Start of a path segment (DT_STRAIGHTPATH_START). |

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
