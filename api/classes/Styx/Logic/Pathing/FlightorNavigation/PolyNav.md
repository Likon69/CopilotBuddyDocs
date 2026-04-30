# PolyNav Class

2D polygon-aware path navigator. Given a continent boundary polygon and a set of hole polygons (aerial blackspots), routes a path between two points using a visibility graph and A*. Ported from HB 6.2.3 PolyNav.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Pathing.FlightorNavigation.PolyNav

## Namespace
[Styx.Logic.Pathing.FlightorNavigation](../../../../../namespaces/Styx/Logic/Pathing/FlightorNavigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class PolyNav
```

The PolyNav type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PolyNav(Vector2[], IEnumerable<Vector2[]>)](PolyNav/Constructors/Constructor_DA317AA8BC21.md) | Initializes a new instance of the PolyNav class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Holes](PolyNav/Properties/Holes_DE7158EED274.md) | Hole polygons (aerial blackspots) that paths must route around. |
| Public property | [Points](PolyNav/Properties/Points_93C3FE4B4691.md) | Continent boundary polygon (must be convex or simple). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [ContainsLine(Vector2, Vector2)](PolyNav/Methods/ContainsLine_01AE0225A431.md) | Returns true if the line segment from to lies entirely within the navigable polygon (inside the outer boundary and not crossing any hole). |
| Public method | [ContainsPoint(Vector2)](PolyNav/Methods/ContainsPoint_77F529406A53.md) | Returns true if is inside the navigable area. |
| Public method | [FindPath(Vector2, Vector2)](PolyNav/Methods/FindPath_C463AE8EA60E.md) | Find a 2D path from to . Returns an empty array if either point is outside the navigable area. Returns {start, end} if a straight line is clear. Otherwise returns visibility-graph waypoints via A*. |
| Public method | [GetBounds(Vector2, Vector2)](PolyNav/Methods/GetBounds_7D87DCFB3924.md) | Compute the bounding box of the continent polygon. |
| Public method | [GetConnections(Vector2, Vector2)](PolyNav/Methods/GetConnections_7260F054889B.md) | Returns the neighbour positions of the graph node closest to . Sets to that node's exact position. (method GetConnections in WoD PolyNav source) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing.FlightorNavigation Namespace](../../../../../namespaces/Styx/Logic/Pathing/FlightorNavigation.md)
