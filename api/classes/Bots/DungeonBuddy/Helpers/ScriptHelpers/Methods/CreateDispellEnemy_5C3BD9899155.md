# ScriptHelpers.CreateDispellEnemy Method

Dispel un buff enemy

## Namespace
[Bots.DungeonBuddy.Helpers](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Composite CreateDispellEnemy(string auraName, EnemyDispellType dispellType, Func<WoWUnit> targetSelector)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| auraName | string | The aura name. |
| dispellType | [EnemyDispellType](../EnemyDispellType.md) | The dispell type. |
| targetSelector | Func<WoWUnit> | The target selector. |

## Return Value

Type: [Composite](../../../../../TreeSharp/Composite.md)
The result of the operation.

## See Also
[ScriptHelpers Class](../../ScriptHelpers.md)
[Bots.DungeonBuddy.Helpers Namespace](../../../../../../namespaces/Bots/DungeonBuddy/Helpers.md)
