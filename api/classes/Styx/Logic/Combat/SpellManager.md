# SpellManager Class

Provides spell management functionality.

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class SpellManager
```

The SpellManager type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public enumeration | [SpellManager.MouseButton](SpellManager/MouseButton.md) | Represents values for Mouse Button. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [CastBarVisible](SpellManager/Properties/CastBarVisible_7AFD567811A2.md) | Gets a value indicating whether cast bar visible. |
| Public property Static member | [GlobalCooldown](SpellManager/Properties/GlobalCooldown_396A29673019.md) | Gets a value indicating whether global cooldown. |
| Public property Static member | [GlobalCooldownLeft](SpellManager/Properties/GlobalCooldownLeft_F1040E34163F.md) | Gets the global cooldown left. |
| Public property Static member | [KnownSpells](SpellManager/Properties/KnownSpells_020E04D32812.md) | Gets the known spells. |
| Public property Static member | [NumKnownSpells](SpellManager/Properties/NumKnownSpells_B1B73BD68A82.md) | Gets the num known spells. |
| Public property Static member | [RawSpells](SpellManager/Properties/RawSpells_0136C9C6440D.md) | Gets the raw spells. |
| Public property Static member | [Spells](SpellManager/Properties/Spells_8F4358AE06C1.md) | Gets the spells. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Buff(string, WoWUnit)](SpellManager/Methods/Buff_88CB8F60D4EF.md) | Cast a buff on a target (cast only if target doesn't already have the aura). |
| Public method Static member | [Buff(int, WoWUnit)](SpellManager/Methods/Buff_61BEA039162D.md) | Cast a buff by spell ID. |
| Public method Static member | [Buff(WoWSpell, WoWUnit)](SpellManager/Methods/Buff_BCE4FB6BBC4E.md) | Cast a buff (WoWSpell overload). |
| Public method Static member | [BuffRandom(IEnumerable<string>, bool)](SpellManager/Methods/BuffRandom_3F98F657C30E.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<WoWSpell>, bool)](SpellManager/Methods/BuffRandom_972A8DAFA9A9.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<int>, WoWUnit)](SpellManager/Methods/BuffRandom_9ED15AA0BD24.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<int>, bool)](SpellManager/Methods/BuffRandom_DF3438B249CA.md) | Applies a random buff. |
| Public method Static member | [BuffRandom(IEnumerable<string>, WoWUnit, bool)](SpellManager/Methods/BuffRandom_B2D8FCF55DC3.md) | Buff a random castable spell from the list on a target (skips if aura present). |
| Public method Static member | [BuffRandom(IEnumerable<WoWSpell>, WoWUnit, bool)](SpellManager/Methods/BuffRandom_703FF49F7D41.md) | Buff a random castable spell from the list on a target (skips if aura present). |
| Public method Static member | [BuffRandom(IEnumerable<int>, WoWUnit, bool)](SpellManager/Methods/BuffRandom_C6CA87C8D40B.md) | Applies a random buff. |
| Public method Static member | [CanBuff(string, WoWUnit, bool)](SpellManager/Methods/CanBuff_DDED84D09E74.md) | Check if we can cast a buff (CanCast + target doesn't already have aura). |
| Public method Static member | [CanBuff(int, WoWUnit, bool)](SpellManager/Methods/CanBuff_F81019553D8F.md) | Check if we can cast a buff by spell ID. |
| Public method Static member | [CanBuff(WoWSpell, WoWUnit, bool)](SpellManager/Methods/CanBuff_B46D33008CD7.md) | Check if we can cast a buff (WoWSpell overload). |
| Public method Static member | [CanCast(string)](SpellManager/Methods/CanCast_392CD4FDF1FA.md) | Determines whether can cast. |
| Public method Static member | [CanCast(int)](SpellManager/Methods/CanCast_C4DACB49AE8D.md) | Determines whether can cast. |
| Public method Static member | [CanCast(WoWSpell)](SpellManager/Methods/CanCast_A5833D30BB86.md) | HB 4.3.4 overload: CanCast(WoWSpell) — no target, no range check. |
| Public method Static member | [CanCast(string, bool)](SpellManager/Methods/CanCast_65BD2E8E8A1F.md) | HB 4.3.4 overload: CanCast(string, bool checkRange) — uses current target. |
| Public method Static member | [CanCast(int, bool)](SpellManager/Methods/CanCast_B92542EAFEB0.md) | HB 4.3.4 overload: CanCast(int, bool checkRange) — uses current target. |
| Public method Static member | [CanCast(WoWSpell, bool)](SpellManager/Methods/CanCast_19986DFB8CBE.md) | HB 4.3.4 overload: CanCast(WoWSpell, bool checkRange) — uses current target. |
| Public method Static member | [CanCast(int, WoWUnit, bool, bool)](SpellManager/Methods/CanCast_AE66EC4EB0CE.md) | Determines whether can cast. |
| Public method Static member | [CanCast(string, WoWUnit, bool, bool)](SpellManager/Methods/CanCast_5D11C352A8EC.md) | HB 4.3.4 SpellManager.cs line 166: CanCast with full validation. Ported exactly from HB 4.3.4 — uses spell.CooldownTimeLeft with lag tolerance, checks IsCasting, movement, range, and power. |
| Public method Static member | [CanCast(WoWSpell, WoWUnit, bool, bool)](SpellManager/Methods/CanCast_D9163E32E204.md) | Determines whether can cast. |
| Public method Static member | [CanCast(WoWSpell, WoWUnit, bool, bool, bool)](SpellManager/Methods/CanCast_AF0D47A4AAF5.md) | HB 4.3.4 SpellManager.cs line 166-222: CanCast with accountForLagTolerance. Ported exactly from the decompiled source. |
| Public method Static member | [CanCastSpell(string)](SpellManager/Methods/CanCastSpell_27283972EA42.md) | Determines whether can cast spell. |
| Public method Static member | [Cast(string)](SpellManager/Methods/Cast_EABB71698C30.md) | Casts the spell. |
| Public method Static member | [Cast(WoWSpell)](SpellManager/Methods/Cast_05F47AB6941C.md) | Casts the spell. |
| Public method Static member | [Cast(int)](SpellManager/Methods/Cast_8604EA1B3674.md) | Cast a spell by ID on the current target. |
| Public method Static member | [Cast(string, WoWUnit)](SpellManager/Methods/Cast_0F509F284F75.md) | HB 4.3.4 line 308: Resolves spell by name, delegates to Cast(WoWSpell, WoWUnit). No CanCast guard — callers check CanCast separately before calling Cast. |
| Public method Static member | [Cast(WoWSpell, WoWUnit)](SpellManager/Methods/Cast_D6D2CD86267C.md) | HB 4.3.4 line 333: Cast spell on target via GUID-based CastSpellById. No CanCast guard — callers check CanCast separately before calling Cast. |
| Public method Static member | [Cast(int, WoWUnit)](SpellManager/Methods/Cast_8845E6107A29.md) | Cast a spell by ID on a specific target using GUID-based casting. |
| Public method Static member | [CastRandom(IEnumerable<string>, bool)](SpellManager/Methods/CastRandom_1C42F7F606C7.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<WoWSpell>, bool)](SpellManager/Methods/CastRandom_2D32E557C1DC.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<int>, WoWUnit)](SpellManager/Methods/CastRandom_D7806ACBF223.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<int>, bool)](SpellManager/Methods/CastRandom_45D5DBD6C357.md) | Casts a random spell. |
| Public method Static member | [CastRandom(IEnumerable<string>, WoWUnit, bool)](SpellManager/Methods/CastRandom_E854553BED47.md) | Cast a random castable spell from the list on a target. |
| Public method Static member | [CastRandom(IEnumerable<WoWSpell>, WoWUnit, bool)](SpellManager/Methods/CastRandom_BF7BA0838E7A.md) | Cast a random castable spell from the list on a target. |
| Public method Static member | [CastRandom(IEnumerable<int>, WoWUnit, bool)](SpellManager/Methods/CastRandom_38592C26E912.md) | Casts a random spell. |
| Public method Static member | [CastSpell(string)](SpellManager/Methods/CastSpell_1C50C583DF89.md) | Casts the spell. |
| Public method Static member | [CastSpell(string, WoWUnit)](SpellManager/Methods/CastSpell_6AD762F01999.md) | Casts the spell. |
| Public method Static member | [CastSpell(string, ulong, bool)](SpellManager/Methods/CastSpell_757AB54B7341.md) | Casts the spell. |
| Public method Static member | [CastSpellById(uint)](SpellManager/Methods/CastSpellById_37D6CC6F6BB5.md) | Casts the spell with the specified ID. |
| Public method Static member | [CastSpellById(int)](SpellManager/Methods/CastSpellById_2C4F92E591AE.md) | Casts the spell with the specified ID. |
| Public method Static member | [CastSpellById(int, ulong)](SpellManager/Methods/CastSpellById_1A0B5D69F4B0.md) | Casts a spell by ID on a specific target via native Spell_C::CastSpell. HB 4.3.4: LegacySpellManager.smethod_1(spellId, 0, targetGuid, 0) Pushes 8 args onto stack (cdecl, 0x20 cleanup). |
| Public method Static member | [CastSpellById(int, WoWUnit)](SpellManager/Methods/CastSpellById_F54BB637C2A9.md) | Casts the spell with the specified ID. |
| Public method Static member | [CastableSpell(WoWSpell)](SpellManager/Methods/CastableSpell_CF0A984EEF27.md) | Determines whether the spell can be cast. |
| Public method Static member | [ClickRemoteLocation(WoWPoint)](SpellManager/Methods/ClickRemoteLocation_D9D6E63A2CCE.md) | Clicks a remote location for spell targeting. |
| Public method Static member | [GetSpellByName(string)](SpellManager/Methods/GetSpellByName_5D1599057CAA.md) | Gets the spell by name. |
| Public method Static member | [GetSpellCooldownTimeLeft(int)](SpellManager/Methods/GetSpellCooldownTimeLeft_481D81E8727D.md) | Gets the remaining cooldown for a specific spell by walking the cooldown linked list via pure ReadProcessMemory. Zero Execute() overhead. Node layout (HB 4.3.4 Struct78): +0x04=Next, +0x08=SpellId, +0x10=StartTime, +0x14=SpellCooldown, +0x2C=GCDDuration. |
| Public method Static member | [HasSpell(string)](SpellManager/Methods/HasSpell_AD5F8670CDD3.md) | Determines whether has spell. |
| Public method Static member | [HasSpell(int)](SpellManager/Methods/HasSpell_24155E96592E.md) | Determines whether has spell. |
| Public method Static member | [HasSpell(WoWSpell)](SpellManager/Methods/HasSpell_C90C3D3A37AA.md) | Determines whether has spell. |
| Public method Static member | [Refresh](SpellManager/Methods/Refresh_35119B57EC6C.md) | Refreshes the cached data. |
| Public method Static member | [StopCasting](SpellManager/Methods/StopCasting_30565909F2FB.md) | Stops the casting. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
