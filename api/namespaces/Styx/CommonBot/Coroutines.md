# Styx.CommonBot.Coroutines Namespace

Contains coroutine helpers used by common bot systems.

## Classes

| | Name | Description |
| --- | --- | --- |
| Public class | [CommonCoroutines](../../../classes/Styx/CommonBot/Coroutines/CommonCoroutines.md) | Port of HB 6.2.3 Styx.CommonBot.Coroutines.CommonCoroutines. Provides async helper methods for lag-aware sleeps, Lua event waits, movement stops, and dismounting. |
| Public class | [CoroutineCompositeExtensions](../../../classes/Styx/CommonBot/Coroutines/CoroutineCompositeExtensions.md) | Port of HB 6.2.3 Styx.CommonBot.Coroutines.CoroutineCompositeExtensions. Allows running a TreeSharp Composite as an async coroutine. |
| Public class | [CoroutineTask](../../../classes/Styx/CommonBot/Coroutines/CoroutineTask.md) | Port of HB 6.2.3 Styx.CommonBot.Coroutines.CoroutineTask (non-generic). |
| Public class | [CoroutineTask<T>](../../../classes/Styx/CommonBot/Coroutines/CoroutineTask_1.md) | Port of HB 6.2.3 Styx.CommonBot.Coroutines.CoroutineTask{T}. Abstract base for hookable coroutine tasks. The GetAwaiter() method returns a custom awaiter that wraps the Run() task, allowing these to be used with await from within ActionRunCoroutine. |

## Structures

| | Name | Description |
| --- | --- | --- |
| Public struct | [CoroutineTaskAwaiter](../../../classes/Styx/CommonBot/Coroutines/CoroutineTaskAwaiter.md) | Port of HB 6.2.3 Styx.CommonBot.Coroutines.CoroutineTaskAwaiter (non-generic). |
| Public struct | [CoroutineTaskAwaiter<T>](../../../classes/Styx/CommonBot/Coroutines/CoroutineTaskAwaiter_1.md) | Port of HB 6.2.3 Styx.CommonBot.Coroutines.CoroutineTaskAwaiter{T}. Custom awaiter that wraps a CoroutineTask's internal TaskAwaiter. |

## See Also
[Namespace Index](../../../index.md)
