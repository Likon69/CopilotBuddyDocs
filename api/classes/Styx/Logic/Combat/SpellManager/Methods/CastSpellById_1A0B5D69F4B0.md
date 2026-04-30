# SpellManager.CastSpellById Method

Casts a spell by ID on a specific target via native Spell_C::CastSpell. HB 4.3.4: LegacySpellManager.smethod_1(spellId, 0, targetGuid, 0) Pushes 8 args onto stack (cdecl, 0x20 cleanup).

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static void CastSpellById(int spellId, ulong targetGuid)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| spellId | int | The spell id. |
| targetGuid | ulong | The target guid. |

## See Also
[SpellManager Class](../../SpellManager.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
