# PathFindStep Enumeration

Pathfinding step values used to track progress and failures.

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed enum PathFindStep
```

The PathFindStep type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PathFindStep](PathFindStep/Constructors/Constructor_A9F041CC9631.md) | Initializes a new instance of the PathFindStep enumeration. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [FinalizePathFind](PathFindStep/Fields/FinalizePathFind_7B91BE3B1B9A.md) | Finalizing the pathfinding result. |
| Public field | [FindEndPoly](PathFindStep/Fields/FindEndPoly_9CB1BC81903A.md) | Finding the ending polygon on the navmesh. |
| Public field | [FindStartPoly](PathFindStep/Fields/FindStartPoly_B082BE221E3E.md) | Finding the starting polygon on the navmesh. |
| Public field | [FindStraightPath](PathFindStep/Fields/FindStraightPath_EE902BC381CA.md) | Finding the straight path from polygon corridor. |
| Public field | [InitPathFind](PathFindStep/Fields/InitPathFind_2EE328DC1ECA.md) | Initializing the pathfinding query. |
| Public field | [None](PathFindStep/Fields/None_57D088B7378A.md) | No step or initial state. |
| Public field | [SnapPartialPathToEnd](PathFindStep/Fields/SnapPartialPathToEnd_AA742667C4D6.md) | Snapping partial path to the end point. |
| Public field | [UpdatePathFind](PathFindStep/Fields/UpdatePathFind_40BB13A01D2A.md) | Updating/calculating the pathfinding corridor. |

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
