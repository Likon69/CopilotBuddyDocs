# WoWUnit.IsPet Property

BUG-08 fix: Check GUID instead of expensive ObjectManager lookup. HB 4.3.4 checks both SummonedByGuid and CharmedByGuid.

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public bool IsPet { get; }
```

## Property Value

Type: bool
true if is pet; otherwise, false.

## See Also
[WoWUnit Class](../../WoWUnit.md)
[Styx.WoWInternals.WoWObjects Namespace](../../../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
