# WoWUnit Class

Represents a wow unit.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.WoWObject
    Styx.WoWInternals.WoWObjects.WoWUnit

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWUnit : WoWObject, ILootableObject
```

The WoWUnit type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWUnit(uint)](WoWUnit/Constructors/Constructor_2CC174317641.md) | Initializes a new instance of the WoWUnit class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ActiveAuras](WoWUnit/Properties/ActiveAuras_8D5ACA93423C.md) | Gets the active auras. |
| Public property | [Aggro](WoWUnit/Properties/Aggro_EAD5ACA913CB.md) | Gets a value indicating whether aggro. |
| Public property | [Agility](WoWUnit/Properties/Agility_07AFE107F175.md) | Gets the agility. |
| Public property | [AgilityBonus](WoWUnit/Properties/AgilityBonus_13344DBF66F7.md) | Gets the agility bonus. |
| Public property | [AgilityNegativeModifier](WoWUnit/Properties/AgilityNegativeModifier_1FC1EE197A36.md) | FEAT-25: Negative agility modifier (UNIT_FIELD_NEGSTAT1). |
| Public property | [ArcaneResist](WoWUnit/Properties/ArcaneResist_DD84F2146465.md) | Gets the arcane resist. |
| Public property | [Armor](WoWUnit/Properties/Armor_D776EF3E8FA6.md) | Gets the armor. |
| Public property | [AttackPower](WoWUnit/Properties/AttackPower_0DEBD82B703E.md) | Melee attack power (UNIT_FIELD_ATTACK_POWER). |
| Public property | [AttackPowerMods](WoWUnit/Properties/AttackPowerMods_F141A97817CC.md) | Melee attack power modifiers (UNIT_FIELD_ATTACK_POWER_MODS). |
| Public property | [AttackPowerMultiplier](WoWUnit/Properties/AttackPowerMultiplier_0B0F79873C3A.md) | Melee attack power multiplier (UNIT_FIELD_ATTACK_POWER_MULTIPLIER). |
| Public property | [Attackable](WoWUnit/Properties/Attackable_9CC1759A2E1E.md) | Gets a value indicating whether attackable. |
| Public property | [AuraState](WoWUnit/Properties/AuraState_DBB04516E8F0.md) | Aura state flags (UNIT_FIELD_AURASTATE). |
| Public property | [Auras](WoWUnit/Properties/Auras_E2D9A8C2C70F.md) | Gets the auras. |
| Public property | [BaseAttackTime](WoWUnit/Properties/BaseAttackTime_0608C90A585C.md) | Base main-hand attack time in ms (UNIT_FIELD_BASEATTACKTIME). |
| Public property | [BaseHealth](WoWUnit/Properties/BaseHealth_5F084247F83D.md) | Base health before modifiers (UNIT_FIELD_BASE_HEALTH). |
| Public property | [BaseMana](WoWUnit/Properties/BaseMana_000818274BDE.md) | Gets the base mana. |
| Public property | [BaseOffHandAttackTime](WoWUnit/Properties/BaseOffHandAttackTime_7088F3139C29.md) | Base off-hand attack time in ms (UNIT_FIELD_BASEATTACKTIME + 1). |
| Public property | [BaseRangedAttackTime](WoWUnit/Properties/BaseRangedAttackTime_03BC51A010B0.md) | Base ranged attack time in ms (UNIT_FIELD_RANGEDATTACKTIME). |
| Public property | [BehindTarget](WoWUnit/Properties/BehindTarget_460C1EF421C4.md) | Gets a value indicating whether behind target. |
| Public property | [BoundingHeight](WoWUnit/Properties/BoundingHeight_300FFF704D6E.md) | Gets the bounding height. |
| Public property | [BoundingRadius](WoWUnit/Properties/BoundingRadius_FB137568582C.md) | Gets the bounding radius. |
| Public property | [Buffs](WoWUnit/Properties/Buffs_EC56EBE366E6.md) | Gets the buffs. |
| Public property | [CanGossip](WoWUnit/Properties/CanGossip_43A22913E56A.md) | Gets a value indicating whether can gossip. |
| Public property | [CanInterruptCurrentSpellCast](WoWUnit/Properties/CanInterruptCurrentSpellCast_C91B494965A0.md) | Returns true if this unit's current cast can be interrupted. Checks both IsCasting and Interruptible flag. |
| Public property | [CanLoot](WoWUnit/Properties/CanLoot_31563D4FC28B.md) | Gets a value indicating whether can loot. |
| Public property | [CanSelect](WoWUnit/Properties/CanSelect_5CB867830979.md) | Gets a value indicating whether can select. |
| Public property | [CanSkin](WoWUnit/Properties/CanSkin_F105243C11BE.md) | Gets a value indicating whether can skin. |
| Public property | [CastSpeedModifier](WoWUnit/Properties/CastSpeedModifier_6E1FBA884EDC.md) | Cast speed multiplier (UNIT_MOD_CAST_SPEED). 1.0 = normal. |
| Public property | [Casting](WoWUnit/Properties/Casting_FCBB9B8B0D81.md) | Gets the spell ID being cast or channeled. Returns CastingSpellId if casting, otherwise ChannelSpellId. |
| Public property | [CastingChanneledId](WoWUnit/Properties/CastingChanneledId_704D1F1414BB.md) | Gets the spell ID currently being channeled. Returns 0 if not channeling. Offset: BaseAddress + 2688 (WoW 3.3.5a build 12340) |
| Public property | [CastingSpell](WoWUnit/Properties/CastingSpell_FE625197D4A1.md) | Gets the spell currently being cast (regular cast only). |
| Public property | [CastingSpellId](WoWUnit/Properties/CastingSpellId_E4500E2FF97A.md) | Gets the spell ID currently being cast or channeled (combined). HB 4.3.4: returns NonChanneledCastingSpellId if != 0, else ChanneledCastingSpellId. |
| Public property | [ChannelObject](WoWUnit/Properties/ChannelObject_AC6066058E58.md) | Gets the WoW object being channeled on. Returns null if not channeling on an object. |
| Public property | [ChannelObjectGuid](WoWUnit/Properties/ChannelObjectGuid_56AB6DDFAFF3.md) | Gets the GUID of the object being channeled on. Used for spells like Mind Control that channel on a target. |
| Public property | [ChannelSpell](WoWUnit/Properties/ChannelSpell_626FDD3AEC15.md) | Gets the spell currently being channeled. |
| Public property | [ChannelSpellId](WoWUnit/Properties/ChannelSpellId_EAFED9982E51.md) | Alias for CastingChanneledId for consistency. |
| Public property | [ChannelTimeLeft](WoWUnit/Properties/ChannelTimeLeft_F001EEAB4317.md) | FEAT-23: Alias for CurrentChannelTimeLeft — HB 4.3.4 compatibility. |
| Public property | [ChanneledCasting](WoWUnit/Properties/ChanneledCasting_ECEA72464EBB.md) | Gets the channeled casting. |
| Public property | [ChanneledCastingSpell](WoWUnit/Properties/ChanneledCastingSpell_8C5EEBCEBD73.md) | FEAT-23: Gets the WoWSpell being channeled (typed version of ChanneledCastingSpellId). |
| Public property | [ChanneledCastingSpellId](WoWUnit/Properties/ChanneledCastingSpellId_E597CF2D230C.md) | Alias for ChannelSpellId - HB 4.3.4 compatibility. |
| Public property | [Charmed](WoWUnit/Properties/Charmed_6F6ADE3AEA95.md) | Gets the charmed. |
| Public property | [CharmedBy](WoWUnit/Properties/CharmedBy_17898E456610.md) | Gets the charmed by. |
| Public property | [CharmedByGuid](WoWUnit/Properties/CharmedByGuid_491F5B9B1629.md) | Gets the charmed by guid. |
| Public property | [CharmedUnit](WoWUnit/Properties/CharmedUnit_27BFBB390955.md) | Gets the charmed unit. |
| Public property | [CharmedUnitGuid](WoWUnit/Properties/CharmedUnitGuid_EA1A0FF4B951.md) | Gets the charmed unit guid. |
| Public property | [Class](WoWUnit/Properties/Class_4DE4B4F51C91.md) | Gets the class. |
| Public property | [Combat](WoWUnit/Properties/Combat_2BBE4D2119DD.md) | Gets a value indicating whether combat. |
| Public property | [CombatReach](WoWUnit/Properties/CombatReach_B5034060CFA2.md) | Gets the combat reach. |
| Public property | [ControllingPlayer](WoWUnit/Properties/ControllingPlayer_AB647F50FF63.md) | Gets the controlling player for this unit. Walks the charm/summon chain up to 2 levels to find a player controller. |
| Public property | [CreatedBy](WoWUnit/Properties/CreatedBy_35BEF96154A0.md) | Gets the created by. |
| Public property | [CreatedByGuid](WoWUnit/Properties/CreatedByGuid_7CE4FE828F2C.md) | Gets the created by guid. |
| Public property | [CreatedBySpellId](WoWUnit/Properties/CreatedBySpellId_E1DC4A8F2004.md) | Gets the created by spell id. |
| Public property | [CreatureRank](WoWUnit/Properties/CreatureRank_5804CADD261E.md) | Gets the creature rank. |
| Public property | [CreatureType](WoWUnit/Properties/CreatureType_CA824340911D.md) | Gets the creature type. |
| Public property | [Critter](WoWUnit/Properties/Critter_C1A948952E87.md) | Gets the critter. |
| Public property | [CurrentCastTime](WoWUnit/Properties/CurrentCastTime_0151E7C519B2.md) | Gets the total cast time of the current spell being cast. Uses WoWSpell.CastTime which comes from spell DBC data. |
| Public property | [CurrentCastTimeLeft](WoWUnit/Properties/CurrentCastTimeLeft_363C56656BC0.md) | Gets the time remaining on the current cast via Lua UnitCastingInfo. BUG-25: Works for player/target/focus via Lua unitId mapping. Returns TimeSpan.Zero for units without a known unitId. |
| Public property | [CurrentCastingSpell](WoWUnit/Properties/CurrentCastingSpell_05AF3EEF23D7.md) | Gets the spell being cast or channeled (whichever is active). |
| Public property | [CurrentChannelTimeLeft](WoWUnit/Properties/CurrentChannelTimeLeft_A275ACC3730D.md) | FEAT-23: Gets the remaining time on the current channel via Lua UnitChannelInfo. Returns TimeSpan.Zero for units without a known unitId. |
| Public property | [CurrentEclipse](WoWUnit/Properties/CurrentEclipse_CF4C0200313C.md) | Eclipse power (Cataclysm+ only). Always 0 in WotLK. |
| Public property | [CurrentEnergy](WoWUnit/Properties/CurrentEnergy_F431982F6FF3.md) | Gets the current energy. |
| Public property | [CurrentFocus](WoWUnit/Properties/CurrentFocus_D6CAF9995E88.md) | Gets the current focus. |
| Public property | [CurrentHappiness](WoWUnit/Properties/CurrentHappiness_E7F9D7A09CB3.md) | Gets the current happiness. |
| Public property | [CurrentHealth](WoWUnit/Properties/CurrentHealth_8DC3A73D64D9.md) | Gets the current health. |
| Public property | [CurrentHolyPower](WoWUnit/Properties/CurrentHolyPower_5AB78EAD87D0.md) | Holy Power (Cataclysm+ only). Always 0 in WotLK. |
| Public property | [CurrentMana](WoWUnit/Properties/CurrentMana_0715A146FAF8.md) | Gets the current mana. |
| Public property | [CurrentPower](WoWUnit/Properties/CurrentPower_91A73486CE25.md) | Gets the current power. |
| Public property | [CurrentPowerInfo](WoWUnit/Properties/CurrentPowerInfo_5A440B9816CE.md) | Gets the current power info. |
| Public property | [CurrentRage](WoWUnit/Properties/CurrentRage_851C600C824F.md) | Gets the current rage. |
| Public property | [CurrentRunicPower](WoWUnit/Properties/CurrentRunicPower_98AA93339309.md) | Gets the current runic power. |
| Public property | [CurrentSoulShards](WoWUnit/Properties/CurrentSoulShards_7E843FE8B0B0.md) | Soul Shards (Cataclysm+ only). Always 0 in WotLK. |
| Public property | [CurrentTarget](WoWUnit/Properties/CurrentTarget_C6AE6BCE1A30.md) | Gets the current target. |
| Public property | [CurrentTargetGuid](WoWUnit/Properties/CurrentTargetGuid_B0C51964F5EF.md) | Gets the current target guid. |
| Public property | [Dazed](WoWUnit/Properties/Dazed_4CF96EACF7E4.md) | Gets a value indicating whether dazed. |
| Public property | [Dead](WoWUnit/Properties/Dead_726F85793E81.md) | Gets a value indicating whether dead. |
| Public property | [Debuffs](WoWUnit/Properties/Debuffs_0B6E5F0FB244.md) | Gets the debuffs. |
| Public property | [Difficulty](WoWUnit/Properties/Difficulty_9FC1D9F47DDC.md) | Simplified difficulty color calculation similar to HB. Determines how close the mob's level is to the player. |
| Public property | [Disarmed](WoWUnit/Properties/Disarmed_7C7D8CF88096.md) | Gets a value indicating whether disarmed. |
| Public property | [DisplayFlags](WoWUnit/Properties/DisplayFlags_76D2FCD0833F.md) | Gets the display flags. |
| Public property | [DisplayId](WoWUnit/Properties/DisplayId_4EEAE6A43B91.md) | Gets the display id. |
| Public property | [EclipseInfo](WoWUnit/Properties/EclipseInfo_CD5862E921D3.md) | Gets the eclipse info. |
| Public property | [EclipsePercent](WoWUnit/Properties/EclipsePercent_6DA489D78B93.md) | Gets the eclipse percent. |
| Public property | [Elite](WoWUnit/Properties/Elite_198B4B75154B.md) | Gets a value indicating whether elite. |
| Public property | [EnergyInfo](WoWUnit/Properties/EnergyInfo_6600CA44BAB8.md) | Convenience: EnergyInfo. |
| Public property | [EnergyPercent](WoWUnit/Properties/EnergyPercent_1A575B9BE3E0.md) | Gets the energy percentage (0-100). Used by Rogues, Feral Druids. |
| Public property | [Faction](WoWUnit/Properties/Faction_3B856BC8D915.md) | HB 4.3.4 WoWUnit.Faction — returns the WoWFaction for this unit's FactionId. |
| Public property | [FactionId](WoWUnit/Properties/FactionId_DCF4476F851D.md) | Gets the faction id. |
| Public property | [FactionTemplate](WoWUnit/Properties/FactionTemplate_637DD56B4D2A.md) | Gets the faction template. |
| Public property | [FeignDeathed](WoWUnit/Properties/FeignDeathed_1777EC128ADF.md) | Gets a value indicating whether feign deathed. |
| Public property | [FireResist](WoWUnit/Properties/FireResist_79FA5FC57EED.md) | Gets the fire resist. |
| Public property | [Fleeing](WoWUnit/Properties/Fleeing_C518608C7822.md) | Gets a value indicating whether fleeing. |
| Public property | [FocusInfo](WoWUnit/Properties/FocusInfo_FCE394979153.md) | Convenience: FocusInfo. |
| Public property | [FocusPercent](WoWUnit/Properties/FocusPercent_A97074DE4A27.md) | Convenience: Focus percentage (hunter pet). |
| Public property | [FrostResist](WoWUnit/Properties/FrostResist_90A30CBAAF1D.md) | Gets the frost resist. |
| Public property | [Gender](WoWUnit/Properties/Gender_EC60F48F284F.md) | Gets the gender. |
| Public property | [GotAlivePet](WoWUnit/Properties/GotAlivePet_0BD18B96ACE1.md) | Gets a value indicating whether got alive pet. |
| Public property | [GotTarget](WoWUnit/Properties/GotTarget_E72090500700.md) | Gets a value indicating whether got target. |
| Public property | [HappinessInfo](WoWUnit/Properties/HappinessInfo_913E4B752B5E.md) | Convenience: HappinessInfo. |
| Public property | [HappinessPercent](WoWUnit/Properties/HappinessPercent_74EB0394CDEF.md) | Gets pet happiness percentage (HB 4.3.4 compatibility). WotLK feature - pets have happiness. |
| Public property | [HealthPercent](WoWUnit/Properties/HealthPercent_7AE6317391FE.md) | Gets the health percent. |
| Public property | [HolyPowerInfo](WoWUnit/Properties/HolyPowerInfo_4E69F400012F.md) | Gets the holy power info. |
| Public property | [HolyPowerPercent](WoWUnit/Properties/HolyPowerPercent_421CF59B4DCA.md) | Gets the holy power percent. |
| Public property | [HolyResist](WoWUnit/Properties/HolyResist_EC91EA35813B.md) | Gets the holy resist. |
| Public property | [HoverHeight](WoWUnit/Properties/HoverHeight_2EDD221C1A77.md) | Hover offset above ground (UNIT_FIELD_HOVERHEIGHT). |
| Public property | [InLineOfSight](WoWUnit/Properties/InLineOfSight_B51E307865B8.md) | Whether this unit is in line of sight from the player. Uses GetTraceLinePos() for eye-level raycast on both ends. Ported from HB 4.3.4 WoWUnit — overrides WoWObject base. (Overrides WoWObject.InLineOfSight.) |
| Public property | [InLineOfSpellSight](WoWUnit/Properties/InLineOfSpellSight_6539173096AE.md) | Whether this unit is in line of spell sight from the player. Ported from HB 4.3.4. |
| Public property | [Intellect](WoWUnit/Properties/Intellect_D2423A276757.md) | Gets the intellect. |
| Public property | [IntellectBonus](WoWUnit/Properties/IntellectBonus_51B054C9DD7E.md) | Gets the intellect bonus. |
| Public property | [IntellectNegativeModifier](WoWUnit/Properties/IntellectNegativeModifier_482881EED465.md) | FEAT-25: Negative intellect modifier (UNIT_FIELD_NEGSTAT3). |
| Public property | [InteractRange](WoWUnit/Properties/InteractRange_6EF0D9978C09.md) | Gets the interact range. (Overrides WoWObject.InteractRange.) |
| Public property | [IsAlive](WoWUnit/Properties/IsAlive_1F6D596B6D1B.md) | Gets a value indicating whether is alive. |
| Public property | [IsAmmoVendor](WoWUnit/Properties/IsAmmoVendor_81F395FAB313.md) | Gets a value indicating whether is ammo vendor. |
| Public property | [IsAnyTrainer](WoWUnit/Properties/IsAnyTrainer_210366C8956D.md) | Gets a value indicating whether is any trainer. |
| Public property | [IsAnyVendor](WoWUnit/Properties/IsAnyVendor_CD940188E059.md) | Gets a value indicating whether is any vendor. |
| Public property | [IsAuctioneer](WoWUnit/Properties/IsAuctioneer_3DA80EFEE9E7.md) | Gets a value indicating whether is auctioneer. |
| Public property | [IsAutoAttacking](WoWUnit/Properties/IsAutoAttacking_05B85D48229B.md) | Gets a value indicating whether is auto attacking. |
| Public property | [IsBanker](WoWUnit/Properties/IsBanker_AD8153AA17C2.md) | Gets a value indicating whether is banker. |
| Public property | [IsBattleMaster](WoWUnit/Properties/IsBattleMaster_272B33FEB87E.md) | Gets a value indicating whether is battle master. |
| Public property | [IsBeast](WoWUnit/Properties/IsBeast_BCC27F4CC210.md) | Gets a value indicating whether is beast. |
| Public property | [IsBoss](WoWUnit/Properties/IsBoss_9FE522461692.md) | Gets whether this unit is a boss (level cranked or rare elite). |
| Public property | [IsCasting](WoWUnit/Properties/IsCasting_91083F0E41B0.md) | Returns true if the unit is currently casting or channeling a spell. |
| Public property | [IsChanneling](WoWUnit/Properties/IsChanneling_F9F66B5501A4.md) | Returns true if the unit is currently channeling a spell. |
| Public property | [IsClassTrainer](WoWUnit/Properties/IsClassTrainer_9E4500A361EC.md) | Gets a value indicating whether is class trainer. |
| Public property | [IsCritter](WoWUnit/Properties/IsCritter_39CD14E6D97A.md) | Gets a value indicating whether is critter. |
| Public property | [IsCrowdControlled](WoWUnit/Properties/IsCrowdControlled_35C568324A80.md) | Whether this unit is under a crowd control effect (stun, polymorph, fear, sap, etc.) |
| Public property | [IsDead](WoWUnit/Properties/IsDead_99BFFEF13C13.md) | Returns true if the unit is dead. From HB 5.4.8+ Checks health, and for non-players also checks the Dead dynamic flag. |
| Public property | [IsDemon](WoWUnit/Properties/IsDemon_B6DA937BE02A.md) | Gets a value indicating whether is demon. |
| Public property | [IsDragon](WoWUnit/Properties/IsDragon_F8413C7FDBB1.md) | Gets a value indicating whether is dragon. |
| Public property | [IsDragonkin](WoWUnit/Properties/IsDragonkin_E3278B266773.md) | FEAT-15: Alias for IsDragon — HB 4.3.4 API compatibility. |
| Public property | [IsElemental](WoWUnit/Properties/IsElemental_EA186E4FF6C6.md) | Gets a value indicating whether is elemental. |
| Public property | [IsExotic](WoWUnit/Properties/IsExotic_1DE906EC8D8B.md) | Gets a value indicating whether is exotic. |
| Public property | [IsFalling](WoWUnit/Properties/IsFalling_3F119A45E88B.md) | Gets a value indicating whether is falling. |
| Public property | [IsFlightMaster](WoWUnit/Properties/IsFlightMaster_0101B121BB2B.md) | Gets a value indicating whether is flight master. |
| Public property | [IsFlying](WoWUnit/Properties/IsFlying_7CE623BCDD30.md) | Gets a value indicating whether is flying. |
| Public property | [IsFoodVendor](WoWUnit/Properties/IsFoodVendor_5A65645E2E95.md) | Gets a value indicating whether is food vendor. |
| Public property | [IsFriendly](WoWUnit/Properties/IsFriendly_BCD93B5C0713.md) | Gets a value indicating whether is friendly. |
| Public property | [IsGasCloud](WoWUnit/Properties/IsGasCloud_CC62D37FDC1C.md) | FEAT-22: Whether this creature is a gas cloud (extractable with engineering). |
| Public property | [IsGhost](WoWUnit/Properties/IsGhost_E3F99BCBCAE5.md) | Gets a value indicating whether is ghost. |
| Public property | [IsGhostVisible](WoWUnit/Properties/IsGhostVisible_019C503548A0.md) | Gets a value indicating whether is ghost visible. |
| Public property | [IsGiant](WoWUnit/Properties/IsGiant_23140891C9B3.md) | Gets a value indicating whether is giant. |
| Public property | [IsGuard](WoWUnit/Properties/IsGuard_6E03B77AED77.md) | Gets a value indicating whether is guard. |
| Public property | [IsGuildBanker](WoWUnit/Properties/IsGuildBanker_B6BD6AE9EF4C.md) | Gets a value indicating whether is guild banker. |
| Public property | [IsHostile](WoWUnit/Properties/IsHostile_ECDC56DB2D4E.md) | Gets a value indicating whether is hostile. |
| Public property | [IsHumanoid](WoWUnit/Properties/IsHumanoid_D1EA93AAB918.md) | Gets a value indicating whether is humanoid. |
| Public property | [IsInMyPartyOrRaid](WoWUnit/Properties/IsInMyPartyOrRaid_8FFD9FD679BB.md) | Check if the unit is in the player's party or raid. |
| Public property | [IsInnkeeper](WoWUnit/Properties/IsInnkeeper_ADA3344DA678.md) | Gets a value indicating whether is innkeeper. |
| Public property | [IsMechanical](WoWUnit/Properties/IsMechanical_1D12EB52F50E.md) | Gets a value indicating whether is mechanical. |
| Public property | [IsMoving](WoWUnit/Properties/IsMoving_B7F0610C3225.md) | Whether the unit is currently moving. Uses MovementInfo.IsMoving which checks movement flags (HB 4.3.4 style). |
| Public property | [IsNeutral](WoWUnit/Properties/IsNeutral_7CE10332DDF0.md) | Gets a value indicating whether is neutral. |
| Public property | [IsNonCombatPet](WoWUnit/Properties/IsNonCombatPet_A99EFFC16514.md) | Gets a value indicating whether is non combat pet. |
| Public property | [IsOnTransport](WoWUnit/Properties/IsOnTransport_8B7B4CB9F01F.md) | Gets a value indicating whether is on transport. |
| Public property | [IsPet](WoWUnit/Properties/IsPet_49B3BA6C600B.md) | BUG-08 fix: Check GUID instead of expensive ObjectManager lookup. HB 4.3.4 checks both SummonedByGuid and CharmedByGuid. |
| Public property | [IsPetitioner](WoWUnit/Properties/IsPetitioner_22A58A5E941E.md) | Gets a value indicating whether is petitioner. |
| Public property | [IsPlayer](WoWUnit/Properties/IsPlayer_C964CF20345B.md) | Gets a value indicating whether is player. |
| Public property | [IsPlayerBehind](WoWUnit/Properties/IsPlayerBehind_8A55BF741C2B.md) | Gets a value indicating whether is player behind. |
| Public property | [IsPoisonVendor](WoWUnit/Properties/IsPoisonVendor_04BF76420328.md) | Gets a value indicating whether is poison vendor. |
| Public property | [IsProfessionTrainer](WoWUnit/Properties/IsProfessionTrainer_46DAC9DCD3CF.md) | Gets a value indicating whether is profession trainer. |
| Public property | [IsQuestGiver](WoWUnit/Properties/IsQuestGiver_E98BC5B0704F.md) | Gets a value indicating whether is quest giver. |
| Public property | [IsReagentVendor](WoWUnit/Properties/IsReagentVendor_5BA908020AE1.md) | Gets a value indicating whether is reagent vendor. |
| Public property | [IsRepairMerchant](WoWUnit/Properties/IsRepairMerchant_F1904E8DD141.md) | Gets a value indicating whether is repair merchant. |
| Public property | [IsSpiritGuide](WoWUnit/Properties/IsSpiritGuide_DA12220D849B.md) | Gets a value indicating whether is spirit guide. |
| Public property | [IsSpiritHealer](WoWUnit/Properties/IsSpiritHealer_92FBF5F6D999.md) | Gets a value indicating whether is spirit healer. |
| Public property | [IsStableMaster](WoWUnit/Properties/IsStableMaster_3385F56A3EEF.md) | Gets a value indicating whether is stable master. |
| Public property | [IsStealthed](WoWUnit/Properties/IsStealthed_DCC724CD6567.md) | Gets a value indicating whether is stealthed. |
| Public property | [IsSwimming](WoWUnit/Properties/IsSwimming_2F1FA8A3525D.md) | Gets a value indicating whether is swimming. |
| Public property | [IsTabardDesigner](WoWUnit/Properties/IsTabardDesigner_CE89D0E9B73E.md) | Gets a value indicating whether is tabard designer. |
| Public property | [IsTameable](WoWUnit/Properties/IsTameable_D6E1E3046FCF.md) | Gets a value indicating whether is tameable. |
| Public property | [IsTargetingAnyMinion](WoWUnit/Properties/IsTargetingAnyMinion_4D5C30C2C698.md) | HB 4.3.4 compatible helper – returns true when any of the player's minions (pets) is currently targeting this unit. Used by Targeting filters to keep attackers on the list even if their Aggro flag hasn't flipped yet. |
| Public property | [IsTargetingMe](WoWUnit/Properties/IsTargetingMe_6D1D96743E25.md) | Gets a value indicating whether is targeting me. |
| Public property | [IsTargetingMeOrPet](WoWUnit/Properties/IsTargetingMeOrPet_E11552A0FD84.md) | Gets a value indicating whether is targeting me or pet. |
| Public property | [IsTargetingMyPartyMember](WoWUnit/Properties/IsTargetingMyPartyMember_647EB8918D45.md) | Gets a value indicating whether is targeting my party member. |
| Public property | [IsTargetingMyRaidMember](WoWUnit/Properties/IsTargetingMyRaidMember_7E6DAF989754.md) | Gets a value indicating whether is targeting my raid member. |
| Public property | [IsTargetingPet](WoWUnit/Properties/IsTargetingPet_4FE3A0EA649F.md) | Gets a value indicating whether is targeting pet. |
| Public property | [IsTotem](WoWUnit/Properties/IsTotem_24637692C3F4.md) | Gets a value indicating whether is totem. |
| Public property | [IsTrainer](WoWUnit/Properties/IsTrainer_6ACA3C9013B6.md) | Gets a value indicating whether is trainer. |
| Public property | [IsUndead](WoWUnit/Properties/IsUndead_450129C018CB.md) | Gets a value indicating whether is undead. |
| Public property | [IsUnit](WoWUnit/Properties/IsUnit_275626CAE06E.md) | Gets a value indicating whether is unit. |
| Public property | [IsVendor](WoWUnit/Properties/IsVendor_BA716931BE9B.md) | Gets a value indicating whether is vendor. |
| Public property | [IsWithinMeleeRange](WoWUnit/Properties/IsWithinMeleeRange_56730194FB11.md) | Returns true if this unit is within melee range of the player. |
| Public property | [KilledByMe](WoWUnit/Properties/KilledByMe_BAD54B53524D.md) | Gets a value indicating whether killed by me. |
| Public property | [Level](WoWUnit/Properties/Level_F12CCE47CCC3.md) | Gets the level. |
| Public property | [Location](WoWUnit/Properties/Location_0DB03816A45E.md) | Gets the location. (Overrides WoWObject.Location.) |
| Public property | [Lootable](WoWUnit/Properties/Lootable_EA94A0CADDC5.md) | Gets a value indicating whether lootable. |
| Public property | [Looting](WoWUnit/Properties/Looting_9162F1E9D2F4.md) | Gets a value indicating whether looting. |
| Public property | [ManaInfo](WoWUnit/Properties/ManaInfo_CCD22A025CBF.md) | Convenience: ManaInfo. |
| Public property | [ManaPercent](WoWUnit/Properties/ManaPercent_66412DF6D45A.md) | Gets the mana percent. |
| Public property | [MaxDamage](WoWUnit/Properties/MaxDamage_C8A90B64653B.md) | Max melee damage (UNIT_FIELD_MAXDAMAGE). |
| Public property | [MaxEclipse](WoWUnit/Properties/MaxEclipse_869AA47A3168.md) | Max Eclipse (Cataclysm+ only). Always 0 in WotLK. |
| Public property | [MaxEnergy](WoWUnit/Properties/MaxEnergy_7CD5EF9E4956.md) | Gets the max energy. |
| Public property | [MaxFocus](WoWUnit/Properties/MaxFocus_471B6C23AE69.md) | Gets the max focus. |
| Public property | [MaxHappiness](WoWUnit/Properties/MaxHappiness_DE723691B7AD.md) | Gets the max happiness. |
| Public property | [MaxHealth](WoWUnit/Properties/MaxHealth_D3D87FFA2370.md) | Gets the max health. |
| Public property | [MaxHealthModifier](WoWUnit/Properties/MaxHealthModifier_B94F6E92C0C5.md) | Health multiplier (UNIT_FIELD_MAXHEALTHMODIFIER). |
| Public property | [MaxHolyPower](WoWUnit/Properties/MaxHolyPower_E70B1335A72A.md) | Max Holy Power (Cataclysm+ only). Always 0 in WotLK. |
| Public property | [MaxMana](WoWUnit/Properties/MaxMana_77AACC4821EA.md) | Gets the max mana. |
| Public property | [MaxOffHandDamage](WoWUnit/Properties/MaxOffHandDamage_3A472C6E09C8.md) | Max off-hand damage (UNIT_FIELD_MAXOFFHANDDAMAGE). |
| Public property | [MaxPower](WoWUnit/Properties/MaxPower_2AD3C0325757.md) | Gets the max power. |
| Public property | [MaxRage](WoWUnit/Properties/MaxRage_75D7DA6EE503.md) | Gets the max rage. |
| Public property | [MaxRangedDamage](WoWUnit/Properties/MaxRangedDamage_DFBC064409BE.md) | Max ranged damage (UNIT_FIELD_MAXRANGEDDAMAGE). |
| Public property | [MaxRunicPower](WoWUnit/Properties/MaxRunicPower_ED92F97E974C.md) | Gets the max runic power. |
| Public property | [MaxSoulShards](WoWUnit/Properties/MaxSoulShards_4C3B293146E2.md) | Max Soul Shards (Cataclysm+ only). Always 0 in WotLK. |
| Public property | [MeleeReach](WoWUnit/Properties/MeleeReach_6DD4F4822C6C.md) | Gets the melee reach for this unit. Special cases for certain NPCs, otherwise CombatReach + 2. |
| Public property | [MinDamage](WoWUnit/Properties/MinDamage_E2B862E747ED.md) | Min melee damage (UNIT_FIELD_MINDAMAGE). |
| Public property | [MinOffHandDamage](WoWUnit/Properties/MinOffHandDamage_1018A339054F.md) | Min off-hand damage (UNIT_FIELD_MINOFFHANDDAMAGE). |
| Public property | [MinRangedDamage](WoWUnit/Properties/MinRangedDamage_728B0AFA2F63.md) | Min ranged damage (UNIT_FIELD_MINRANGEDDAMAGE). |
| Public property | [MountDisplayId](WoWUnit/Properties/MountDisplayId_B9371ADD9F3A.md) | Gets the mount display id. |
| Public property | [Mounted](WoWUnit/Properties/Mounted_E10582AE9930.md) | Gets a value indicating whether mounted. |
| Public property | [MovementFlags](WoWUnit/Properties/MovementFlags_3F918222B431.md) | Gets the movement flags. |
| Public property | [MovementInfo](WoWUnit/Properties/MovementInfo_53E3290EF0CE.md) | Movement information for this unit. Alias for WoWMovementInfo for HB 4.3.4 compatibility. |
| Public property | [MyAggroRange](WoWUnit/Properties/MyAggroRange_E0B847E716DA.md) | Gets the my aggro range. |
| Public property | [MyReaction](WoWUnit/Properties/MyReaction_7B2268F0CFED.md) | Gets the my reaction. |
| Public property | [MyStealthDetectionRange](WoWUnit/Properties/MyStealthDetectionRange_DDFADCD45F93.md) | Gets the my stealth detection range. |
| Public property | [NativeDisplayId](WoWUnit/Properties/NativeDisplayId_51B44880F5FF.md) | FEAT-13: Native (original) display ID before model changes (UNIT_FIELD_NATIVEDISPLAYID). |
| Public property | [NatureResist](WoWUnit/Properties/NatureResist_27C47F7C9C21.md) | Gets the nature resist. |
| Public property | [NonChanneledCastingSpellId](WoWUnit/Properties/NonChanneledCastingSpellId_B002314BA50B.md) | Returns the raw non-channeled casting spell ID (offset 2668). HB 4.3.4 compatibility — reads only the non-channeled cast. |
| Public property | [NpcEmoteState](WoWUnit/Properties/NpcEmoteState_9DD3941E96B7.md) | NPC emote state (UNIT_NPC_EMOTESTATE). |
| Public property | [OnTaxi](WoWUnit/Properties/OnTaxi_519084EF1024.md) | Gets a value indicating whether on taxi. |
| Public property | [OwnedByRoot](WoWUnit/Properties/OwnedByRoot_34F8F614F496.md) | Gets the owned by root. |
| Public property | [OwnedByUnit](WoWUnit/Properties/OwnedByUnit_2DB5AF97DABB.md) | Gets the owned by unit. |
| Public property | [Pacified](WoWUnit/Properties/Pacified_FE7548153229.md) | Gets a value indicating whether pacified. |
| Public property | [PassiveAuras](WoWUnit/Properties/PassiveAuras_E5B47DA1F664.md) | Gets the passive auras. |
| Public property | [Pet](WoWUnit/Properties/Pet_4D9CA6E09BC5.md) | Gets the pet. |
| Public property | [PetAggro](WoWUnit/Properties/PetAggro_766D40A23B92.md) | Gets a value indicating whether pet aggro. |
| Public property | [PetExperience](WoWUnit/Properties/PetExperience_E7C3F879792D.md) | Pet XP (UNIT_FIELD_PETEXPERIENCE). |
| Public property | [PetInCombat](WoWUnit/Properties/PetInCombat_5ECF316CA277.md) | Gets a value indicating whether pet in combat. |
| Public property | [PetNextLevelExperience](WoWUnit/Properties/PetNextLevelExperience_9841262AAFF9.md) | Pet XP to next level (UNIT_FIELD_PETNEXTLEVELEXP). |
| Public property | [PetNumber](WoWUnit/Properties/PetNumber_811606D8D523.md) | Pet tracking number (UNIT_FIELD_PETNUMBER). |
| Public property | [PlayerControlled](WoWUnit/Properties/PlayerControlled_FE670DED188D.md) | Gets a value indicating whether player controlled. |
| Public property | [Possessed](WoWUnit/Properties/Possessed_302F9874BBAC.md) | Gets a value indicating whether possessed. |
| Public property | [PowerPercent](WoWUnit/Properties/PowerPercent_3D93C5142592.md) | Generic power percent — auto-selects the unit's active power type. |
| Public property | [PowerType](WoWUnit/Properties/PowerType_B4044346AD4E.md) | Gets the power type. |
| Public property | [PvpFlagged](WoWUnit/Properties/PvpFlagged_4296443F40E4.md) | Gets a value indicating whether pvp flagged. |
| Public property | [Race](WoWUnit/Properties/Race_4E6BFD3D7E0C.md) | Gets the race. |
| Public property | [RafLinked](WoWUnit/Properties/RafLinked_D007F5F47579.md) | Gets a value indicating whether raf linked. |
| Public property | [RageInfo](WoWUnit/Properties/RageInfo_FAFDF6246BF3.md) | Convenience: RageInfo. |
| Public property | [RagePercent](WoWUnit/Properties/RagePercent_2398FAA009D4.md) | Gets the rage percentage (0-100). Used by Warriors. |
| Public property | [RangedAttackPower](WoWUnit/Properties/RangedAttackPower_A5FC1A234E96.md) | Ranged attack power (UNIT_FIELD_RANGED_ATTACK_POWER). |
| Public property | [RangedAttackPowerMods](WoWUnit/Properties/RangedAttackPowerMods_AAEC6C3B0C9A.md) | Ranged attack power modifiers (UNIT_FIELD_RANGED_ATTACK_POWER_MODS). |
| Public property | [RangedAttackPowerMultiplier](WoWUnit/Properties/RangedAttackPowerMultiplier_6DEFA7FF1B47.md) | Ranged attack power multiplier (UNIT_FIELD_RANGED_ATTACK_POWER_MULTIPLIER). |
| Public property | [RelativeLocation](WoWUnit/Properties/RelativeLocation_1EFC532BFD5E.md) | Raw transport-local position (from CMovementData). Use Location for world coords. |
| Public property | [RenderFacing](WoWUnit/Properties/RenderFacing_A9A04E7851C2.md) | Gets the render facing. |
| Public property | [Rooted](WoWUnit/Properties/Rooted_569FED559601.md) | Gets a value indicating whether rooted. |
| Public property | [Rotation](WoWUnit/Properties/Rotation_D912D0679AF0.md) | Gets the rotation. (Overrides WoWObject.Rotation.) |
| Public property | [RunesPercent](WoWUnit/Properties/RunesPercent_74994A815841.md) | Runes percentage (DK). WotLK-valid. |
| Public property | [RunesPowerInfo](WoWUnit/Properties/RunesPowerInfo_FB51C688A53F.md) | Convenience: RunesPowerInfo (DK). WotLK-valid. |
| Public property | [RunicPowerInfo](WoWUnit/Properties/RunicPowerInfo_9CE1583F3881.md) | Convenience: RunicPowerInfo. |
| Public property | [RunicPowerPercent](WoWUnit/Properties/RunicPowerPercent_D74EDB7A9BFF.md) | Gets the runic power percentage (0-100). Used by Death Knights. |
| Public property | [ShadowResist](WoWUnit/Properties/ShadowResist_FFA64A4AC661.md) | Gets the shadow resist. |
| Public property | [Shapeshift](WoWUnit/Properties/Shapeshift_B805A4BFB372.md) | Gets the shapeshift. |
| Public property | [Silenced](WoWUnit/Properties/Silenced_DE5515BBA8A0.md) | Gets a value indicating whether silenced. |
| Public property | [SkinType](WoWUnit/Properties/SkinType_CBEDCBB9CB42.md) | Gets the skin type. |
| Public property | [Skinnable](WoWUnit/Properties/Skinnable_09D5FEE0E4C8.md) | Gets a value indicating whether skinnable. |
| Public property | [SoulShardsInfo](WoWUnit/Properties/SoulShardsInfo_DFFC14C1C410.md) | Gets the soul shards info. |
| Public property | [SoulShardsPercent](WoWUnit/Properties/SoulShardsPercent_B59308EAF7DB.md) | Gets the soul shards percent. |
| Public property | [Spirit](WoWUnit/Properties/Spirit_78781B4C321D.md) | Gets the spirit. |
| Public property | [SpiritBonus](WoWUnit/Properties/SpiritBonus_2ED1BFB33F50.md) | Gets the spirit bonus. |
| Public property | [SpiritNegativeModifier](WoWUnit/Properties/SpiritNegativeModifier_5EB9017EAEEB.md) | FEAT-25: Negative spirit modifier (UNIT_FIELD_NEGSTAT4). |
| Public property | [Stamina](WoWUnit/Properties/Stamina_67679F927BD3.md) | Gets the stamina. |
| Public property | [StaminaBonus](WoWUnit/Properties/StaminaBonus_3024B0393F80.md) | Gets the stamina bonus. |
| Public property | [StaminaNegativeModifier](WoWUnit/Properties/StaminaNegativeModifier_6AC744AECA28.md) | FEAT-25: Negative stamina modifier (UNIT_FIELD_NEGSTAT2). |
| Public property | [StateFlag](WoWUnit/Properties/StateFlag_6BC5E4F6ADFF.md) | Gets the state flag. |
| Public property | [Strength](WoWUnit/Properties/Strength_F034B5D164C3.md) | Gets the strength. |
| Public property | [StrengthBonus](WoWUnit/Properties/StrengthBonus_6532B5008DB2.md) | Gets the strength bonus. |
| Public property | [StrengthNegativeModifier](WoWUnit/Properties/StrengthNegativeModifier_B1543E97311D.md) | FEAT-25: Negative strength modifier (UNIT_FIELD_NEGSTAT0). |
| Public property | [Stunned](WoWUnit/Properties/Stunned_AFE34D369C47.md) | Gets a value indicating whether stunned. |
| Public property | [SubName](WoWUnit/Properties/SubName_D80EB456DBC7.md) | Creature subtitle/guild text from cache. |
| Public property | [Summon](WoWUnit/Properties/Summon_2CF87292EC3C.md) | Gets the summon. |
| Public property | [SummonedBy](WoWUnit/Properties/SummonedBy_B5296B16F3FD.md) | Gets the summoned by. |
| Public property | [SummonedByGuid](WoWUnit/Properties/SummonedByGuid_4E9EE3ACBEEA.md) | Gets the summoned by guid. |
| Public property | [SummonedUnit](WoWUnit/Properties/SummonedUnit_E82B84E8067D.md) | Gets the summoned unit. |
| Public property | [SummonedUnitGuid](WoWUnit/Properties/SummonedUnitGuid_D19D8D35214C.md) | Gets the summoned unit guid. |
| Public property | [Tagged](WoWUnit/Properties/Tagged_9B3ACB5D7DD5.md) | Gets a value indicating whether tagged. |
| Public property | [TaggedByMe](WoWUnit/Properties/TaggedByMe_28F83DD44071.md) | Gets a value indicating whether tagged by me. |
| Public property | [TaggedByOther](WoWUnit/Properties/TaggedByOther_EE0D8D9F6645.md) | Gets a value indicating whether tagged by other. |
| Public property | [TappedByAllThreatLists](WoWUnit/Properties/TappedByAllThreatLists_8CB000C2EB42.md) | Gets a value indicating whether tapped by all threat lists. |
| Public property | [ThreatInfo](WoWUnit/Properties/ThreatInfo_748D7B89BE4A.md) | Gets the threat info. |
| Public property | [Tracked](WoWUnit/Properties/Tracked_E835C8D15394.md) | Gets a value indicating whether tracked. |
| Public property | [Transport](WoWUnit/Properties/Transport_3A3A57FC3492.md) | Gets the transport. |
| Public property | [VanityPet](WoWUnit/Properties/VanityPet_87452C6AD0AB.md) | Gets the vanity pet. |
| Public property | [VanityPetGuid](WoWUnit/Properties/VanityPetGuid_E9B13F544B50.md) | Gets the vanity pet guid. |
| Public property | [VirtualItemSlotIds](WoWUnit/Properties/VirtualItemSlotIds_23459AC95D6F.md) | Visual weapon slot IDs (UNIT_VIRTUAL_ITEM_SLOT_ID, 3 entries). |
| Public property | [WoWMovementInfo](WoWUnit/Properties/WoWMovementInfo_1CAA90756BE6.md) | Gets the wow movement info. |
| Public property | [X](WoWUnit/Properties/X_3138615C89A0.md) | Gets the x. (Overrides WoWObject.X.) |
| Public property | [Y](WoWUnit/Properties/Y_2E1B6FFA7DAA.md) | Gets the y. (Overrides WoWObject.Y.) |
| Public property | [Z](WoWUnit/Properties/Z_56362C6EAEB5.md) | Gets the z. (Overrides WoWObject.Z.) |
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
| Public property | [Type](WoWObject/Properties/Type_B75E2D6A00EB.md) | Gets the type. (Inherited from WoWObject.) |
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
| Public method | [Behind(WoWUnit)](WoWUnit/Methods/Behind_BEE118393F27.md) | Determines whether this unit is behind the specified unit. |
| Public method | [Distance2DTo(WoWUnit)](WoWUnit/Methods/Distance2DTo_6C065309740F.md) | Returns the 2D distance to another unit (ignoring Z axis). |
| Public method | [Face](WoWUnit/Methods/Face_B70BFDBF3DE7.md) | Faces the target. |
| Public method | [GetAggroRange(WoWUnit)](WoWUnit/Methods/GetAggroRange_C05CD8718DA3.md) | Gets the aggro range. |
| Public method | [GetAllAuras](WoWUnit/Methods/GetAllAuras_6AABB29CB43B.md) | Gets the all auras. |
| Public method | [GetAuraById(int)](WoWUnit/Methods/GetAuraById_98C41DC8818F.md) | Gets an aura by its spell ID. |
| Public method | [GetAuraByName(string)](WoWUnit/Methods/GetAuraByName_D5AA1306F2E2.md) | Gets the aura by name. |
| Public method | [GetBuffs(bool)](WoWUnit/Methods/GetBuffs_A243A9DEE6C7.md) | Gets the buffs. |
| Public method | [GetCachedInfo(CreatureCacheEntry)](WoWUnit/Methods/GetCachedInfo_58C1DD7304F8.md) | Gets the cached info. |
| Public method | [GetCurrentPower(WoWPowerType)](WoWUnit/Methods/GetCurrentPower_BAC717F06077.md) | Gets the current power. |
| Protected method | [GetLuaUnitId](WoWUnit/Methods/GetLuaUnitId_C2220395FAAE.md) | Maps this unit to a WoW Lua unitId string for API calls. Returns empty string if no known unitId matches this unit. |
| Public method | [GetMaxPower(WoWPowerType)](WoWUnit/Methods/GetMaxPower_E090646B4FD5.md) | Gets the max power. |
| Public method | [GetPowerCostModifier(WoWPowerType)](WoWUnit/Methods/GetPowerCostModifier_1A04C0838495.md) | Gets the flat power cost modifier for the specified power type. Index into UNIT_FIELD_POWER_COST_MODIFIER (7 entries starting at 0x83). |
| Public method | [GetPowerCostMultiplier(WoWPowerType)](WoWUnit/Methods/GetPowerCostMultiplier_BC88A2330478.md) | Gets the percent power cost multiplier for the specified power type. Index into UNIT_FIELD_POWER_COST_MULTIPLIER (7 entries starting at 0x8A). |
| Public method | [GetPowerInfo(WoWPowerType)](WoWUnit/Methods/GetPowerInfo_654C1785A74A.md) | Gets structured power info for the specified power type. |
| Public method | [GetPowerPercent(WoWPowerType)](WoWUnit/Methods/GetPowerPercent_25485169327B.md) | Gets the power percent. |
| Public method | [GetPowerRegenFlat(WoWPowerType)](WoWUnit/Methods/GetPowerRegenFlat_30AA790B84C5.md) | Gets the flat regen rate for the specified power type. Index into UNIT_FIELD_POWER_REGEN_FLAT_MODIFIER (7 entries starting at 0x28). |
| Public method | [GetPowerRegenInterrupted(WoWPowerType)](WoWUnit/Methods/GetPowerRegenInterrupted_F530BAAA4FBB.md) | Gets the interrupted (combat) regen rate for the specified power type. Index into UNIT_FIELD_POWER_REGEN_INTERRUPTED_FLAT_MODIFIER (7 entries starting at 0x2F). |
| Public method | [GetReactionTowards(WoWUnit)](WoWUnit/Methods/GetReactionTowards_4CC93AFEEDB8.md) | Gets the reaction towards. |
| Public method | [GetStealthDetectionRange(WoWUnit)](WoWUnit/Methods/GetStealthDetectionRange_7AD2FF7FECDE.md) | Gets the stealth detection range. |
| Public method | [GetThreatInfoFor(WoWUnit)](WoWUnit/Methods/GetThreatInfoFor_B98D6DD67971.md) | Gets the threat info for. |
| Public method | [GetTraceLinePos](WoWUnit/Methods/GetTraceLinePos_B493A20D94E7.md) | Gets the trace line pos. |
| Public method | [GetWorldPosition](WoWUnit/Methods/GetWorldPosition_AE708D04B0F7.md) | Returns the world-space position of this unit. When on a transport (elevator, ship), transforms the transport-local position by the transport's world matrix (read from GO BaseAddress + 0x1A8). Matches HB 3.3.5a's GetWorldPosition(). |
| Public method | [HasAura(int)](WoWUnit/Methods/HasAura_F20427A069FE.md) | Checks if the unit has an aura with the specified spell ID. |
| Public method | [HasAura(string)](WoWUnit/Methods/HasAura_DCB74C287DBA.md) | Determines whether has aura. |
| Public method | [HasAuraWithMechanic(WoWSpellMechanic)](WoWUnit/Methods/HasAuraWithMechanic_5E9556CAB295.md) | Checks if the unit has any aura with the specified spell mechanic. |
| Public method | [HasUnitDynamicFlag(UnitDynamicFlags)](WoWUnit/Methods/HasUnitDynamicFlag_4DBD681B9551.md) | Public method to check if unit has a specific dynamic flag. |
| Public method | [IsDueling(WoWUnit)](WoWUnit/Methods/IsDueling_2E0735C3AA8D.md) | Checks if this unit is dueling another unit. Both units must be player-controlled and have matching duel arbiters but different teams. |
| Public method | [IsWithinMeleeRangeOf(WoWUnit)](WoWUnit/Methods/IsWithinMeleeRangeOf_BDCD1B0C7D19.md) | Returns true if this unit is within melee range of another unit. |
| Public method | [Target](WoWUnit/Methods/Target_E384D1CE7F3B.md) | Targets the unit. |
| Public method | [ToWoWUnit](WoWUnit/Methods/ToWoWUnit_98BCBBCBCD4A.md) | Converts to wow unit. |
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
