# WoWPlayer Class

Represents a wow player.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWObject
    Styx.WoWInternals.WoWObjects.WoWUnit
      Styx.WoWInternals.WoWObjects.WoWPlayer

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWPlayer : WoWUnit
```

The WoWPlayer type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWPlayer(uint)](WoWPlayer/Constructors/Constructor_7991E1EB7191.md) | Initializes a new instance of the WoWPlayer class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ArcaneBonusNegative](WoWPlayer/Properties/ArcaneBonusNegative_9C78D10A4537.md) | Arcane bonus damage (negative). |
| Public property | [ArcaneBonusPercent](WoWPlayer/Properties/ArcaneBonusPercent_87E6B9A46BE5.md) | Arcane bonus damage percent. |
| Public property | [ArcaneBonusPositive](WoWPlayer/Properties/ArcaneBonusPositive_3238F90996CE.md) | Arcane bonus damage (positive). |
| Public property | [ArcaneCritPercent](WoWPlayer/Properties/ArcaneCritPercent_5E42A415FA38.md) | Arcane spell crit percentage. |
| Public property | [ArenaCurrency](WoWPlayer/Properties/ArenaCurrency_DFB32F587614.md) | Arena points (PLAYER_FIELD_ARENA_CURRENCY). |
| Public property | [ArmorPenetration](WoWPlayer/Properties/ArmorPenetration_41C5B05A2BAF.md) | Armor penetration rating (index 24 = CR_ARMOR_PENETRATION in WotLK). |
| Public property | [BankBagSlotCount](WoWPlayer/Properties/BankBagSlotCount_89E8D9E70FDB.md) | Number of purchased bank bag slots (byte 2 of PLAYER_BYTES_2, 0x9A). |
| Public property | [BattlefieldArenaFaction](WoWPlayer/Properties/BattlefieldArenaFaction_2F2AD6362D2C.md) | Battlefield arena faction (byte 3 of PLAYER_BYTES_3). |
| Public property | [BlockPercent](WoWPlayer/Properties/BlockPercent_F0580DDF8AA4.md) | Block chance percentage (PLAYER_BLOCK_PERCENTAGE). |
| Public property | [CharacterPoints](WoWPlayer/Properties/CharacterPoints_F3DC8526FDBA.md) | Talent points remaining (PLAYER_CHARACTER_POINTS1). |
| Public property | [CharacterPoints2](WoWPlayer/Properties/CharacterPoints2_F7EAF42F1EFA.md) | Profession points remaining (PLAYER_CHARACTER_POINTS2). |
| Public property | [ChosenTitle](WoWPlayer/Properties/ChosenTitle_801E7E5ACD57.md) | Currently displayed title (PLAYER_CHOSEN_TITLE). |
| Public property | [Coinage](WoWPlayer/Properties/Coinage_1840F8FDC39B.md) | BUG-16: Changed from int to uint to avoid overflow at high gold amounts. WotLK gold cap is ~214k gold = ~2.14 billion copper, fits uint but overflows int. |
| Public property | [ContestedPvPFlagged](WoWPlayer/Properties/ContestedPvPFlagged_943A727ECA61.md) | Gets a value indicating whether contested pv p flagged. |
| Public property | [Copper](WoWPlayer/Properties/Copper_5C74E916155D.md) | Total money expressed in copper (same as Coinage). HB 3.3.5a: Copper == Coinage. HB 4.3.4: Copper reads the raw descriptor. |
| Public property | [CritPercent](WoWPlayer/Properties/CritPercent_0CAD8860CE39.md) | Melee crit chance percentage (PLAYER_CRIT_PERCENTAGE). |
| Public property | [DodgePercent](WoWPlayer/Properties/DodgePercent_5ABA30598734.md) | Dodge chance percentage (PLAYER_DODGE_PERCENTAGE). |
| Public property | [DuelArbiterGuid](WoWPlayer/Properties/DuelArbiterGuid_18E58C61C930.md) | Gets the GUID of the duel arbiter (the flag in the ground during a duel) |
| Public property | [DuelTeam](WoWPlayer/Properties/DuelTeam_EE02ABB97C7F.md) | Gets the player's duel team (0 = not dueling, 1 or 2 = team number) |
| Public property | [Experience](WoWPlayer/Properties/Experience_5F6BDB7FCB66.md) | Gets the experience. |
| Public property | [Expertise](WoWPlayer/Properties/Expertise_11186A106639.md) | Expertise rating (PLAYER_EXPERTISE). |
| Public property | [ExpertiseRating](WoWPlayer/Properties/ExpertiseRating_15AB20ECDB81.md) | Expertise rating (index 23 = CR_EXPERTISE). |
| Public property | [FaceType](WoWPlayer/Properties/FaceType_4438181F2625.md) | Face type (byte 1 of PLAYER_BYTES). |
| Public property | [FacialHair](WoWPlayer/Properties/FacialHair_F183F70979EC.md) | Facial hair style (byte 0 of PLAYER_BYTES_2). |
| Public property | [FireBonusNegative](WoWPlayer/Properties/FireBonusNegative_ED0F326E1F6E.md) | Fire bonus damage (negative). |
| Public property | [FireBonusPercent](WoWPlayer/Properties/FireBonusPercent_2CEB1A1292B7.md) | Fire bonus damage percent. |
| Public property | [FireBonusPositive](WoWPlayer/Properties/FireBonusPositive_6486A785419C.md) | Fire bonus damage (positive). |
| Public property | [FireCritPercent](WoWPlayer/Properties/FireCritPercent_8F727B8053A7.md) | Fire spell crit percentage. |
| Public property | [FrostBonusNegative](WoWPlayer/Properties/FrostBonusNegative_AC2A28AF373E.md) | Frost bonus damage (negative). |
| Public property | [FrostBonusPercent](WoWPlayer/Properties/FrostBonusPercent_15F047E2B01D.md) | Frost bonus damage percent. |
| Public property | [FrostBonusPositive](WoWPlayer/Properties/FrostBonusPositive_D25A4F36A5AB.md) | Frost bonus damage (positive). |
| Public property | [FrostCritPercent](WoWPlayer/Properties/FrostCritPercent_42D64F2EA404.md) | Frost spell crit percentage. |
| Public property | [Glyphs](WoWPlayer/Properties/Glyphs_3F7E4DADD8D2.md) | Returns all 6 glyph slots as a list (WotLK: 3 major + 3 minor). |
| Public property | [GlyphsEnabled](WoWPlayer/Properties/GlyphsEnabled_E5EF71A877C2.md) | Glyph enabled bitmask (PLAYER_GLYPHS_ENABLED). |
| Public property | [Gold](WoWPlayer/Properties/Gold_3FEF106DD875.md) | Gets the gold. |
| Public property | [GuildDeleteDate](WoWPlayer/Properties/GuildDeleteDate_B7B33CD561BA.md) | Guild delete date (Cata+ only). Always 0 in WotLK. |
| Public property | [GuildLevel](WoWPlayer/Properties/GuildLevel_12C1BA548418.md) | Guild level (Cata+ only). Always 0 in WotLK. |
| Public property | [GuildRank](WoWPlayer/Properties/GuildRank_EA8F895A6B84.md) | Guild rank (PLAYER_GUILDRANK). |
| Public property | [GuildTimestamp](WoWPlayer/Properties/GuildTimestamp_0B88A0FEE357.md) | Guild timestamp (PLAYER_GUILD_TIMESTAMP). |
| Public property | [HairColor](WoWPlayer/Properties/HairColor_0EA1F08247EE.md) | Hair color (byte 3 of PLAYER_BYTES). |
| Public property | [HairStyle](WoWPlayer/Properties/HairStyle_8A5205D16110.md) | Hair style (byte 2 of PLAYER_BYTES). |
| Public property | [HasRestedXp](WoWPlayer/Properties/HasRestedXp_8395E0DF9832.md) | Whether the player has rested XP. |
| Public property | [HasteRating](WoWPlayer/Properties/HasteRating_2B975ECF3FD6.md) | Melee haste rating (index 17 = CR_HASTE_MELEE). |
| Public property | [HealingBonusPercent](WoWPlayer/Properties/HealingBonusPercent_8E8315B56021.md) | Healing bonus percent. |
| Public property | [HealingBonusPositive](WoWPlayer/Properties/HealingBonusPositive_2BBB99F15CA7.md) | Healing bonus (positive). |
| Public property | [HealingModifierPercent](WoWPlayer/Properties/HealingModifierPercent_68C1FFA5CA1F.md) | Healing modifier percent. |
| Public property | [HolyBonusNegative](WoWPlayer/Properties/HolyBonusNegative_7B2F2D2AC7C3.md) | Holy bonus damage (negative). |
| Public property | [HolyBonusPercent](WoWPlayer/Properties/HolyBonusPercent_113B71E5F55C.md) | Holy bonus damage percent. |
| Public property | [HolyBonusPositive](WoWPlayer/Properties/HolyBonusPositive_A93787D415CD.md) | Holy bonus damage (positive). |
| Public property | [HolyCritPercent](WoWPlayer/Properties/HolyCritPercent_1243C7BF9C4D.md) | Holy spell crit percentage. |
| Public property | [Honor](WoWPlayer/Properties/Honor_6D919CCA5849.md) | Gets the honor. |
| Public property | [HonorableKillsToday](WoWPlayer/Properties/HonorableKillsToday_9D77A71D8142.md) | Today's honorable kills (lower 16 bits of PLAYER_FIELD_KILLS). |
| Public property | [HonorableKillsYesterday](WoWPlayer/Properties/HonorableKillsYesterday_5CDC342B2688.md) | Yesterday's honorable kills (upper 16 bits of PLAYER_FIELD_KILLS). |
| Public property | [InMyParty](WoWPlayer/Properties/InMyParty_DC3BAF077245.md) | HB compatibility alias. |
| Public property | [InMyPartyOrRaid](WoWPlayer/Properties/InMyPartyOrRaid_CECD6E7C26FE.md) | HB compatibility alias. |
| Public property | [InMyRaid](WoWPlayer/Properties/InMyRaid_115F633D6605.md) | HB compatibility alias. |
| Public property | [InteractRange](WoWPlayer/Properties/InteractRange_0ED79C3FD232.md) | Gets the interact range. (Overrides WoWUnit.InteractRange.) |
| Public property | [IsAFKFlagged](WoWPlayer/Properties/IsAFKFlagged_398FD14251E3.md) | Gets a value indicating whether is afk flagged. |
| Public property | [IsAlive](WoWPlayer/Properties/IsAlive_843ACC008714.md) | Gets a value indicating whether is alive. (Overrides WoWUnit.IsAlive.) |
| Public property | [IsAlliance](WoWPlayer/Properties/IsAlliance_9B2184E2E6A1.md) | Gets a value indicating whether is alliance. |
| Public property | [IsCaster](WoWPlayer/Properties/IsCaster_44E174A6E5DE.md) | Gets a value indicating whether is caster. |
| Public property | [IsDNDFlagged](WoWPlayer/Properties/IsDNDFlagged_B9A2818B31DF.md) | Gets a value indicating whether is dnd flagged. |
| Public property | [IsDueling](WoWPlayer/Properties/IsDueling_FE4468F07CD8.md) | Returns true if this player is currently in a duel. |
| Public property | [IsFFAPvPFlagged](WoWPlayer/Properties/IsFFAPvPFlagged_C55874D671C3.md) | Gets a value indicating whether is ffa pv p flagged. |
| Public property | [IsFemale](WoWPlayer/Properties/IsFemale_9FB9DD6D4958.md) | Gets a value indicating whether is female. |
| Public property | [IsGM](WoWPlayer/Properties/IsGM_9135EE5F1F34.md) | Gets a value indicating whether is gm. |
| Public property | [IsGhost](WoWPlayer/Properties/IsGhost_7B578B6C26F3.md) | Gets a value indicating whether is ghost. |
| Public property | [IsGroupLeader](WoWPlayer/Properties/IsGroupLeader_51AE3278822E.md) | Gets a value indicating whether is group leader. |
| Public property | [IsHealer](WoWPlayer/Properties/IsHealer_3087EA486E85.md) | Gets a value indicating whether is healer. |
| Public property | [IsHidingCloak](WoWPlayer/Properties/IsHidingCloak_B21F70810848.md) | Gets a value indicating whether is hiding cloak. |
| Public property | [IsHidingHelm](WoWPlayer/Properties/IsHidingHelm_711D115BC23B.md) | Gets a value indicating whether is hiding helm. |
| Public property | [IsHorde](WoWPlayer/Properties/IsHorde_A80ECC95DF61.md) | Gets a value indicating whether is horde. |
| Public property | [IsInMyParty](WoWPlayer/Properties/IsInMyParty_043579AB72C9.md) | Whether this player is in the local player's party (not including self). |
| Public property | [IsInMyPartyOrRaid](WoWPlayer/Properties/IsInMyPartyOrRaid_A6C780BCBDB8.md) | Whether this player is in the local player's party or raid. |
| Public property | [IsInMyRaid](WoWPlayer/Properties/IsInMyRaid_A79DAE86B708.md) | Whether this player is in the local player's raid (not including self). |
| Public property | [IsInsideSanctuary](WoWPlayer/Properties/IsInsideSanctuary_11D828B9CECC.md) | Gets a value indicating whether is inside sanctuary. |
| Public property | [IsMale](WoWPlayer/Properties/IsMale_B267B0AE8DF1.md) | Gets a value indicating whether is male. |
| Public property | [IsMelee](WoWPlayer/Properties/IsMelee_6B8B31808D1A.md) | Gets a value indicating whether is melee. |
| Public property | [IsOutOfBounds](WoWPlayer/Properties/IsOutOfBounds_FFDA2B950D3D.md) | Gets a value indicating whether is out of bounds. |
| Public property | [IsPvPFlagged](WoWPlayer/Properties/IsPvPFlagged_CADB62075482.md) | Gets a value indicating whether is pv p flagged. |
| Public property | [IsPvPTimerActive](WoWPlayer/Properties/IsPvPTimerActive_C748006CCF8B.md) | Gets a value indicating whether is pv p timer active. |
| Public property | [IsResting](WoWPlayer/Properties/IsResting_7BEA9D0A4AD8.md) | Gets a value indicating whether is resting. |
| Public property | [IsTank](WoWPlayer/Properties/IsTank_49792E0D369E.md) | Gets a value indicating whether is tank. |
| Public property | [IsTrackingStealthed](WoWPlayer/Properties/IsTrackingStealthed_51D9A4347CA6.md) | Whether the player is tracking stealthed units (bit 1 of PlayerFieldBytes byte 0). |
| Public property | [LevelFraction](WoWPlayer/Properties/LevelFraction_8917D19426D4.md) | Gets the level fraction. |
| Public property | [LifetimeHonorableKills](WoWPlayer/Properties/LifetimeHonorableKills_4DC05C5629C7.md) | Lifetime honorable kills (PLAYER_FIELD_LIFETIME_HONORABLE_KILLS). |
| Public property | [Mainhand](WoWPlayer/Properties/Mainhand_75072898B100.md) | Gets the mainhand. |
| Public property | [MainhandEntryId](WoWPlayer/Properties/MainhandEntryId_E0CFCD110C4D.md) | Gets the mainhand entry id. |
| Public property | [Mastery](WoWPlayer/Properties/Mastery_B42D42E82966.md) | Mastery rating (Cataclysm+ only). Always 0 in WotLK. |
| Public property | [MasteryPercent](WoWPlayer/Properties/MasteryPercent_BFED4F6F7E21.md) | Mastery percent (Cataclysm+ only). Always 0 in WotLK. |
| Public property | [MaxLevel](WoWPlayer/Properties/MaxLevel_24719DD4C625.md) | Max level (80 in WotLK). |
| Public property | [Minions](WoWPlayer/Properties/Minions_8A8A5ABAA6D2.md) | Gets all minions (pets, totems, etc.) controlled by this player. Excludes non-combat pets. |
| Public property | [Mounted](WoWPlayer/Properties/Mounted_9B93405A1E35.md) | Gets a value indicating whether mounted. (Overrides WoWUnit.Mounted.) |
| Public property | [NatureBonusNegative](WoWPlayer/Properties/NatureBonusNegative_15F2DFD52E57.md) | Nature bonus damage (negative). |
| Public property | [NatureBonusPercent](WoWPlayer/Properties/NatureBonusPercent_319DB66AA3B9.md) | Nature bonus damage percent. |
| Public property | [NatureBonusPositive](WoWPlayer/Properties/NatureBonusPositive_7221B02E80B3.md) | Nature bonus damage (positive). |
| Public property | [NatureCritPercent](WoWPlayer/Properties/NatureCritPercent_1073751B3E3F.md) | Nature spell crit percentage. |
| Public property | [NextLevelExperience](WoWPlayer/Properties/NextLevelExperience_9DEA321544B0.md) | Gets the next level experience. |
| Public property | [NextLevelXP](WoWPlayer/Properties/NextLevelXP_BD00C1E33C30.md) | Gets the next level xp. |
| Public property | [OffHandCritPercent](WoWPlayer/Properties/OffHandCritPercent_D88E53CA7594.md) | Off-hand crit percentage (PLAYER_OFFHAND_CRIT_PERCENTAGE). |
| Public property | [OffHandExpertise](WoWPlayer/Properties/OffHandExpertise_80BEA2AA5CB7.md) | Off-hand expertise rating (PLAYER_OFFHAND_EXPERTISE). |
| Public property | [Offhand](WoWPlayer/Properties/Offhand_963BC38AAECE.md) | Gets the offhand. |
| Public property | [OffhandEntryId](WoWPlayer/Properties/OffhandEntryId_CB814771DFA5.md) | Gets the offhand entry id. |
| Public property | [ParryPercent](WoWPlayer/Properties/ParryPercent_1B7552FD838D.md) | Parry chance percentage (PLAYER_PARRY_PERCENTAGE). |
| Public property | [PetSpellPower](WoWPlayer/Properties/PetSpellPower_51FC0A28AE7C.md) | Pet spell power scaling for hunter/warlock pets (PLAYER_PET_SPELL_POWER). |
| Public property | [PhysicalBonusNegative](WoWPlayer/Properties/PhysicalBonusNegative_1F86158E4ED1.md) | Physical bonus damage (negative, school 0). |
| Public property | [PhysicalBonusPositive](WoWPlayer/Properties/PhysicalBonusPositive_C660ABA006DF.md) | Physical bonus damage (positive, school 0). |
| Public property | [PhysicalCritPercent](WoWPlayer/Properties/PhysicalCritPercent_16AE93D430C9.md) | Physical spell crit percentage (school 0). |
| Public property | [PvpMedalCount](WoWPlayer/Properties/PvpMedalCount_AC657B4DD7FE.md) | PvP medal count (PLAYER_FIELD_PVP_MEDALS). |
| Public property | [RangedCritPercent](WoWPlayer/Properties/RangedCritPercent_125713BECB44.md) | Ranged crit chance percentage (PLAYER_RANGED_CRIT_PERCENTAGE). |
| Public property | [ReleaseTimerIsVisible](WoWPlayer/Properties/ReleaseTimerIsVisible_CD43BAD6F821.md) | Whether the corpse release timer is visible (bit 3 of PlayerFieldBytes byte 0). |
| Public property | [Resilience](WoWPlayer/Properties/Resilience_7D2A8DA3BFA5.md) | Resilience rating (index 14 = CR_CRIT_TAKEN_MELEE, base resilience in WotLK). |
| Public property | [RestedExperience](WoWPlayer/Properties/RestedExperience_6CB8D7F3E6C6.md) | Rested XP amount (PLAYER_REST_STATE_EXPERIENCE). |
| Public property | [RuneRegen](WoWPlayer/Properties/RuneRegen_CD380F1FBA6C.md) | DK rune regeneration rates (4 floats, PLAYER_RUNE_REGEN_1). |
| Public property | [SelfResurrectSpellId](WoWPlayer/Properties/SelfResurrectSpellId_CB3F66E7D92D.md) | Self-resurrection spell ID (e.g., Soulstone, Ankh). 0 = none. |
| Public property | [ShadowBonusNegative](WoWPlayer/Properties/ShadowBonusNegative_91ECB9CCF6DE.md) | Shadow bonus damage (negative). |
| Public property | [ShadowBonusPercent](WoWPlayer/Properties/ShadowBonusPercent_0A50BE4F99C0.md) | Shadow bonus damage percent. |
| Public property | [ShadowBonusPositive](WoWPlayer/Properties/ShadowBonusPositive_E51347EDC1B7.md) | Shadow bonus damage (positive). |
| Public property | [ShadowCritPercent](WoWPlayer/Properties/ShadowCritPercent_20DBF6F121FF.md) | Shadow spell crit percentage. |
| Public property | [ShieldBlock](WoWPlayer/Properties/ShieldBlock_8AAD2BCC3D54.md) | Shield block value (PLAYER_SHIELD_BLOCK). |
| Public property | [ShieldBlockCritPercent](WoWPlayer/Properties/ShieldBlockCritPercent_817F4C436C93.md) | Shield block crit percentage (PLAYER_SHIELD_BLOCK_CRIT_PERCENTAGE). |
| Public property | [Silver](WoWPlayer/Properties/Silver_4C4C059E6A73.md) | Total money expressed in silver. HB 3.3.5a/4.3.4: Coinage / 100. |
| Public property | [Skin](WoWPlayer/Properties/Skin_4B1F40E25231.md) | Skin color/type (byte 0 of PLAYER_BYTES). |
| Public property | [SpellPowerModifierPercent](WoWPlayer/Properties/SpellPowerModifierPercent_4FA128316726.md) | Spell power modifier percent (Cata+ only, does not exist in WotLK). Always 1.0f. |
| Public property | [TargetArmorModifier](WoWPlayer/Properties/TargetArmorModifier_43C6A3B69AC1.md) | Armor modifier vs target (PLAYER_FIELD_MOD_TARGET_PHYSICAL_RESISTANCE). |
| Public property | [TargetResistanceModifier](WoWPlayer/Properties/TargetResistanceModifier_394B7D184786.md) | Spell power modifier vs target (PLAYER_FIELD_MOD_TARGET_RESISTANCE). |
| Public property | [Type](WoWPlayer/Properties/Type_04B69103EC44.md) | Gets the type. (Overrides WoWObject.Type.) |
| Public property | [WatchedFactionIndex](WoWPlayer/Properties/WatchedFactionIndex_F7B4524CFCAC.md) | Watched faction index (PLAYER_FIELD_WATCHED_FACTION_INDEX). |
| Public property | [XP](WoWPlayer/Properties/XP_DA2CF3DF1F4C.md) | Gets the xp. |
| Public property | [XPPercent](WoWPlayer/Properties/XPPercent_119DAF9589A5.md) | Gets the xp percent. |
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
| Public property | IsStealthed | Gets a value indicating whether is stealthed. (Inherited from WoWUnit.) |
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
| Public property | Pet | Gets the pet. (Inherited from WoWUnit.) |
| Public property | PetAggro | Gets a value indicating whether pet aggro. (Inherited from WoWUnit.) |
| Public property | PetExperience | Pet XP (UNIT_FIELD_PETEXPERIENCE). (Inherited from WoWUnit.) |
| Public property | PetInCombat | Gets a value indicating whether pet in combat. (Inherited from WoWUnit.) |
| Public property | PetNextLevelExperience | Pet XP to next level (UNIT_FIELD_PETNEXTLEVELEXP). (Inherited from WoWUnit.) |
| Public property | PetNumber | Pet tracking number (UNIT_FIELD_PETNUMBER). (Inherited from WoWUnit.) |
| Public property | PlayerControlled | Gets a value indicating whether player controlled. (Inherited from WoWUnit.) |
| Public property | Possessed | Gets a value indicating whether possessed. (Inherited from WoWUnit.) |
| Public property | PowerPercent | Generic power percent — auto-selects the unit's active power type. (Inherited from WoWUnit.) |
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
| Public property | [BaseAddress](WoWObject/Properties/BaseAddress_492AAE85E67F.md) | Gets the base address. (Inherited from WoWObject.) |
| Public property | [DescriptorGuid](WoWObject/Properties/DescriptorGuid_B26F316E4116.md) | Gets the descriptor guid. (Inherited from WoWObject.) |
| Public property | [Distance](WoWObject/Properties/Distance_CE704472EEFF.md) | Gets the distance. (Inherited from WoWObject.) |
| Public property | [Distance2D](WoWObject/Properties/Distance2D_711DA676678E.md) | Gets the distance2d. (Inherited from WoWObject.) |
| Public property | [Distance2DSqr](WoWObject/Properties/Distance2DSqr_56513A6C016B.md) | Gets the distance2d sqr. (Inherited from WoWObject.) |
| Public property | [DistanceSqr](WoWObject/Properties/DistanceSqr_0EED3CFC9635.md) | Gets the distance sqr. (Inherited from WoWObject.) |
| Public property | [Entry](WoWObject/Properties/Entry_BB30729388DC.md) | Gets the entry. (Inherited from WoWObject.) |
| Public property | [Guid](WoWObject/Properties/Guid_9EBAFBD4CA9C.md) | Gets the guid. (Inherited from WoWObject.) |
| Public property | [InLineOfSightOCD](WoWObject/Properties/InLineOfSightOCD_9BDD4A778E20.md) | HB 4.3.4 compat — was marked [Obsolete], just delegates to InLineOfSight. External bots (LazyRaider etc.) reference this. (Inherited from WoWObject.) |
| Public property | [InteractRangeSqr](WoWObject/Properties/InteractRangeSqr_03A9554B5AE9.md) | FEAT-28: Squared interact range for faster distance checks (avoids sqrt). (Inherited from WoWObject.) |
| Public property | [InteractType](WoWObject/Properties/InteractType_9EA6D2B14334.md) | Gets the interact type. (Inherited from WoWObject.) |
| Public property | [IsDisabled](WoWObject/Properties/IsDisabled_CA00033E94A6.md) | Gets a value indicating whether is disabled. (Inherited from WoWObject.) |
| Public property | [IsIndoors](WoWObject/Properties/IsIndoors_BFC833E84B34.md) | Gets a value indicating whether is indoors. (Inherited from WoWObject.) |
| Public property | [IsMe](WoWObject/Properties/IsMe_591F6D9719B7.md) | Gets a value indicating whether is me. (Inherited from WoWObject.) |
| Public property | [IsOutdoors](WoWObject/Properties/IsOutdoors_B015AB15D5D1.md) | Whether this object is indoors. Override on LocalPlayer uses Lua for accuracy. FEAT-45: Made virtual so LocalPlayer can override. (Inherited from WoWObject.) |
| Public property | [IsUnderground](WoWObject/Properties/IsUnderground_E27ED67229BC.md) | Gets a value indicating whether is underground. (Inherited from WoWObject.) |
| Public property | [IsValid](WoWObject/Properties/IsValid_4E903E878B2D.md) | Gets a value indicating whether is valid. (Inherited from WoWObject.) |
| Public property | [MeIsBehind](WoWObject/Properties/MeIsBehind_397CD087104B.md) | Gets a value indicating whether me is behind. (Inherited from WoWObject.) |
| Public property | [MeIsSafelyBehind](WoWObject/Properties/MeIsSafelyBehind_2244DCAB4964.md) | Gets a value indicating whether me is safely behind. (Inherited from WoWObject.) |
| Public property | [Name](WoWObject/Properties/Name_2ED73C6FC932.md) | Gets the name. (Inherited from WoWObject.) |
| Public property | [ObjectFlags](WoWObject/Properties/ObjectFlags_2A5DE384B24A.md) | Gets the object flags. (Inherited from WoWObject.) |
| Public property | [QuestGiverStatus](WoWObject/Properties/QuestGiverStatus_106D54DD1695.md) | Gets the quest giver status. (Inherited from WoWObject.) |
| Public property | [RotationDegrees](WoWObject/Properties/RotationDegrees_35D5A15A1EE2.md) | Gets the rotation degrees. (Inherited from WoWObject.) |
| Public property | [TypeFlags](WoWObject/Properties/TypeFlags_53052F716CEF.md) | Gets the type flags. (Inherited from WoWObject.) |
| Public property | [WithinInteractRange](WoWObject/Properties/WithinInteractRange_FD011C1E1AA3.md) | Gets a value indicating whether within interact range. (Inherited from WoWObject.) |
| Public property | [WorldLocation](WoWObject/Properties/WorldLocation_1AFA4C2657C4.md) | Alias for Location. Matches HB 4.3.4 API surface used by external plugins. (Inherited from WoWObject.) |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [OnInvalidate](WoWObject/Events/OnInvalidate_0488B27147AC.md) | Occurs when invalidate. (Inherited from WoWObject.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetCombatRating(int)](WoWPlayer/Methods/GetCombatRating_ECCF5AEBCD68.md) | Gets a combat rating value by index (0-24). |
| Public method | [GetGlyph(int)](WoWPlayer/Methods/GetGlyph_AD0182E8A67D.md) | Gets the glyph spell ID at the specified slot (0-5). |
| Public method | [GetGlyphSlot(int)](WoWPlayer/Methods/GetGlyphSlot_01F9F474B359.md) | Gets the glyph slot type at the specified index (0-5). |
| Public method | [GetSpellBonusDamageNegative(int)](WoWPlayer/Methods/GetSpellBonusDamageNegative_ADDCE2C2BE68.md) | Gets negative spell bonus damage for the specified school index (0-6). |
| Public method | [GetSpellBonusDamagePercent(int)](WoWPlayer/Methods/GetSpellBonusDamagePercent_D613960D9D66.md) | Gets spell bonus damage percent for the specified school index (0-6). |
| Public method | [GetSpellBonusDamagePositive(int)](WoWPlayer/Methods/GetSpellBonusDamagePositive_1293AA7D35BC.md) | Gets positive spell bonus damage for the specified school index (0-6). |
| Public method | [GetSpellCritPercent(int)](WoWPlayer/Methods/GetSpellCritPercent_49548F84D85B.md) | Spell crit percentage for the specified school index (0-6). |
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
| Public method | [CompareTo(WoWObject)](WoWObject/Methods/CompareTo_B9F594AE34DB.md) | Compares the current instance with another object. (Inherited from WoWObject.) |
| Public method | [Equals(object)](WoWObject/Methods/Equals_87ADC3D3DB3A.md) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from WoWObject.) |
| Public method | [Equals(WoWObject)](WoWObject/Methods/Equals_13ECB9CABD6F.md) | Determines whether the specified object is equal to the current object. (Inherited from WoWObject.) |
| Protected method | [GetDescriptorField(int)](WoWObject/Methods/GetDescriptorField_134A15A13DF3.md) | Gets the descriptor field. (Inherited from WoWObject.) |
| Public method | [GetHashCode](WoWObject/Methods/GetHashCode_8D8608D5A92C.md) | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from WoWObject.) |
| Public method | [GetObjectName](WoWObject/Methods/GetObjectName_5AAFAAC1340C.md) | Gets the name of this WoW object from game memory. Uses Executor to call WoW's internal name retrieval function. Based on HB 3.3.5a WoWObject.GetObjectName() implementation. (Inherited from WoWObject.) |
| Public method | [GetPosition](WoWObject/Methods/GetPosition_167A0C0B7807.md) | Gets the position. (Inherited from WoWObject.) |
| Public method | [Interact](WoWObject/Methods/Interact_0532516B1E22.md) | Interacts with the object. (Inherited from WoWObject.) |
| Public method | [Interact(bool)](WoWObject/Methods/Interact_E166198E5B7A.md) | Interacts with the object. (Inherited from WoWObject.) |
| Public method | [IsBehind(WoWObject)](WoWObject/Methods/IsBehind_8C60C65DE906.md) | Determines whether the target is behind. (Inherited from WoWObject.) |
| Public method | [IsFacing(WoWObject)](WoWObject/Methods/IsFacing_A832009980DB.md) | Determines whether the target is facing the point. (Inherited from WoWObject.) |
| Public method | [IsFacing(WoWPoint)](WoWObject/Methods/IsFacing_C7C07841DC12.md) | Determines whether the target is facing the point. (Inherited from WoWObject.) |
| Public method | [IsSafelyBehind(WoWObject)](WoWObject/Methods/IsSafelyBehind_2C146F2ECFF5.md) | Determines whether the target is safely behind. (Inherited from WoWObject.) |
| Public method | [IsSafelyFacing(WoWObject)](WoWObject/Methods/IsSafelyFacing_DB5513A397BD.md) | Determines whether the target is safely facing the point. (Inherited from WoWObject.) |
| Public method | [IsSafelyFacing(WoWPoint)](WoWObject/Methods/IsSafelyFacing_E5AF377C20A7.md) | Determines whether the target is safely facing the point. (Inherited from WoWObject.) |
| Public method | [IsSafelyFacing(WoWObject, float)](WoWObject/Methods/IsSafelyFacing_682B8ED9E760.md) | Determines whether the target is safely facing the point. (Inherited from WoWObject.) |
| Public method | [ToContainer](WoWObject/Methods/ToContainer_2BBB85EC8FA1.md) | Converts to container. (Inherited from WoWObject.) |
| Public method | [ToDynamicObject](WoWObject/Methods/ToDynamicObject_0B3D998E0B57.md) | FEAT-28: Cast this object to WoWDynamicObject (e.g., Blizzard, Rain of Fire ground effects). (Inherited from WoWObject.) |
| Public method | [ToGameObject](WoWObject/Methods/ToGameObject_D7DEAF4EE2DA.md) | Converts to game object. (Inherited from WoWObject.) |
| Public method | [ToItem](WoWObject/Methods/ToItem_E53609786462.md) | Converts to item. (Inherited from WoWObject.) |
| Public method | [ToPlayer](WoWObject/Methods/ToPlayer_BB5E28DE9BF2.md) | Converts to player. (Inherited from WoWObject.) |
| Public method | [ToString](WoWObject/Methods/ToString_A851304933D2.md) | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from WoWObject.) |
| Public method | [ToUnit](WoWObject/Methods/ToUnit_A89B65FFC386.md) | Converts to unit. (Inherited from WoWObject.) |
| Protected method | [WriteDescriptor(uint, T)](WoWObject/Methods/WriteDescriptor_B0A8EB1C75A3.md) | Writes the descriptor. (Inherited from WoWObject.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
