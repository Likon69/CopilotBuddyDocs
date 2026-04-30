# Navigator.PathDistance Method

Computes the path distance between two points using TripperNavigator. Returns null if no path could be generated or if the calculated distance exceeds . This helper backs and was removed earlier during refactoring; it has now been restored.

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
