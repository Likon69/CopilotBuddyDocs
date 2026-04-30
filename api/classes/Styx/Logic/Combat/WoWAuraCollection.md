# WoWAuraCollection Class

Collection class for WoWAura objects. Extends List<WoWAura> with helper methods for aura management.

## Inheritance Hierarchy
System.Object
  System.Collections.Generic.List<Styx.Logic.Combat.WoWAura>
    Styx.Logic.Combat.WoWAuraCollection

## Namespace
[Styx.Logic.Combat](../../../../namespaces/Styx/Logic/Combat.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class WoWAuraCollection : List<WoWAura>
```

The WoWAuraCollection type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [WoWAuraCollection](WoWAuraCollection/Constructors/Constructor_A26CBA2779A6.md) | Creates an empty aura collection. |
| Public constructor | [WoWAuraCollection(int)](WoWAuraCollection/Constructors/Constructor_ACF366AED465.md) | Creates an aura collection with the specified initial capacity. |
| Public constructor | [WoWAuraCollection(IEnumerable<WoWAura>)](WoWAuraCollection/Constructors/Constructor_CB96C3A152A5.md) | Creates an aura collection from an existing collection of auras. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ActiveAuras](WoWAuraCollection/Properties/ActiveAuras_15BF6E3B0441.md) | Gets all active (non-passive) auras in the collection. |
| Public property | [Buffs](WoWAuraCollection/Properties/Buffs_C811BEA176E3.md) | Gets all buffs (non-harmful auras) in the collection. |
| Public property | [Debuffs](WoWAuraCollection/Properties/Debuffs_AE0FF663A7DE.md) | Gets all debuffs (harmful auras) in the collection. |
| Public property | [PassiveAuras](WoWAuraCollection/Properties/PassiveAuras_8D7EDBF1DDD6.md) | Gets all passive auras in the collection. |
| Public property | Capacity | Gets or sets the capacity. (Inherited from List<WoWAura>.) |
| Public property | Count | Gets the count. (Inherited from List<WoWAura>.) |
| Public property | this[int] | Gets or sets the this[]. (Inherited from List<WoWAura>.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Contains(int)](WoWAuraCollection/Methods/Contains_CBE479F862DB.md) | Checks if an aura with the specified spell ID exists in the collection. |
| Public method | [ContainsByName(string)](WoWAuraCollection/Methods/ContainsByName_6BD15F5BC36D.md) | Checks if an aura with the specified name exists in the collection. |
| Public method | [GetByAuraType(WoWApplyAuraType)](WoWAuraCollection/Methods/GetByAuraType_B8F5183609DA.md) | Gets all auras of a specific apply aura type. |
| Public method | [GetByCreator(ulong)](WoWAuraCollection/Methods/GetByCreator_844489C0104E.md) | Gets all auras cast by the specified unit. |
| Public method | [GetById(int)](WoWAuraCollection/Methods/GetById_AC0461FAE0AF.md) | Gets an aura by spell ID. |
| Public method | [GetByName(string)](WoWAuraCollection/Methods/GetByName_EB4312B17D18.md) | Gets an aura by name. |
| Public method | [GetMaxStackCount(int)](WoWAuraCollection/Methods/GetMaxStackCount_C021DB880A9F.md) | Gets the maximum stack count among all auras with the specified spell ID. |
| Public method | [GetMinTimeLeft(int)](WoWAuraCollection/Methods/GetMinTimeLeft_C6BDCF8CBC85.md) | Gets the minimum time remaining among all auras with the specified spell ID. |
| Public method | [GetTotalAuraModifier(WoWApplyAuraType)](WoWAuraCollection/Methods/GetTotalAuraModifier_30744352D4D5.md) | Calculates the total modifier from all auras of a specific type. This is useful for calculating stat bonuses from buffs. |
| Public method | [ToDictionaryByName](WoWAuraCollection/Methods/ToDictionaryByName_A23833F88680.md) | Converts the collection to a dictionary keyed by name. |
| Public method | [ToDictionaryBySpellId](WoWAuraCollection/Methods/ToDictionaryBySpellId_AFD7F3A91655.md) | Converts the collection to a dictionary keyed by spell ID. |
| Public method | Add(WoWAura) | Adds values. (Inherited from List<WoWAura>.) |
| Public method | AddRange(IEnumerable<WoWAura>) | Adds the range. (Inherited from List<WoWAura>.) |
| Public method | AsReadOnly | Returns a read-only wrapper for the collection. (Inherited from List<WoWAura>.) |
| Public method | BinarySearch(WoWAura) | Searches the sorted collection for an item. (Inherited from List<WoWAura>.) |
| Public method | BinarySearch(WoWAura, IComparer<WoWAura>) | Searches the sorted collection for an item. (Inherited from List<WoWAura>.) |
| Public method | BinarySearch(int, int, WoWAura, IComparer<WoWAura>) | Searches the sorted collection for an item. (Inherited from List<WoWAura>.) |
| Public method | Clear | Clears the current contents. (Inherited from List<WoWAura>.) |
| Public method | Contains(WoWAura) | Determines whether the collection contains the specified value. (Inherited from List<WoWAura>.) |
| Public method | ConvertAll(Converter<WoWAura, TOutput>) | Converts all items in the collection. (Inherited from List<WoWAura>.) |
| Public method | CopyTo(WoWAura[]) | Copies the collection to an array. (Inherited from List<WoWAura>.) |
| Public method | CopyTo(WoWAura[], int) | Copies the collection to an array. (Inherited from List<WoWAura>.) |
| Public method | CopyTo(int, WoWAura[], int, int) | Copies the collection to an array. (Inherited from List<WoWAura>.) |
| Public method | EnsureCapacity(int) | Ensures the collection can hold the specified number of elements. (Inherited from List<WoWAura>.) |
| Public method | Exists(Predicate<WoWAura>) | Determines whether an item matches the predicate. (Inherited from List<WoWAura>.) |
| Public method | Find(Predicate<WoWAura>) | Finds the . (Inherited from List<WoWAura>.) |
| Public method | FindAll(Predicate<WoWAura>) | Finds the all. (Inherited from List<WoWAura>.) |
| Public method | FindIndex(Predicate<WoWAura>) | Finds the index. (Inherited from List<WoWAura>.) |
| Public method | FindIndex(int, Predicate<WoWAura>) | Finds the index. (Inherited from List<WoWAura>.) |
| Public method | FindIndex(int, int, Predicate<WoWAura>) | Finds the index. (Inherited from List<WoWAura>.) |
| Public method | FindLast(Predicate<WoWAura>) | Finds the last. (Inherited from List<WoWAura>.) |
| Public method | FindLastIndex(Predicate<WoWAura>) | Finds the last index. (Inherited from List<WoWAura>.) |
| Public method | FindLastIndex(int, Predicate<WoWAura>) | Finds the last index. (Inherited from List<WoWAura>.) |
| Public method | FindLastIndex(int, int, Predicate<WoWAura>) | Finds the last index. (Inherited from List<WoWAura>.) |
| Public method | ForEach(Action<WoWAura>) | Performs the action on each item in the collection. (Inherited from List<WoWAura>.) |
| Public method | GetEnumerator | Gets the enumerator. (Inherited from List<WoWAura>.) |
| Public method | GetRange(int, int) | Gets the range. (Inherited from List<WoWAura>.) |
| Public method | IndexOf(WoWAura) | Searches for the specified item and returns its index. (Inherited from List<WoWAura>.) |
| Public method | IndexOf(WoWAura, int) | Searches for the specified item and returns its index. (Inherited from List<WoWAura>.) |
| Public method | IndexOf(WoWAura, int, int) | Searches for the specified item and returns its index. (Inherited from List<WoWAura>.) |
| Public method | Insert(int, WoWAura) | Inserts the . (Inherited from List<WoWAura>.) |
| Public method | InsertRange(int, IEnumerable<WoWAura>) | Inserts the range. (Inherited from List<WoWAura>.) |
| Public method | LastIndexOf(WoWAura) | Searches for the specified item from the end and returns its index. (Inherited from List<WoWAura>.) |
| Public method | LastIndexOf(WoWAura, int) | Searches for the specified item from the end and returns its index. (Inherited from List<WoWAura>.) |
| Public method | LastIndexOf(WoWAura, int, int) | Searches for the specified item from the end and returns its index. (Inherited from List<WoWAura>.) |
| Public method | Remove(WoWAura) | Removes the item. (Inherited from List<WoWAura>.) |
| Public method | RemoveAll(Predicate<WoWAura>) | Removes the all. (Inherited from List<WoWAura>.) |
| Public method | RemoveAt(int) | Removes the at. (Inherited from List<WoWAura>.) |
| Public method | RemoveRange(int, int) | Removes the range. (Inherited from List<WoWAura>.) |
| Public method | Reverse | Reverses the order of the items in the collection. (Inherited from List<WoWAura>.) |
| Public method | Reverse(int, int) | Reverses the order of the items in the collection. (Inherited from List<WoWAura>.) |
| Public method | Slice(int, int) | Returns a slice of the collection. (Inherited from List<WoWAura>.) |
| Public method | Sort | Sorts the items in the collection. (Inherited from List<WoWAura>.) |
| Public method | Sort(IComparer<WoWAura>) | Sorts the items in the collection. (Inherited from List<WoWAura>.) |
| Public method | Sort(Comparison<WoWAura>) | Sorts the items in the collection. (Inherited from List<WoWAura>.) |
| Public method | Sort(int, int, IComparer<WoWAura>) | Sorts the items in the collection. (Inherited from List<WoWAura>.) |
| Public method | ToArray | Converts to array. (Inherited from List<WoWAura>.) |
| Public method | TrimExcess | Sets the capacity to the actual number of elements. (Inherited from List<WoWAura>.) |
| Public method | TrueForAll(Predicate<WoWAura>) | Determines whether all items match the predicate. (Inherited from List<WoWAura>.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Combat Namespace](../../../../namespaces/Styx/Logic/Combat.md)
