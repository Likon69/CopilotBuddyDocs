# Navigator.Extents Property

Search extents passed raw to dtNavMeshQuery in Detour space [horizontal, vertical, horizontal]. Navigation.cpp applies WoWToDetour on center only — extents go direct to Detour. Must match HB 6.2.3 WowNavigator.Extents = (3,20,3): ±3 horizontal, ±20 vertical.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public Vector3 Extents { get; set; }
```

## Property Value

Type: Vector3
The extents.

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
