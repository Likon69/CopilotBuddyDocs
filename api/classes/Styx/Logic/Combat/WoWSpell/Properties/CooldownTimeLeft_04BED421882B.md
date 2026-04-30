# WoWSpell.CooldownTimeLeft Property

Gets the remaining cooldown time for this spell. HB 4.3.4 pattern: uses Lua GetSpellCooldown which correctly includes GCD. The memory-based approach had timing issues.

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
