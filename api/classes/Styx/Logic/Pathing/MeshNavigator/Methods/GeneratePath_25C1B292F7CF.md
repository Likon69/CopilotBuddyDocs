# MeshNavigator.GeneratePath Method

Generates a navmesh path from player position to destination. HB 6.2.3 MeshNavigator.GeneratePath. (Overrides NavigationProvider.GeneratePath().)

## Namespace
[Styx.Logic.Pathing](../../../../../../namespaces/Styx/Logic/Pathing.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public override WoWPoint[] GeneratePath(WoWPoint from, WoWPoint to)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| from | [WoWPoint](../../WoWPoint.md) | The from. |
| to | [WoWPoint](../../WoWPoint.md) | The to. |

## Return Value

Type: [WoWPoint](../../WoWPoint.md)[]
The result of the operation.

## See Also
[MeshNavigator Class](../../MeshNavigator.md)
[Styx.Logic.Pathing Namespace](../../../../../../namespaces/Styx/Logic/Pathing.md)
