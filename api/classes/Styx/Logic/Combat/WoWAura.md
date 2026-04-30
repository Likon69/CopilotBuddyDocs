# WoWAura Class

Represents an aura (buff/debuff) on a unit. Based on HonorBuddy 3.3.5a structure.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Combat.WoWAura

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWAura : IEquatable<WoWAura>
```

The WoWAura type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [WoWAura.AuraFlags](WoWAura/AuraFlags.md) | Flags indicating the state and behavior of an aura. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWAura(int, ulong, AuraFlags, ushort, byte, uint, uint)](WoWAura/Constructors/Constructor_98950920408D.md) | Creates a new WoWAura from individual values. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ApplyAuraType](WoWAura/Properties/ApplyAuraType_3216A1DFA9CD.md) | Gets the apply aura type from the first effect of the spell. |
| Public property | [Cancellable](WoWAura/Properties/Cancellable_7419F4F2AB38.md) | Gets whether this aura can be cancelled by the player. |
| Public property | [CreatorGuid](WoWAura/Properties/CreatorGuid_8ABBAF67046F.md) | Gets the GUID of the unit that created this aura. |
| Public property | [Duration](WoWAura/Properties/Duration_62BDF022AE9F.md) | Gets the total duration of this aura in milliseconds. |
| Public property | [EndTime](WoWAura/Properties/EndTime_67576E94D0FA.md) | Gets the performance counter value when this aura will end. |
| Public property | [Flags](WoWAura/Properties/Flags_0D138394D370.md) | Gets the flags for this aura. |
| Public property | [HasCaster](WoWAura/Properties/HasCaster_C5D0EE4D95CF.md) | Gets whether this aura has a known caster. |
| Public property | [HasNoDuration](WoWAura/Properties/HasNoDuration_5F9DC2B0F9CD.md) | Gets whether this aura has no duration (permanent). |
| Public property | [IsActive](WoWAura/Properties/IsActive_134A9C8036A8.md) | Gets whether this aura has any active effect. |
| Public property | [IsHarmful](WoWAura/Properties/IsHarmful_B8D61192A04B.md) | Gets whether this aura is harmful (a debuff). |
| Public property | [IsPassive](WoWAura/Properties/IsPassive_DA9FAE1CEBBD.md) | Gets whether this aura is passive (Unknown flag, commonly used). |
| Public property | [Level](WoWAura/Properties/Level_AD39569A8C3F.md) | Gets the level at which this aura was applied. |
| Public property | [Name](WoWAura/Properties/Name_717A124CFB42.md) | Gets the name of the spell associated with this aura. |
| Public property | [Rank](WoWAura/Properties/Rank_0BBD693A4826.md) | Gets the rank of the spell associated with this aura. |
| Public property | [Spell](WoWAura/Properties/Spell_1D83CDAB19AB.md) | Gets the spell associated with this aura. |
| Public property | [SpellId](WoWAura/Properties/SpellId_41B0A2866E45.md) | Gets the spell ID of this aura. |
| Public property | [StackCount](WoWAura/Properties/StackCount_2C293C0C8A1D.md) | Gets the current stack count of this aura. |
| Public property | [TimeLeft](WoWAura/Properties/TimeLeft_B05084475C85.md) | Gets the time remaining on this aura. |
| Public property | [TimeLeftMs](WoWAura/Properties/TimeLeftMs_7CA4526F7EA4.md) | Gets the time remaining in milliseconds. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Equals(object)](WoWAura/Methods/Equals_D3ED1C0A797A.md) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().) |
| Public method | [Equals(WoWAura)](WoWAura/Methods/Equals_EA7BB06118CE.md) | Determines whether the specified object is equal to the current object. |
| Public method | [GetHashCode](WoWAura/Methods/GetHashCode_98176DDDA82F.md) | Serves as a hash function for a particular type. (Overrides object.GetHashCode().) |
| Public method | [ToString](WoWAura/Methods/ToString_D7E9D8E03B7D.md) | Returns a string representation of this aura. (Overrides object.ToString().) |
| Public method | [TryCancel](WoWAura/Methods/TryCancel_419454D6DB43.md) | Attempts to cancel this aura (if it's cancellable). Only works for auras on the player. |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
