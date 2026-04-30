# FlightPaths.GetFullTravelTime Method

Get total travel time including ground paths to/from flight points

## Namespace
[Styx.Logic](../../../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static TimeSpan GetFullTravelTime(WoWPoint start, WoWPoint end, WoWPoint flightPathStart, WoWPoint flightPathEnd, float travelSpeed)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| start | [WoWPoint](../../Pathing/WoWPoint.md) | The start. |
| end | [WoWPoint](../../Pathing/WoWPoint.md) | The end. |
| flightPathStart | [WoWPoint](../../Pathing/WoWPoint.md) | The flight path start. |
| flightPathEnd | [WoWPoint](../../Pathing/WoWPoint.md) | The flight path end. |
| travelSpeed | float | The travel speed. |

## Return Value

Type: TimeSpan
The result of the operation.

## See Also
[FlightPaths Class](../../FlightPaths.md)
[Styx.Logic Namespace](../../../../../namespaces/Styx/Logic.md)
