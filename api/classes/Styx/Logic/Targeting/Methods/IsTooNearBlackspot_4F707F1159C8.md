# Targeting.IsTooNearBlackspot Method

Checks if a point is within any blackspot. HB 4.3.4 compatible - used by Quest Behaviors.

## Namespace
[Styx.Logic](../../../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool IsTooNearBlackspot(IEnumerable<Blackspot> blackspots, WoWPoint point)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| blackspots | IEnumerable<Blackspot> | Collection of blackspots to check. |
| point | [WoWPoint](../../Pathing/WoWPoint.md) | The point to check. |

## Return Value

Type: bool
True if the point is within any blackspot.

## See Also
[Targeting Class](../../Targeting.md)
[Styx.Logic Namespace](../../../../../namespaces/Styx/Logic.md)
