# LocalPlayer.GetEstimatedRepairCost Method

HB 4.3.4: Gets estimated total repair cost. HB 4.3.4 iterates CarriedItems and reads DurabilityCosts[itemLevel].Multiplier[subClassId] from ClientDb. CB does not yet have ClientDb, so we fall back to Lua GetRepairAllCost() which only returns a valid value when at a repair merchant. When ClientDb is implemented, replace with the item-iteration approach.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public WoWPrice GetEstimatedRepairCost()
```

## Return Value

Type: [WoWPrice](../../../../Logic/Inventory/WoWPrice.md)
The result of the operation.

## See Also
[LocalPlayer Class](../../LocalPlayer.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
