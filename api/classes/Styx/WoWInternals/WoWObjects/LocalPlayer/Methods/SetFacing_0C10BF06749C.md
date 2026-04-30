# LocalPlayer.SetFacing Method

Sets the player's facing to a specific angle (in radians). Uses ClickToMove with Face type like HB 4.3.4 for proper server sync and animation. Adding epsilon (1E-06f) like HB 4.3.4 to prevent precision issues.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public void SetFacing(float facing)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| facing | float | The facing. |

## See Also
[LocalPlayer Class](../../LocalPlayer.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
