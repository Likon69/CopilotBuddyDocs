# Flightor.MountHelper.Mounted Property

Check if currently on a flying mount. WotLK-specific: checks druid shapeshift field first because CMovementData.CanFly (0x800000) lags behind the shapeshift state by several ticks after form invocation. Using CanFly alone causes an infinite mount-spam loop for druids.

## Namespace
[Styx.Logic.Pathing](../../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static bool Mounted { get; }
```

## Property Value

Type: bool
true if mounted; otherwise, false.

## See Also
[Flightor.MountHelper Class](../../MountHelper.md)
[Styx.Logic.Pathing Namespace](../../../../../../../namespaces/Styx/Logic/Pathing.md)
