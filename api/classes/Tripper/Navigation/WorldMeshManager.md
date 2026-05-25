# WorldMeshManager Class

Provides world mesh management functionality.

## Inheritance Hierarchy
System.Object
  Tripper.Navigation.WorldMeshManager

## Namespace
[Tripper.Navigation](../../../namespaces/Tripper/Navigation.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public sealed class WorldMeshManager : IDisposable, IMeshManager
```

The WorldMeshManager type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [GarbageCollectTime](WorldMeshManager/Properties/GarbageCollectTime_36F7D42E866D.md) | Gets or sets the garbage collect time. |
| Public property | [IsLoaded](WorldMeshManager/Properties/IsLoaded_8D5BFF785FC3.md) | Gets a value indicating whether is loaded. |
| Public property | [Mesh](WorldMeshManager/Properties/Mesh_D46DC1AFAFAD.md) | Gets the mesh. |
| Public property | [MeshQuery](WorldMeshManager/Properties/MeshQuery_7915C43F5650.md) | Gets the mesh query. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event | [SubTileLoaded](WorldMeshManager/Events/SubTileLoaded_23DBD2FA82EA.md) | Occurs when sub tile is loaded. |
| Public event | [TileLoaded](WorldMeshManager/Events/TileLoaded_7027EAC411AC.md) | Occurs when tile is loaded. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Dispose](WorldMeshManager/Methods/Dispose_C13FD1B49A18.md) | Releases the resources used by the instance. |
| Public method | [FindPath(Vector3, Vector3)](WorldMeshManager/Methods/FindPath_C65B8D5D1446.md) | Finds the path. |
| Public method | [LoadTile(TileIdentifier)](WorldMeshManager/Methods/LoadTile_3A874FB312B2.md) | Loads the tile. |
| Public method | [UnloadAllTiles](WorldMeshManager/Methods/UnloadAllTiles_D404D267F8EA.md) | Executes the unload all tiles operation. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Tripper.Navigation Namespace](../../../namespaces/Tripper/Navigation.md)
