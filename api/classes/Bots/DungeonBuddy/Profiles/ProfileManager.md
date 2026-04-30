# ProfileManager Class

Provides access to DungeonBuddy profile definitions.

## Namespace
[Bots.DungeonBuddy.Profiles](../../../../namespaces/Bots/DungeonBuddy/Profiles.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class ProfileManager
```

The ProfileManager type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [CurrentProfile](ProfileManager/Properties/CurrentProfile_CF74610B34AB.md) | Gets the current profile. |

## Events

| | Name | Description |
| --- | --- | --- |
| Public event Static member | [OnProfileSet](ProfileManager/Events/OnProfileSet_182137F89110.md) | Occurs when profile set. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [GetLfgDungeonIdFromMapId(uint)](ProfileManager/Methods/GetLfgDungeonIdFromMapId_3F2C81D030E6.md) | HB 4.3.4: GetLfgDungeonIdFromMapId Recherche l'ID du donjon LFG correspondant à un MapId et une difficulté. Utilise LfgDungeons.dbc pour la correspondance. |
| Public method Static member | [IsNpcInPullBlackspot(WoWUnit)](ProfileManager/Methods/IsNpcInPullBlackspot_FC2294354B30.md) | Determines whether is npc in pull blackspot. |
| Public method Static member | [Load(Profile)](ProfileManager/Methods/Load_E594A3C6E0FF.md) | Loads the resource. |
| Public method Static member | [LoadFromPath(string)](ProfileManager/Methods/LoadFromPath_31E20035DE33.md) | Charge un profil directement depuis un chemin XML (utilisé par FormConfig). |
| Public method Static member | [LoadProfileForDungeon(uint)](ProfileManager/Methods/LoadProfileForDungeon_3F409D3D2858.md) | Scanne Default Profiles\DungeonBuddy\ pour trouver le profil XML correspondant au dungeonId. |
| Public method Static member | [UnloadProfile](ProfileManager/Methods/UnloadProfile_EFC9B4EF6469.md) | Unloads the resource. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy.Profiles Namespace](../../../../namespaces/Bots/DungeonBuddy/Profiles.md)
