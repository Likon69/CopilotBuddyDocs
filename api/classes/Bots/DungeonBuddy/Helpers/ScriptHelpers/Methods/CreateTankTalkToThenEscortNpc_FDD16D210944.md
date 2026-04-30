# ScriptHelpers.CreateTankTalkToThenEscortNpc Method

Creates the tank talk to then escort npc.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateTankTalkToThenEscortNpc(CanRunDecoratorDelegate canRun, Func<WoWUnit> npc, float range, bool waitToTalk, int gossipIndex, Func<WoWPoint> waitLocation)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| canRun | [CanRunDecoratorDelegate](../../../../../TreeSharp/CanRunDecoratorDelegate.md) | The can run. |
| npc | Func<WoWUnit> | The npc. |
| range | float | The range. |
| waitToTalk | bool | The wait to talk. |
| gossipIndex | int | The gossip index. |
| waitLocation | Func<WoWPoint> | The wait location. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
