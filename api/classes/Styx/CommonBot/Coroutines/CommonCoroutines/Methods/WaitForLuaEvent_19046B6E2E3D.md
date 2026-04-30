# CommonCoroutines.WaitForLuaEvent Method

HB 6.2.3: Wait for a Lua event with optional alternate condition. Attaches event, optionally fires action, waits for event or condition, then detaches event.

## Namespace
[Styx.CommonBot.Coroutines](../../../../../../namespaces/Styx/CommonBot/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Task<bool> WaitForLuaEvent(string eventName, TimeSpan maxWaitTimeout, Func<bool> alternateCondition, Action action)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| eventName | string | The event name. |
| maxWaitTimeout | TimeSpan | The max wait timeout. |
| alternateCondition | Func<bool> | The alternate condition. |
| action | Action | The action. |

## Return Value

Type: Task<bool>
The result of the operation.

## See Also
[CommonCoroutines Class](../../CommonCoroutines.md)
[Styx.CommonBot.Coroutines Namespace](../../../../../../namespaces/Styx/CommonBot/Coroutines.md)
