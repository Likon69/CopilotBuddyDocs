# CoroutineTask<T> Class

Port of HB 6.2.3 Styx.CommonBot.Coroutines.CoroutineTask{T}. Abstract base for hookable coroutine tasks. The GetAwaiter() method returns a custom awaiter that wraps the Run() task, allowing these to be used with await from within ActionRunCoroutine.

## Inheritance Hierarchy
System.Object
  Styx.CommonBot.Coroutines.CoroutineTask<T>

## Namespace
[Styx.CommonBot.Coroutines](../../../../namespaces/Styx/CommonBot/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public abstract class CoroutineTask<T>
```

The CoroutineTask<T> type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Protected constructor | [CoroutineTask](CoroutineTask_1/Constructors/Constructor_FDEA7F269DF8.md) | Initializes a new instance of the CoroutineTask<T> class. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetAwaiter](CoroutineTask_1/Methods/GetAwaiter_86D9225E4024.md) | Gets the awaiter. |
| Public method | [Run](CoroutineTask_1/Methods/Run_34DD234DE95B.md) | Runs the operation. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.CommonBot.Coroutines Namespace](../../../../namespaces/Styx/CommonBot/Coroutines.md)
