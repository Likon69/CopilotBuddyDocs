# ScriptHelpers.CreateTankTalkToThenEscortNpc Method

Creates the tank talk to then escort npc.

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateTankTalkToThenEscortNpc(int escortNpcId, int gossipIndex, WoWPoint escortNpcLocation, WoWPoint endLocation, float followDistance, Func<bool> isDoneCondition)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| escortNpcId | int | The escort npc id. |
| gossipIndex | int | The gossip index. |
| escortNpcLocation | [WoWPoint](../../../../../Styx/Logic/Pathing/WoWPoint.md) | The escort npc location. |
| endLocation | [WoWPoint](../../../../../Styx/Logic/Pathing/WoWPoint.md) | The end location. |
| followDistance | float | The follow distance. |
| isDoneCondition | Func<bool> | The is done condition. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
