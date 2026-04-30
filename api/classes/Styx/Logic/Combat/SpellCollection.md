# SpellCollection Class

FEAT-17: Typed wrapper for a player's known spells. Extends Dictionary for name-based lookup, matching HB 4.3.4 API.

## Inheritance Hierarchy
System.Object
  System.Collections.Generic.Dictionary<System.String, Styx.Logic.Combat.WoWSpell>
    Styx.Logic.Combat.SpellCollection

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class SpellCollection : Dictionary<string, WoWSpell>
```

The SpellCollection type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [SpellCollection](SpellCollection/Constructors/Constructor_5F458C05C8B3.md) | Initializes a new instance of the SpellCollection class. |
| Public constructor | [SpellCollection(int)](SpellCollection/Constructors/Constructor_CEF39CE51933.md) | Initializes a new instance of the SpellCollection class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [this[string]](SpellCollection/Properties/Item_EC3EE00B42B0.md) | Gets a spell by name. Throws KeyNotFoundException if not known. |
| Public property | Capacity | Gets the capacity. (Inherited from Dictionary<string, WoWSpell>.) |
| Public property | Comparer | Gets the comparer. (Inherited from Dictionary<string, WoWSpell>.) |
| Public property | Count | Gets the count. (Inherited from Dictionary<string, WoWSpell>.) |
| Public property | Keys | Gets the keys. (Inherited from Dictionary<string, WoWSpell>.) |
| Public property | Values | Gets the values. (Inherited from Dictionary<string, WoWSpell>.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetById(int)](SpellCollection/Methods/GetById_BD5A894328C8.md) | Gets a spell by ID, or null if not known. |
| Public method | [HasSpell(string)](SpellCollection/Methods/HasSpell_F167CED7897B.md) | Whether the player knows a spell with this name. |
| Public method | [HasSpell(int)](SpellCollection/Methods/HasSpell_C0316E02CE2E.md) | Whether the player knows a spell with this ID. |
| Public method | Add(string, WoWSpell) | Adds values. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | Clear | Clears the current contents. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | ContainsKey(string) | Determines whether the dictionary contains the specified key. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | ContainsValue(WoWSpell) | Determines whether the dictionary contains the specified value. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | EnsureCapacity(int) | Ensures the collection can hold the specified number of elements. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | GetAlternateLookup | Gets the alternate lookup. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | GetEnumerator | Gets the enumerator. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | GetObjectData(SerializationInfo, StreamingContext) | Gets the object data. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | OnDeserialization(object) | Handles the on deserialization operation. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | Remove(string) | Removes the item. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | Remove(string, WoWSpell) | Removes the item. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | TrimExcess | Sets the capacity to the actual number of elements. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | TrimExcess(int) | Sets the capacity to the actual number of elements. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | TryAdd(string, WoWSpell) | Attempts to add the specified key and value. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | TryGetAlternateLookup(AlternateLookup<TAlternateKey>) | Attempts to get alternate lookup. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | TryGetValue(string, WoWSpell) | Attempts to get the value associated with the specified key. (Inherited from Dictionary<string, WoWSpell>.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
