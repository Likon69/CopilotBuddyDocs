# MeshNavigator.StuckHandler Property

HB 6.2.3 MeshNavigator.StuckHandler — Class469 instance. Lifecycle (OnSetAsCurrent/OnRemoveAsCurrent) is handled by the base class setter which guards on IsCurrent per HB NavigationProvider pattern. MeshNavigator uses _stuckHandler directly for Reset() calls. (Overrides NavigationProvider.StuckHandler.)

## Namespace
[Styx.Logic.Pathing](../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public override StuckHandler StuckHandler { get; set; }
```

## Property Value

Type: [StuckHandler](../../StuckHandler.md)
The stuck handler.

## See Also
[MeshNavigator Class](../../MeshNavigator.md)
[Styx.Logic.Pathing Namespace](../../../../../../namespaces/Styx/Logic/Pathing.md)
