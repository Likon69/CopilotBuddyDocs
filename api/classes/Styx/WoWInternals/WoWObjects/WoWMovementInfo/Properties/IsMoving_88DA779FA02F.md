# WoWMovementInfo.IsMoving Property

Whether the unit is currently moving. Uses movement flags like HB 4.3.4 instead of TimeMoved for accurate detection. This prevents false positives during facing/turning operations.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool IsMoving { get; }
```

## Property Value

Type: bool
true if is moving; otherwise, false.

## See Also
[WoWMovementInfo Class](../../WoWMovementInfo.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
