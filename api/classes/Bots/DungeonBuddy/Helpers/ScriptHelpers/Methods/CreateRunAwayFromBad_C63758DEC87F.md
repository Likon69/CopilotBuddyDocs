# ScriptHelpers.CreateRunAwayFromBad Method

Overload avec WoWPoint direct (pas Func) — Azjol-Nerub, Deadmines. HB 4.3.4: convertit WoWPoint en lambda pour les scripts qui passent le point directement.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateRunAwayFromBad(CanRunDecoratorDelegate condition, WoWPoint centerPoint, float radius, float maxDistance, uint objectEntry)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| condition | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The condition. |
| centerPoint | [WoWPoint](../../../../../Styx/Logic/Pathing/WoWPoint.md) | The center point. |
| radius | float | The radius. |
| maxDistance | float | The max distance. |
| objectEntry | uint | The object entry. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
