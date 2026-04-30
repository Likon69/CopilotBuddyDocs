# BossManager Class

Gère les boss du donjon actuel. Track les boss tués et le boss actuel à target.

## Namespace
[Bots.DungeonBuddy](../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class BossManager
```

The BossManager type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public class | [BossManager.Boss](BossManager/Boss.md) | Represents a dungeon boss definition. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field Static member | [BossTimer](BossManager/Fields/BossTimer_4846B0DCB124.md) | Represents the boss timer. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [BossEncounters](BossManager/Properties/BossEncounters_F2894262432B.md) | Gets the boss encounters. |
| Public property Static member | [Bosses](BossManager/Properties/Bosses_372E6667C6BB.md) | Liste de tous les boss du donjon |
| Public property Static member | [CurrentBoss](BossManager/Properties/CurrentBoss_8D1170C3B259.md) | HB 4.3.4 parity: returns the first Boss object that is not yet dead, ordered by registration order (kill order from [EncounterHandler] attributes). Does NOT require the boss to be in ObjectManager range — using ObjectManager here would return null when bosses are out of draw distance at the dungeon entrance, causing IsComplete = true and premature 'dungeon complete'. Matches HB smethod_9: IsAlive check + Optional/KillOptionalBosses guard. (Faction guard omitted — inner Boss has no Faction field; all registered bosses default to Both.) |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event Static member | [OnBossKill](BossManager/Events/OnBossKill_05F84D3837F5.md) | Fired after a boss is marked as dead. Payload is the killed boss. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [AreAllRequiredBossesDead](BossManager/Methods/AreAllRequiredBossesDead_98DFA53EC9C7.md) | Vérifie si tous les boss obligatoires sont morts |
| Public method Static member | [CreateCheckForDeadBossBehavior](BossManager/Methods/CreateCheckForDeadBossBehavior_F53FE6B9B6ED.md) | HB 4.3.4 parity: poll one dead boss candidate per tick and mark it dead. Used as a dedicated root branch (DungeonBot.method_12 array[2]). |
| Public method Static member | [Initialize(Dungeon)](BossManager/Methods/Initialize_60518D9417CA.md) | Initialise les boss pour le donjon actuel. Remet à zéro les boss tués et re-peuple la liste depuis les attributs [EncounterHandler]. |
| Public method Static member | [MarkBossDead(uint)](BossManager/Methods/MarkBossDead_74E35687913F.md) | Marque un boss comme tué et fire l'événement OnBossKill. Also syncs Profile.Boss.MarkAsDead() so PathBreadCrumbs advances to the next boss. |
| Public method Static member | [MarkBossDead(string)](BossManager/Methods/MarkBossDead_96DACBB11247.md) | Marque un boss comme tué (par nom, utilisé par l'UI) |
| Public method Static member | [RegisterBoss(uint, string, bool)](BossManager/Methods/RegisterBoss_9BF9B5FAADF1.md) | Register un boss (appelé par DungeonManager lors du chargement des scripts) |
| Public method Static member | [Reset](BossManager/Methods/Reset_36C4DABF5785.md) | Reset pour nouveau donjon |
| Public method Static member | [ResetBoss(string)](BossManager/Methods/ResetBoss_43E24AE2CBEB.md) | Remet un boss à vivant (par nom, utilisé par l'UI) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy Namespace](../../../namespaces/Bots/DungeonBuddy.md)
