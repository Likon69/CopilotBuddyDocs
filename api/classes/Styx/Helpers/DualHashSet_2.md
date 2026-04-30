# DualHashSet<T1, T2> Class

A collection that contains two HashSets of different types. Allows checking membership against either type.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.DualHashSet<T1, T2>

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class DualHashSet<T1, T2> : IEnumerable<object>
```

The DualHashSet<T1, T2> type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [DualHashSet](DualHashSet_2/Constructors/Constructor_7B2FEA4AAABF.md) | Creates a new DualHashSet. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Count](DualHashSet_2/Properties/Count_E5EA8D9BC86F.md) | Gets the total count of items in both sets. |
| Public property | [HashSet1](DualHashSet_2/Properties/HashSet1_771BF2CC8AD7.md) | Gets the first HashSet. |
| Public property | [HashSet2](DualHashSet_2/Properties/HashSet2_927B05000220.md) | Gets the second HashSet. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Add(T1)](DualHashSet_2/Methods/Add_7639928489E3.md) | Adds an item of type T1. |
| Public method | [Add(T2)](DualHashSet_2/Methods/Add_9D7E4E06A22E.md) | Adds an item of type T2. |
| Public method | [Add(ValuePair<T1, T2>)](DualHashSet_2/Methods/Add_47CF2A433A56.md) | Adds a pair of items. |
| Public method | [Clear](DualHashSet_2/Methods/Clear_6ABF86ACDDBC.md) | Clears both hash sets. |
| Public method | [Contains(T1)](DualHashSet_2/Methods/Contains_4ED16CBA9B28.md) | Checks if an item of type T1 exists. |
| Public method | [Contains(T2)](DualHashSet_2/Methods/Contains_E252D505B139.md) | Checks if an item of type T2 exists. |
| Public method | [Contains(ValuePair<T1, T2>)](DualHashSet_2/Methods/Contains_586FF6017AF2.md) | Checks if either value in the pair exists. |
| Public method | [GetEnumerator](DualHashSet_2/Methods/GetEnumerator_278DAE131442.md) | Gets the enumerator. |
| Public method | [Remove(T1)](DualHashSet_2/Methods/Remove_40353A645118.md) | Removes an item of type T1. |
| Public method | [Remove(T2)](DualHashSet_2/Methods/Remove_9E0257F9F226.md) | Removes an item of type T2. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
