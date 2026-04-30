# SpellManager.BuffRandom Method

Buff a random castable spell from the list on a target (skips if aura present).

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool BuffRandom(IEnumerable<WoWSpell> spellList, WoWUnit target, bool checkRange)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| spellList | IEnumerable<WoWSpell> | The spell list. |
| target | [WoWUnit](../../../../WoWInternals/WoWObjects/WoWUnit.md) | The target. |
| checkRange | bool | The check range. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[SpellManager Class](../../SpellManager.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
