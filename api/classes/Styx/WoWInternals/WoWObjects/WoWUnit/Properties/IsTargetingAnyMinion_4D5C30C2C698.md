# WoWUnit.IsTargetingAnyMinion Property

HB 4.3.4 compatible helper – returns true when any of the player's minions (pets) is currently targeting this unit. Used by Targeting filters to keep attackers on the list even if their Aggro flag hasn't flipped yet.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool IsTargetingAnyMinion { get; }
```

## Property Value

Type: bool
true if is targeting any minion; otherwise, false.

## See Also
[WoWUnit Class](../../WoWUnit.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
