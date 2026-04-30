# CustomForcedBehavior.GetXYZAttributeAsWoWPoint Method

Gets the xyz attribute as wow point.

## Namespace
[Styx.Logic.Questing](../../../../../../namespaces/Styx/Logic/Questing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool GetXYZAttributeAsWoWPoint(string attributeNameX, string attributeNameY, string attributeNameZ, bool isAttributeRequired, WoWPoint defaultValue, out WoWPoint returnedValue)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| attributeNameX | string | The attribute name x. |
| attributeNameY | string | The attribute name y. |
| attributeNameZ | string | The attribute name z. |
| isAttributeRequired | bool | The is attribute required. |
| defaultValue | [WoWPoint](../../../Pathing/WoWPoint.md) | The default value. |
| returnedValue | [WoWPoint](../../../Pathing/WoWPoint.md) | The returned value. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[CustomForcedBehavior Class](../../CustomForcedBehavior.md)
[Styx.Logic.Questing Namespace](../../../../../../namespaces/Styx/Logic/Questing.md)
