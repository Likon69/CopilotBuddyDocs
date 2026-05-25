# Navigator.ComputeRawPath Method

Pathfinds from → to via TripperNavigator and returns the waypoints as WoWPoint[]. Lightweight wrapper: no tile pre-load, no blackspot sync. For avoidance use only.

## Namespace
[Styx.Logic.Pathing](../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static WoWPoint[] ComputeRawPath(WoWPoint from, WoWPoint to)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| from | [WoWPoint](../../WoWPoint.md) | The from. |
| to | [WoWPoint](../../WoWPoint.md) | The to. |

## Return Value

Type: [WoWPoint](../../WoWPoint.md)[]
The result of the operation.

## See Also
[Navigator Class](../../Navigator.md)
[Styx.Logic.Pathing Namespace](../../../../../../namespaces/Styx/Logic/Pathing.md)
