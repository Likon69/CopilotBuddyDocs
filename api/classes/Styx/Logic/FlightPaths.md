# FlightPaths Class

FlightPaths - Manages taxi/flight path learning and usage Ported from HB 4.3.4

## Namespace
[Styx.Logic](../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class FlightPaths
```

The FlightPaths type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [CanTakeFlightPaths](FlightPaths/Properties/CanTakeFlightPaths_A45DD587E507.md) | Whether flight paths are enabled in settings |
| Public property Static member | [IsAtEnd](FlightPaths/Properties/IsAtEnd_B7C4B4A4E55D.md) | Whether we're at the end flight point |
| Public property Static member | [IsAtStart](FlightPaths/Properties/IsAtStart_EA2F60E0BEC4.md) | Whether we're at the start flight point |
| Public property Static member | [NearestFlightMerchant](FlightPaths/Properties/NearestFlightMerchant_F01E6CD91561.md) | Get nearest valid flight master |
| Public property Static member | [NeedFlightPath](FlightPaths/Properties/NeedFlightPath_1A7BA91DA069.md) | Whether we need to visit a flight path |
| Public property Static member | [Reason](FlightPaths/Properties/Reason_458A5F16F43F.md) | Current reason for flight path action |
| Public property Static member | [TakingPathFrom](FlightPaths/Properties/TakingPathFrom_499BFC24F395.md) | Origin flight node |
| Public property Static member | [TakingPathTo](FlightPaths/Properties/TakingPathTo_025993DCC0DE.md) | Destination flight node |
| Public property Static member | [XmlNodes](FlightPaths/Properties/XmlNodes_C14AE245E9D5.md) | Known flight nodes from XML |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [GetFlightPathTime(WoWPoint, WoWPoint)](FlightPaths/Methods/GetFlightPathTime_40029B6C8C6B.md) | Get estimated flight time between two points |
| Public method Static member | [GetFullTravelTime(WoWPoint, WoWPoint, WoWPoint, WoWPoint, float)](FlightPaths/Methods/GetFullTravelTime_EF506B8B592C.md) | Get total travel time including ground paths to/from flight points |
| Public method Static member | [GetRunPathTime(IList<WoWPoint>, float)](FlightPaths/Methods/GetRunPathTime_F376F7711EDC.md) | Get time to run a path at given speed |
| Public method Static member | [Initialize](FlightPaths/Methods/Initialize_1F4B13551DA9.md) | Initialize flight paths system |
| Public method Static member | [NeedNearbyUpdate](FlightPaths/Methods/NeedNearbyUpdate_FC2C766C7CCC.md) | Check if we need to update nearby flight path info |
| Public method Static member | [Reset](FlightPaths/Methods/Reset_575DCC5BFF51.md) | Reset flight path state |
| Public method Static member | [SetFlightPathUsage(WoWPoint, WoWPoint, WoWPoint, WoWPoint)](FlightPaths/Methods/SetFlightPathUsage_3205315A1969.md) | Set flight path usage from point A to B |
| Public method Static member | [SetPoi(XmlFlightNode)](FlightPaths/Methods/SetPoi_8BC82A056295.md) | Set POI for flight path action |
| Public method Static member | [ShouldTakeFlightpath(WoWPoint, WoWPoint, float)](FlightPaths/Methods/ShouldTakeFlightpath_32EB60A99B41.md) | Check if flight path would be faster than running |
| Public method Static member | [TakeFlightPath](FlightPaths/Methods/TakeFlightPath_53FB24B84327.md) | Take flight path if possible |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic Namespace](../../../namespaces/Styx/Logic.md)
