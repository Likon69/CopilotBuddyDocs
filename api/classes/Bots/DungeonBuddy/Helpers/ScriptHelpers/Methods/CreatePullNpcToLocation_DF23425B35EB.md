# ScriptHelpers.CreatePullNpcToLocation Method

Crée un behavior pour pull trash vers une position

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreatePullNpcToLocation(CanRunDecoratorDelegate condition, Func<WoWUnit> npcSelector, Func<WoWPoint> tankLocation, float pullRange)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| condition | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The condition. |
| npcSelector | Func<WoWUnit> | The npc selector. |
| tankLocation | Func<WoWPoint> | The tank location. |
| pullRange | float | The pull range. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
