# Logging.LogMessageDelegate.BeginInvoke Method

Begins asynchronous invocation of the delegate.

## Namespace
[Styx.Helpers](../../../../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public virtual IAsyncResult BeginInvoke(ReadOnlyCollection<LogMessage> messages, AsyncCallback callback, object object)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| messages | ReadOnlyCollection<LogMessage> | The messages. |
| callback | AsyncCallback | The callback. |
| object | object | The object. |

## Return Value

Type: IAsyncResult
The result of the operation.

## See Also
[Logging.LogMessageDelegate Delegate](../../LogMessageDelegate.md)
[Styx.Helpers Namespace](../../../../../../namespaces/Styx/Helpers.md)
