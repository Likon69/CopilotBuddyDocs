# Mount.MountUp Method

Mounts up with a custom can-mount check and destination (HB 4.3.4). Returns true if mount was attempted.

## Namespace
[Styx.Logic](../../../../../namespaces/Styx/Logic.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool MountUp(CanMountDelegate extra, LocationRetriever travelingTo)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| extra | [CanMountDelegate](../CanMountDelegate.md) | The extra. |
| travelingTo | [LocationRetriever](../../LocationRetriever.md) | The traveling to. |

## Return Value

Type: bool
true if the operation succeeds; otherwise, false.

## See Also
[Mount Class](../../Mount.md)
[Styx.Logic Namespace](../../../../../namespaces/Styx/Logic.md)
