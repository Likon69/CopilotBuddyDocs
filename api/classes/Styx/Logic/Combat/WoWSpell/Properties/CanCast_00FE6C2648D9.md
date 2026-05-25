# WoWSpell.CanCast Property

Returns true if the spell is currently usable (power, stance, equipped items, etc.) AND not on cooldown. HB 4.3.4 WoWSpell.cs: delegates to IsUsableSpell Lua. IsUsableSpell in WoW 3.3.5a does NOT check cooldowns — we pre-check Cooldown (ASM-based, language-independent) so that instant off-GCD spells like Blood Fury are never reported as castable while on their 2-minute cooldown.

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool CanCast { get; }
```

## Property Value

Type: bool
true if can cast; otherwise, false.

## See Also
[WoWSpell Class](../../WoWSpell.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
