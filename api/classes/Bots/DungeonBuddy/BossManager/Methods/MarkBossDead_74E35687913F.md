# BossManager.MarkBossDead Method

Marque un boss comme tué et fire l'événement OnBossKill. Also syncs Profile.Boss.MarkAsDead() so PathBreadCrumbs advances to the next boss.

## Namespace
[Bots.DungeonBuddy](../../../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static void MarkBossDead(uint entryId)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| entryId | uint | The entry id. |

## See Also
[BossManager Class](../../BossManager.md)
[Bots.DungeonBuddy Namespace](../../../../../namespaces/Bots/DungeonBuddy.md)
