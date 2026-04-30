# SpellManager.CanCast Method

HB 4.3.4 SpellManager.cs line 166: CanCast with full validation. Ported exactly from HB 4.3.4 — uses spell.CooldownTimeLeft with lag tolerance, checks IsCasting, movement, range, and power.

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool CanCast(string spellName, WoWUnit target, bool checkRange, bool checkMovement)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| spellName | string | The spell name. |
| target | [WoWUnit](../../../../WoWInternals/WoWObjects/WoWUnit.md) | The target. |
| checkRange | bool | The check range. |
| checkMovement | bool | The check movement. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[SpellManager Class](../../SpellManager.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
