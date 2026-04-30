# LegacySpellManager Class

Legacy spell manager wrapper for older Singular code compatibility. Wraps SpellManager methods for HB 3.3.5a/4.3.4 compatibility.

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class LegacySpellManager
```

The LegacySpellManager type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [KnownSpells](LegacySpellManager/Properties/KnownSpells_F38D6F9F5D59.md) | Known spells dictionary keyed by name (populated via Refresh). |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Cast(string)](LegacySpellManager/Methods/Cast_1A442A250E49.md) | Casts a spell by name on the current target. |
| Public method Static member | [Cast(int)](LegacySpellManager/Methods/Cast_DD72284D58F1.md) | Casts a spell by ID on the current target. |
| Public method Static member | [Cast(string, WoWUnit)](LegacySpellManager/Methods/Cast_B6BC8B689C4C.md) | Casts a spell by name on a specific target. |
| Public method Static member | [Cast(int, WoWUnit)](LegacySpellManager/Methods/Cast_4808C12F6D83.md) | Casts a spell by ID on a specific target. |
| Public method Static member | [CastPetAction(string)](LegacySpellManager/Methods/CastPetAction_9372A2D12103.md) | Casts a pet spell by name. |
| Public method Static member | [CastSpellById(int)](LegacySpellManager/Methods/CastSpellById_A92C4C38E785.md) | Casts a spell by ID on the current target. Used by Singular for trap launcher and similar mechanics. |
| Public method Static member | [CastSpellById(int, WoWUnit)](LegacySpellManager/Methods/CastSpellById_A9619CC2D49A.md) | Casts a spell by ID on a specific target. |
| Public method Static member | [ClickRemoteLocation(WoWPoint)](LegacySpellManager/Methods/ClickRemoteLocation_BECED8C1BC09.md) | Clicks a remote location for ground-targeted spells (trap placement, etc). |
| Public method Static member | [GetSpell(string)](LegacySpellManager/Methods/GetSpell_EA5167EDB3C8.md) | Gets spell by name. |
| Public method Static member | [GetSpellCooldown(string)](LegacySpellManager/Methods/GetSpellCooldown_88438AD0FBA1.md) | Gets spell cooldown remaining in milliseconds. |
| Public method Static member | [HasSpell(string)](LegacySpellManager/Methods/HasSpell_A6A08B4D0374.md) | Checks if player has a spell. |
| Public method Static member | [HasSpell(int)](LegacySpellManager/Methods/HasSpell_3E41937F10B5.md) | Checks if player has a spell by ID. |
| Public method Static member | [Refresh](LegacySpellManager/Methods/Refresh_1D468967F632.md) | Rebuilds the KnownSpells dictionary from the player's spell book. Called when a combat routine is loaded or changed (HB 4.3.4 pattern). |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
