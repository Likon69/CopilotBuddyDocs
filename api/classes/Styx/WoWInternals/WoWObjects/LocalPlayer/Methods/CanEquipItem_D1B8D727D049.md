# LocalPlayer.CanEquipItem Method

Checks if the player can equip an item (with reason output). Calls native CGPlayer_C::CanUseItem at 0x6DC3F0 (7193584)

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool CanEquipItem(ItemInfo itemInfo, out GameError reason)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| itemInfo | [ItemInfo](../../ItemInfo.md) | The item info. |
| reason | [GameError](../../../../GameError.md) | The reason. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[LocalPlayer Class](../../LocalPlayer.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
