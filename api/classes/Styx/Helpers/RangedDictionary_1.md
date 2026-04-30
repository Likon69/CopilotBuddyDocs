# RangedDictionary<T> Class

Dictionary that organizes items by range.

## Inheritance Hierarchy
System.Object
  System.Collections.Generic.Dictionary<Styx.Helpers.Range, System.Collections.Generic.List<T>>
    Styx.Helpers.RangedDictionary<T>

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class RangedDictionary<T> : Dictionary<Range, List<T>>
```

The RangedDictionary<T> type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [RangedDictionary](RangedDictionary_1/Constructors/Constructor_AFA8CC90185D.md) | Initializes a new instance of the RangedDictionary<T> class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [ValueCount](RangedDictionary_1/Properties/ValueCount_37388E89D587.md) | Gets the total count of values across all ranges. |
| Public property | Capacity | Gets the capacity. (Inherited from Dictionary<Range, List<T>>.) |
| Public property | Comparer | Gets the comparer. (Inherited from Dictionary<Range, List<T>>.) |
| Public property | Count | Gets the count. (Inherited from Dictionary<Range, List<T>>.) |
| Public property | Keys | Gets the keys. (Inherited from Dictionary<Range, List<T>>.) |
| Public property | Values | Gets the values. (Inherited from Dictionary<Range, List<T>>.) |
| Public property | this[Range] | Gets or sets the this[]. (Inherited from Dictionary<Range, List<T>>.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Add(T)](RangedDictionary_1/Methods/Add_98117568A907.md) | Adds an item to the dictionary using its range. |
| Public method | [Contains(T)](RangedDictionary_1/Methods/Contains_792EB551A070.md) | Checks if the dictionary contains a specific item. |
| Public method | [GetAllValues](RangedDictionary_1/Methods/GetAllValues_7C835ABA3F09.md) | Gets all values from all ranges. |
| Public method | [GetByBigRange(Range)](RangedDictionary_1/Methods/GetByBigRange_5544500B87BA.md) | Gets all items within a larger range (spanning multiple unit ranges). |
| Public method | [Remove(T)](RangedDictionary_1/Methods/Remove_69A428EECF3C.md) | Removes a specific item from the dictionary. |
| Public method | [RemoveIndexFromRange(Range, int)](RangedDictionary_1/Methods/RemoveIndexFromRange_939CCFD8D1D9.md) | Removes an item at a specific index from a range. |
| Public method | [RemoveWhereValue(Predicate<T>)](RangedDictionary_1/Methods/RemoveWhereValue_76010DFD9262.md) | Removes all items matching the predicate. |
| Public method | Add(Range, List<T>) | Adds values. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | Clear | Clears the current contents. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | ContainsKey(Range) | Determines whether the dictionary contains the specified key. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | ContainsValue(List<T>) | Determines whether the dictionary contains the specified value. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | EnsureCapacity(int) | Ensures the collection can hold the specified number of elements. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | GetAlternateLookup | Gets the alternate lookup. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | GetEnumerator | Gets the enumerator. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | GetObjectData(SerializationInfo, StreamingContext) | Gets the object data. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | OnDeserialization(object) | Handles the on deserialization operation. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | Remove(Range) | Removes the item. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | Remove(Range, List<T>) | Removes the item. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | TrimExcess | Sets the capacity to the actual number of elements. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | TrimExcess(int) | Sets the capacity to the actual number of elements. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | TryAdd(Range, List<T>) | Attempts to add the specified key and value. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | TryGetAlternateLookup(AlternateLookup<TAlternateKey>) | Attempts to get alternate lookup. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | TryGetValue(Range, List<T>) | Attempts to get the value associated with the specified key. (Inherited from Dictionary<Range, List<T>>.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
