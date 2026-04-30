# WoWGameObject.SubObj Property

Sub-object associated with this GameObject (chair, door, bobber, etc.). HB-compatible API: returns a `WoWSubObject` so callers can cast to specific sub-types (e.g. `WoWFishingBobber`). When a real sub-object pointer is unavailable we return an inert `WoWSubObject` with a zero base address to preserve runtime safety.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public WoWSubObject SubObj { get; }
```

## Property Value

Type: [WoWSubObject](../../WoWSubObject.md)
The sub obj.

## See Also
[WoWGameObject Class](../../WoWGameObject.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
