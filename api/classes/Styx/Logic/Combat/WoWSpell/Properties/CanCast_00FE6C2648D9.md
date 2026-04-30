# WoWSpell.CanCast Property

Returns true if the spell is currently usable (power, stance, equipped items, etc.). HB 4.3.4 WoWSpell.cs: delegates to IsUsableSpell Lua. IsUsableSpell exists in the WoW 3.3.5a Lua API — returns (usable, nomana).

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
