# LocalPlayer.IsInInstance Property

Whether the player is in an instanced zone. Reads Map.dbc field 2 (MapType) via WoWDb — field != 0 means Instance/Raid/BG/Arena. Matches HB 3.3.5a LocalPlayer.IsInInstance exactly.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool IsInInstance { get; }
```

## Property Value

Type: bool
true if is in instance; otherwise, false.

## See Also
[LocalPlayer Class](../../LocalPlayer.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
