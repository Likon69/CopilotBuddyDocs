# ForcedUseItem.ForcedUseItem Constructor

Initializes a new instance of the ForcedUseItem class.

## Namespace
[Bots.Quest.QuestOrder](../../../../../../namespaces/Bots/Quest/QuestOrder.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public ForcedUseItem(Func<WoWItem> itemRetriever, Func<WoWObject> targetRetriever, bool forceUse, uint questId, WoWPoint location)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| itemRetriever | Func<WoWItem> | The item retriever. |
| targetRetriever | Func<WoWObject> | The target retriever. |
| forceUse | bool | The force use. |
| questId | uint | The quest id. |
| location | [WoWPoint](../../../../../Styx/Logic/Pathing/WoWPoint.md) | The location. |

## See Also
[ForcedUseItem Class](../../ForcedUseItem.md)
[Bots.Quest.QuestOrder Namespace](../../../../../../namespaces/Bots/Quest/QuestOrder.md)
