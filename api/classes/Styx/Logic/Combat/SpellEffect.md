# SpellEffect Class

Represents a single spell effect within a WoW spell. Each spell can have up to 3 effects (SpellEffect1, SpellEffect2, SpellEffect3). Contains all data about how the effect modifies targets, damage/healing values, etc.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Combat.SpellEffect

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class SpellEffect
```

The SpellEffect type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Amplitude](SpellEffect/Properties/Amplitude_0A1D2DF00997.md) | Amplitude for periodic effects (time between ticks in milliseconds). |
| Public property | [AuraType](SpellEffect/Properties/AuraType_F359E48A38D0.md) | The type of aura this effect applies (if it's an aura effect). Used to identify modifiers like ModStealth, ModStealthDetect, etc. |
| Public property | [BasePoints](SpellEffect/Properties/BasePoints_279A449070D0.md) | Base value of the effect (damage, healing, modifier amount, etc.). This is the primary value used in calculations like GetTotalAuraModifier. |
| Public property | [ChainTarget](SpellEffect/Properties/ChainTarget_9D4B34E205C2.md) | Number of targets the effect can chain to. |
| Public property | [EffectType](SpellEffect/Properties/EffectType_2330833DA47F.md) | The type of effect (Heal, SchoolDamage, ApplyAura, etc.). |
| Public property | [ImplicitTargetA](SpellEffect/Properties/ImplicitTargetA_6FA6EFC3B129.md) | First implicit target (who/what the effect targets). |
| Public property | [ImplicitTargetB](SpellEffect/Properties/ImplicitTargetB_646C06468DD1.md) | Second implicit target (alternative targeting). |
| Public property | [ItemType](SpellEffect/Properties/ItemType_D1661E3C61CA.md) | Item type requirement for the effect. |
| Public property | [Mechanic](SpellEffect/Properties/Mechanic_63C9CEFA2B4D.md) | Mechanic type of the effect (stun, root, etc.). |
| Public property | [MiscValueA](SpellEffect/Properties/MiscValueA_F6E5F3254CBB.md) | First miscellaneous value (usage varies by effect type). Examples: school mask, stat type, creature type, etc. |
| Public property | [MiscValueB](SpellEffect/Properties/MiscValueB_4412F94F1712.md) | Second miscellaneous value (usage varies by effect type). |
| Public property | [MultipleValue](SpellEffect/Properties/MultipleValue_C5BEA770D33A.md) | Multiplier value for certain effect calculations. |
| Public property | [PointsPerComboPoint](SpellEffect/Properties/PointsPerComboPoint_943A48533035.md) | Additional points gained per combo point spent. |
| Public property | [RadiusIndex](SpellEffect/Properties/RadiusIndex_66371D0F9B9E.md) | Index into SpellRadius.dbc (effect area of effect). |
| Public property | [RealPointsPerLevel](SpellEffect/Properties/RealPointsPerLevel_93C743CCD207.md) | Points gained per caster level (for scaling effects). |
| Public property | [SpellClassMask](SpellEffect/Properties/SpellClassMask_29D0AB1B27B1.md) | Spell class mask - identifies which spell classes this effect applies to. Used for talents that modify specific spell types. |
| Public property | [TriggerSpell](SpellEffect/Properties/TriggerSpell_837F718C01F9.md) | Spell ID that this effect triggers (if it triggers another spell). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [ToString](SpellEffect/Methods/ToString_DD2B097F1CE3.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
