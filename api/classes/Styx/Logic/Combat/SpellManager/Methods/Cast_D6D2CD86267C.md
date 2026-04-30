# SpellManager.Cast Method

HB 4.3.4 line 333: Cast spell on target via GUID-based CastSpellById. No CanCast guard — callers check CanCast separately before calling Cast.

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool Cast(WoWSpell spell, WoWUnit target)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| spell | [WoWSpell](../../WoWSpell.md) | The spell. |
| target | [WoWUnit](../../../../WoWInternals/WoWObjects/WoWUnit.md) | The target. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[SpellManager Class](../../SpellManager.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
