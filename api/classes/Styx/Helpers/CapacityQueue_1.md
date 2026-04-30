# CapacityQueue<T> Class

A queue with a fixed capacity that automatically dequeues old items when full.

## Inheritance Hierarchy
System.Object
  System.Collections.Generic.Queue<T>
    Styx.Helpers.CapacityQueue<T>

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class CapacityQueue<T> : Queue<T>
```

The CapacityQueue<T> type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [CapacityQueue(int)](CapacityQueue_1/Constructors/Constructor_0BB461682FF5.md) | Initializes a new instance of the CapacityQueue class with the specified capacity. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Capacity](CapacityQueue_1/Properties/Capacity_3DA46001DC06.md) | Gets the maximum capacity of the queue. |
| Public property | Count | Gets the count. (Inherited from Queue<T>.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Enqueue(T)](CapacityQueue_1/Methods/Enqueue_4C8C984957F8.md) | Adds an item to the queue. If the queue is at capacity, the oldest item is removed. |
| Public method | Clear | Clears the current contents. (Inherited from Queue<T>.) |
| Public method | Contains(T) | Determines whether the collection contains the specified value. (Inherited from Queue<T>.) |
| Public method | CopyTo(T[], int) | Copies the collection to an array. (Inherited from Queue<T>.) |
| Public method | Dequeue | Removes and returns the next item from the queue. (Inherited from Queue<T>.) |
| Public method | EnsureCapacity(int) | Ensures the collection can hold the specified number of elements. (Inherited from Queue<T>.) |
| Public method | GetEnumerator | Gets the enumerator. (Inherited from Queue<T>.) |
| Public method | Peek | Returns the next item without removing it. (Inherited from Queue<T>.) |
| Public method | ToArray | Converts to array. (Inherited from Queue<T>.) |
| Public method | TrimExcess | Sets the capacity to the actual number of elements. (Inherited from Queue<T>.) |
| Public method | TrimExcess(int) | Sets the capacity to the actual number of elements. (Inherited from Queue<T>.) |
| Public method | TryDequeue(T) | Attempts to remove and return the next item. (Inherited from Queue<T>.) |
| Public method | TryPeek(T) | Attempts to return the next item without removing it. (Inherited from Queue<T>.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
