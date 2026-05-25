# Navigator.PathDistance Method

HB 6.2.3 Navigator.PathDistance — delegates to NavigationProvider.PathDistance. Falls back to raw Tripper path calculation when no provider is set.

## Namespace
[Styx.Logic.Pathing](../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static float? PathDistance(WoWPoint from, WoWPoint to, float maxDistance)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| from | [WoWPoint](../../WoWPoint.md) | The from. |
| to | [WoWPoint](../../WoWPoint.md) | The to. |
| maxDistance | float | The max distance. |

## Return Value

Type: float?
The result of the operation.

## See Also
[Navigator Class](../../Navigator.md)
[Styx.Logic.Pathing Namespace](../../../../../../namespaces/Styx/Logic/Pathing.md)
