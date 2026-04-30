# WoWItem.CooldownTimeLeft Property

FEAT-43: Gets the remaining cooldown as a TimeSpan. Uses Lua GetItemCooldown which returns (startTime, duration, isEnabled).

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

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
[WoWItem Class](../../WoWItem.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
