# WoWUnit.CurrentCastTimeLeft Property

Gets the time remaining on the current cast via Lua UnitCastingInfo. BUG-25: Works for player/target/focus via Lua unitId mapping. Returns TimeSpan.Zero for units without a known unitId.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public virtual TimeSpan CurrentCastTimeLeft { get; }
```

## Property Value

Type: TimeSpan
The current cast time left.

## See Also
[WoWUnit Class](../../WoWUnit.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
