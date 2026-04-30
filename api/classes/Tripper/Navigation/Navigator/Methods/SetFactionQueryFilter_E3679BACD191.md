# Navigator.SetFactionQueryFilter Method

Sets faction-aware query filter based on player faction. Ported from HB 6.2.3 WowNavigator.SetFactionQueryFilter. Excludes the opposite faction's ability flag and applies a 50x cost penalty on the opposite faction's area type (prevents pathing through enemy-only areas).

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public void SetFactionQueryFilter(bool isHorde)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| isHorde | bool | True if the player is Horde, false if Alliance. |

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
