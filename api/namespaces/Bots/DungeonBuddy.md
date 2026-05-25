# Bots.DungeonBuddy Namespace

Contains dungeon bot types and supporting runtime logic.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [BossManager](../../classes/Bots/DungeonBuddy/BossManager.md) | Gère les boss du donjon actuel. Track les boss tués et le boss actuel à target. |
| Public class | [BossManager.Boss](../../classes/Bots/DungeonBuddy/BossManager/Boss.md) | Represents a dungeon boss definition. |
| Public class | [Dungeon](../../classes/Bots/DungeonBuddy/Dungeon.md) | Classe de base pour tous les scripts de donjon. Chaque donjon hérite de cette classe. |
| Public class | [DungeonBuddy](../../classes/Bots/DungeonBuddy/DungeonBuddy.md) | DungeonBuddy - BotBase pour Dungeon Finder automatique WotLK 3.3.5a (patch 3.3 — Dungeon Finder ajouté) State machine: NotInLfg → SetRole + Queue → InQueue → Proposal → Accept → InDungeon InDungeon → Combat/Follow → DungeonComplete → TeleportOut → Requeue LFG state détecté via GetLFGMode() (API canonique WotLK 3.3). Events LFG via Lua.Events.AttachEvent (confirmé dans CopilotBuddy). |
| Public class | [DungeonBuddySettings](../../classes/Bots/DungeonBuddy/DungeonBuddySettings.md) | Represents settings for dungeon buddy. |
| Public class | [DungeonManager](../../classes/Bots/DungeonBuddy/DungeonManager.md) | Charge et gère les scripts de donjons. Scripts dynamiques depuis Dungeon Scripts\ + types compilés dans l'assembly. |
| Public class | [DynamicBlackspot](../../classes/Bots/DungeonBuddy/DynamicBlackspot.md) | HB WoD DungeonBuddy dynamic blackspot: marks nearby navmesh polygons while a condition is active. |
| Public class | [DynamicBlackspotManager](../../classes/Bots/DungeonBuddy/DynamicBlackspotManager.md) | HB WoD DungeonBuddy dynamic blackspot manager. Restores polygon areas when blackspots expire. |
| Public class | [LfgManager](../../classes/Bots/DungeonBuddy/LfgManager.md) | Gère l'interface avec le Dungeon Finder (LFG). Compatible WotLK 3.3 - Dungeon Finder ajouté en patch 3.3. |

## See Also
[Namespace Index](../../index.md)
