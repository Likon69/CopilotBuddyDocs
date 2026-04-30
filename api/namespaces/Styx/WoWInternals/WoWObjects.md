# Styx.WoWInternals.WoWObjects Namespace

Contains high-level wrappers around in-game units, players, items, game objects, and other object manager entries.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [GameObjectInfo](../../../classes/Styx/WoWInternals/WoWObjects/GameObjectInfo.md) | Cached information about a game object. |
| Public class | [GameObjectSubData](../../../classes/Styx/WoWInternals/WoWObjects/GameObjectSubData.md) | Minimal cached gameobject sub-data (distance, focus id, model id). |
| Public class | [ItemInfo](../../../classes/Styx/WoWInternals/WoWObjects/ItemInfo.md) | Represents an item info. |
| Public class | [ItemStats](../../../classes/Styx/WoWInternals/WoWObjects/ItemStats.md) | Represents an item stats. |
| Public class | [LocalPlayer](../../../classes/Styx/WoWInternals/WoWObjects/LocalPlayer.md) | Represents a local player. |
| Public class | [UnitThreatInfo](../../../classes/Styx/WoWInternals/WoWObjects/UnitThreatInfo.md) | Threat information for a unit. |
| Public class | [WoWAnimatedSubObject](../../../classes/Styx/WoWInternals/WoWObjects/WoWAnimatedSubObject.md) | Represents an animated WoW sub-object. WoW 3.3.5a build 12340. |
| Public class | [WoWChair](../../../classes/Styx/WoWInternals/WoWObjects/WoWChair.md) | Represents a chair in WoW. WoW 3.3.5a build 12340. |
| Public class | [WoWContainer](../../../classes/Styx/WoWInternals/WoWObjects/WoWContainer.md) | Represents an equipped bag container in the player's inventory. Ported from HB 4.3.4 WoWContainer — delegates all item access to an internal WoWBag constructed from BagStructure at containerBaseAddress + 1888 (3.3.5a offset). |
| Public class | [WoWCorpse](../../../classes/Styx/WoWInternals/WoWObjects/WoWCorpse.md) | Represents a wow corpse. |
| Public class | [WoWDoor](../../../classes/Styx/WoWInternals/WoWObjects/WoWDoor.md) | Represents a door in WoW. WoW 3.3.5a build 12340. |
| Public class | [WoWDynamicObject](../../../classes/Styx/WoWInternals/WoWObjects/WoWDynamicObject.md) | Represents a wow dynamic object. |
| Public class | [WoWFishingBobber](../../../classes/Styx/WoWInternals/WoWObjects/WoWFishingBobber.md) | Represents a fishing bobber in WoW. WoW 3.3.5a build 12340. |
| Public class | [WoWGameObject](../../../classes/Styx/WoWInternals/WoWObjects/WoWGameObject.md) | Represents a wow game object. |
| Public class | [WoWItem](../../../classes/Styx/WoWInternals/WoWObjects/WoWItem.md) | Represents a wow item. |
| Public class | [WoWItem.WoWItemEnchantment](../../../classes/Styx/WoWInternals/WoWObjects/WoWItem/WoWItemEnchantment.md) | Represents a wow item enchantment. |
| Public class | [WoWItem.WoWItemRandomProperties](../../../classes/Styx/WoWInternals/WoWObjects/WoWItem/WoWItemRandomProperties.md) | Represents a wow item random properties. |
| Public class | [WoWItem.WoWItemRandomSuffix](../../../classes/Styx/WoWInternals/WoWObjects/WoWItem/WoWItemRandomSuffix.md) | Represents a wow item random suffix. |
| Public class | [WoWItem.WoWItemSpell](../../../classes/Styx/WoWInternals/WoWObjects/WoWItem/WoWItemSpell.md) | Represents a wow item spell. |
| Public class | [WoWItem.WoWItemStat](../../../classes/Styx/WoWInternals/WoWObjects/WoWItem/WoWItemStat.md) | Represents a wow item stat. |
| Public class | [WoWMovementInfo](../../../classes/Styx/WoWInternals/WoWObjects/WoWMovementInfo.md) | Represents movement information for a WoW unit. Contains position, speed, flags and other movement-related data. |
| Public class | [WoWObject](../../../classes/Styx/WoWInternals/WoWObjects/WoWObject.md) | Represents a wow object. |
| Public class | [WoWPartyMember](../../../classes/Styx/WoWInternals/WoWObjects/WoWPartyMember.md) | Represents a party/raid member. WotLK 3.3.5a implementation using Lua calls. |
| Public class | [WoWPlayer](../../../classes/Styx/WoWInternals/WoWObjects/WoWPlayer.md) | Represents a wow player. |
| Public class | [WoWSubObject](../../../classes/Styx/WoWInternals/WoWObjects/WoWSubObject.md) | Represents a WoW sub-object (chair, door, bobber, etc.). WoW 3.3.5a build 12340. |
| Public class | [WoWTotemExtensions](../../../classes/Styx/WoWInternals/WoWObjects/WoWTotemExtensions.md) | Extension methods for WoWTotem enum (HB 4.3.4 compatibility). WotLK 3.3.5a implementation. |
| Public class | [WoWTotemInfo](../../../classes/Styx/WoWInternals/WoWObjects/WoWTotemInfo.md) | Information about an active totem. WotLK 3.3.5a implementation using Lua. |
| Public class | [WoWUnit](../../../classes/Styx/WoWInternals/WoWObjects/WoWUnit.md) | Represents a wow unit. |

## Structures

| | Name | Description |
| --- | --- | --- |
| Public struct | [DurabilityCostEntry](../../../classes/Styx/WoWInternals/WoWObjects/DurabilityCostEntry.md) | Represents a durability cost entry value. |
| Public struct | [DurabilityQualityEntry](../../../classes/Styx/WoWInternals/WoWObjects/DurabilityQualityEntry.md) | Represents a durability quality entry value. |
| Public struct | [FactionStanding](../../../classes/Styx/WoWInternals/WoWObjects/FactionStanding.md) | Represents a player's standing with a faction. |
| Public struct | [LockEntry](../../../classes/Styx/WoWInternals/WoWObjects/LockEntry.md) | Lock entry from Lock.dbc - used for lockpicking/mining/herbalism requirements. |
| Public struct | [MirrorTimerInfo](../../../classes/Styx/WoWInternals/WoWObjects/MirrorTimerInfo.md) | Represents a mirror timer info value. |
| Public struct | [PowerInfo](../../../classes/Styx/WoWInternals/WoWObjects/PowerInfo.md) | FEAT-24: Structured power data for a unit's power type. Provides current/max values, percentages, regen rates, and cost modifiers. |
| Public struct | [WoWArenaTeamInfo](../../../classes/Styx/WoWInternals/WoWObjects/WoWArenaTeamInfo.md) | Represents a wow arena team info value. |
| Public struct | [WoWGlyphInfo](../../../classes/Styx/WoWInternals/WoWObjects/WoWGlyphInfo.md) | FEAT-17: Glyph slot information for WotLK (6 slots: 3 major, 3 minor). |
| Public struct | [WoWMovementInfo.CMovementData](../../../classes/Styx/WoWInternals/WoWObjects/WoWMovementInfo/CMovementData.md) | The raw CMovementData structure as stored in WoW memory. |

## Interfaces

| | Name | Description |
| --- | --- | --- |
| Public interface | [ILootableObject](../../../classes/Styx/WoWInternals/WoWObjects/ILootableObject.md) | Defines the contract for I Lootable Object. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [CorpseFlags](../../../classes/Styx/WoWInternals/WoWObjects/CorpseFlags.md) | Represents flag values for Corpse Flags. |
| Public enumeration | [CorpseType](../../../classes/Styx/WoWInternals/WoWObjects/CorpseType.md) | Type de corps (corpse) dans WoW 3.3.5a |
| Public enumeration | [DynamicObjectType](../../../classes/Styx/WoWInternals/WoWObjects/DynamicObjectType.md) | Represents values for Dynamic Object Type. |
| Public enumeration | [GameObjectFlags](../../../classes/Styx/WoWInternals/WoWObjects/GameObjectFlags.md) | Represents flag values for Game Object Flags. |
| Public enumeration | [RaidTargetMarker](../../../classes/Styx/WoWInternals/WoWObjects/RaidTargetMarker.md) | Represents values for Raid Target Marker. |
| Public enumeration | [ReputationFlags](../../../classes/Styx/WoWInternals/WoWObjects/ReputationFlags.md) | Reputation flags for faction standings. WoW 3.3.5a build 12340. |
| Public enumeration | [RuneType](../../../classes/Styx/WoWInternals/WoWObjects/RuneType.md) | Enumeration of Death Knight rune types. Values match WoW 3.3.5a memory layout at 0xC24304. |
| Public enumeration | [SpecType](../../../classes/Styx/WoWInternals/WoWObjects/SpecType.md) | FEAT-16: Player specialization type for role detection. In WotLK, this is determined by analyzing talent point distribution. Matches HB 4.3.4 enum values: None=0, RangedDps=1, MeleeDps=2, Healer=3, Tank=4. |
| Public enumeration | [WoWGameObjectState](../../../classes/Styx/WoWInternals/WoWObjects/WoWGameObjectState.md) | Represents values for WoW Game Object State. |
| Public enumeration | [WoWInebriationLevel](../../../classes/Styx/WoWInternals/WoWObjects/WoWInebriationLevel.md) | Matches the Honorbuddy enumeration for player alcohol status. This is present in later WoW versions; in 3.3.5a it is unused, but we port it for API compatibility with HB 4.3.4. |
| Public enumeration | [WoWItemStatType](../../../classes/Styx/WoWInternals/WoWObjects/WoWItemStatType.md) | Represents values for WoW Item Stat Type. |
| Public enumeration | [WoWLockType](../../../classes/Styx/WoWInternals/WoWObjects/WoWLockType.md) | Represents values for WoW Lock Type. |
| Public enumeration | [WoWMovementInfo.MoveInfoOffsets](../../../classes/Styx/WoWInternals/WoWObjects/WoWMovementInfo/MoveInfoOffsets.md) | Offsets within the CMovementData structure for WoW 3.3.5a (Build 12340). |
| Public enumeration | [WoWMovementInfo.MovementFlag](../../../classes/Styx/WoWInternals/WoWObjects/WoWMovementInfo/MovementFlag.md) | Movement flags for WoW 3.3.5a. Ported from HB 4.3.4. |
| Public enumeration | [WoWPartyMember.GroupRole](../../../classes/Styx/WoWInternals/WoWObjects/WoWPartyMember/GroupRole.md) | Group role flags. |
| Public enumeration | [WoWPlayerCombatRating](../../../classes/Styx/WoWInternals/WoWObjects/WoWPlayerCombatRating.md) | Represents values for WoW Player Combat Rating. |
| Public enumeration | [WoWSocketColor](../../../classes/Styx/WoWInternals/WoWObjects/WoWSocketColor.md) | Represents values for WoW Socket Color. |
| Public enumeration | [WoWTotem](../../../classes/Styx/WoWInternals/WoWObjects/WoWTotem.md) | Known totem spell IDs for WotLK 3.3.5a. Each totem is identified by its SpellId. |
| Public enumeration | [WoWTotemType](../../../classes/Styx/WoWInternals/WoWObjects/WoWTotemType.md) | Totem element types for Shamans. WotLK has 4 totem slots: Fire, Earth, Water, Air |

## Delegates

| | Name | Description |
| --- | --- | --- |
| Public delegate | [ObjectInvalidateDelegate](../../../classes/Styx/WoWInternals/WoWObjects/ObjectInvalidateDelegate.md) | Represents a delegate for object invalidate. |

## See Also
[Namespace Index](../../../index.md)
