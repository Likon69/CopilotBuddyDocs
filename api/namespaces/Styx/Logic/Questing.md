# Styx.Logic.Questing Namespace

Contains questing support types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [CustomForcedBehavior](../../../classes/Styx/Logic/Questing/CustomForcedBehavior.md) | Represents a custom forced behavior. |
| Public class | [CustomForcedBehavior.ConfigMemento](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/ConfigMemento.md) | Represents a config memento. |
| Public class | [CustomForcedBehavior.ConstrainAs](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/ConstrainAs.md) | Represents a constrain as. |
| Public class | [CustomForcedBehavior.ConstrainTo](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/ConstrainTo.md) | Represents a constrain to. |
| Public class | [CustomForcedBehavior.ConstrainTo.Anything<T>](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/ConstrainTo/Anything_1.md) | Represents an anything. |
| Public class | [CustomForcedBehavior.ConstrainTo.Domain<T>](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/ConstrainTo/Domain_1.md) | Represents a domain. |
| Public class | [CustomForcedBehavior.ConstrainTo.NonEmptyString<T>](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/ConstrainTo/NonEmptyString_1.md) | Represents a non empty string. |
| Public class | [CustomForcedBehavior.ConstrainTo.NonEmptyWoWPoint<T>](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/ConstrainTo/NonEmptyWoWPoint_1.md) | Represents a non empty wow point. |
| Public class | [CustomForcedBehavior.ConstrainTo.QuestId<T>](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/ConstrainTo/QuestId_1.md) | Represents a quest id. |
| Public class | [CustomForcedBehavior.ConstrainTo.SpecificValues<T>](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/ConstrainTo/SpecificValues_1.md) | Represents a specific values. |
| Public class | [CustomForcedBehavior.IConstraintChecker<T>](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/IConstraintChecker_1.md) | Represents an i constraint checker. |
| Public class | [PlayerQuest](../../../classes/Styx/Logic/Questing/PlayerQuest.md) | Represents a quest in the player's quest log. |
| Public class | [Quest](../../../classes/Styx/Logic/Questing/Quest.md) | Represents a quest. |
| Public class | [QuestLog](../../../classes/Styx/Logic/Questing/QuestLog.md) | Provides access to the player's quest log. Matches HB 4.3.4 API while using Lua for completed quests (more reliable than memory reads). |
| Public class | [Questing](../../../classes/Styx/Logic/Questing/Questing.md) | Provides quest-related functionality including completed quest tracking. |

## Structures

| | Name | Description |
| --- | --- | --- |
| Public struct | [Quest.QuestObjective](../../../classes/Styx/Logic/Questing/Quest/QuestObjective.md) | Represents a single quest objective. |
| Public struct | [QuestDescriptorData](../../../classes/Styx/Logic/Questing/QuestDescriptorData.md) | Quest data structure read from player unit descriptor fields. Contains quest identification, state flags, objective progress counters, and optional failure timer for timed quests. Size: 20 bytes (5 x uint32 equivalent) |
| Public struct | [QuestLogEntry](../../../classes/Styx/Logic/Questing/QuestLogEntry.md) | Quest log entry structure (20 bytes). Layout: Id(4) + State(4) + ObjectiveRequiredCounts(8) + Time(4) = 20 bytes. Read from address 12728252 (0xC23F3C). WoW 3.3.5a build 12340. |
| Public struct | [QuestStepLocation](../../../classes/Styx/Logic/Questing/QuestStepLocation.md) | Location data for a quest step or objective. |
| Public struct | [Vector2i](../../../classes/Styx/Logic/Questing/Vector2i.md) | Integer 2D vector for quest area coordinates. NOTE: This struct exists in HB 3.3.5a for grid-based quest step coordinates. While not in HB 4.3.4, it's used by WoWQuestStep/QuestStepLocation for integer tile coordinates from quest cache data. |
| Public struct | [WoWDescriptorQuest](../../../classes/Styx/Logic/Questing/WoWDescriptorQuest.md) | Represents a quest descriptor from WoW memory. |
| Public struct | [WoWQuestCompletionInfo](../../../classes/Styx/Logic/Questing/WoWQuestCompletionInfo.md) | Quest completion info structure (48 bytes). Read from address 12729088 (0xC24380) - array of 25 entries. |
| Public struct | [WoWQuestCurrentStep](../../../classes/Styx/Logic/Questing/WoWQuestCurrentStep.md) | Current step information for a quest objective. |
| Public struct | [WoWQuestStep](../../../classes/Styx/Logic/Questing/WoWQuestStep.md) | Quest step structure (52 bytes). Contains POI and area information for quest objectives. |
| Public struct | [WoWQuestStepsCollection](../../../classes/Styx/Logic/Questing/WoWQuestStepsCollection.md) | Collection of quest steps (12 bytes). |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [CustomForcedBehavior.QuestCompleteRequirement](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/QuestCompleteRequirement.md) | Represents values for Quest Complete Requirement. |
| Public enumeration | [CustomForcedBehavior.QuestInLogRequirement](../../../classes/Styx/Logic/Questing/CustomForcedBehavior/QuestInLogRequirement.md) | Represents values for Quest In Log Requirement. |
| Public enumeration | [Quest.QuestObjectiveType](../../../classes/Styx/Logic/Questing/Quest/QuestObjectiveType.md) | Types of quest objectives. |
| Public enumeration | [QuestLogEntry.StateFlag](../../../classes/Styx/Logic/Questing/QuestLogEntry/StateFlag.md) | Represents values for State Flag. |
| Public enumeration | [WoWDescriptorQuestFlags](../../../classes/Styx/Logic/Questing/WoWDescriptorQuestFlags.md) | Quest flags stored in player descriptor. |
| Public enumeration | [WoWQuestState](../../../classes/Styx/Logic/Questing/WoWQuestState.md) | Quest completion state. |

## See Also
[Namespace Index](../../../index.md)
