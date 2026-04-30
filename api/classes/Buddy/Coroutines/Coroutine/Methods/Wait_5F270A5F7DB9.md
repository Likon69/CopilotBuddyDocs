# Coroutine.Wait Method

Waits for the condition or timeout.

## Namespace
[Buddy.Coroutines](../../../../../namespaces/Buddy/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Task<bool> Wait(TimeSpan maxWaitTimeout, Func<bool> condition)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| maxWaitTimeout | TimeSpan | The max wait timeout. |
| condition | Func<bool> | The condition. |

## Return Value

Type: Task<bool>
The result of the operation.

## See Also
[Coroutine Class](../../Coroutine.md)
[Buddy.Coroutines Namespace](../../../../../namespaces/Buddy/Coroutines.md)
