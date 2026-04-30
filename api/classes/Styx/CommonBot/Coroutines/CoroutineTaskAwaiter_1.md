# CoroutineTaskAwaiter<T> Struct

Port of HB 6.2.3 Styx.CommonBot.Coroutines.CoroutineTaskAwaiter{T}. Custom awaiter that wraps a CoroutineTask's internal TaskAwaiter.

## Namespace
[Styx.CommonBot.Coroutines](../../../../namespaces/Styx/CommonBot/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed struct CoroutineTaskAwaiter<T> : INotifyCompletion
```

The CoroutineTaskAwaiter<T> type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [CoroutineTaskAwaiter](CoroutineTaskAwaiter_1/Constructors/Constructor_6D9B7EF3AE49.md) | Initializes a new instance of the CoroutineTaskAwaiter<T> struct. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [IsCompleted](CoroutineTaskAwaiter_1/Properties/IsCompleted_F8839DC6BBC1.md) | Gets a value indicating whether is completed. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [GetResult](CoroutineTaskAwaiter_1/Methods/GetResult_A2B43924EE06.md) | Gets the result. |
| Public method | [OnCompleted(Action)](CoroutineTaskAwaiter_1/Methods/OnCompleted_FE740C63F4D2.md) | Handles the on completed operation. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Overrides object.Equals().). (Inherited from ValueType.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Overrides object.GetHashCode().). (Inherited from ValueType.) |
| Public method | ToString | Returns a string that represents the current object. (Overrides object.ToString().). (Inherited from ValueType.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Styx.CommonBot.Coroutines Namespace](../../../../namespaces/Styx/CommonBot/Coroutines.md)
