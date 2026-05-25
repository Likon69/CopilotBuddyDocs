# WoWSpell Class

Represents a wow spell.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Combat.WoWSpell

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWSpell : IEquatable<WoWSpell>
```

The WoWSpell type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [AttributesEx](WoWSpell/Properties/AttributesEx_3489D1344D2E.md) | Gets the attributes ex. |
| Public property | [BaseCooldown](WoWSpell/Properties/BaseCooldown_C43B6C2B2307.md) | Gets the base cooldown. |
| Public property | [BaseDuration](WoWSpell/Properties/BaseDuration_2FEDE83341D2.md) | Gets the base duration. |
| Public property | [BaseLevel](WoWSpell/Properties/BaseLevel_7D91324A73AB.md) | Gets the base level. |
| Public property | [CanCast](WoWSpell/Properties/CanCast_00FE6C2648D9.md) | Returns true if the spell is currently usable (power, stance, equipped items, etc.) AND not on cooldown. HB 4.3.4 WoWSpell.cs: delegates to IsUsableSpell Lua. IsUsableSpell in WoW 3.3.5a does NOT check cooldowns — we pre-check Cooldown (ASM-based, language-independent) so that instant off-GCD spells like Blood Fury are never reported as castable while on their 2-minute cooldown. |
| Public property | [CastTime](WoWSpell/Properties/CastTime_586F00885207.md) | Gets the cast time. |
| Public property | [Category](WoWSpell/Properties/Category_E257BBC7BFAF.md) | Gets the category. |
| Public property | [Cooldown](WoWSpell/Properties/Cooldown_E919D913851D.md) | Gets a value indicating whether cooldown. |
| Public property | [CooldownTimeLeft](WoWSpell/Properties/CooldownTimeLeft_04BED421882B.md) | Gets the remaining cooldown time for this spell. WotLK 3.3.5a: GetSpellCooldown() requires the spell name in the CLIENT'S LANGUAGE. Passing the English name fails on non-English clients (e.g. "Blood Fury" on a Russian client where the spell is "\208\175\209\128\208\190\209\129\209\130\209\140 \208\186\209\128\208\190\208\178\208\184"). Fix: use GetSpellInfo(id) to get the localized name first — language-independent. |
| Public property | [CreatesItemId](WoWSpell/Properties/CreatesItemId_2321CC627190.md) | Gets the creates item id. |
| Public property | [Description](WoWSpell/Properties/Description_471BF43F1E28.md) | Gets the description. |
| Public property | [DispelType](WoWSpell/Properties/DispelType_B3ADB0072286.md) | Gets the dispel type. |
| Public property | [DurationPerLevel](WoWSpell/Properties/DurationPerLevel_4FA523B1DF14.md) | Gets the duration per level. |
| Public property | [HasRange](WoWSpell/Properties/HasRange_2818DE8CBBBD.md) | Gets a value indicating whether has range. |
| Public property | [Id](WoWSpell/Properties/Id_E66C14606EC5.md) | Gets the id. |
| Public property | [InternalInfo](WoWSpell/Properties/InternalInfo_CE0212D83158.md) | Gets the internal info. |
| Public property | [IsChanneled](WoWSpell/Properties/IsChanneled_D669F8EB39E5.md) | Returns true if this spell is channeled. Checks AttributesEx for channeled flag (0x44). |
| Public property | [IsFunnel](WoWSpell/Properties/IsFunnel_751E2012E42C.md) | Gets a value indicating whether is funnel. |
| Public property | [IsMeleeSpell](WoWSpell/Properties/IsMeleeSpell_964B6D2836EF.md) | Returns true if this is a melee-range spell (SpellRangeId == 2). Does NOT include self-only spells (RangeId == 1). Matches HB 4.3.4. |
| Public property | [IsSelfOnlySpell](WoWSpell/Properties/IsSelfOnlySpell_E34F8C91B34A.md) | Returns true if this spell can only target self. FEAT-08: Uses synthetic rangeId (Lua-based MaxRange == 0). |
| Public property | [IsValid](WoWSpell/Properties/IsValid_C4E2071CE885.md) | Gets a value indicating whether is valid. |
| Public property | [Level](WoWSpell/Properties/Level_455E5D79E210.md) | Gets the level. |
| Public property | [ManaCostPercent](WoWSpell/Properties/ManaCostPercent_83BBC4EBBCAF.md) | Gets the mana cost percent. |
| Public property | [MaxDuration](WoWSpell/Properties/MaxDuration_11B59386DE6B.md) | Gets the max duration. |
| Public property | [MaxRange](WoWSpell/Properties/MaxRange_EEA81704A9D2.md) | Gets the max range. |
| Public property | [MaxStackCount](WoWSpell/Properties/MaxStackCount_F33E18438385.md) | Gets the max stack count. |
| Public property | [MaxTargets](WoWSpell/Properties/MaxTargets_2FFC9A231941.md) | Gets the max targets. |
| Public property | [Mechanic](WoWSpell/Properties/Mechanic_524F804F9787.md) | Gets the mechanic. |
| Public property | [MinRange](WoWSpell/Properties/MinRange_3A4801FE41E7.md) | Gets the min range. |
| Public property | [Name](WoWSpell/Properties/Name_DE9B89B07791.md) | Gets the name. |
| Public property | [PowerCost](WoWSpell/Properties/PowerCost_A7DFFF8DFC95.md) | Gets the power cost. |
| Public property | [PowerType](WoWSpell/Properties/PowerType_7203A401307B.md) | Gets the power type. |
| Public property | [RangeDescription](WoWSpell/Properties/RangeDescription_17EBE268AED8.md) | Gets the range description. |
| Public property | [Rank](WoWSpell/Properties/Rank_2B219112031E.md) | Gets the rank. |
| Public property | [School](WoWSpell/Properties/School_02A00F759C42.md) | Gets the school. |
| Public property | [SpellEffect1](WoWSpell/Properties/SpellEffect1_3E304C302B39.md) | Gets the spell effect1. |
| Public property | [SpellEffect2](WoWSpell/Properties/SpellEffect2_D7FD3D326124.md) | Gets the spell effect2. |
| Public property | [SpellEffect3](WoWSpell/Properties/SpellEffect3_050A32F71179.md) | Gets the spell effect3. |
| Public property | [SpellEffects](WoWSpell/Properties/SpellEffects_39487AF89255.md) | Gets the spell effects. |
| Public property | [SpellRangeId](WoWSpell/Properties/SpellRangeId_A848B0775224.md) | Gets the spell range ID for combat routine range checks. Uses Lua-based MinRange/MaxRange which are reliable and match what Singular expects: 1 = Self Only (max=0), 2 = Melee (max≤5), 3+ = Ranged. Note: DBC rangeIndex is available via RangeIndex property for DBC lookups. |
| Public property | [TargetType](WoWSpell/Properties/TargetType_15A1080B31F4.md) | Gets the target type. |
| Public property | [Tooltip](WoWSpell/Properties/Tooltip_08C0DAAA7CF9.md) | Gets the tooltip. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Cast](WoWSpell/Methods/Cast_DD0C1EDAD7DA.md) | Casts the spell. |
| Public method | [Equals(WoWSpell)](WoWSpell/Methods/Equals_20C7D63D8F06.md) | Determines whether the specified object is equal to the current object. |
| Public method Static member | [FromId(int)](WoWSpell/Methods/FromId_39FCC4EE4E49.md) | Gets the instance for the specified ID. |
| Public method | [GetSpellEffect(int)](WoWSpell/Methods/GetSpellEffect_4C2CB17DFB10.md) | Gets the spell effect. |
| Public method | [ToString](WoWSpell/Methods/ToString_37D226F8A33D.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
