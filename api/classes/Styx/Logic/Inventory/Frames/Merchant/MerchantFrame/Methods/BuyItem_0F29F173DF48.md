# MerchantFrame.BuyItem Method

FEAT-32: Buys an item by name from the merchant. Iterates through merchant items, finds by name, buys the requested amount. Returns true if the item was found and purchased.

## Namespace
[Styx.Logic.Inventory.Frames.Merchant](../../../../../../../../namespaces/Styx/Logic/Inventory/Frames/Merchant.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool BuyItem(string name, int amount)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | string | The name. |
| amount | int | The amount. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[MerchantFrame Class](../../MerchantFrame.md)
[Styx.Logic.Inventory.Frames.Merchant Namespace](../../../../../../../../namespaces/Styx/Logic/Inventory/Frames/Merchant.md)
