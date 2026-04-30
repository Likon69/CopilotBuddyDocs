# CommonCoroutines.StopMoving Method

HB 6.2.3: Stop all movement and wait up to 4s for character to stop. Returns true if movement was stopped, false if already stationary.

## Namespace
[Styx.CommonBot.Coroutines](../../../../../../namespaces/Styx/CommonBot/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Task<bool> StopMoving(string reason)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| reason | string | The reason. |

## Return Value

Type: Task<bool>
The result of the operation.

## See Also
[CommonCoroutines Class](../../CommonCoroutines.md)
[Styx.CommonBot.Coroutines Namespace](../../../../../../namespaces/Styx/CommonBot/Coroutines.md)
