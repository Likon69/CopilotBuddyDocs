# ClassCollection<T> Class

A collection of dynamically loaded classes that compiles and instantiates types inheriting from T. Ported exactly from HB 3.3.5a.

## Inheritance Hierarchy
System.Object
  System.Collections.Generic.List<T>
    Styx.Helpers.ClassCollection<T>

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class ClassCollection<T> : List<T>, IDisposable
```

The ClassCollection<T> type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [ClassCollection](ClassCollection_1/Constructors/Constructor_F6BFCA84437B.md) | Initializes a new instance of the ClassCollection<T> class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | Capacity | Gets or sets the capacity. (Inherited from List<T>.) |
| Public property | Count | Gets the count. (Inherited from List<T>.) |
| Public property | this[int] | Gets or sets the this[]. (Inherited from List<T>.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CompileAndLoadFrom(string, CompilerResults)](ClassCollection_1/Methods/CompileAndLoadFrom_9B5D9A02A798.md) | Compiles and loads classes from a path (file or directory). |
| Public method | [Dispose](ClassCollection_1/Methods/Dispose_CDA99970FFC1.md) | Releases the resources used by the instance. |
| Protected method | [Finalize](ClassCollection_1/Methods/Finalize_DDEDE1542435.md) | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. |
| Public method | Add(T) | Adds values. (Inherited from List<T>.) |
| Public method | AddRange(IEnumerable<T>) | Adds the range. (Inherited from List<T>.) |
| Public method | AsReadOnly | Returns a read-only wrapper for the collection. (Inherited from List<T>.) |
| Public method | BinarySearch(T) | Searches the sorted collection for an item. (Inherited from List<T>.) |
| Public method | BinarySearch(T, IComparer<T>) | Searches the sorted collection for an item. (Inherited from List<T>.) |
| Public method | BinarySearch(int, int, T, IComparer<T>) | Searches the sorted collection for an item. (Inherited from List<T>.) |
| Public method | Clear | Clears the current contents. (Inherited from List<T>.) |
| Public method | Contains(T) | Determines whether the collection contains the specified value. (Inherited from List<T>.) |
| Public method | ConvertAll(Converter<T, TOutput>) | Converts all items in the collection. (Inherited from List<T>.) |
| Public method | CopyTo(T[]) | Copies the collection to an array. (Inherited from List<T>.) |
| Public method | CopyTo(T[], int) | Copies the collection to an array. (Inherited from List<T>.) |
| Public method | CopyTo(int, T[], int, int) | Copies the collection to an array. (Inherited from List<T>.) |
| Public method | EnsureCapacity(int) | Ensures the collection can hold the specified number of elements. (Inherited from List<T>.) |
| Public method | Exists(Predicate<T>) | Determines whether an item matches the predicate. (Inherited from List<T>.) |
| Public method | Find(Predicate<T>) | Finds the . (Inherited from List<T>.) |
| Public method | FindAll(Predicate<T>) | Finds the all. (Inherited from List<T>.) |
| Public method | FindIndex(Predicate<T>) | Finds the index. (Inherited from List<T>.) |
| Public method | FindIndex(int, Predicate<T>) | Finds the index. (Inherited from List<T>.) |
| Public method | FindIndex(int, int, Predicate<T>) | Finds the index. (Inherited from List<T>.) |
| Public method | FindLast(Predicate<T>) | Finds the last. (Inherited from List<T>.) |
| Public method | FindLastIndex(Predicate<T>) | Finds the last index. (Inherited from List<T>.) |
| Public method | FindLastIndex(int, Predicate<T>) | Finds the last index. (Inherited from List<T>.) |
| Public method | FindLastIndex(int, int, Predicate<T>) | Finds the last index. (Inherited from List<T>.) |
| Public method | ForEach(Action<T>) | Performs the action on each item in the collection. (Inherited from List<T>.) |
| Public method | GetEnumerator | Gets the enumerator. (Inherited from List<T>.) |
| Public method | GetRange(int, int) | Gets the range. (Inherited from List<T>.) |
| Public method | IndexOf(T) | Searches for the specified item and returns its index. (Inherited from List<T>.) |
| Public method | IndexOf(T, int) | Searches for the specified item and returns its index. (Inherited from List<T>.) |
| Public method | IndexOf(T, int, int) | Searches for the specified item and returns its index. (Inherited from List<T>.) |
| Public method | Insert(int, T) | Inserts the . (Inherited from List<T>.) |
| Public method | InsertRange(int, IEnumerable<T>) | Inserts the range. (Inherited from List<T>.) |
| Public method | LastIndexOf(T) | Searches for the specified item from the end and returns its index. (Inherited from List<T>.) |
| Public method | LastIndexOf(T, int) | Searches for the specified item from the end and returns its index. (Inherited from List<T>.) |
| Public method | LastIndexOf(T, int, int) | Searches for the specified item from the end and returns its index. (Inherited from List<T>.) |
| Public method | Remove(T) | Removes the item. (Inherited from List<T>.) |
| Public method | RemoveAll(Predicate<T>) | Removes the all. (Inherited from List<T>.) |
| Public method | RemoveAt(int) | Removes the at. (Inherited from List<T>.) |
| Public method | RemoveRange(int, int) | Removes the range. (Inherited from List<T>.) |
| Public method | Reverse | Reverses the order of the items in the collection. (Inherited from List<T>.) |
| Public method | Reverse(int, int) | Reverses the order of the items in the collection. (Inherited from List<T>.) |
| Public method | Slice(int, int) | Returns a slice of the collection. (Inherited from List<T>.) |
| Public method | Sort | Sorts the items in the collection. (Inherited from List<T>.) |
| Public method | Sort(IComparer<T>) | Sorts the items in the collection. (Inherited from List<T>.) |
| Public method | Sort(Comparison<T>) | Sorts the items in the collection. (Inherited from List<T>.) |
| Public method | Sort(int, int, IComparer<T>) | Sorts the items in the collection. (Inherited from List<T>.) |
| Public method | ToArray | Converts to array. (Inherited from List<T>.) |
| Public method | TrimExcess | Sets the capacity to the actual number of elements. (Inherited from List<T>.) |
| Public method | TrueForAll(Predicate<T>) | Determines whether all items match the predicate. (Inherited from List<T>.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
