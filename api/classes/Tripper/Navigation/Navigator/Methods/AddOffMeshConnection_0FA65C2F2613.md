# Navigator.AddOffMeshConnection Method

Adds a custom offmesh connection at runtime.

## Namespace
[Tripper.Navigation](../../../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public void AddOffMeshConnection(uint mapId, Vector3 start, Vector3 end, float radius, byte flags, byte type, uint interactId)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| mapId | uint | Map ID. |
| start | Vector3 | Connection start position. |
| end | Vector3 | Connection end position. |
| radius | float | Connection radius. |
| flags | byte | Connection flags. |
| type | byte | Connection type (0=normal, 1=elevator, 2=portal). |
| interactId | uint | Object ID to interact with (for elevators/portals). |

## See Also
[Navigator Class](../../Navigator.md)
[Tripper.Navigation Namespace](../../../../../namespaces/Tripper/Navigation.md)
