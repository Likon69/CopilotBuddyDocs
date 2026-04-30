# QuestLog Class

Provides access to the player's quest log. Matches HB 4.3.4 API while using Lua for completed quests (more reliable than memory reads).

## Inheritance Hierarchy
System.Object
  Styx.Logic.Questing.QuestLog

## Namespace
[Styx.Logic.Questing](../../../../namespaces/Styx/Logic/Questing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class QuestLog
```

The QuestLog type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [QuestLog](QuestLog/Constructors/Constructor_ADDEF2F77E47.md) | Initializes a new instance of the QuestLog class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [QuestCount](QuestLog/Properties/QuestCount_9B993239C65A.md) | Number of quests in the log. Address: 12729040 (0xC24350) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [AbandonQuest(byte)](QuestLog/Methods/AbandonQuest_CA199E89B57F.md) | Abandons a quest by log slot. |
| Public method | [AbandonQuestById(uint)](QuestLog/Methods/AbandonQuestById_DA8BB03BA32E.md) | Abandons a quest by ID. Address: 12729052 (0xC2435C), Call: 6163648 (0x5E1CC0) |
| Public method | [AddCompletedQuest(uint)](QuestLog/Methods/AddCompletedQuest_13A1B66D844D.md) | Adds a quest ID to the completed quests cache. |
| Public method | [AddCompletedQuestId(uint)](QuestLog/Methods/AddCompletedQuestId_758178644FE9.md) | Adds a quest ID to the completed quests cache (HB 3.3.5a alias). |
| Public method | [ContainsQuest(uint)](QuestLog/Methods/ContainsQuest_8E5182444054.md) | Checks if a quest is in the log. |
| Public method | [GetAllQuests](QuestLog/Methods/GetAllQuests_9E1C01E97775.md) | Gets all quests in the log. |
| Public method | [GetCompletedQuests](QuestLog/Methods/GetCompletedQuests_FAD36336E2BA.md) | Gets a read-only collection of quest IDs that have been completed. Uses Lua QueryQuestsCompleted() which triggers QUEST_QUERY_COMPLETE event. Then reads the completed quest linked list from memory. Results are cached for 1 minute. |
| Public method | [GetIndexForQuest(uint)](QuestLog/Methods/GetIndexForQuest_24231636A00C.md) | Gets the quest log index for a quest ID. |
| Public method | [GetQuest(uint)](QuestLog/Methods/GetQuest_95AA47A0F6E7.md) | Gets a quest by log index. |
| Public method | [GetQuestById(uint)](QuestLog/Methods/GetQuestById_94EC0C412BD5.md) | Gets a quest by ID. |
| Public method | [GetQuestId(uint)](QuestLog/Methods/GetQuestId_81438F5144AE.md) | Gets the quest ID at a log index. |
| Public method | [GetQuestInfo(int)](QuestLog/Methods/GetQuestInfo_6B30FD1BE060.md) | Gets quest info at a log index. descriptor_ptr + (field * 4) — quest log starts at field 158, each entry is 5 fields (20 bytes). So byte offset = (158 + index * 5) * 4, NOT 158 + index * 5 * 4. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Questing Namespace](../../../../namespaces/Styx/Logic/Questing.md)
