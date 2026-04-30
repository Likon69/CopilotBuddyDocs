# Coroutine.ExternalTask Method

Wraps an external task for coroutine execution.

## Namespace
[Buddy.Coroutines](../../../../../namespaces/Buddy/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Task<T> ExternalTask(Func<Task<T>> taskProducer)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| taskProducer | Func<Task<T>> | The task producer. |

## Return Value

Type: Task<T>
The result of the operation.

## See Also
[Coroutine Class](../../Coroutine.md)
[Buddy.Coroutines Namespace](../../../../../namespaces/Buddy/Coroutines.md)
