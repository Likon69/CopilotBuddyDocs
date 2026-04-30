# CommonCoroutines.WaitForLuaEvent Method

HB 6.2.3: Wait for a Lua event with optional alternate condition. int overload — delegates to TimeSpan overload.

## Namespace
[Styx.CommonBot.Coroutines](../../../../../../namespaces/Styx/CommonBot/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Task<bool> WaitForLuaEvent(string eventName, int maxWaitMs, Func<bool> alternateCondition, Action action)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| eventName | string | The event name. |
| maxWaitMs | int | The max wait ms. |
| alternateCondition | Func<bool> | The alternate condition. |
| action | Action | The action. |

## Return Value

Type: Task<bool>
The result of the operation.

## See Also
[CommonCoroutines Class](../../CommonCoroutines.md)
[Styx.CommonBot.Coroutines Namespace](../../../../../../namespaces/Styx/CommonBot/Coroutines.md)
