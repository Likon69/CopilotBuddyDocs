# BossManager.CurrentBoss Property

HB 4.3.4 parity: returns the first Boss object that is not yet dead, ordered by registration order (kill order from [EncounterHandler] attributes). Does NOT require the boss to be in ObjectManager range — using ObjectManager here would return null when bosses are out of draw distance at the dungeon entrance, causing IsComplete = true and premature 'dungeon complete'. Matches HB smethod_9: IsAlive check + Optional/KillOptionalBosses guard. (Faction guard omitted — inner Boss has no Faction field; all registered bosses default to Both.)

## Namespace
[Bots.DungeonBuddy](../../../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Boss CurrentBoss { get; }
```

## Property Value

Type: [Boss](../Boss.md)
The current boss.

## See Also
[BossManager Class](../../BossManager.md)
[Bots.DungeonBuddy Namespace](../../../../../namespaces/Bots/DungeonBuddy.md)
