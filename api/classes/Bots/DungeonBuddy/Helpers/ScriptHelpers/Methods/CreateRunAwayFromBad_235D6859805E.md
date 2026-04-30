# ScriptHelpers.CreateRunAwayFromBad Method

Overload avec Func center + range + radius + uint — HoL, Gundrak, DTK.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateRunAwayFromBad(CanRunDecoratorDelegate condition, Func<WoWPoint> centerSelector, float range, float radius, uint objectEntry)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| condition | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The condition. |
| centerSelector | Func<WoWPoint> | The center selector. |
| range | float | The range. |
| radius | float | The radius. |
| objectEntry | uint | The object entry. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
