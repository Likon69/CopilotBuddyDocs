# FlightPaths.SetFlightPathUsage Method

Set flight path usage from point A to B

## Namespace
[Styx.Logic](../../../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool SetFlightPathUsage(WoWPoint from, WoWPoint to, out WoWPoint startFp, out WoWPoint endFp)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| from | [WoWPoint](../../Pathing/WoWPoint.md) | The from. |
| to | [WoWPoint](../../Pathing/WoWPoint.md) | The to. |
| startFp | [WoWPoint](../../Pathing/WoWPoint.md) | The start fp. |
| endFp | [WoWPoint](../../Pathing/WoWPoint.md) | The end fp. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[FlightPaths Class](../../FlightPaths.md)
[Styx.Logic Namespace](../../../../../namespaces/Styx/Logic.md)
