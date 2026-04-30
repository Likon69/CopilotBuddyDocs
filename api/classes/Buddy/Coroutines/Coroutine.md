# Coroutine Class

Provides coroutine execution that bridges asynchronous tasks with the behavior tree tick loop.

## Inheritance Hierarchy
System.Object
  Buddy.Coroutines.Coroutine

## Namespace
[Buddy.Coroutines](../../../namespaces/Buddy/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed class Coroutine : IDisposable
```

The Coroutine type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [Coroutine(Func<Task>)](Coroutine/Constructors/Constructor_A9F75981A348.md) | Initializes a new instance of the Coroutine class. |
| Public constructor | [Coroutine(Func<Task<object>>)](Coroutine/Constructors/Constructor_D5B60862F279.md) | Initializes a new instance of the Coroutine class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [Current](Coroutine/Properties/Current_201BB881C8C8.md) | Gets the current. |
| Public property | [FaultingException](Coroutine/Properties/FaultingException_C3196A1FC0F5.md) | Gets the faulting exception. |
| Public property | [IsDisposed](Coroutine/Properties/IsDisposed_4C402206E022.md) | Gets a value indicating whether is disposed. |
| Public property | [IsFinished](Coroutine/Properties/IsFinished_D7640C2CC533.md) | Gets a value indicating whether is finished. |
| Public property | [Result](Coroutine/Properties/Result_9429BEF77210.md) | Gets the result. |
| Public property | [Status](Coroutine/Properties/Status_4EC3DFAD4B24.md) | Gets the status. |
| Public property | [Ticks](Coroutine/Properties/Ticks_31B9CFE22846.md) | Gets the ticks. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Dispose](Coroutine/Methods/Dispose_08C155E8C746.md) | Releases the resources used by the instance. |
| Public method Static member | [ExternalTask(Func<Task>)](Coroutine/Methods/ExternalTask_4F27C468B0EB.md) | Wraps an external task for coroutine execution. |
| Public method Static member | [ExternalTask(Task)](Coroutine/Methods/ExternalTask_68EF2D88C89B.md) | Wraps an external task for coroutine execution. |
| Public method Static member | [ExternalTask(Func<Task<T>>)](Coroutine/Methods/ExternalTask_5B26AF9B884E.md) | Wraps an external task for coroutine execution. |
| Public method Static member | [ExternalTask(Task<T>)](Coroutine/Methods/ExternalTask_BF90106E0DD9.md) | Wraps an external task for coroutine execution. |
| Public method Static member | [ExternalTask(Task, TimeSpan)](Coroutine/Methods/ExternalTask_7EEA71BD82B0.md) | Wraps an external task for coroutine execution. |
| Public method Static member | [ExternalTask(Task, int)](Coroutine/Methods/ExternalTask_10AE8DA7C94B.md) | Wraps an external task for coroutine execution. |
| Public method Static member | [ExternalTask(Task<T>, int)](Coroutine/Methods/ExternalTask_9AFD106CC357.md) | Wraps an external task for coroutine execution. |
| Public method Static member | [ExternalTask(Task<T>, TimeSpan)](Coroutine/Methods/ExternalTask_97CFC092E9D8.md) | Wraps an external task for coroutine execution. |
| Public method | [Resume](Coroutine/Methods/Resume_2DE58286B0F9.md) | Advance the coroutine by one tick. The coroutine runs until it awaits a yield point, then returns control to the caller. |
| Public method Static member | [Sleep(TimeSpan)](Coroutine/Methods/Sleep_73B2D2B15811.md) | Suspends execution for the specified duration. |
| Public method Static member | [Sleep(int)](Coroutine/Methods/Sleep_20F104709E53.md) | Suspends execution for the specified duration. |
| Public method | [ToString](Coroutine/Methods/ToString_F781EE8A693E.md) | Returns a string that represents the current object. (Overrides object.ToString().) |
| Public method Static member | [Wait(TimeSpan, Func<bool>)](Coroutine/Methods/Wait_5F270A5F7DB9.md) | Waits for the condition or timeout. |
| Public method Static member | [Wait(int, Func<bool>)](Coroutine/Methods/Wait_A92E7293D7E9.md) | Waits for the condition or timeout. |
| Public method Static member | [Yield](Coroutine/Methods/Yield_A9F58AABBBE9.md) | Yields execution. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |

## See Also
[Buddy.Coroutines Namespace](../../../namespaces/Buddy/Coroutines.md)
