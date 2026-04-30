# OrderNodeCollection Class

Represents a collection of order node.

## Inheritance Hierarchy
System.Object
  System.Collections.Generic.List<Styx.Logic.Profiles.Quest.OrderNode>
    Styx.Logic.Profiles.Quest.OrderNodeCollection

## Namespace
[Styx.Logic.Profiles.Quest](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class OrderNodeCollection : List<OrderNode>, INodeContainer
```

The OrderNodeCollection type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [OrderNodeCollection](OrderNodeCollection/Constructors/Constructor_119CC29BD951.md) | Initializes a new instance of the OrderNodeCollection class. |
| Public constructor | [OrderNodeCollection(int)](OrderNodeCollection/Constructors/Constructor_463F75032049.md) | Initializes a new instance of the OrderNodeCollection class. |
| Public constructor | [OrderNodeCollection(IEnumerable<OrderNode>)](OrderNodeCollection/Constructors/Constructor_1EB4265A6504.md) | Initializes a new instance of the OrderNodeCollection class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IgnoreCheckpoints](OrderNodeCollection/Properties/IgnoreCheckpoints_68655DB5A0C1.md) | Gets or sets a value indicating whether ignore checkpoints. |
| Public property | Capacity | Gets or sets the capacity. (Inherited from List<OrderNode>.) |
| Public property | Count | Gets the count. (Inherited from List<OrderNode>.) |
| Public property | this[int] | Gets or sets the this[]. (Inherited from List<OrderNode>.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [FromXml(XElement)](OrderNodeCollection/Methods/FromXml_BE4F1EB90441.md) | Creates the instance from XML. |
| Public method | [GetNodes](OrderNodeCollection/Methods/GetNodes_11E6328F988A.md) | Gets the nodes. |
| Public method | Add(OrderNode) | Adds values. (Inherited from List<OrderNode>.) |
| Public method | AddRange(IEnumerable<OrderNode>) | Adds the range. (Inherited from List<OrderNode>.) |
| Public method | AsReadOnly | Returns a read-only wrapper for the collection. (Inherited from List<OrderNode>.) |
| Public method | BinarySearch(OrderNode) | Searches the sorted collection for an item. (Inherited from List<OrderNode>.) |
| Public method | BinarySearch(OrderNode, IComparer<OrderNode>) | Searches the sorted collection for an item. (Inherited from List<OrderNode>.) |
| Public method | BinarySearch(int, int, OrderNode, IComparer<OrderNode>) | Searches the sorted collection for an item. (Inherited from List<OrderNode>.) |
| Public method | Clear | Clears the current contents. (Inherited from List<OrderNode>.) |
| Public method | Contains(OrderNode) | Determines whether the collection contains the specified value. (Inherited from List<OrderNode>.) |
| Public method | ConvertAll(Converter<OrderNode, TOutput>) | Converts all items in the collection. (Inherited from List<OrderNode>.) |
| Public method | CopyTo(OrderNode[]) | Copies the collection to an array. (Inherited from List<OrderNode>.) |
| Public method | CopyTo(OrderNode[], int) | Copies the collection to an array. (Inherited from List<OrderNode>.) |
| Public method | CopyTo(int, OrderNode[], int, int) | Copies the collection to an array. (Inherited from List<OrderNode>.) |
| Public method | EnsureCapacity(int) | Ensures the collection can hold the specified number of elements. (Inherited from List<OrderNode>.) |
| Public method | Exists(Predicate<OrderNode>) | Determines whether an item matches the predicate. (Inherited from List<OrderNode>.) |
| Public method | Find(Predicate<OrderNode>) | Finds the . (Inherited from List<OrderNode>.) |
| Public method | FindAll(Predicate<OrderNode>) | Finds the all. (Inherited from List<OrderNode>.) |
| Public method | FindIndex(Predicate<OrderNode>) | Finds the index. (Inherited from List<OrderNode>.) |
| Public method | FindIndex(int, Predicate<OrderNode>) | Finds the index. (Inherited from List<OrderNode>.) |
| Public method | FindIndex(int, int, Predicate<OrderNode>) | Finds the index. (Inherited from List<OrderNode>.) |
| Public method | FindLast(Predicate<OrderNode>) | Finds the last. (Inherited from List<OrderNode>.) |
| Public method | FindLastIndex(Predicate<OrderNode>) | Finds the last index. (Inherited from List<OrderNode>.) |
| Public method | FindLastIndex(int, Predicate<OrderNode>) | Finds the last index. (Inherited from List<OrderNode>.) |
| Public method | FindLastIndex(int, int, Predicate<OrderNode>) | Finds the last index. (Inherited from List<OrderNode>.) |
| Public method | ForEach(Action<OrderNode>) | Performs the action on each item in the collection. (Inherited from List<OrderNode>.) |
| Public method | GetEnumerator | Gets the enumerator. (Inherited from List<OrderNode>.) |
| Public method | GetRange(int, int) | Gets the range. (Inherited from List<OrderNode>.) |
| Public method | IndexOf(OrderNode) | Searches for the specified item and returns its index. (Inherited from List<OrderNode>.) |
| Public method | IndexOf(OrderNode, int) | Searches for the specified item and returns its index. (Inherited from List<OrderNode>.) |
| Public method | IndexOf(OrderNode, int, int) | Searches for the specified item and returns its index. (Inherited from List<OrderNode>.) |
| Public method | Insert(int, OrderNode) | Inserts the . (Inherited from List<OrderNode>.) |
| Public method | InsertRange(int, IEnumerable<OrderNode>) | Inserts the range. (Inherited from List<OrderNode>.) |
| Public method | LastIndexOf(OrderNode) | Searches for the specified item from the end and returns its index. (Inherited from List<OrderNode>.) |
| Public method | LastIndexOf(OrderNode, int) | Searches for the specified item from the end and returns its index. (Inherited from List<OrderNode>.) |
| Public method | LastIndexOf(OrderNode, int, int) | Searches for the specified item from the end and returns its index. (Inherited from List<OrderNode>.) |
| Public method | Remove(OrderNode) | Removes the item. (Inherited from List<OrderNode>.) |
| Public method | RemoveAll(Predicate<OrderNode>) | Removes the all. (Inherited from List<OrderNode>.) |
| Public method | RemoveAt(int) | Removes the at. (Inherited from List<OrderNode>.) |
| Public method | RemoveRange(int, int) | Removes the range. (Inherited from List<OrderNode>.) |
| Public method | Reverse | Reverses the order of the items in the collection. (Inherited from List<OrderNode>.) |
| Public method | Reverse(int, int) | Reverses the order of the items in the collection. (Inherited from List<OrderNode>.) |
| Public method | Slice(int, int) | Returns a slice of the collection. (Inherited from List<OrderNode>.) |
| Public method | Sort | Sorts the items in the collection. (Inherited from List<OrderNode>.) |
| Public method | Sort(IComparer<OrderNode>) | Sorts the items in the collection. (Inherited from List<OrderNode>.) |
| Public method | Sort(Comparison<OrderNode>) | Sorts the items in the collection. (Inherited from List<OrderNode>.) |
| Public method | Sort(int, int, IComparer<OrderNode>) | Sorts the items in the collection. (Inherited from List<OrderNode>.) |
| Public method | ToArray | Converts to array. (Inherited from List<OrderNode>.) |
| Public method | TrimExcess | Sets the capacity to the actual number of elements. (Inherited from List<OrderNode>.) |
| Public method | TrueForAll(Predicate<OrderNode>) | Determines whether all items match the predicate. (Inherited from List<OrderNode>.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Logic.Profiles.Quest Namespace](../../../../../namespaces/Styx/Logic/Profiles/Quest.md)
