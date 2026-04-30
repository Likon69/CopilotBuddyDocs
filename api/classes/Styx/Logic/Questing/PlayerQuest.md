# PlayerQuest Class

Represents a quest in the player's quest log.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Questing.Quest
    Styx.Logic.Questing.PlayerQuest

## Namespace
[Styx.Logic.Questing](../../../../namespaces/Styx/Logic/Questing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class PlayerQuest : Quest
```

The PlayerQuest type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [PlayerQuest(QuestCacheEntry)](PlayerQuest/Constructors/Constructor_412D3D2E1A79.md) | Initializes a new instance of the PlayerQuest class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsCompleted](PlayerQuest/Properties/IsCompleted_D18D64196AD0.md) | Whether the quest is completed. |
| Public property | [IsFailed](PlayerQuest/Properties/IsFailed_0523D1F6EA5E.md) | Whether the quest has failed. |
| Public property | CollectIntermediateItemCounts | Gets the collect intermediate item counts. (Inherited from Quest.) |
| Public property | CollectIntermediateItemIds | Gets the collect intermediate item ids. (Inherited from Quest.) |
| Public property | CollectItemCounts | Gets the collect item counts. (Inherited from Quest.) |
| Public property | CollectItemIds | Gets the collect item ids. (Inherited from Quest.) |
| Public property | CompletionText | Gets the completion text. (Inherited from Quest.) |
| Public property | Description | Gets the description. (Inherited from Quest.) |
| Public property | Flags | Gets the flags. (Inherited from Quest.) |
| Public property | FlagsPVP | True if quest has PVP flag (HB 3.3.5a parity). (Inherited from Quest.) |
| Public property | FriendlyFactionAmount | Gets the friendly faction amount. (Inherited from Quest.) |
| Public property | FriendlyFactionId | Gets the friendly faction id. (Inherited from Quest.) |
| Public property | HostileFactionAmount | Gets the hostile faction amount. (Inherited from Quest.) |
| Public property | HostileFactionId | Gets the hostile faction id. (Inherited from Quest.) |
| Public property | Id | Gets the id. (Inherited from Quest.) |
| Public property | InternalInfo | Gets the internal info. (Inherited from Quest.) |
| Public property | IsAutoAccepted | True if quest is auto-accepted (HB 3.3.5a parity). (Inherited from Quest.) |
| Public property | IsDaily | True if quest is a daily quest (HB 3.3.5a parity). (Inherited from Quest.) |
| Public property | IsPartyQuest | True if quest has PartyQuest flag (HB 3.3.5a parity). (Inherited from Quest.) |
| Public property | IsShareable | True if quest can be shared with party members (HB 3.3.5a parity). (Inherited from Quest.) |
| Public property | IsStayAliveQuest | True if quest has StayAlive flag (HB 3.3.5a parity). (Inherited from Quest.) |
| Public property | IsWeekly | True if quest is a weekly quest (HB 3.3.5a parity). (Inherited from Quest.) |
| Public property | Level | Gets the level. (Inherited from Quest.) |
| Public property | Name | Gets the name. (Inherited from Quest.) |
| Public property | NextQuestId | Gets the next quest id. (Inherited from Quest.) |
| Public property | NormalObjectiveIDs | Gets the normal objective i ds. (Inherited from Quest.) |
| Public property | NormalObjectiveRequiredCounts | Gets the normal objective required counts. (Inherited from Quest.) |
| Public property | ObjectiveText | Gets the objective text. (Inherited from Quest.) |
| Public property | Objectives | Gets the objectives. (Inherited from Quest.) |
| Public property | PointMapId | Gets the point map id. (Inherited from Quest.) |
| Public property | PointOptional | Gets the point optional. (Inherited from Quest.) |
| Public property | PointX | Gets the point x. (Inherited from Quest.) |
| Public property | PointY | Gets the point y. (Inherited from Quest.) |
| Public property | RequiredLevel | Gets the required level. (Inherited from Quest.) |
| Public property | RequiredPlayersKilled | Gets the required players killed. (Inherited from Quest.) |
| Public property | RewardArenaPoints | Gets the reward arena points. (Inherited from Quest.) |
| Public property | RewardChoiceItemCounts | Gets the reward choice item counts. (Inherited from Quest.) |
| Public property | RewardChoiceItemIds | Gets the reward choice item ids. (Inherited from Quest.) |
| Public property | RewardItemCounts | Gets the reward item counts. (Inherited from Quest.) |
| Public property | RewardItemIds | Gets the reward item ids. (Inherited from Quest.) |
| Public property | RewardMoney | Gets the reward money. (Inherited from Quest.) |
| Public property | RewardMoneyAtMaxLevel | Alias for RewardMoneyCompensation — money reward at max level instead of XP (HB 3.3.5a parity). (Inherited from Quest.) |
| Public property | RewardMoneyCompensation | Gets the reward money compensation. (Inherited from Quest.) |
| Public property | RewardNumTalentPoints | Gets the reward num talent points. (Inherited from Quest.) |
| Public property | RewardSpell | Cached WoWSpell for the quest reward spell (HB 3.3.5a parity). (Inherited from Quest.) |
| Public property | RewardSpellId | Gets the reward spell id. (Inherited from Quest.) |
| Public property | RewardTalentPoints | Gets the reward talent points. (Inherited from Quest.) |
| Public property | RewardTitleId | Gets the reward title id. (Inherited from Quest.) |
| Public property | RewardXp | Estimated XP reward based on quest and player level (HB 3.3.5a parity). (Inherited from Quest.) |
| Public property | SubDescription | Gets the sub description. (Inherited from Quest.) |
| Public property | SuggestedPlayers | Gets the suggested players. (Inherited from Quest.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetCompletionInfo](PlayerQuest/Methods/GetCompletionInfo_1828EAFF9D2F.md) | Gets completion info for this quest. Address: 12729088 (0xC24380) |
| Public method | [GetCompletionInfo(WoWQuestCompletionInfo)](PlayerQuest/Methods/GetCompletionInfo_46CE4A550087.md) | Gets completion info for this quest. |
| Public method | [GetData(WoWDescriptorQuest)](PlayerQuest/Methods/GetData_91C20F049019.md) | Gets quest data from player descriptor. Offset: BaseAddress + 8 -> descriptor + 632 |
| Public method | GetData(QuestDescriptorData) | Gets descriptor data for this quest from the player's quest log. Reads the 25 quest log slots in the player descriptor table. Layout per slot (5 descriptor indices each, starting at 0x9E): +0: Quest ID (uint) +1: State flags (uint → WoWDescriptorQuestFlags) +2: Objective counts low (2 packed ushorts: objectives 0,1) +3: Objective counts high (2 packed ushorts: objectives 2,3) +4: Timer (uint, seconds before failed). (Inherited from Quest.) |
| Public method | GetObjectives | Gets all objectives for this quest. (Inherited from Quest.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from Quest.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Questing Namespace](../../../../namespaces/Styx/Logic/Questing.md)
