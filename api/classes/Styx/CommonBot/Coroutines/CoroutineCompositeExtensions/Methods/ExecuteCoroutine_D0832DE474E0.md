# CoroutineCompositeExtensions.ExecuteCoroutine Method

HB 6.2.3: Extension method to execute any Composite as a coroutine. If the composite is an ActionRunCoroutine with a task producer, invokes the producer directly (avoids extra wrapping).

## Namespace
[Styx.CommonBot.Coroutines](../../../../../../namespaces/Styx/CommonBot/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Task<bool> ExecuteCoroutine(Composite composite, object context)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| composite | [Composite](../../../../../TreeSharp/Composite.md) | The composite. |
| context | object | The context. |

## Return Value

Type: Task<bool>
The result of the operation.

## See Also
[CoroutineCompositeExtensions Class](../../CoroutineCompositeExtensions.md)
[Styx.CommonBot.Coroutines Namespace](../../../../../../namespaces/Styx/CommonBot/Coroutines.md)
