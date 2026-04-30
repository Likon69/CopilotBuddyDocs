# WoWGameObject.GetWorldMatrix Method

World transform matrix. For transports (elevators, ships), reads the live matrix from game memory at BaseAddress + 0x1A8 (updated each frame by the client). For static objects, computes from position + rotation. Matches HB 3.3.5a's GetWorldMatrix().

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public Matrix GetWorldMatrix()
```

## Return Value

Type: [Matrix](../../../../../Tripper/Tools/Math/Matrix.md)
The result of the operation.

## See Also
[WoWGameObject Class](../../WoWGameObject.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
