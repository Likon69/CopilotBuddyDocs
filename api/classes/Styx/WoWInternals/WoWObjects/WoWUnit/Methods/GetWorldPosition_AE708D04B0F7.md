# WoWUnit.GetWorldPosition Method

Returns the world-space position of this unit. When on a transport (elevator, ship), transforms the transport-local position by the transport's world matrix (read from GO BaseAddress + 0x1A8). Matches HB 3.3.5a's GetWorldPosition().

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public WoWPoint GetWorldPosition()
```

## Return Value

Type: [WoWPoint](../../../../Logic/Pathing/WoWPoint.md)
The result of the operation.

## See Also
[WoWUnit Class](../../WoWUnit.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
