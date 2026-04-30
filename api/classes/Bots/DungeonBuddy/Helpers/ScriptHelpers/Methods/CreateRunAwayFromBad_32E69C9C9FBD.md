# ScriptHelpers.CreateRunAwayFromBad Method

Creates the run away from bad.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateRunAwayFromBad(CanRunDecoratorDelegate condition, WoWPoint centerPoint, float radius, float maxDistance, uint[] objectEntries)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| condition | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The condition. |
| centerPoint | [WoWPoint](../../../../../Styx/Logic/Pathing/WoWPoint.md) | The center point. |
| radius | float | The radius. |
| maxDistance | float | The max distance. |
| objectEntries | uint[] | The object entries. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
