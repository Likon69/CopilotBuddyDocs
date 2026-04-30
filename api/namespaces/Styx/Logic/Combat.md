# Styx.Logic.Combat Namespace

Contains combat-related types.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [Healing](../../../classes/Styx/Logic/Combat/Healing.md) | Helper class for healing and potion usage. WoW 3.3.5a build 12340. |
| Public class | [LegacySpellManager](../../../classes/Styx/Logic/Combat/LegacySpellManager.md) | Legacy spell manager wrapper for older Singular code compatibility. Wraps SpellManager methods for HB 3.3.5a/4.3.4 compatibility. |
| Public class | [RoutineManager](../../../classes/Styx/Logic/Combat/RoutineManager.md) | Manages combat routines - loads, compiles, and selects the appropriate routine. Follows HB pattern: Init() is called after WoW attachment when ObjectManager.Me is available. FEAT-37: Added CLI parsing, locking, improved selection. |
| Public class | [SpellCollection](../../../classes/Styx/Logic/Combat/SpellCollection.md) | FEAT-17: Typed wrapper for a player's known spells. Extends Dictionary for name-based lookup, matching HB 4.3.4 API. |
| Public class | [SpellEffect](../../../classes/Styx/Logic/Combat/SpellEffect.md) | Represents a single spell effect within a WoW spell. Each spell can have up to 3 effects (SpellEffect1, SpellEffect2, SpellEffect3). Contains all data about how the effect modifies targets, damage/healing values, etc. |
| Public class | [SpellManager](../../../classes/Styx/Logic/Combat/SpellManager.md) | Provides spell management functionality. |
| Public class | [SpellManagerEx](../../../classes/Styx/Logic/Combat/SpellManagerEx.md) | Extended spell manager with CanBuff/Buff/CastRandom/BuffRandom helpers. FEAT-06: All methods have been merged into SpellManager. This class is kept for backward compatibility only — new code should use SpellManager directly. |
| Public class | [WoWAura](../../../classes/Styx/Logic/Combat/WoWAura.md) | Represents an aura (buff/debuff) on a unit. Based on HonorBuddy 3.3.5a structure. |
| Public class | [WoWAuraCollection](../../../classes/Styx/Logic/Combat/WoWAuraCollection.md) | Collection class for WoWAura objects. Extends List<WoWAura> with helper methods for aura management. |
| Public class | [WoWPetSpell](../../../classes/Styx/Logic/Combat/WoWPetSpell.md) | Represents a wow pet spell. |
| Public class | [WoWSpell](../../../classes/Styx/Logic/Combat/WoWSpell.md) | Represents a wow spell. |

## Structures

| | Name | Description |
| --- | --- | --- |
| Public struct | [SpellClassMask](../../../classes/Styx/Logic/Combat/SpellClassMask.md) | Represents a 96-bit spell class mask (3 x 32-bit values). Used for spell family flags and effect class masks in WoW. |
| Public struct | [SpellCooldownInfo](../../../classes/Styx/Logic/Combat/SpellCooldownInfo.md) | FEAT-17: Spell cooldown tracking information. Represents the cooldown state of a single spell at a point in time. |
| Public struct | [SpellEntry](../../../classes/Styx/Logic/Combat/SpellEntry.md) | Represents a spell entry value. |

## Enumerations

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [SpellManager.MouseButton](../../../classes/Styx/Logic/Combat/SpellManager/MouseButton.md) | Represents values for Mouse Button. |
| Public enumeration | [WoWApplyAuraType](../../../classes/Styx/Logic/Combat/WoWApplyAuraType.md) | Types of aura effects that can be applied to units. This is the apply aura type from spell effects. |
| Public enumeration | [WoWAura.AuraFlags](../../../classes/Styx/Logic/Combat/WoWAura/AuraFlags.md) | Flags indicating the state and behavior of an aura. |
| Public enumeration | [WoWDispelType](../../../classes/Styx/Logic/Combat/WoWDispelType.md) | Represents values for WoW Dispel Type. |
| Public enumeration | [WoWPetSpell.PetAction](../../../classes/Styx/Logic/Combat/WoWPetSpell/PetAction.md) | Represents values for Pet Action. |
| Public enumeration | [WoWPetSpell.PetSpellType](../../../classes/Styx/Logic/Combat/WoWPetSpell/PetSpellType.md) | Represents values for Pet Spell Type. |
| Public enumeration | [WoWPetSpell.PetStance](../../../classes/Styx/Logic/Combat/WoWPetSpell/PetStance.md) | Represents values for Pet Stance. |
| Public enumeration | [WoWSpellEffectType](../../../classes/Styx/Logic/Combat/WoWSpellEffectType.md) | Types of spell effects used in WoW's spell system. Each spell can have up to 3 effects, each with one of these types. |
| Public enumeration | [WoWSpellFocus](../../../classes/Styx/Logic/Combat/WoWSpellFocus.md) | Spell focus requirements used by World of Warcraft spells. |
| Public enumeration | [WoWSpellMechanic](../../../classes/Styx/Logic/Combat/WoWSpellMechanic.md) | Spell mechanic values used by World of Warcraft spells. |
| Public enumeration | [WoWSpellSchool](../../../classes/Styx/Logic/Combat/WoWSpellSchool.md) | Represents values for WoW Spell School. |

## See Also
[Namespace Index](../../../index.md)
