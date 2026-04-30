# QuestManager.CreateQuestObjective Method

Creates the quest objective.

## Namespace
[Bots.Quest](../../../../../namespaces/Bots/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static QuestObjective CreateQuestObjective(QuestObjective questObjective, PlayerQuest quest, List<WoWQuestStep> poiSteps, List<QuestObjective> objectivePool)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| questObjective | [QuestObjective](../../../../Styx/Logic/Questing/Quest/QuestObjective.md) | The quest objective. |
| quest | [PlayerQuest](../../../../Styx/Logic/Questing/PlayerQuest.md) | The quest. |
| poiSteps | List<WoWQuestStep> | The poi steps. |
| objectivePool | List<QuestObjective> | The objective pool. |

## Return Value

Type: [QuestObjective](../../Objectives/QuestObjective.md)
The result of the operation.

## See Also
[QuestManager Class](../../QuestManager.md)
[Bots.Quest Namespace](../../../../../namespaces/Bots/Quest.md)
