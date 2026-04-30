# DungeonManager Class

Charge et gère les scripts de donjons. Scripts dynamiques depuis Dungeon Scripts\ + types compilés dans l'assembly.

## Namespace
[Bots.DungeonBuddy](../../../namespaces/Bots/DungeonBuddy.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public static class DungeonManager
```

The DungeonManager type exposes the following members.

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property Static member | [CurrentDungeon](DungeonManager/Properties/CurrentDungeon_CF5444387AAD.md) | Donjon actif |
| Public property Static member | [CurrentDungeonBehavior](DungeonManager/Properties/CurrentDungeonBehavior_55211F2BA55A.md) | Gets the current dungeon behavior. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method Static member | [Clear](DungeonManager/Methods/Clear_9B77E661351D.md) | Clears the current contents. |
| Public method Static member | [GetEncounterBehavior(int)](DungeonManager/Methods/GetEncounterBehavior_7566F401C7F9.md) | Obtient le behavior pour un boss spécifique |
| Public method Static member | [GetEntranceForDungeon(uint)](DungeonManager/Methods/GetEntranceForDungeon_EC98E76EED24.md) | Retourne la position d'entrée d'un donjon depuis son script, SANS activer ce script. Utilisé par SoloFarm pour naviguer vers l'entrée avant d'entrer dans l'instance. Évite d'appeler SetDungeonById (qui déclenche Attach/BossManager/Profile) hors instance. |
| Public method Static member | [GetObjectBehavior(int)](DungeonManager/Methods/GetObjectBehavior_BC1E5A925987.md) | Obtient le behavior pour un objet spécifique |
| Public method Static member | [LoadDungeonScripts](DungeonManager/Methods/LoadDungeonScripts_95052CC1B4EE.md) | Charge les scripts de donjon depuis Dungeon Scripts\ (compilation dynamique, pattern HB 4.3.4), plus les scripts compilés dans l'assembly. |
| Public method Static member | [ReloadDungeons](DungeonManager/Methods/ReloadDungeons_FA8EB6F85BD5.md) | Reload dungeon scripts at runtime (HB 4.3.4: DungeonManager.ReloadDungeons()). |
| Public method Static member | [SetDungeon(uint)](DungeonManager/Methods/SetDungeon_09358FF0F08C.md) | Active le script de donjon approprié. HB 4.3.4: utilise LfgManager.CurrentLfgDungeonId quand on est en groupe LFG, sinon GetLfgDungeonIdFromMapId pour faire la correspondance MapId → LFG DungeonId. |
| Public method Static member | [SetDungeonById(uint)](DungeonManager/Methods/SetDungeonById_7B4E9A70E4C5.md) | Active un script de donjon à partir de son ID. Ce flux est le même que HB 4.3.4 method_43. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy Namespace](../../../namespaces/Bots/DungeonBuddy.md)
