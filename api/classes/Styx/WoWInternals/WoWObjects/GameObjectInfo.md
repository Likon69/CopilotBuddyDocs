# GameObjectInfo Class

Cached information about a game object.

## Inheritance Hierarchy
System.Object
  Styx.WoWInternals.WoWObjects.GameObjectInfo

## Namespace
[Styx.WoWInternals.WoWObjects](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class GameObjectInfo
```

The GameObjectInfo type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [BaseAddress](GameObjectInfo/Properties/BaseAddress_2BFF8240AA23.md) | Base address of the cache entry. |
| Public property | [Id](GameObjectInfo/Properties/Id_FA1CD2F30333.md) | Game object ID. |
| Public property | [InternalInfo](GameObjectInfo/Properties/InternalInfo_74F635FBE0B3.md) | Internal cache entry. |
| Public property | [IsCached](GameObjectInfo/Properties/IsCached_923975D3A77F.md) | Whether this game object is cached. |
| Public property | [QuestItems](GameObjectInfo/Properties/QuestItems_E8B3EB72CF71.md) | Quest items associated with this game object. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [FromId(uint)](GameObjectInfo/Methods/FromId_A79EA11C2EC6.md) | Creates a GameObjectInfo from an ID. |
| Public method | [GetGameObjectInfo](GameObjectInfo/Methods/GetGameObjectInfo_63F7AF5B6942.md) | Gets the game object cache entry with caching. |
| Public method | [GetQuestItems](GameObjectInfo/Methods/GetQuestItems_B092F31EF84D.md) | Gets the quest items for this game object. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.WoWInternals.WoWObjects Namespace](../../../../namespaces/Styx/WoWInternals/WoWObjects.md)
