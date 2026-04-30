# Bots.Quest.QuestOrder Namespace

Contains quest order nodes and forced behavior types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [ForcedBehavior](../../../classes/Bots/Quest/QuestOrder/ForcedBehavior.md) | Base class for all forced quest behaviors. Forced behaviors are executed in order from the quest profile. |
| Public class | [ForcedCodeBehavior](../../../classes/Bots/Quest/QuestOrder/ForcedCodeBehavior.md) | Represents a forced code behavior step. |
| Public class | [ForcedGrindTo](../../../classes/Bots/Quest/QuestOrder/ForcedGrindTo.md) | Represents a forced grind to step. |
| Public class | [ForcedIf](../../../classes/Bots/Quest/QuestOrder/ForcedIf.md) | Represents a forced if step. |
| Public class | [ForcedMoveTo](../../../classes/Bots/Quest/QuestOrder/ForcedMoveTo.md) | Represents a forced move to step. |
| Public class | [ForcedNothing](../../../classes/Bots/Quest/QuestOrder/ForcedNothing.md) | A forced behavior that does nothing and immediately completes. Used for checkpoint nodes and other pass-through nodes. |
| Public class | [ForcedQuestObjective](../../../classes/Bots/Quest/QuestOrder/ForcedQuestObjective.md) | Represents a forced quest objective step. |
| Public class | [ForcedQuestPickUp](../../../classes/Bots/Quest/QuestOrder/ForcedQuestPickUp.md) | Represents a forced quest pick up step. |
| Public class | [ForcedQuestTurnIn](../../../classes/Bots/Quest/QuestOrder/ForcedQuestTurnIn.md) | Represents a forced quest turn in step. |
| Public class | [ForcedSingleton](../../../classes/Bots/Quest/QuestOrder/ForcedSingleton.md) | A forced behavior that executes a single action and completes immediately. Used for simple one-shot actions like setting grind area, vendors, etc. HB 4.3.4: Action runs in OnStart(), IsDone is always true, Branch is ActionAlwaysSucceed. This lets the while(IsDone) loop in ForcedBehaviorExecutor process singletons instantly without consuming a full tick. |
| Public class | [ForcedUseItem](../../../classes/Bots/Quest/QuestOrder/ForcedUseItem.md) | Represents a forced use item step. |
| Public class | [ForcedWhile](../../../classes/Bots/Quest/QuestOrder/ForcedWhile.md) | Represents a forced while step. |
| Public class | [QuestOrder](../../../classes/Bots/Quest/QuestOrder/QuestOrder.md) | Manages the quest order - the list of ordered nodes to execute. |

## See Also
[Namespace Index](../../../index.md)
