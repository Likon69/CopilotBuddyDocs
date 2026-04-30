# LocalPlayer Class

Represents a local player.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWObject
    Styx.WoWInternals.WoWObjects.WoWUnit
      Styx.WoWInternals.WoWObjects.WoWPlayer
        Styx.WoWInternals.WoWObjects.LocalPlayer

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class LocalPlayer : WoWPlayer
```

The LocalPlayer type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [LocalPlayer(uint)](LocalPlayer/Constructors/Constructor_CB02084D6419.md) | Initializes a new instance of the LocalPlayer class. |

## Fields

| | Name | Description |
| --- | --- | --- |
| Public field | [QuestLog](LocalPlayer/Fields/QuestLog_D1A40BF9DBF3.md) | Gets the player's quest log. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AccountName](LocalPlayer/Properties/AccountName_30D10B447475.md) | Gets the account name. |
| Public property | [AllSkills](LocalPlayer/Properties/AllSkills_71D86BE67033.md) | Gets all skills in a dictionary (ID -> WoWSkill). |
| Public property | [AuthRepeatingSpellId](LocalPlayer/Properties/AuthRepeatingSpellId_B064926DD5B5.md) | Gets the current repeating spell ID (auto-attack spell). |
| Public property | [AutoRepeatingSpellId](LocalPlayer/Properties/AutoRepeatingSpellId_0838018BA48D.md) | Alias for AuthRepeatingSpellId for compatibility. |
| Public property | [BagItemGuids](LocalPlayer/Properties/BagItemGuids_9A3B575B84AE.md) | Gets the backpack and bag contents (GUIDs only). |
| Public property | [BagItems](LocalPlayer/Properties/BagItems_760AAE711169.md) | Gets all items in bags and equipped slots. |
| Public property | [BagsFull](LocalPlayer/Properties/BagsFull_DCEB9561CF18.md) | Whether all bag slots are full. Ported from HB 3.3.5a |
| Public property | [BloodRuneCount](LocalPlayer/Properties/BloodRuneCount_A5EA6B8C463A.md) | Gets the count of blood runes. |
| Public property | [CachedCurrentTarget](LocalPlayer/Properties/CachedCurrentTarget_AF34EE068965.md) | Helper that mirrors Honorbuddy's 400ms target cache used all over the targeting code. Access through rather than calling GetTarget repeatedly. |
| Public property | [CanSkinLevel](LocalPlayer/Properties/CanSkinLevel_49C366F7D960.md) | Gets the maximum level of creatures this player can skin based on Skinning skill. |
| Public property | [CarriedItemGuids](LocalPlayer/Properties/CarriedItemGuids_767F964DCAC2.md) | Gets all carried items (bags + currency + keyring + equipped). |
| Public property | [CarriedItems](LocalPlayer/Properties/CarriedItems_044B65FD4633.md) | Gets all carried items (bags + currency + keyring + equipped). |
| Public property | [ComboPoints](LocalPlayer/Properties/ComboPoints_F7F1D0F48469.md) | Gets the current combo points on the target. Ported from HB 3.3.5a - Addresses: 12388520 (target GUID), 12388429 (combo points byte) |
| Public property | [ContinentName](LocalPlayer/Properties/ContinentName_751763CB8F73.md) | Gets the continent name. |
| Public property | [CorpsePoint](LocalPlayer/Properties/CorpsePoint_B9A7BB237027.md) | Gets the corpse point. |
| Public property | [CurrentCastId](LocalPlayer/Properties/CurrentCastId_68E3751F672B.md) | Gets the spell ID currently being cast (HB 4.3.4 compatibility). |
| Public property | [CurrentCursorSpell](LocalPlayer/Properties/CurrentCursorSpell_AD67E83EE962.md) | Gets the spell currently pending on the cursor (if any). Address: 11489876 (0xAF5254) Ported from HB 3.3.5a smethod_11 |
| Public property | [CurrentMap](LocalPlayer/Properties/CurrentMap_E05DA4998AE0.md) | Gets the current map information from the Map.dbc. Based on HB 4.3.4. |
| Public property | [CurrentPendingCursorSpell](LocalPlayer/Properties/CurrentPendingCursorSpell_FC70CDC10460.md) | Gets the spell currently awaiting target selection (null if none). Ported from HB 4.3.4. |
| Public property | [CurrentXP](LocalPlayer/Properties/CurrentXP_BCBBD3C38863.md) | Gets the current xp. |
| Public property | [DeathRuneCount](LocalPlayer/Properties/DeathRuneCount_B9D3374DC744.md) | Gets the count of death runes. |
| Public property | [Distance](LocalPlayer/Properties/Distance_DDA7E88D292A.md) | Gets the distance. (Overrides WoWObject.Distance.) |
| Public property | [DistanceSqr](LocalPlayer/Properties/DistanceSqr_45FF14AED9B3.md) | Gets the distance sqr. (Overrides WoWObject.DistanceSqr.) |
| Public property | [Durability](LocalPlayer/Properties/Durability_AEDE304D39A5.md) | Gets the total durability of all equipped items. HB 4.3.4: Inventory.Equipped.PhysicalItems.Sum(i => i.Durability) |
| Public property | [DurabilityPercent](LocalPlayer/Properties/DurabilityPercent_A8C69184CE7B.md) | Gets the durability percentage (0.0 to 1.0). |
| Public property | [FocusedUnit](LocalPlayer/Properties/FocusedUnit_1A25270EF5CA.md) | Gets the focused unit (if any). |
| Public property | [FocusedUnitGuid](LocalPlayer/Properties/FocusedUnitGuid_E5EE7449623A.md) | Gets the GUID of the focused unit. |
| Public property | [FreeBagSlots](LocalPlayer/Properties/FreeBagSlots_0AE38EF82DF0.md) | Gets the number of free bag slots (including bank bags when at bank). Ported from HB 3.3.5a |
| Public property | [FreeNormalBagSlots](LocalPlayer/Properties/FreeNormalBagSlots_5C98B00FAEC4.md) | Gets the number of free normal bag slots (excludes special bags like herb, mining, etc.). Ported from HB 3.3.5a |
| Public property | [FrostRuneCount](LocalPlayer/Properties/FrostRuneCount_36246CFB9BC3.md) | Gets the count of frost runes. |
| Public property | [GroupInfo](LocalPlayer/Properties/GroupInfo_200AEBEAEFF2.md) | Gets the group information for this player. |
| Public property | [HasPet](LocalPlayer/Properties/HasPet_77DC51381995.md) | Gets a value indicating whether has pet. |
| Public property | [HearthstoneAreaId](LocalPlayer/Properties/HearthstoneAreaId_5024705B1539.md) | Returns the area ID of the player's hearthstone binding point. HB 4.3.4: ReadRelative(Offsets[5013]). 3.3.5a: GetHomebindAreaId() @ 0x6CEF10. |
| Public property | [InPvpCombat](LocalPlayer/Properties/InPvpCombat_22AE4A57DF73.md) | Whether the player is engaged in PvP combat. HB exposed this so certain logic can ignore PvP situations. We return the PvP flag. |
| Public property | [InVehicle](LocalPlayer/Properties/InVehicle_CE758B9795BF.md) | Whether the player is currently in a vehicle. Vehicles were introduced in WotLK 3.3.5a. Uses Lua UnitInVehicle("player"). |
| Public property | [InstanceCorpseLocation](LocalPlayer/Properties/InstanceCorpseLocation_9C2DD4A19D44.md) | Gets the instance corpse location. |
| Public property | [Inventory](LocalPlayer/Properties/Inventory_538988333882.md) | Gets the player's inventory structure. |
| Public property | [IsActuallyInCombat](LocalPlayer/Properties/IsActuallyInCombat_DBEFEAE798E3.md) | Gets a value indicating whether is actually in combat. |
| Public property | [IsAscending](LocalPlayer/Properties/IsAscending_8837097491DC.md) | Whether the player is ascending (in elevator/moving up). |
| Public property | [IsAutoRepeatingSpell](LocalPlayer/Properties/IsAutoRepeatingSpell_2899A2F42565.md) | Whether the player is auto-repeating a spell. |
| Public property | [IsBeingAttacked](LocalPlayer/Properties/IsBeingAttacked_C569A5D8C974.md) | Returns true if the player is currently being attacked by something. This is a lightweight approximation of HonorBuddy's logic, using threat status when available and falling back to "in combat". |
| Public property | [IsGhost](LocalPlayer/Properties/IsGhost_7B165F687BBE.md) | Gets a value indicating whether is ghost. (Overrides WoWPlayer.IsGhost.) |
| Public property | [IsInCombat](LocalPlayer/Properties/IsInCombat_86792F7BE7B4.md) | Gets a value indicating whether is in combat. |
| Public property | [IsInInstance](LocalPlayer/Properties/IsInInstance_EF74075DF724.md) | Whether the player is in an instanced zone. Reads Map.dbc field 2 (MapType) via WoWDb — field != 0 means Instance/Raid/BG/Arena. Matches HB 3.3.5a LocalPlayer.IsInInstance exactly. |
| Public property | [IsInParty](LocalPlayer/Properties/IsInParty_EFAE1469AE13.md) | Gets whether the player is in a party. |
| Public property | [IsInRaid](LocalPlayer/Properties/IsInRaid_167354A1EA5D.md) | Gets whether the player is in a raid. |
| Public property | [IsIndoors](LocalPlayer/Properties/IsIndoors_4922FC0B0319.md) | FEAT-45: IsIndoors = !IsOutdoors for LocalPlayer. (Overrides WoWObject.IsIndoors.) |
| Public property | [IsMe](LocalPlayer/Properties/IsMe_CA4E5333D7AB.md) | Gets a value indicating whether is me. |
| Public property | [IsMounted](LocalPlayer/Properties/IsMounted_EE4264F663A0.md) | Gets a value indicating whether is mounted. |
| Public property | [IsOutdoors](LocalPlayer/Properties/IsOutdoors_79527E64BE0D.md) | FEAT-45: More accurate indoor check for LocalPlayer via Lua IsOutdoors(). HB 4.3.4 overrides IsOutdoors on LocalPlayer with Lua call. (Overrides WoWObject.IsOutdoors.) |
| Public property | [IsRooted](LocalPlayer/Properties/IsRooted_3369AEB82FFC.md) | Returns true if the player is rooted. |
| Public property | [IsStealthed](LocalPlayer/Properties/IsStealthed_BABD104CFFDB.md) | Gets whether the player is stealthed. |
| Public property | [IsStunned](LocalPlayer/Properties/IsStunned_7E05C2DC359B.md) | Returns true if the player is stunned. |
| Public property | [IsTravelForm](LocalPlayer/Properties/IsTravelForm_CBB5A787156F.md) | Gets a value indicating whether is travel form. |
| Public property | [KnownSpells](LocalPlayer/Properties/KnownSpells_B394FBA9267E.md) | Gets the known spells. |
| Public property | [LastRedErrorMessage](LocalPlayer/Properties/LastRedErrorMessage_5E3D1C8B4430.md) | Gets the last red error message. |
| Public property | [LoadingScreen](LocalPlayer/Properties/LoadingScreen_9EEF24591343.md) | Whether there's a loading screen. Deprecated: Use StyxWoW.IsInGame instead. Ported from HB 3.3.5a for compatibility. |
| Public property | [LocalTarget](LocalPlayer/Properties/LocalTarget_8BE6783A4F06.md) | Gets the local target. |
| Public property | [LocalTargetGuid](LocalPlayer/Properties/LocalTargetGuid_ED50B5E289FF.md) | Gets the local target guid. |
| Public property | [LowestDurabilityPercent](LocalPlayer/Properties/LowestDurabilityPercent_9AC14562EE9D.md) | Gets the lowest durability percentage among equipped items (0.0 to 1.0). HB 4.3.4: iterates Equipped.PhysicalItems, finds min DurabilityPercent / 100.0 |
| Public property | [ManaRegenRate](LocalPlayer/Properties/ManaRegenRate_4787E729B282.md) | Gets the mana regeneration rate per 5 seconds. |
| Public property | [MapId](LocalPlayer/Properties/MapId_64DE581D2022.md) | Gets the map id. |
| Public property | [MapName](LocalPlayer/Properties/MapName_85141755EA78.md) | Gets the map name. Ported from HB 3.3.5a - Address 13502160U |
| Public property | [MaxDurability](LocalPlayer/Properties/MaxDurability_79C8C57C2490.md) | Gets the maximum durability of all equipped items. HB 4.3.4: Inventory.Equipped.PhysicalItems.Sum(i => i.MaxDurability) |
| Public property | [MinimapZoneText](LocalPlayer/Properties/MinimapZoneText_2FE2C117D6DD.md) | Gets the current minimap zone text. Ported from HB 3.3.5a - reads pointer at 12388220U then string at that address. |
| Public property | [NormalBagsFull](LocalPlayer/Properties/NormalBagsFull_B37DC6DE877C.md) | Whether all normal (non-special) bag slots are full. Ported from HB 3.3.5a |
| Public property | [NumRaidMembers](LocalPlayer/Properties/NumRaidMembers_1119BFB01741.md) | Gets the number of raid members. |
| Public property | [PartyMember1](LocalPlayer/Properties/PartyMember1_9D8085C6813C.md) | Gets party member 1. |
| Public property | [PartyMember1GUID](LocalPlayer/Properties/PartyMember1GUID_A6417ADEBB2E.md) | Gets the GUID of party member 1. |
| Public property | [PartyMember2](LocalPlayer/Properties/PartyMember2_1426E9E738BB.md) | Gets party member 2. |
| Public property | [PartyMember2GUID](LocalPlayer/Properties/PartyMember2GUID_09E68104F55C.md) | Gets the GUID of party member 2. |
| Public property | [PartyMember3](LocalPlayer/Properties/PartyMember3_3ACF702D2658.md) | Gets party member 3. |
| Public property | [PartyMember3GUID](LocalPlayer/Properties/PartyMember3GUID_4CB0921BE2D0.md) | Gets the GUID of party member 3. |
| Public property | [PartyMember4](LocalPlayer/Properties/PartyMember4_8C34F3B7F17B.md) | Gets party member 4. |
| Public property | [PartyMember4GUID](LocalPlayer/Properties/PartyMember4GUID_FCDC2AABFCCA.md) | Gets the GUID of party member 4. |
| Public property | [PartyMemberGuids](LocalPlayer/Properties/PartyMemberGuids_E8C3B01A938F.md) | Gets all party member GUIDs as array (non-zero values only). |
| Public property | [PartyMemberInfos](LocalPlayer/Properties/PartyMemberInfos_A97BEBFB3BF6.md) | Gets party member infos (WoWPartyMember objects). |
| Public property | [PartyMembers](LocalPlayer/Properties/PartyMembers_C81C119D17C4.md) | Gets party members as WoWPlayer objects (only alive/valid players). |
| Public property | [Pet](LocalPlayer/Properties/Pet_09F970CBDE25.md) | Gets the pet. (Overrides WoWUnit.Pet.) |
| Public property | [PetSpells](LocalPlayer/Properties/PetSpells_4C8E7003331D.md) | Gets the list of pet spells (action bar). |
| Public property | [PowerPercent](LocalPlayer/Properties/PowerPercent_3FB3CF6CE84C.md) | Gets the power percentage (mana/rage/energy/etc). |
| Public property | [RaidMemberGuids](LocalPlayer/Properties/RaidMemberGuids_0F1FF94BF6EC.md) | Gets all raid member GUIDs as array (non-zero values only). |
| Public property | [RaidMemberInfos](LocalPlayer/Properties/RaidMemberInfos_311F9109A632.md) | Gets raid member infos (WoWPartyMember objects). |
| Public property | [RaidMembers](LocalPlayer/Properties/RaidMembers_65D0AF985E8E.md) | Gets all raid members (HB 4.3.4 compatibility). Returns party members if not in raid. |
| Public property | [RawComboPoints](LocalPlayer/Properties/RawComboPoints_2576426E308A.md) | Gets raw combo points (HB 4.3.4 compatibility - no Anticipation talent in WotLK). In WotLK, this is identical to ComboPoints. |
| Public property | [RealZoneText](LocalPlayer/Properties/RealZoneText_86E78E926051.md) | Gets the real zone text (unmodified by subzones). Ported from HB 3.3.5a - Address 12388224U |
| Public property | [RealmName](LocalPlayer/Properties/RealmName_E47E07BC1ECF.md) | Gets the realm name. |
| Public property | [Role](LocalPlayer/Properties/Role_66207E50201A.md) | Gets the player's group role (Tank, Healer, Damage). Uses GetRaidRosterInfo() which exists in WotLK 3.3.5a (patch 3.3.0+). |
| Public property | [Snared](LocalPlayer/Properties/Snared_6830C374F159.md) | Returns true if the player is snared (slowed). |
| Public property | [SpecType](LocalPlayer/Properties/SpecType_2F1FF5766C35.md) | HB 4.3.4 API compatibility alias — combat routines and bots reference Me.SpecType. |
| Public property | [Specialization](LocalPlayer/Properties/Specialization_3D569277855B.md) | FEAT-39: Detects the player's spec type from talent tree points. Analyzes the primary talent tree to determine role. |
| Public property | [Stance](LocalPlayer/Properties/Stance_6E4CADF84AE9.md) | Gets the player's current shapeshift form (stance). |
| Public property | [SubZoneId](LocalPlayer/Properties/SubZoneId_4582F75764A7.md) | Gets the current sub-zone (area) ID. Reads from 0xBD0810 — matches GlobalOffsets.AreaId. HB API exposes this as SubZoneId on LocalPlayer. |
| Public property | [SubZoneText](LocalPlayer/Properties/SubZoneText_CD81FD6493AF.md) | Gets the subzone text. Ported from HB 3.3.5a - Address 12388228U |
| Public property | [Totems](LocalPlayer/Properties/Totems_0A21BB589732.md) | Gets the totems. |
| Public property | [UnholyRuneCount](LocalPlayer/Properties/UnholyRuneCount_B2ECB504302E.md) | Gets the count of unholy runes. |
| Public property | [XPPercent](LocalPlayer/Properties/XPPercent_D2D9D71B8DDE.md) | Gets the xp percent. |
| Public property | [XPToNextLevel](LocalPlayer/Properties/XPToNextLevel_E7EBCA6A95A0.md) | BUG-15: Reads PLAYER_NEXT_LEVEL_XP from descriptor instead of hardcoded formula. WoWPlayer already reads this correctly via NextLevelXP. |
| Public property | [ZoneId](LocalPlayer/Properties/ZoneId_42B7BB58C5C9.md) | Gets the zone id. |
| Public property | [ZoneText](LocalPlayer/Properties/ZoneText_1CFDD2E9B35C.md) | Gets the zone text (may be modified by subzones). Ported from HB 3.3.5a - Address 12388232U |
| Public property | ArcaneBonusNegative | Arcane bonus damage (negative). (Inherited from WoWPlayer.) |
| Public property | ArcaneBonusPercent | Arcane bonus damage percent. (Inherited from WoWPlayer.) |
| Public property | ArcaneBonusPositive | Arcane bonus damage (positive). (Inherited from WoWPlayer.) |
| Public property | ArcaneCritPercent | Arcane spell crit percentage. (Inherited from WoWPlayer.) |
| Public property | ArenaCurrency | Arena points (PLAYER_FIELD_ARENA_CURRENCY). (Inherited from WoWPlayer.) |
| Public property | ArmorPenetration | Armor penetration rating (index 24 = CR_ARMOR_PENETRATION in WotLK). (Inherited from WoWPlayer.) |
| Public property | BankBagSlotCount | Number of purchased bank bag slots (byte 2 of PLAYER_BYTES_2, 0x9A). (Inherited from WoWPlayer.) |
| Public property | BattlefieldArenaFaction | Battlefield arena faction (byte 3 of PLAYER_BYTES_3). (Inherited from WoWPlayer.) |
| Public property | BlockPercent | Block chance percentage (PLAYER_BLOCK_PERCENTAGE). (Inherited from WoWPlayer.) |
| Public property | CharacterPoints | Talent points remaining (PLAYER_CHARACTER_POINTS1). (Inherited from WoWPlayer.) |
| Public property | CharacterPoints2 | Profession points remaining (PLAYER_CHARACTER_POINTS2). (Inherited from WoWPlayer.) |
| Public property | ChosenTitle | Currently displayed title (PLAYER_CHOSEN_TITLE). (Inherited from WoWPlayer.) |
| Public property | Coinage | BUG-16: Changed from int to uint to avoid overflow at high gold amounts. WotLK gold cap is ~214k gold = ~2.14 billion copper, fits uint but overflows int. (Inherited from WoWPlayer.) |
| Public property | ContestedPvPFlagged | Gets a value indicating whether contested pv p flagged. (Inherited from WoWPlayer.) |
| Public property | Copper | Total money expressed in copper (same as Coinage). HB 3.3.5a: Copper == Coinage. HB 4.3.4: Copper reads the raw descriptor. (Inherited from WoWPlayer.) |
| Public property | CritPercent | Melee crit chance percentage (PLAYER_CRIT_PERCENTAGE). (Inherited from WoWPlayer.) |
| Public property | DodgePercent | Dodge chance percentage (PLAYER_DODGE_PERCENTAGE). (Inherited from WoWPlayer.) |
| Public property | DuelArbiterGuid | Gets the GUID of the duel arbiter (the flag in the ground during a duel). (Inherited from WoWPlayer.) |
| Public property | DuelTeam | Gets the player's duel team (0 = not dueling, 1 or 2 = team number). (Inherited from WoWPlayer.) |
| Public property | Experience | Gets the experience. (Inherited from WoWPlayer.) |
| Public property | Expertise | Expertise rating (PLAYER_EXPERTISE). (Inherited from WoWPlayer.) |
| Public property | ExpertiseRating | Expertise rating (index 23 = CR_EXPERTISE). (Inherited from WoWPlayer.) |
| Public property | FaceType | Face type (byte 1 of PLAYER_BYTES). (Inherited from WoWPlayer.) |
| Public property | FacialHair | Facial hair style (byte 0 of PLAYER_BYTES_2). (Inherited from WoWPlayer.) |
| Public property | FireBonusNegative | Fire bonus damage (negative). (Inherited from WoWPlayer.) |
| Public property | FireBonusPercent | Fire bonus damage percent. (Inherited from WoWPlayer.) |
| Public property | FireBonusPositive | Fire bonus damage (positive). (Inherited from WoWPlayer.) |
| Public property | FireCritPercent | Fire spell crit percentage. (Inherited from WoWPlayer.) |
| Public property | FrostBonusNegative | Frost bonus damage (negative). (Inherited from WoWPlayer.) |
| Public property | FrostBonusPercent | Frost bonus damage percent. (Inherited from WoWPlayer.) |
| Public property | FrostBonusPositive | Frost bonus damage (positive). (Inherited from WoWPlayer.) |
| Public property | FrostCritPercent | Frost spell crit percentage. (Inherited from WoWPlayer.) |
| Public property | Glyphs | Returns all 6 glyph slots as a list (WotLK: 3 major + 3 minor). (Inherited from WoWPlayer.) |
| Public property | GlyphsEnabled | Glyph enabled bitmask (PLAYER_GLYPHS_ENABLED). (Inherited from WoWPlayer.) |
| Public property | Gold | Gets the gold. (Inherited from WoWPlayer.) |
| Public property | GuildDeleteDate | Guild delete date (Cata+ only). Always 0 in WotLK. (Inherited from WoWPlayer.) |
| Public property | GuildLevel | Guild level (Cata+ only). Always 0 in WotLK. (Inherited from WoWPlayer.) |
| Public property | GuildRank | Guild rank (PLAYER_GUILDRANK). (Inherited from WoWPlayer.) |
| Public property | GuildTimestamp | Guild timestamp (PLAYER_GUILD_TIMESTAMP). (Inherited from WoWPlayer.) |
| Public property | HairColor | Hair color (byte 3 of PLAYER_BYTES). (Inherited from WoWPlayer.) |
| Public property | HairStyle | Hair style (byte 2 of PLAYER_BYTES). (Inherited from WoWPlayer.) |
| Public property | HasRestedXp | Whether the player has rested XP. (Inherited from WoWPlayer.) |
| Public property | HasteRating | Melee haste rating (index 17 = CR_HASTE_MELEE). (Inherited from WoWPlayer.) |
| Public property | HealingBonusPercent | Healing bonus percent. (Inherited from WoWPlayer.) |
| Public property | HealingBonusPositive | Healing bonus (positive). (Inherited from WoWPlayer.) |
| Public property | HealingModifierPercent | Healing modifier percent. (Inherited from WoWPlayer.) |
| Public property | HolyBonusNegative | Holy bonus damage (negative). (Inherited from WoWPlayer.) |
| Public property | HolyBonusPercent | Holy bonus damage percent. (Inherited from WoWPlayer.) |
| Public property | HolyBonusPositive | Holy bonus damage (positive). (Inherited from WoWPlayer.) |
| Public property | HolyCritPercent | Holy spell crit percentage. (Inherited from WoWPlayer.) |
| Public property | Honor | Gets the honor. (Inherited from WoWPlayer.) |
| Public property | HonorableKillsToday | Today's honorable kills (lower 16 bits of PLAYER_FIELD_KILLS). (Inherited from WoWPlayer.) |
| Public property | HonorableKillsYesterday | Yesterday's honorable kills (upper 16 bits of PLAYER_FIELD_KILLS). (Inherited from WoWPlayer.) |
| Public property | InMyParty | HB compatibility alias. (Inherited from WoWPlayer.) |
| Public property | InMyPartyOrRaid | HB compatibility alias. (Inherited from WoWPlayer.) |
| Public property | InMyRaid | HB compatibility alias. (Inherited from WoWPlayer.) |
| Public property | InteractRange | Gets the interact range. (Overrides WoWUnit.InteractRange.). (Inherited from WoWPlayer.) |
| Public property | IsAFKFlagged | Gets a value indicating whether is afk flagged. (Inherited from WoWPlayer.) |
| Public property | IsAlive | Gets a value indicating whether is alive. (Overrides WoWUnit.IsAlive.). (Inherited from WoWPlayer.) |
| Public property | IsAlliance | Gets a value indicating whether is alliance. (Inherited from WoWPlayer.) |
| Public property | IsCaster | Gets a value indicating whether is caster. (Inherited from WoWPlayer.) |
| Public property | IsDNDFlagged | Gets a value indicating whether is dnd flagged. (Inherited from WoWPlayer.) |
| Public property | IsDueling | Returns true if this player is currently in a duel. (Inherited from WoWPlayer.) |
| Public property | IsFFAPvPFlagged | Gets a value indicating whether is ffa pv p flagged. (Inherited from WoWPlayer.) |
| Public property | IsFemale | Gets a value indicating whether is female. (Inherited from WoWPlayer.) |
| Public property | IsGM | Gets a value indicating whether is gm. (Inherited from WoWPlayer.) |
| Public property | IsGroupLeader | Gets a value indicating whether is group leader. (Inherited from WoWPlayer.) |
| Public property | IsHealer | Gets a value indicating whether is healer. (Inherited from WoWPlayer.) |
| Public property | IsHidingCloak | Gets a value indicating whether is hiding cloak. (Inherited from WoWPlayer.) |
| Public property | IsHidingHelm | Gets a value indicating whether is hiding helm. (Inherited from WoWPlayer.) |
| Public property | IsHorde | Gets a value indicating whether is horde. (Inherited from WoWPlayer.) |
| Public property | IsInMyParty | Whether this player is in the local player's party (not including self). (Inherited from WoWPlayer.) |
| Public property | IsInMyPartyOrRaid | Whether this player is in the local player's party or raid. (Inherited from WoWPlayer.) |
| Public property | IsInMyRaid | Whether this player is in the local player's raid (not including self). (Inherited from WoWPlayer.) |
| Public property | IsInsideSanctuary | Gets a value indicating whether is inside sanctuary. (Inherited from WoWPlayer.) |
| Public property | IsMale | Gets a value indicating whether is male. (Inherited from WoWPlayer.) |
| Public property | IsMelee | Gets a value indicating whether is melee. (Inherited from WoWPlayer.) |
| Public property | IsOutOfBounds | Gets a value indicating whether is out of bounds. (Inherited from WoWPlayer.) |
| Public property | IsPvPFlagged | Gets a value indicating whether is pv p flagged. (Inherited from WoWPlayer.) |
| Public property | IsPvPTimerActive | Gets a value indicating whether is pv p timer active. (Inherited from WoWPlayer.) |
| Public property | IsResting | Gets a value indicating whether is resting. (Inherited from WoWPlayer.) |
| Public property | IsTank | Gets a value indicating whether is tank. (Inherited from WoWPlayer.) |
| Public property | IsTrackingStealthed | Whether the player is tracking stealthed units (bit 1 of PlayerFieldBytes byte 0). (Inherited from WoWPlayer.) |
| Public property | LevelFraction | Gets the level fraction. (Inherited from WoWPlayer.) |
| Public property | LifetimeHonorableKills | Lifetime honorable kills (PLAYER_FIELD_LIFETIME_HONORABLE_KILLS). (Inherited from WoWPlayer.) |
| Public property | Mainhand | Gets the mainhand. (Inherited from WoWPlayer.) |
| Public property | MainhandEntryId | Gets the mainhand entry id. (Inherited from WoWPlayer.) |
| Public property | Mastery | Mastery rating (Cataclysm+ only). Always 0 in WotLK. (Inherited from WoWPlayer.) |
| Public property | MasteryPercent | Mastery percent (Cataclysm+ only). Always 0 in WotLK. (Inherited from WoWPlayer.) |
| Public property | MaxLevel | Max level (80 in WotLK). (Inherited from WoWPlayer.) |
| Public property | Minions | Gets all minions (pets, totems, etc.) controlled by this player. Excludes non-combat pets. (Inherited from WoWPlayer.) |
| Public property | Mounted | Gets a value indicating whether mounted. (Overrides WoWUnit.Mounted.). (Inherited from WoWPlayer.) |
| Public property | NatureBonusNegative | Nature bonus damage (negative). (Inherited from WoWPlayer.) |
| Public property | NatureBonusPercent | Nature bonus damage percent. (Inherited from WoWPlayer.) |
| Public property | NatureBonusPositive | Nature bonus damage (positive). (Inherited from WoWPlayer.) |
| Public property | NatureCritPercent | Nature spell crit percentage. (Inherited from WoWPlayer.) |
| Public property | NextLevelExperience | Gets the next level experience. (Inherited from WoWPlayer.) |
| Public property | NextLevelXP | Gets the next level xp. (Inherited from WoWPlayer.) |
| Public property | OffHandCritPercent | Off-hand crit percentage (PLAYER_OFFHAND_CRIT_PERCENTAGE). (Inherited from WoWPlayer.) |
| Public property | OffHandExpertise | Off-hand expertise rating (PLAYER_OFFHAND_EXPERTISE). (Inherited from WoWPlayer.) |
| Public property | Offhand | Gets the offhand. (Inherited from WoWPlayer.) |
| Public property | OffhandEntryId | Gets the offhand entry id. (Inherited from WoWPlayer.) |
| Public property | ParryPercent | Parry chance percentage (PLAYER_PARRY_PERCENTAGE). (Inherited from WoWPlayer.) |
| Public property | PetSpellPower | Pet spell power scaling for hunter/warlock pets (PLAYER_PET_SPELL_POWER). (Inherited from WoWPlayer.) |
| Public property | PhysicalBonusNegative | Physical bonus damage (negative, school 0). (Inherited from WoWPlayer.) |
| Public property | PhysicalBonusPositive | Physical bonus damage (positive, school 0). (Inherited from WoWPlayer.) |
| Public property | PhysicalCritPercent | Physical spell crit percentage (school 0). (Inherited from WoWPlayer.) |
| Public property | PvpMedalCount | PvP medal count (PLAYER_FIELD_PVP_MEDALS). (Inherited from WoWPlayer.) |
| Public property | RangedCritPercent | Ranged crit chance percentage (PLAYER_RANGED_CRIT_PERCENTAGE). (Inherited from WoWPlayer.) |
| Public property | ReleaseTimerIsVisible | Whether the corpse release timer is visible (bit 3 of PlayerFieldBytes byte 0). (Inherited from WoWPlayer.) |
| Public property | Resilience | Resilience rating (index 14 = CR_CRIT_TAKEN_MELEE, base resilience in WotLK). (Inherited from WoWPlayer.) |
| Public property | RestedExperience | Rested XP amount (PLAYER_REST_STATE_EXPERIENCE). (Inherited from WoWPlayer.) |
| Public property | RuneRegen | DK rune regeneration rates (4 floats, PLAYER_RUNE_REGEN_1). (Inherited from WoWPlayer.) |
| Public property | SelfResurrectSpellId | Self-resurrection spell ID (e.g., Soulstone, Ankh). 0 = none. (Inherited from WoWPlayer.) |
| Public property | ShadowBonusNegative | Shadow bonus damage (negative). (Inherited from WoWPlayer.) |
| Public property | ShadowBonusPercent | Shadow bonus damage percent. (Inherited from WoWPlayer.) |
| Public property | ShadowBonusPositive | Shadow bonus damage (positive). (Inherited from WoWPlayer.) |
| Public property | ShadowCritPercent | Shadow spell crit percentage. (Inherited from WoWPlayer.) |
| Public property | ShieldBlock | Shield block value (PLAYER_SHIELD_BLOCK). (Inherited from WoWPlayer.) |
| Public property | ShieldBlockCritPercent | Shield block crit percentage (PLAYER_SHIELD_BLOCK_CRIT_PERCENTAGE). (Inherited from WoWPlayer.) |
| Public property | Silver | Total money expressed in silver. HB 3.3.5a/4.3.4: Coinage / 100. (Inherited from WoWPlayer.) |
| Public property | Skin | Skin color/type (byte 0 of PLAYER_BYTES). (Inherited from WoWPlayer.) |
| Public property | SpellPowerModifierPercent | Spell power modifier percent (Cata+ only, does not exist in WotLK). Always 1.0f. (Inherited from WoWPlayer.) |
| Public property | TargetArmorModifier | Armor modifier vs target (PLAYER_FIELD_MOD_TARGET_PHYSICAL_RESISTANCE). (Inherited from WoWPlayer.) |
| Public property | TargetResistanceModifier | Spell power modifier vs target (PLAYER_FIELD_MOD_TARGET_RESISTANCE). (Inherited from WoWPlayer.) |
| Public property | Type | Gets the type. (Overrides WoWObject.Type.). (Inherited from WoWPlayer.) |
| Public property | WatchedFactionIndex | Watched faction index (PLAYER_FIELD_WATCHED_FACTION_INDEX). (Inherited from WoWPlayer.) |
| Public property | XP | Gets the xp. (Inherited from WoWPlayer.) |
| Public property | ActiveAuras | Gets the active auras. (Inherited from WoWUnit.) |
| Public property | Aggro | Gets a value indicating whether aggro. (Inherited from WoWUnit.) |
| Public property | Agility | Gets the agility. (Inherited from WoWUnit.) |
| Public property | AgilityBonus | Gets the agility bonus. (Inherited from WoWUnit.) |
| Public property | AgilityNegativeModifier | FEAT-25: Negative agility modifier (UNIT_FIELD_NEGSTAT1). (Inherited from WoWUnit.) |
| Public property | ArcaneResist | Gets the arcane resist. (Inherited from WoWUnit.) |
| Public property | Armor | Gets the armor. (Inherited from WoWUnit.) |
| Public property | AttackPower | Melee attack power (UNIT_FIELD_ATTACK_POWER). (Inherited from WoWUnit.) |
| Public property | AttackPowerMods | Melee attack power modifiers (UNIT_FIELD_ATTACK_POWER_MODS). (Inherited from WoWUnit.) |
| Public property | AttackPowerMultiplier | Melee attack power multiplier (UNIT_FIELD_ATTACK_POWER_MULTIPLIER). (Inherited from WoWUnit.) |
| Public property | Attackable | Gets a value indicating whether attackable. (Inherited from WoWUnit.) |
| Public property | AuraState | Aura state flags (UNIT_FIELD_AURASTATE). (Inherited from WoWUnit.) |
| Public property | Auras | Gets the auras. (Inherited from WoWUnit.) |
| Public property | BaseAttackTime | Base main-hand attack time in ms (UNIT_FIELD_BASEATTACKTIME). (Inherited from WoWUnit.) |
| Public property | BaseHealth | Base health before modifiers (UNIT_FIELD_BASE_HEALTH). (Inherited from WoWUnit.) |
| Public property | BaseMana | Gets the base mana. (Inherited from WoWUnit.) |
| Public property | BaseOffHandAttackTime | Base off-hand attack time in ms (UNIT_FIELD_BASEATTACKTIME + 1). (Inherited from WoWUnit.) |
| Public property | BaseRangedAttackTime | Base ranged attack time in ms (UNIT_FIELD_RANGEDATTACKTIME). (Inherited from WoWUnit.) |
| Public property | BehindTarget | Gets a value indicating whether behind target. (Inherited from WoWUnit.) |
| Public property | BoundingHeight | Gets the bounding height. (Inherited from WoWUnit.) |
| Public property | BoundingRadius | Gets the bounding radius. (Inherited from WoWUnit.) |
| Public property | Buffs | Gets the buffs. (Inherited from WoWUnit.) |
| Public property | CanGossip | Gets a value indicating whether can gossip. (Inherited from WoWUnit.) |
| Public property | CanInterruptCurrentSpellCast | Returns true if this unit's current cast can be interrupted. Checks both IsCasting and Interruptible flag. (Inherited from WoWUnit.) |
| Public property | CanLoot | Gets a value indicating whether can loot. (Inherited from WoWUnit.) |
| Public property | CanSelect | Gets a value indicating whether can select. (Inherited from WoWUnit.) |
| Public property | CanSkin | Gets a value indicating whether can skin. (Inherited from WoWUnit.) |
| Public property | CastSpeedModifier | Cast speed multiplier (UNIT_MOD_CAST_SPEED). 1.0 = normal. (Inherited from WoWUnit.) |
| Public property | Casting | Gets the spell ID being cast or channeled. Returns CastingSpellId if casting, otherwise ChannelSpellId. (Inherited from WoWUnit.) |
| Public property | CastingChanneledId | Gets the spell ID currently being channeled. Returns 0 if not channeling. Offset: BaseAddress + 2688 (WoW 3.3.5a build 12340). (Inherited from WoWUnit.) |
| Public property | CastingSpell | Gets the spell currently being cast (regular cast only). (Inherited from WoWUnit.) |
| Public property | CastingSpellId | Gets the spell ID currently being cast or channeled (combined). HB 4.3.4: returns NonChanneledCastingSpellId if != 0, else ChanneledCastingSpellId. (Inherited from WoWUnit.) |
| Public property | ChannelObject | Gets the WoW object being channeled on. Returns null if not channeling on an object. (Inherited from WoWUnit.) |
| Public property | ChannelObjectGuid | Gets the GUID of the object being channeled on. Used for spells like Mind Control that channel on a target. (Inherited from WoWUnit.) |
| Public property | ChannelSpell | Gets the spell currently being channeled. (Inherited from WoWUnit.) |
| Public property | ChannelSpellId | Alias for CastingChanneledId for consistency. (Inherited from WoWUnit.) |
| Public property | ChannelTimeLeft | FEAT-23: Alias for CurrentChannelTimeLeft — HB 4.3.4 compatibility. (Inherited from WoWUnit.) |
| Public property | ChanneledCasting | Gets the channeled casting. (Inherited from WoWUnit.) |
| Public property | ChanneledCastingSpell | FEAT-23: Gets the WoWSpell being channeled (typed version of ChanneledCastingSpellId). (Inherited from WoWUnit.) |
| Public property | ChanneledCastingSpellId | Alias for ChannelSpellId - HB 4.3.4 compatibility. (Inherited from WoWUnit.) |
| Public property | Charmed | Gets the charmed. (Inherited from WoWUnit.) |
| Public property | CharmedBy | Gets the charmed by. (Inherited from WoWUnit.) |
| Public property | CharmedByGuid | Gets the charmed by guid. (Inherited from WoWUnit.) |
| Public property | CharmedUnit | Gets the charmed unit. (Inherited from WoWUnit.) |
| Public property | CharmedUnitGuid | Gets the charmed unit guid. (Inherited from WoWUnit.) |
| Public property | Class | Gets the class. (Inherited from WoWUnit.) |
| Public property | Combat | Gets a value indicating whether combat. (Inherited from WoWUnit.) |
| Public property | CombatReach | Gets the combat reach. (Inherited from WoWUnit.) |
| Public property | ControllingPlayer | Gets the controlling player for this unit. Walks the charm/summon chain up to 2 levels to find a player controller. (Inherited from WoWUnit.) |
| Public property | CreatedBy | Gets the created by. (Inherited from WoWUnit.) |
| Public property | CreatedByGuid | Gets the created by guid. (Inherited from WoWUnit.) |
| Public property | CreatedBySpellId | Gets the created by spell id. (Inherited from WoWUnit.) |
| Public property | CreatureRank | Gets the creature rank. (Inherited from WoWUnit.) |
| Public property | CreatureType | Gets the creature type. (Inherited from WoWUnit.) |
| Public property | Critter | Gets the critter. (Inherited from WoWUnit.) |
| Public property | CurrentCastTime | Gets the total cast time of the current spell being cast. Uses WoWSpell.CastTime which comes from spell DBC data. (Inherited from WoWUnit.) |
| Public property | CurrentCastTimeLeft | Gets the time remaining on the current cast via Lua UnitCastingInfo. BUG-25: Works for player/target/focus via Lua unitId mapping. Returns TimeSpan.Zero for units without a known unitId. (Inherited from WoWUnit.) |
| Public property | CurrentCastingSpell | Gets the spell being cast or channeled (whichever is active). (Inherited from WoWUnit.) |
| Public property | CurrentChannelTimeLeft | FEAT-23: Gets the remaining time on the current channel via Lua UnitChannelInfo. Returns TimeSpan.Zero for units without a known unitId. (Inherited from WoWUnit.) |
| Public property | CurrentEclipse | Eclipse power (Cataclysm+ only). Always 0 in WotLK. (Inherited from WoWUnit.) |
| Public property | CurrentEnergy | Gets the current energy. (Inherited from WoWUnit.) |
| Public property | CurrentFocus | Gets the current focus. (Inherited from WoWUnit.) |
| Public property | CurrentHappiness | Gets the current happiness. (Inherited from WoWUnit.) |
| Public property | CurrentHealth | Gets the current health. (Inherited from WoWUnit.) |
| Public property | CurrentHolyPower | Holy Power (Cataclysm+ only). Always 0 in WotLK. (Inherited from WoWUnit.) |
| Public property | CurrentMana | Gets the current mana. (Inherited from WoWUnit.) |
| Public property | CurrentPower | Gets the current power. (Inherited from WoWUnit.) |
| Public property | CurrentPowerInfo | Gets the current power info. (Inherited from WoWUnit.) |
| Public property | CurrentRage | Gets the current rage. (Inherited from WoWUnit.) |
| Public property | CurrentRunicPower | Gets the current runic power. (Inherited from WoWUnit.) |
| Public property | CurrentSoulShards | Soul Shards (Cataclysm+ only). Always 0 in WotLK. (Inherited from WoWUnit.) |
| Public property | CurrentTarget | Gets the current target. (Inherited from WoWUnit.) |
| Public property | CurrentTargetGuid | Gets the current target guid. (Inherited from WoWUnit.) |
| Public property | Dazed | Gets a value indicating whether dazed. (Inherited from WoWUnit.) |
| Public property | Dead | Gets a value indicating whether dead. (Inherited from WoWUnit.) |
| Public property | Debuffs | Gets the debuffs. (Inherited from WoWUnit.) |
| Public property | Difficulty | Simplified difficulty color calculation similar to HB. Determines how close the mob's level is to the player. (Inherited from WoWUnit.) |
| Public property | Disarmed | Gets a value indicating whether disarmed. (Inherited from WoWUnit.) |
| Public property | DisplayFlags | Gets the display flags. (Inherited from WoWUnit.) |
| Public property | DisplayId | Gets the display id. (Inherited from WoWUnit.) |
| Public property | EclipseInfo | Gets the eclipse info. (Inherited from WoWUnit.) |
| Public property | EclipsePercent | Gets the eclipse percent. (Inherited from WoWUnit.) |
| Public property | Elite | Gets a value indicating whether elite. (Inherited from WoWUnit.) |
| Public property | EnergyInfo | Convenience: EnergyInfo. (Inherited from WoWUnit.) |
| Public property | EnergyPercent | Gets the energy percentage (0-100). Used by Rogues, Feral Druids. (Inherited from WoWUnit.) |
| Public property | Faction | HB 4.3.4 WoWUnit.Faction — returns the WoWFaction for this unit's FactionId. (Inherited from WoWUnit.) |
| Public property | FactionId | Gets the faction id. (Inherited from WoWUnit.) |
| Public property | FactionTemplate | Gets the faction template. (Inherited from WoWUnit.) |
| Public property | FeignDeathed | Gets a value indicating whether feign deathed. (Inherited from WoWUnit.) |
| Public property | FireResist | Gets the fire resist. (Inherited from WoWUnit.) |
| Public property | Fleeing | Gets a value indicating whether fleeing. (Inherited from WoWUnit.) |
| Public property | FocusInfo | Convenience: FocusInfo. (Inherited from WoWUnit.) |
| Public property | FocusPercent | Convenience: Focus percentage (hunter pet). (Inherited from WoWUnit.) |
| Public property | FrostResist | Gets the frost resist. (Inherited from WoWUnit.) |
| Public property | Gender | Gets the gender. (Inherited from WoWUnit.) |
| Public property | GotAlivePet | Gets a value indicating whether got alive pet. (Inherited from WoWUnit.) |
| Public property | GotTarget | Gets a value indicating whether got target. (Inherited from WoWUnit.) |
| Public property | HappinessInfo | Convenience: HappinessInfo. (Inherited from WoWUnit.) |
| Public property | HappinessPercent | Gets pet happiness percentage (HB 4.3.4 compatibility). WotLK feature - pets have happiness. (Inherited from WoWUnit.) |
| Public property | HealthPercent | Gets the health percent. (Inherited from WoWUnit.) |
| Public property | HolyPowerInfo | Gets the holy power info. (Inherited from WoWUnit.) |
| Public property | HolyPowerPercent | Gets the holy power percent. (Inherited from WoWUnit.) |
| Public property | HolyResist | Gets the holy resist. (Inherited from WoWUnit.) |
| Public property | HoverHeight | Hover offset above ground (UNIT_FIELD_HOVERHEIGHT). (Inherited from WoWUnit.) |
| Public property | InLineOfSight | Whether this unit is in line of sight from the player. Uses GetTraceLinePos() for eye-level raycast on both ends. Ported from HB 4.3.4 WoWUnit — overrides WoWObject base. (Overrides WoWObject.InLineOfSight.). (Inherited from WoWUnit.) |
| Public property | InLineOfSpellSight | Whether this unit is in line of spell sight from the player. Ported from HB 4.3.4. (Inherited from WoWUnit.) |
| Public property | Intellect | Gets the intellect. (Inherited from WoWUnit.) |
| Public property | IntellectBonus | Gets the intellect bonus. (Inherited from WoWUnit.) |
| Public property | IntellectNegativeModifier | FEAT-25: Negative intellect modifier (UNIT_FIELD_NEGSTAT3). (Inherited from WoWUnit.) |
| Public property | IsAmmoVendor | Gets a value indicating whether is ammo vendor. (Inherited from WoWUnit.) |
| Public property | IsAnyTrainer | Gets a value indicating whether is any trainer. (Inherited from WoWUnit.) |
| Public property | IsAnyVendor | Gets a value indicating whether is any vendor. (Inherited from WoWUnit.) |
| Public property | IsAuctioneer | Gets a value indicating whether is auctioneer. (Inherited from WoWUnit.) |
| Public property | IsAutoAttacking | Gets a value indicating whether is auto attacking. (Inherited from WoWUnit.) |
| Public property | IsBanker | Gets a value indicating whether is banker. (Inherited from WoWUnit.) |
| Public property | IsBattleMaster | Gets a value indicating whether is battle master. (Inherited from WoWUnit.) |
| Public property | IsBeast | Gets a value indicating whether is beast. (Inherited from WoWUnit.) |
| Public property | IsBoss | Gets whether this unit is a boss (level cranked or rare elite). (Inherited from WoWUnit.) |
| Public property | IsCasting | Returns true if the unit is currently casting or channeling a spell. (Inherited from WoWUnit.) |
| Public property | IsChanneling | Returns true if the unit is currently channeling a spell. (Inherited from WoWUnit.) |
| Public property | IsClassTrainer | Gets a value indicating whether is class trainer. (Inherited from WoWUnit.) |
| Public property | IsCritter | Gets a value indicating whether is critter. (Inherited from WoWUnit.) |
| Public property | IsCrowdControlled | Whether this unit is under a crowd control effect (stun, polymorph, fear, sap, etc.). (Inherited from WoWUnit.) |
| Public property | IsDead | Returns true if the unit is dead. From HB 5.4.8+ Checks health, and for non-players also checks the Dead dynamic flag. (Inherited from WoWUnit.) |
| Public property | IsDemon | Gets a value indicating whether is demon. (Inherited from WoWUnit.) |
| Public property | IsDragon | Gets a value indicating whether is dragon. (Inherited from WoWUnit.) |
| Public property | IsDragonkin | FEAT-15: Alias for IsDragon — HB 4.3.4 API compatibility. (Inherited from WoWUnit.) |
| Public property | IsElemental | Gets a value indicating whether is elemental. (Inherited from WoWUnit.) |
| Public property | IsExotic | Gets a value indicating whether is exotic. (Inherited from WoWUnit.) |
| Public property | IsFalling | Gets a value indicating whether is falling. (Inherited from WoWUnit.) |
| Public property | IsFlightMaster | Gets a value indicating whether is flight master. (Inherited from WoWUnit.) |
| Public property | IsFlying | Gets a value indicating whether is flying. (Inherited from WoWUnit.) |
| Public property | IsFoodVendor | Gets a value indicating whether is food vendor. (Inherited from WoWUnit.) |
| Public property | IsFriendly | Gets a value indicating whether is friendly. (Inherited from WoWUnit.) |
| Public property | IsGasCloud | FEAT-22: Whether this creature is a gas cloud (extractable with engineering). (Inherited from WoWUnit.) |
| Public property | IsGhostVisible | Gets a value indicating whether is ghost visible. (Inherited from WoWUnit.) |
| Public property | IsGiant | Gets a value indicating whether is giant. (Inherited from WoWUnit.) |
| Public property | IsGuard | Gets a value indicating whether is guard. (Inherited from WoWUnit.) |
| Public property | IsGuildBanker | Gets a value indicating whether is guild banker. (Inherited from WoWUnit.) |
| Public property | IsHostile | Gets a value indicating whether is hostile. (Inherited from WoWUnit.) |
| Public property | IsHumanoid | Gets a value indicating whether is humanoid. (Inherited from WoWUnit.) |
| Public property | IsInnkeeper | Gets a value indicating whether is innkeeper. (Inherited from WoWUnit.) |
| Public property | IsMechanical | Gets a value indicating whether is mechanical. (Inherited from WoWUnit.) |
| Public property | IsMoving | Whether the unit is currently moving. Uses MovementInfo.IsMoving which checks movement flags (HB 4.3.4 style). (Inherited from WoWUnit.) |
| Public property | IsNeutral | Gets a value indicating whether is neutral. (Inherited from WoWUnit.) |
| Public property | IsNonCombatPet | Gets a value indicating whether is non combat pet. (Inherited from WoWUnit.) |
| Public property | IsOnTransport | Gets a value indicating whether is on transport. (Inherited from WoWUnit.) |
| Public property | IsPet | BUG-08 fix: Check GUID instead of expensive ObjectManager lookup. HB 4.3.4 checks both SummonedByGuid and CharmedByGuid. (Inherited from WoWUnit.) |
| Public property | IsPetitioner | Gets a value indicating whether is petitioner. (Inherited from WoWUnit.) |
| Public property | IsPlayer | Gets a value indicating whether is player. (Inherited from WoWUnit.) |
| Public property | IsPlayerBehind | Gets a value indicating whether is player behind. (Inherited from WoWUnit.) |
| Public property | IsPoisonVendor | Gets a value indicating whether is poison vendor. (Inherited from WoWUnit.) |
| Public property | IsProfessionTrainer | Gets a value indicating whether is profession trainer. (Inherited from WoWUnit.) |
| Public property | IsQuestGiver | Gets a value indicating whether is quest giver. (Inherited from WoWUnit.) |
| Public property | IsReagentVendor | Gets a value indicating whether is reagent vendor. (Inherited from WoWUnit.) |
| Public property | IsRepairMerchant | Gets a value indicating whether is repair merchant. (Inherited from WoWUnit.) |
| Public property | IsSpiritGuide | Gets a value indicating whether is spirit guide. (Inherited from WoWUnit.) |
| Public property | IsSpiritHealer | Gets a value indicating whether is spirit healer. (Inherited from WoWUnit.) |
| Public property | IsStableMaster | Gets a value indicating whether is stable master. (Inherited from WoWUnit.) |
| Public property | IsSwimming | Gets a value indicating whether is swimming. (Inherited from WoWUnit.) |
| Public property | IsTabardDesigner | Gets a value indicating whether is tabard designer. (Inherited from WoWUnit.) |
| Public property | IsTameable | Gets a value indicating whether is tameable. (Inherited from WoWUnit.) |
| Public property | IsTargetingAnyMinion | HB 4.3.4 compatible helper – returns true when any of the player's minions (pets) is currently targeting this unit. Used by Targeting filters to keep attackers on the list even if their Aggro flag hasn't flipped yet. (Inherited from WoWUnit.) |
| Public property | IsTargetingMe | Gets a value indicating whether is targeting me. (Inherited from WoWUnit.) |
| Public property | IsTargetingMeOrPet | Gets a value indicating whether is targeting me or pet. (Inherited from WoWUnit.) |
| Public property | IsTargetingMyPartyMember | Gets a value indicating whether is targeting my party member. (Inherited from WoWUnit.) |
| Public property | IsTargetingMyRaidMember | Gets a value indicating whether is targeting my raid member. (Inherited from WoWUnit.) |
| Public property | IsTargetingPet | Gets a value indicating whether is targeting pet. (Inherited from WoWUnit.) |
| Public property | IsTotem | Gets a value indicating whether is totem. (Inherited from WoWUnit.) |
| Public property | IsTrainer | Gets a value indicating whether is trainer. (Inherited from WoWUnit.) |
| Public property | IsUndead | Gets a value indicating whether is undead. (Inherited from WoWUnit.) |
| Public property | IsUnit | Gets a value indicating whether is unit. (Inherited from WoWUnit.) |
| Public property | IsVendor | Gets a value indicating whether is vendor. (Inherited from WoWUnit.) |
| Public property | IsWithinMeleeRange | Returns true if this unit is within melee range of the player. (Inherited from WoWUnit.) |
| Public property | KilledByMe | Gets a value indicating whether killed by me. (Inherited from WoWUnit.) |
| Public property | Level | Gets the level. (Inherited from WoWUnit.) |
| Public property | Location | Gets the location. (Overrides WoWObject.Location.). (Inherited from WoWUnit.) |
| Public property | Lootable | Gets a value indicating whether lootable. (Inherited from WoWUnit.) |
| Public property | Looting | Gets a value indicating whether looting. (Inherited from WoWUnit.) |
| Public property | ManaInfo | Convenience: ManaInfo. (Inherited from WoWUnit.) |
| Public property | ManaPercent | Gets the mana percent. (Inherited from WoWUnit.) |
| Public property | MaxDamage | Max melee damage (UNIT_FIELD_MAXDAMAGE). (Inherited from WoWUnit.) |
| Public property | MaxEclipse | Max Eclipse (Cataclysm+ only). Always 0 in WotLK. (Inherited from WoWUnit.) |
| Public property | MaxEnergy | Gets the max energy. (Inherited from WoWUnit.) |
| Public property | MaxFocus | Gets the max focus. (Inherited from WoWUnit.) |
| Public property | MaxHappiness | Gets the max happiness. (Inherited from WoWUnit.) |
| Public property | MaxHealth | Gets the max health. (Inherited from WoWUnit.) |
| Public property | MaxHealthModifier | Health multiplier (UNIT_FIELD_MAXHEALTHMODIFIER). (Inherited from WoWUnit.) |
| Public property | MaxHolyPower | Max Holy Power (Cataclysm+ only). Always 0 in WotLK. (Inherited from WoWUnit.) |
| Public property | MaxMana | Gets the max mana. (Inherited from WoWUnit.) |
| Public property | MaxOffHandDamage | Max off-hand damage (UNIT_FIELD_MAXOFFHANDDAMAGE). (Inherited from WoWUnit.) |
| Public property | MaxPower | Gets the max power. (Inherited from WoWUnit.) |
| Public property | MaxRage | Gets the max rage. (Inherited from WoWUnit.) |
| Public property | MaxRangedDamage | Max ranged damage (UNIT_FIELD_MAXRANGEDDAMAGE). (Inherited from WoWUnit.) |
| Public property | MaxRunicPower | Gets the max runic power. (Inherited from WoWUnit.) |
| Public property | MaxSoulShards | Max Soul Shards (Cataclysm+ only). Always 0 in WotLK. (Inherited from WoWUnit.) |
| Public property | MeleeReach | Gets the melee reach for this unit. Special cases for certain NPCs, otherwise CombatReach + 2. (Inherited from WoWUnit.) |
| Public property | MinDamage | Min melee damage (UNIT_FIELD_MINDAMAGE). (Inherited from WoWUnit.) |
| Public property | MinOffHandDamage | Min off-hand damage (UNIT_FIELD_MINOFFHANDDAMAGE). (Inherited from WoWUnit.) |
| Public property | MinRangedDamage | Min ranged damage (UNIT_FIELD_MINRANGEDDAMAGE). (Inherited from WoWUnit.) |
| Public property | MountDisplayId | Gets the mount display id. (Inherited from WoWUnit.) |
| Public property | MovementFlags | Gets the movement flags. (Inherited from WoWUnit.) |
| Public property | MovementInfo | Movement information for this unit. Alias for WoWMovementInfo for HB 4.3.4 compatibility. (Inherited from WoWUnit.) |
| Public property | MyAggroRange | Gets the my aggro range. (Inherited from WoWUnit.) |
| Public property | MyReaction | Gets the my reaction. (Inherited from WoWUnit.) |
| Public property | MyStealthDetectionRange | Gets the my stealth detection range. (Inherited from WoWUnit.) |
| Public property | NativeDisplayId | FEAT-13: Native (original) display ID before model changes (UNIT_FIELD_NATIVEDISPLAYID). (Inherited from WoWUnit.) |
| Public property | NatureResist | Gets the nature resist. (Inherited from WoWUnit.) |
| Public property | NonChanneledCastingSpellId | Returns the raw non-channeled casting spell ID (offset 2668). HB 4.3.4 compatibility — reads only the non-channeled cast. (Inherited from WoWUnit.) |
| Public property | NpcEmoteState | NPC emote state (UNIT_NPC_EMOTESTATE). (Inherited from WoWUnit.) |
| Public property | OnTaxi | Gets a value indicating whether on taxi. (Inherited from WoWUnit.) |
| Public property | OwnedByRoot | Gets the owned by root. (Inherited from WoWUnit.) |
| Public property | OwnedByUnit | Gets the owned by unit. (Inherited from WoWUnit.) |
| Public property | Pacified | Gets a value indicating whether pacified. (Inherited from WoWUnit.) |
| Public property | PassiveAuras | Gets the passive auras. (Inherited from WoWUnit.) |
| Public property | PetAggro | Gets a value indicating whether pet aggro. (Inherited from WoWUnit.) |
| Public property | PetExperience | Pet XP (UNIT_FIELD_PETEXPERIENCE). (Inherited from WoWUnit.) |
| Public property | PetInCombat | Gets a value indicating whether pet in combat. (Inherited from WoWUnit.) |
| Public property | PetNextLevelExperience | Pet XP to next level (UNIT_FIELD_PETNEXTLEVELEXP). (Inherited from WoWUnit.) |
| Public property | PetNumber | Pet tracking number (UNIT_FIELD_PETNUMBER). (Inherited from WoWUnit.) |
| Public property | PlayerControlled | Gets a value indicating whether player controlled. (Inherited from WoWUnit.) |
| Public property | Possessed | Gets a value indicating whether possessed. (Inherited from WoWUnit.) |
| Public property | PowerType | Gets the power type. (Inherited from WoWUnit.) |
| Public property | PvpFlagged | Gets a value indicating whether pvp flagged. (Inherited from WoWUnit.) |
| Public property | Race | Gets the race. (Inherited from WoWUnit.) |
| Public property | RafLinked | Gets a value indicating whether raf linked. (Inherited from WoWUnit.) |
| Public property | RageInfo | Convenience: RageInfo. (Inherited from WoWUnit.) |
| Public property | RagePercent | Gets the rage percentage (0-100). Used by Warriors. (Inherited from WoWUnit.) |
| Public property | RangedAttackPower | Ranged attack power (UNIT_FIELD_RANGED_ATTACK_POWER). (Inherited from WoWUnit.) |
| Public property | RangedAttackPowerMods | Ranged attack power modifiers (UNIT_FIELD_RANGED_ATTACK_POWER_MODS). (Inherited from WoWUnit.) |
| Public property | RangedAttackPowerMultiplier | Ranged attack power multiplier (UNIT_FIELD_RANGED_ATTACK_POWER_MULTIPLIER). (Inherited from WoWUnit.) |
| Public property | RelativeLocation | Raw transport-local position (from CMovementData). Use Location for world coords. (Inherited from WoWUnit.) |
| Public property | RenderFacing | Gets the render facing. (Inherited from WoWUnit.) |
| Public property | Rooted | Gets a value indicating whether rooted. (Inherited from WoWUnit.) |
| Public property | Rotation | Gets the rotation. (Overrides WoWObject.Rotation.). (Inherited from WoWUnit.) |
| Public property | RunesPercent | Runes percentage (DK). WotLK-valid. (Inherited from WoWUnit.) |
| Public property | RunesPowerInfo | Convenience: RunesPowerInfo (DK). WotLK-valid. (Inherited from WoWUnit.) |
| Public property | RunicPowerInfo | Convenience: RunicPowerInfo. (Inherited from WoWUnit.) |
| Public property | RunicPowerPercent | Gets the runic power percentage (0-100). Used by Death Knights. (Inherited from WoWUnit.) |
| Public property | ShadowResist | Gets the shadow resist. (Inherited from WoWUnit.) |
| Public property | Shapeshift | Gets the shapeshift. (Inherited from WoWUnit.) |
| Public property | Silenced | Gets a value indicating whether silenced. (Inherited from WoWUnit.) |
| Public property | SkinType | Gets the skin type. (Inherited from WoWUnit.) |
| Public property | Skinnable | Gets a value indicating whether skinnable. (Inherited from WoWUnit.) |
| Public property | SoulShardsInfo | Gets the soul shards info. (Inherited from WoWUnit.) |
| Public property | SoulShardsPercent | Gets the soul shards percent. (Inherited from WoWUnit.) |
| Public property | Spirit | Gets the spirit. (Inherited from WoWUnit.) |
| Public property | SpiritBonus | Gets the spirit bonus. (Inherited from WoWUnit.) |
| Public property | SpiritNegativeModifier | FEAT-25: Negative spirit modifier (UNIT_FIELD_NEGSTAT4). (Inherited from WoWUnit.) |
| Public property | Stamina | Gets the stamina. (Inherited from WoWUnit.) |
| Public property | StaminaBonus | Gets the stamina bonus. (Inherited from WoWUnit.) |
| Public property | StaminaNegativeModifier | FEAT-25: Negative stamina modifier (UNIT_FIELD_NEGSTAT2). (Inherited from WoWUnit.) |
| Public property | StateFlag | Gets the state flag. (Inherited from WoWUnit.) |
| Public property | Strength | Gets the strength. (Inherited from WoWUnit.) |
| Public property | StrengthBonus | Gets the strength bonus. (Inherited from WoWUnit.) |
| Public property | StrengthNegativeModifier | FEAT-25: Negative strength modifier (UNIT_FIELD_NEGSTAT0). (Inherited from WoWUnit.) |
| Public property | Stunned | Gets a value indicating whether stunned. (Inherited from WoWUnit.) |
| Public property | SubName | Creature subtitle/guild text from cache. (Inherited from WoWUnit.) |
| Public property | Summon | Gets the summon. (Inherited from WoWUnit.) |
| Public property | SummonedBy | Gets the summoned by. (Inherited from WoWUnit.) |
| Public property | SummonedByGuid | Gets the summoned by guid. (Inherited from WoWUnit.) |
| Public property | SummonedUnit | Gets the summoned unit. (Inherited from WoWUnit.) |
| Public property | SummonedUnitGuid | Gets the summoned unit guid. (Inherited from WoWUnit.) |
| Public property | Tagged | Gets a value indicating whether tagged. (Inherited from WoWUnit.) |
| Public property | TaggedByMe | Gets a value indicating whether tagged by me. (Inherited from WoWUnit.) |
| Public property | TaggedByOther | Gets a value indicating whether tagged by other. (Inherited from WoWUnit.) |
| Public property | TappedByAllThreatLists | Gets a value indicating whether tapped by all threat lists. (Inherited from WoWUnit.) |
| Public property | ThreatInfo | Gets the threat info. (Inherited from WoWUnit.) |
| Public property | Tracked | Gets a value indicating whether tracked. (Inherited from WoWUnit.) |
| Public property | Transport | Gets the transport. (Inherited from WoWUnit.) |
| Public property | VanityPet | Gets the vanity pet. (Inherited from WoWUnit.) |
| Public property | VanityPetGuid | Gets the vanity pet guid. (Inherited from WoWUnit.) |
| Public property | VirtualItemSlotIds | Visual weapon slot IDs (UNIT_VIRTUAL_ITEM_SLOT_ID, 3 entries). (Inherited from WoWUnit.) |
| Public property | WoWMovementInfo | Gets the wow movement info. (Inherited from WoWUnit.) |
| Public property | X | Gets the x. (Overrides WoWObject.X.). (Inherited from WoWUnit.) |
| Public property | Y | Gets the y. (Overrides WoWObject.Y.). (Inherited from WoWUnit.) |
| Public property | Z | Gets the z. (Overrides WoWObject.Z.). (Inherited from WoWUnit.) |
| Public property | BaseAddress | Gets the base address. (Inherited from WoWObject.) |
| Public property | DescriptorGuid | Gets the descriptor guid. (Inherited from WoWObject.) |
| Public property | Distance2D | Gets the distance2d. (Inherited from WoWObject.) |
| Public property | Distance2DSqr | Gets the distance2d sqr. (Inherited from WoWObject.) |
| Public property | Entry | Gets the entry. (Inherited from WoWObject.) |
| Public property | Guid | Gets the guid. (Inherited from WoWObject.) |
| Public property | InLineOfSightOCD | HB 4.3.4 compat — was marked [Obsolete], just delegates to InLineOfSight. External bots (LazyRaider etc.) reference this. (Inherited from WoWObject.) |
| Public property | InteractRangeSqr | FEAT-28: Squared interact range for faster distance checks (avoids sqrt). (Inherited from WoWObject.) |
| Public property | InteractType | Gets the interact type. (Inherited from WoWObject.) |
| Public property | IsDisabled | Gets a value indicating whether is disabled. (Inherited from WoWObject.) |
| Public property | IsUnderground | Gets a value indicating whether is underground. (Inherited from WoWObject.) |
| Public property | IsValid | Gets a value indicating whether is valid. (Inherited from WoWObject.) |
| Public property | MeIsBehind | Gets a value indicating whether me is behind. (Inherited from WoWObject.) |
| Public property | MeIsSafelyBehind | Gets a value indicating whether me is safely behind. (Inherited from WoWObject.) |
| Public property | Name | Gets the name. (Inherited from WoWObject.) |
| Public property | ObjectFlags | Gets the object flags. (Inherited from WoWObject.) |
| Public property | QuestGiverStatus | Gets the quest giver status. (Inherited from WoWObject.) |
| Public property | RotationDegrees | Gets the rotation degrees. (Inherited from WoWObject.) |
| Public property | TypeFlags | Gets the type flags. (Inherited from WoWObject.) |
| Public property | WithinInteractRange | Gets a value indicating whether within interact range. (Inherited from WoWObject.) |
| Public property | WorldLocation | Alias for Location. Matches HB 4.3.4 API surface used by external plugins. (Inherited from WoWObject.) |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | OnInvalidate | Occurs when invalidate. (Inherited from WoWObject.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CanEquipItem(WoWItem)](LocalPlayer/Methods/CanEquipItem_C21C3D93F264.md) | Checks if the player can equip the specified item. |
| Public method | [CanEquipItem(ItemInfo)](LocalPlayer/Methods/CanEquipItem_3CA9B9E54F51.md) | Checks if the player can equip an item with the specified info. |
| Public method | [CanEquipItem(ItemInfo, GameError)](LocalPlayer/Methods/CanEquipItem_D1B8D727D049.md) | Checks if the player can equip an item (with reason output). Calls native CGPlayer_C::CanUseItem at 0x6DC3F0 (7193584) |
| Public method | [CanEquipItem(WoWItem, GameError)](LocalPlayer/Methods/CanEquipItem_775237B1F4B3.md) | Checks if the player can equip the specified item (with reason output). |
| Public method | [CanUseItem(uint)](LocalPlayer/Methods/CanUseItem_F9784ED5E422.md) | FEAT-39: Checks if the player can use an item by entry ID via Lua. |
| Public method | [ClearFocus](LocalPlayer/Methods/ClearFocus_A65562EA5E9B.md) | Clears the current focus target. |
| Public method | [ClearTarget](LocalPlayer/Methods/ClearTarget_F3D36C618CB5.md) | Clears the current target. |
| Public method | [GetAllSkills](LocalPlayer/Methods/GetAllSkills_4E075C80EE99.md) | Gets all known skills. |
| Public method | [GetBag(WoWBagSlot)](LocalPlayer/Methods/GetBag_CCEBA10F376E.md) | Gets the container at the specified bag slot. |
| Public method | [GetBagAtIndex(uint)](LocalPlayer/Methods/GetBagAtIndex_87539FA6CBB6.md) | Gets the container at the specified bag index. |
| Public method | [GetBagGuidAtIndex(uint)](LocalPlayer/Methods/GetBagGuidAtIndex_F401FAE5B9E6.md) | Gets the GUID of the bag at the specified index (0-10). Reads from global bag GUID array at 12727616 + 8 * index. HB 3.3.5a: ObjectManager.Wow.Read<ulong>(12727616U + 8U * index) |
| Public method | [GetEstimatedRepairCost](LocalPlayer/Methods/GetEstimatedRepairCost_F281D20CC7E9.md) | HB 4.3.4: Gets estimated total repair cost. HB 4.3.4 iterates CarriedItems and reads DurabilityCosts[itemLevel].Multiplier[subClassId] from ClientDb. CB does not yet have ClientDb, so we fall back to Lua GetRepairAllCost() which only returns a valid value when at a repair merchant. When ClientDb is implemented, replace with the item-iteration approach. |
| Public method | [GetFactionStanding(WoWFaction, FactionStanding)](LocalPlayer/Methods/GetFactionStanding_81526ECF57FA.md) | Gets faction standing for a faction. |
| Public method | [GetFactionStanding(uint, FactionStanding)](LocalPlayer/Methods/GetFactionStanding_38DA8298669D.md) | Gets faction standing by faction ID. |
| Public method | [GetMirrorTimerInfo(MirrorTimerType)](LocalPlayer/Methods/GetMirrorTimerInfo_58F0CB524D18.md) | Gets the mirror timer info for the specified type (Breath, Fatigue, FeignDeath). Address: 12389248 (0xBD0380) Ported from HB 3.3.5a |
| Public method | [GetPartyMemberGUID(int)](LocalPlayer/Methods/GetPartyMemberGUID_7EF3E6E30FDE.md) | Gets the GUID of a party member by index (0-4). Renamed method - use GetPartyMemberGuid instead. Ported from HB 3.3.5a |
| Public method | [GetPartyMemberGUIDs](LocalPlayer/Methods/GetPartyMemberGUIDs_681C7778F998.md) | Gets all party member GUIDs. |
| Public method | [GetPartyMemberGuid(int)](LocalPlayer/Methods/GetPartyMemberGuid_DC42DC6123CE.md) | Gets the GUID of a party member by index (0-3). Ported from HB 3.3.5a - Address 12392776 (0xBD1DD8) |
| Public method | [GetRaidMember(int)](LocalPlayer/Methods/GetRaidMember_D62CE8E492C7.md) | Gets a raid member by index. Ported from HB 3.3.5a |
| Public method | [GetRaidMemberGUID(int)](LocalPlayer/Methods/GetRaidMemberGUID_961FC79F7BB3.md) | Gets the GUID of a raid member by index (0-39). Renamed method - use GetRaidMemberGuid instead. Ported from HB 3.3.5a |
| Public method | [GetRaidMemberGUIDs](LocalPlayer/Methods/GetRaidMemberGUIDs_F664CD49606E.md) | Gets all raid member GUIDs. |
| Public method | [GetRaidMemberGuid(int)](LocalPlayer/Methods/GetRaidMemberGuid_EC517B3564DC.md) | Gets the GUID of a raid member by index (0-39). Ported from HB 3.3.5a - Address 12498280 (0xBECFC8) |
| Public method | [GetReputationLevelWith(uint)](LocalPlayer/Methods/GetReputationLevelWith_E14D364723BB.md) | FEAT-18: Gets the reputation standing level with a faction. Uses HB 4.3.4 threshold-based approach on raw reputation value. |
| Public method | [GetReputationWith(uint)](LocalPlayer/Methods/GetReputationWith_AA39244F44E8.md) | Gets the raw reputation value with a faction using GetFactionStanding (HB 4.3.4 pattern). |
| Public method | [GetRuneCount(int)](LocalPlayer/Methods/GetRuneCount_2EB03F29457C.md) | Gets the rune count at the specified index (0-5). |
| Public method | [GetRuneCount(RuneType)](LocalPlayer/Methods/GetRuneCount_96FEA0EC486E.md) | Gets the total rune count of a specific type. |
| Public method | [GetRuneType(int)](LocalPlayer/Methods/GetRuneType_5F9A08E3B7AE.md) | Gets the rune type at the specified index (0-5). |
| Public method | [GetSkill(SkillLine)](LocalPlayer/Methods/GetSkill_38837060BB9A.md) | Gets a skill by skill line. |
| Public method | [GetSkill(int)](LocalPlayer/Methods/GetSkill_F66085F315F4.md) | Gets a skill by skill line ID. |
| Public method | [GetSkill(uint)](LocalPlayer/Methods/GetSkill_6C61366B3877.md) | Gets a skill by skill line ID. Scans the player descriptor's skill block at BaseAddress+8 → descriptorBase+0x9F0. |
| Public method | [GetSkill(string)](LocalPlayer/Methods/GetSkill_CB8AFD575A83.md) | Gets skill by name. Ported from HB 3.3.5a |
| Public method | [GetTotemBarSpells(int)](LocalPlayer/Methods/GetTotemBarSpells_414D7349A732.md) | FEAT-39: Gets spells on a totem multi-cast bar for a given totem element. Note: Multi-cast totem bar (Call of the Elements) is Cataclysm+. In WotLK, this returns an empty list. Kept for API compatibility. |
| Public method | [HasPendingSpell(int)](LocalPlayer/Methods/HasPendingSpell_01439A7D0462.md) | Checks if a pending cursor spell matches the given spell ID. |
| Public method | [HasPendingSpell(string)](LocalPlayer/Methods/HasPendingSpell_3A592EE089DE.md) | Checks if a pending cursor spell matches the given spell name. |
| Public method | [HasPendingSpell(WoWSpell)](LocalPlayer/Methods/HasPendingSpell_07B73189FDF3.md) | Checks if a pending cursor spell matches the given WoWSpell. |
| Public method | [IsBehind(WoWUnit)](LocalPlayer/Methods/IsBehind_B8B573628D66.md) | Checks if the specified unit is behind the player. |
| Public method | [SetFacing(WoWUnit)](LocalPlayer/Methods/SetFacing_F62D833533B2.md) | Sets the player's facing towards a unit. |
| Public method | [SetFacing(WoWGameObject)](LocalPlayer/Methods/SetFacing_FD665BD41D9F.md) | Sets the player's facing towards a game object. |
| Public method | [SetFacing(WoWPoint)](LocalPlayer/Methods/SetFacing_ABE9892C91E6.md) | Sets the player's facing towards a point. |
| Public method | [SetFacing(float)](LocalPlayer/Methods/SetFacing_0C10BF06749C.md) | Sets the player's facing to a specific angle (in radians). Uses ClickToMove with Face type like HB 4.3.4 for proper server sync and animation. Adding epsilon (1E-06f) like HB 4.3.4 to prevent precision issues. |
| Public method | [SetFocus(WoWUnit)](LocalPlayer/Methods/SetFocus_FE7EFA39D68A.md) | Sets the focus target by WoWUnit. Returns true on success. HB 4.3.4 pattern: delegates to guid overload. Null clears focus. |
| Public method | [SetFocus(ulong)](LocalPlayer/Methods/SetFocus_E96A6245EB1E.md) | Sets the focus target by GUID. Returns true on success. HB 4.3.4 pattern: writes GUID directly to the focus address in memory. |
| Public method | [TargetLastTarget](LocalPlayer/Methods/TargetLastTarget_CFA8B4987A96.md) | Targets the last target. |
| Public method | [ToggleAttack](LocalPlayer/Methods/ToggleAttack_5BA13E1163BC.md) | Toggles attack on the current target. |
| Public method | GetCombatRating(int) | Gets a combat rating value by index (0-24). (Inherited from WoWPlayer.) |
| Public method | GetGlyph(int) | Gets the glyph spell ID at the specified slot (0-5). (Inherited from WoWPlayer.) |
| Public method | GetGlyphSlot(int) | Gets the glyph slot type at the specified index (0-5). (Inherited from WoWPlayer.) |
| Public method | GetSpellBonusDamageNegative(int) | Gets negative spell bonus damage for the specified school index (0-6). (Inherited from WoWPlayer.) |
| Public method | GetSpellBonusDamagePercent(int) | Gets spell bonus damage percent for the specified school index (0-6). (Inherited from WoWPlayer.) |
| Public method | GetSpellBonusDamagePositive(int) | Gets positive spell bonus damage for the specified school index (0-6). (Inherited from WoWPlayer.) |
| Public method | GetSpellCritPercent(int) | Spell crit percentage for the specified school index (0-6). (Inherited from WoWPlayer.) |
| Public method | Behind(WoWUnit) | Determines whether this unit is behind the specified unit. (Inherited from WoWUnit.) |
| Public method | Distance2DTo(WoWUnit) | Returns the 2D distance to another unit (ignoring Z axis). (Inherited from WoWUnit.) |
| Public method | Face | Faces the target. (Inherited from WoWUnit.) |
| Public method | GetAggroRange(WoWUnit) | Gets the aggro range. (Inherited from WoWUnit.) |
| Public method | GetAllAuras | Gets the all auras. (Inherited from WoWUnit.) |
| Public method | GetAuraById(int) | Gets an aura by its spell ID. (Inherited from WoWUnit.) |
| Public method | GetAuraByName(string) | Gets the aura by name. (Inherited from WoWUnit.) |
| Public method | GetBuffs(bool) | Gets the buffs. (Inherited from WoWUnit.) |
| Public method | GetCachedInfo(CreatureCacheEntry) | Gets the cached info. (Inherited from WoWUnit.) |
| Public method | GetCurrentPower(WoWPowerType) | Gets the current power. (Inherited from WoWUnit.) |
| Protected method | GetLuaUnitId | Maps this unit to a WoW Lua unitId string for API calls. Returns empty string if no known unitId matches this unit. (Inherited from WoWUnit.) |
| Public method | GetMaxPower(WoWPowerType) | Gets the max power. (Inherited from WoWUnit.) |
| Public method | GetPowerCostModifier(WoWPowerType) | Gets the flat power cost modifier for the specified power type. Index into UNIT_FIELD_POWER_COST_MODIFIER (7 entries starting at 0x83). (Inherited from WoWUnit.) |
| Public method | GetPowerCostMultiplier(WoWPowerType) | Gets the percent power cost multiplier for the specified power type. Index into UNIT_FIELD_POWER_COST_MULTIPLIER (7 entries starting at 0x8A). (Inherited from WoWUnit.) |
| Public method | GetPowerInfo(WoWPowerType) | Gets structured power info for the specified power type. (Inherited from WoWUnit.) |
| Public method | GetPowerPercent(WoWPowerType) | Gets the power percent. (Inherited from WoWUnit.) |
| Public method | GetPowerRegenFlat(WoWPowerType) | Gets the flat regen rate for the specified power type. Index into UNIT_FIELD_POWER_REGEN_FLAT_MODIFIER (7 entries starting at 0x28). (Inherited from WoWUnit.) |
| Public method | GetPowerRegenInterrupted(WoWPowerType) | Gets the interrupted (combat) regen rate for the specified power type. Index into UNIT_FIELD_POWER_REGEN_INTERRUPTED_FLAT_MODIFIER (7 entries starting at 0x2F). (Inherited from WoWUnit.) |
| Public method | GetReactionTowards(WoWUnit) | Gets the reaction towards. (Inherited from WoWUnit.) |
| Public method | GetStealthDetectionRange(WoWUnit) | Gets the stealth detection range. (Inherited from WoWUnit.) |
| Public method | GetThreatInfoFor(WoWUnit) | Gets the threat info for. (Inherited from WoWUnit.) |
| Public method | GetTraceLinePos | Gets the trace line pos. (Inherited from WoWUnit.) |
| Public method | GetWorldPosition | Returns the world-space position of this unit. When on a transport (elevator, ship), transforms the transport-local position by the transport's world matrix (read from GO BaseAddress + 0x1A8). Matches HB 3.3.5a's GetWorldPosition(). (Inherited from WoWUnit.) |
| Public method | HasAura(int) | Checks if the unit has an aura with the specified spell ID. (Inherited from WoWUnit.) |
| Public method | HasAura(string) | Determines whether has aura. (Inherited from WoWUnit.) |
| Public method | HasAuraWithMechanic(WoWSpellMechanic) | Checks if the unit has any aura with the specified spell mechanic. (Inherited from WoWUnit.) |
| Public method | HasUnitDynamicFlag(UnitDynamicFlags) | Public method to check if unit has a specific dynamic flag. (Inherited from WoWUnit.) |
| Public method | IsDueling(WoWUnit) | Checks if this unit is dueling another unit. Both units must be player-controlled and have matching duel arbiters but different teams. (Inherited from WoWUnit.) |
| Public method | IsWithinMeleeRangeOf(WoWUnit) | Returns true if this unit is within melee range of another unit. (Inherited from WoWUnit.) |
| Public method | Target | Targets the unit. (Inherited from WoWUnit.) |
| Public method | ToWoWUnit | Converts to wow unit. (Inherited from WoWUnit.) |
| Public method | CompareTo(WoWObject) | Compares the current instance with another object. (Inherited from WoWObject.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from WoWObject.) |
| Public method | Equals(WoWObject) | Determines whether the specified object is equal to the current object. (Inherited from WoWObject.) |
| Protected method | GetDescriptorField(int) | Gets the descriptor field. (Inherited from WoWObject.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from WoWObject.) |
| Public method | GetObjectName | Gets the name of this WoW object from game memory. Uses Executor to call WoW's internal name retrieval function. Based on HB 3.3.5a WoWObject.GetObjectName() implementation. (Inherited from WoWObject.) |
| Public method | GetPosition | Gets the position. (Inherited from WoWObject.) |
| Public method | Interact | Interacts with the object. (Inherited from WoWObject.) |
| Public method | Interact(bool) | Interacts with the object. (Inherited from WoWObject.) |
| Public method | IsBehind(WoWObject) | Determines whether the target is behind. (Inherited from WoWObject.) |
| Public method | IsFacing(WoWObject) | Determines whether the target is facing the point. (Inherited from WoWObject.) |
| Public method | IsFacing(WoWPoint) | Determines whether the target is facing the point. (Inherited from WoWObject.) |
| Public method | IsSafelyBehind(WoWObject) | Determines whether the target is safely behind. (Inherited from WoWObject.) |
| Public method | IsSafelyFacing(WoWObject) | Determines whether the target is safely facing the point. (Inherited from WoWObject.) |
| Public method | IsSafelyFacing(WoWPoint) | Determines whether the target is safely facing the point. (Inherited from WoWObject.) |
| Public method | IsSafelyFacing(WoWObject, float) | Determines whether the target is safely facing the point. (Inherited from WoWObject.) |
| Public method | ToContainer | Converts to container. (Inherited from WoWObject.) |
| Public method | ToDynamicObject | FEAT-28: Cast this object to WoWDynamicObject (e.g., Blizzard, Rain of Fire ground effects). (Inherited from WoWObject.) |
| Public method | ToGameObject | Converts to game object. (Inherited from WoWObject.) |
| Public method | ToItem | Converts to item. (Inherited from WoWObject.) |
| Public method | ToPlayer | Converts to player. (Inherited from WoWObject.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from WoWObject.) |
| Public method | ToUnit | Converts to unit. (Inherited from WoWObject.) |
| Protected method | WriteDescriptor(uint, T) | Writes the descriptor. (Inherited from WoWObject.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
