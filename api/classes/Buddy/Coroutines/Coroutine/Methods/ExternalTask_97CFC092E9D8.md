# Coroutine.ExternalTask Method

Wraps an external task for coroutine execution.

## Namespace
[Buddy.Coroutines](../../../../../namespaces/Buddy/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Task<ExternalTaskWaitResult<T>> ExternalTask(Task<T> externalTask, TimeSpan timeout)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| externalTask | Task<T> | The external task. |
| timeout | TimeSpan | The timeout. |

## Return Value

Type: Task<ExternalTaskWaitResult<T>>
The result of the operation.

## See Also
[Coroutine Class](../../Coroutine.md)
[Buddy.Coroutines Namespace](../../../../../namespaces/Buddy/Coroutines.md)
