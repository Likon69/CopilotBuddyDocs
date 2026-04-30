# WoWSpell.SpellRangeId Property

Gets the spell range ID for combat routine range checks. Uses Lua-based MinRange/MaxRange which are reliable and match what Singular expects: 1 = Self Only (max=0), 2 = Melee (max≤5), 3+ = Ranged. Note: DBC rangeIndex is available via RangeIndex property for DBC lookups.

## Namespace
[Styx.Logic.Combat](../../../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public uint SpellRangeId { get; }
```

## Property Value

Type: uint
The spell range id.

## See Also
[WoWSpell Class](../../WoWSpell.md)
[Styx.Logic.Combat Namespace](../../../../../../namespaces/Styx/Logic/Combat.md)
