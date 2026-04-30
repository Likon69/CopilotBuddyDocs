# SpellManager.CanCast Method

HB 4.3.4 SpellManager.cs line 166-222: CanCast with accountForLagTolerance. Ported exactly from the decompiled source.

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool CanCast(WoWSpell spell, WoWUnit target, bool checkRange, bool checkMovement, bool accountForLagTolerance)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| spell | [WoWSpell](../../WoWSpell.md) | The spell. |
| target | [WoWUnit](../../../../WoWInternals/WoWObjects/WoWUnit.md) | The target. |
| checkRange | bool | The check range. |
| checkMovement | bool | The check movement. |
| accountForLagTolerance | bool | The account for lag tolerance. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[SpellManager Class](../../SpellManager.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
