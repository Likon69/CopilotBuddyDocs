# DungeonManager.GetEntranceForDungeon Method

Retourne la position d'entrée d'un donjon depuis son script, SANS activer ce script. Utilisé par SoloFarm pour naviguer vers l'entrée avant d'entrer dans l'instance. Évite d'appeler SetDungeonById (qui déclenche Attach/BossManager/Profile) hors instance.

## Namespace
[Bots.DungeonBuddy](../../../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static WoWPoint GetEntranceForDungeon(uint dungeonId)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| dungeonId | uint | The dungeon id. |

## Return Value

Type: [WoWPoint](../../../../Styx/Logic/Pathing/WoWPoint.md)
The result of the operation.

## See Also
[DungeonManager Class](../../DungeonManager.md)
[Bots.DungeonBuddy Namespace](../../../../../namespaces/Bots/DungeonBuddy.md)
