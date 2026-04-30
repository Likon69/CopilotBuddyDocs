# ScriptHelpers.CreateSpreadOutLogic Method

Creates the spread out logic.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateSpreadOutLogic(CanRunDecoratorDelegate canRun, Func<WoWPoint> centerPointSelector, int distanceToSpread, float maxDistanceFromCenterPoint)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| canRun | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The can run. |
| centerPointSelector | Func<WoWPoint> | The center point selector. |
| distanceToSpread | int | The distance to spread. |
| maxDistanceFromCenterPoint | float | The max distance from center point. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
