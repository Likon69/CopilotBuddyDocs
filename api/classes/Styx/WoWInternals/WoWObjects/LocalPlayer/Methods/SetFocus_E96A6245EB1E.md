# LocalPlayer.SetFocus Method

Sets the focus target by GUID. Returns true on success. HB 4.3.4 pattern: writes GUID directly to the focus address in memory.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool SetFocus(ulong guid)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| guid | ulong | The guid. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[LocalPlayer Class](../../LocalPlayer.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
