# CircularQueue<T> Class

Represents a circular queue.

## Inheritance Hierarchy
System.Object
  System.Collections.Generic.Queue<T>
    Styx.Helpers.CircularQueue<T>

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class CircularQueue<T> : Queue<T>
```

The CircularQueue<T> type exposes the following members.

## Nested Types

| | Name | Description |
| --- | --- | --- |
| Public delegate | [CircularQueue.EndOfQueue](CircularQueue_1/EndOfQueue.md) | Represents a delegate for End Of Queue. |
| Public delegate | [CircularQueue.StartOfQueue](CircularQueue_1/StartOfQueue.md) | Represents a delegate for Start Of Queue. |

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [CircularQueue](CircularQueue_1/Constructors/Constructor_F50CC16FCD77.md) | Initializes a new instance of the CircularQueue<T> class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Count](CircularQueue_1/Properties/Count_FEF78D555CFA.md) | Total item count. In bounce mode driven by the snapshot list. |
| Public property | [First](CircularQueue_1/Properties/First_1D13CA7FEA15.md) | Gets the first. |
| Public property | [Mode](CircularQueue_1/Properties/Mode_5E1A6510A1FB.md) | Controls whether the queue circles or bounces. Set before first Dequeue. |
| Public property | Capacity | Gets the capacity. (Inherited from Queue<T>.) |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [OnEndOfQueue](CircularQueue_1/Events/OnEndOfQueue_1BE990AA3F68.md) | Occurs when end of queue. |
| Public event | [OnStartOfQueue](CircularQueue_1/Events/OnStartOfQueue_EA5A321988FA.md) | Occurs when start of queue. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Add(T)](CircularQueue_1/Methods/Add_E4B987C8E6B4.md) | Adds values. |
| Public method | [CycleTo(T)](CircularQueue_1/Methods/CycleTo_BB5EB8882D18.md) | Cycles to the specified item. |
| Public method | [Dequeue](CircularQueue_1/Methods/Dequeue_F13B66BB3E95.md) | Removes and returns the next item from the queue. |
| Public method | [Enqueue(T)](CircularQueue_1/Methods/Enqueue_2CE994F197C9.md) | Adds an item to the queue. |
| Public method | [Peek](CircularQueue_1/Methods/Peek_307642D1936B.md) | Returns the next item without advancing. Bounce-aware. |
| Public method | [ResetBounce](CircularQueue_1/Methods/ResetBounce_16B4A1A2A591.md) | Resets the bounce traversal to the beginning of the list. |
| Public method | Clear | Clears the current contents. (Inherited from Queue<T>.) |
| Public method | Contains(T) | Determines whether the collection contains the specified value. (Inherited from Queue<T>.) |
| Public method | CopyTo(T[], int) | Copies the collection to an array. (Inherited from Queue<T>.) |
| Public method | EnsureCapacity(int) | Ensures the collection can hold the specified number of elements. (Inherited from Queue<T>.) |
| Public method | GetEnumerator | Gets the enumerator. (Inherited from Queue<T>.) |
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
