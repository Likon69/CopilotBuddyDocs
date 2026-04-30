# Quest Class

Represents a quest.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Questing.Quest

## Namespace
[Styx.Logic.Questing](../../../../namespaces/Styx/Logic/Questing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class Quest
```

The Quest type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public struct | [Quest.QuestObjective](Quest/QuestObjective.md) | Represents a single quest objective. |
| Public enumeration | [Quest.QuestObjectiveType](Quest/QuestObjectiveType.md) | Types of quest objectives. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [Quest(QuestCacheEntry)](Quest/Constructors/Constructor_DB7D377E0533.md) | Initializes a new instance of the Quest class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [CollectIntermediateItemCounts](Quest/Properties/CollectIntermediateItemCounts_85F11454D9F9.md) | Gets the collect intermediate item counts. |
| Public property | [CollectIntermediateItemIds](Quest/Properties/CollectIntermediateItemIds_BBCB3D08F2D7.md) | Gets the collect intermediate item ids. |
| Public property | [CollectItemCounts](Quest/Properties/CollectItemCounts_151F75EB66B2.md) | Gets the collect item counts. |
| Public property | [CollectItemIds](Quest/Properties/CollectItemIds_A260AAFF905B.md) | Gets the collect item ids. |
| Public property | [CompletionText](Quest/Properties/CompletionText_480310D4F945.md) | Gets the completion text. |
| Public property | [Description](Quest/Properties/Description_FDE4D8F4FAEA.md) | Gets the description. |
| Public property | [Flags](Quest/Properties/Flags_C3AA11F69DA2.md) | Gets the flags. |
| Public property | [FlagsPVP](Quest/Properties/FlagsPVP_8C74D0F14D3C.md) | True if quest has PVP flag (HB 3.3.5a parity). |
| Public property | [FriendlyFactionAmount](Quest/Properties/FriendlyFactionAmount_B0BFB9BEFD9E.md) | Gets the friendly faction amount. |
| Public property | [FriendlyFactionId](Quest/Properties/FriendlyFactionId_070D6D512DEF.md) | Gets the friendly faction id. |
| Public property | [HostileFactionAmount](Quest/Properties/HostileFactionAmount_B33DF538B675.md) | Gets the hostile faction amount. |
| Public property | [HostileFactionId](Quest/Properties/HostileFactionId_E0FF3C0FB64C.md) | Gets the hostile faction id. |
| Public property | [Id](Quest/Properties/Id_D4E5011AEABC.md) | Gets the id. |
| Public property | [InternalInfo](Quest/Properties/InternalInfo_C7B99D643F26.md) | Gets the internal info. |
| Public property | [IsAutoAccepted](Quest/Properties/IsAutoAccepted_398A9D01A56E.md) | True if quest is auto-accepted (HB 3.3.5a parity). |
| Public property | [IsDaily](Quest/Properties/IsDaily_F4064EAC9A7C.md) | True if quest is a daily quest (HB 3.3.5a parity). |
| Public property | [IsPartyQuest](Quest/Properties/IsPartyQuest_477F0904E152.md) | True if quest has PartyQuest flag (HB 3.3.5a parity). |
| Public property | [IsShareable](Quest/Properties/IsShareable_4F8E1188EAC6.md) | True if quest can be shared with party members (HB 3.3.5a parity). |
| Public property | [IsStayAliveQuest](Quest/Properties/IsStayAliveQuest_E379D130F509.md) | True if quest has StayAlive flag (HB 3.3.5a parity). |
| Public property | [IsWeekly](Quest/Properties/IsWeekly_011D687172BD.md) | True if quest is a weekly quest (HB 3.3.5a parity). |
| Public property | [Level](Quest/Properties/Level_54846422A61D.md) | Gets the level. |
| Public property | [Name](Quest/Properties/Name_23CCC6A2AD6D.md) | Gets the name. |
| Public property | [NextQuestId](Quest/Properties/NextQuestId_AD31C62B253A.md) | Gets the next quest id. |
| Public property | [NormalObjectiveIDs](Quest/Properties/NormalObjectiveIDs_017B2B281C1D.md) | Gets the normal objective i ds. |
| Public property | [NormalObjectiveRequiredCounts](Quest/Properties/NormalObjectiveRequiredCounts_13E2B66A5DD8.md) | Gets the normal objective required counts. |
| Public property | [ObjectiveText](Quest/Properties/ObjectiveText_99288D8FA2B1.md) | Gets the objective text. |
| Public property | [Objectives](Quest/Properties/Objectives_57CE4B11823B.md) | Gets the objectives. |
| Public property | [PointMapId](Quest/Properties/PointMapId_631ED87809F1.md) | Gets the point map id. |
| Public property | [PointOptional](Quest/Properties/PointOptional_2AC7CC87BAF2.md) | Gets the point optional. |
| Public property | [PointX](Quest/Properties/PointX_0B21DBE64E7A.md) | Gets the point x. |
| Public property | [PointY](Quest/Properties/PointY_64E3CE5C3768.md) | Gets the point y. |
| Public property | [RequiredLevel](Quest/Properties/RequiredLevel_FCE2DCC4DE5F.md) | Gets the required level. |
| Public property | [RequiredPlayersKilled](Quest/Properties/RequiredPlayersKilled_886208F12B5C.md) | Gets the required players killed. |
| Public property | [RewardArenaPoints](Quest/Properties/RewardArenaPoints_E2FA5450214D.md) | Gets the reward arena points. |
| Public property | [RewardChoiceItemCounts](Quest/Properties/RewardChoiceItemCounts_E028F99594D9.md) | Gets the reward choice item counts. |
| Public property | [RewardChoiceItemIds](Quest/Properties/RewardChoiceItemIds_A37B7F4B4DCE.md) | Gets the reward choice item ids. |
| Public property | [RewardItemCounts](Quest/Properties/RewardItemCounts_93DE326C553D.md) | Gets the reward item counts. |
| Public property | [RewardItemIds](Quest/Properties/RewardItemIds_67580D08CF0B.md) | Gets the reward item ids. |
| Public property | [RewardMoney](Quest/Properties/RewardMoney_5CF21F2D4627.md) | Gets the reward money. |
| Public property | [RewardMoneyAtMaxLevel](Quest/Properties/RewardMoneyAtMaxLevel_97361D2EAAEC.md) | Alias for RewardMoneyCompensation — money reward at max level instead of XP (HB 3.3.5a parity). |
| Public property | [RewardMoneyCompensation](Quest/Properties/RewardMoneyCompensation_8A775AD8484E.md) | Gets the reward money compensation. |
| Public property | [RewardNumTalentPoints](Quest/Properties/RewardNumTalentPoints_96F50BF6E743.md) | Gets the reward num talent points. |
| Public property | [RewardSpell](Quest/Properties/RewardSpell_136F7BE3F852.md) | Cached WoWSpell for the quest reward spell (HB 3.3.5a parity). |
| Public property | [RewardSpellId](Quest/Properties/RewardSpellId_6B7938A7A9EF.md) | Gets the reward spell id. |
| Public property | [RewardTalentPoints](Quest/Properties/RewardTalentPoints_2E970FC6C87F.md) | Gets the reward talent points. |
| Public property | [RewardTitleId](Quest/Properties/RewardTitleId_022233283454.md) | Gets the reward title id. |
| Public property | [RewardXp](Quest/Properties/RewardXp_104E5E4C23EA.md) | Estimated XP reward based on quest and player level (HB 3.3.5a parity). |
| Public property | [SubDescription](Quest/Properties/SubDescription_60C5F6AF38C5.md) | Gets the sub description. |
| Public property | [SuggestedPlayers](Quest/Properties/SuggestedPlayers_3C7AA1A92EB3.md) | Gets the suggested players. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [FromId(uint)](Quest/Methods/FromId_4C2E55425997.md) | Gets the instance for the specified ID. |
| Public method | [GetData(QuestDescriptorData)](Quest/Methods/GetData_1F8CC0621B55.md) | Gets descriptor data for this quest from the player's quest log. Reads the 25 quest log slots in the player descriptor table. Layout per slot (5 descriptor indices each, starting at 0x9E): +0: Quest ID (uint) +1: State flags (uint → WoWDescriptorQuestFlags) +2: Objective counts low (2 packed ushorts: objectives 0,1) +3: Objective counts high (2 packed ushorts: objectives 2,3) +4: Timer (uint, seconds before failed) |
| Public method | [GetObjectives](Quest/Methods/GetObjectives_D74D88DB28D9.md) | Gets all objectives for this quest. |
| Public method | [ToString](Quest/Methods/ToString_245DD588DA41.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Questing Namespace](../../../../namespaces/Styx/Logic/Questing.md)
