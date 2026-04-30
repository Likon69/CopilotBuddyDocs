# Coroutine.ExternalTask Method

Wraps an external task for coroutine execution.

## Namespace
[Buddy.Coroutines](../../../../../namespaces/Buddy/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Task<bool> ExternalTask(Task externalTask, int millisecondsTimeout)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| externalTask | Task | The external task. |
| millisecondsTimeout | int | The milliseconds timeout. |

## Return Value

Type: Task<bool>
The result of the operation.

## See Also
[Coroutine Class](../../Coroutine.md)
[Buddy.Coroutines Namespace](../../../../../namespaces/Buddy/Coroutines.md)
