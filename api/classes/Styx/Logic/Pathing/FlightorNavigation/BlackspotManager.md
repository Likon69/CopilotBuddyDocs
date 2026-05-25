# BlackspotManager Class

Manages polygon-based aerial blackspots that Flightor avoids during flight. Ported from HB 6.2.3 BlackspotManager; WotLK-only default data.

## Namespace
[Styx.Logic.Pathing.FlightorNavigation](../../../../../namespaces/Styx/Logic/Pathing/FlightorNavigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class BlackspotManager
```

The BlackspotManager type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [Blackspots](BlackspotManager/Properties/Blackspots_D437CC566B13.md) | All aerial blackspot polygons for the current map and player faction. Includes neutral polygons + faction-specific polygons. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [AddBlackspot(uint, WoWFactionGroup, Vector2[])](BlackspotManager/Methods/AddBlackspot_E7625CE4A317.md) | Adds the blackspot. |
| Public method Static member | [AddBlackspots(uint, WoWFactionGroup, IEnumerable<Vector2[]>)](BlackspotManager/Methods/AddBlackspots_D521B2594424.md) | Adds the blackspots. |
| Public method Static member | [IsInBlackspot(WoWPoint)](BlackspotManager/Methods/IsInBlackspot_2EFE19F8A3C5.md) | Returns true if falls inside any active aerial blackspot. |
| Public method Static member | [RemoveBlackspot(uint, WoWFactionGroup, Vector2[])](BlackspotManager/Methods/RemoveBlackspot_B43E6297596D.md) | Removes the blackspot. |
| Public method Static member | [RemoveBlackspots(uint, WoWFactionGroup, IEnumerable<Vector2[]>)](BlackspotManager/Methods/RemoveBlackspots_DD89D2903111.md) | Removes the blackspots. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Pathing.FlightorNavigation Namespace](../../../../../namespaces/Styx/Logic/Pathing/FlightorNavigation.md)
