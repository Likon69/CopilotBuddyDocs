# WaitTimer.WaitTimerFinishedHandler.BeginInvoke Method

Begins asynchronous invocation of the delegate.

## Namespace
[Styx.Helpers](../../../../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public virtual IAsyncResult BeginInvoke(object sender, WaitTimerEventArgs args, AsyncCallback callback, object object)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| sender | object | The sender. |
| args | [WaitTimerEventArgs](../../WaitTimerEventArgs.md) | The args. |
| callback | AsyncCallback | The callback. |
| object | object | The object. |

## Return Value

Type: IAsyncResult
The result of the operation.

## See Also
[WaitTimer.WaitTimerFinishedHandler Delegate](../../WaitTimerFinishedHandler.md)
[Styx.Helpers Namespace](../../../../../../namespaces/Styx/Helpers.md)
