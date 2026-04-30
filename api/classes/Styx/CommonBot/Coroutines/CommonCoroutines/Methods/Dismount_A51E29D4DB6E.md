# CommonCoroutines.Dismount Method

HB 6.2.3: Dismount the character. If flying and descend=true, descends until grounded first.

## Namespace
[Styx.CommonBot.Coroutines](../../../../../../namespaces/Styx/CommonBot/Coroutines.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Task<bool> Dismount(string reason, bool descend)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| reason | string | The reason. |
| descend | bool | The descend. |

## Return Value

Type: Task<bool>
The result of the operation.

## See Also
[CommonCoroutines Class](../../CommonCoroutines.md)
[Styx.CommonBot.Coroutines Namespace](../../../../../../namespaces/Styx/CommonBot/Coroutines.md)
