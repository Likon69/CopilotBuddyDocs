# PathFindResult Class

Pathfinding result data, including points, polygons, flags, and status.

## Inheritance Hierarchy
System.Object
  Tripper.Navigation.PathFindResult

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed class PathFindResult
```

The PathFindResult type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PathFindResult](PathFindResult/Constructors/Constructor_F87B88F39012.md) | Initializes an empty PathFindResult (used for failed pathfinding). |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AbilityFlags](PathFindResult/Properties/AbilityFlags_3C972E2F20D2.md) | Array of ability flags required for each path segment. Indicates movement capabilities needed (Run, Swim, Jump, etc.). |
| Public property | [Aborted](PathFindResult/Properties/Aborted_F95F228A92EA.md) | Indicates if pathfinding was aborted before completion. |
| Public property | [Elapsed](PathFindResult/Properties/Elapsed_B28AEF5BD502.md) | Time elapsed during pathfinding operation. |
| Public property | [End](PathFindResult/Properties/End_25C630B093DD.md) | Ending position (actual end point on navmesh). |
| Public property | [EndPoly](PathFindResult/Properties/EndPoly_6FA8F56A23DD.md) | Ending polygon reference. |
| Public property | [FailStep](PathFindResult/Properties/FailStep_415E3E48EBC7.md) | If pathfinding failed, indicates the specific failure step. Only set when Status != Success. |
| Public property | [Flags](PathFindResult/Properties/Flags_0ECC655CDFCB.md) | Array of straight path flags for each path segment. Indicates segment type (Start, End, OffMeshConnection). |
| Public property | [IsPartialPath](PathFindResult/Properties/IsPartialPath_0832C2D96CD1.md) | Indicates if the path is incomplete. True when destination is unreachable but a partial path was found. |
| Public property | [PathLength](PathFindResult/Properties/PathLength_22A3EA849D1B.md) | Gets the number of points in the path. Returns 0 if pathfinding failed. |
| Public property | [Points](PathFindResult/Properties/Points_EBBE0A75BC72.md) | Array of world positions representing the path from start to end. Empty if pathfinding failed. |
| Public property | [PolyTypes](PathFindResult/Properties/PolyTypes_1EFFFF2FDD24.md) | Array of area types for each path segment. Indicates terrain type (Ground, Water, Elevator, etc.). |
| Public property | [Polygons](PathFindResult/Properties/Polygons_B2DEB0D6EABD.md) | Array of polygon references for each path segment. Used for advanced path manipulation and validation. |
| Public property | [Start](PathFindResult/Properties/Start_A4FE15310560.md) | Starting position (actual start point on navmesh). |
| Public property | [StartPoly](PathFindResult/Properties/StartPoly_97C95077D688.md) | Starting polygon reference. |
| Public property | [Status](PathFindResult/Properties/Status_6F5598A8605C.md) | Detour status of the pathfinding operation. |
| Public property | [Succeeded](PathFindResult/Properties/Succeeded_0F3FA0226F5A.md) | Gets a value indicating whether the pathfinding operation succeeded. Based on Status.Succeeded property. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [CreateFailed(PathFindStep)](PathFindResult/Methods/CreateFailed_47FF503F3D34.md) | Creates a failed PathFindResult with the specified error step. |
| Public method | [ToString](PathFindResult/Methods/ToString_66E24DDDDDE3.md) | Returns a string representation of this PathFindResult. (Overrides object.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Tripper.Navigation Namespace](../../../namespaces/Tripper/Navigation.md)
