# WoWPlayer.Coinage Property

BUG-16: Changed from int to uint to avoid overflow at high gold amounts. WotLK gold cap is ~214k gold = ~2.14 billion copper, fits uint but overflows int.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public uint Coinage { get; }
```

## Property Value

Type: uint
The coinage.

## See Also
[WoWPlayer Class](../../WoWPlayer.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
