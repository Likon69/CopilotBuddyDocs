# UseItemNode.UseItemNode Constructor

Initializes a new instance of the UseItemNode class.

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public UseItemNode(Func<WoWItem> itemRetriever, Func<WoWObject> targetRetriever, UseItemTargetType targetType, bool forceUse, uint questId, WoWPoint location)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| itemRetriever | Func<WoWItem> | The item retriever. |
| targetRetriever | Func<WoWObject> | The target retriever. |
| targetType | [UseItemTargetType](../UseItemTargetType.md) | The target type. |
| forceUse | bool | The force use. |
| questId | uint | The quest id. |
| location | [WoWPoint](../../../../Pathing/WoWPoint.md) | The location. |

## See Also
[UseItemNode Class](../../UseItemNode.md)
[Styx.Logic.Profiles.Quest Namespace](../../../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
