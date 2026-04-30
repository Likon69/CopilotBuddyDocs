# LocalPlayer.GetBagGuidAtIndex Method

Gets the GUID of the bag at the specified index (0-10). Reads from global bag GUID array at 12727616 + 8 * index. HB 3.3.5a: ObjectManager.Wow.Read<ulong>(12727616U + 8U * index)

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public ulong GetBagGuidAtIndex(uint index)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | uint | The index. |

## Return Value

Type: ulong
The result of the operation.

## See Also
[LocalPlayer Class](../../LocalPlayer.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
