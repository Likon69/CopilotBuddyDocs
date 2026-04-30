# PathPostProcessing Enumeration

Path post-processing mode for pathfinding results. Matches Honorbuddy's PathPostProcessing enum.

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum PathPostProcessing
```

The PathPostProcessing type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PathPostProcessing](PathPostProcessing/Constructors/Constructor_A5BE9DBB84DF.md) | Initializes a new instance of the PathPostProcessing enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [MoveAwayFromEdges](PathPostProcessing/Fields/MoveAwayFromEdges_76E9AAAED9D9.md) | Move waypoints away from navmesh edges/walls. This prevents the character from walking too close to walls, stairs edges, or other terrain features. |
| Public field | [None](PathPostProcessing/Fields/None_DC8A158C2D9C.md) | No post-processing. Return raw path from Detour. |
| Public field | [Randomize](PathPostProcessing/Fields/Randomize_1B3D0FFF6B07.md) | Add randomization to path points for more human-like movement. Includes edge avoidance plus random offset. |

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
