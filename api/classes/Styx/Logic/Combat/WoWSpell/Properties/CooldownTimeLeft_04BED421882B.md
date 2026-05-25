# WoWSpell.CooldownTimeLeft Property

Gets the remaining cooldown time for this spell. WotLK 3.3.5a: GetSpellCooldown() requires the spell name in the CLIENT'S LANGUAGE. Passing the English name fails on non-English clients (e.g. "Blood Fury" on a Russian client where the spell is "\208\175\209\128\208\190\209\129\209\130\209\140 \208\186\209\128\208\190\208\178\208\184"). Fix: use GetSpellInfo(id) to get the localized name first — language-independent.

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public TimeSpan CooldownTimeLeft { get; }
```

## Property Value

Type: TimeSpan
The cooldown time left.

## See Also
[WoWSpell Class](../../WoWSpell.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
