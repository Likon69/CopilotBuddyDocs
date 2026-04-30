# LootRoll Class

Handles loot roll events for group loot in dungeons/raids.

## Namespace
[Styx.Logic.Inventory](../../../../namespaces/Styx/Logic/Inventory.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class LootRoll
```

The LootRoll type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public delegate | [LootRoll.LootRollEventDelegate](LootRoll/LootRollEventDelegate.md) | Delegate for loot roll events. |
| Public class | [LootRoll.LootRollItem](LootRoll/LootRollItem.md) | Wrapper class for interacting with loot roll info. |
| Public struct | [LootRoll.LootRollItemInfo](LootRoll/LootRollItemInfo.md) | Information about a loot roll item. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event Static member | [OnLootRoll](LootRoll/Events/OnLootRoll_9CA8870500CD.md) | Event fired when a loot roll starts. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [RollDisenchant(uint)](LootRoll/Methods/RollDisenchant_8FA971943187.md) | Rolls disenchant on an item. |
| Public method Static member | [RollGreed(uint)](LootRoll/Methods/RollGreed_CC3C961C15C9.md) | Rolls greed on an item. |
| Public method Static member | [RollNeed(uint)](LootRoll/Methods/RollNeed_D3B89CCE6B3E.md) | Rolls need on an item. |
| Public method Static member | [RollPass(uint)](LootRoll/Methods/RollPass_B7FCC7D68235.md) | Passes on an item. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Inventory Namespace](../../../../namespaces/Styx/Logic/Inventory.md)
