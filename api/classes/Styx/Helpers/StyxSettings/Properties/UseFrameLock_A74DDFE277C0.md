# StyxSettings.UseFrameLock Property

Whether to use the memory frame lock during bot ticks. When enabled (HB 5.4.8/6.2.3 default), the entire tick runs inside a hard AcquireFrame — all game reads are consistent within one frame.

## Namespace
[Styx.Helpers](../../../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool UseFrameLock { get; set; }
```

## Property Value

Type: bool
true if use frame lock; otherwise, false.

## See Also
[StyxSettings Class](../../StyxSettings.md)
[Styx.Helpers Namespace](../../../../../namespaces/Styx/Helpers.md)
