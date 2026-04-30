# TimedRecordKeeper<T>.GetRecord Method

Gets the record.

## Namespace
[Styx.CommonBot](../../../../../namespaces/Styx/CommonBot.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool GetRecord(TimeSpan maxAge, out T oldValue, out TimeSpan elapsed)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| maxAge | TimeSpan | The max age. |
| oldValue | T | The old value. |
| elapsed | TimeSpan | The elapsed. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[TimedRecordKeeper<T> Class](../../TimedRecordKeeper_1.md)
[Styx.CommonBot Namespace](../../../../../namespaces/Styx/CommonBot.md)
