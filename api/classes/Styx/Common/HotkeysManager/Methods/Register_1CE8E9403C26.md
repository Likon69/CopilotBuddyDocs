# HotkeysManager.Register Method

Executes the register operation.

## Namespace
[Styx.Common](../../../../../namespaces/Styx/Common.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static Hotkey Register(string name, Keys key, ModifierKeys modifierKeys, Action<Hotkey> callback)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | string | The name. |
| key | Keys | The key. |
| modifierKeys | [ModifierKeys](../../ModifierKeys.md) | The modifier keys. |
| callback | Action<Hotkey> | The callback. |

## Return Value

Type: [Hotkey](../../Hotkey.md)
The result of the operation.

## See Also
[HotkeysManager Class](../../HotkeysManager.md)
[Styx.Common Namespace](../../../../../namespaces/Styx/Common.md)
