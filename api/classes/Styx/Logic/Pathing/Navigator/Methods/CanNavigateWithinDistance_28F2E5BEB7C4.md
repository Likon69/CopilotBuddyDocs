# Navigator.CanNavigateWithinDistance Method

Mirrors HB 4.3.4 Class81.method_10: returns true only if the actual nav path from to is complete (not partial) and its total length in yards is ≤ . Used by DungeonTargeting to reject through-wall mobs whose straight-line distance is within range but whose nav path winds far around the dungeon geometry.

## Namespace
[Styx.Logic.Pathing](../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool CanNavigateWithinDistance(WoWPoint start, WoWPoint destination, float maxPathDistance)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| start | [WoWPoint](../../WoWPoint.md) | The start. |
| destination | [WoWPoint](../../WoWPoint.md) | The destination. |
| maxPathDistance | float | The max path distance. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[Navigator Class](../../Navigator.md)
[Styx.Logic.Pathing Namespace](../../../../../../namespaces/Styx/Logic/Pathing.md)
