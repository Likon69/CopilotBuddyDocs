# DungeonManager.SetDungeon Method

Active le script de donjon approprié. HB 4.3.4: utilise LfgManager.CurrentLfgDungeonId quand on est en groupe LFG, sinon GetLfgDungeonIdFromMapId pour faire la correspondance MapId → LFG DungeonId.

## Namespace
[Bots.DungeonBuddy](../../../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static void SetDungeon(uint mapId)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | The map id. |

## See Also
[DungeonManager Class](../../DungeonManager.md)
[Bots.DungeonBuddy Namespace](../../../../../namespaces/Bots/DungeonBuddy.md)
