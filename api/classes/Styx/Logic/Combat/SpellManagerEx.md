# SpellManagerEx Class

Extended spell manager with CanBuff/Buff/CastRandom/BuffRandom helpers. FEAT-06: All methods have been merged into SpellManager. This class is kept for backward compatibility only — new code should use SpellManager directly.

## Inheritance Hierarchy
System.Object
  Styx.Logic.Combat.SpellManagerEx

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class SpellManagerEx
```

The SpellManagerEx type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [SpellManagerEx](SpellManagerEx/Constructors/Constructor_49E0915515E5.md) | Initializes a new instance of the SpellManagerEx class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [Spells](SpellManagerEx/Properties/Spells_16ACF353F22B.md) | Gets the spells. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Buff(string)](SpellManagerEx/Methods/Buff_E6320F799377.md) | Applies the buff. |
| Public method Static member | [Buff(int)](SpellManagerEx/Methods/Buff_D659837E645E.md) | Applies the buff. |
| Public method Static member | [Buff(WoWSpell)](SpellManagerEx/Methods/Buff_B702DECB53D3.md) | Applies the buff. |
| Public method Static member | [Buff(string, WoWUnit)](SpellManagerEx/Methods/Buff_69AA5B91D262.md) | Applies the buff. |
| Public method Static member | [Buff(int, WoWUnit)](SpellManagerEx/Methods/Buff_045480DE3690.md) | Applies the buff. |
| Public method Static member | [Buff(WoWSpell, WoWUnit)](SpellManagerEx/Methods/Buff_100857AA7A56.md) | Applies the buff. |
| Public method Static member | [BuffRandom(IEnumerable<string>, WoWUnit)](SpellManagerEx/Methods/BuffRandom_06931B8DACEA.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<string>, bool)](SpellManagerEx/Methods/BuffRandom_599141615959.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<int>, WoWUnit)](SpellManagerEx/Methods/BuffRandom_634BAF77AD66.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<int>, bool)](SpellManagerEx/Methods/BuffRandom_C7EC108D5CDF.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<WoWSpell>, WoWUnit)](SpellManagerEx/Methods/BuffRandom_0BA59C46CB7B.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<WoWSpell>, bool)](SpellManagerEx/Methods/BuffRandom_3A1F5B1E858E.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<string>, WoWUnit, bool)](SpellManagerEx/Methods/BuffRandom_420DE5A7ACCB.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<int>, WoWUnit, bool)](SpellManagerEx/Methods/BuffRandom_914067B3C947.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<WoWSpell>, WoWUnit, bool)](SpellManagerEx/Methods/BuffRandom_D7F8E87EA0BD.md) | Applies a random buff. |
| Public method Static member | [CanBuff(string)](SpellManagerEx/Methods/CanBuff_7E96C85B2E48.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(int)](SpellManagerEx/Methods/CanBuff_08AD9D2FEBF8.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(WoWSpell)](SpellManagerEx/Methods/CanBuff_676B4D5550FE.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(string, WoWUnit)](SpellManagerEx/Methods/CanBuff_5B7550A923ED.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(string, bool)](SpellManagerEx/Methods/CanBuff_276106030F21.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(int, WoWUnit)](SpellManagerEx/Methods/CanBuff_F437ACBDDC37.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(int, bool)](SpellManagerEx/Methods/CanBuff_BD37069080BC.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(WoWSpell, WoWUnit)](SpellManagerEx/Methods/CanBuff_F36EBB328FD0.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(WoWSpell, bool)](SpellManagerEx/Methods/CanBuff_702AC30563C8.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(string, WoWUnit, bool)](SpellManagerEx/Methods/CanBuff_9E3FECE28E53.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(int, WoWUnit, bool)](SpellManagerEx/Methods/CanBuff_C84AEE4FC0CC.md) | Determines whether can buff. |
| Public method Static member | [CanBuff(WoWSpell, WoWUnit, bool)](SpellManagerEx/Methods/CanBuff_3E1344BDE4B2.md) | Determines whether can buff. |
| Public method Static member | [CanCast(string)](SpellManagerEx/Methods/CanCast_4F03E6C32FC5.md) | Determines whether can cast. |
| Public method Static member | [CanCast(int)](SpellManagerEx/Methods/CanCast_B30F0C89EA82.md) | Determines whether can cast. |
| Public method Static member | [CanCast(WoWSpell)](SpellManagerEx/Methods/CanCast_7B149C5E2632.md) | Determines whether can cast. |
| Public method Static member | [CanCast(string, WoWUnit)](SpellManagerEx/Methods/CanCast_C1C404752321.md) | Determines whether can cast. |
| Public method Static member | [CanCast(string, bool)](SpellManagerEx/Methods/CanCast_CC6E15063FAC.md) | Determines whether can cast. |
| Public method Static member | [CanCast(int, WoWUnit)](SpellManagerEx/Methods/CanCast_CB741224E4AF.md) | Determines whether can cast. |
| Public method Static member | [CanCast(int, bool)](SpellManagerEx/Methods/CanCast_1402FB05BBB5.md) | Determines whether can cast. |
| Public method Static member | [CanCast(WoWSpell, WoWUnit)](SpellManagerEx/Methods/CanCast_6D0A512C1198.md) | Determines whether can cast. |
| Public method Static member | [CanCast(WoWSpell, bool)](SpellManagerEx/Methods/CanCast_38DCAD9A94CD.md) | Determines whether can cast. |
| Public method Static member | [CanCast(string, WoWUnit, bool)](SpellManagerEx/Methods/CanCast_C1033CEB8168.md) | Determines whether can cast. |
| Public method Static member | [CanCast(int, WoWUnit, bool)](SpellManagerEx/Methods/CanCast_EF71B4C09500.md) | Determines whether can cast. |
| Public method Static member | [CanCast(WoWSpell, WoWUnit, bool)](SpellManagerEx/Methods/CanCast_179D7BC68279.md) | Determines whether can cast. |
| Public method Static member | [Cast(string)](SpellManagerEx/Methods/Cast_DD209487FF02.md) | Casts the spell. |
| Public method Static member | [Cast(int)](SpellManagerEx/Methods/Cast_400143DDDA07.md) | Casts the spell. |
| Public method Static member | [Cast(WoWSpell)](SpellManagerEx/Methods/Cast_76EAA4B77B15.md) | Casts the spell. |
| Public method Static member | [Cast(string, WoWUnit)](SpellManagerEx/Methods/Cast_55B698D8B9DC.md) | Casts the spell. |
| Public method Static member | [Cast(int, WoWUnit)](SpellManagerEx/Methods/Cast_85CE90C59EB8.md) | Casts the spell. |
| Public method Static member | [Cast(WoWSpell, WoWUnit)](SpellManagerEx/Methods/Cast_28CEADF75874.md) | Casts the spell. |
| Public method Static member | [CastRandom(IEnumerable<string>, WoWUnit)](SpellManagerEx/Methods/CastRandom_C6BBD94F4723.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<string>, bool)](SpellManagerEx/Methods/CastRandom_4ACB4207CC52.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<int>, WoWUnit)](SpellManagerEx/Methods/CastRandom_78F63C40FA18.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<int>, bool)](SpellManagerEx/Methods/CastRandom_78A2CA58C0E5.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<WoWSpell>, WoWUnit)](SpellManagerEx/Methods/CastRandom_726598B42D7B.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<WoWSpell>, bool)](SpellManagerEx/Methods/CastRandom_52B13FF0E2E4.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<string>, WoWUnit, bool)](SpellManagerEx/Methods/CastRandom_E8ED38759E72.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<int>, WoWUnit, bool)](SpellManagerEx/Methods/CastRandom_205982D190DD.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<WoWSpell>, WoWUnit, bool)](SpellManagerEx/Methods/CastRandom_20A5B52C0A87.md) | Casts a random spell. |
| Public method Static member | [HasSpell(string)](SpellManagerEx/Methods/HasSpell_FD6BFCCB37DC.md) | Determines whether has spell. |
| Public method Static member | [HasSpell(int)](SpellManagerEx/Methods/HasSpell_61791E8D00D3.md) | Determines whether has spell. |
| Public method Static member | [HasSpell(WoWSpell)](SpellManagerEx/Methods/HasSpell_8D3C97BD1026.md) | Determines whether has spell. |
| Public method Static member | [StopCasting](SpellManagerEx/Methods/StopCasting_E88CE94D95CA.md) | Stops the casting. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
