# SpellManager.CanBuff Method

Check if we can cast a buff (CanCast + target doesn't already have aura).

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool CanBuff(string spellName, WoWUnit target, bool checkRange)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| spellName | string | The spell name. |
| target | [WoWUnit](../../../../WoWInternals/WoWObjects/WoWUnit.md) | The target. |
| checkRange | bool | The check range. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[SpellManager Class](../../SpellManager.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
